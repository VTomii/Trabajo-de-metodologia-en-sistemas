# Git Merge

Concepto:

git merge se usa cuando queres unir los commits de una rama X a la rama donde estas parado. Supongamos que estamos parados en main y queremos incorporar o integrar los commits de la rama X. al ejecutar el comando merge + nombre de la rama (en este caso rama X), git toma los commits que existen en X y que todavía no están en main e incorpora sus cambios a main. **importane: los commits se unen y quedan en el historial de la rama. no es como git rebase que unifica las ramas, sino que merge crea una union entre la rama X y rama Y**

##Sintaxis:
git merge nombre-de-rama

ME FALTA MERGE REVERT Y RESET.
