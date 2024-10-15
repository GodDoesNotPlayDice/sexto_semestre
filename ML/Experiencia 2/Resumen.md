# Clasificación
Clasificación es un tipo de tarea en aprendizaje automático supervisado en el que el modelo intenta predecir la etiqueta (o clase) correcta de unos datos de entrada determinados.

## Regresión y Clasificación
Aunque la clasificación y la regresión pertenecen a la categoría de aprendizaje supervisado, no son el mismo tipo, ni son lo mismo.

![[Pasted image 20240924095752.png]]

## Tipos de clasificación

### Clasificación binaria
En una tarea de clasificación binaria, el objetivo es clasificar los datos de entrada en dos categorías mutuamente excluyentes. 

Los datos de entrenamiento en tal situación se etiquetan en formato binario: verdadero y falso; positivo y negativo; 0 y 1; spam y no spam, etc. según el problema que se aborde.

Por ejemplo, podríamos querer detectar si una imagen dada es un camión o un bote.
![[Pasted image 20240924095903.png]]

### Clasificación multiclase
La clasificación multiclase, por otro lado, tiene a lo menos dos etiquetas de clase mutuamente excluyentes, donde el objetivo es predecir a qué clase pertenece un ejemplo de entrada dado. 

En el siguiente caso, el modelo clasificó correctamente la imagen como un avión.


La mayoría de los algoritmos de clasificación binaria también se pueden utilizar para la clasificación multiclase.
![[Pasted image 20240924100011.png]]

### Clasificación etiqueta multiclase
En las tareas de clasificación de etiquetas múltiples, intentamos predecir 0 o más clases para cada ejemplo de entrada. 

En este caso, no hay exclusión mutua porque el ejemplo de entrada puede tener más de una etiqueta.

Este escenario se puede observar en diferentes dominios, como el etiquetado automático en el procesamiento del lenguaje natural, donde un texto determinado puede contener varios temas. De manera similar a la visión por computadora, una imagen puede contener múltiples objetos, como se ilustra a continuación: el modelo predijo que la imagen contiene: un avión, un bote, un camión y un perro.
![[Pasted image 20240924100111.png]]

### Clasificación desbalanceada
Para la clasificación desequilibrada o desbalanceada, el número de ejemplos se distribuye de manera desigual en cada clase, lo que significa que podemos tener más de una clase que de las otras en los datos de entrenamiento. 

El uso de modelos predictivos convencionales, como árboles de decisión, regresión logística, etc., podría no ser eficaz cuando se trata de un conjunto de datos desequilibrado, ya que podrían estar sesgados hacia la predicción de la clase con el mayor número de observaciones y considerar aquellas con menos números como ruido.

![[Pasted image 20240924100240.png]]
Consideremos el siguiente escenario de clasificación de 3 clases donde los datos de entrenamiento contienen: 60 % de camiones, 25 % de aviones y 15 % de barcos.

El problema de clasificación desequilibrada podría ocurrir en el siguiente escenario:
- Detecciones de transacciones fraudulentas 
- Diagnóstico de enfermedades raras
- Análisis de abandono de clientes

# Regresión Logística
La **regresión logística** es un algoritmo de **aprendizaje automático** comúnmente utilizado para problemas de **clasificación binaria**. Este modelo predice la **probabilidad** de que un evento ocurra (como clasificar un correo como spam o no, o predecir si un tumor es maligno). Es útil cuando las etiquetas a predecir son **binarias** (es decir, 0 o 1).

A diferencia de la regresión lineal, que predice un valor continuo, la regresión logística utiliza la **función sigmoide** (o logística), que transforma las combinaciones lineales de las características en **probabilidades** entre 0 y 1. Estas probabilidades se usan para clasificar las observaciones en dos clases, con un **umbral** (generalmente 0.5) que determina si se asigna a la clase positiva (1) o negativa (0).

- Es un modelo de **clasificación**, no de regresión, aunque su nombre pueda confundir.
- Se utiliza para predecir **probabilidades** de que un evento ocurra (como si un correo es spam o no) basándose en datos de entrada. A diferencia de la regresión lineal, que predice valores continuos, la regresión logística predice un valor que puede interpretarse como una probabilidad entre 0 y 1.

Se utiliza para predecir la probabilidad de que ocurra un evento dado un conjunto de características. Aunque lleva el nombre "regresión", se usa principalmente para clasificación, no para predecir valores continuos.
- **Función Logística o Sigmoide**: Convierte una combinación lineal de características en una probabilidad entre 0 y 1. La salida final suele clasificarse como 0 o 1, utilizando un umbral (generalmente 0.5) para decidir entre las clases.
- **Logit**: Es el logaritmo de las probabilidades, que es la razón entre la probabilidad de que una muestra pertenezca a la clase positiva y la probabilidad de que pertenezca a la clase negativa.
- **Clasificador lineal**: La regresión logística asume que el límite entre clases es una superficie lineal, lo que convierte a este modelo en un clasificador lineal.
## ¿Cuándo usar la regresión logística?
- **Problemas de clasificación binaria**: Por ejemplo, para determinar si un correo es spam o no, o si un paciente tiene una enfermedad.
- **Interpretabilidad**: Es útil cuando quieres un modelo que sea fácil de interpretar, ya que te permite ver cómo las características influyen en la probabilidad de pertenecer a una clase.
- **Simplicidad**: A menudo se usa como modelo de referencia para comparar el rendimiento de otros modelos más complejos.

### Aplicaciones típicas:

- Clasificación de correos electrónicos como spam o no spam.
- Diagnóstico médico para determinar si una condición es presente (por ejemplo, si un tumor es maligno).
- Modelos de predicción de abandono en estudios de clientes o usuarios.

### ¿Cómo usar la regresión logística?

- **Entrenamiento**: Se necesita un conjunto de datos etiquetados con muestras y sus correspondientes clases (0 o 1). El modelo ajusta sus parámetros utilizando técnicas como el máximo de verosimilitud para minimizar el error de clasificación.
- **Predicción**: Para una nueva muestra, el modelo genera una probabilidad y clasifica en función del umbral definido (generalmente 0.5).
- **Interpretación**: Los coeficientes del modelo pueden interpretarse como la influencia de cada característica en la probabilidad de pertenecer a una clase.

### Cómo funciona
- **Modelo Lineal**: Similar a la regresión lineal, combina las características de entrada con pesos (coeficientes), produciendo un valor intermedio llamado **log-odds** o **logit**.
- **Función Sigmoide**: Este valor intermedio luego pasa por la función **sigmoide** para convertir el valor en una probabilidad. La fórmula de la sigmoide.
	- Donde **z=wTx+bz = w^T x + bz=wTx+b**, que es la combinación lineal de las características ( xxx ) y sus pesos ( www ). La función sigmoide comprime este valor en el rango de 0 a 1, lo que representa una probabilidad.
		- **Decisión final**: Una vez que tienes la probabilidad, se define un **umbral** (generalmente 0.5). Si la probabilidad es mayor a 0.5, clasificas la muestra como **positiva** (por ejemplo, spam o enfermedad), y si es menor, la clasificas como **negativa**.

### La función logit o log-odds
- El **logit** es el logaritmo de las probabilidades de que un evento ocurra en relación a que no ocurra:
$$
\text{logit}(p) = \log\left(\frac{p}{1 - p}\right)
$$
 Este valor es lo que transforma el modelo lineal en un problema de clasificación. Lo que se hace es ajustar un modelo lineal a los **log-odds** en lugar de las probabilidades directamente. Luego, la función **sigmoide** convierte esos log-odds en probabilidades que interpretamos fácilmente.

### Interpretación de los coeficientes
- **Coeficientes (pesos)**: Los coeficientes del modelo logístico indican cómo una característica afecta la probabilidad de un resultado positivo.
- Si un coeficiente es positivo, indica que esa característica **aumenta** la probabilidad de un resultado positivo. Si es negativo, indica que la **disminuye**.
- **Odds ratio**: Los coeficientes también pueden interpretarse en términos de **razón de probabilidades (odds ratio)**. Por ejemplo, un coeficiente de 0.7 significa que la razón de probabilidades aumenta en un factor de **e0.7e^{0.7}e0.7**, es decir, 2 veces más probable de pertenecer a la clase positiva cuando esa característica aumenta en una unidad.

### Cómo entrenar y optimizar el modelo
El modelo ajusta sus pesos durante el entrenamiento usando **algoritmos de optimización** como el **gradiente descendente**. El gradiente descendente busca minimizar la función de costo ajustando los coeficientes del modelo para que las predicciones se acerquen a las verdaderas clases.


### Aplicación de la regresión logística

- **Cuando la salida es binaria**: La regresión logística es ideal para problemas donde la salida tiene dos posibles valores (sí/no, 0/1, spam/no spam, etc.).
- **Problemas lineales**: Funciona mejor cuando la relación entre las características y las probabilidades es **lineal**. Si las relaciones son no lineales, puedes mejorar el modelo aplicando **transformaciones** a las variables o añadiendo características polinómicas.
- **Comparación de otros modelos**: A menudo es un **modelo base** contra el cual se comparan otros modelos más complejos, como árboles de decisión o redes neuronales. Aunque estos modelos más complejos pueden ser más precisos, la regresión logística sigue siendo útil por su **simplicidad** e **interpretabilidad**.

### Limitaciones

- **Linealidad**: Como es un clasificador lineal, no captura relaciones no lineales entre las características y el resultado sin algún tipo de transformación de datos.
- **Multicolinealidad**: Si hay alta correlación entre las características, esto puede hacer que los coeficientes sean difíciles de interpretar y disminuir el rendimiento. En estos casos, es recomendable reducir la dimensionalidad.
- **Imbalanced Data**: La regresión logística puede tener problemas si los datos están desbalanceados (por ejemplo, muchas más muestras de una clase que de otra). En estos casos, es importante ajustar los umbrales de clasificación o aplicar técnicas como sobremuestreo o submuestreo.

### Ventajas
- **Facilidad de uso**: La regresión logística es uno de los algoritmos más simples de implementar, especialmente para problemas de clasificación binaria.
- **Interpretabilidad**: Es fácil de interpretar y entender cómo las variables afectan el resultado.
- **Versatilidad**: Aunque es un modelo lineal, es aplicable a muchos tipos de problemas, tanto en áreas científicas como de negocios.