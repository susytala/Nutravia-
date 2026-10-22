# Bionatural — Catálogo online

Tienda de productos naturales (sahumerios, suplementos, barras y bebidas). Los pedidos se envían por WhatsApp.

## Archivos
- `index.html` — toda la tienda (productos, carrito, estilos)
- `logo.svg` — logo en vector
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — app instalable (PWA) y uso sin conexión
- `.github/workflows/pages.yml` — publica el sitio automáticamente
- `.nojekyll` — evita que GitHub procese el sitio

## Publicar en GitHub Pages
1. Creá un repositorio nuevo en github.com (por ejemplo `bionatural`).
2. Subí todos estos archivos (botón **Add file → Upload files**; incluí la carpeta `.github`).
3. En **Settings → Pages**, elegí **Source: GitHub Actions**.
4. En un minuto el sitio queda en `https://TU-USUARIO.github.io/bionatural/`.

## Editar productos
Abrí `index.html`, buscá `PRODUCTS` y modificá título, precio o venta mínima. Guardá (commit) y el sitio se actualiza solo.

## App instalable (PWA)
Con el sitio publicado en https (GitHub Pages lo es), en Chrome/Android aparece el botón **Instalar app** arriba. En iPhone: Safari → Compartir → **Agregar a pantalla de inicio**.
