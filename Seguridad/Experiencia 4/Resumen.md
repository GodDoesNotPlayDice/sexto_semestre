# Gestión de Riesgos

**Riesgo**: Un riesgo es el potencial de que una amenaza pueda explotar alguna debilidad o algún fallo, sea de diseño, implementación o configuración, la cual se aplica en una fórmula muy sencilla que tenemos a continuación

```
Riesgo = Amenaza * Vulnerabilidad * Impacto
```

Para esto existe la gestión de riesgos, que es un proceso interactivo que emite identificar cuáles son esos riesgos, evaluar esos riesgos y cómo vamos a responder a esos riesgos.

## Identificación de los activos críticos
Para optimizar costos, no es viable proteger todos los activos de manera uniforme, por lo que es fundamental identificar aquellos que son críticos. Esta identificación debe basarse en un enfoque empresarial, evaluando el impacto que la pérdida o degradación de cada activo tendría en la organización en su conjunto. Así, los recursos y medidas de protección se pueden priorizar en función de su importancia para el negocio.

## Identificación del riesgo
- **Riesgos ambientales y humanos**: Considerar tanto los riesgos que provienen del entorno como los que son causados por personas.
    
- **Accidentes internos**: Pueden ocurrir por errores humanos o por configuraciones incorrectas hechas por personal sin la capacitación adecuada.
    
- **Amenazas humanas**: Cuando las personas son una amenaza, es importante identificar quiénes son, cuáles son sus motivos y los medios que pueden utilizar para causar daño.


## Evaluación del impacto
Es necesario relacionar cada riesgo con uno o más de los componentes arquitectónicos y determinar el impacto potencial de la amenaza sobre el activo.

## Tratamiento del riesgo
Esta actividad se basa en la planificación e implementación del mejor curso de acción: la aceptación del riesgo actual; la gestión activa del riesgo; la observación de cambios en las características del riesgo.
_Además se debe destinar una mayor investigación sobre el riesgo hasta que se sepa lo suficiente para aplicar adecuadamente una de las alternativas de planificación._

## Notificación de riesgos
¿Quién debe tener conocimiento de los riesgos? ¿Quién debe tener conocimiento de los incidentes? ¿Quién debe tener conocimiento de las amenazas que se presentan?

## Intercambio de información
¿Que información debe intercambiarse?, ¿Cómo se realiza el intercambio?, ¿Cuáles son las restricciones para el intercambio?, ¿Deberán los datos hacerse anónimos antes de ser intercambiados?

## Monitoreo/Auditoría
¿Es necesario realizar auditorías internas? , ¿Es necesario contar con auditores externos?, ¿Imponen auditorías los órganos reguladores? , ¿Deben realizarse auditorías de los accionistas?

## Entorno reglamentario/legislativo
¿Cuál es el marco reglamentario? , ¿Qué leyes deben seguirse? , ¿Qué requisitos de seguridad imponen los órganos externos?

# Terminología
- **Vulnerabilidad**:
    - Debilidad de implementación.
    - Debilidad en procedimientos.
    - Oportunidad de ataques.
- **Exploit**:
    - Ataque real.
    - Ataque ejecutado.
    - Proceso de ataque identificado.
- **Amenaza**:
    - Cualquier circunstancia que afecte a:
        - Confidencialidad.
        - Integridad.
        - Disponibilidad.
- **Límite de confianza**:
    - Cambia en todos los sistemas.
    - Potencia el espacio de amenazas.
    - Línea para la suplantación.
- **Superficie de ataque**:
    - Puntos de entrada a vectores de ataques.
    - Contiene activos de la empresa.
    - Contiene personas y procesos.
- **Riesgo**:
    - Nivel de impacto.
    - Cuantitativo / cualitativo.
    - Probabilidad de que ocurra.
- **Mitigar**:
    - Disminuir el impacto del problema de seguridad.
    - Implementar mecanismos para reducir la probabilidad de que ocurra un riesgo.
- **Eliminar**:
    - Corregir las causas raíz de un problema de seguridad.
    - Modificar y corregir problemas para evitar futuros riesgos.
- **Transferir**:
    - Transferir el riesgo a terceros cuando es más económico.
    - No elimina el riesgo, pero reduce su impacto.
- **Aceptar**:
    - Decidir vivir con el riesgo cuando su impacto es asumible.
    - Se acepta cuando el costo de mitigarlo o eliminarlo es mayor que el impacto potencial.



## Enfoques comunes del modelado de amenazas

### Software
Centrado en la representación arquitectónica e identificación del flujo de datos, además de establecer su estado en el tiempo y poder identificar entradas y salidas

### Activos
Centrado en la identificación, conocimiento y significado de los activos, ¿Qué sucedería si alguien obtiene esta información? Quizás no sean tan importantes para el modelo de negocio de la empresa

### Atacante
Centrado en herramientas, procedimientos y formas de ataque, es especialista en conocer todo lo último en ataques y a partir de esos ataques se identifica cuáles podría aplicar a nuestro sistema.


### Centrado en activos
Se focaliza en el análisis respecto a los activos a los cuales se pueden acceder
Se trata de explicar que consecuencias e impacto tiene el uso de estos datos
Pregunta constante ¿Qué pasaría si acceden a X?


### Metodología modelo de amenazas
**Microsoft Threat modeling**
**PASTA (Process for Attack Simulation and Threat Analysis)**
**Trike**
**VAST (Visual Agile Simple Threat Modeling)**
**OCTAVE (Operation Critical Threat Asset and Vunerability Evaluation)**


# Modelamiento de amenazas
El objetivo del modelado de amenazas es entender la naturaleza cambiante de la seguridad y reconocer los procesos fundamentales involucrados. La seguridad es dinámica y se debe a cuatro factores principales:

1. **Ataques frecuentes que evolucionan**.
2. **Defensas comúnmente reactivas**.
3. **Tipos de ataques emergentes**.
4. **Motivación de los atacantes**.

Dado que la seguridad no es estática, lo que funciona hoy podría no ser efectivo mañana, ya que los atacantes constantemente buscan nuevas formas de vulnerar los sistemas. Esta dinámica no solo involucra la tecnología, sino también los procesos y los factores humanos, ya que los ataques pueden enfocarse en manipular o transformar la información.

- **Etapas del modelado de amenazas**:
    
    - **Descomponer**: Analizar a fondo el sistema para entender sus componentes. Esto incluye identificar puntos de entrada y vulnerabilidades.
    - **Identificar**: Una vez descompuesto el sistema, se detectan posibles amenazas basándose en lo que se descubrió en la primera etapa.
    - **Mitigar**: Implementar medidas de seguridad para reducir o eliminar el riesgo identificado.
- **Ejemplo práctico**:
    
    - Imagina un almacén que tiene puertas y ventanas que pueden ser vulnerables.
    - Amenazas identificadas: alguien podría retirar los cerrojos, forzar las puertas o incluso entrar por las ventanas.
    - Soluciones propuestas: instalar alarmas, sensores, cámaras y cercas para disuadir a los intrusos. También se considera proteger el almacén de incendios y daños por lluvia.
- **Consideraciones finales**:
    
    - Las contramedidas a implementar dependen de los recursos disponibles, la experiencia del equipo y el valor de lo que se está protegiendo.
    - No siempre es necesario implementar todas las soluciones; a veces es más práctico enfocarse solo en proteger los activos más importantes.
# Segregación de grupos

- **Roles en la seguridad del software**:
    
    - **Equipo de seguridad**: Responsable de integrar los procesos de modelado de amenazas a lo largo del ciclo de vida del software.
    - **Hackers éticos y testers**: Se centran en asegurar el sistema de forma preventiva, mejorando la precisión en la detección de posibles ataques.
    - **Arquitectos y líderes de proyecto**: Encargados de integrar la seguridad desde el diseño arquitectónico, tomando decisiones sobre la tecnología y los procesos a utilizar.
- **Estrategia proactiva**:
    
    - La idea es actuar temprano para prevenir problemas de seguridad en lugar de esperar a que sucedan (enfoque reactivo).
    - Al integrar el modelado de amenazas desde el inicio, se logra una postura proactiva que refuerza la robustez y disponibilidad del sistema.
- **Beneficios**:
    
    - Evitar problemas de seguridad antes de que ocurran, mejorando la calidad del software.
    - Adoptar un enfoque preventivo permite proteger mejor los sistemas y reducir riesgos.

