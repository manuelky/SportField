SPORTFIELD - PROYECTO WEB

ESTRUCTURA
- index.html          Página principal
- canchas.html        Catálogo y filtros de escenarios deportivos
- reservas.html       Formulario y listado de reservas
- nosotros.html       Información del proyecto
- contacto.html       Formulario de contacto
- css/estilos.css     Estilos y diseño adaptable
- js/app.js           Lógica de la aplicación

CÓMO EJECUTAR
1. Descarga y descomprime la carpeta.
2. Abre la carpeta en Visual Studio Code.
3. Abre index.html en tu navegador. También puedes instalar la extensión Live Server
   en Visual Studio Code y seleccionar "Open with Live Server".
4. Navega desde el menú superior.

FUNCIONALIDADES INCLUIDAS
- Catálogo de escenarios para diferentes deportes.
- Filtros por deporte, nombre y precio.
- Formulario para reservar escenario, fecha y hora.
- Validación para evitar duplicar el mismo escenario, fecha y hora.
- Almacenamiento de reservas en LocalStorage.
- Consulta y cancelación de reservas.
- Formularios con validación básica.
- Diseño adaptable a móviles y computadores.

IMPORTANTE: ALCANCE DE ESTA VERSIÓN
Esta es una versión frontend funcional para demostración académica. Los datos se guardan
en el navegador del dispositivo mediante LocalStorage. No existe una base de datos central,
inicio de sesión, pagos en línea, envío real de correos ni sincronización entre dispositivos.
Para publicar el sistema como servicio real se debe desarrollar un backend, una base de datos,
autenticación, gestión de administradores y controles de disponibilidad del lado del servidor.

SCRUM - PROPUESTA DE TRABAJO
Product Goal:
Facilitar la búsqueda y reserva de escenarios deportivos desde una sola plataforma.

Roles sugeridos:
- Product Owner: representante del negocio / prioriza el Product Backlog.
- Scrum Master: facilita los eventos Scrum y elimina impedimentos.
- Developers: construyen, prueban y documentan el producto.

Sprint 1 - Descubrimiento y diseño:
Entregables: visión, historias de usuario, criterios de aceptación, mapa de navegación y prototipo visual.

Sprint 2 - Construcción del frontend:
Entregables: inicio, catálogo, nosotros, contacto, estilos responsive y navegación.

Sprint 3 - Reservas:
Entregables: selección de escenario, fecha y hora, validaciones, LocalStorage, consulta y cancelación.

Sprint 4 - Pruebas y entrega:
Entregables: pruebas funcionales, corrección de errores, revisión responsive y documentación.

Historias de usuario:
1. Como visitante, quiero explorar los deportes disponibles para elegir una actividad.
2. Como usuario, quiero filtrar escenarios para encontrar uno que se ajuste a mis necesidades.
3. Como usuario, quiero seleccionar fecha y hora para registrar una reserva.
4. Como usuario, quiero que el sistema impida duplicar un horario ya reservado.
5. Como usuario, quiero consultar y cancelar mis reservas.
6. Como visitante, quiero enviar una consulta mediante el formulario de contacto.

Criterios de aceptación principales:
- No se permite enviar el formulario de reserva con campos obligatorios vacíos.
- No se permite reservar fechas anteriores al día actual.
- No se permite duplicar el mismo escenario, fecha y hora en el mismo navegador.
- Las reservas se mantienen al recargar la página en el mismo navegador.
- El usuario puede cancelar una reserva y el horario vuelve a estar disponible.
