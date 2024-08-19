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

> “Business intelligence (BI) es un termino que agrupa aplicaciones, infraestructura y herramientas y las mejores practicas que permiten el acceso y análisis de la información pero mejorar y optimizar la toma de decisiones y gestión del desempeño.” -  Gartner.

## Porque inteligencia de negocio?
- **Toma de decisiones**: Ayuda a tomar decisiones más informadas y acertadas.
- **Eficiencia**: Permite optimizar procesos y recursos.
- **Competitividad**: Aporta ventajas competitivas.
- **Identificar oportunidades**: Ayuda a identificar oportunidades de negocio.

> “BI puede tener un impacto directo y positivo sobre el rendimiento de una empresa, mejorando significativamente su capacidad a cumplir sus objetivos a través de la mejora de la toma de las decisiones en todos los niveles del negocio, desde la estrategia corporativa hasta los procesos operacionales". - Gartner.

![[Pasted image 20240813145137.png]]
## Que es un data warehouse
Un data warehouse es un sistema de almacenamiento de datos orientado a temas, que integra, consolida y depura datos de una o varias fuentes diferentes para su análisis y generación de informes y están almacenadas en un repositorio central de la empresa.

### Fuentes
**BDR  (Base de datos relacional)**: Tienen una estructura de datos que permite relacionar la información de diferentes tablas. Como por ejemplo (Excel, Access, SQL Server, Oracle, MySQL, PostgreSQL, etc.)

**ERP TL (Extracción, Transformación y Carga)**:  Son procesos que permiten extraer datos de diferentes fuentes, transformarlos y cargarlos en un data warehouse.

**CRM (Customer Relationship Management)** : Son sistemas que permiten gestionar la relación con los clientes, como por ejemplo, ventas, marketing, atención al cliente, etc.

**Sistema transaccionales**:  Son sistemas que permiten realizar operaciones de negocio, como por ejemplo, ventas, compras, inventario, etc.

Son pasadas por un proceso de ETL (Extracción, Transformación y Carga) para ser almacenadas en un data warehouse.

### Modelo dimensional (DW, DM)
Es un modelo de datos que se utiliza en data warehouse y se compone de tablas de hechos y tablas de dimensiones.
**Características**:
- Panel de control
- OLAP
- Mininería de datos
