# Fitty: tu app de gimnasio

Archivos: index.html (toda la app), manifest.json (nombre e icono), sw.js (funciona sin internet) e iconos.

## Instalarla en el móvil
1. Crea una cuenta en github.com y un repositorio nuevo, público, llamado `fitty`.
2. Pulsa "Add file" > "Upload files" y sube TODOS estos archivos (sin carpeta).
3. Ve a Settings > Pages, en "Branch" elige `main` y pulsa Save.
4. En un par de minutos tendrás la app en https://TU-USUARIO.github.io/fitty/
5. Ábrela en Chrome, menú ⋮ > "Añadir a pantalla de inicio" > Instalar.

## Cambiar cosas
- Colores: al principio de index.html, en `:root`.
- Ejercicios iniciales: lista `DEFAULT_EX` en el script.
- Al subir cambios, sube el número de `VERSION` en sw.js para que el móvil descargue la versión nueva.

Tus datos se guardan solo en tu móvil. Exporta una copia desde Ajustes de vez en cuando.
