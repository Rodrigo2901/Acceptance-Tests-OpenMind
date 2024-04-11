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
   <tr>
    <td>E04</td>
    <td>Funcionalidades Avanzadas de Interacción</td>
    <td>Desarrollar funcionalidades avanzadas para mejorar la interacción entre las empresas de telecomunicaciones y las empresas de instalación de postes.</td>
  </tr>
   <tr>
    <td>E05</td>
    <td>Mejora de la Experiencia del Usuario</td>
    <td>Mejorar la experiencia del usuario en la plataforma para garantizar una navegación intuitiva y una interacción fluida.</td>
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
 <td>US10</td>
    <td>Calificación y Comentarios sobre Empresas</td>
    <td>Como usuario, quiero poder calificar y dejar comentarios sobre las empresas de instalación de postes con las que he trabajado para ayudar a otros usuarios en sus decisiones.</td>
    <td>Escenario 1:
Dado que el usuario accede a la página de perfil de una empresa.
Cuando desde los resultados de búsqueda o la lista de proyectos, hace clic en el nombre de una empresa.
Entonces se muestra la información detallada de la empresa, incluida su calificación actual y los comentarios de otros usuarios.

Escenario 2:
Dado que el usuario desea dejar una calificación.
Cuando accede a la página de perfil de una empresa.
Entonces puede seleccionar una calificación de estrellas y escribir un comentario opcional sobre su experiencia con la empresa.

Escenario 3:
Dado que el usuario visualiza las calificaciones y comentarios de otras personas.
Cuando busca empresas de instalación de postes o revisa su historial de proyectos.
Entonces puede ver las calificaciones promedio y los comentarios de otros usuarios sobre cada empresa.
</td>
    <td>E04</td>
  </tr>
    </tr>
      <td>US11</td>
    <td>Notificaciones Personalizadas</td>
    <td>Como usuario, quiero recibir notificaciones personalizadas sobre actualizaciones relevantes y eventos importantes.</td>
    <td>Escenario 1:
Dado que el usuario accede a la página de configuración de notificaciones.
Cuando desde su perfil, accede a la configuración de notificaciones.
Entonces puede seleccionar qué tipos de notificaciones desea recibir.

Escenario 2:
Dado que el usuario recibe una notificación.
Cuando ocurre un evento relevante según la configuración del usuario.
Entonces recibe una notificación instantánea en la plataforma y/o un correo electrónico, según sus preferencias.

Escenario 3:
Dado que el usuario desea desactivar ciertas notificaciones.
Cuando cambia su configuración de notificaciones.
Entonces puede desactivar notificaciones específicas.
</td>
    <td>E04</td>
  <td>US12</td>
    <td>Diseño Responsivo</td>
    <td>Como usuario, quiero que la interfaz se adapte automáticamente a diferentes dispositivos y tamaños de pantalla para una experiencia consistente en cualquier dispositivo.</td>
    <td>Escenario 1:
Dado que el usuario accede a la plataforma desde un dispositivo móvil.
Cuando carga la página de inicio o cualquier otra página dentro de la plataforma.
Entonces todos los elementos de la interfaz se reorganizan y ajustan para adaptarse a la pantalla más pequeña, manteniendo la usabilidad y la legibilidad.

Escenario 2:
Dado que el usuario accede a la plataforma desde una tableta.
Cuando navega por diferentes secciones y funciones de la plataforma.
Entonces la interfaz se ajusta automáticamente para aprovechar el espacio disponible en la pantalla, proporcionando una experiencia de usuario cómoda y funcional.

Escenario 3:
Dado que el usuario accede a la plataforma desde un ordenador de escritorio.
Cuando utiliza la plataforma en una pantalla grande.
Entonces la interfaz se expande para aprovechar al máximo el espacio disponible.
</td>
    <td>E05</td>
  </tr>
    </tr>
      <td>US13</td>
    <td>Mejora de la navegación</td>
    <td>Como usuario, quiero una navegación clara y consistente para poder encontrar rápidamente la información que necesito.</td>
    <td>Escenario 1:
Dado que el usuario accede a la plataforma desde cualquier dispositivo y conexión a internet.
Cuando carga cualquier página dentro de la plataforma.
Entonces la página se carga completamente en menos de 3 segundos, proporcionando una experiencia de usuario fluida y sin esperas.

Escenario 2:
Dado que el usuario accede a la plataforma en momentos de alta demanda.
Cuando navega por la plataforma durante horas pico o períodos de carga elevada.
Entonces la velocidad de carga de las páginas se mantiene constante y no se ven afectadas por la carga del servidor.

Escenario 3:
Dado que el usuario accede a la plataforma desde una conexión de datos móviles.
Cuando utiliza la plataforma en un entorno con conexión a internet móvil.
Entonces las páginas se cargan rápidamente incluso en conexiones más lentas, gracias a la optimización de imágenes y recursos.
</td>
    <td>E05</td>
  </tr>
    </tr>
      <td>US14</td>
    <td>Optimización de la velocidad de carga</td>
    <td>Como usuario, quiero que las páginas carguen rápidamente para poder acceder a la información y funciones sin demoras.</td>
    <td>Escenario 1:
Dado que el usuario accede a la plataforma desde cualquier página.
Cuando busca un menú de navegación.
Entonces encuentra un menú claramente visible y fácil de usar que le permite acceder a todas las secciones principales de la plataforma.

Escenario 2:
Dado que el usuario desea volver a la página de inicio.
Cuando navega por diferentes secciones de la plataforma.
Entonces encuentra un enlace de "Inicio" o un botón de logo que le permite volver a la página de inicio en cualquier momento.

Escenario 3:
Dado que el usuario desea acceder a funciones específicas desde cualquier página.
Cuando necesita acceder a su perfil, configuración o funciones principales de la plataforma.
Entonces encuentra enlaces o botones consistentes en todas las páginas que le permiten acceder a estas funciones de manera rápida y directa.
</td>
    <td>E05</td>
  </tr>
    </tr>
</table>
