# git
Practicas con git
![Image of Yaktocat](https://github.com/GyserMaster/images/blob/master/arquitectura%20git.png)

COMANDOS BASICOS 
* git init Oye Git, voy a usar estos documentos contigo ¿vale?
* git add <file> Pasa los docs a staging area 
* git add . Pasa todos los archivos
* git commit Pasa los docs de staging area a repository (Después de esto se te va a abrir el editor de código VIN en donde tendrás que escribir un comentario, si te quieres evitar abrir VIN entonces utiliza los siguientes comandos:)
* git commit -m "comentario" Lo mismo que el commit regular, pero ahora no necesitas entrar a VIN
* git status Ver en que status (wd, sa, r) están los docs
* git push Subir los docs a un server (Github)
* git pull  Traer los docs de un server, traer los cambios de tus compañeros
* git clone Hacerte una copia de lo que está en el server a tu PC
* git checkout -- <file> Para revertir los cambios de los archivos
* git diff <file> Para ver las diferencias hechas en los archivos
* git branch Ver las ramas que hay ("master" es la rama default)
* git branch "nombre" Crear una nueva rama
* git checkout "nombre" Ir a una rama en especifico 

*  git config -- global user.email "email" Para configurar email del usuario
*  git config -- global user.name "nombre" Para configurar nombre del usuario

* Git checkout –b nombre de la rama: nos permite crear una nueva rama y cambiar de rama  a la misma vez con un solo comando
* Git branch –m nombreActualDeLaRama NombreNuevaDeLaRama: para cambiar el nombre de la rama
* Git branch –d NombreDeLaRamaQueQuieroEliminar: eliminar rama

.gitignore Es un archivo reservado de git que tenemos que crear si queremos decirle a git los archivos que no vamos a utilizar y así decida ignorarlos.
Escribe dentro de el archivo .gitignore los nombres de los archivos que desees ignorar.
Nota: Las carpetas se escriben solas y los archivos con su terminación.
