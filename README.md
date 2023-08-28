# InstantPolyglot

InstantPolyglot es una plataforma de traducción en tiempo real que permite a los usuarios comunicarse en diferentes idiomas de manera instantánea. La plataforma combina la potencia de Node.js y Java para ofrecer una experiencia de chat en tiempo real con traducción automática.

## Características Principales

- Registro de Usuarios: Los usuarios pueden registrarse e iniciar sesión en la plataforma.
- Selección de Idioma: Los usuarios pueden elegir su idioma preferido para la comunicación.
- Chat en Tiempo Real: Comunicación en tiempo real a través de WebSockets con mensajes traducidos automáticamente.
- Traducción Automática: Utilización de Java para integrar bibliotecas de traducción como Google Cloud Translate.
- Interfaz de Usuario Atractiva: Diseño web cuidadosamente diseñado para una experiencia de usuario fluida.
- Historial de Chat: Los usuarios pueden ver su historial de conversaciones, incluyendo traducciones.
- Notificaciones en Tiempo Real: Notificaciones instantáneas para nuevos mensajes utilizando Node.js.
- Gestión de Usuarios y Sesiones: Autenticación y gestión de sesiones con Node.js.
- Opciones de Configuración: Personalización de preferencias, incluyendo cambio de idioma de destino.
- Seguridad: Implementación de medidas de seguridad para proteger los datos y las comunicaciones.

## Tecnologías Utilizadas

- **Node.js**: Para la parte del servidor y la comunicación en tiempo real utilizando WebSockets.
- **Java**: Para la funcionalidad de traducción automática utilizando bibliotecas como Google Cloud Translate.
- **Express**: Marco de aplicación web para Node.js utilizado para manejar rutas y lógica de negocio.
- **Socket.IO**: Biblioteca de tiempo real para la comunicación bidireccional en tiempo real entre el cliente y el servidor.
- **Passport.js**: Middleware de autenticación utilizado para gestionar el registro y el inicio de sesión de los usuarios.
- **MongoDB**: Base de datos NoSQL utilizada para almacenar información de usuarios y registros de chat.
- **Bootstrap**: Framework de diseño front-end utilizado para crear una interfaz de usuario atractiva y receptiva.
- **HTML / CSS / JavaScript**: Lenguajes esenciales para desarrollar la interfaz de usuario y la lógica del cliente.
- **Google Cloud Translate / Microsoft Translator**: Bibliotecas utilizadas para la traducción automática de mensajes.
- **Heroku / AWS / DigitalOcean**: Opciones para desplegar la plataforma en un entorno en la nube.
- **Docker**: Para la creación de contenedores. En este caso para MongoDB.

## Instalación y Uso

1. Clona el repositorio.
2. Instala las dependencias utilizando `npm install`.
3. Configura tus credenciales para las bibliotecas de traducción (si es necesario).
4. Ejecuta la aplicación con `node src/index.js`.
5. Visita `http://localhost:3000` en tu navegador.

## Contribución

Contribuciones son bienvenidas. Si deseas contribuir a este proyecto, sigue las pautas de contribución en `CONTRIBUTING.md`.

