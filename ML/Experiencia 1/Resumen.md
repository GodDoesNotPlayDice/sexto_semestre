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
**Determinación de objetivos:** Establece los posibles resultados a obtener al proponer la solución.
**Evaluación de la situación actual:** Describe el estado actual antes de ser implementada la solución propuesta, con el fin de tener un objeto de comparación que permita medir el grado de éxito del proyecto.

### Data Understanding
**Comprensión de los datos:** Comprende la recolección inicial de datos, con el objetivo de establecer un primer acercamiento con el problema, conociendo a los datos, identificando su calidad y estableciendo las primeras relaciones que permitan definir correlaciones entre variables.

#### Actividades
**Recolección de datos:** Consiste en obtener los datos a utilizar en el proyecto a partir de algunas fuentes de datos, e identificando las técnicas utilizadas para su recolección.
**Exploración de datos:** Se basa en aplicar pruebas estadísticas que permitan conocer las propiedades de los datos.


### Data Preparation
**Preparación de datos:** Esta es la etapa que demanda más tiempo en el proyecto, aquí se seleccionan los datos que serán transformados de acuerdo con los resultados de la etapa anterior a fin de ser utilizados en la etapa de modelado. 

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
