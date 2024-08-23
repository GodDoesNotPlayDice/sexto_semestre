**Objetivo**: Identificar tabla de **hecho**, dimensiones y medidas.

**Caso Americans.**
La empresa de ventas de productos para mascotas _“Americans”_ lo ha seleccionado a usted y su equipo de trabajo para que los asesoren en la construcción de un Data Warehouse que los ayude a mejorar su proceso de toma de decisiones generar un mejor conocimiento de sus clientes.


Algunas de las preguntas de negocio que buscan responder los ejecutivos son:
- Cantidad de productos vendidos.
- Ingresos por los distintos canales.
- Montos por vendedor.
- En qué meses se vende más.


Aplicar y documentar los 4 pasos del modelamiento dimensional:
- Elegir el proceso de negocio.
- Establecer el nivel de granularidad.
- Elegir las dimensiones.
- Identificar medidas o métricas y la tabla hechos.

## 1. Elegir el proceso de negocio.
Seleccionar el proceso de negocio es seleccionar un **proceso relevante para la organización** ,en vez de tratar cada pregunta por separado, se pueden ver como diferentes ángulos o aspectos que deseas analizar dentro del proceso general de **Ventas**. Esto permite un enfoque más integrado y coherente en el modelado dimensional.





## 2. Establecer el nivel de granularidad.
En el modelamiento **Kimball**, la granularidad se refiere al nivel de detalle de los datos almacenados en una tabla de hechos. Es básicamente cuán específicos o desglosados son los datos que vas a analizar.
### ¿Por qué es importante?
La granularidad determina qué preguntas puedes responder con tus datos. Si la granularidad es alta, puedes hacer preguntas muy específicas, como "¿Cuántos libros vendimos a las 10:00 AM el 1 de agosto?". Si la granularidad es baja, podrías hacer preguntas más generales, como "¿Cuánto vendimos en todo el día el 1 de agosto?".

Definir que puedo relacionar con las Dimensiones seleccionadas.

- **Alta Granularidad (Muy Detallada):**
    - Cada fila de la tabla representa la venta de **un solo producto** en una **única transacción**.
    - Por ejemplo, una venta específica de un libro en particular realizada a las 10:00 AM el 1 de agosto por un cliente llamado Juan.
- **Baja Granularidad (Menos Detallada):**
    - Cada fila de la tabla representa las ventas **totales del día** en la tienda.
    - Por ejemplo, la suma total de todos los productos vendidos el 1 de agosto.


## 3. Elegir las dimensiones.
Las **dimensiones** son tablas que contienen información descriptiva sobre los aspectos del negocio que se quieren analizar, como productos, tiempo, clientes, vendedores, entre otros. Estas tablas se enlazan con la tabla de hechos para permitir el análisis detallado de las métricas.

Las dimensiones **están relacionadas con la tabla de hechos porque proporcionan el contexto necesario para entender y analizar los datos cuantitativos** (como los ingresos) en detalle. Sin estas relaciones, no podrías desglosar y explorar los datos de manera efectiva.

### Dimensiones encontradas.
**D_PRODUCTO**
**D_CANAL**
**D_VENDEDOR**
**D_TIEMPO**
**D_CLIENTE**
**D_UBICACIÓN**: es un combinado de tablas, se usan las descripciones porque es mas rápido que el codigo id.
- `region nvarchar(255)`
- `provincia nvarchar(255)`
- `ciudad_comuna nvarchar(255)`
- `nombre_sucursal(255)`

## 4.  Identificar medidas o métricas y la tabla hechos.
**Métricas Directas**: Estas son las métricas que se obtienen directamente de la tabla de hechos sin necesidad de cálculos adicionales complejos. Representan los valores que estás midiendo directamente.

**Métricas de Contexto**: Son métricas que se calculan a partir de las métricas directas y que proporcionan un contexto adicional sobre los datos. Por ejemplo, el promedio de ventas diarias, la suma de ventas por mes, etc.


**En general**: las métricas se pueden definir por se cuantificables y calculadas a posterior, además las métricas van dentro de la tabla **hechos**, eso si una excepción puede ser la fecha.

**Métricas encontradas**: Cantidad, Total, Precio unitario, Costo unitario, Total neto, Impuesto, Total documento