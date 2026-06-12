# Git reset

Concepto:

git reset sirve para volver una rama a un estado anterior. Tambien puedo borrar los commits al volver a un commit anterior o mantener los cambios del commit borrando ese mismo commit. Tiene varias formas de uso: Si usamos git reset --soft hash o hashes del/los commit este borrara el o los commits seleccionados **Pero conserva los archivos modificados listos para volver hacer un commit**.
Si usamos git reset --mixed Elimina hash o hashes del/los commit este borrara los commits de la rama y conserva los cambios en los archivos. **A diferencia de soft, mixed deja los archivos no preparados para el commit (ideal si queres ver que archivo agregar y cual no)**.
SI usamos git reset --hard en **este caso elimina los commits de la rama y también elimina los cambios de los archivos. (descarta completamente lo que hiciste)**

## Sintaxis:

git reset --soft (hash o hashes, o nombre de rama)
git reset --mixed (hash o hashes, o nombre de rama)
