# Que es ML?

## En que Consiste?

Consiste en una disciplina que, a través del uso de datos y algoritmos matemáticos, permiten a los computadores aprender ayudando a predecir, clasificar, ordenar, tomar decisiones y, en general, **extraer conocimientos de los datos sin necesidad de definir explícitamente las reglas para realizar esas tareas.**


![[Pasted image 20240812201815.png]]



| Programacion Tradicional                                             | Machine Learning                                                          |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Es un proceso manual.                                                | Los datos de entrada y salida alimentan un programa para crear un modelo. |
| El programador formula manualmente o codifica reglas.                | Los algoritmos formulan automáticamente las reglas a partir de los datos. |
| Se usan datos de entrada, se procesan y se obtienen datos de salida. | No sustituye la programación tradicional; la complementa y potencia.      |

## Aplicaciones
Algunas de las aplicaciones que se pueden llegar a realizar son **Marketing, Venta Cruzada, predicciones.**

- **Segmentar clientes** en función de sus compras, para poder diseñar una estrategia de marketing diferente para cada segmento.
- **Predecir ingresos** de la empresa para el año siguiente, en función de muchas métricas de rendimiento.
- **Recomendar un producto** en el que un cliente pueda estar interesado, en función de sus compras anteriores.
- **Analizar imágenes** de productos en una cadena de producción para clasificarlas de manera automática.
- **Detectar tumores** en escáneres cerebrales.
- **Crear un chatbot** o asistente personal.

## Tipos de Sistemas

### Aprendizaje Supervisado
Se entrena al modelo con datos etiquetados.

El aprendizaje supervisado generalmente comienza con un conjunto establecido de datos y una cierta comprensión de cómo se clasifican esos datos.

El aprendizaje supervisado pretende encontrar patrones en los datos que puedan aplicarse a un proceso analítico. **Estos datos tienen características etiquetadas que definen el significado de los datos.**	

Cuando la etiqueta es continua, **es una regresión; cuando los datos provienen de un conjunto finito de valores o clases, es lo que se conoce como clasificación.**

![[Pasted image 20240812203057.png]]

### Aprendizaje No Supervisado
Se entrena al modelo con datos no etiquetados.

El aprendizaje no supervisado es más adecuado **cuando el problema requiere una gran cantidad de datos que no están etiquetados.**

Los algoritmos de aprendizaje **no supervisados más utilizados segmentan los datos en grupos de ejemplos (clusters) o grupos de características.**

![[Pasted image 20240812203148.png]]


### Aprendizaje por Refuerzo
Se entrena al modelo con un sistema de recompensas.

El aprendizaje por refuerzo es un modelo de aprendizaje conductual. **El sistema no está entrenado con el conjunto de datos de muestra.** Más bien, el sistema aprende **a través de prueba y error.** Por lo tanto, una secuencia de decisiones exitosas dará como resultado que el proceso sea "reforzado”.

Una de las aplicaciones más comunes del aprendizaje por refuerzo es en robótica o juegos.

![[Pasted image 20240812203221.png]]



# Roles en Ciencia de Datos y CRISP-DM
## Ciencias de Datos
Las ciencias de datos son un campo interdisciplinario que utiliza métodos, procesos, algoritmos y sistemas científicos para extraer conocimiento y **pero también para predecir eventos futuros.**

El objetivo es descubrir información práctica, verídica, relevante oculta en los datos de una organización y esta información se **puede utilizar como guía para la toma de decisiones y la planificación estratégica de los equipos y empresas.**

**La Ciencia de Datos es una combinación de:**
- Matemáticas y estadística
- Programación especializada
- Análisis avanzados
- Inteligencia artificial (IA)
- Machine learning 
- Experiencia en distintas materias.

### Roles en Ciencias de Datos
**Ingenieros de Datos:** Trabajan con big data y tecnologías en la nube, saben cómo construir canalizaciones de datos, diseñar bases de datos y extraer datos de ellas.

**Analistas de Datos**: Son personas que puedan tomar esos datos, limpiarlos, analizarlos, ejecutar experimentos con ellos y comunicar los resultados.

**Ingenieros de Machine Learning:** desarrolladores de software que están familiarizados con varias bibliotecas de ciencia de datos y saben cómo implementar modelos matemáticos a los datos.

**Especialista en visualización:** centrado en el diseño para crear gráficos e informes altamente refinados.

**Científico de Datos**: Quien es un experto en el dominio del problema.


| Ciencia de Datos                                                                                              | Minería de Datos                                                                                                     |
| ------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Es un área                                                                                                    | Es una Técnica                                                                                                       |
| Se trata de la recopilación, el procesamiento, el análisis y la utilización de datos en diversas operaciones. | Se trata de extraer la información vital y valiosa de los datos.                                                     |
| El objetivo es crear productos de datos dominantes para una empresa.                                          | El objetivo es hacer que los datos sean más vitales y utilizables, es decir, extrayendo solo información importante. |
| Se utiliza principalmente con fines científicos.                                                              | Se utiliza principalmente para fines comerciales.                                                                    |

## Origen del CRISP-DM
Fue inspirado por el modelo KDD (Knowledge Discovery in Databases) y fue desarrollado por un consorcio de empresas y organizaciones en 1996.
### Minería de Datos 
La minería de datos es un proceso que toma grandes volúmenes de datos y los analiza para descubrir patrones o información útil que antes no se conocía. Este proceso incluye varios pasos, desde recopilar los datos hasta mostrarlos de manera que sean fáciles de entender.

La tarea principal en la minería de datos es encontrar automáticamente (o con poca intervención humana) cosas interesantes en los datos, como:
- **Agrupación de datos similares** (como juntar personas con intereses comunes).
- **Detección de datos inusuales** (como identificar transacciones sospechosas en un banco).
- **Descubrimiento de relaciones entre datos** (como saber que la gente que compra pan también suele comprar leche).

Estos patrones ayudan a resumir la información y se pueden usar para hacer predicciones o mejorar decisiones en otros análisis.
#### KDD
KDD es el proceso completo que toma datos en bruto y los convierte en conocimiento útil a través de varias etapas. La minería de datos es una parte central de este proceso, pero todo el ciclo de KDD es necesario para extraer valor real de los datos.

- **Selección**: Primero, se eligen los datos que son importantes y que se van a analizar de una base de datos más grande.
- **Preprocesamiento**: Luego, esos datos seleccionados se limpian y preparan para asegurarse de que sean correctos y útiles para el análisis.
- **Transformación**: Después, los datos se transforman o se reorganizan de manera que sea más fácil analizarlos. Este paso hace que los datos estén listos para la minería.
- **Minería de datos**: Aquí es donde realmente se aplican técnicas para descubrir patrones interesantes o información importante dentro de los datos. Este paso es clave para extraer lo más valioso de la información.
- **Interpretación y evaluación**: Finalmente, los resultados obtenidos se interpretan y se evalúan para asegurarse de que sean útiles y correctos. Esto es lo que te ayuda a obtener **insights** (ideas o conocimientos) que puedes usar para tomar decisiones o hacer predicciones.

#### SEMMA
La metodología **SEMMA** es un enfoque utilizado en la minería de datos que consta de cinco fases:
1. **Sample (Muestra)**: Esta fase consiste en seleccionar una muestra representativa de los datos disponibles para trabajar con ella. Es como tomar una parte pequeña de toda la información para empezar a analizarla.
2. **Explore (Explora)**: Aquí, se examinan los datos para encontrar patrones o relaciones interesantes. Se utilizan herramientas y técnicas para ver cómo están distribuidos los datos y si hay algo que llame la atención.
3. **Modify (Modifica)**: En esta fase, los datos se ajustan o transforman según sea necesario. Esto puede incluir limpiar los datos, eliminar lo que no sirve, o crear nuevas variables que faciliten el análisis.
4. **Model (Modela)**: Luego, se construyen modelos matemáticos o estadísticos para predecir o explicar algo a partir de los datos. Es como crear una fórmula que te ayuda a hacer predicciones basadas en la información que tienes.
5. **Assess (Evalúa)**: Finalmente, se evalúan los resultados del modelo para ver si funciona bien y si las predicciones o conclusiones que se sacan son correctas. Es como verificar si lo que hiciste tiene sentido y es útil.

## CRISP-DM
CRISP-DM (Cross-Industry Standard Process for Data Mining) es un modelo de proceso de minería de datos que describe en detalle las etapas de un proyecto de minería de datos.

**Como metodología**, incluye descripciones de las fases normales de un proyecto, las tareas necesarias en cada fase y una explicación de las relaciones entre las tareas.

El modelo contiene seis fases con flechas que indican las dependencias más importantes y frecuentes entre fases. **La secuencia de las fases no es estricta**. De hecho, la mayoría de los proyectos avanzan y retroceden entre fases si es necesario.

![[Pasted image 20240812205150.png]] 

### Business Understanding
**Comprensión del problema o negocio:** Esta es la etapa más importante, ya que, si no se comprende correctamente el negocio, o problema, no servirá pasar a las siguientes etapas.
#### Actividades
**Identificación del problema:** Aborda el entendimiento y delimitación de la problemática, así como la identificación de los requisitos, restricciones, supuestos y beneficios del proyecto.
**Determinación de objetivos:** Establece los posibles resultados a obtener al proponer la solución. (El cliente tiene que ser claro)
**Evaluación de la situación actual:** Describe el estado actual antes de ser implementada la solución propuesta, con el fin de tener un objeto de comparación que permita medir el grado de éxito del proyecto. (Se saca lo que se cobra).

### Data Understanding
**Comprensión de los datos:** Comprende la recolección inicial de datos, con el objetivo de establecer un primer acercamiento con el problema, conociendo a los datos, identificando su calidad y estableciendo las primeras relaciones que permitan definir correlaciones entre variables.


#### Actividades
**Recolección de datos:** Consiste en obtener los datos a utilizar en el proyecto a partir de algunas fuentes de datos, e identificando las técnicas utilizadas para su recolección.
**Exploración de datos:** Se basa en aplicar pruebas estadísticas que permitan conocer las propiedades de los datos.


### Data Preparation
**Preparación de datos:** Esta es la etapa que demanda más tiempo en el proyecto, aquí se seleccionan los datos que serán transformados de acuerdo con los resultados de la etapa anterior a fin de ser utilizados en la etapa de modelado. 

**Dos grandes etapas**: Limpieza de datos y transformación de datos.

**Scaling**: el escalamiento se hace cuando uno tiene variables de magnitudes muy distintas, y el algoritmo tiene todas las variables iguales sin preferencia, entonce si hay dos variables una muy grande que otra el modelo se come una variable, se hace después de la estadística descriptiva.
> En resumen hace que todas las variables midan lo mismo y ninguna variable se coma a otra.

En esta fase se realiza estadística descriptiva, se eliminan valores nulos, se eliminan duplicados, se eliminan variables que no aportan al modelo, se transforman variables categóricas a numéricas, se normalizan las variables, se eliminan outliers, se eliminan variables correlacionadas, se eliminan variables que no aportan al modelo.

Hay veces que uno tiene supuestos que no son correctos, por ejemplo, uno puede tener una variable que es la edad y uno puede tener un valor de 0, entonces uno tiene que hacer un análisis de los datos para ver si es correcto o no.


#### Actividades
**Limpieza de datos:** Para este fin se aplican diferentes técnicas, por ejemplo, normalización de datos, tratamiento de valores nulos, tratamiento de duplicados e imputación de datos.
**Transformación de datos:** Aquí se cambia la estructura o el formato de ciertos datos sin alterar su significado, a fin de poder ser utilizados en la etapa de modelado.

### Modeling
**Modelado:** En esta etapa se seleccionan las técnicas de modelado y se aplican a los datos preparados en la etapa anterior. 

#### Actividades
**Selección de técnica de modelado:** Se elige la técnica apropiada de acuerdo con el problema a resolver, los datos disponibles, las herramientas de minería de datos disponibles.

**Selección de datos de prueba:** En algunos modelos se necesita segmentar la muestra en datos de entrenamiento y de prueba.

**Obtención del modelo:** Aquí se genera el mejor modelo mediante un proceso iterativo con los datos de prueba y de entrenamiento.

### Evaluation
**Evaluación:** En esta etapa se determina la calidad del modelo teniendo en cuenta el análisis de determinadas métricas y criterios estadísticos del mismo, comparando los resultados que se van obteniendo con resultados previos. 


### Deployment
**Despliegue:** Aquí el modelo ya ha sido construido y evaluado. Esta etapa lleva a producción el modelo desarrollado, mediante acciones específicas, el conocimiento adquirido mediante las etapas previas, pudiendo ser aplicado a diversos y nuevos conjuntos de datos o también dentro de un proceso del negocio. 

# Algebra Lineal
El álgebra lineal es una rama de las matemáticas utilizada en ciencia e ingeniería, centrada en el **estudio de vectores, matrices, espacios vectoriales y sus transformaciones lineales.** Aunque "lineal" se refiere a la línea en términos generales, en matemáticas tiene un significado más amplio, relacionado con la generalización de propiedades de la línea recta. Los vectores, conocidos comúnmente como "vectores geométricos", son objetos que pueden sumarse y multiplicarse por escalares, generando otros objetos del mismo tipo.


## En Machine Learning
Dentro de Machine Learning se manejan cantidades enormes de datos y es más fácil su manipulación convirtiéndolos en matrices.

El álgebra lineal hace que las operaciones matriciales sean rápidas y fáciles, especialmente cuando se utiliza GPU (graphics processing unit). De hecho, las GPU se crearon pensando en las operaciones vectoriales y matriciales.

> Pero no solamente los datos se pueden representar en matrices sino también las imágenes pueden representarse como matrices de píxeles, los videojuegos generan atractivas experiencias de juego utilizando enormes matrices en constante evolución. 
> 
> En lugar de procesar los píxeles uno a uno, las GPU manipulan matrices enteras de píxeles en paralelo, y para realizar todo esto se necesita aplicar álgebra lineal.


## Conjunto de datos
En  Machine Learning  los conjuntos de datos que se manejan suelen convertirse en forma de vectores o matrices, y las salidas también son **escalares, vectores, matrices o tensores.**

### Escalares
Son un único número o valor, a diferencia de la mayoría de los otros elementos del álgebra lineal que son conjuntos de valores como los vectores y matrices.
> Generalmente, por convención a los escalares los escribimos en letra cursiva minúscula o usando el alfabeto griego.

#### Caracteristicas
Los principales conjuntos de **escalares** son:

**Números Naturales (ℕ):** los números que se utilizan para contar los elementos de cualquier conjunto. (1, 2, 3, 4, …)

**Números Enteros (ℤ):** el conjunto de los números enteros está dado por el conjunto de los naturales, sus negativos y el cero. (…, -2, -1, 0, 1, 2, …)

**Números Reales (ℝ):** el conjunto de los reales incluye tanto a los racionales como a los irracionales.


```python
a = 2
b = 4.8
c = 7.435

print(a) # 2
print(b) # 4.8
print(c) # 7.435

print(a + b) # 6.8
print(b - c) # -2.635
print(b * a)  # 9.6
print(c / b) # 1.54
print(c // b)  # 1.0
```

### Vectores
Son una matriz de números, ya sea en una fila o en una columna, y se identifican con un solo índice, si existen palabras o booleanos que se deben encodear en vectores.


Un vector de ”n” componentes se define como un conjunto ordenado de ”n” números escrito de forma horizontal si es un “vector fila”.

$$
\mathbf{V} = (x_1, x_2, \ldots, x_n)
$$
El vector de **columna se ve así**:

$$
\mathbf{V} = \begin{pmatrix}
x_1 \\
x_2 \\
\vdots \\
x_n
\end{pmatrix}

$$


A los vectores se le denota por una letra minúscula en **negrita**.

```python
import numpy as np

v = np.array([1, 2, 3, 4, 5])
print(v) # [1 2 3 4 5]

```


### Matriz.
Una matriz es un arreglo bi-dimensional de números. Cada elemento de la misma está identificado por dos índices, en lugar de uno como en los vectores. Usualmente, a una matriz la denotamos por una letra mayúscula en negrita.

$$
\mathbf{A} = \begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1j} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2j} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots & \ddots & \vdots \\
a_{i1} & a_{i2} & \cdots & a_{ij} & \cdots & a_{in} \\
\vdots & \vdots & \ddots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mj} & \cdots & a_{mn}
\end{pmatrix}
$$


```python
import numpy as np

A = np.Array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
print(A) # [[1 2 3]
          #  [4 5 6]
          #  [7 8 9]]
```



### Tensores
Se puede tener cualquier número de dimensiones en un tensor, aunque se hace más caro computacionalmente para manejar (Es una matriz de matrices).

existen diversos casos en los cuales se precisan más de dos ejes para almacenar valores. 
En el caso general, **una matriz con un número regular de ejes se lo conoce como tensor.** 
**Por ejemplo, cuando almacenamos los valores de los píxeles de una imagen a color necesitamos una matriz con tres ejes (uno para cada canal de color: R, G y B).**

![[Pasted image 20240814185349.png]]

```python
import matplotlib.pyplot as plt

np.random.seed(123) # Semilla con valores aleatorios
A = np.random.randint(256, size=(10,10,10)) # 256 indica que se crean valores entre 0 y 255

plt.imshow(A)
```

![[Pasted image 20240814185331.png]]


**Dato**: cuando habla de hiper se refiere a la forma de la matriz.



## Operaciones

### Vectores

#### Adición.
Esto es cuando se suman dos vectores, se suman cada componente del vector uno con el vector dos.

```python
import numpy as np

rango_1 = np.arange(10)
rango_2 = rango_1 * 2

suma = rango_1 + rango_2

```

Representación gráfica del concepto de la propiedad conmutativa de la suma de vectores en álgebra lineal.

La imagen muestra una representación gráfica del concepto de la propiedad conmutativa de la suma de vectores en álgebra lineal. 

En la imagen, se tienen dos vectores **rr y ss**, y se ilustra que sumar **rr a ss** es lo mismo que sumar **ss a rr,** es decir, **r+s=s+rr+s=s+r.**

![[Pasted image 20240814190812.png]]


#### Sustracción de vectores
Esto es cuando se resta un vector de otro vector, se resta cada componente del vector de otro.

```python
import numpy as np

a = np.random.random_sample(5) # Genera un vector de 5 elementos aleatorios
b = np.ones(5) # Devuelve una lista de 5 "1"

resta = a - b
```

![[Pasted image 20240814191333.png]]
La imagen ilustra la propiedad de que restar un vector ss de otro **vector rr** es equivalente a sumar **rr** con el vector opuesto de **ss, −s−s.** Esto se visualiza mediante la construcción geométrica que muestra la suma de **rr y −s−s.**


#### Multiplicar escalar por vectores
Esto es cuando se multiplica un número por un vector, se multiplica cada componente del vector por ese número.

```python
import numpy as np

r = np.array([3,2]) # Vector
e = 2 # Escalar


mul = e * r # Multiplicación escalar por vector
print(mul) # [6 4]
```

![[Pasted image 20240814191924.png]]


### Matriz
#### Multiplicar escalar con Matriz
Cuando un Escalar es multiplicado con una Matriz, esta se realiza con todos los números que están en la Matriz.

```python
import numpy as np

m = np.array([[4, 1, 7], [5, 9, 12]]) # Matriz
e = 3
mul = e * m
print(mul) # [[12  3 21]
           #  [15 27 36]]
```

$$
3 \begin{pmatrix} 4 & 1 & 7 \\ 5 & 9 & 12 \end{pmatrix} = \begin{pmatrix} 3 \times 4 & 3 \times 1 & 3 \times 7 \\ 3 \times 5 & 3 \times 9 & 3 \times 12 \end{pmatrix} = \begin{pmatrix} 12 & 3 & 21 \\ 15 & 27 & 36 \end{pmatrix} \
$$

#### Producto punto o dot (producto cruz)
El producto punto es la suma de los productos de los elementos correspondientes de dos vectores.

```python
import numpy as np

ma = np.array([1, 2], [3,4])
mb = np.array([5, 6], [7, 8])

mul = np.dot(ma, mb)
print(mul) # [[19 22]
           #  [43 50]]
```

$$
\begin{pmatrix} a & b \end{pmatrix} \cdot \begin{pmatrix} x \\ y \end{pmatrix} = [ax + by]
$$
$$
\begin{pmatrix} a & b \\ c & d \end{pmatrix} \cdot \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} ax + by \\ cx + dy \end{pmatrix}
$$
$$
\begin{pmatrix} a & b \\ c & d \end{pmatrix} \cdot \begin{pmatrix} w & x \\ y & z \end{pmatrix} = \begin{pmatrix} aw + by & ax + bz \\ cw + dy & cx + dz \end{pmatrix}
$$

#### Producto Hadamard (punto)
El producto de **Hadamard** es el producto de dos matrices del mismo tamaño, donde cada elemento de la matriz resultante es el producto de los elementos correspondientes de las matrices originales.

```python
import numpy as np

a = np.array([[1, 2], [3, 4]])
b = np.array([[5, 6], [7, 8]])

mul = np.multiply(a, b)

print(mul) # [[ 5 12]
           #  [21 32]]
```

$$
\begin{pmatrix} 3 & 5 & 7 \\ 4 & 9 & 8 \end{pmatrix} \circ \begin{pmatrix} 1 & 6 & 3 \\ 0 & 2 & 9 \end{pmatrix} = \begin{pmatrix} 3 \times 1 & 5 \times 6 & 7 \times 3 \\ 4 \times 0 & 9 \times 2 & 8 \times 9 \end{pmatrix} \
$$

**Dato**: A las maquinas les paso un vector que puede ser `1xn` y el resultado de clasificación es `1x1`


#### Matriz de Identidad
Una matriz identidad, representado por I, tiene toda la diagonal principal definida por 1, y los demás valores rellenadas con 0.

Una matriz identidad es siempre una matriz cuadrada.

```python
import numpy as np

m_identidad = np.identity(5)
array([[1., 0., 0., 0., 0.],
       [0., 1., 0., 0., 0.],
       [0., 0., 1., 0., 0.],
       [0., 0., 0., 1., 0.],
       [0., 0., 0., 0., 1.]])
```

$$
\begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}_{2 \times 2} \quad \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}_{3 \times 3} \
$$
#### Matriz inversa
La matriz inversa, es aquella que al multiplicarse por sí misma, es igual a la matriz identidad y puede expresarse como
$$
AA^{-1} = A^{-1}A = I
$$
Estas matrices deben ser cuadradas y no todas las matrices tienen inversa.

**Dato**: en las matrices inversas es importante ya que podemos encontrar variables **x** y **z** que son incógnitas que podemos usar para el modelo.

```python
import numpy as np

A = np.array(([1,3,3], [1,4,3], [1,3,4]))
A_inv = np.linalg.inv(A)

print(A_inv) # [[ 7. -3. -3.]
             #  [-1.  1.  0.]
             #  [-1.  0.  1.]]
```

$$
\begin{pmatrix} a & b \\ c & d \end{pmatrix}^{-1} = \frac{1}{ad - bc} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix} \
$$
#### Traspuesta de una matriz
Una transpuesta de una matriz, es una nueva matriz donde prácticamente las filas son las columnas de la matriz original.

```python
import numpy as np
A = np.array([[1, 2], [3, 4], [5, 6, 7]])
A_t = A.T
print(A_t) # [[1 3 5]
           #  [2 4 6]]
```

$$
\begin{pmatrix} 3 & 3 \\ 5 & -3 \\ 1 & 0 \\ 0 & -2 \\ 5 & -2 \end{pmatrix}^{T} = \begin{pmatrix} 3 & 5 & 1 & 0 & 5 \\ 3 & -3 & 0 & -2 & -2 \end{pmatrix} \
$$

## Eigenvalores y Eigenvectores

Los **eigenvalores** y **eigenvectores** son conceptos clave en álgebra lineal que se utilizan en muchas áreas de las matemáticas y la ciencia, como la física, la informática, y la economía.

1. **Eigenvectores**: Son vectores especiales que, cuando se multiplican por una matriz, no cambian de dirección. Solo pueden alargarse o acortarse, pero siempre apuntan en la misma dirección.
2. **Eigenvalores**: Son los números que indican cuánto se alarga o se acorta un eigenvector cuando se multiplica por la matriz. 

### Propiedades claves
- **Vectores inmutables**: Los eigenvectores solo existen para matrices cuadradas (matrices que tienen el mismo número de filas y columnas) y no todas las matrices tienen eigenvectores. Si una matriz cuadrada tiene eigenvectores, tendrá tantos eigenvectores como el número de filas o columnas (por ejemplo, una matriz 3x3 tendrá 3 eigenvectores).
    
- **Multiplicación**: Si escalas (haces más grande o más pequeño) un eigenvector antes de multiplicarlo por la matriz, el resultado sigue siendo un múltiplo del mismo eigenvector. Es decir, cambiar la longitud del eigenvector no afecta su dirección, solo la cantidad por la que se escala.
    
- **Perpendicularidad**: En muchos casos, los eigenvectores de una matriz son perpendiculares (ortogonales) entre sí, lo que significa que forman ángulos rectos entre ellos.
$$
\begin{pmatrix} 2 & 3 \\ 2 & 1 \end{pmatrix} \times \begin{pmatrix} 3 \\ 2 \end{pmatrix} = \begin{pmatrix} 12 \\ 8 \end{pmatrix} = 4 \times \begin{pmatrix} 3 \\ 2 \end{pmatrix}
$$

**Dato**: Esos vectores que son propiedades en el significado fisico que cualquier matriz de cualquier dimension es el espacio y aca buscamos 3 vectores especiales, tencnica que veremos a fin de semestre es el PCA, en conclusion son variables que entregan datos en un cierto espacio.


### Neutralización
Dada la propiedad de que **multiplicar un eigenvector solo cambia su longitud pero no su naturaleza de eigenvector**, es frecuente **escalarlos de tal forma que su longitud sea 1**.

A estos eigenvectors se les llama **eigenvectors normalizados.**

**Dato**: Escalar los datos sirven para que las variables mas grandes no se coman las mas pequeñas.

$$
\text{X}_{\text{scaled}} = \frac{\text{X} - \text{X}_{\text{min}}}{\text{X}_{\text{max}} - \text{X}_{\text{min}}}

$$
#### Ejemplo de Estandarización de un Eigenvector

Supongamos que tienes un **eigenvector** 
$$ v=(32)\mathbf{v} = \begin{pmatrix} 3 \\ 2 \end{pmatrix}$$

**Paso 1**: Calcular la longitud del eigenvector

La longitud de **v** se calcula usando la fórmula de la raíz cuadrada de la suma de los cuadrados de sus componentes:
$$
\text{Longitud} = \sqrt{3^2 + 2^2} = \sqrt{9 + 4} = \sqrt{13}
$$


**Paso 2**: Estandarizar el eigenvector
Para hacer que el eigenvector tenga una longitud de 1 (lo que se llama estandarizar), divides cada componente del vector original por su longitud:

$$
\mathbf{v}_{\text{estandarizado}} = \begin{pmatrix} \frac{3}{\sqrt{13}} \\ \frac{2}{\sqrt{13}} \end{pmatrix}
$$

##### Interpretación
El eigenvector estandarizado tiene la **misma dirección que el eigenvector original**, pero ahora **su longitud es 1.** Esto es útil porque facilita las comparaciones entre eigenvectores y es una práctica común en muchas aplicaciones matemáticas y científicas.

En resumen, l**a estandarización hace que todos los eigenvectores tengan la misma "longitud" sin cambiar su dirección**


### Eigenvalues
Cuando se multiplica una matriz por alguno de sus eigenvectors se obtiene un múltiplo del vector original, es decir, el resultado es ese mismo vector multiplicado por un número. 

Al valor por el que se multiplica el **eigenvector** resultante se le conoce como **eigenvalue**. 
A todo **eigenvector** le corresponde un **eigenvalue** y **viceversa**.

$$
\begin{pmatrix} 2 & 3 \\ 2 & 1 \end{pmatrix} \times \begin{pmatrix} 3 \\ 2 \end{pmatrix} = \begin{pmatrix} 12 \\ 8 \end{pmatrix} = 4 \times \begin{pmatrix} 3 \\ 2 \end{pmatrix}

$$

**4**: eigenvalue
**2  3**: eigenvector


# Estadística Descriptiva
Refiere al análisis, el resumen y la presentación de los resultados relacionados con un conjunto de datos derivados de una muestra o de toda la población. 

El **objetivo** de la estadística descriptiva es describir los datos observados de forma sintética y significativa para poder analizarlos mejor. Es recoger observaciones sobre sujetos con una determinada propiedad y traducir estas observaciones en números que proporcionen información sobre dicha propiedad.

Las estadísticas descriptivas ofrecen un resumen conciso de los datos. Puedes resumir los datos en forma numérica o gráfica. 

A diferencia de **estadística inferencial** utiliza una muestra aleatoria de datos de una población para describirla y hacer inferencias (deducción) sobre ella. Las estadísticas inferenciales son pertinentes cuando es difícil o imposible examinar a todos los miembros de una población entera. 

La estadística descriptiva comprende tres categorías principales: **distribución de frecuencias, medidas de tendencia central y medidas de variabilidad.**


**Dato**: estadistica descriptiva sacarle al foto a los datos, y la inferencial la cual se puede sacar con un grupo de datos, las medidas de variabilidad son importantes.

**Dato acerca la media y mediana**: la media se puede contrastar con la desviación estandar ya que si es muy grande es pq hay valores muy grandes y otros muy pequeños y cuando es muy pequeña es porque si hay una igualdad en los datos.
## Estructura de datos
Los datos provienen de muchas fuentes: mediciones de sensores, eventos, texto, imágenes y videos.

Gran parte de estos datos no están estructurados: las imágenes son una colección de píxeles, y cada píxel contiene **información de color RGB (rojo, verde, azul)**. Los textos son secuencias de palabras y caracteres **que no son palabras**. Los flujos de “clics” son **secuencias de acciones** realizadas por un usuario que interactúa con una aplicación o una página web. De hecho, un gran desafío de la ciencia de datos es convertir este torrente de datos sin procesar en información procesable. 

Los datos sin estructura deben procesarse y manipularse en una forma estructurada. 

Una de las formas más comunes de datos estructurados es una tabla con filas y columnas, ya que los datos pueden surgir de una base de datos relacional o recopilarse para un estudio.

Hay dos tipos de datos estructurados : **numéricos y categóricos.**


![[Pasted image 20240822182919.png]]

### El motivo
Para efectos del análisis de datos y **el modelado predictivo, identificar los tipos de datos es clave para ayudar a determinar el tipo de visualización, las transformaciones a realizar, la interpretación de la información o modelo matemático a aplicar.**

Python, utiliza estos tipos de datos **para mejorar el rendimiento computacional.**

Saber que los datos son categóricos puede actuar como una señal que le dice al software cómo **deben comportarse los procedimientos estadísticos, como producir un gráfico o ajustar un modelo.**

### Clasificación de datos
Con **datos categóricos nominales** es posible calcular **frecuencias y moda**. No tiene sentido calcular promedios, desviación estándar, cuartiles, etc. **Generalmente se grafican con gráficos de tortas y gráficos de barras.**

Con **datos categóricos ordinales,** al poder transformarlas en números, es posible aplicar estadísticos más completos. A lo que se suma que podemos realizar la operación inversa: transformar números en variables categóricas. Esto se llama Intervalos de Clase (tablas de frecuencia).

Con **datos numéricos continuos**  son datos que adoptan un número ilimitado de valores diferentes porque sus valores no son fijos. Se pueden aplicar casi todos los estadísticos. Se representan gráficamente con histogramas y tendencias. Algunos ejemplos: altura, el peso, la temperatura, etc.

Con **datos numéricos discretos**, son aquellos que sólo pueden tomar valores determinados. Se trata de datos que se pueden contar y que tienen un número limitado de valores. Suelen presentarse en forma de números. Ejemplos son número de nuevos clientes, número de artículos en un stock, número de alumnos. Se pueden representar por gráficos de barras 


## Tipos estadísticos

### Estimaciones de localización
La **media** es una medida que representa el **"valor típico"** de una variable, mostrando dónde se concentran la mayoría de los datos. Se calcula sumando todos los valores y dividiendo el resultado entre el número total de valores en la muestra.
$$
\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i
$$
```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
media = np.mean(a)
```

Una variación de la media es una **media recortada**, que se calcula dejando fuera un número fijo de valores ordenados en cada extremo y luego tomando un promedio de los valores restantes.

Este tipo de media, elimina la influencia de los valores extremos, que podrían ser posibles outliers.
$$
\bar{x} = \frac{\sum_{i=p+1}^{n-p} x_{(i)}}{n - 2p}
$$

```python
from scipy import stats

a = np.array([1, 2, 3, 4, 5])
media_recortada = stats.trim_mean(a, 0.2)
```

Otro tipo de media es una **media ponderada**, que se calcula multiplicando cada valor de datos por un peso especificado por el usuario y dividiendo su suma por la suma de los pesos.

Hay **dos razones** para usar este tipo de media:
- Algunos **valores son intrínsecamente más variables que otros**, y las observaciones altamente variables reciben un peso más bajo. 
	- Por ejemplo, para un sensor con falla, podemos ponderar **sus datos en forma menor.**
- Los datos recogidos no representan por igual a los diferentes colectivos que nos interesa medir.
$$
\bar{x}_w = \frac{\sum_{i=1}^{n} w_i x_i}{\sum_{i=1}^{n} w_i}
$$
La **mediana** es el número del medio en una lista ordenada de datos. Si hay un número par de valores de datos, el valor medio es uno que no está realmente en el conjunto de datos, sino el promedio de los dos valores que dividen los datos ordenados en mitades superior e inferior. 

**La mediana se conoce como una estimación robusta de la ubicación, ya que no está influenciada por valores atípicos (outliers) que podrían sesgar los resultados.**

![[Pasted image 20240822194545.png]]


```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
mediana = np.median(a) # 3
```

### Estimaciones de variabilidad
La ubicación es solo una dimensión al resumir una característica. 

Una segunda dimensión, la variabilidad, también conocida como **dispersión, mide si los valores de los datos están muy agrupados o dispersos.** 

![[Pasted image 20240822194748.png]]

La **variabilidad** de los datos se mide observando las diferencias (o desviaciones) entre los datos y un valor central, como la media o la mediana. Por ejemplo, si tienes los datos {1, 4, 4}, la media es 3. Las desviaciones de la media serían: 1 – 3 = -2, 4 – 3 = 1, y 4 – 3 = 1.

Estas desviaciones muestran qué tan dispersos están los datos respecto a la media. Sin embargo, si sumamos estas desviaciones, obtendríamos cero, lo que no nos dice nada útil. Para evitar esto, se toman los valores absolutos de las desviaciones (es decir, sin signos negativos) y se promedian. En este caso, las desviaciones absolutas son {2, 1, 1} y su promedio es 1,33. Esto se llama **desviación absoluta media** y es una manera sencilla de entender cuánta variación hay en los datos.

$$
\text{Mean absolute deviation} = \frac{\sum_{i=1}^{n} \left| x_i - \bar{x} \right|}{n}
$$
```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
desviacion_absoluta_media = np.mean(np.abs(a - np.mean(a)))
```

Las estimaciones de variabilidad más conocidas son la **varianza y la desviación estándar**, que se basan en desviaciones al cuadrado. 

La **varianza** es un promedio de las desviaciones al cuadrado (sin signos negativos), y mide cuánto varían los datos de la media).
La **desviación** estándar es la raíz cuadrada de la varianza. (mismo rango que el de la variable original osea en raiz cuadrada de la varianza)

La **desviación estándar** es mucho más fácil de interpretar que la **varianza** ya que está en la misma escala que los datos originales.

**Ni la varianza, ni la desviación estándar, ni la desviación absoluta media son robustas frente a valores atípicos y extremos.** La varianza y la desviación estándar son especialmente **sensibles a los valores atípicos**, ya que se basan en las desviaciones al cuadrado.

$$
\text{Variance} = s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n - 1}
$$
$$
\text{Standard deviation} = s = \sqrt{\text{Variance}}
$$
  
  ```python
  import numpy as np

a = np.array([1, 2, 3, 4, 5])
varianza = np.var(a) # 2.5
desviacion_estandar = np.std(a) # 1.58
```

### Estimaciones basadas en percentiles
Un enfoque diferente para estimar la dispersión se basa en observar la **dispersión de los datos ordenados.** 

Un enfoque para medir la dispersión en los datos es mirar cómo se distribuyen cuando están ordenados. Una medida simple es el rango, **que es la diferencia entre el valor más alto y el más bajo.** Sin embargo, **el rango puede ser engañoso si hay valores extremos (atípicos) en los datos.**

Para evitar este problema, podemos calcular **el rango después de eliminar los valores más altos y más bajos.** Esto se basa en la diferencia entre **percentiles**, que son puntos que dividen los datos ordenados en partes iguales. Por ejemplo, la **mediana** es el percentil 50, es decir, el punto medio de los datos.

En conjuntos de datos muy grandes, calcular percentiles exactos puede ser complicado y costoso en términos de tiempo y recursos, porque implica ordenar todos los datos.

![[Pasted image 20240822200009.png]]

```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
percentil_25 = np.percentile(a, 25) # 2
percentil_75 = np.percentile(a, 75) # 4
```

### Estimaciones basadas en percentiles - `boxplot`
Se basan en percentiles y brindan una forma rápida de visualizar la distribución de datos. 

La figura muestra un diagrama de caja de la población por estado, podemos ver de inmediato que la población estatal promedio es de aproximadamente 5 millones, la mitad de los estados se encuentran entre aproximadamente 2 millones y aproximadamente 7 millones, y hay algunos valores atípicos (outliers) de población altos. 

![[Pasted image 20240822200227.png]]

La parte **superior** e inferior de la caja son los percentiles 75 y 25, respectivamente. 

La **mediana** se **muestra** con la línea horizontal en el recuadro. 

Las **líneas discontinuas**, denominadas bigotes, se extienden desde la parte superior e inferior del cuadro para indicar el rango de la mayor parte de los datos.

Los **valores atípicos** se muestran como puntos individuales.




```python
import matplotlib.pyplot as plt

a = np.array([1, 2, 3, 4, 5])
plt.boxplot(a)
```


### Tablas de frecuencia e histogramas
Una **tabla de frecuencia** de una variable, divide el rango de la variable en segmentos igualmente espaciados y nos dice cuántos valores caen dentro de cada segmento.

**Un histograma es una forma de visualizar una tabla de frecuencia**, con barras en el eje x y el conteo de datos en el eje y. 

En general, los histogramas se trazan de manera que:
- Las barras vacías se incluyen en el gráfico.
- Las barras tienen el mismo ancho.
- El número de barras dependen del usuario.
- Las barras son contiguas: no se muestra ningún espacio vacío entre las barras, a menos que haya una barra vacía.

**Diferencia entre gráfico de barra y histograma**: en el histograma las barras están juntas y en el gráfico de barra están separadas, además en el histograma se puede ver la distribución de los datos y en el gráfico de barra no
- **Cuando usar un histograma**: cuando se quiere ver la distribución de los datos, en el caso de los gráficos de barra se usan para comparar datos.
- **Cuando usar un grafico de barras**: cuando se quiere comparar datos y que se diferencia del histograma porque las barras están separadas y no se ve la distribución de los datos sino se ve la comparación en variables categoricas.

**Analisis antojadizo**: esto es cuando se toma un dato y se le da un significado que no tiene.
**Bins**: es el número de barras que se van a mostrar en el histograma, y esto empieza a dividir los datos en segmentos. (como ejemplo se pueden sacar grupos de edades y saber si son familias.)
 

![[Pasted image 20240822200831.png]]

```python
import matplotlib.pyplot as plt

a = np.array([1, 2, 3, 4, 5])
plt.hist(a)
```

### Datos binarios y categóricos
La **moda** es el valor (o valor que más se repite) que aparece con mayor frecuencia en los datos. 
- La moda es una estadística de resumen simple para datos categóricos y, por lo general, no se usa para datos numéricos.

![[Pasted image 20240822201025.png]]

```python
import cipy.stats as stats

a = np.array([1, 2, 3, 4, 5, 5])
moda = stats.mode(a) # 5
```


Algunas veces los datos **categóricos podemos expresarlos matemáticamente a través del concepto de “ocurrencia futura”** o probabilidad.

La **probabilidad** de que suceda un evento es la proporción de veces que ocurrirá si la situación pudiera repetirse una y otra vez, innumerables veces.

Las probabilidades se expresan como fracciones `(1/6, 1/2, 8/9)` o como decimales `(0.167, 0.500, 0.889)` que están entre cero y uno. 

Tener una **probabilidad de cero** significa que algo nunca va a suceder; una probabilidad de uno indica que algo va a suceder siempre.

![[Pasted image 20240822202104.png]]

### Correlación
El análisis exploratorio implica **examinar la correlación entre los predictores y entre los predictores y una variable objetivo.** 

La correlación sirve para eliminar variables que están altamente correlacionadas entre sí, ya que no aportan información adicional al modelo y son redundantes.


Dos variables, X e Y, están **correlacionadas positivamente** cuando, al aumentar los valores de X, también aumentan los valores de Y, y cuando X disminuye, Y también disminuye. Por ejemplo, si a más horas de estudio (X) corresponde un mayor puntaje en un examen (Y), hay una correlación positiva.

Por otro lado, están **correlacionadas negativamente** cuando, al aumentar los valores de X, los valores de Y disminuyen, y viceversa. Por ejemplo, si a más horas de ver televisión (X) corresponde un menor puntaje en un examen (Y), hay una correlación negativa.

El **coeficiente de correlación**, que da una estimación de la correlación entre dos variables que siempre se encuentran en la misma escala. Para calcular el coeficiente de correlación de Pearson, multiplicamos las desviaciones de la media de la variable 1 por las de la variable 2 y dividimos por el producto de las desviaciones estándar.

$$
r = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{(n - 1)s_x s_y}
$$
El coeficiente de correlación siempre se encuentra entre +1 (correlación positiva perfecta) y –1 (correlación negativa perfecta); 0 indica que no hay correlación. 

**Las variables pueden tener una asociación que no sea lineal, en cuyo caso el coeficiente de correlación puede no ser una métrica útil.**

A partir de una tabla de correlaciones, se puede trazar un mapa de calor para mostrar visualmente la relación entre múltiples variables. 

La correlación va entre -1 y 1.
- **1**: Significa que si una variable aumenta la otra también aumenta perfectamente.

Decir que hay correlacion no es igual a decir que hay causalidad, ya que pueden haber variables que se comporten muy similares pero que no tienen sentido que esten relacionadas.

![[Pasted image 20240822203057.png]]

**Variables dependiente y Independiente**: La variable dependiente es aquella que se mide o se observa en un experimento, y la variable independiente es la que se manipula, las variables independientes ayudan  a predecir o explicar la variable dependiente.

```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
b = np.array([5, 4, 3, 2, 1])

correlacion = np.corrcoef(a, b)
```

**Dato:** La causalidad es el resultado de una causa.


# Tratamiento de datos
En cualquier proyecto de Machine Learning o Ciencia de datos nos tenemos que enfrentar a una situación ineludible: **los datos no son ideales y, generalmente, faltan muchos de ellos.**

Existen varias formas **de detectar y eliminar los valores atípicos, pero los métodos que hemos visto son ampliamente utilizados y fáciles de entender.**

**Si un valor atípico debe eliminarse o no dependerá  de cada problema en el que esté trabajando.**

Para saber **cuál técnica podremos utilizar para el tratamiento de los datos faltantes, primero debemos determinar el mecanismo detrás de esa pérdida de datos.** Y estos mecanismos se dividen en tres:

## (MCAR: Missing Completely at Random)
Ocurre cuando la probabilidad de que una variable **tenga valor faltante es independiente de la misma variable y de cualquier otra influencia externa**. Lo que significa que los valores faltantes no dependen de los datos.
- Cuando no hay una razón especifica de porque apareció. (es aleatorio)


## (MNAR: Missing Not at Random)
Ocurre cuando la probabilidad de que una variable tenga valores faltantes no es al azar, por lo tanto depende de las variables faltantes.
- Hay una situación en particular que hace que ese dato falte.

Supongamos que tenemos un set de datos y que los datos faltantes aparecen tanto en la **categoría A como en la B o en la C,** y los valores faltantes pueden **ser altos o bajos**. 

Esto quiere decir que esos datos faltantes no dependen ni de la categoría ni del valor mismo de los datos, por lo que podemos decir que el mecanismo es completamente aleatorio.

![[Pasted image 20240826194345.png]]


## (MAR: Missing at Random)
Ocurre cuando la probabilidad de que una variable tenga valores faltantes no es al azar, por lo tanto depende de las variables faltantes.
- Supone que los datos faltantes tienen alguna relación con las variables que se observan.

Volviendo a nuestro set de datos hipotético podemos ver que sistemáticamente los datos con valores menores a 100 faltan, tanto para las categorías A, B como C. **Es decir que los valores faltantes dependen de la variable “V2”, y por tanto la razón de la falta de datos NO es aleatoria.**

Este mecanismo es el más complicado de todos, porque como la pérdida de datos es sistemática tenemos que encontrar esta razón, intentar corregir el problema y, muy probablemente, adquirir los datos nuevamente.

![[Pasted image 20240826201350.png]]

## (MAR: Missing at Random)
Ocurre cuando la probabilidad de que una variable tenga valor faltante es independiente de las variables con valores faltantes pero dependiente de las otras variables con valores observables. Esto sugiere un supuesto menos restringido.

Este mecanismo es un punto intermedio entre los dos anteriores.

En el ejemplo vemos que los datos faltantes corresponden únicamente a datos en la categoría B, y que estos datos faltantes van desde los más pequeños a los más grandes. Esto quiere decir que los valores faltantes dependen sólo de la variable “V1” (la categoría) y no de la propia variable “V2”.

![[Pasted image 20240826201444.png]]


## Arboles
Los arboles no necesitan tanta data e ignora nulls y no necesita escalar los datos, pero no es tan interpretable y no es tan bueno para predecir.

## Convergencia
Es cuando al modelo de entrenamiento ya no puede predecir mas datos sino que queda siempre en los mismos datos.

## Estrategias
Tenemos dos grandes grupos que **son el descarte de datos y la imputación.**

Consiste simplemente en eliminar los registros que contengan datos faltantes, mientras que en **la imputación** lo que se busca es estimar el valor del dato faltante. Para esto último se puede usar la información de los registros vecinos, la información presente en otras variables (o columnas) del set de datos, como un estadístico o simplemente una constante.

En términos generales estas técnicas se pueden aplicar a datos faltantes aleatorios o completamente aleatorios, es decir que asumen un grado de aleatoriedad en el mecanismo responsable de la pérdida de los datos.

Sin embargo, **para el caso de datos faltantes no aleatorios no es recomendable usar estas técnicas** porque la pérdida de datos en este caso es sistemática.

![[Pasted image 20240826202059.png]]

### Descarte

Eliminar los ejemplos (o variables) con MV: sencillo, pero no se puede aplicar siempre. **Sólo cuando el porcentaje de datos faltantes es pequeño.**

Si el porcentaje de **MV** es grande, debemos pensar en otra solución. Es bueno ver como están distribuido los **MV** en el dataset completo.

Aunque existen diferentes técnicas, en general estas se centran en tres:
- Eliminar valores faltantes
- Eliminar filas del dataset faltantes
- Eliminar columnas del dataset faltantes

![[Pasted image 20240826203336.png]]

Una forma es la eliminación por pares (pairwise deletion),  donde se quitarán únicamente las casillas con el dato faltante. 

La ventaja es que preservamos los datos conocidos, pero la desventaja es que podremos tener características (es decir columnas) con diferente cantidad de datos, lo que puede complicar el entrenamiento de un modelo de Machine Learning pues el número de datos debe ser el mismo para cada característica:

![[Pasted image 20240826203745.png]]

Una forma más agresiva, es la eliminación de la lista (listwise deletion).

La cual consiste en remover del set de datos las filas que contengan datos faltantes, con la desventaja de que al eliminar la fila completa eliminaremos también algunos datos existentes, lo que puede llevar a una pérdida significativa de información

![[Pasted image 20240826203804.png]]

### Imputación
En muchos casos, la mejor opción es imputar datos, ya que esto permite trabajar con todos los datos aunque produzca un sesgo.

Existen muchas técnicas para lidiar con esto. La taxonomía no está 100% definida, pero acá entregamos un ejemplo.

**Las técnicas de imputación están enfocadas a variables numéricas.**

Para variables categóricas se podría imputar con la moda, pero es preferible realizar un encoding antes, identificando si es una variable categórica nominal u ordinal.

![[Pasted image 20240826204017.png]]

En la imputación **lo que hacemos es mirar el comportamiento de los datos vecinos para poder estimar el valor del dato faltante.**

Idealmente esta imputación no debería cambiar la distribución de nuestros datos. Así que si originalmente teníamos una distribución normal (con forma de campana), entonces después de la imputación se debería mantener esta distribución original.

Acá podemos usar dos técnicas: **la imputación simple y la imputación múltiple,** y en ambos casos, las debemos usar sólo si estamos seguros de que los mecanismos son para datos faltantes completamente aleatorios.

![[Pasted image 20240826204148.png]]

#### Imputación simple
En la imputación simple se usa un algoritmo para hacer una única estimación y el valor obtenido se usa para reemplazar el dato faltante correspondiente. En este caso las tres técnicas más usadas son:

- **Imputación por la media o la mediana:** se calcula la media o la mediana y se reemplazan los datos faltantes con cualquiera de estos dos valores.  Tiene la desventaja de que al reemplazar muchos datos faltantes con un único valor estaremos cambiando la distribución de los datos.

- **Imputación por una constante:** se reemplazan los valores faltantes con un valor que luego nos ayudará a reconocer estos registros como faltantes. Tiene la desventaja que el modelo de ML puede detectar reglas en los datos de manera errónea.

- **Hacer la imputación por regresión**: En este caso cada dato faltante es reemplazado con el valor predicho por un modelo de regresión. Aquí se preserva la distribución de los datos. Pero, debe haber algún tipo de correlación entre las variables que estamos usando para construir este modelo.

- **Imputación hot-deck**: En este caso, el dato faltante es reemplazado con valores tomados de datos “cercanos” al dato faltante. Dentro de esta categoría el método más usado es el de k-vecinos más cercanos (o kNN por sus siglas en Inglés: k-Nearest Neighbors). Es mucho más preciso que la media o la mediana, y puede funcionar en lugar de la regresión cuando los datos no están correlacionados. La desventaja es que si tenemos muchos datos se requiere bastante tiempo de cómputo.
	- Hace grupos de datos para que sea mas fácil de recomendar para el algoritmo.

#### Imputación múltiple
En la imputación múltiple se hacen múltiples estimaciones, que luego se combinan para producir un único valor, que será el usado para reemplazar el dato faltante correspondiente, con lo cual se puede disminuir el sesgo de la estimación.

El método más usado es el algoritmo de Imputación Múltiple con Ecuaciones Encadenadas (o MICE por sus siglas en Inglés: **Multiple Imputation by Chained Equations). Aquí, la idea es que progresivamente las estimaciones sean cada vez más precisas y se acerquen más y más al valor real.**

Aunque es un método muy preciso, requiere que haya relación lineal entre las variables.
- Es por su iteración.

## Outliers
Los valores atípicos son **aquellos puntos de datos que difieren significativamente de otras observaciones presentes en un conjunto de datos dado.** Puede ocurrir debido a la variabilidad en la medición y debido a una mala interpretación al llenar los puntos de datos.

Al realizar la recopilación de datos, es cuando los valores atípicos se presentan por primera vez a la población. Los valores atípicos pueden ser el resultado de un error durante la recopilación de datos o pueden ser solo una indicación de variación en los datos.

En el ejemplo,  todos los jugadores obtuvieron una puntuación de más de 300, excepto el Jugador 3, que obtuvo una puntuación de 10. Si esto es un error, podemos ignorarlo, pero si es una variación en los datos, debemos analizar un poco más.

![[Pasted image 20240826204445.png]]

### Detección con Visualización

#### Boxplot
En un gráfico de caja (boxplot), los outliers se trazan como puntos individuales, mientras que el resto de la población se agrupará dentro de la caja o los “bigotes” del gráfico.

La gráfica muestra tres puntos entre 10 y 12, estos son valores atípicos ya que no están incluidos en el cuadro de la observación, es decir, no están cerca de los cuartiles.

Aquí analizamos el **valor atípico univariable.**

**Porque?**: Se hace un boxplot para analizar una variable y regresa quantiles (esto responde para el proque quiero saber.)

![[Pasted image 20240826204626.png]]

#### Gráfico de dispersión
Un gráfico de dispersión es un tipo de gráfico o diagrama matemático que utiliza coordenadas cartesianas para mostrar valores de dos variables típicamente para un conjunto de datos. 

Mirando la gráfica, podemos ver que la mayoría de los puntos de datos se encuentran en el lado inferior izquierdo, pero hay puntos que están lejos de la población, como la esquina superior derecha.

Este es un análisis de  **valores atípico multivariable.**

![[Pasted image 20240826204744.png]]

### Detección con Métricas
**La puntuación Z** asume que las variables tienen una distribución Gaussiana. Aquí se representan el “número de desviaciones estándar” alejadas de la media.

Aquí, normalmente definimos valores atípicos como puntos cuyo módulo de puntuación z es mayor que un valor de umbral. Este valor de umbral suele ser superior a 2 (3 es un valor común).

![[Pasted image 20240826204914.png]]

**El método IQR**, usa del rango intercuartílico (IQR), para detectar valores atípicos. 

IQR nos dice la variación en el conjunto de datos. **Cualquier valor que esté más allá del rango de -1,5 x IQR a 1,5 x IQR se trata como un valor atípico.**

- Q1 representa el primer cuartil/percentil 25 de los datos.
- Q2 representa el segundo cuartil/mediana/percentil 50 de los datos.
- Q3 representa el tercer cuartil/percentil 75 de los datos.
- (Q1–1.5IQR) representan el valor más pequeño en el conjunto de datos y 
- (Q3+1.5IQR) representan el valor más grande en el conjunto de datos

![[Pasted image 20240826205115.png]]

### Corrección o eliminación
**Usando el puntaje Z:** si queremos eliminar o filtrar los valores atípicos y obtener los datos limpios, se puede hacer con solo un código de línea, ya que ya hemos calculado el puntaje Z.

En el código se eliminan más de 90 filas del conjunto de datos BOSTON HOUSE, es decir, se eliminaron los valores atípicos usando la librería SPICY.

```python
from scipy import stats
import numpy as np

z = np.abs(stats.zscore(boston_df))
boston_df_o = boston_df[(z < 3).all(axis=1)]
boson_df.shape # (506, 13) 
boson_df_o.shape # (415, 13) 
```

**Puntuación IQR,** al igual que el puntaje Z, podemos usar el puntaje IQR para filtrar los valores atípicos manteniendo solo los valores válidos.

El código descrito eliminará los valores atípicos del conjunto de datos.

```python
Q1 = boston_df_o1.quantile(0.25)
Q3 = boston_df_o1.quantile(0.75)
IQR = Q3 - Q1

boston_df_out = boston_df_o1[~((boston_df_o1 < (Q1 - 1.5 * IQR)) |(boston_df_o1 > (Q3 + 1.5 * IQR))).any(axis=1)]
```

Al igual que la imputación de valores faltantes, también podemos imputar valores atípicos

Podemos **usar la media, la mediana, el valor cero en este método.**  Al imputar, no hay pérdida de datos. 
- Por ejemplo, aquí aplicamos la media.

![[Pasted image 20240826210409.png]]

En otro caso aplicamos mediana

![[Pasted image 20240826210431.png]]

# Que es KNN
KNN significa K vecino más cercano (K-Nearest Neighbors), el propio nombre sugiere que se considera el vecino más cercano, **es uno de los algoritmos de aprendizaje automático supervisado**, curiosamente, podemos resolver problemas de clasificación y regresión con el algoritmo. 

Es uno de los modelos de **Machine Learning más simples y además nos sirve para la imputación de datos.**

## Como funciona
K-NN tiene dos parámetros: **La medida de distancia o similaridad.**
- El parámetro “K” o “e” según como se decida crear los vecindarios.
	- **e**: parametro de la distancia
	- **K**: concidera los dos mas parecidos.

El **concepto de similaridad o distancia** son parecidos, ya que tratan de cuantificar lo mismo, pero de puntos de vistas distinto.
- **La distancia** entre más crece, más alejados o distintos son los objetos a medir
- **La similaridad** entre más crece, más parecidos o cercanos son los objetos a medir.

### Formas de calcular las métricas
**EUCLIDIANA**: es la fórmula de distancia más utilizada. La fórmula de la distancia euclidiana encuentra la distancia más corta entre los puntos A y B. Esto a veces se conoce como el teorema de Pitágoras.

$$
d = \sqrt{(p_1 - q_1)^2 + (p_2 - q_2)^2}
$$

**MANHATTAN** es la suma de las diferencias absolutas entre puntos en todas las dimensiones. La distancia Manhattan **se usa  si necesitamos calcular la distancia entre dos puntos de datos en una ruta similar a una cuadrícula.**

$$
d = \sum_{i=1}^{n} |x_i - y_i|

$$

**MINKOWSKI** es un espacio vectorial normado que puede considerarse como una generalización de la distancia euclidiana y la distancia de Manhattan.

$$
d(i, j) = \left( \sum_{k=1}^{p} |x_{ik} - x_{jk}|^q \right)^{\frac{1}{q}}, \quad q > 0
$$


#### Formas
![[Pasted image 20240826211321.png]]


### Vecindarios
**La más tradicional es usar el parámetro K:** esto se basa en elegir los K vecinos más cercanos según una métrica de distancia o similaridad.

No existe un método estructurado para encontrar el mejor valor de K.

En este ejemplo, el punto negro central busca los K=6 vecinos más cercanos en un espacio de 2 dimensiones.

![[Pasted image 20240826211420.png]]

**La otra estrategia es usar el parámetro “e”:** este parámetro define un radio “e” y todo dato que esté dentro de ese radio “e” es un dato perteneciente al vecindario.

En este ejemplo, hay un punto central indicado con la flecha. Este punto define su vecindario según el valor del parámetro “e”, hay 2 circunferencias que son el resultado de 2 valores de “e” distintos y según el valor de “e”, es el tamaño del vecindario (3 y 5).

![[Pasted image 20240826211515.png]]

Una manera es con la estrategia de radio y barre a los que estan cercanos.

## Imputación

### Usos de KNN en la imputación
La idea de usar K-NN para imputación es usar los vecindarios para obtener el valor que reemplazaremos por el “valor faltante”.

Definidos los parámetros del algoritmo (distancia y valor de K o “e”), buscaremos cuáles son los datos que conformarán el vecindario.

La distancia se debe calcular con las variables observables y, además, se deben elegir datos que tengan valores que sirvan para realizar la imputación.

#### Ejemplo
Supongamos que queremos imputar un valor a valores **NaN**.
Podemos usar las variables numéricas y observables para calcular la distancia.

![[Pasted image 20240826211843.png]]

La distancia se calcula entre el vector que tiene el MV que queremos imputar y los vectores que también tienen valores en esas variables y que tengan datos observados en la variable **Humidity**, eso hace que los datos: 3, 6, 8 y 9 no sean considerados por tener “valores faltantes”.

![[Pasted image 20240826212113.png]]

Supongamos que K=3. Entonces, los vecinos más cercanos serían: 1, 5 y 7, finalmente, con esos 3 datos estimamos el MV con la técnica que queramos. En este caso, podríamos usar la media: (64.0 + 68.0 + 68.0)/3.

![[Pasted image 20240826212204.png]]

`weight`: es un parámetro que se le puede dar a los datos que están mas cerca para que tengan mas peso en la imputación.

```python
knn_imputer = KNNImputer(n_neighbors=2, weights='uniform')
```

# Escalado
Una de las transformaciones más importantes que hay que aplicar a los datos es el escalado de características. **Salvo algunas excepciones, los algoritmos de Machine Learning no tienen un buen rendimiento cuando los atributos numéricos de entrada tienen escalas muy diferentes.**
- Acá habla de que el escalado es importante para igual números muy pequeños con números muy grandes.

## Por que escalar?
La mayoría de las veces, nuestro conjunto de datos contendrá características que **varían mucho en magnitudes, unidades y rango.** Pero dado que la **mayoría de los algoritmos de aprendizaje automático usan la distancia euclidiana** _entre dos puntos de datos en sus cálculos_, esto es un problema.

Si se dejan solos, estos algoritmos sólo toman en cuenta la magnitud de las características y descuidan las unidades.

Los resultados variarían mucho entre diferentes unidades, por ejemplo entre 5 kg y 5000 g. 

Las características con magnitudes altas pesarán mucho más en los cálculos de distancia que las características con magnitudes bajas. Para suprimir este efecto, necesitamos traer todas las características al mismo nivel de magnitudes. Esto se puede lograr escalando.


## Normalización
El objetivo de la normalización es cambiar sus observaciones para que puedan describirse como una distribución normal.

La distribución normal (distribución gaussiana), también conocida como curva de campana , es una distribución estadística específica en la que aproximadamente las mismas observaciones caen por encima y por debajo de la media, la media y la mediana son iguales y hay más observaciones más cercanas a la media.

Se utiliza la siguiente fórmula.
Podemos ver que cuando Xi=min, entonces Xnew=0, y cuando Xi=max, entonces Xnew=1.
Esto significa que el valor mínimo de X se asigna a 0 y el valor máximo de X se asigna a 1. 
Por lo tanto, **todo el rango de valores de X, desde el mínimo hasta el máximo, se asigna al rango de 0 a 1.**
Esta forma de escalamiento es muy sensible a los outliers.
En Python, usamos **MinMaxScaler**.
$$
X_{\text{new}} = \frac{X_i - \min(X)}{\max(X) - \min(X)}
$$

## Estandarización
**La estandarización** **(también llamada normalización de puntuación z)** transforma sus datos de modo que la distribución resultante tenga una media de 0 y una desviación estándar de 1.

En Python usamos la función **StandardScaler**.

Es más resistente a outliers, pero no es muy interpretable para datos que se alejan mucho de una distribución Normal.
$$
X_{\text{new}} = \frac{X_i - X_{\text{mean}}}{\text{Standard Deviation}}
$$

## Comparación
**Escalado vs. Normalización: ¿Cuál es la diferencia?** En ambos casos, está transformando los valores de las variables numéricas para que los puntos de datos transformados tengan propiedades útiles específicas. 

La diferencia es que, al escalar, está cambiando el rango de sus datos mientras que en la normalización está cambiando la forma de la distribución de sus datos.

![[Pasted image 20240909194952.png]]


# Encoding
La mayoría de los **algoritmos de aprendizaje automático no pueden manejar variables categóricas a menos que las convirtamos en valores numéricos.** 

El rendimiento de muchos algoritmos varía en función de cómo se codifican las variables categóricas.

Hay muchas maneras en que podemos codificar estas variables categóricas como números y usarlas en un algoritmo.

## One Hot Encoding
En este método, asignamos cada categoría a un vector que contiene 1 y 0, lo que denota la presencia o ausencia de la característica. 

El número de vectores depende del número de categorías de características. 

Este **método produce muchas columnas que ralentizan significativamente el aprendizaje** si el número de la categoría es muy alto para la función. 

```python

from sklearn.preprocessing import OneHotEncoder
import pandas as pd

# Suponiendo que 'df' es el DataFrame original con la columna 'Temperature'
ohe = OneHotEncoder()
ohc = ohe.fit_transform(df.Temperature.values.reshape(-1, 1)).toarray()
dfOneHot = pd.DataFrame(ohc, columns=["Temp_" + str(ohe.categories_[0][i]) for i in range(len(ohe.categories_[0]))])

# Concatenar el DataFrame original con el codificado
dfh = pd.concat([df, dfOneHot], axis=1)

# Mostrar el DataFrame resultante
dfh
```

## Binary Encoding
La codificación binaria convierte una categoría en dígitos binarios, cada dígito binario crea una columna de características, **si hay n categorías únicas, la codificación binaria da como resultado las únicas funciones de registro `(base 2)ⁿ`**. 

En este ejemplo, tenemos cuatro características; por lo tanto, las características codificadas en binario serán tres características. 

En comparación con One Hot Encoding, esto requerirá menos columnas de funciones (para 100 categorías, One Hot Encoding tendrá 100 funciones, mientras que para la codificación binaria, necesitaremos solo siete funciones).

```python
import category_encoders as ce
import pandas as pd

# Suponiendo que 'df' es el DataFrame original con la columna 'Temperature'
encoder = ce.BinaryEncoder(cols=['Temperature'])
dfbin = encoder.fit_transform(df['Temperature'])

# Concatenar el DataFrame original con el codificado
df = pd.concat([df, dfbin], axis=1)

# Mostrar el DataFrame resultante
df
```

## Label Encoding
En esta codificación, a cada categoría se le asigna un valor de 1 a N (donde N es el número de categorías para la función. 

**Un problema importante con este enfoque es que no hay relación ni orden entre estas clases**, pero el algoritmo podría considerarlas como algún orden o alguna relación.

En el siguiente ejemplo, puede verse como **Scikit** Learn nos permite aplicar Label Encoding con: `(Cold<Hot<Very Hot<Warm….0 < 1 < 2 < 3)`.

```python
from sklearn.preprocessing import LabelEncoder
import pandas as pd

# Suponiendo que 'df' es el DataFrame original con la columna 'Temperature'
df['Temp_label_encoded'] = LabelEncoder().fit_transform(df.Temperature)

# Mostrar el DataFrame resultante
df
```

## Ordinal Encoding
Realizamos la codificación ordinal **para garantizar que la codificación de las variables conserve la naturaleza ordinal de la variable.** Esta codificación se ve casi similar a Label Encoder, pero es ligeramente diferente, ya que la Label Encoder no consideraría si la variable es ordinal o no, y asignará una secuencia de números enteros.

En este código usando Pandas, primero debemos asignar el orden original de la variable a través de un diccionario. Luego podemos **mapear** cada fila para la variable según el diccionario.

```python
import pandas as pd

# Diccionario de mapeo de valores ordinales
Temp_dict = {
    'Cold': 1,
    'Warm': 2,
    'Hot': 3,
    'Very Hot': 4
}

# Aplicar el mapeo a la columna 'Temperature'
df['Temp_Ordinal'] = df.Temperature.map(Temp_dict)

# Mostrar el DataFrame resultante
df
```

Aunque es muy sencillo, **requiere codificación** para indicar los valores ordinales y la asignación real de texto a un número entero según el orden.


