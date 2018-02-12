# gitClass
Curso Git para mejorar branch mejorando
mkdir--comando de linux para crear una carpeta.

mkdir--comando de linux para crear una carpeta.

git clone "url a clonar"-- esto me clona cualquier proyecto en git de forma rapida.

para conectarme a un reporsitorio en github debo configurar mi pc mediante la consola de git con mis datos.
datos importantes
Esto configura mi nombre y correo en las variables globales de git.
git config --global user.name "Jeffry"
git config --global user.email "micorreoeletronico.com"


Para conectar mi pc tengo que generar una llave ssh la cual me permitira conectar mi pc con git.

El comando es el siguiente.

ssh-keygen-- esto me genera el key mediante la consola de git.

 cat  ~/.ssh/id_rsa.pub --con es te comando leo el key generado y se lo paso a github para que reconozca mi pc.
 
 git init -- comando que sirve par inicializar un proyecto en una carpeta.
 
 comandos linux
 touch nombreArchivo-- esto es para crear un nuevo archivo mediante la consola.
 git add nombrearchivocreado para agregarlo al proyecto git en el que estoy trabajando.
 
 git status -- este comando me permite ver el estado de mi proyecto, mediante consola.

 El comando
 
 git remote add origin "url del proyecto que queremos sincronizar"-- esto nos permite machear nuestra pc con el repo en github.
 
 git commit -m " el comentario que quieras del commit"
 
 git pull origin master -- este comando trae todo lo que tengo en mi proyecto git a mi repo local en la pc.
 
 git push origin master -- para agregar los proyecto .