# Ejercicio01
Ejercicio 01 de GIT

- Inicializar un repositorio

Creamos una carpeta 'Ejercicio01'
En el terminal buscamos y abrimos la carpeta

$cd d´/'Miguel Guarrochena/Clase03/Ejercicio01

- Inicializamos el repositorio

$ git init

- Enlazar con un repositorio remoto

En GitHub creamos un repositorio remoto nuevo y lo enlazamos con el de GIT
por medio de comandos
$ git clone https://github.com/Maicolgua/Ejercicio01.git


- Obtener un repositorio remoto

Conectamos git con github

$ git remote

- Permisos de acceso a un repositorio remoto

$ git config --global user.name 'Maicolgua'
$ git config --globar user.mail mikeguarrochena@hotmail.com

- Listando los ultimos cambios del repositorio

$ git config user.name
$ git config user.mail

- Obtener los últimos cambios del repositorio remoto

$ git status

- Examinar el historial de cambios de un archivo

$git log

- Crear una nueva rama en el repositorio remoto

$ git checkout -b develop

- Diferencias entre 2 ramas de nuestro proyecto

- git diff master ..develop
- Manejar etiquetas (tags)

Primero creamos la etiqueta (tag)

$ git tag 1.0

Luego pusheamos para actualizar el repositorio remoto

$ git push origin tag 1.0

- Crear una rama local en el repositorio remoto

$ git push origin develop

- ¿Quién hizo que? Uso de git: git blame

git blame README.md