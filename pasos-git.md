1. Git Init (Crear un repositorio) Me aparece cada archivo con una U (untracker es sin seguimiento)

2. git add 'titulo' (Aparece la A) = Area de preparacion
git status (te muestra todos los archivos de la carpeta)

Git add . (Seguimiento a todo el proyecto)

Para no dar seguimiento e ignorar : 'nombre de archivo'

M = Modified (No se encuentra en el staging area)
U = Uploaded File
A = Added File
Committed = Cambios para la versión

3. Crear una versión (Commit) del repositorio 
git commit -m "Nombre"

Ver version: Git log

4. Renombra la rama master a main
git branch -M main


5. Conectar nuestro repositorio local con un origen remoto
git remote add origin https://github.com/IanGorski/Repo1.git

6. Subir nuestros cambios al repositorio remoto
git push -u origin main

PASOS PARA ACTUALIZAR EL PROYECTO

Paso 1:
Añadimos los cambios
Git add . 

Paso 2:
Hacer una version
Git commit -m "describi los cambios brevemente"

Paso 3:
Subir la version
git push
