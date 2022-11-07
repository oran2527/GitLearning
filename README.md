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

