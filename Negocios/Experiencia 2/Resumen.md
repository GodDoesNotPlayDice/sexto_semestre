# Procesos de ETL
Los procesos de Extracción, Transformación y Carga de Datos (ETL), son los encargados de realizar la carga inicial e incremental, desde los sistemas fuentes al Data Warehouse. 
- Se estima que el 70% del esfuerzo de un proyecto de BI, es la construcción de los ETL.

**Puntos a considerar** 
- Perspectiva de Negocio
- Data Quality
- Latencia
- Linaje
- Procesamiento End2End 
- Estadísticas de Carga

![[Pasted image 20240909210911.png]]


# Conceptos
- **Control Flow (Flujo de control)**: Es la parte del paquete de SSIS que define el orden de ejecución de las tareas y los flujos de trabajo en el proceso ETL. Controla el flujo general de los datos y la lógica del paquete.
    
- **Execute SQL Task (Tarea Ejecutar SQL)**: Permite ejecutar comandos SQL, como consultas, procedimientos almacenados o scripts, dentro del flujo de control de un paquete SSIS. Se usa para tareas como crear tablas, actualizar registros o manejar datos en una base de datos.
    
- **Data Flow Task (Tarea de flujo de datos)**: Maneja la extracción, transformación y carga de datos (ETL). Dentro de esta tarea, los datos son movidos y transformados desde orígenes a destinos a través de componentes específicos como transformaciones.
    
- **Data Flow (Flujo de datos)**: Se refiere al proceso interno de ETL dentro de una tarea de flujo de datos, donde se define cómo los datos se extraen de las fuentes, se transforman y se cargan en los destinos.
    
- **Source Assistant (Asistente de orígenes)**: Ayuda a configurar rápidamente un origen de datos dentro de un flujo de datos. Este asistente facilita la conexión a diversas fuentes de datos como bases de datos, archivos o servicios.
    
- **Destination Assistant (Asistente de destinos)**: Similar al asistente de orígenes, pero enfocado en configurar destinos de datos en un flujo de datos. Permite definir rápidamente a dónde se dirigirán los datos transformados, como bases de datos, archivos o sistemas externos.