# Cloudnet IA — sitio web

Sitio estático de [cloudnet.cl](https://cloudnet.cl) (también responde en cloudnetia.cl).

- `index.html` — página principal
- `styles.css` — estilos y tokens de marca (colores, tipografía)
- `logo.svg`, `favicon.svg` — logo

## Despliegue en DigitalOcean App Platform

1. Create App → GitHub → `moralesmanuel/cloudnetia`, rama `main` (o `feature/website-01` para pruebas).
2. Tipo de componente: **Static Site**. Build command: vacío. Output directory: `/`.
3. Settings → Domains: `cloudnet.cl` (principal), `www.cloudnet.cl`, `cloudnetia.cl`, `www.cloudnetia.cl`.
