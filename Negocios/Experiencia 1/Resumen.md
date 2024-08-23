# La información

## Características de la información
- Es intangible
- Al contrario de otros activos no se deprecia con el uso, sino por el contrario, se hace más valioso.
- Se deprecia con la desactualización.
- Es un activo que fluye por la organización.

## Características de los datos
- Es una representación simbólica de un atributo o variable.
- Son registros almacenados en algún contexto particular.
- Pueden ser cuantitativos o cualitativos. 
- Se almacenan de forma estructurada, semi estructurada o no estructurada.
- Hoy en día todo contiene flujo de datos.

Un ejemplo de datos seria esta tabla.

| Fecha      | Codigo  | Sucursal     | Monto |
| ---------- | ------- | ------------ | ----- |
| 2019-07-19 | AACFD12 | Viña del Mar | 10000 |
| 2019-07-19 | AACFD13 | Viña del Mar | 5000  |
| 2019-07-21 | AACFD21 | Viña del Mar | 25000 |
| 2019-07-21 | AACFD22 | Valparaíso   | 12000 |
| 2019-07-21 | AACFD23 | Valparaíso   | 16000 |

Si los datos no son tratados no sirven para generar información ni mucho menos conocimiento.


# Piramide del conocimiento

Representa una jerarquía de cómo los datos se transforman en comprensión compartida a través de diferentes niveles de procesamiento mental:

1. **Datos (Data)**: Son los hechos y cifras crudos, sin procesar. Es la base de la pirámide.
    
2. **Información (Information)**: Los datos se procesan para que tengan sentido y se conviertan en información. Es un paso más avanzado que los datos puros.
    
3. **Conocimiento (Knowledge)**: Cuando la información se analiza y se comprende, se convierte en conocimiento. Aquí entra en juego la cognición, que es el proceso mental de entender y aprender a partir de la información.
    
4. **Juicio (Judgment)**: A partir del conocimiento, usamos nuestro juicio para tomar decisiones informadas. Es la capacidad de valorar y tomar decisiones basadas en el conocimiento que hemos adquirido.
    
5. **Comprensión compartida (Shared Understanding)**: En la cima de la pirámide, el juicio y el conocimiento se combinan para crear una comprensión compartida. Esto es cuando un grupo de personas llega a un acuerdo común o a un entendimiento colectivo sobre un tema.
![[Pasted image 20240813143728.png]]

# Que es la Inteligencia de negocio
La inteligencia de negocio es un conjunto de metodologías, aplicaciones y tecnologías que permiten reunir, depurar y transformar datos de los sistemas transaccionales e información desestructurada en información estructurada, para producir información y conocimientos que optimicen la toma de decisiones de negocio en una organización.

En resumen la inteligencia de negocio es el conjunto de herramientas para poder obtener información desde los datos.

> “Business intelligence (BI) es un termino que agrupa aplicaciones, infraestructura y herramientas y las mejores practicas que permiten el acceso y análisis de la información pero mejorar y optimizar la toma de decisiones y gestión del desempeño.” -  Gartner.

## Porque inteligencia de negocio?
- **Toma de decisiones**: Ayuda a tomar decisiones más informadas y acertadas.
- **Eficiencia**: Permite optimizar procesos y recursos.
- **Competitividad**: Aporta ventajas competitivas.
- **Identificar oportunidades**: Ayuda a identificar oportunidades de negocio.

> “BI puede tener un impacto directo y positivo sobre el rendimiento de una empresa, mejorando significativamente su capacidad a cumplir sus objetivos a través de la mejora de la toma de las decisiones en todos los niveles del negocio, desde la estrategia corporativa hasta los procesos operacionales". - Gartner.

![[Pasted image 20240813145137.png]]
#  DataWherehouse

Un data warehouse es un sistema de almacenamiento de datos orientado a temas, que integra, consolida y depura datos de una o varias fuentes diferentes para su análisis y generación de informes y están almacenadas en un repositorio central de la empresa.

### Arquitectura
1. **Diversas** fuentes de datos, que generalmente contienen los datos transaccionales u operacionales de la organización.
2. **Procesos** de Extracción, Transformación y Carga de Datos (**ETL**) 
3. Data Warehouse o almacén de datos
4. Capa de explotación, la cual puede ser representada como reportes, minería de datos o herramientas **OLAP** (Procesamiento Analítico en Línea).


![[Pasted image 20240819201621.png]]

### Fuentes
**BDR  (Base de datos relacional)**: Tienen una estructura de datos que permite relacionar la información de diferentes tablas. Como por ejemplo (Excel, Access, SQL Server, Oracle, MySQL, PostgreSQL, etc.)

**ERP TL (Extracción, Transformación y Carga)**:  Son procesos que permiten extraer datos de diferentes fuentes, transformarlos y cargarlos en un data warehouse.

**CRM (Customer Relationship Management)** : Son sistemas que permiten gestionar la relación con los clientes, como por ejemplo, ventas, marketing, atención al cliente, etc.

**Sistema transaccionales**:  Son sistemas que permiten realizar operaciones de negocio, como por ejemplo, ventas, compras, inventario, etc.

### Proceso ETL
Son pasadas por un proceso de ETL (Extracción, Transformación y Carga) para ser almacenadas en un data warehouse.

### Modelo dimensional (DW, DM)
Es un modelo de datos que se utiliza en data warehouse y se compone de tablas de hechos y tablas de dimensiones.
**Características**:
- Panel de control
- OLAP
- Mininería de datos

## Arquitectura de un DWH en Big Data.
En esta arquitectura se incorpora al ecosistema un repositorio de Big Data, para capturar datos **semiestructurados** o no **estructurados**.
![[Pasted image 20240819202131.png]]



## Estrategia para desarrollar un DWH
### Enfoque de Data Warehouse Corporativo
- **Top-down**
- **Metodología de Bill Inmon (Padre del DWH)**

![[Pasted image 20240819203251.png]]

### Enfoque de Data Mart
- **Bottom-up**
- **Metodología de Ralph Kimball (Padre del BI)**
![[Pasted image 20240819203342.png]]


## Moldeamiento Dimensional Kimball
Es una técnica de diseño de bases de datos que se utiliza en data warehouse y se compone de tablas de hechos y tablas de dimensiones.
- **Elegir el proceso de negocio**
	- Proceso de Venta
	- Proceso de Compras
	- Proceso de Selección de Personal
- **Establecer el nivel de granularidad**
	- Definir el nivel de detalle que se desea almacenar los datos del proceso.Elegir las dimensiones
	- Depende de los requerimientos del negocio y los datos que existe en los sistemas que soportan el proceso
	- La sugerencia es comenzar a diseñar el DW al mayor nivel de detalle posible
	- Se puede luego realizar Sumarizaciones (Agregaciones) al nivel deseado
- **Elegir las dimensiones**
	- Surgen naturalmente de las sesiones de análisis y facilitadas por la elección del nivel de granularidad y de la matriz de procesos/dimensiones, todo lo que nos permite analizar el proceso.
	- **Ejemplo**:
		- **Tiempo**: ¿cuándo se produce la actividad?
		- **Producto**: ¿cuál es el objeto de la actividad?
		- **Almacén**: ¿dónde se produce la actividad?
		- **Cliente**: ¿quién es el destinatario de la actividad?
- **Identificar medidas y las tablas de hechos**
	- Decidir la información a almacenar sobre el proceso.
	- **Hechos**: información (sobre la actividad) que se desea almacenar en cada registro de la tabla de hechos y que será objeto del análisis.
	- **Ejemplo:** cantidades, sumas, maximos...
		- Métricas Directas:
			- Unidades Vendidas
			- Monto Vendido
			- Monto Pago
			- Puntos
			- Vuelto
		- Métricas del Contexto
			- Costo Venta
			- Margen Venta


## Diseño Físico
Minimo son dos dimensiones.

### Esquema Estrella
Es un esquema de diseño de bases de datos que se utiliza en data warehouse y se compone de una tabla de hechos y varias tablas de dimensiones.
**Caracteristicas**:
- El centro del modelo es la tabla de hechos (Fact Table).
- Alrededor de la tabla de hechos se organizan las tablas de Dimensiones (Dimension Table)
- La tabla de hechos de arma en base a las Primary Key de cada tabla de dimensión y con atributos numéricos (medidas), que corresponden a los valores medibles sobre el proceso que se está modelando.
- Se sugiere que cada dimensión tenga como Primary Key un clave subrogada, para independizarla de cambios del negocio o para generar distintas versiones de la información (Slowly Changing Dimension)
- Las Dimensiones se utilizan para filtrar o agrupar las medidas

![[Pasted image 20240819204246.png]]


#### **Centro del Análisis métricas:**

- **Tabla de Hechos:** En el modelo estrella, las métricas o medidas cuantitativas (como ventas, ingresos, cantidad vendida) se almacenan en la tabla de hechos, que está en el centro del modelo. Las tablas de dimensiones rodean la tabla de hechos y proporcionan contexto para interpretar estas métricas.
2. **Toma de Decisiones Basada en Datos:**

- Las métricas proporcionan los datos cuantitativos necesarios para la toma de decisiones informada. Por ejemplo, una métrica de ingresos por ventas permite a los gerentes evaluar el rendimiento financiero y tomar decisiones sobre estrategias de precios, marketing y ventas.
3. **Rendimiento y Comparación:**

- Las métricas permiten comparar el rendimiento a lo largo del tiempo, entre diferentes regiones, productos o cualquier otra dimensión. Esto ayuda a identificar patrones, tendencias y áreas que requieren atención o mejora.

4. **Facilita el Análisis Multidimensional:**

- Al estar integradas en un modelo estrella, las métricas pueden ser analizadas desde múltiples perspectivas (dimensiones), como tiempo, ubicación, producto, cliente, etc. Esto permite a los usuarios de negocio entender el rendimiento en diferentes contextos y niveles de detalle.

5. **Optimización y Mejora Continua:**

- Las métricas proporcionan indicadores clave que permiten a las empresas medir el éxito de sus operaciones y estrategias. Al monitorear y analizar estas métricas, las organizaciones pueden identificar oportunidades para optimizar procesos y mejorar el desempeño general.

6. **Simplicidad y Eficiencia:**

- En el modelo estrella, las métricas están organizadas de manera que las consultas sean rápidas y eficientes, lo que facilita el acceso a la información clave sin necesidad de realizar operaciones complejas en la base de datos.




### Esquema Copo de Nieve
Es un esquema de diseño de bases de datos que se utiliza en data warehouse y se compone de una tabla de hechos y varias tablas de dimensiones.
**Caracteristicas**:
- Es una extensión del modelo Estrella.
- Cada dimensión se normaliza, por lo que cada nivel (atributo) se lleva a una tabla (Lookup Table)

![[Pasted image 20240819204327.png]]

| Estrella          | Copo de Nieve     |
|-------------------|-------------------|
| Mayor espacio     | Menos espacio     |
| Menos Join        | Más flexible      |
| Menos flexible    |                   |

# SQL Server 2019

1) Conectar con el usuario windows
2) Crear una base de datos, crear tablas, etc
3) Guardar backup → BD → Tasks → Backup ⇒
	1) `C:\Program Files\Microsoft SQL Server\MSSQL15.MSSQLSERVER\MSSQL\Backup`

