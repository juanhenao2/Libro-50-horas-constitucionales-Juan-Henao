# Libro virtual — Estudios Constitucionales

Este repositorio está preparado para publicarse con GitHub Pages. Conserva el contenido del PDF original y lo muestra en un lector tipo libro con portada, índice y navegación.

## Archivos
- `index.html`: página del libro.
- `assets/libro.pdf`: documento original que se renderiza página a página.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y la carpeta `assets` completa (incluido `libro.pdf`).
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique la página. La dirección será similar a `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

Las librerías PDF.js y PageFlip se cargan desde CDN, así que el lector necesita conexión a internet. El PDF está alojado en tu propio repositorio.
