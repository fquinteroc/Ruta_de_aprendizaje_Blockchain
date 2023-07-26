## **Aplicación de Blockchain** 
Una *aplicación de blockchain* consiste en el programa de la aplicación y el libro mayor distribuido, que contiene al blockchain (Figura 1.19).  

![](./imagenes/Aspose.Words.44825fc3-f5b9-42f6-881d-8858ae44005c.001.png) 

Figura 1.19 – Una aplicación de blockchain abarca al libro mayor distribuido. 

Una característica que define la arquitectura de una aplicación de blockchain es que por naturaleza es descentralizada, lo que resulta en que tanto el programa de la aplicación como el libro mayor distribuido son instalados de manera redundante en cada estación de trabajo del participante de la aplicación (Figura 1.20). 

![](./imagenes/Aspose.Words.44825fc3-f5b9-42f6-881d-8858ae44005c.002.png)

Figura 1.20 – Cada usuario de la aplicación tiene su propia implementación redundante de toda la aplicación de blockchain, incluyendo el libro mayor distribuido. 
## **Red de blockchain**  
Una *red de blockchain* es un marco de comunicaciones que permite que los participantes de la aplicación de blockchain se comuniquen entre sí (Figura 1.21).  

![](./imagenes/Aspose.Words.44825fc3-f5b9-42f6-881d-8858ae44005c.003.png)

Figura 1.21 – Usuarios de la aplicación de blockchain se conectan a la red de blockchain. 

Los participantes de la aplicación de blockchain generalmente usan la red para conectarse usando TCP/IP, a través del cual cada uno contacta al otro mediante su dirección IP. Como se explica en la sección subsiguiente *Nodos*, los usuarios de una red se conocen y son representados como nodos (Figura 1.22). 

![Imagen que contiene Diagrama

Descripción generada automáticamente](Aspose.Words.44825fc3-f5b9-42f6-881d-8858ae44005c.004.png)

Figura 1.22 – Los participantes de la aplicación de blockchain establecen una conexión con la red usando el protocolo TCP/IP estándar. 

Una red de blockchain generalmente se conoce como *red superpuesta*, porque generalmente se encuentra en la parte superior de una red TCP/IP que puede extenderse más allá del alcance de la aplicación de blockchain (Figura 1.23). Dentro de la red superpuesta de blockchain, se usan protocolos de comunicación adicionales para llevar a cabo la actividad de blockchain. Tan pronto como se hace un intento de comunicación con un nodo mediante el protocolo de red de blockchain, se invoca a la red superpuesta. 

![](./imagenes/Aspose.Words.44825fc3-f5b9-42f6-881d-8858ae44005c.005.png)

Figura 1.24 – En un modelo de base de datos centralizado (izquierda), se requiere a cada usuario acceder a la base de datos central de manera individual. El libro mayor distribuido de blockchain se basa en un modelo de base de datos descentralizado (derecha), en el que cada usuario tiene una copia individual de la base de datos de la aplicación que se sincroniza con las copias de la base de datos de los otros usuarios. 

Con un libro mayor distribuido, cada usuario participante (o nodo) guarda una copia idéntica del libro mayor (base de datos) en la red en la que se sincronizan todas las réplicas del libro mayor (Figura 1.25). Esto se lleva a cabo con el mecanismo replicador del libro mayor.

![](./imagenes/Aspose.Words.44825fc3-f5b9-42f6-881d-8858ae44005c.006.png)

Figura 1.25 – El libro mayor distribuido se sincroniza entre todos los usuarios participantes de la aplicación. 

Los libros mayores distribuidos almacenan y organizan datos de manera diferente que las bases de datos relacionales tradicionales. Por lo tanto, también son usados para almacenar tipos específicos de datos. 

Los datos almacenados típicamente en un libro mayor distribuido incluyen: 

- registros que requieren de almacenamiento seguro e inmutable 
- registros de transacción e historial de la actividad 
- metadatos asociados con transacciones históricas y actividad de registros  Los datos no almacenados típicamente en un libro mayor incluyen:  
- datos empresariales y registros que requieren crear, leer, actualizar y borrar el acceso a los datos 
- datos que necesitan ser almacenados instantáneamente 
- datos para los que se requieren consultas profundas y complejas 

El modelo de base de datos descentralizado usado por el libro mayor distribuido no necesariamente entra en conflicto con un modelo de base de datos centralizado. En un ambiente de solución mayor, se puede usar un libro mayor distribuido junto con una base de datos relacional central. Existen diferentes modelos específicos sobre cómo se puede posicionar un libro mayor distribuido en relación con una base de datos relacional estándar. La sección *Modelos de coexistencia de libro mayor distribuido* al final de este curso los explora más a fondo. 

Como se explicó anteriormente en la sección *Alcance y propósito de la arquitectura de blockchain*, el libro mayor distribuido es utilizado comúnmente para evitar la dependencia de una autoridad central. Sin embargo, la arquitectura de la tecnología de blockchain aún puede ser diseñada para permitir que el libro mayor sea propiedad y esté gobernado por una organización específica (o entidad legal) que controle el acceso a los datos del libro mayor. En este caso, generalmente se le llama *libro mayor empresarial*. 
## **Usuarios y consumidores** 
Un *usuario* es típicamente una persona que posee o usa una aplicación de blockchain (Figura 1.26). Cada aplicación de blockchain tiene múltiples usuarios, y algunas tienen una gran cantidad de usuarios. El término *consumidor* se usa para representar una gama más amplia de participantes, incluyendo personas, dispositivos, o programas de software que pueden estar participando en una capacidad automatizada.  

Por ejemplo, si una persona usa un sistema de pago de blockchain ofrecido por la Compañía A para hacer una transacción, puede ser considerado un usuario y un consumidor. Si, para completar la transacción, la Compañía A requiere la participación de un servicio de pasarela de pagos de un tercero (tal vez para convertir diferentes monedas), entonces la pasarela de pagos podría ser considerada solo como un consumidor. 

Un usuario activo (o consumidor) es un participante que está activo actualmente en una red de blockchain. Por ejemplo, un usuario puede instalar y participar en una aplicación de blockchain mediante su estación de trabajo. Esto hace del usuario un usuario activo. Sin embargo, si el usuario se aleja por un tiempo durante el cual la estación de trabajo se apaga, el usuario no es considerado como participante activo hasta que vuelve a unirse a la red de blockchain y sincroniza su estación de trabajo.
