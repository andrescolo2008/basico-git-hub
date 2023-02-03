# Comandos útiles de Git

1. git init   = va iniciar el repositorio
2. git add .  =   sube los archivos  al "escenario" llamado stage, y  deja listos los archivos para "tomarles la foto", es decir,  commit 
3. git reset .  = revierte todo lo que hace git add .
4. git commit -m" nombre del commit "   =  les"va a tomar una fotografía" a los archivos, crea un respaldo en git, la cual se va a llamar commit.
5. git checkout -- .   = reconstruirá el código del documento de acuerdo al último commit genreado, es decir, la última copia de seguridad que se encunetre en git
6. git log   = lista los commits registrados
7. git commit --amend  =  sirve para arrglar el nombre del último commit

sEgundO CoMMit-- lo voy a arreglar

git commit --amend 
pasos:

 corregir el nombre = Segundo Commit

 presionar tecla esc 
 presionar la sigueinte tecla :
 presionar la sigueinte tecla w
 presionar la sigueinte tecla q
 presionar la sigueinte tecla !




8. git checkout -b rama-heroes   : sirve para trabajar en una rama diferente a la principal, una rama 2ria
9. git checkout master
10. git branch -d rama-heroes   : borra la rama heroes 
11. git push      : sirve para desplegar el archivo en git hub con sus cambios ya realziados
12. git commit -am   : combina al mimso tiempo git add . + git commit -m" mensaje del commit  "

