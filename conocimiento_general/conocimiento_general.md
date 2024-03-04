# Información General

Este es el punto de partida perfecto para adentrarse en el fascinante mundo de la tecnología blockchain. Aquí exploraremos los conceptos fundamentales, los principios clave y las características básicas que definen a esta innovadora tecnología.

En esta sección, obtendrás una comprensión sólida de qué es blockchain, cómo funciona y por qué ha generado un impacto revolucionario en diversos sectores. Exploraremos las diferencias entre blockchain público, privado y permisionado, así como los casos de uso y las ventajas que cada uno de ellos ofrece.

A medida que avanzamos en esta sección, también nos adentraremos en los conceptos esenciales que sustentan la tecnología blockchain, como la criptografía, las transacciones, los bloques y la descentralización. Obtendrás una visión clara de cómo se asegura la integridad y la confianza en una red blockchain y cómo se gestionan los activos digitales a través de contratos inteligentes.

No importa tu nivel de conocimiento previo sobre blockchain, esta sección está diseñada para ofrecerte una base sólida y un contexto comprensible para el resto de tu viaje en el mundo de la tecnología blockchain. Prepárate para adentrarte en un emocionante universo de innovación y descubrimiento mientras exploramos los aspectos clave de blockchain en esta sección

<br>

En esta sección aprenderás y produndizarás en temas como: criptografía, estructura de datos, nodos, bloques y minería. Estos conceptos son claves, ya que son la base en la que está conformada esta tecnología, verás como se conecta uno a uno de los conceptos y al final de la sección podrás describir con mayor detalle la teoría detrás del Blockchain.

Cada uno de las modalidades las podrás identificar al lado del nombre de cada lección con los siguientes iconos:

Lectura: :page_facing_up:

Videos: :camera:

Notebooks: :blue_book:

Tour guiado: :dart:
| Módulo | Lección | Descripción | Fuente | Modalidad |
| --- | --- | --- | --- | --- |
| [01 - Conocimiento general de Blockchain](#información-general) | 1. Criptografía | Información general | Estrategía e Innovación de TI & Bancolombia | Lectura |
| [01 - Conocimiento general de Blockchain](#funciones-hash) | 1. Criptografía | [Funciones hash](#funciones-hash) | Estrategía e Innovación de TI & Bancolombia | Lectura :page_facing_up: |
| [01 - Conocimiento general de Blockchain](#cifrado) | 1. Criptografía | [Cifrado: simétrico y asimétrico](#cifrado) | Estrategía e Innovación de TI & Bancolombia | Lectura :page_facing_up: |
| [01 - Conocimiento general de Blockchain](#firmas-digitales) | 1. Criptografía | Firmas digitales | Ejercicios | Ejercicios :dart: |
| [01 - Conocimiento general de Blockchain](#pequeñas-lecciones) | 1. Criptografía | [Serie de rompecabezas que enseñan pequeñas lecciones](#pequeñas-lecciones) | Bit2me | Tour guiado :dart: |
| [01 - Conocimiento general de Blockchain](#arboles-de-merkle) | 2. Estructura de Datos | [Árboles de Merkle](#arboles-de-merkle) | Estrategía e Innovación de TI & Bancolombia | Lectura :page_facing_up: |
| [01 - Conocimiento general de Blockchain](#bloques) | 3. Bloques | [Cadena de bloques](#bloques) | Lectura | Lectura :dart: |
| [01 - Conocimiento general de Blockchain](#nodos) | 4. Nodos | [¿Qué son los nodos blockchain y cómo funcionan?](#nodos) | Lectura | Lectura :dart: |
| [01 - Conocimiento general de Blockchain](#mineria) | 5. Mineria | [Información General](#mineria) | Lectura | Lectura :dart: |

# **Criptografía**

## **Información general**:

- **Descripción:** Exploraremos información general de blockchain. Este módulo te proporcionará una comprensión más profunda de conceptos como funciones hash, llaves y conceptos matemáticos detrás de esta tecnología. Aquí te ofrecemos dos fuentes donde puedes aprender, la primera un poco más corta [aquí](https://cryptobook.nakov.com/cryptography-overview) y la segunda con información más detallada [aquí](https://github.com/ethereumbook/ethereumbook/blob/develop/04keys-addresses.asciidoc).

- **Idioma:** Ingles
- **Contenido:**
    - Criptografía
    - Encriptación y llaves
    - Mensajes de autenticación
    - Secure Random Numbers
    - Librerías de Criptografía

## Funciones Hash:

- **Descripción:** Exploraremos información general de las funciones hash. Te ofrecemos documentación con ejemplos reales de las funciones hash en blockchain [aquí](https://cryptobook.nakov.com/cryptographic-hash-functions). Además, para comprender mejor el proceso de cálculo de hash, puedes acceder a una calculadora interactiva que muestra el paso a paso del cálculo de SHA256 en el siguiente enlace: [Calculadora SHA256](https://sha256algorithm.com/)

- **Idioma:** Ingles
- **Contenido:**
    - Generalidades
    - Hashing (in Software Engineering)
    - Cryptographic Hash Functions
    - Examples

## **Cifrado**:

- **Descripción:** Exploraremos el cifrado o encriptación. Este módulo te proporciona información sobre los tipos de cifrado, tipos de llaves criptográficas, sistemas de encriptación de llaves públicas, etc...  [Aquí](https://cryptobook.nakov.com/encryption-symmetric-and-asymmetric). Además, para entender un poco más el proceso que hay detrás de las curvas elípticas, se sugiere ver el video relacionado que proporciona una explicación detallada sobre este tema. Puedes acceder al video [Aquí](https://www.youtube.com/watch?v=yBr3Q6xiTw4).

- **Idioma:** Ingles
- **Contenido:**
    - Symmetric Encryption - Concepts and Algorithms
      - Secret Keys
      - Modern Symmetric Encryption Algorithms
    - Public Key Cryptography - Concepts
      - Public Key Encryption / Decryption
      - Signatures: Asymmetric Signing / Verification
      - Key Pairs
    - Popular Public Key Cryptosystems
      - The RSA Cryptosystem
      - The ECC Cryptosystem
      - ECC is Recommended in the General Case
    - Asymmetric Encryption in Practice
      - Asymmetric Encryption - Online Demo
    
## **Firmas Digitales**:

- **Descripción:** Exploraremos información relacionada a las firmas digitales. Dentro de su contenido principal están los esquemas y algoritmos de estas. [Aquí](https://cryptobook.nakov.com/digital-signatures).

- **Idioma:** Ingles
- **Contenido:**
    - ¿Cómo funciona?
    - Digital Signature Schemes and Algorithms
      - RSA Signatures
      - DSA (Digital Signature Algorithm)
      - ECDSA (Elliptic Curve Digital Signature Algorithm)
      - EdDSA (Edwards-curve Digital Signature Algorithm)
      - Otros
    
## **Pequeñas Lecciones**:

- **Descripción:** En esta sección reforzarás los conceptos adquiridos a partir de pequeños retos o ejercicios que deberás resolver en el siguiente enlace. [Aquí](https://cryptohack.org/) 

- **Idioma:** Ingles
- **Contenido:**
    - Criptografía
    - Encriptación y llaves
    - Mensajes de autenticación
    - Secure Random Numbers
    - Librerías de Criptografía

# **Estructura de Datos**

## **Arboles de Merkle**:

- **Descripción:** Los árboles de Merkle son estructuras que se usan para validar eficientemente la integridad de nuestra información. [aquí](https://academy.binance.com/es/articles/merkle-trees-and-merkle-roots-explained).

- **Idioma:** Español
- **Contenido:**
    - ¿Qué es un Merkle tree?
    - ¿Cómo funcionan los Merkle trees?
    - ¿Por qué se utilizan las Merkle roots en Bitcoin?
    - Conclusiones

# **Bloques**

## **Cadena de Bloques**:

- **Descripción:** Exploraremos información general de blockchain. [aquí](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch11_blockchain.adoc). De esta información de invitamos a leer las secciones:

- **Idioma:** Ingles
- **Contenido:**
    - Structure of a Block
      - Block Header
      - Block Identifiers: Block Header Hash and Block Height
    - The Genesis Block
    - Linking Blocks in the Blockchain

# **Nodos**

## **¿Qué son los nodos blockchain y cómo funcionan?**:

- **Descripción:** En esta sección aprederás sobre los nodos. Aquí te ofrecemos una fuente de información muy completa, aqui verás detalle a detalle todo lo que necesitas saber [aquí](https://builtin.com/blockchain/blockchain-node).

- **Idioma:** Ingles
- **Contenido:**
    - What Is a Blockchain Node?
    - Why Are Blockchain Nodes Needed?
    - How Do Blockchain Nodes Work?
    - 10 Types of Blockchain Nodes

# **Mineria**

## **Información general**:

- **Descripción:** La minería blockchain es un componente esencial para mantener la integridad, seguridad y descentralización de las redes basadas en esta tecnología, asegurando que los nuevos bloques sean agregados a la cadena de bloques de manera segura y verificable. En esta sección conocerás con más detalle sobre este concepto. [Aquí](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch12_mining.adoc). Te recomendamos mayor atención en secciones que consideramos claves, las cuales listamos a continuación.

- **Idioma:** Ingles
- **Contenido:**
    - Introducción
    - Independent Verification of Transactions
    - Mining nodes
    - Aggregating Transactions into Blocks
    - Mining the Block
    - Successfully Mining the Block
    - Validating a New Block
    - Assembling and Selecting Chains of Blocks
    - Changing the Consensus Rules
