# Andanada del 5

Proyecto de medio taurino digital.

## Netlify Identity — Invitaciones y Reset

Para el correcto funcionamiento del flujo de autenticación (invitaciones, recuperación de contraseña, confirmaciones), es necesario configurar las plantillas de correo en Netlify Identity para que apunten a la siguiente URL:

`https://andanadadel5final.netlify.app/accept/`

Esta ruta (`/accept/`) contiene la lógica necesaria para detectar los tokens en el hash de la URL y abrir el widget de Netlify Identity automáticamente, evitando conflictos con otros scripts de la página principal.
