# **Características de Blockchain**

**Criptografía de hash:** SHA-256 Es el algoritmo que se usa para la criptografía de Blockchain.
Un documento hash es una identificación única para el documento, un hash con un algoritmo SHA-256 se vería como una tira de caractéres alfanuméricos. Sus caacterísticas son:

- Son unidireccionales, es decir, con el hash no se puede relacionar el contenido del documento.
- Son deterministas, si se toma el mismo documento en otro momento del tiempo va a resultar el mismo hash.
- Fáciles de calcular, son eficientes y rápidos y no requieren potencia de cálculo.
- Son compresibles, el resultados siempre será una cadena de longitud fija, con SHA 256 es una tira de caracteres alfanuméricos de 64 caracteres.
- Funcionamiento tipo avalancha, cualquier mínimo cambio de documento genera un enorme cambio.
- Resisntencia débil y fuerte a colisiones, es imposible calcular un hash que permita encontrar otro hash igual, es casi imposible encontrar 2 hashes iguales.
- Son irreversibles, tomar un hash y obtener los datos que dieron ese resultado es imposible.


Cada bloque tiene un hash asociado en el hash del bloque previo y el block hash que tiene el hash del bloque. Se requieren ambos hashes para construir la cadena.


**LIBRO MAYOR INMUTABLE:**
En lugar de almacenar el contrato de compra en un sistema centralizado, se almacena en blockchain, eso permite que la blockchain se replique en miles de servidores o nodos, así que si un atacante ataca a un nodo, pues los demás nodos seguirán teniendo la información.

**RED DISTRIBUIDA (P2P):**
Es un fundamento de blockchain, es una capa más de seguridad, una capa es la criptografía con hashes, con la red distribuida con arquitectura P2P se tienen distintos nodos conectados entre ellos, un servidor puede ser desde una máquina computadora portátil sencilla. En una red pública como bitcoin se tienen miles de miles de ordenadores. Si un atacante actúa en un servidor, como más del 50% de la red tienen la información correcta, serán capaces de replicar la información correcta en el nodo afectado.

	

**MINADO:** Hace que la cadena sea inmutable.
Si vemos en bitcoin, el hash tiene varios ceros al inicio de la cadena, pero si vemos el conversor SHA256 no se tienen esos ceros.
Un bloque tiene 4 parámetros:

**Nonce:** es la pieza clave del minado, es un número entero y junto con otros términos como el número de bloque, los datos, el hash previo sirve como un input de la función SHA256 para calcular el hash actual. Está diseñado para estar bajo nuestro control, tenemos el mecanismo para manipular el hash.
Datos: son las trasacciones que se van generando sobre la blockchain
Hash previo: el hash del bloque previo, el bloque 3 debe estar conectado con el bloque 2.
Hash: Es el hash identificador, ¿Cómo se genera este hash? Para entender, se necesita del Nonce. Hay un total de 1664 valores de HASH criptográficos SHA256 posibles. Sin embargo no todos son hashes válidos, por ejemplo en bitcoin hay un valor objetivo que generan unos ceros a la izquierda, cada cero a la izquierda reduce la magnitud del npumero en un factor de 16.


Esta probabilidad lo que indica es encontrar un hash que empiece con 18 ceros delante. En términos de minería de bitcoin, esta es la probabilidad de que cualquier valor Nonce dado genere un hash válido para el bloque actual. El número de hashes válidos es extremadamente pequeño en comparación con el grupo de hashes completo. Los mineros compiten entre ellos para generar un Nonce que genere un hash válido. Este objetivo se irán cambiando en función de la potencia de cálculo, entre más mineros mayor será mayor el objetivo y en ligar de 18 ceros, será de 30 ceros y si hay menos mineros, menor es la potencia de cálculo y en lugar de 18 ceros podrá ser solo 8 o 10. El objetivo del algoritmo es garantizar que solo se agregue 1 bloque cada 10 minutos.

El minado se enfoca en el campo del Nonce, que los mineros van variando para crear distintos hash hasta encontrar uno válido. Por eso los mineros están compitiendo todo el tiempo entre ellos.

 Con este Nonce es un valor de 32 bits de memoria asignados, tiene un rango limitado de 4000 millones de valores. 232 . Un dispositivo de minero promedio puede calcular hasta 100 millones de hashes por segundo, es decir pasará por todo el rango del nonce cada 4 segundos. La probabilidad de encontrar un hash vpalido es tan pequeña que con 4000 millones de intentos sería muy baja.
El bloque tambien tiene una marca de tiempo que es en timestamp, es la hora actual de UNIX que expresa el número de segundo trascurridos desde 1970, esta marca de tiempo tambien será como input para el hash, entonces si se cambia la marca de tiempo cada segundo, el hash siempre va a ser distinta.



**MINADO:** Mempool Los participantes de la red de bitcoin realizan trasacciones todo el tiempo sin preocuparse por los bloques, a donde van las trasacciones antes de generar un nuevo bloque? Estas trasacciones se van a la Mempool, la mempool se ubican en la mempool antes de que se se agregue a los bloques. Los mineros eligen las trasacciones que van al nuevo bloque, tambien pueden cambiarlas y hacen que el hash del bloque cambie. Los mineros obtienen un control adicional sobre el hash. Esto genera variabilidad en la función hash. Cuando el minero acaba con el rango del nonce y no ha encontrado en número, puede cambiar por otras trasacciones seleccionadas para volver a probar. No todos los bloques tienen que estar al tamaño máximo del bloque.

**PROTOCOLOS DE CONSENSO:** En blockchain el proceso de añadir un bloque es el minado, el protocolo de consenso es el mecanismo que regula la forma en que los nodos que minan los bloques llegan a un acuerdo entre sí apra poder hacerlo. Los protocolos de consenso son:
	- Proof of mork (PoW): De bitcoin y Ethereum
	- pROOF OF sTAKE (PoS): Se están adaptando muchas blockchain como ethereum2
	- Otros
Si tenemos una red blockchain con miles de nodos, tenemos que cada máquina tiene la cadena de bloques replicada, si llega un nodo y mina un nuevo bloque, la info se debe replicar en toda la cadena, varios de estos nodos deben tomar el bloque y añadirlo, pero como los bloques están distribuidos, hay un tiempo de espera para que el bloque se difunda. Si otro nodo obtuvo otro bloque y los difundió, entonces hay un conflicto de cadena.


Con qué bloque nos quedamos? Con el protocolo de consenso, nos vamos oc¿¿con la cadena más larga o con más potencia de cálculo. Pero que pasa con los bloques dobrantes? Se va y se convierte en un bloque huérfano. 

**Bloques huérfanos:**  Los bloques huérfanos son aquellos bloques que nacen cuando varios mineros logran resolver el hash en el mismo instánte, puede ocurrir que otro minero resuelva el mismo bloque y se distribuyen a la red para su validación, por lo que el bloque con menor distribución se convertirá en bloque huérfano, estos se almacenan en un sitio concreto de forma temporal, horfan block pool, es una especie de lista de bloques huérfanos. Pueden ser añadidos a la blochain posteriormente. Estos bloques son válidos pero no forma parte de la blockchain principal, la info que contiene para a ser irrelevante para la red. Se estima que entre 1 y 3 bloques cada día son huérfanos, las trasacciones añadidas en un bloque huérfanos las toma otro bloque para añadirlas a la blockchain principal.
