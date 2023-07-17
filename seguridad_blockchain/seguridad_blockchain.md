# **Rutas de concimiento - Experto en seguridad de Web 3.0**

La seguridad Web3 se refiere a las medidas tomadas para proteger las aplicaciones descentralizadas (dApps) y las redes blockchain de ataques. Web3 es una nueva iteración de Internet que se basa en tecnologías descentralizadas, como blockchain. Esto significa que no existe una autoridad central que controle estos sistemas, lo que los hace más vulnerables a los ataques.

Los expertos de seguridad de Web3 juegan un papel vital en la protección de la integridad, confidencialidad y disponibilidad de los sistemas Web3. Lo hacen realizando auditorías de seguridad, identificando y mitigando vulnerabilidades, implementando las mejores prácticas de seguridad y respondiendo a incidentes de seguridad.

Su rol es clave ya que:

* La tecnología Blockchain sigue siendo una tecnología relativamente nueva y emergente, y hay muchas vulnerabilidades de seguridad que aún no se han descubierto.

* La naturaleza descentralizada de la tecnología blockchain dificulta la implementación de medidas de seguridad tradicionales, como firewalls y sistemas de detección de intrusos.

* El valor financiero de algunos activos basados en blockchain, como las criptomonedas, los convierte en objetivos atractivos para los delincuentes.

Esta guía presenta una serie de conceptos junto con su bibliografía que ayudaran a formar al experto divididos en 14 categorías

* Fundamentos de Internet
* Modelos de autenticación/autorización existentes en aplicaciones Web2.0
* Top 10 de OWASP
* Conceptos básicos de Ethereum
* Contratos inteligentes
* Solidity
* Testing Frameworks
* Vectores de ataque DEFI:
* Herramientas y Linters para la seguridad en Smart Contracts
* Vulnerabilidades en contratos inteligentes
* Errores de contratos inteligentes y mejores prácticas de seguridad
* CTF y sus retos
* Informes de Auditoría:

Adcionalmente es importante como insumo tener claro los conceptos propuestos en [conocimiento general](../conocmiento_general/conocimiento_general.md)

<br>

**Lecturas:** :page_facing_up:

**Videos:**  :video_camera:

**Cursos:** :books:

<br>

## **Fundamentos de Internet**

Buena comprensión de los conceptos de redes.

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.mozilla.org/en-US/firefox/browsers/what-is-a-browser/">Cómo funciona un navegador web</a></td>
      <td>
      Descripción básica del funcionamiento de un navegador
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers">¿Qué es un DNS?</a>
      </td>
      <td>Qué sucede detrás de escena cuando escribes google.com en el navegador
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview">Una descripción general de HTTP</a>
      </td>
      <td>Descripción básica de http
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers">¿Qué son los encabezados de solicitud y respuesta HTTP?</a>
      </td>
      <td>Como se trasmiten información el cliente y el servidor
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.guru99.com/remote-procedure-call-rpc.html">¿Qué es el protocolo RPC?</a>
      </td>
      <td>El protocolo de comunicación para aplicaciones cliente-servidor
      </td>
      <td>:page_facing_up: </td>
    </tr>
  </tbody>
</table>
<br>

## **Modelos de autenticación/autorización existentes en aplicaciones Web2.0**

Estudio de los fundamentos se seguridad en web 2.0 

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.onelogin.com/learn/how-single-sign-on-works">Single Sign-On</a></td>
      <td>
      ¿Cómo funciona Single Sign-On?
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.csoonline.com/article/562635/what-is-oauth-how-the-open-authorization-framework-works.html">OAuth</a>
      </td>
      <td>¿Qué es OAuth? Cómo funciona el marco de autorización abierta
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.youtube.com/watch?v=7Q17ubqLfaM&ab_channel=WebDevSimplified">JWT</a>
      </td>
      <td>¿Qué es JWT y por qué debería usarlo?
      </td>
      <td>:video_camera:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.okta.com/identity-101/what-is-token-based-authentication/">Token-Based Authentication</a>
      </td>
      <td>¿Qué es la autenticación basada en token?
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://sherryhsu.medium.com/session-vs-token-based-authentication-11a6c5ac45e4">Session vs Token Based Authentication</a>
      </td>
      <td>¿Por qué necesitamos sesión o token para la autenticación?
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://www.ibm.com/docs/en/cics-ts/5.2?topic=web-internet-tcpip-http-concepts">Conceptos de Internet junto con TCP/IP y HTTP</a>
      </td>
      <td>Detalles sobre TCP, autenticación básica en http entre otros
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://www.cloudflare.com/en-in/learning/cdn/what-is-caching/">Cache</a>
      </td>
      <td>¿Qué es el almacenamiento en caché?
      </td>
      <td>:page_facing_up: </td>
    </tr>
  </tbody>
</table>
<br>

## **OWASP Top 10**

Informe en el que se exponen los problemas de seguridad de las aplicaciones web, centrándose en los 10 riesgos más importantes

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://owasp.org/Top10/A01_2021-Broken_Access_Control/">A01</a></td>
      <td>
      Vulnerabilidades de control de acceso
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://owasp.org/Top10/A02_2021-Cryptographic_Failures/">A02</a>
      </td>
      <td>Fallos criptográficos
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://owasp.org/Top10/A03_2021-Injection/">A03</a>
      </td>
      <td>Vulnerabilidades de inyección
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://owasp.org/Top10/A04_2021-Insecure_Design/">A04</a>
      </td>
      <td>Diseño inseguro
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://owasp.org/Top10/A05_2021-Security_Misconfiguration/">A05</a>
      </td>
      <td>Configuraciones incorrectas de seguridad
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/">A06</a>
      </td>
      <td>Componentes vulnerables y obsoletos
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://owasp.org/Top10/A07_2021-Identification_and_Authentication_Failures/">A07</a>
      </td>
      <td>Fallos de identificación y autenticación
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://owasp.org/Top10/A08_2021-Software_and_Data_Integrity_Failures/">A08</a>
      </td>
      <td>Fallas de integridad de software y datos
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://owasp.org/Top10/A09_2021-Security_Logging_and_Monitoring_Failures/">A09</a>
      </td>
      <td>Registro de seguridad y fallas de monitoreo
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://owasp.org/Top10/A10_2021-Server-Side_Request_Forgery_%28SSRF%29/">A10</a>
      </td>
      <td>Falsificación de solicitud del lado del servidor
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://www.pluralsight.com/cloud-guru/courses/introduction-to-owasp-top-10-security-risks">Introducción a los 10 principales riesgos de seguridad de OWASP</a>
      </td>
      <td>Aprenda a defenderse de los riesgos comunes de seguridad de las aplicaciones web con OWASP Top 10.
      </td>
      <td>:books: </td>
    </tr>
  </tbody>
</table>
<br>

## **Conceptos básicos de Ethereum**

Esta es una de las redes Blockchain mas relevantes 

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://ethereum.org/en/developers/docs/web2-vs-web3/">WEB2 VS WEB3</a></td>
      <td>
       La revolución del internet
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://ethereum.org/en/what-is-ethereum/">¿Qué es Ethereum?</a>
      </td>
      <td>Una guía básica de introducción
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://medium.com/@reyesale/ethereum-the-world-computer-fb7b58948280">Ethereum: la computadora mundial</a>
      </td>
      <td>Una descripción de Ethereum
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.investopedia.com/articles/investing/031416/bitcoin-vs-ethereum-driven-different-purposes.asp">Bitcoin vs. Ethereum: ¿Cuál es la diferencia?</a>
      </td>
      <td>Bitcoin vs. Ethereum: una descripción general
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.investopedia.com/tech/what-ether-it-same-ethereum/">¿Qué es el éter (ETH)?</a>
      </td>
      <td>La criptomoneda de Ethereum
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/transactions/">Transacciones</a>
      </td>
      <td>Las transacciones son instrucciones firmadas criptográficamente desde las cuentas. Una cuenta iniciará una transacción para actualizar el estado de la red Ethereum. La transacción más simple es transferir ETH de una cuenta a otra.
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/accounts/">Ethereum accounts</a>
      </td>
      <td>An Ethereum account is an entity with an ether (ETH) balance that can send transactions on Ethereum. Accounts can be user-controlled or deployed as smart contracts.
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://ethereum.org/en/wallets/">Ethereum wallets</a>
      </td>
      <td>Wallets give access to your funds and Ethereum applications. Only you should have access to your wallet.
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://eips.ethereum.org/">EIPs</a>
      </td>
      <td>Ethereum Improvement Proposals
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://finance.yahoo.com/news/guide-ethereum-erc-standards-150024381.html">ERC standards</a>
      </td>
      <td>A guide to Ethereum’s ERC standards
      </td>
      <td>:page_facing_up: </td>
    </tr>
      <tr>
      <td>
        <a href="https://finance.yahoo.com/news/guide-ethereum-erc-standards-150024381.html">ERC standards</a>
      </td>
      <td>A guide to Ethereum’s ERC standards
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/standards/tokens/erc-20/">ERC-20</a>
      </td>
      <td>Token standard
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/standards/tokens/erc-721/">ERC-721</a>
      </td>
      <td>Non-fungible token standard
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/standards/tokens/erc-1155/">ERC-1155</a>
      </td>
      <td>Multi-token standard
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/standards/tokens/erc-4626/">ERC-4626</a>
      </td>
      <td>Tokenized vault standard
      </td>
      <td>:page_facing_up: </td>
    </tr>
     <tr>
      <td>
        <a href="https://github.com/ethereumbook/ethereumbook">Dominar Ethereum</a>
      </td>
      <td>Mastering Ethereum es un libro para desarrolladores que ofrece una guía para el funcionamiento y uso de Ethereum, Ethereum Classic, RootStock (RSK) y otras cadenas de bloques abiertas basadas en EVM compatibles.
      </td>
      <td>:page_facing_up: </td>
    </tr>
  </tbody>
</table>
<br>

## **Smart Contracts**

¿Qué son los contratos inteligentes?

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://lifemathmoney.com/what-is-a-smart-contract-explained-with-real-world-examples/">¿Qué es un contrato inteligente?</a></td>
      <td>
       Explicado con ejemplos del mundo real
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.youtube.com/watch?v=_J6G5g-nKg0&ab_channel=Simplilearn">Conceptos básicos de los contratos inteligentes</a>
      </td>
      <td>Incluye contexto y una implementación de ejemplo
      </td>
      <td>:video_camera:</td>
    </tr>
    <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/smart-contracts/">Introducción a los contratos inteligentes</a>
      </td>
      <td>Definiciones y ejemplos
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/smart-contracts/languages/">Lenguajes de contratos inteligentes</a>
      </td>
      <td>Un gran aspecto de Ethereum es que los contratos inteligentes se pueden programar usando lenguajes relativamente amigables para los desarrolladores. 
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://medium.com/quillhash/life-cycle-of-smart-contract-development-8929fa073b7f">Ciclo de vida del desarrollo de contratos inteligentes</a>
      </td>
      <td>Una guía detallada para obtener una comprensión completa de los procedimientos involucrados en el desarrollo de un contrato inteligente
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://ethereum.org/en/developers/docs/transactions/">Crear desplegar y usar contratos inteligentes</a>
      </td>
      <td>Guías completas para cada paso de su viaje de desarrollo.
      </td>
      <td> :books:</td>
    </tr>
  </tbody>
</table>
<br>

## **Solidity**

El lenguaje de programación de contratos inteligentes más usado

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.youtube.com/watch?v=gyMwXuJrbJQ&ab_channel=freeCodeCamp.org">Curso general de Blockchain y Solidity</a></td>
      <td>
       Aprenda Blockchain, Solidity y desarrollo Full Stack Web3 con JavaScript, curso de 32 horas
      </td>
      <td>:books:</td>
    </tr>
    <tr>
      <td>
        <a href="https://docs.soliditylang.org/en/latest/">Solidity</a>
      </td>
      <td>Documentación de Solidity
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://cryptozombies.io/en/course/">Solidity Principiante a intermedio</a>
      </td>
      <td>Curso interactivo de programación
      </td>
      <td>:books:</td>
    </tr>
    <tr>
      <td>
        <a href="https://remix-ide.readthedocs.io/en/latest/">Documentación de Remix</a>
      </td>
      <td>Remix IDE se utiliza para todo el proceso de desarrollo de contratos inteligentes por parte de los usuarios en todos los niveles de conocimiento.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://web3js.readthedocs.io/en/v1.5.2/">web3.js</a>
      </td>
      <td>web3.js es una colección de bibliotecas que le permiten interactuar con un nodo ethereum local o remoto mediante HTTP, IPC o WebSocket.
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://solidity-by-example.org/">Solidity by Example</a>
      </td>
      <td>Una introducción a Solidity con ejemplos simples
      </td>
      <td>:books: </td>
    </tr>
  </tbody>
</table>
<br>

## **Testing Frameworks**

Estas herramientas ayudan a desplegar y probar códigos de prueba de Smart Contracts para la creación de dApps. 

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://book.getfoundry.sh/">Foundry</a></td>
      <td>
       Foundry administra sus dependencias, compila su proyecto, ejecuta pruebas, implementa y le permite interactuar con la cadena desde la línea de comandos y mediante scripts de Solidity.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://hardhat.org/docs">Hardhat</a>
      </td>
      <td>Hardhat es un entorno de desarrollo para el software Ethereum. Consta de diferentes componentes para editar, compilar, depurar e implementar sus contratos inteligentes y dApps, todos los cuales trabajan juntos para crear un entorno de desarrollo completo.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://eth-brownie.readthedocs.io/en/stable/">Brownie</a>
      </td>
      <td>Brownie es un marco de prueba y desarrollo basado en Python para contratos inteligentes dirigidos a la máquina virtual Ethereum.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://trufflesuite.com/">Truffle</a>
      </td>
      <td>Conjunto de herramientas para el desarrollo de contratos inteligentes.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.infura.io/">Infura</a>
      </td>
      <td>Conjunto de herramientas para desarrolladores y API de cadena de bloques de alta disponibilidad.
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://www.openzeppelin.com/contracts">OpenZeppelin</a>
      </td>
      <td>OpenZeppelin Contracts lo ayuda a minimizar el riesgo mediante el uso de bibliotecas probadas en batalla de contratos inteligentes para Ethereum y otras cadenas de bloques. Incluye las implementaciones más utilizadas de los estándares ERC.
      </td>
      <td>:page_facing_up: </td>
    </tr>
  </tbody>
</table>
<br>

## **DEFI y Vectores de ataque de DEFI**

Decentralized finance potencialmente tiene las claves para bancarizar a los no bancarizados y democratizar verdaderamente las finanzas.

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://teachyourselfcrypto.com/#ftoc-module-4-decentralized-finance-defi">Teach yourself crypto (Chapter 4)</a></td>
      <td>
       Curso integral para el entendimiento de DEFI y su funcionamiento
      </td>
      <td>:books:</td>
    </tr>
     <tr>
      <td>
        <a href="https://101blockchains.com/course/defi-security-fundamentals/">Fundamentos de seguridad de DeFi</a>
      </td>
      <td>Amenazas de seguridad comunes para proyectos DeFi, ejemplos prácticos de hacks de DeFi que explotan vulnerabilidades de seguridady mejores prácticas para mitigar los riesgos de seguridad comunes de DeFi
      </td>
      <td>:books:</td>
    </tr>
         <tr>
      <td>
        <a href="https://defi-learning.org/f22s">Decentralized Finance Cousrse</a>
      </td>
      <td>Particularmente los Capitulos 10 y 11 de curso se centran en la seguridad en DeFi
      </td>
      <td>:books:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.coursera.org/learn/decentralized-finance-opportunities-and-risk-duke">Oportunidades y riesgos de las finanzas descentralizadas (DeFi)</a>
      </td>
      <td>Curso que plantea diversos riesgos y oportunidades
      </td>
      <td>:books:</td>
    </tr>
    <tr>
      <td>
        <a href="https://moralismoney.com/blog/defi-deep-dive-explaining-defi-attack-vectors-and-prevention">Vectores de ataque de DEFI</a>
      </td>
      <td>Explicación de los vectores de ataque en DEFI y cómo prevenirlos
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/Quillhash/DeFi-Attack-Vectors">Vectores de ataque de DEFI</a>
      </td>
      <td>Este repositorio contiene una lista de amenazas DeFi comunes y vectores de ataque. QuillAudits mantendrá y actualizará activamente este repositorio.
      </td>
      <td>:page_facing_up:</td>
    </tr>
  </tbody>
</table>
<br>


## **Herramientas y Linters para la seguridad en Smart Contracts**

Diversas herramientas visuales de formato ayudan a tener un código limpio, bien estructurado y seguro.

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor">Solidity Visual Developer</a></td>
      <td>
      Esta extensión aporta sintaxis centrada en la seguridad y resaltado semántico, un esquema de clase detallado, vistas especializadas, información avanzada sobre el código de Solidity en Visual Studio Code.
      </td>
      <td>:page_facing_up:</td>
    </tr>
     <tr>
      <td>
        <a href="https://github.com/ConsenSys/surya">Surya</a>
      </td>
      <td>Surya es una herramienta de utilidad para sistemas de contratos inteligentes. Proporciona una serie de resultados visuales e información sobre la estructura de los contratos. También es compatible con la consulta del gráfico de llamada de funciones de varias maneras para ayudar en la inspección manual de los contratos.
      </td>
      <td>:page_facing_up:</td>
    </tr>
         <tr>
      <td>
        <a href="https://github.com/raineorshine/solgraph">Solgraph</a>
      </td>
      <td>Genera un gráfico DOT que visualiza el flujo de control de funciones de un contrato de Solidity y destaca posibles vulnerabilidades de seguridad.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/ethereum/evmlab">Evmlab</a>
      </td>
      <td>Este paquete contiene varias herramientas para interactuar con la máquina virtual Ethereum.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/fergarrui/ethereum-graph-debugger">Ethereum-graph-debugger</a>
      </td>
      <td>Este depurador adopta un enfoque diferente a la depuración tradicional. En lugar de recorrer paso a paso la ejecución del programa, muestra todo el gráfico de flujo de control del programa y la ejecución real de la transacción resaltada en rojo. De esta forma, el desarrollador puede ver la imagen completa y saltar donde sea necesario de forma rápida y gráfica.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/blockchainsllc/piet">Piet</a>
      </td>
      <td>Piet es una aplicación web que brinda soporte para comprender las arquitecturas de contratos inteligentes. Esto se aborda generando una representación gráfica de tales arquitecturas y la posibilidad de consultar instancias implementadas de contratos inteligentes.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/duaraghav8/Ethlint">Ethlint</a>
      </td>
      <td>Ethlint (anteriormente Solium) analiza su código Solidity en busca de problemas de estilo y seguridad y los corrige.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/protofire/solhint">Solhint</a>
      </td>
      <td>Este es un proyecto de código abierto para limpiar el código de Solidity. Este proyecto proporciona validaciones tanto de seguridad como de guía de estilo.
      </td>
      <td>:page_facing_up:</td>
    </tr>
  </tbody>
</table>
<br>

## **Vulnerabilidades en Smart Contracts**

Existen diversas vulnerabilidades de todo tipo en los contratos inteligentes, a continuación, se presentan algunas de las más importantes junto con ejemplos de código:

<br>
<table>
  <thead>
    <tr>
      <th>Recurso</th>
      <th>Descripción</th>
      <th>Modalidad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://swcregistry.io/docs/SWC-101">Integer Overflow and Underflow</a></td>
      <td>
      Un overflow/underflow ocurre cuando una operación aritmética alcanza el tamaño máximo o mínimo de un tipo.
      </td>
      <td>:page_facing_up:</td>
    </tr>
     <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-103">Floating Pragma</a>
      </td>
      <td>Los contratos deben implementarse con la misma versión del compilador y las mismas marcas con las que se probaron minuciosamente. Bloquear el pragma ayuda a garantizar que los contratos no se implementen accidentalmente usando versiones desactualizadas.
      </td>
      <td>:page_facing_up:</td>
    </tr>
         <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-104">Unchecked Call Return Value</a>
      </td>
      <td>El valor de retorno de una llamada de mensaje no se comprueba. La ejecución se reanudará incluso si el contrato llamado arroja una excepción. Si la llamada falla accidentalmente o un atacante fuerza la llamada a fallar, esto puede provocar un comportamiento inesperado en la lógica del programa posterior.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-106">Instrucción de autodestrucción sin protección</a>
      </td>
      <td>Debido a controles de acceso faltantes o insuficientes, partes malintencionadas pueden autodestruir el contrato.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-107">Reentrancy</a>
      </td>
      <td>Uno de los principales peligros de llamar a contratos externos es que pueden hacerse cargo del flujo de control. En el ataque de reentrada (también conocido como ataque de llamada recursiva), un contrato malicioso vuelve a llamar al contrato de llamada antes de que finalice la primera invocación de la función. Esto puede provocar que las diferentes invocaciones de la función interactúen de formas no deseadas.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-108">State Variable Default Visibility</a>
      </td>
      <td>Etiquetar la visibilidad explícitamente facilita la detección de suposiciones incorrectas sobre quién puede acceder a la variable.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-109">Uninitialized Storage Pointer</a>
      </td>
      <td>Las variables de almacenamiento local no inicializadas pueden apuntar a ubicaciones de almacenamiento inesperadas en el contrato, lo que puede generar vulnerabilidades intencionales o no intencionales.
      </td>
      <td>:page_facing_up:</td>
    </tr>
     <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-111">Use of Deprecated Solidity Functions</a>
      </td>
      <td>Varias funciones y operadores en Solidity están en desuso. Su uso conduce a una calidad de código reducida. Con las nuevas versiones principales del compilador de Solidity, las funciones y los operadores obsoletos pueden provocar efectos secundarios y errores de compilación.
      </td>
      <td>:page_facing_up:</td>
    </tr>
     <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-113">DoS with Failed Call</a>
      </td>
      <td>Las llamadas externas pueden fallar de forma accidental o deliberada, lo que puede provocar una condición DoS en el contrato. Para minimizar el daño causado por tales fallas, es mejor aislar cada llamada externa en su propia transacción que puede ser iniciada por el destinatario de la llamada. Esto es especialmente relevante para los pagos, donde es mejor permitir que los usuarios retiren fondos en lugar de enviarles fondos automáticamente (esto también reduce la posibilidad de problemas con el límite de gas).
      </td>
      <td>:page_facing_up:</td>
    </tr>
     <tr>
      <td>
        <a href="https://swcregistry.io/docs/SWC-115">Authorization through tx.origin</a>
      </td>
      <td>tx.origin es una variable global en Solidity que devuelve la dirección de la cuenta que envió la transacción. El uso de la variable para la autorización podría hacer que un contrato sea vulnerable si una cuenta autorizada llama a un contrato malicioso. Se podría hacer una llamada al contrato vulnerable que pasa la verificación de autorización ya que tx.origin devuelve el remitente original de la transacción que en este caso es la cuenta autorizada.
      </td>
      <td>:page_facing_up:</td>
    </tr>
     <tr>
      <td>
        <a href="https://swcregistry.io/">Lista de vulnerabilidades conocidas en el desarrollo de Smart Contrats  </a>
      </td>
      <td>Se deben revisar todas las vulnerabilidades presentes.
      </td>
      <td>:page_facing_up:</td>
    </tr>
  </tbody>
</table>
<br>



