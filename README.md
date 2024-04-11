<table>
    <th>Epic ID</th>
    <th>Título</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>E01</td>
    <td>Creación y Gestión de Cuentas de Usuario</td>
    <td>Desarrollar la funcionalidad de registro, inicio de sesión y gestión de cuentas de usuario.</td>
  </tr>
   <tr>
   <td>E02</td>
    <td>Búsqueda y Filtrado de Empresas de Postes.</td>
    <td>Implementar la funcionalidad de búsqueda y filtrado para permitir a las empresas de telecomunicaciones encontrar empresas de instalación de postes según sus necesidades.</td>
  </tr>
   <tr>
    <td>E03</td>
    <td>Gestión de Proyectos de Instalación de Postes.</td>
    <td>Desarrollar la funcionalidad para que las empresas de instalación de postes gestionen sus proyectos de manera efectiva desde la plataforma.</td>
  </tr>
</table>

<table>
  <tr>
    <th>Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionados con Epic (Epic ID)</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Registro de nuevo usuario</td>
    <td>Como visitante al sitio web, quiero poder registrarme como usuario para acceder a las funciones de la plataforma.</td>
    <td>Escenario 1:
Dado que el usuario accede al formulario de registro.
Cuando haga clic en el botón de registro desde la página de inicio.
Entonces se muestra un formulario de registro con campos para ingresar la información requerida.

Escenario 2:
Dado que el usuario completa todos los campos del formulario de registro.
Cuando envía la solicitud de registro.
Entonces se crea una nueva cuenta de usuario y se redirige al usuario a la página de inicio de sesión.

Escenario 3:
Dado que el usuario intenta registrarse con un correo electrónico que ya está en uso.
Cuando envía la solicitud de registro.
Entonces se muestra un mensaje de error indicando que el correo electrónico ya está registrado y se le sugiere iniciar sesión en su lugar.
</td>
    <td>E01</td>
  </tr>
   <tr>
    <td>US02</td>
    <td>Inicio de sesión de usuario</td>
    <td>Como usuario registrado, quiero poder iniciar sesión en mi cuenta para acceder a las funciones.</td>
    <td>Escenario 1:
Dado que el usuario accede al formulario de inicio de sesión.
Cuando haga clic en el enlace de inicio de sesión desde la página de inicio.
Entonces se muestra un formulario de inicio de sesión con campos para ingresar correo electrónico y contraseña.

Escenario 2:
Dado que el usuario ingresa las credenciales correctas.
Cuando envía la solicitud de inicio de sesión.
Entonces se autentica al usuario y se le redirige al panel de control de su cuenta.

Escenario 3:
Dado que el usuario olvida su contraseña.
Cuando haga clic en el enlace de recuperación de contraseña.
Entonces se le redirige a una página donde puede restablecer su contraseña mediante un correo electrónico de restablecimiento.
</td>
    <td>E01</td>
  </tr>
      <td>US03</td>
    <td>Gestión de Perfil de Usuario</td>
    <td>Como usuario registrado, quiero poder editar mi perfil y actualizar mi información personal.</td>
    <td>Escenario 1:
Dado que el usuario accede a la página de configuración de perfil.
Cuando desde el panel de control, hace clic en la opción de editar perfil.
Entonces se muestra un formulario rellenado con la información actual del usuario.

Escenario 2:
Dado que el usuario realiza cambios en su perfil.
Cuando edita y guarda los cambios.
Entonces la información del perfil se actualiza correctamente en la base de datos.

Escenario 3:
Dado que el usuario desea cambiar su contraseña.
Cuando accede a la página de configuración de contraseña.
Entonces se le permite cambiar su contraseña, y la nueva contraseña se almacena de forma segura en la base de datos.
</td>
    <td>E01</td>
  </tr>
</td>
   </tr>
      <td>US04</td>
    <td>Búsqueda por ubicación</td>
    <td>Como usuario, quiero poder buscar empresas de instalación de postes por ubicación para encontrar opciones cercanas a una área específica.</td>
    <td>Escenario 1:
Dado que el usuario accede a la página de búsqueda.
Cuando desde el panel de control, selecciona la opción de búsqueda por ubicación.
Entonces se muestra un mapa interactivo donde el usuario puede ingresar una ubicación o hacer clic en un punto en el mapa.

Escenario 2:
Dado que el usuario ingresa una ubicación específica.
Cuando completa el campo de búsqueda con una dirección o coordenadas.
Entonces se muestran las empresas de instalación de postes cercanas a esa ubicación, ordenadas por distancia.

Escenario 3:
Dado que el usuario hace clic en una empresa de postes en el mapa.
Cuando selecciona un marcador en el mapa.
Entonces se muestra información detallada sobre esa empresa de instalación de postes, como su nombre, dirección y servicios ofrecidos.
</td>
    <td>E02</td>
  </tr>
    </tr>
      <td>US05</td>
    <td>Filtrado por servicios ofrecidos</td>
    <td>Como usuario, quiero poder filtrar las empresas de instalación de postes por los servicios específicos que ofrecen.</td>
    <td>Escenario 1:
Dado que el usuario accede a la página de búsqueda.
Cuando desde el panel de control, selecciona la opción de filtrar por servicios.
Entonces se muestran opciones de filtro que incluyen diferentes servicios relacionados con la instalación de postes de fibra óptica.

Escenario 2:
Dado que el usuario selecciona un servicio específico.
Cuando marca la casilla correspondiente en el menú de filtrado.
Entonces se muestran solo las empresas de instalación de postes que ofrecen ese servicio en particular.

Escenario 3:
Dado que el usuario selecciona múltiples servicios para filtrar.
Cuando marca varias casillas de servicios en el menú de filtrado.
Entonces se muestran las empresas de instalación de postes que ofrecen todos los servicios seleccionados, cumpliendo con todos los criterios de filtro.
</td>
    <td>E02</td>
  </tr>
    </tr>
      <td>US06</td>
    <td>Visualización de resultados de búsqueda</td>
    <td>Como usuario, quiero poder ver los resultados de mi búsqueda de manera clara y ordenada.</td>
    <td>Escenario 1:
Dado que el usuario realiza una búsqueda.
Cuando ingresa sus criterios de búsqueda y envía la solicitud.
Entonces se muestran los resultados de manera clara, con información relevante como el nombre de la empresa y su ubicación.

Escenario 2:
Dado que la búsqueda no arroja resultados.
Cuando el usuario ingresa criterios de búsqueda que no coinciden con ninguna empresa de instalación de postes.
Entonces se muestra un mensaje indicando que no se encontraron resultados coincidentes y se le sugiere al usuario que intente con diferentes criterios de búsqueda.

Escenario 3:
Dado que el usuario desea ver más detalles sobre una empresa de postes.
Cuando se hace clic en el nombre de una empresa en los resultados de búsqueda.
Entonces se muestra una ventana emergente o una página nueva con información detallada sobre esa empresa.
</td>
    <td>E02</td>
  </tr>
</tr>
    </tr>
      <td>US07</td>
    <td>Recepción de Solicitudes de Cotización</td>
    <td>Como empresa de instalación de postes, quiero recibir solicitudes de cotización de las empresas de telecomunicaciones interesadas en mis servicios.</td>
    <td>Escenario 1:
Dado que la empresa de telecomunicaciones selecciona la opción de solicitar cotización.
Cuando completa un formulario con detalles sobre el proyecto.
Entonces se genera automáticamente una solicitud de cotización y se envía a la empresa de instalación de postes seleccionada.

Escenario 2:
Dado que la empresa de instalación de postes recibe una solicitud de cotización.
Cuando accede a su panel de control.
Entonces se muestra la solicitud con todos los detalles proporcionados por la empresa de telecomunicaciones.

Escenario 3:
Dado que la empresa de instalación de postes desea responder a la solicitud.
Cuando revisa los detalles del proyecto y determina un precio.
Entonces envía una cotización detallada a la empresa de telecomunicaciones a través de la plataforma.
</td>
    <td>E03</td>
  </tr>
    </tr>
      <td>US08</td>
    <td>Gestión de Proyectos Asignados</td>
    <td>Como empresa de instalación de postes, quiero poder gestionar los proyectos asignados de manera efectiva para garantizar su finalización exitosa.</td>
    <td>Escenario 1:
Dado que la empresa de instalación de postes recibe una solicitud de proyecto.
Cuando se acepta una solicitud de cotización y se convierte en un proyecto asignado.
Entonces el proyecto se añade automáticamente a la lista de proyectos activos en el panel de control de la empresa.

Escenario 2:
Dado que la empresa de instalación de postes desea asignar recursos al proyecto.
Cuando accede a los detalles del proyecto.
Entonces puede asignar empleados, materiales y equipos necesarios para completar el proyecto.

Escenario 3:
Dado que la empresa de instalación de postes actualiza el estado del proyecto.
Cuando hay avances significativos en el proyecto.
Entonces actualiza el estado del proyecto en la plataforma, indicando si está en progreso, completado o pendiente de aprobación.
</td>
    <td>E03</td>
  </tr>
   </tr>
      <td>US09</td>
    <td>Comunicación con los clientes</td>
    <td>Como empresa de instalación de postes, quiero poder comunicarme de manera efectiva con mis clientes a través de la plataforma.</td>
    <td>Escenario 1:
Dado que el cliente solicita actualizaciones sobre el proyecto.
Cuando accede al panel de control y envía un mensaje a la empresa de instalación de postes.
Entonces la empresa recibe la solicitud de información y puede responder directamente desde la plataforma.

Escenario 2:
Dado que la empresa de instalación de postes desea enviar actualizaciones periódicas.
Cuando hay cambios importantes en el proyecto.
Entonces puede enviar notificaciones automáticas o mensajes personalizados a los clientes para mantenerlos informados sobre el progreso del proyecto.

Escenario 3:
Dado que el cliente tiene una queja o consulta.
Cuando envía un mensaje a través de la plataforma.
Entonces la empresa de instalación de postes recibe la notificación y puede responder de manera oportuna para resolver el problema o responder a la consulta.
</td>
    <td>E03</td>
    </tr>
</table>
