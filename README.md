# GitLearning
Git practice
Cambio en primera

git diff <archivo> ver diferencias entre versiones
git add <archivo> -> agregar archivos al estado de archivos modificados
git commit -m "<mensajeCortoDelCambioDelArchivo>" ->  guardar los cambios en el historial de git
git log -> permite revisar el historial de commits de git
git log --stat -> permite ver la informacion cuantitativa de los commits
git log --patch -> permite ver los cambios especificos en los commits
git log --graph -> permite ver los cambios del commit de manera grafica como arboles
git log --pretty --format="%h %an %ad : %s" -> permite ver la informacion de los commits segun un formato
%h -> hash del commit
%an -> nombre del autor
%ad -> fecha del commit
%s -> mensaje del commit
git log --pretty --format="%h %an %ar : %s" -> permite ver info con la fecha de manera relativa
%ar -> se ve los cambios diciendo "hace 1 minuto" "hace dos dias" etc
git log --after=<fecha> -> permite ver commits despues de la condicion de fecha. Ejemplo --after=29/10/2021
git log --since=<fechaRelativa> -> permite ver commits segun fecha relativa. Ejemplo --since=1day
git restore <archivo> -> devuelve un archivo de stage a un archivo modificado
git commit --amend -> modifica el mensaje del ultimo commit realizado o sea el head sin perder el numero de commit
----- para probar amend luego del comando add --------
git commit --amend <archivo> -> agregar el mensaje de un commit a otro archivo que no se adjunto por olvido y que queden con el mismo mensaje y el mismo commit o sea el ultimo commit o sea el head
git branch -> muestra la rama actual en la que estamos trabajando
git branch -a -> muestra la rama actual y si es remota o local o ambas
git branch <nombreDeLaRamaNueva> -> crear una rama nueva
git branch --show-current -> muestra la rama actual que se esta usando o sea la que esta en verde
git switch <nombreRama> -> permite cambiar de una rama a otra
git checkout <nombreRama> -> cambia de una rama a otra
git checkout -b <nombreRamaNueva> -> permite crear una rama nueva y de una vez cambiar a ella
git checkout <archivo> -> devuelve la informacion al ultimo commit

#.gitignore
archivo .gitignore sirve para ignorar archivos o carpetas que no queremos que queden sus cambios. Agregar asi:
/nombrecarpeta
nombrearchivo



