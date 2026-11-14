# ¿Con amor? — Pokémon estilo Tinder

PWA para recorrer los **1025 Pokémon** por generación. Deslizá a la **derecha** si fue hecho con amor y a la **izquierda** si no.

## Funciones

- Menú con tus votos (con amor / sin amor), filtro por generación y opción de cambiar un voto.
- Compartir el resultado como imagen + texto.
- Instalable en iPhone y Android.
- Caché offline mediante Service Worker.
- Los votos se guardan localmente en el dispositivo.
- Sin build ni dependencias: HTML, CSS y JavaScript puros.

## Aplicación publicada

https://shonydev.github.io/pokemon/

## Despliegue

El workflow de GitHub Actions en `.github/workflows/pages.yml` publica automáticamente el contenido de la rama `main`.

Para habilitarlo la primera vez, entrá en **Settings → Pages** y elegí **GitHub Actions** como fuente de despliegue. Después de cada push a `main`, se ejecutará el despliegue.

## Instalar en iPhone

Abrí la URL en Safari → Compartir → **Agregar a pantalla de inicio**.

## Estructura

```
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
apple-touch-icon.png
.nojekyll
.github/workflows/pages.yml
```
