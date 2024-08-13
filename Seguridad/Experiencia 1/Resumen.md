
# PPT1

## Dimensiones de la Seguridad
Las **dimensiones de la Seguridad** son aspectos esenciales que aseguran la protección de la información en un sistema de información y comunicaciones:

1. **Confidencialidad**: Asegura que solo personas o procesos autorizados puedan acceder a la información.
2. **Integridad**: Garantiza que la información no ha sido alterada de manera no autorizada y que cualquier modificación pueda ser detectada.
3. **Disponibilidad**: Asegura que la información esté accesible cuando los usuarios autorizados la necesiten.
4. **Autenticidad**: Verifica la identidad del usuario que genera o envía la información.
5. **Trazabilidad**: Permite rastrear quién realizó una acción específica y cuándo lo hizo.

### Conservación y acceso de la información
La **conservación de la información** es crucial y debe gestionarse de manera independiente, ya que es parte esencial del ciclo de vida de la información. Es necesario asegurar que toda la información se conserve adecuadamente durante todo su ciclo de vida. Para lograrlo, la gestión de dispositivos, soportes electrónicos y formatos debe seguir procedimientos específicos que garanticen su preservación.

Además, el **acceso** a la información se refiere a la capacidad de utilizar los sistemas necesarios para obtener esa información.

**Donde**: La información en los sistemas de información y comunicaciones debe protegerse en todas sus dimensiones (confidencialidad, integridad, disponibilidad, etc.) para garantizar la seguridad global del sistema y cumplir con los objetivos de la organización.

**Como**: Las amenazas a la información deben contrarrestarse mediante controles que reduzcan la probabilidad de que ocurran, minimicen su impacto, permitan una recuperación rápida y adapten los controles según la experiencia previa.

**Cuando**: La información debe protegerse en todas las etapas de su ciclo de vida, desde su ingreso en el sistema hasta su destrucción, incluyendo su almacenamiento, procesamiento, transmisión y utilización.


## Seguridad de la Información y Ciberseguridad

### Ques la Ciberseguridad
Es la práctica de defender, **con tecnologías o prácticas ofensivas**, las computadoras, los servidores, los dispositivos móviles, los sistemas electrónicos, las redes y los datos de ataques maliciosos llevados a cabo por cibercriminales.

**Objetivo**: Su objetivo es proteger la información digital en los sistemas interconectados. 

### Seguridad de la Información y Ciberseguridad
La **Seguridad de la Información** tiene un alcance de proteger la información de riesgos que puedan afectarla, en sus diferentes formas y estados. 

Por el contrario, la **Ciberseguridad** se enfoca principalmente en la información en formato digital y los sistemas interconectados que la procesan, almacenan o transmiten, por lo que tiene un mayor acercamiento con la Seguridad Informática.


## Problemas de las Dimensiones

### Algunas definiciones de Seguridad
**Amenaza**: cualquier circunstancia o evento  que pueda explotar, intencionalmente o no, una vulnerabilidad especifica de un sistema de información y comunicaciones, resultando en una perdida de confidencialidad, integridad, disponibilidad, autenticidad o trazabilidad de la información manejada o de la integridad o disponibilidad del propio sistema.

**Vulnerabilidad**: cualquier debilidad o falta de control que aumente la probabilidad de que se materialice una de las amenazas a las que están expuestos los activos o los elementos del sistema de información y comunicaciones.

**Impacto**: es la consecuencia que tiene la materialización de una amenaza sobre un activo, sobre el sistema de información y de comunicaciones o sobre la organización.****

**Riesgo**: es la estimación del grado de exposición a que una amenaza se materialice sobre uno o mas activos causando daños o perjuicios a la organización.

**Datos Personales:** Datos que te conciernen solo a ti: fotos, redes sociales, información familiar, cuentas bancarias, facturas, etc. Debemos asegurarnos que esta información solo llegue a quien nos interese.

**Datos de la empresa:** Datos que administras en tu trabajo día a día: datos de los clientes, información financiera y tributaria, estructura organizacional, métricas, etc. La empresa generalmente asegura esta información mediante un NDA.


### El eslabón mas débil
Los incidentes de seguridad de la información y ciberseguridad son cada vez más frecuente. Esto debido a que en la gran mayoría de ocasiones el eslabón más débil es el usuario y por ello, nos daremos cuenta **que el usuario es quien les abre la puerta** a los ciberdelincuentes, 

La gran mayoría de los ciberataques se produce a través de lo que conocemos como **phishing**.

#### Entradas de ataque
**La Ingeniería Social:** es usar nuestras características humanas (hablar, no estar atento, confiar, conversar) para conseguir información a la que no deberíamos dar acceso.

**Phishing:** consiste en enviar diferentes mensajes haciéndose pasar por una entidad importante (Google, Facebook, bancos, policía de tránsito) o una persona necesitada para pedirte información personal con el fin de solucionar un problema que, en realidad, no es real.

**Ataques DoS y DDoS:** los atacantes usan diferentes clientes/dispositivos sincronizados para hacer muchísimas peticiones a un solo servidor, haciendo que este no pueda responder más y deje de funcionar.

**Man In the Middle:** Es interceptar la información que mandamos por la red: mensajes, contraseñas, entre otras.

**Ransomware:** Es software que accede a nuestros dispositivos para secuestrar nuestra información y pedirnos un pago por entregárnosla de vuelta. 


## Tipos de Malware

Un **Malware** es un código o software malicioso que tiene el propósito de afectar, dañar o deshabilitar los sistemas informáticos y otorga un control limitado o total de los sistemas al creador del malware con el propósito de robo o fraude.

**Troyanos**: Se presentan al usuario como un programa aparentemente legítimo, pero que al ejecutarlo, le brinda al atacante acceso remoto al equipo infectado.

**Trojanos**: Son programas que aparentan ser una cosa pero son de hecho malware.

**Backdoor**: Son puertas traseras donde el hacker pueda mantener el acceso al sistema sin que el usuario pueda notarlo.

**Gusanos**: Puede replicarse a sí mismo en los equipos o a través de redes de computadores sin que te des cuenta de que el equipo está infectado.

**Spyware**: Recopila información de un equipo y después transmite esa información a una entidad externa sin el consentimiento del propietario de la información.

**Botnet**: Es una red de equipos que han sido infectados por malware y se ejecutan de manera autónoma y automática.

**Bots**: Es una colección de dispositivos hackeados que están en control de un atacante. (DDOS)

**Crypter**: Tipo de software que puede encriptar y manipular malware, para que sea más difícil de detectar mediante programas de seguridad.

**Virus**: Software que tiene por objetivo alterar el funcionamiento normal de cualquier tipo de dispositivo informático.

**Macro Virus**: Muchas aplicaciones permiten que algunos scripts sean agregados en los documentos, así que el script será ejecutado automáticamente cuando el documento sea abierto **(Word,Excel,PDF,etc).**

**Stealth Virus:** Es un virus que esconde las modificaciones. También intenta engañar al antivirus interceptando las peticiones que hace al sistema operativo y dándole información falsa.

**Polymorphic Virus:** Produce copias variadas de si mismo. Un virus de este tipo puede tener diferentes paths que no tengan nada que ver unos con los otros lo cual lo hace muy difícil de detectar.

**Self-garbling Virus:** Pueden llegar a cambiar su propio código internamente para engañar y romper las muestras de la base de datos del antivirus.

**Gusanos**: Estos son simplemente virus que se pasan de una máquina a otra y otra una y otra vez

**OS Rootkits:** Estos son de los peores tipos de malware que existen. se instalan en el kernel del sistema operativo por lo que pueden esconder su existencia por completo

**Frimware Rootkits:** Estos son verdaderamente el peor tipo de malware que existe. Se pueden instalar, por dar un ejemplo en el chip de tu disco duro por lo cual ni siquiera formateando se lograra eliminar este tipo de malware.

**Keyloggers**: Realizan la captura de tus pulsaciones y las envía a algún servidor o correo electrónico.

**Rats (Remote Administration Tools)**: Estos son programas maliciosos que corren en tu sistema y permiten a intrusos acceder a tu sistema de manera remota (Como un Teamviewer o asistencia rápida pero sin informar al usuario).

**Malvertisment:** Son anuncios que contienen scripts (ya que muchas compañías de anuncios, desconocen exactamente que anuncios están mostrando)

**Spyware**: su propósito principal es obtener información sobre la víctima y enviarla de regreso al atacante.

**Adware**: Podría considerarse una variante de spyware. es un tipo de malware que te muestra publicidad forzosamente y que es muy difícil de remover.

**Scareware:** Es utilizado para hacer ataques de ingeniería social que hacen creer a una víctima que hay una amenaza que no es real. Un ejemplo común es antivirus FAKE que te aseguran que tienes un problema de seguridad y te piden un pago a cambio de solucionar el problema.


## Casos y Consecuencias

### Caso 1
**Cartolas Banco de Chile (2012)**:  El martes 3 de julio del año 2012, 52.770 cuenta corrientistas del Banco de Chile recibieron en sus correos electrónicos cartolas con la información de últimos movimientos,   pero de otro cliente. 

**Consecuencias**:
Daño reputacional,  Multas del Sernac y de la SBIF (Actual CMF)
Demanda de la Corporación Nacional de Consumidores y Usuarios (Conadecus)

### Caso 2
**Clonadores de tarjetas: ex ingeniero de Transbank (2007)**: El ingeniero Javier Cárdenas aprovechó el acceso a información privilegiada para realizar estafas por 200 millones de pesos a clientes de los bancos de Chile y Santander. 

**Consecuencias**:
Daño reputacional para Transbank
Demandas de los bancos afectados (Santander y Chile)

### Caso 3
**Inverlink (2003)**: El grupo **Inverlink**  se dedicaba a la administración de fondos de pensiones, seguros generales, seguros médicos privados, fondos mutuos y acciones, y arrendamiento.

**Consecuencias**:
Condenas de cárcel.
Implicancias políticas (Renuncia presidente de Banco central y del superintendente de valores alvaro Clarke).
Multas económicas por mas de 12 Millones de pesos.




# PPT2

