# Realtime chat app - En curso

### [Ver demo](http://laravel-websocket.typingideas.com)

usuario: example@example.com \
password: 12345678

usuario: example2@example.com \
password: 12345678

usuario: example3@example.com \
password: 12345678

Por el momento, el proyecto se encuentra en etapa de desarrollo, no existe una fecha límite para tener una demo, ya que hay otros aspectos que investigar antes de lanzar la aplicación.
Es importante mencionar que el código no será público.

## Dependecias

- Laravel 10
- Laravel WebSocket
- Laravel Echo
- Pusher JS
- Inertia JS
- React v18
- React Icons
- React Query
- Tailwind CSS

Es importante mencionar que actualmente el canal de comunicación `WebSocket` funciona mediante un servicio proporcionado por `Pusher JS`, ya que el servidor de producción no cuenta con las funcionalidades para habilitar `Laravel WebSocket`, independiente de este problema, el proyecto soporta el cambio entre un servicio u otro ya sea si en un futuro la máquina que aloja la aplicación web tiene la capacidad para habilitar el canal de comunicación `socket`.

## Funcionalidades

- Chat privado entre usuarios
- Mensajes instantáneos
- Compartir imagenes en chat
- Estados de conexiones en contactos
- Ultimo mensaje recibido (destacado en contactos)
- Notificación por audio al recibir mensajes


## Próximas funcionalidades

- Emojis en chat
- Capturar y enviar audios
- Actualizar perfil
- Ver nuevas solicitudes
- Ver perfil de usuarios
- Publicación de reels
- Interacción en reels
- Publicación de historias mas imagenes, videos
- Comentarios en publicaciones
- Reacción en publicaciones
- Seguir usuarios

## Chat privado

![private-chat](private-chat.png)

## Chat privado responsivo

![chat-responsive](chat-responsive.png)

## Home

![home](home.png)

## Home responsivo

![home](home-responsive.png)
