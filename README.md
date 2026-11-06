# Indes x Vale & Jorge

Landing privada de un solo archivo (`index.html`, sin build ni base de datos) para entregar
los videos de la boda. Los videos viven en Google Drive; la página los reproduce tipo stories
y permite bajarlos.

El código de entrada (`071126`) es un show de ingreso privado, no seguridad real.

## Cambiar algo

Todo está en el script: `API_KEY` (clave de Google restringida a este sitio y a Drive API) y el bloque `DEFAULTS` (código, textos, jornadas con sus videos; el título de cada video es el stage).
Foto de portada opcional: `assets/portada.jpg` (vertical 9:16, ~810×1440 px).

## Borrarlo del todo

1. GitHub: Settings → Danger zone → Delete this repository.
2. Drive: quitar el acceso público de la carpeta (Compartir → Acceso restringido).

No usa base de datos ni toca ningún otro proyecto.

## Pasárselo a otro dueño

GitHub: Settings → Danger zone → Transfer ownership, o que hagan fork del repo.
