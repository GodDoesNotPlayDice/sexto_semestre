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

En resumen, el modelo toma las características de entrada, las combina linealmente y aplica la función sigmoide para generar una probabilidad. Si esa probabilidad supera el umbral, se clasifica como positiva; de lo contrario, como negativa

