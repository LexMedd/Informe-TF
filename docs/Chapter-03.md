# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Luego de realizar el as-is con sus fases propuestas, para el to-be se realizaron nuevos procesos enfocados en mejorar las fases de los segmentos objetivos con nuestro proyecto. 

**_Segmento Objetivo 1: Abogados especializados en derecho médico_**
![alt text](<https://raw.githubusercontent.com/LexMedd/Informe-TF/Chapter-03/assets/imgs/TOBE%20scenario%20abogados.jpeg>)

**_Segmento Objetivo 2: Doctores que enfrentan problemas legales por mala praxis_**
![alt text](<https://raw.githubusercontent.com/LexMedd/Informe-TF/Chapter-03/assets/imgs/TOBE%20scenario%20doctores.jpeg>)

## 3.2. User Stories

Los User Stories describen las funciones de la aplicación adaptadas a las necesidades y prioridades de los usuarios, proporcionando una comprensión más completa de cómo se relacionan con la plataforma y qué esperan lograr con ella.

EPIC|Título|Descripción|
| :-: | :-: | :-: |
|EP01|Gestión de Cuentas de Usuario|Como usuario, quiero registrarme, iniciar sesión y gestionar mi cuenta para acceder de manera segura a la aplicación y mantener mis datos personales actualizados.|
|EP02|Navegación Intuitiva y Accesible|Como usuario quiero un sistema de navegación que me permita acceder rápidamente a las funciones principales, como buscar y gestionar casos, usar el chat para el seguimiento y actualizar mi perfil, mejorando mi experiencia en LexMed.|
|EP03|Landing Page Informativa|Como usuario interesado, quiero una landing page clara, atractiva y fácil de entender, que me informe sobre LexMed y los servicios que ofrece, para que pueda tomar una decisión informada sobre su uso.|
|EP04|Gestión de Tarifas y Solicitudes de Casos para Abogados|Como Abogado, quiero gestionar tarifas y solicitudes de casos para evaluar y aceptar aquellos que se ajusten a mis criterios, permitiendo una mejor organización y eficiencia en mi trabajo.|
|EP05|Redirección Accesible desde la Landing Page|Como visitante de la landing page, quiero componentes que me redirijan fácilmente a las diferentes secciones de la plataforma para disfrutar de los servicios que ofrece LexMed|
|EP06|Sistema de Navegación para Visualización de Casos|Como abogado, quiero un sistema de navegación eficiente y fácil de usar que me permita visualizar y organizar de manera clara y detallada los casos de mala praxis o asesoría legal, para poder gestionarlos y analizar mejor la información relevante a cada caso|
|EP07|Gestión de Presupuesto y Tarifas para Casos Legales|Como médico, quiero gestionar y comparar propuestas de tarifas de abogados, con el fin de seleccionar al abogado más adecuado para llevar mi caso, asegurando que se ajuste a mis necesidades y presupuesto.|


| | | | | |
|-|-|-|-|-|
|ID |Título |Descripción |Criterios de Aceptación| Relacionado con (Epic ID)|
|EP01|Registro de Usuario|Como usuario, quiero registrarme para crear una cuenta y acceder a las funcionalidades de la aplicación de manera segura.|Escenario 1: Registro Exitoso Dado que el usuario está en la página de registro, Cuando ingresa todos los datos requeridos de manera correcta y presiona "Crear", Entonces la cuenta se creará correctamente Y el usuario será redirigido a la página de inicio de sesión. Escenario 2: Error en el Registro Dado que el usuario está en la página de registro, Cuando ingresa datos faltantes o incorrectos, Entonces el sistema no te dejara crear cuenta Y resaltará los campos que necesitan corrección.|EP01|
|EP02| Inicio de Sesión|Como usuario, quiero iniciar sesión con mi cuenta para acceder de manera segura a la aplicación.|Escenario 1: Inicio de Sesión Exitoso Dado que el usuario está en la página de inicio de sesión, Cuando introduce sus credenciales correctas y presiona "Iniciar Sesión", Entonces será autenticado correctamente Y redirigido al panel principal de la aplicación.  Escenario 2: Error en el Inicio de Sesión Dado que el usuario está en la página de inicio de sesión, Cuando introduce credenciales incorrectas, Entonces el sistema no permitirá el acceso.|EP01|
|EP03|Navegación Rápida a Funciones Principales|Como usuario, quiero navegar fácilmente a las funciones principales como buscar y gestionar casos, usar el chat, y actualizar mi perfil para mejorar mi experiencia en LexMed.|Escenario 1: Navegación Fluida Dado que el usuario está en el panel principal, Cuando hace clic en "Gestionar Casos", Entonces será redirigido rápidamente a la sección de gestión de casos Y verá la lista de sus casos activos.  Escenario 2: Acceso al Perfil Dado que el usuario está en el panel principal, Cuando selecciona "Perfil", Entonces accederá a la página de edición de su perfil Y podrá actualizar su información personal.|EP02|
|EP04|Información Clara en la Landing Page|Como usuario interesado, quiero ver una landing page que me informe sobre LexMed y los servicios que ofrece para poder entender mejor la plataforma.|Escenario 1: Visualización de Servicios Dado que el usuario está en la landing page, Cuando carga la página, Entonces podrá ver información clara sobre los servicios principales de LexMed Y se presentarán de manera atractiva y organizada.  Escenario 2: Botón de Registro Visible Dado que el usuario está en la landing page, Cuando revisa la información, Entonces verá un botón de "Contact" claramente visible Y podrá hacer clic para proceder al registro.|EP03|
|EP05|Gestión de Tarifas de Casos para Abogados|como abogado, quiero gestionar las tarifas y solicitudes de casos para evaluar y aceptar aquellos que cumplan con mis criterios.|Escenario 1: Evaluación de Solicitudes Dado que el abogado está en el panel de casos, Cuando revisa una nueva solicitud de caso, Entonces podrá ver los detalles del caso y la tarifa propuesta Y decidir si aceptarla o rechazarla.  Escenario 2: Modificación de Tarifas Dado que el abogado está en el panel de tarifas, Cuando selecciona un caso pendiente, Entonces podrá ajustar la tarifa propuesta Y enviarla nuevamente al cliente para su aprobación.|EP04|
|EP07|Redirección Rápida desde la Landing Page|Como visitante de la landing page, quiero componentes interactivos que me redirijan fácilmente a diferentes secciones de la plataforma.|Escenario 1: Redirección a Registro Dado que el visitante está en la landing page, Cuando hace clic en "Registrarse", Entonces será redirigido inmediatamente al formulario de registro Y podrá comenzar el proceso de creación de cuenta.  Escenario 2: Redirección a Información de Servicios Dado que el visitante está en la landing page, Cuando hace clic en "Ver Servicios", Entonces será redirigido a la sección que detalla los servicios de LexMed Y podrá explorar más información.|EP05|
|EP08| Visualización y Organización de Casos para Abogados|Como abogado, quiero un sistema que me permita visualizar y organizar de manera clara los casos de mala praxis o asesoría legal para gestionarlos de manera eficiente.|Escenario 1: Visualización de Casos Dado que el abogado está en la sección de casos, Cuando selecciona un caso específico, Entonces podrá ver todos los detalles relevantes del caso Y acceder a documentos asociados.  Escenario 2: Organización por Estado Dado que el abogado está en la sección de gestión de casos, Cuando filtra los casos por estado (activo, cerrado, pendiente), Entonces podrá ver solo los casos que coincidan con ese estado Y organizarlos para un mejor seguimiento.|EP06|
|EP09|Comparación de Tarifas para Médicos|Como médico, quiero gestionar y comparar propuestas de tarifas de abogados para seleccionar al más adecuado para mi caso.|Escenario 1: Comparación de Tarifas Dado que el médico está en la sección de "propuestas", Cuando recibe múltiples propuestas, Entonces podrá comparar las tarifas y detalles de cada abogado Y seleccionar la opción que mejor se ajuste a sus necesidades.  Escenario 2: Selección de Abogado Dado que el médico ha revisado las propuestas, Cuando elige una propuesta de tarifa, Entonces podrá aceptar la oferta Y proceder con el abogado seleccionado.|EP07|
|EP10|Actualización de Datos de Perfil|Como usuario, quiero actualizar mi información de perfil para mantener mis datos personales siempre actualizados.|Escenario 1: Actualización Exitosa Dado que el usuario está en la página de perfil, Cuando modifica su información y hace clic en "Guardar", Entonces los datos serán actualizados correctamente. Escenario 2: Error en la Actualización Dado que el usuario está en la página de perfil, Cuando intenta guardar datos incorrectos o incompletos, Entonces el sistema no podrá hacer los cambios.|EP01|
|EP11|Búsqueda de Casos por Criterios Específicos|omo usuario, quiero buscar casos mediante criterios específicos, como nombre del cliente o fecha de creación, para encontrar rápidamente el caso que necesito.|Búsqueda Exitosa Dado que el usuario está en la página de gestión de casos, Cuando ingresa criterios de búsqueda válidos, Entonces el sistema mostrará una lista filtrada de casos Y el caso deseado estará visible. Escenario 2: Sin Resultados Dado que el usuario está en la página de gestión de casos, Cuando ingresa criterios de búsqueda que no coinciden con ningún caso, Entonces el sistema mostrará un mensaje de "Sin resultados" Y permitirá ajustar los criterios.|EP02|
|EP12|Solicitud de Nueva Propuesta de Caso|Como abogado, quiero recibir solicitudes de nuevos casos de clientes para evaluarlos y decidir si aceptarlos.|Escenario 1: Recepción del Nuevo Caso Dado que el abogado está en la sección de "casos", Cuando un medico envía una solicitud de caso, Entonces el abogado verá una notificación de nueva caso Y podrá revisarla. Escenario 2: Evaluación del Caso Dado que el abogado revisa el nuevo caso, Cuando el caso cumple con sus criterios, Entonces podrá aceptarla Y el medico será notificado de la aceptación.|EP04|
|EP13|Gestión de Notificaciones|Como usuario, quiero recibir notificaciones sobre actualizaciones en mis casos o solicitudes para estar al tanto de los cambios importantes.|Escenario 1: Notificación de Nueva Solicitud Dado que el medico ha enviado una solicitud de caso, Cuando el estado de la solicitud cambia, Entonces el sistema enviará una notificación Y el medico  podrá revisarla desde "gestion de casos". Escenario 2: Notificación de Actualización de Caso Dado que el abogado o médico tiene un caso activo, Cuando hay una actualización en el estado del caso, Entonces el sistema enviará una notificación Y el usuario podrá ver los detalles del cambio.|EP02|
|EP14|Filtros de Búsqueda en el Historial de Casos|Como medico, quiero utilizar filtros avanzados para buscar casos,  como por fecha , demografico, para acceder rápidamente a la información relevante.|Escenario 1: Filtro por Fecha  Dado que el abogado está en la página de "mis casos", Cuando selecciona un filtro por fecha, Entonces el sistema mostrará solo los casos que cumplen con ese filtro. Escenario 2: Filtro  geografico Dado que el usuario busca casos específicos, Cuando aplica un filtro por tipo de geografía, Entonces solo se mostrarán los casos correspondientes a ese tipo Y podrá revisarlos más fácilmente.|EP02|
|EP15|Chat para Seguimiento de Casos|Como usuario, quiero usar el chat integrado para hacer seguimiento en tiempo real de la evolución de mis casos con los profesionales involucrados.|Escenario 1: Enviar Mensaje Exitosamente Dado que el usuario está en la pagina "mensajes", Cuando escribe y envía un mensaje en el chat, Entonces el mensaje será enviado Y el destinatario lo recibirá instantáneamente.  Escenario 2: Recepción de Respuesta Dado que el usuario ha enviado un mensaje, Cuando el destinatario responde, Entonces el usuario recibirá una notificación en el chat Y podrá ver la respuesta en tiempo real.|EP02|
|EP16|Recuperación de Contraseña|Como usuario, quiero poder recuperar mi contraseña en caso de olvidarla para acceder nuevamente a mi cuenta.|Escenario 1: Recuperación Exitosa Dado que el usuario ha olvidado su contraseña, Cuando ingresa  al inicio, Entonces hara clic en "olvide mi contraseña"  Y podrá restablecer su contraseña con éxito.  Escenario 2: Error en el Cambio de Contraseña Dado que el usuario intenta recuperar su contraseña, Cuando no cumple con los criterios, Entonces el sistema no dejará cambiar tu contraseña|EP01|

    
## 3.4. Product Backlog

<table>
    <tr>
        <th>Orden</th>
        <th>User Story/Technical Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
    </tr>
    <tr>
        <td>1</td>
        <td>US29</td>
        <td>Gestión de Suscripciones</td>
        <td>Como desarrollador, quiero implementar la gestión de suscripciones para que los usuarios puedan ver, seleccionar y administrar sus planes de suscripción en la plataforma.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>2</td>
        <td>US26</td>
        <td>Implementación de la funcionalidad de búsqueda de abogados</td>
        <td>Como desarrollador, quiero agregar una función de búsqueda en la página de lista de abogados para que los usuarios puedan buscar abogados por nombre o especialidad.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>3</td>
        <td>US19</td>
        <td>Base de datos de usuarios</td>
        <td>Como administrador, quiero implementar una base de datos segura y escalable, para proteger y gestionar eficazmente la información de los usuarios.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>4</td>
        <td>US18</td>
        <td>Integración de pagos</td>
        <td>Como administrador, quiero integrar un sistema de pagos seguro para gestionar las suscripciones y compras en la plataforma.</td>
        <td>2</td>
    </tr>
   <tr>
        <td>5</td>
        <td>US17</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de LEXMED, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>6</td>
        <td>US16</td>
        <td>Sección de Creadores</td>
        <td>Como visitante de la landing page de LEXMED, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>7</td>
        <td>US15</td>
        <td>Sección about us</td>
        <td>Como visitante de la landing page de LEXMED, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>8</td>
        <td>US11</td>
        <td>Postulación a un caso por parte de un abogado</td>
        <td>Como abogado quiero postularme para representar un caso específico publicado por un médico.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>9</td>
        <td>US10</td>
        <td>Notificación de nuevos casos al abogado</td>
        <td>Como abogado quiero recibir una notificación cuando un nuevo caso relacionado con mi área de especialización es publicado.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>10</td>
        <td>US05</td>
        <td>Notificación al médico sobre el interés de un abogado</td>
        <td>Como médico quiero recibir una notificación cuando un abogado se interese en mi caso.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>11</td>
        <td>US02</td>
        <td>Solicitud de casos por parte de un abogado</td>
        <td>Como abogado especializado en derecho médico solicito recibir casos relacionados con mi área de expertise.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>12</td>
        <td>US01</td>
        <td>Registro de un nuevo abogado especializado</td>
        <td>Como abogado especializado en derecho médico quiero registrarme en la plataforma LEXMED para ofrecer mis servicios.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>13</td>
        <td>US39</td>
        <td>Respuesta a solicitudes de contacto de abogados</td>
        <td>Como médico quiero responder a las solicitudes de contacto de los abogados interesados en mi caso.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>14</td>
        <td>US38</td>
        <td>Evaluación de la calidad del servicio por parte del médico</td>
        <td>Como médico quiero evaluar la calidad del servicio del abogado después de completar el caso.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>15</td>
        <td>US24</td>
        <td>Soporte para Múltiples Navegadores</td>
        <td>Como desarrollador, quiero garantizar la compatibilidad en múltiples navegadores para una experiencia de usuario uniforme.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>16</td>
        <td>US33</td>
        <td>Obtener una Notificación por ID</td>
        <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener una notificación específica por su ID para permitir a los usuarios recuperar los detalles de una notificación particular.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>17</td>
        <td>US32</td>
        <td>Crear una Nueva Notificación</td>
        <td>Como desarrollador backend, quiero implementar un endpoint POST para crear una nueva notificación para permitir a los usuarios enviar nuevas notificaciones que se almacenarán en el sistema.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>18</td>
        <td>US31</td>
        <td>Obtener Todas las Notificaciones</td>
        <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener todas las notificaciones para permitir a los usuarios recuperar la lista completa de notificaciones almacenadas en el sistema.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>19</td>
        <td>US25</td>
        <td>Configuración de la Base de Datos</td>
        <td>Como desarrollador, quiero diseñar y configurar la estructura de la base de datos para almacenar la información de los abogados, incluyendo campos como nombre, especialidad y ubicación.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>20</td>
        <td>US20</td>
        <td>API para gestión de perfiles</td>
        <td>Como desarrollador, quiero APIs robustas para crear, editar y eliminar perfiles de usuario.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>21</td>
        <td>US12</td>
        <td>Confirmación de recepción de documentos del caso</td>
        <td>Como médico quiero confirmar que he recibido los documentos enviados por un abogado.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>22</td>
        <td>US14</td>
        <td>Creación de la landing page</td>
        <td>Como usuario quiero acceder a una página de inicio que presenta información relevante sobre LEXMED y sus servicios.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>23</td>
        <td>US07</td>
        <td>Actualización de perfil del abogado</td>
        <td>Como abogado quiero actualizar mi perfil con información adicional o correcciones.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>24</td>
        <td>US06</td>
        <td>Generación de reporte de casos y abogados</td>
        <td>Como administrador quiero generar un reporte de todos los casos médicos y abogados registrados en la plataforma.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>25</td>
        <td>US03</td>
        <td>Subida de un caso médico</td>
        <td>Como médico quiero subir mi caso relacionado con una posible negligencia médica en la plataforma para que los abogados puedan verlo.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>26</td>
        <td>US37</td>
        <td>Envío de Mensajes entre Médicos y Abogados</td>
        <td>Como médico o abogado, quiero enviar mensajes a través de la plataforma para discutir detalles del caso.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>27</td>
        <td>US36</td>
        <td>Creación y Gestión de Asuntos Legales</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de asuntos legales para que los administradores puedan gestionar los asuntos legales.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>28</td>
        <td>US35</td>
        <td>Creación y Gestión de Recursos de Consultas</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de consultas para que los administradores puedan gestionar las consultas necesarias.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>29</td>
        <td>US34</td>
        <td>Creación y Gestión de Recursos de Casos Legales</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de casos legales para que los administradores puedan gestionar los casos legales.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>30</td>
        <td>US30</td>
        <td>Creación y Gestión de Recursos Informativos</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de recursos informativos en la base de datos para que los administradores puedan añadir, actualizar y eliminar recursos.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>31</td>
        <td>US28</td>
        <td>Creación y Gestión de Entidad de Usuario Médico</td>
        <td>Como desarrollador, quiero crear la entidad de usuario que represente a médicos en la plataforma.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>32</td>
        <td>US27</td>
        <td>Creación y Gestión de la Entidad de Abogados</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de la entidad de abogados en la base de datos para almacenar información detallada de los abogados.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>33</td>
        <td>US23</td>
        <td>Servicio de notificaciones</td>
        <td>Como desarrollador, quiero implementar un servicio de notificaciones, para mantener a los usuarios informados.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>34</td>
        <td>US22</td>
        <td>API para búsqueda por filtros</td>
        <td>Como desarrollador, quiero crear una API para búsquedas por filtros, para mejorar la accesibilidad de la información.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>35</td>
        <td>US21</td>
        <td>Logging de Actividades</td>
        <td>Como administrador, quiero un sistema de logging robusto para registrar la actividad en la plataforma, facilitando la auditoría y la detección temprana de problemas.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>36</td>
        <td>US13</td>
        <td>Registro de un nuevo caso por un médico</td>
        <td>Como médico quiero crear un nuevo caso en la plataforma LEXMED para su revisión.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>37</td>
        <td>US09</td>
        <td>Búsqueda de abogados por especialización</td>
        <td>Como médico quiero buscar abogados especializados en un área específica para su caso.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>38</td>
        <td>US08</td>
        <td>Filtrado de casos por área de especialización</td>
        <td>Como abogado quiero filtrar los casos médicos en la plataforma según su área de especialización.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>39</td>
        <td>US04</td>
        <td>Evaluación de casos por parte de los abogados</td>
        <td>Como abogado quiero evaluar casos médicos publicados en la plataforma para decidir si deseo tomar el caso.</td>
        <td>8</td>
    </tr>
</table>
