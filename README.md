# RAGsoluciones

Landing page de RAGsoluciones (Rodrigo Antonio Gutiérrez). Es un solo archivo `index.html` sin dependencias: no necesita instalar nada ni compilar.

## Publicar gratis en GitHub + Vercel

1. En GitHub, cree un repositorio nuevo, por ejemplo `ragsoluciones` (público o privado).
2. Pulse **Add file → Upload files**, arrastre `index.html` (y este README) y pulse **Commit changes**.
3. Entre a vercel.com con su cuenta de GitHub → **Add New… → Project** → elija el repositorio → **Deploy**.
   - Framework Preset: **Other**. No hace falta configurar nada más.
4. En un minuto tendrá su sitio en `https://ragsoluciones.vercel.app` (o el nombre que Vercel le asigne; se cambia en Settings → Domains).

Cada vez que edite `index.html` en GitHub, Vercel publica la nueva versión sola.

## Cambios comunes

- **Teléfono de WhatsApp:** busque `50671086706` (aparece 4 veces).
- **Portafolio:** cada proyecto es un bloque `<article class="proyecto">`. Copie uno para agregar otro.
- **Colores:** al inicio del `<style>`, en `:root` (crema, verde, terracota).
- **Foto:** va incrustada en el archivo. Para cambiarla, reemplace el `src` de la imagen con alt "Rodrigo Gutiérrez…" por la ruta de una imagen nueva (p. ej. `foto.jpg` subida al mismo repositorio).
