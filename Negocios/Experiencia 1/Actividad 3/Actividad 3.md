**Desarrollo**:
La Escuela de Informática y Telecomunicaciones de DUOC UC ha solicitado a la biblioteca un listado de los libros solicitados por los alumnos de las carreras de la escuela en las diferentes sedes en diferentes períodos de tiempo. 

Ud. ha sido contratado para aplicar Inteligencia de Negocios y generar un modelo dimensional que permita generar los siguientes reportes.

- **Clasificación** de los **libros** por **categoría**.
- **Distribución** de los **alumnos** por **sede** y **carrera**.
- **Tipos** de **libros solicitados** por los **alumnos** (**papel** o **digital**).
- **Préstamos** de libros por alumno y **período de tiempo.**
- **Cantidad** de libros prestados de **manera semestral y anual.**

**Tabla hecho**: H_PRESTAMOS
**Dimensiones:** D_Tiempo, D_Alumnos, D_Categoria, D_Libro, D_Sede, D_Tipo, D_Comuna
**Metricas**: cantidad_libros_presados, total_libros 