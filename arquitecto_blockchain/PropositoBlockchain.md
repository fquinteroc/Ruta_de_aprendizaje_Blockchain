## **Alcance y propósito de la arquitectura Blockchain** 
Esta sección aclara el propósito y el alcance funcional de una aplicación de blockchain para definir su propósito, enlistando qué puede y qué no puede hacer una aplicación de blockchain y para qué se usa normalmente y para qué no. 

*Qué puede hacer una aplicación de Blockchain:* 

- Establecer una base de datos descentralizada (conocida como libro mayor) sin que tenga que ser propiedad o administrada por una sola autoridad. 
- Establecer una aplicación conducida por la comunidad mediante la cual la confianza y la autoridad están descentralizadas entre los usuarios. 
- Mantener un historial seguro e inmutable de las transacciones y la actividad de registro que no puede ser alterada.  
- Permitir múltiples copias grabables de una base de datos distribuida para que existan al mismo tiempo. 
- Escalar el número de las copias de la base de datos distribuida en la medida de lo posible. Las figuras 1.7 a la 1.9 ilustran la relación única entre una aplicación de blockchain y sus usuarios. 

![Diagrama

Descripción generada automáticamente](Aspose.Words.acd90895-c749-4918-a064-bb2abe49465f.001.png)



Figura 1.7 – Con una aplicación de blockchain, los datos no son gobernados y accedidos por una sola autoridad central, sino que pueden estar disponibles para todos los usuarios de la aplicación participantes. 

![Diagrama

Descripción generada automáticamente](Aspose.Words.acd90895-c749-4918-a064-bb2abe49465f.002.png)

Figura 1.8 – En una arquitectura de aplicación típica, el programa y los datos de la aplicación están centralizados, requiriendo a todos los usuarios acceder de manera centralizada a la aplicación y sus datos. 



![](Aspose.Words.acd90895-c749-4918-a064-bb2abe49465f.003.png)

Figura 1.9 – En una arquitectura de aplicación blockchain, normalmente no hay un programa de aplicación ni base de datos central. En su lugar, cada usuario de la aplicación participante instala una copia de la aplicación y su base de datos (libro mayor) en su propia estación de trabajo local. Todos los usuarios participantes se conectan a la misma red para comunicarse e interactuar. 
### Qué no puede hacer una aplicación de Blockchain 
- Ofrecer una base de datos apropiada para la funcionalidad tradicional de acceso a datos.   
- Verificar a un usuario sin tener un registro del usuario o de la identidad digital del usuario. 
- Soportar la automatización de una típica solución de automatización de negocio de punta a punta o flujo de trabajo. 

Las figuras 1.10 y 1.11 resaltan algunas de las características de las aplicaciones de negocio típicas que una aplicación de blockchain no puede soportar. 



![Imagen que contiene Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.acd90895-c749-4918-a064-bb2abe49465f.004.png)

Figura 1.10 – Mientras que crear, leer, escribir y actualizar son funciones comunes con las aplicaciones de negocio, tal funcionalidad no es bien soportada en una aplicación de blockchain típica. La base de datos (libro mayor) que forma parte de una aplicación de blockchain además es incapaz de soportar tablas que tienen relaciones entre sí, como lo hace una base de datos relacional. 

*Una aplicación de Blockchain se usa generalmente para:*  

- Capturar, de manera permanente, el historial de transacciones y registros importantes.  
- Establecer la transparencia y la confianza entre los usuarios de la aplicación. 
- Prevenir fraudes relacionados con datos.  
- Eliminar la dependencia de una autoridad central. 
- Eliminar la necesidad de que terceras partes lleven a cabo transacciones de igual a igual y la compra de activos.  

*Una aplicación de Blockchain no se usa generalmente para:* 

- Soluciones empresariales que requieren el soporte para un programa de flujo de trabajo de punta a punta. 
- Acceso a datos y almacenamiento de registros de negocio completos. 
- Programas de negocio que requieren consultas o actualizaciones instantáneas de datos. 
- Programas de negocio que requieren consultas complejas. 
- Programas de negocio que requieren el uso de bases de datos centralizadas o de una autoridad centralizada. 
## **Factores de negocio de Blockchain** 
Cierto número de factores clave de negocio llevaron a la emergencia del blockchain y a la necesidad de un cambio hacia la confianza descentralizada, incluyendo: 

- Dependencia en autoridades centrales 
- Falta de transparencia 
- Tarifas financieras y plazos 
### Dependencia de autoridades centrales 
La crisis financiera global expuso cómo algunas instituciones financieras se sobrepasaron, en particular dando en préstamo muchos de los fondos de sus clientes a otras instituciones financieras y otras organizaciones, y luego fueron incapaces de pagar a sus clientes. La práctica de una entidad regulada (como un banco) realizando actividades no reguladas se conoce como “banca en la sombra”.  

Durante y después de la crisis, se hizo evidente que no siempre se puede depender de las autoridades centrales. Esto avivó la necesidad de un enfoque con el que la autoridad fuera descentralizada y compartida. 
### Falta de transparencia 
Con las aplicaciones tradicionales, los propietarios de las aplicaciones eran las autoridades sobre las mismas y como consecuencia, tenían la propiedad absoluta sobre los datos asociados. Esto significa que las transacciones actuales e históricas, otras formas de registros y las actualizaciones de los registros, no estaban disponibles para los clientes de la aplicación. Esto puede llevar a problemas cuando los datos son comprometidos, o cuando la autoridad gestiona las transacciones y los datos de manera que no cumple con las regulaciones o las políticas. 

La habilidad natural de las aplicaciones de blockchain para ofrecer una transparencia abierta a todos los miembros participantes, aborda esta preocupación. No todas las aplicaciones de blockchain están diseñadas para ser completamente transparentes, pero la habilidad de ofrecer una transparencia abierta es soportada de manera natural por la arquitectura subyacente. 
### Tarifas financieras y plazos 
Llevar a cabo varias formas de transacciones financieras con los bancos tradicionales, dio como resultado una gama de tarifas y a menudo, plazos extendidos para que las transacciones fueran finalmente completadas. Por ejemplo, una simple transferencia bancaria entre dos organizaciones en diferentes países puede tomar días para ser completada y puede resultar en tarifas tanto para la organización emisora como para la receptora. Con el blockchain y las criptomonedas, muchos de los servicios financieros ofrecidos por los bancos pueden ejecutarse más rápido y de manera más rentable sin la intervención de los bancos.  
## **Factores tecnológicos de Blockchain** 
El Blockchain existe como resultado de una colección de innovaciones tecnológicas, algunas de las cuáles tienen más de una década de existir. Combinadas, estas innovaciones cumplen con requerimientos clave en las soluciones de automatización contemporáneas, incluyendo: 
### Almacenamiento de registros altamente seguro 
Las organizaciones que han sido tradicionalmente responsables de almacenar y mantener registros importantes (como registros de salud) han sido desafiadas a menudo para hacerlo de manera segura, transparente y eficiente. Algunas veces la seguridad de los registros está comprometida por los hackers; otras veces, están totalmente fuera de sincronía en los almacenes de datos, comprometiendo así su integridad. 

La seguridad incorporada, la protección de los datos, y las características de transparencia ofrecidas por la tecnología de blockchain la hace altamente apropiada para almacenar y gestionar de forma segura los datos de registros de manera distribuida. 
### Protección inmutable de la integridad de los registros 
En las arquitecturas de aplicación típicas, es posible que los datos sean modificados y que los registros sean eliminados permanentemente, sin rastro alguno. Esto puede permitir a individuos no autorizados obtener acceso y modificar los datos, usarlos sin consentimiento, o destruirlos. Blockchain introduce un medio para almacenar datos de manera permanente e inmutable. Quien obtiene acceso a los datos es controlado, y también se registra un acceso de registro inmutable. Esto ha motivado a las organizaciones a reemplazar o complementar los sistemas de recolección de registros existentes con sistemas de blockchain.  

Por ejemplo, las organizaciones de cuidado de la salud necesitan proteger los registros de sus clientes de ser accedidos por usuarios no autorizados. Además, necesitan asegurar que todos los cambios hechos sean almacenados permanentemente y que no puedan ser modificados. Blockchain hace esto posible al ofrecer una arquitectura capaz de almacenar los datos de manera segura, inmutable y permanente. 
### Arquitectura de aplicación descentralizada 
Mientras que las soluciones de automatización han sido tradicionalmente distribuidas, tales soluciones generalmente no eran completamente descentralizadas. Por ejemplo, las bases de datos de la aplicación eran distribuidas en el sentido de que pueden haber sido copiadas a diferentes ubicaciones. Una copia de la base de datos era designada como la “fuente de la verdad” maestra y central, y otras existían como copias replicadas. Las copias de la base de datos permanecían bajo el control central de su propietario, y generalmente no eran compartidas en su totalidad con los clientes de las aplicaciones (usuarios o programas de software).  

Por ejemplo, un banco dado puede ser el solo propietario de, y tener el acceso a, las bases de datos con la información acerca de las transacciones que ocurren entre sus diferentes clientes. Blockchain hace posible permitir a todos los usuarios de una red tener acceso a la base de datos de la transacción, no sólo a la autoridad central. Esta forma de arquitectura descentralizada se ha convertido en la base de muchas innovaciones en diferentes industrias. 
### Procedencia de los datos 
La procedencia de los datos puede definirse como un método para determinar los orígenes de los datos y registrar lo que pasó con esos datos con el transcurso del tiempo. Esto puede incluir quién accedió a los datos, los cambios hechos a los datos, y quién hizo esos cambios. Esto previene a otras partes de reclamar la falsa propiedad de los datos, o modificar o eliminar la historia asociada a los datos. La procedencia de los datos además se ocupa de controlar quién accede a los datos, a la vez de asegurar que el creador original de los datos mantiene la propiedad de estos. 

La habilidad de un sistema de blockchain para establecer datos inmutables asegura que, una vez que los datos son registrados en un bloque, la procedencia de los datos será registrada y protegida. El sistema de blockchain hace además posible controlar quién accede a los datos a la vez que evita que los usuarios sean capaces de modificar o manipular el historial de los datos. 
## **Beneficios y retos de Blockchain** 
Antes de hacer una exploración sobre cómo trabaja blockchain, aquí se ofrecen dos listas que resaltan los beneficios y los retos comunes asociados con la adopción de blockchain: 
### Beneficios 
- *Confianza descentralizada* – elimina la necesidad de una sola autoridad central. 
- *Transparencia abierta* – transparenta el acceso a las transacciones históricas y a los datos de registro. 
- *Inmutabilidad* – una vez escritos, los datos no pueden ser cambiados. 
- *Seguridad mejorada* – los datos son distribuidos a través de los participantes de la red, haciendo casi imposible que sean comprometidos. 
- *Reducir los costos y a la vez aumentar la velocidad* – evitar la dependencia en una autoridad central o en intermediaros puede ser rentable y eficiente en tiempo. 
- *Soberanía de los datos*– se registra dónde se almacenan los datos y quién accede a ellos. 
### Retos  
- *Seguridad* – blockchain puede confiar en un sistema de votación, lo que significa que si una entidad maliciosa fuera capaz de controlar la mayoría necesaria de los votos, podría ser capaz de validar registros inválidos o falsificados, a propósito. 
- *Privacidad* – los blockchains pueden ser libres de permisos, permitiendo potencialmente que los datos privados sean accedidos abiertamente. 
- *Integración* – la tecnología de blockchain puede ser dispar a la tecnología de solución de automatización convencional, haciendo su integración potencialmente costosa y compleja. 
- *Procesamiento excesivo* – algunos requerimientos de procesamiento de blockchain pueden demandar un consumo significativo de capacidad de cómputo, teniendo como resultado un consumo de energía exorbitante y potencialmente desperdiciado. 
- *Escalabilidad* – algunos diseños de blockchain pueden poner restricciones en la validación y creación de bloques, inhibiendo así la escalabilidad total del sistema. 
- *Actividad ilegal* – puesto que un sistema de blockchain puede evitar la necesidad de una autoridad central, puede ser más susceptible a sufrir abusos para propósitos ilegales. 

