# Integrante que realizo la mayor cantidad de commits,
Comando utilizado:
`git shortlog -sn --all`

Resultado:

Valenguerrieri: 12 commits

**Observacion:**
Git registra a "VTomii" y "Vtomii" como autores distintos debido a diferencias en la configuración del nombre de usuario.
al usar el comando:
12 Valenguerrieri
8 VTomii
7 Vtomii
5 Priscila Arrimada

# Cantidad total de merges realizados
Comando utilizado:

`git rev-list --merges --count HEAD`

Resultado:

9 merges

# Cantidad de conflictos producidos
Git no almacena un contador de conflictos resueltos.


Cantidad de ramas existentes en el repositorio,
Comando utilizado:
`git branch -a`

Resultado:

cantidad de ramas locales: 2

cantidad de ramas remotas: 5

Cantidad total de ramas: 7 ramas

**Ramas encontradas:**

alumno-astudillo
main
origin/alumno-arrimada
origin/alumno-astudillo
origin/alumno-guerrieri
origin/dev
origin/main

Commit con la mayor cantidad de archivos modificados,
Comando utilizado:

`git log --pretty=format:"COMMIT %H" --numstat --all`

Para inspeccionar el commit:

`git show caf64737be8005cd47a9d3e647109bc4be9bd583`

Resultado:

Hash: caf64737be8005cd47a9d3e647109bc4be9bd583
Archivos modificados: 6

**Archivos afectados:**

git-add.md
git-commit.md
git-init.md
git-log.md
git-pull.md
git-push.md

Mensaje del commit:

style(docs): unifico formato de los docs y corrijo redaccion


