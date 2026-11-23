# SPORTFIELD

**Plataforma web para la búsqueda y reserva de escenarios deportivos**

## 1. Descripción del proyecto

Sportfield es una plataforma web creada para facilitar la búsqueda de escenarios deportivos y el alquiler de canchas. La idea principal es reunir en un solo sitio diferentes opciones para que las personas puedan encontrar lugares donde practicar su deporte favorito.

En la plataforma se podrá consultar información como el nombre del escenario, el deporte que ofrece, su ubicación, los precios y los datos de contacto. También contará con una sección destinada a las reservas.

## 2. Problemática

Cuando una persona desea alquilar una cancha para jugar fútbol, baloncesto, voleibol u otro deporte, muchas veces no sabe dónde encontrar diferentes opciones disponibles.

Generalmente debe buscar en redes sociales, preguntar a conocidos o comunicarse con varios establecimientos para conocer los precios, la ubicación y los servicios que ofrecen.

Esto hace que encontrar una cancha adecuada pueda convertirse en un proceso demorado.

Sportfield busca solucionar esta situación reuniendo la información de diferentes escenarios deportivos en una sola plataforma, para que los usuarios puedan consultar y comparar las opciones de una manera más sencilla.

## 3. Objetivo general

Desarrollar una plataforma web que facilite la búsqueda y selección de escenarios deportivos, permitiendo a los usuarios consultar información sobre las canchas, sus precios, ubicación y opciones de reserva.

## 4. Objetivos específicos

- Reunir información de diferentes escenarios deportivos en una sola plataforma.
- Facilitar la búsqueda de canchas según el deporte que desea practicar el usuario.
- Mostrar información importante como precios, ubicación y contacto.
- Incorporar filtros que permitan encontrar escenarios de manera más rápida.
- Facilitar el acceso a la sección de reservas.
- Crear una página sencilla y fácil de utilizar.

## 5. Alcance del proyecto

Sportfield está enfocado en ofrecer una plataforma web donde las personas puedan consultar diferentes escenarios deportivos y conocer sus características antes de elegir dónde jugar.

El proyecto contempla las siguientes secciones y funcionalidades:

- Página principal con información general de la plataforma.
- Catálogo de escenarios deportivos.
- Búsqueda de canchas por nombre.
- Filtros según el deporte.
- Organización de resultados por precio.
- Consulta de información de los escenarios.
- Sección de reservas.
- Página de contacto.
- Sección sobre el proyecto.

## 6. Requisitos funcionales

| Código | Requisito | Descripción |
|---|---|---|
| RF01 | Catálogo de escenarios | Mostrar los escenarios deportivos disponibles. |
| RF02 | Filtro por deporte | Permitir filtrar las canchas según el deporte. |
| RF03 | Búsqueda | Buscar escenarios por su nombre. |
| RF04 | Ordenar por precio | Organizar los escenarios según su precio. |
| RF05 | Información de escenarios | Mostrar los datos principales de cada cancha. |
| RF06 | Reservas | Contar con una sección para gestionar las reservas. |
| RF07 | Contacto | Permitir consultar la información de contacto. |
| RF08 | Información del proyecto | Mostrar información sobre Sportfield. |

## 7. Requisitos no funcionales

- **Facilidad de uso:** La página debe ser sencilla y permitir que cualquier usuario pueda navegar por ella.
- **Rendimiento:** Las páginas deben cargar correctamente y responder a las acciones del usuario.
- **Compatibilidad:** El sistema debe funcionar en los principales navegadores web.
- **Diseño adaptable:** La página debe visualizarse correctamente en computadores y dispositivos móviles.
- **Mantenimiento:** El código debe estar organizado para facilitar futuras modificaciones.
- **Seguridad:** La información de los usuarios debe manejarse de manera adecuada cuando se implementen funciones que la almacenen.

## 8. Tecnologías utilizadas

| Tecnología | Uso en el proyecto |
|---|---|
| HTML | Creación de la estructura de las páginas. |
| CSS | Diseño y apariencia de la plataforma. |
| JavaScript | Implementación de funciones e interactividad. |
| Visual Studio Code | Programa utilizado para escribir y editar el código. |
| Git | Control de cambios del proyecto. |
| GitHub | Almacenamiento y organización del código. |

## 9. Arquitectura del sistema

Sportfield está desarrollado como una aplicación web que utiliza principalmente tecnologías del lado del cliente.

- **Frontend:** Está compuesto por HTML, CSS y JavaScript. Es la parte que los usuarios pueden visualizar y utilizar.
- **Estilos:** Los archivos CSS se encargan de definir los colores, tamaños, distribución y apariencia de la página.
- **Lógica:** Los archivos JavaScript contienen las funciones que permiten realizar búsquedas, aplicar filtros y manejar la interacción con la página.

## 10. Estructura del proyecto

```text
SportField/
│
├── css/
├── js/
├── index.html
├── canchas.html
├── reservas.html
├── contacto.html
├── nosotros.html
└── README.md
```

## 11. Instalación y ejecución

Para ejecutar el proyecto desde un computador se deben seguir estos pasos:

1. Descargar el proyecto desde GitHub o clonar el repositorio.
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Instalar la extensión Live Server.
4. Abrir el archivo `index.html`.
5. Hacer clic derecho y seleccionar la opción Open with Live Server.
6. La página se abrirá en el navegador.

Para clonar el repositorio se puede utilizar el siguiente comando:

```bash
git clone https://github.com/manuelky/SportField.git
```

## 12. Estado del proyecto

El proyecto se encuentra en desarrollo. Actualmente se trabaja en la construcción de las diferentes páginas, el diseño de la plataforma y la implementación de sus funcionalidades.

## 13. Mejoras futuras

- Implementar registro e inicio de sesión de usuarios.
- Conectar la plataforma con una base de datos.
- Permitir realizar reservas de manera funcional.
- Consultar la disponibilidad de horarios.
- Incorporar pagos electrónicos.
- Agregar comentarios y calificaciones de los escenarios.
- Incluir escenarios deportivos de diferentes ciudades.

---

**SPORTFIELD**

Encuentra tu cancha y disfruta del deporte.
