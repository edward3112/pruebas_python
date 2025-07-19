1. paso. git init es por iniciar proyecto por cada proyecto
2. git add <Nombre del archivo> añadir este archivo al stagin
3. 
git add . - añade todos los cambios a partir de este directorio
git add -A
git add --all

git diff - ves la diferencia desde el ultimo commit
4. 
git commit -m "descripcion"
git log -- para ver el historial
git log --oneline mas resumido

git status para ver el status

git show <numero de operacion> muestra el historial de dicha operaicon

git checkout - b "descripcion" --para crear y moverte a la rama descrpcion

git branch -D "RAMA" --eliminar la rama  

un flujo de trabajo habitual
git checkout -b feat/index -- algo nuevo en index de un error que aparecio