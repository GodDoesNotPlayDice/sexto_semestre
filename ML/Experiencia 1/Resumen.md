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

La **varianza** es un promedio de las desviaciones al cuadrado
La **desviación** estándar es la raíz cuadrada de la varianza.

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

![[Pasted image 20240822203057.png]]

**Variables dependiente y Independiente**: La variable dependiente es aquella que se mide o se observa en un experimento, y la variable independiente es la que se manipula, las variables independientes ayudan  a predecir o explicar la variable dependiente.

```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
b = np.array([5, 4, 3, 2, 1])

correlacion = np.corrcoef(a, b)
```

**Dato:** La causalidad es el resultado de una causa.