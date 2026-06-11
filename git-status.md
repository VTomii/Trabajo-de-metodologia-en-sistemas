# Git status
Concepto: Usamos el git status para conocer el estado de nuestros cambios o modificaciones dentro del repo. Es importante para saber a su vez que cambios estan preparados para hacer el commit y cuales faltan agregar. Por ello siempre se suele utiliza antes del *git add* y el *git commit*.

Durante el desarrollo de este trabajo fue util para verificar qué cambios habiamos realizado antes de ejecutar comandos como git add o git commit, evitando incluir archivos o modificaciones por error.

Sintaxis: 
git status

durante la ejecucion pueden aparecer 
1. Archivos modificados (modified).
2. Archivos nuevos que aún no fueron agregados (untracked).
3. Cambios listos para ser confirmados mediante un commit (Changes to be committed).

Aprovechando la bibliografia recomendada: (https://www.freecodecamp.org/espanol/news/gitting-things-done-una-guia-visual-y-practica-para-git-libro-completo/#cap-6)
## Git diff
*cita : "git diff es un comando que toma dos entradas, y calcula la diferencia entre ellos. Las entradas pueden ser confirmaciones, pero también archivos, e inclusive archivos que nunca han sido introducidos al repositorio."*


En caso de necesitar mas detalle sobre los cambios detectados, el comando git diff permite visualizar especificamente que modificaciones fueron realizadas dentro de los archivos. Mientras que git status indica que archivos cambiaron y en que estado se encuentran, git diff muestra el contenido exacto de esos cambios.
 Usamos git status para saber que habia cambiado y git diff para entender exactamente que habia cambiado.

