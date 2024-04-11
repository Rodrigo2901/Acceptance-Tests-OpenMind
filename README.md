<table>
  <tr>
    <td>E10</td>
    <td>Implementación de Seguridad en el RESTful API</td>
    <td>Implementar las funcionalidades de seguridad necesarias en el RESTful API para garantizar la autenticación y autorización adecuadas de los usuarios.</td>
  </tr>
</table>

<table>
   <td>US26</td>
    <td>Autenticación de Usuarios a través de API</td>
    <td>Como Developer, quiero implementar una API de autenticación de usuarios que permita a los clientes autenticarse y obtener un token de acceso para acceder a las funciones protegidas de la API.</td>
    <td>Escenario 1: 
Dado que el Developer recibe las credenciales de inicio de sesión del cliente. 
Cuando las envía a la API de autenticación. 
Entonces la API verifica las credenciales y devuelve un token de acceso válido si son correctas.

Escenario 2:
Dado que el cliente proporciona un token de acceso caducado.
Cuando lo envía a la API en una solicitud protegida. Entonces la API devuelve un error indicando que el token ha caducado y solicita al cliente que vuelva a autenticarse.
</td>
    <td>E10</td>
 </tr>
    <td>US27</td>
    <td>Creación de Nuevos Usuarios a través de API</td>
    <td>Como Developer, quiero implementar una API que permita a los clientes crear nuevos usuarios en el sistema.</td>
    <td>Escenario 1: 
Dado que el cliente envía una solicitud de creación de usuario a la API. 
Cuando proporciona los datos necesarios para crear un nuevo usuario. 
Entonces la API crea el usuario y devuelve un mensaje de confirmación.

Escenario 2:
Dado que el cliente intenta crear un usuario con credenciales inválidas o incompletas.
Cuando envía una solicitud de creación de usuario a la API.
Entonces la API devuelve un error indicando los campos inválidos o faltantes.
</td>
    <td>E10</td>
 </tr>
    <td>US28</td>
    <td>Gestión de Proyectos a través de API</td>
    <td>Como Developer, quiero implementar una API que permita a los clientes gestionar proyectos en el sistema, incluyendo la creación, actualización y eliminación de proyectos.</td>
    <td>Escenario 1: 
Dado que el cliente envía una solicitud de creación de proyecto a la API. 
Cuando proporciona los datos necesarios para crear un nuevo proyecto. 
Entonces la API crea el proyecto y devuelve un mensaje de confirmación.

Escenario 2:
Dado que el cliente envía una solicitud de actualización de proyecto a la API.
Cuando proporciona los datos actualizados para un proyecto existente.
Entonces la API actualiza el proyecto y devuelve un mensaje de confirmación.

Escenario 3:
Dado que el cliente envía una solicitud de eliminación de proyecto a la API.
Cuando proporciona el identificador de un proyecto existente.
Entonces la API elimina el proyecto y devuelve un mensaje de confirmación.
</td>
    <td>E10</td>
 </tr>
    <td>US29</td>
    <td>Gestión de Cotizaciones a través de API</td>
    <td>Como Developer, quiero implementar una API que permita a los clientes gestionar cotizaciones en el sistema, incluyendo la creación, actualización y eliminación de cotizaciones.</td>
    <td>Escenario 1: 
Dado que el cliente envía una solicitud de creación de cotización a la API. 
Cuando proporciona los datos necesarios para crear una nueva cotización. 
Entonces la API crea la cotización y devuelve un mensaje de confirmación.

Escenario 2:
Dado que el cliente envía una solicitud de actualización de cotización a la API.
Cuando proporciona los datos actualizados para una cotización existente.
Entonces la API actualiza la cotización y devuelve un mensaje de confirmación.

Escenario 3:
Dado que el cliente envía una solicitud de eliminación de cotización a la API.
Cuando proporciona el identificador de una cotización existente.
Entonces la API elimina la cotización y devuelve un mensaje de confirmación.
</td>
    <td>E10</td>
 </tr>
</table>
