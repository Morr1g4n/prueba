# prueba HML CSS GIT
## Nombre: Ricardo Beltrán
git clone {url}
clona un repositorio de forma local

git --config user.name "Usuario"
git --config user.email "mail"
sirven para establecer la cuenta

git add {archivo/cambio}
sirve para añadir cualquier cambio o archivo al staging para posterior confirmación y push en el repositorio
se puede escribir un archivo especifico o escribir un solo punto "." para añadir todos los cambios realizados a nivel local en staging

git commit
guarda una snapshot de los cambios a nivel repositorio local en el staging
se le puede añadir un mensaje con el parametro -m (git commit -m "{mensaje}")

git log
permite ver los cambios a nivel local y en el repositorio remoto

git push {remoto} {rama}
sirve para aplicar los cambios en stagging al repositorio remoto (requiere autenticación)
ejemplo: aplicar cambios del commit a la rama main en el repositorio de origen

git push origin main

Terminologia:
Staging: Es una especie de sala de espera para los cambios realizados a nivel local, donde estos cambios esperan a confirmarse mediante un commit

Se debe usar git add para añadir archivos o cambios
