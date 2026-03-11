# Laboratorio Git

## Descripción
Github laboratio de bootcampjs de lemoncode donde explico paso a paso la descripción de lo realizado

En este laboratorio he practicado los comandos básicos de Git y GitHub.

## Pasos realizados

### 1. Creación de  un repositorio local
Primero creé la carpeta del proyecto y ejecuté `git init`

### 2. Creación de un repositorio remoto en GitHub
Entré en GitHub y creé un repositorio llamado `bootcampjs-modulo0`

### 3. Creación de un repositorio remoto en GitHub
He conectado el repositorio local con GitHub con `git reote add` y he comprobado la conexión con `git remove -v`

### 4. Creación de un archivo llamado archivo.txt
He creado un fichero que se llama `archivo.txt` al que le he puesto `hola mundo`

### 5. Añadir el archivo al staging
Mediante el comando `git add archivo.txt`

### 6. Hacer un commit y un push
He realizado un commit y un push al repositorio de github, con los comandos `git commit -a` y `git push -u origin main`

### 7. Creación de una rama llamada development
Mediante el comando `git checkout`, que crea la rama y me cambia a ella de manera automatica 

### 8. Modificación del archivo en la rama development
Añadí una línea nueva al archivo, que es mi `Mi cambio`

### 9. Realización de commit en development y lo he subido a GitHub+
Hice un `git add de archivo.txt` un `git commit -a` y subi a a la rama `git push origin development`

### 10. Volver a main

Mediante el comando `git checkout main`

### 11. Hacer un merge de development en main

Esto lo que hizo fue integrar los cambios de development en main mediante `git merge development`

### 12. Subir cambios 

Subida de los cambios al repositorio mediante `git push origin main`