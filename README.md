# Catálogo – The Crafty Teckel & Garder3D

Catálogo digital de impresión 3D (Garder3D), resina y crochet (The Crafty Teckel).

Es una web estática: no necesita servidor ni instalar nada. Cada modelo 3D y cada
grupo de fotos se descarga solo cuando alguien lo abre.

## Publicarlo con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `catalogo`), público.
2. Sube **todos** los archivos de esta carpeta a la raíz del repositorio, incluido
   el archivo oculto `.nojekyll`.
   - Desde la web de GitHub ("Add file" → "Upload files") se suben como máximo
     100 archivos cada vez: súbelos en dos tandas.
   - Con GitHub Desktop puedes arrastrar la carpeta entera de una vez.
3. En el repositorio, ve a **Settings → Pages**.
4. En "Build and deployment", elige **Deploy from a branch**, rama `main` y
   carpeta `/ (root)`. Pulsa **Save**.
5. En uno o dos minutos la web estará en
   `https://TU-USUARIO.github.io/catalogo/`.

Para usar un dominio propio (por ejemplo `catalogo.thecraftyteckel.com`),
escríbelo en **Settings → Pages → Custom domain** y sigue las instrucciones de DNS
que te da GitHub.

## Qué es cada archivo

- `index.html`: la web y la lista de productos.
- `assets.js`: logos y miniaturas.
- `catalogo-tienda.js`: productos de resina y crochet de la tienda.
- `fotos-resina.js`, `fotos-crochet.js`: fotos de cada sección.
- `ngotchi-datos.js`: pantallas de N-Gotchi, Pokéwalker y Digivice.
- `modelo-*.js`: un archivo por modelo 3D, cifrado.

## Actualizar

Sustituye los archivos que cambien y súbelos de nuevo: GitHub Pages publica los
cambios solo, en un par de minutos.
