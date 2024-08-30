**Desarrollo**:
La Escuela de Informática y Telecomunicaciones de DUOC UC ha solicitado a la biblioteca un listado de los libros solicitados por los alumnos de las carreras de la escuela en las diferentes sedes en diferentes períodos de tiempo. 

Ud. ha sido contratado para aplicar Inteligencia de Negocios y generar un modelo dimensional que permita generar los siguientes reportes.

- **Clasificación** de los **libros** por **categoría**.
- **Distribución** de los **alumnos** por **sede** y **carrera**.
- **Tipos** de **libros solicitados** por los **alumnos** (**papel** o **digital**).
- **Préstamos** de libros por alumno y **período de tiempo.**
- **Cantidad** de libros prestados de **manera semestral y anual.**

**Tabla hecho**: H_PRESTAMOS
**Granularidad**: 
- Los libros que se prestaron La categoría de los libros prestados
- El tipo de libro prestado El alumno que solicito el libro
- La sede que pertenece el alumno 
- La carrera que esta cursando el alumno
- Cuando el alumno solicito el préstamo
**Dimensiones:** D_Tiempo, D_Alumnos, D_Categoría, D_Libro, D_Sede, D_Tipo, D_Carrera

**Métricas**: días_retraso (int), dias_prestados (int), cant_prestados_semestral (int), cant_prestados_anual (int)



# Concepto Base para Identificar Métricas:
El proceso de identificar y validar métricas se basa en entender el negocio, definir correctamente la granularidad del hecho y asegurarse de que cada métrica aporte un valor cuantificable y relevante al análisis de ese evento. Las métricas deben reflejar aspectos medibles del proceso que ayuden a evaluar y optimizar el sistema, garantizando su alineación con los objetivos del negocio.

## Entender el proceso de negocio:
El primer paso es comprender **detalladamente** el **proceso** de **negocio** que estás modelando. En este caso, es el proceso de préstamo de libros en una biblioteca.
- Pregunta clave: **¿Qué acciones o eventos están ocurriendo?** Aquí, se presta un libro a un alumno, lo devuelve, y puede ocurrir con o sin retraso.

## Definir la granularidad del Hecho.
La granularidad determina el nivel de detalle de los datos en la tabla de hechos. Debe estar claro qué representa cada registro en la tabla de hechos. Para `H_PRESTAMO`, cada registro representa un préstamo individual de un libro.
- Pregunta clave: **¿Qué nivel de detalle necesito?** Aquí, necesitamos registrar cada préstamo individual.

## Identificar las métricas cuantitativas del Evento:
Una métrica directa es una medida cuantificable que surge del evento que estás registrando en la tabla de hechos.
- Pregunta clave: **¿Qué se puede contar, medir o calcular directamente en cada evento?**
	- Ejemplos: Número de libros prestados (`cant_libros_prestados`), días de préstamo (`dias_prestados`).

## Evaluar métricas de rendimiento y comportamiento.
Son métricas que reflejan el desempeño del proceso o el comportamiento del usuario.
- Pregunta clave: **¿Qué se puede contar, medir o calcular directamente en cada evento?**
	- Ejemplos: Número de libros prestados (`cant_libros_prestados`), días de préstamo (`dias_prestados`).

## Buscar Métricas que Impacten en la Toma de Decisiones:
- Las métricas deben ser relevantes para la toma de decisiones estratégicas o operativas. Pregunta clave: **¿Esta métrica ayuda a mejorar o evaluar el proceso?**
    - Ejemplos: Multa aplicada (`monto_multa`) para evaluar la puntualidad, o `calificacion_servicio` para medir la satisfacción del usuario.

## Considerar Métricas que Reflejen la Calidad y Eficiencia del Servicio:
 Métricas como `dias_anticipados` o `monto_multa` reflejan la eficiencia del servicio y pueden ser usadas para mejorar políticas de préstamo.


## Métricas de Contexto:
Aunque no siempre se almacenan directamente, métricas de contexto proporcionan información adicional sobre las circunstancias del evento.
- Pregunta clave: **¿Qué contexto rodea al evento que pueda influir en su análisis?**
    - Ejemplo: `cantidad_reservas` indica la popularidad y demanda de un libro antes del préstamo.


## Validación de Métricas:
Para validar que una métrica es relevante y debe estar en la tabla de hechos:

- **Relación con el Hecho**: La métrica debe estar directamente relacionada con el evento de la tabla.
- **Medible**: Debe ser cuantificable y registrable en el momento del evento.
- **Relevancia**: Debe aportar valor en el análisis del proceso, permitiendo evaluar, mejorar o entender el comportamiento del negocio.
- **No Derivable**: Idealmente, las métricas directas no deberían ser fácilmente derivables de otras métricas ya presentes, para evitar redundancia.
