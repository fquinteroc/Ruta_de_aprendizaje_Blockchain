# **Rutas de concimiento - Desarrollador Contratos inteligentes**

La tecnología blockchain y los contratos inteligentes están revolucionando la forma en que interactuamos y realizamos transacciones en el mundo digital. Como desarrollador de contratos inteligentes, tendrás la oportunidad de adentrarte en este fascinante campo y contribuir a la creación de aplicaciones descentralizadas seguras y transparentes. A través de esta ruta de aprendizaje, explorarás los fundamentos de la tecnología blockchain, te sumergirás en la programación de contratos inteligentes utilizando lenguajes como Solidity, y aprenderás a construir aplicaciones descentralizadas en la red Ethereum. A medida que adquieras experiencia y conocimientos en seguridad y buenas prácticas de desarrollo, te convertirás en un experto en el diseño y la implementación de contratos inteligentes. ¡Prepárate para un emocionante viaje en el que transformarás la forma en que interactuamos con la tecnología y el mundo financiero!

Ethereum es la segunda blockchain pública más utilizada y grande, después de la red de Bitcoin. La naturaleza de Bitcoin, de manera simplificada, se centra en mover saldos entre cuentas. Sin embargo, si deseamos establecer lógica o reglas específicas, debemos recurrir a la redacción de contratos. Ethereum, en su búsqueda por ser la computadora de propósito general del mundo, cuenta con una máquina virtual (EVM) que se ejecuta en los nodos de la red, lo que permite el despliegue de lógica y reglas escritas en un contrato inteligente.

Algunas blockchains alternativas han optado por hacer un fork de la EVM y desplegar sus propias redes, modificando ciertas reglas con el objetivo de lograr una mayor escalabilidad. Sin embargo, en ocasiones esto se hace a expensas de la seguridad o la descentralización. Algunas de estas redes compatibles con la EVM son:

* BNB Smart Chain.
* Arbitrum.
* Polygon.
* Avalanche.
* Optimism.
* Fantom.
* Cronos.

Esto implica que en estas redes podemos desplegar los mismos contratos sin mayores modificaciones. Por esta razón, es importante adquirir habilidades en el desarrollo de contratos en Ethereum, ya que esto permite que un desarrollador sea productivo en otras redes compatibles.

Se presentara un ruta a nivel técnico sobre desarrollo de contratos, es importante como insumo tener claro los conceptos propuestos en [conocimiento general](../conocmiento_general/conocimiento_general.md)

<br>

**Lectura:** :page_facing_up:

**Videos:**  :camera:

**Notebooks:** :blue_book:

<br>

## **Introducción a Ethereum**

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
      <td><a href="https://ethereum.org/en/developers/docs/intro-to-ethereum/">Introducción a Ethereum</a></td>
      <td>
      Documentación oficial de la fundación de Ethereum
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/ethereumbook/ethereumbook"> Mastering Ethereum</a>
      </td>
      <td>Mastering Ethereum es un libro para desarrolladores, que ofrece una guía para el funcionamiento y uso de Ethereum, Ethereum Classic, RootStock [(RSK) y o)]()ras cadenas de bloques abiertas basadas en EVM compatibles.
      </td>
      <td>:page_facing_up:</td>
    </tr>

  </tbody>
</table>

---

<br>

Sugerencia:

El libro [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) es un recurso altamente usado por la comunidad, es un buen lugar para tener una referencia conceptual sobre el funcionamiento de Ethereum. Los capítulos del libro son los siguientes:

* Prefacio: [Prefacio](https://github.com/ethereumbook/ethereumbook/blob/develop/preface.asciidoc)
* Capítulo 1: [¿Qué es Ethereum?](https://github.com/ethereumbook/ethereumbook/blob/develop/01what-is.asciidoc)
* Capítulo 2: [Conceptos básicos de Ethereum](https://github.com/ethereumbook/ethereumbook/blob/develop/02intro.asciidoc)
* Capítulo 3: [Clientes Ethereum](https://github.com/ethereumbook/ethereumbook/blob/develop/03clients.asciidoc)
* Capítulo 4: [Criptografía](https://github.com/ethereumbook/ethereumbook/blob/develop/04keys-addresses.asciidoc)
* Capítulo 5: [Carteras](https://github.com/ethereumbook/ethereumbook/blob/develop/05wallets.asciidoc)
*	Capítulo 6: [Operaciones](https://github.com/ethereumbook/ethereumbook/blob/develop/06transactions.asciidoc)
*	Capítulo 7: [Contratos inteligentes y solidez](https://github.com/ethereumbook/ethereumbook/blob/develop/07smart-contracts-solidity.asciidoc)
*	Capítulo 8: [Contratos inteligentes y Vyper](https://github.com/ethereumbook/ethereumbook/blob/develop/08smart-contracts-vyper.asciidoc)
*	Capítulo 9: [Seguridad de contratos inteligentes](https://github.com/ethereumbook/ethereumbook/blob/develop/09smart-contracts-security.asciidoc)
*	Capítulo 10: [Tokens](https://github.com/ethereumbook/ethereumbook/blob/develop/10tokens.asciidoc)
*	Capítulo 11: [Oráculos](https://github.com/ethereumbook/ethereumbook/blob/develop/11oracles.asciidoc)
*	Capítulo 12: [Aplicaciones descentralizadas (DApps)](https://github.com/ethereumbook/ethereumbook/blob/develop/12dapps.asciidoc)
*	Capítulo 13: [La máquina virtual Ethereum](https://github.com/ethereumbook/ethereumbook/blob/develop/13evm.asciidoc)
*	Capítulo 14: [Consenso](https://github.com/ethereumbook/ethereumbook/blob/develop/14consensus.asciidoc)

---
<br>

## **Solidity**

Familiarízate con el lenguaje de programación Solidity, utilizado para escribir contratos inteligentes en Ethereum. Aprende los conceptos fundamentales de Solidity, como tipos de datos, estructuras de control, funciones y eventos.

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
      <td><a href="https://docs.soliditylang.org/en/latest/">Documentación</a></td>
      <td>
      Documentación oficial del lenguaje
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://docs.soliditylang.org/en/latest/solidity-by-example.html"> Solidity con ejemplos</a>
      </td>
      <td>Ejemplos desde la documentación oficial
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://solidity-by-example.org/"> Solidity con ejemplos</a>
      </td>
      <td>una introducción a Solidity con ejemplos sencillos
      </td>
      <td>:page_facing_up: / :camera:</td>
    </tr>
    <tr>
      <td>
        <a href="https://secureum.substack.com/p/solidity-101"> Solidity 101 | Secureum </a>
      </td>
      <td>101 aspectos clave sobre Solidiy
      </td>
      <td>:page_facing_up: </td>
    </tr>
    <tr>
      <td>
        <a href="https://secureum.substack.com/p/solidity-201"> Solidity 201 | Secureum </a>
      </td>
      <td>201 aspectos clave sobre Solidiy
      </td>
      <td>:page_facing_up: </td>
    </tr>


  </tbody>
</table>

---

<br>

### **Tutoriales**

Profundiza en el desarrollo de contratos inteligentes con Solidity. Aprende a crear contratos desde cero, implementar lógica de negocio, manejar la interacción con otros contratos y gestionar eventos.

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
      <td><a href="https://learnweb3.io/degrees/ethereum-developer-degree)">Ethereum Developer Degree</a></td>
      <td>
      Construido por LearnWeb3. Si eres un desarrollador que no tiene conocimientos previos de blockchain y criptografía, el Ethereum Developer Degree es el paso perfecto para pasar de no tener conocimiento de fondo a poder construir múltiples aplicaciones y comprender varios protocolos, marcos y conceptos clave en el espacio.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://university.alchemy.com/overview/ethereum"> Ethereum Developer Bootcamp</a>
      </td>
      <td>Construido por Alchemy: Desarrollará sus habilidades desde cero con fundamentos sólidos que le brindarán la capacidad de adaptarse a este ecosistema en rápida evolución. Esta experiencia de bootcamp definitiva pone un gran énfasis en aprender haciendo y en la comunidad.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://cryptozombies.io/es/"> cryptozombies</a>
      </td>
      <td>CryptoZombies es una escuela de programación interactiva que enseña a crear contratos inteligentes en Solidity mientras construyes tu propio juego cripto-coleccionable.
      </td>
      <td>:page_facing_up:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.youtube.com/watch?v=M576WGiDBdQ"> Patrick Collins : Solidity, Blockchain, and Smart Contract Course – Beginner to Expert Python Tutorial </a>
      </td>
      <td>
      Este curso en Ingles te va a dar una introducción completa de los conceptos de blockchain, smart contracts, solidity, NFT/ERC721s, ERC20s, programación de Finanzas Descentralizadas [(DeFi), p)]()thon, Chainlink, Ethereum, upgradable smart contracts, y desarrollo full stack.
      </td>
      <td>:camera:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.youtube.com/watch?v=yN3zpI3sNAE&t=13766s"> Solidity, Blockchain y Smart Contracts - De Cero a Experto</a>
      </td>
      <td>
      Este curso en Español te va a dar una introducción completa de los conceptos de blockchain, smart contracts, solidity, NFT/ERC721s, ERC20s, programación de Finanzas Descentralizadas [(DeFi), p)]()thon, Chainlink, Ethereum, upgradable smart contracts, y desarrollo full stack.
      </td>
      <td>:camera:</td>
    </tr>
    <tr>
      <td>
        <a href="https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=16700s"> Aprenda Blockchain, Solidity y Full Stack Web3 Development con JavaScript - Curso de 32 horas</a>
      </td>
      <td>
      Este curso en ingles le dará una introducción completa a todos los conceptos básicos relacionados con blockchain, contratos inteligentes, Solidity, ERC20s, dapps Web3 full stack, finanzas descentralizadas [(DeFi), J)]()vaScript, TypeScript, Chainlink, Ethereum, contratos inteligentes actualizables, DAO,El moralis, aave, IPFS y más.
      </td>
      <td>:camera:</td>
    </tr>
  </tbody>
</table>

---
<br>

Sugerencia:

[El curso de 32 horas](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=16700s), posiblemente sera uno de los mejores recursos gratuitos que podrá encontrar, navegara por conceptos básicos hasta avanzados sobre el desarrollo en Solidity y aplicaciones descentralizadas quienes son posiblemente una interfaz de interacción con los contratos.


⌨️ [(00:00:00)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=0s) Lección 0: Bienvenido a Blockchain

⌨️ [(00:09:05)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=545s) Lección 1: Conceptos básicos de Blockchain

⌨️ [(02:01:16)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=7276s) Lección 2: ¡Bienvenido a Remix! Almacenamiento sencillo

⌨️ [(03:05:34)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=11134s) Lección 3: Remix Storage Factory

⌨️ [(03:31:55)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=12715s) Lección 4: Remix Fund Me

⌨️ [(05:30:42)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=19842s) Lección 5: Ethers.js almacenamiento simple

⌨️ [(08:20:17)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=30017s) Lección 6: Almacenamiento simple de Hardhat

⌨️ [(10:00:48)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=36048s) Lección 7: Hardhat Fund Me

⌨️ [(12:32:57)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=45177s) Lección 8: HTML / Javascript Fund Me (Full Stak / Front End)

⌨️ [(13:41:02)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=49262s) Lección 9: Lotería de contratos inteligentes de Hardhat

⌨️ [(16:34:07)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=59647s) Lección 10: NextJS Smart Contract Lottery (Full Stak / Front End)

⌨️ [(18:51:36)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=67896s) Lección 11: Kit de inicio de casco

⌨️ [(18:59:24)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=68364s) Lección 12: Hardhat ERC20s

⌨️ [(19:16:13)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=69373s) Lección 13: Hardhat DeFi & Aave

⌨️ [(20:28:51)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=73731s) Lección 14: NFT de Hardhat

⌨️ [(23:37:03)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=85023s) Lección 15: NextJS NFT Marketplace (Full Stak / Front End)

⌨️ [(28:53:11)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=103991s) Lección 16: Actualizaciones de Hardhat

⌨️ [(29:45:24)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=107124s) Lección 17: DAO de Hardhat

⌨️ [(31:28:32)](https://www.youtube.com/watch?v=gyMwXuJrbJQ&t=113312s) Lección 18: Seguridad y auditoría


---
<br>

### **Pruebas y Debugging**

---
<br>

### **Herramientas y Frameworks**

---
<br>

### **Interacción con la Blockchain**

---
<br>
