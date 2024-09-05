# Modelo Kimball
## Identificar el Proceso de Negocio
- Proceso Ordenes
## Identificar Nivel de Granularidad
- **Orden: Identificador único de la orden.**
    - **Justificación**: Este campo es esencial para identificar cada transacción individualmente. Permite rastrear la totalidad de una orden y sus componentes, relacionando cada producto vendido con la orden específica. Esto es crucial para evaluar el desempeño de cada orden y su impacto en las métricas generales de la empresa.
- **Producto: El producto específico que se vendió.**
    - **Justificación**: Incluir el detalle de cada producto vendido en la orden es fundamental para comprender cuáles productos están generando más ingresos, cuáles se venden más frecuentemente, y cuáles requieren atención especial (por ejemplo, promociones o ajustes de precio). Este nivel de detalle permite un análisis del rendimiento a nivel de producto.
- **Cantidad: Número de unidades del producto vendido en la orden.**
    - **Justificación**: La cantidad vendida es una métrica clave para medir la demanda de cada producto y es esencial para cálculos de ingresos y evaluación de inventario. Ayuda a cuantificar el volumen de ventas y a proyectar necesidades de producción o reabastecimiento.
- **Descuento: Descuento aplicado a ese producto específico en la orden.**
    - **Justificación**: Registrar los descuentos a nivel de producto permite analizar el impacto de estrategias de descuento en las ventas y en los márgenes de ganancia. Es crucial para evaluar si los descuentos están incentivando ventas adicionales o erosionando los ingresos sin aportar valor.
- **Precio Unitario: Precio por unidad del producto vendido.**
    - **Justificación**: El precio unitario es esencial para calcular el valor de las ventas y para analizar la rentabilidad de cada producto. Tener esta métrica a nivel de producto permite determinar los ingresos generados por cada venta y evaluar la efectividad de la política de precio
## Identificar Dimensiones
- D_Transportistas 
	- id_transportista (int)
	- transportista (nvarchar(40))
	- telefono (nvarchar(24))
- D_Clientes 
	- id_cliente (nvarchar(5))
	- telefono  (nvarchar(24))
	- pais  (nvarchar(15))
	- codigo_postal  (nvarchar(10))
	- ciudad  (nvarchar(15))
	- direccion  (nvarchar(60))
	- contacto  (nvarchar(30))
	- empresa  (nvarchar(40))
- D_Empleados
	- id_empleado (int)
	- nombre  (nvarchar(10))
	- apellido  (nvarchar(20))
	- cargo  (nvarchar(30))
	- fecha de nacimiento  (datetime)
	- fecha de contratacion (datetime)
	- direccion  (nvarchar(60))
	- pais  (nvarchar(15))
- D_Ubicación 
	- id_ubicacion (int)
	- territorio  (nvarchar(50))
	- region  (nvarchar(50))
	- pais (nvarchar(15)) 
	- ciudad (nvarchar(60))
	- direccion (nvarchar(60))
- D_Productos 
	- id_producto (int)
	- producto  (nvarchar(40))
	- categoria  (nvarchar(15))
	- descripción (ntext)
- D_Tiempo
	- fecha
## Identificar Métricas y Tabla de Hechos
Tabla Hechos: **H_ORDEN**
**Métricas**:
- precio_unitario (money)
- cantidad (smallint)
- descuento (real)

## KPI
preguntas con enfoque estrategico
- Ejemplo: ¿Cuál es el producto más vendido? -> que hacer? -> aumentar la producción.


Que valor usamos de pk en la dimension tiempo?
- Agregar metricas de tiempo (dia, mes, año, etc)
Los tipos de datos estan bien en la tablas?
- XD
El nivel de granularidad esta bien?
- Corregir algunas granularidades redundantes
Las dimensiones modeladas son las correctas?
- Remplazar la D_Ubicación por otra.

