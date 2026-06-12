# Git Rebase

Concepto:

git rebase es "mover la rama donde estas hasta el final del historial de la rama que elijas" , es decir si **estas parado en una rama X y vos queres basarte en la rama Y. este comando hace que la rama (X) vaya al final del historial de commits de la rama (Y) y luego agrega los commits de la rama X. Es importante saber que los commits de la rama X son replicadas y creadas nuevamente en la rama Y (NO SON LOS MISMOS COMMITS)**

##Sintaxis:

git rebase nombre-de-rama
