# **Rutas de concimiento - Experto en seguridad de Web 3.0**

La seguridad Web3 se refiere a las medidas tomadas para proteger las aplicaciones descentralizadas (dApps) y las redes blockchain de ataques. Web3 es una nueva iteración de Internet que se basa en tecnologías descentralizadas, como blockchain. Esto significa que no existe una autoridad central que controle estos sistemas, lo que los hace más vulnerables a los ataques.

Los expertos de seguridad de Web3 juegan un papel vital en la protección de la integridad, confidencialidad y disponibilidad de los sistemas Web3. Lo hacen realizando auditorías de seguridad, identificando y mitigando vulnerabilidades, implementando las mejores prácticas de seguridad y respondiendo a incidentes de seguridad.

Su rol es clave ya que:

* La tecnología Blockchain sigue siendo una tecnología relativamente nueva y emergente, y hay muchas vulnerabilidades de seguridad que aún no se han descubierto.

* La naturaleza descentralizada de la tecnología blockchain dificulta la implementación de medidas de seguridad tradicionales, como firewalls y sistemas de detección de intrusos.

* El valor financiero de algunos activos basados en blockchain, como las criptomonedas, los convierte en objetivos atractivos para los delincuentes.

Esta guía presenta una serie de conceptos junto con su bibliografía que ayudaran a formar al experto divididos en 15 categorías

* Fundamentos de Internet
* Modelos de autenticación/autorización existentes en aplicaciones Web2.0
* Top 10 de OWASP
* Conceptos básicos de Ethereum
* Contratos inteligentes
* Solidity
* Testing Frameworks
* Vectores de ataque DEFI:
* Librerias y estándares de token que se usan comúnmente:
* Seguridad de contratos inteligentes
* Vulnerabilidades en contratos inteligentes
* Errores de contratos inteligentes y mejores prácticas de seguridad
* CTF y sus retos
* Informes de Auditoría:

Adcionalmente es importante como insumo tener claro los conceptos propuestos en [conocimiento general](../conocmiento_general/conocimiento_general.md)

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
      <td>:camera:</td>
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


