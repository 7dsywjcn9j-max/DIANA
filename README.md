# dianapiedrola.com

Presentación personal de Diana Piedrola — página de una sola vista.

## Estructura

```
index.html   → toda la página (HTML + CSS + JS en un solo archivo)
img/         → fotografías
fonts/       → tipografías Cormorant Garamond y Jost (woff2)
```

## Verla en local

Abrir `index.html` en el navegador. No requiere build ni dependencias.

## Publicar

Sitio estático. Funciona tal cual en Netlify, Vercel o GitHub Pages
(en GitHub Pages: Settings → Pages → Deploy from a branch → main / root).

## Editar

- **Textos:** directamente en `index.html`.
- **Fotos:** reemplazar el archivo dentro de `img/` conservando el mismo nombre.
- **Encuadre de una foto:** ajustar `object-position` en el `style` de esa etiqueta `<img>`.
- **Colores:** variables CSS al inicio del `<style>` (`--espresso`, `--cream`, `--sand`, `--tan`).
