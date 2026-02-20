#flexbox

como
traer una rama remota a local

# Agregar el repo original como un remoto llamado 'upstream'

git remote add upstream URL_DEL_REPO_ORIGINAL.git

# Verificar que ahora tienes 'origin' (tu fork) y 'upstream' (el original)

git remote -v

# descarga la informacion de las ramas sin modificar nada

git fetch upstream

# Cambiar a la rama donde quieres recibir los cambios

git checkout mi-rama-nueva

# Mergear los cambios de la rama principal del original (suele ser 'main' o 'master')

git merge upstream/main

