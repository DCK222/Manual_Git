# Manual_Git
configurar correo /user
git config --local user.mail correo@gmail.com
git config --local user.name "NombreUser"

crear rama : $ git checkout -b tita

cambio de rama : git checkout main

consultar ramas : git Branch

subir en el main los cambios de otras ramas :  git merge tita

borrar rmaas : git branch -d tita

borrar ramas del GitHub : git push origin --delete tita

mostrar etiquetas :  git tag

crear etiquetas : git tag 1.0.0

crear fichero :touch versiones.log

deshacer cambios $ git log --oneline
(el numero del commit que queras revertir)
$ git log --oneline > versiones_resumido.log
$ git reset --hard e8d459b

para ver los cambios :$ git status

para no hacer cambios sin commit : $ git commit --amend --no-edit

usuario , hora de los commits del proyecto : git log --pretty=format:"%h - %an, %ar : %s"


------------------------------------------------------------------------------------------

Para colaborar en proyectos con otros usuarios
