# Git commit

El comando git commit se utiliza para guardar de manera permanente los cambios que fueron preparados por git add. 
Cada commit representa un momento o etapa del proecto y permite llevar un registro ordenado de las modificaciones 
cada commit tiene informacion como quien es el autor de este, la fecha en que fue realizado y un mensaje que escribe quien hace el commit que ayuda o describe que se cambio entre comillas

## Sintaxis
git commit -m "mensaje"

Importancia de los mensajes

## Usos
Se recomienda que cada commit represente una unica idea o cambio concreto. De esta manera, el historial del proyecto resulta mas claro y sencillo, por ejemplo una vez que este archivo quede modificado, usare git add git-commit.md y proximamente git commit -m junto a un mensaje para ir actualizando los cambios en el repo
Por otro lado los commits realizados permanecen inicialmente en el repositorio local. Para compartirlos con otros integrantes del equipo, es necesario utilizar comandos como *git push*, que permiten sincronizar los cambios con el repositorio remoto.