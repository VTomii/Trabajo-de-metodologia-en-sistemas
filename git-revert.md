# Git revert

Concepto:

Git revert sirve para deshacer los cambios de un commit pero a diferencia de git reset. git revert no borra ese commit del historial. es decir en lugar de mover la rama hacia atrás (como hace git reset), Git crea un nuevo commit que revierte o deshace los cambios hechos en el commit que elegiste revertir.

## Sintaxis:

git revert hash-del-commit
