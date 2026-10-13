# Menú de My Time Salón y Café

Página pública del menú: **https://mytimesalonycafe1-source.github.io/menu-mytime/**

El QR impreso en las mesas apunta a esa dirección. **Nunca cambia**: para actualizar el menú solo se reemplaza el PDF.

## Cómo cambiar el menú

1. Exporta el menú nuevo desde Canva como PDF y nómbralo exactamente **`menu.pdf`** (minúsculas, sin acento).
2. En esta página de GitHub toca **Add file → Upload files**.
3. Arrastra el `menu.pdf` nuevo (reemplaza al anterior) y toca **Commit changes**.
4. En 1–2 minutos la página ya muestra el menú nuevo. En los celulares puede tardar hasta 10 minutos por la memoria del navegador.

La página salta la **portada** del PDF (página 1, «My Time · MENÚ») porque el encabezado ya la muestra. Si algún día el PDF no trae portada, en `index.html` cambia `SALTAR_PORTADA = true` a `false`.

## Archivos

- `index.html` — la página (muestra `menu.pdf` con PDF.js).
- `menu.pdf` — el menú. **Es lo único que hay que cambiar.**
- `logo.png`, `apple-touch-icon.png`, `favicon-32.png` — logo dorado.

Este repositorio es público a propósito: solo contiene el menú, nada del punto de venta.
