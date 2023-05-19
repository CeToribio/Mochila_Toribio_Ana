# Comandos más utilizados

* Crear o Inicializar un repositorio local
 ```
  git init
 ```
* Configuración del usuario por nombre y correo
 ```
  git config user.name
  git config user.email
 ```
* Configuración del usuario por nombre y correo de forma global para todos los repositorios
 ```
  git config --global user.name
  git config --global user.email
 ```
* Agregar un archivo en especifico al stage area y preparación antes del commit
 ```
  git add nombre_del_archivo
 ```
* Agregar todo los cambios al stage area y preparación antes del commit
 ```
  git add .
 ```
* Observar el status del archivo o cambios
 ```
  git status
 ```
* Guardar una versión
 ```
  git commit -m "mensaje descriptivo y resumido de la versión"
 ```
* Ver el historial de las versiones de nuestro proyecto
 ```
  git log
 ```
* Crear una rama
 ```
  git branch "nombre-de-la-rama"
 ```
* Movernos entre ramas
 ```
  git checkout "nombre-de-la-rama"
 ```
* Enviar las versiones al repositorio remoto
 ```
  git push origin main o nombre-de-la-rama
 ```
* Clonar un repositorio remoto al local
 ```
  git clona http
 ```
* Traer los cambios del repositorio remoto al local
 ```
  git pull origin main
 ```