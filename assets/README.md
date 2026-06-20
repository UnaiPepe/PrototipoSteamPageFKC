# Recursos visuales

Los recursos de la web publicada se guardan como archivos normales en esta carpeta. `content.js` solo referencia sus rutas relativas, por lo que sigue siendo pequeño y apto para GitHub.

- `screenshots/`: imágenes del carrusel.
- `gifs/`: GIFs insertados en «Acerca de este juego».
- `art/`: arte disponible para asignar a una cápsula u otra ubicación.

Cada archivo debe pesar menos de 100 MB, que es el límite de GitHub. Al añadir un recurso nuevo, cópialo aquí, registra su ruta en el manifiesto `media` de `content.js` y súbelo junto con ese archivo.

El editor usa únicamente este manifiesto: no publica archivos que se carguen solo en el navegador. Los GIFs deben tener un identificador estable en `media.gifs`; el texto los inserta como `[[gif:identificador]]`. Si un marcador no tiene archivo asociado, el editor bloquea la exportación.
