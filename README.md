# Práctica de despliegue web — Antonio Fernández González

## Webs
- `massively/` — CV, basado en el template Massively de HTML5 UP.
- `ethereal/` — Portfolio, basado en el template Ethereal de HTML5 UP.

## Apache
Copiar las carpetas `massively` y `ethereal` dentro del DocumentRoot de Apache (por ejemplo `/var/www/html/`) y acceder a:
- `http://localhost/massively/`
- `http://localhost/ethereal/`

## GitHub Pages
Una opción sencilla es subir ambas carpetas al mismo repositorio y publicar la rama principal. Las webs quedarán bajo la URL del repositorio, por ejemplo `https://USUARIO.github.io/REPOSITORIO/massively/` y `.../ethereal/`.

## PHP
GitHub Pages sirve contenido estático y no ejecuta PHP en el servidor. Para PHP se necesita un hosting con soporte de PHP o un servidor propio.
