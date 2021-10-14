#Git

Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente.

Git es una herramienta util, ya que su primordial funcion es permitirnos tener una gestion sobre la versiones de nuestro codigo de manera sencilla.

####Comandos de Git

Estos son los comandos que he encontrado para trabajar con git.

$ git init

Esto generara un fichero listo para almacenar las versiones de nuestro codigo, aunque aun esta vacio, aun debemos guardar las versiones de nuestro codigo.

$ git commit

Commit es la confirmacion de un estado, los cuales seran los puntos a los que podremos volver.

$ git add

Este comando añadira todos los cambios realizados al “Staging area”.

$ git log

Te permite ver todos los cambios al repositorio

$ git branch

Se utiliza para crear una nueva rama o cambiar la rama con la que se desea trabajar.

$ git status

Muestra el estado actual del repositorio, incluyendo la rama en la que se está trabajando.

$ git merge

Combina los cambios de dos ramas

$ git remote

Conecta un repositorio local a un repositorio remoto.

$ git clone

Crea una copia local de un repositorio remoto.

$ git pull

Carga los cambios del repositorio remoto al repositorio local.

$ git push

Envía los cambios del repositorio local al repositorio remoto.

$ git rm

Elimina archivos o directorios. Hay dos tipos de git rm, force y cached. un rm force borra el archivo entero, mientras que el rm cached solo lo borra del index del repositorio.

Git utiliza una "Staging area" lo cual permite que los cambios realizados puedan ser comprobados antes de hace run commit. la estructura es la siguiente:

Working directory	Staging area	Local repository	Remote repository
Directorio en el que se está trabajando	Area intermedia	Repositorio local	Repositorio remoto
Comandos necesarios para añadir este archivo a mi repositorio:

git add Git.md 
git status
git commit -m "Nombre-del-commit"
git push origin master
Enlace al repositorio público **"https://github.com/Oskere/Test"**