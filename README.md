# REPOSITORIO
REPOSITORIO DE DATOS

## ⚠️ No borrar: imágenes de las publicaciones de X

Este repositorio es de BoardingGate y tiene dos usos:

- En la rama `main` está la página de notas que lee Grok en el Tesla (`index.html`, publicada con GitHub Pages).
- En la rama `imagenes-x`, dentro de la carpeta `imagenes-x/`, están las imágenes y los vídeos de las publicaciones de X de @boardinggate: [ver la carpeta imagenes-x](https://github.com/BoardingGate/REPOSITORIO/tree/imagenes-x/imagenes-x).

Por qué no hay que borrar nada:

- Buffer, el programador de publicaciones, descarga cada imagen desde su enlace de raw.githubusercontent.com en el momento de publicar. Si antes se borra el repositorio, la rama `imagenes-x` o la carpeta `imagenes-x/`, las publicaciones programadas fallan. Cuando ya se han publicado, X guarda su propia copia y no dependen de GitHub.
- Los tuits nunca llevan un enlace a estas imágenes: la imagen va siempre adjunta. El enlace solo lo usa Buffer para recogerla.
- La limpieza ya es automática: el 1 de enero, abril, julio y octubre se borran las imágenes con más de 3 meses que no necesite ninguna publicación pendiente. No hace falta borrar nada a mano.
- No cierres la [pull request número 1](https://github.com/BoardingGate/REPOSITORIO/pull/1) ni borres la rama `imagenes-x`. La pull request está abierta a propósito y no se fusiona: la rama es la que aloja las imágenes.
