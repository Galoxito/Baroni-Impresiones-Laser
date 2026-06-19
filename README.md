# Baroni · Impresiones Láser — Sitio web

Sitio estático (HTML + CSS puro). Mobile-first, responsive, listo para GitHub Pages.
Todo el contenido ya está cargado: logo, misión, visión, propósito, sección "La marca",
WhatsApp (2964 619620) e Instagram (@baronis.impresiones.laser).

## Archivos
- `index.html` — la página
- `styles.css` — estilos (paleta + tipografías del manual)
- `logo.png` — logo negro (para fondos claros / favicon)
- `logo-cream.png` — logo crema (el que se usa en header y footer oscuros)

## Publicar en GitHub Pages

GitHub no permite espacios en el nombre del repo. Usá guiones: `baroni-impresiones-laser`.

1. Creá un repo vacío en github.com con ese nombre.
2. En la terminal, parado en esta carpeta:

```bash
git init
git add .
git commit -m "Sitio Baroni Impresiones Láser"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/baroni-impresiones-laser.git
git push -u origin main
```

3. En GitHub: **Settings → Pages → Source: Deploy from a branch → main / root → Save**.

En ~1 minuto queda online en:
`https://TU_USUARIO.github.io/baroni-impresiones-laser/`

## Notas
- Para cambiar el número o el Instagram, buscá `wa.me` e `instagram.com` en `index.html` (aparecen 2 veces cada uno: en el botón de la sección Contacto y en el botón flotante).
- Las fuentes (Cormorant Garamond + Hanken Grotesk) se cargan desde Google Fonts, no hace falta instalar nada.
