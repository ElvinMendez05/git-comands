# comandos utiles para git 

1. git init // inicializa el repositorio
2. git add . // toma todos los archivos desde el ultimo comit y lo lleva a un lugar llamado stage
3. git reset . // revierte todo lo que hace el git add .
4. git commit -m "" // captura los cambios del proyecto al momento 
5. git checkout -- . // restaura los archivos desde el ultimo commit osea lo revierte 
6. git log // para ver el listado de commit 
7. git commit --amend // modifica mi ultimo commit, para modificar se preciona tecla (i) insert, para salir se preciona esc, luego :wq!
8. git checkout -b rama-program //para crear una nueva rama, -b es branch 
9. git checkout master  // cambia de rama (git commit -m "git checkout") se hace despues
10. git merge rama-lenguajes // fucionar los cambios 
11. git branch -d //para borrar una rama 
12. git push //despliega el archivo en githup
13. git commit -am // evita hacer el git add . y git commit -m