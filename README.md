# NetPulse — sitio promocional

Sitio estático en español. No requiere Node, compilación ni dependencias: `index.html` es la página de entrada.

## Publicar en GitHub

Subí el contenido de esta carpeta a la raíz del repositorio o configurá esta carpeta como directorio de publicación. Incluye `staticwebapp.config.json` para el enrutamiento de Azure Static Web Apps.

## Publicar en Azure Static Web Apps

Al crear el recurso, conectá el repositorio de GitHub y configurá:

- **Build preset:** Custom
- **App location:** `/` (o `/netpulse-site` si el sitio vive en una subcarpeta del repositorio)
- **API location:** dejar vacío
- **Output location:** dejar vacío

El despliegue sirve directamente los archivos estáticos. La página de privacidad está en `privacidad.html`.

## Contenido

- Capturas, icono e imagen promocional: `assets/`
- Video: embed de YouTube `dN-RMXVkwXA`
- Descarga: ZIP de NetPulse alojado en Cloudflare R2
- Contacto: email, WhatsApp y Discord
