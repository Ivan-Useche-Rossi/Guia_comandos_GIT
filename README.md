# Guia_comandos_GIT

GIT STATUS

Este comando te muestra el estado en que se encuentra tu archivo que desas subir a GitHub (no es necesario usarlo toda slas veces, pero en caso de no estar seguro de en que estado se encuentra el repositorio, se recomiendo escribir el comando seguido de la tecla "enter" para verificar el estado del repositorio)

GIT INIT

Este comando inicializa la carpeta que contine los archivos a subir a GIT como un repositorio. (Esto solo se realiza cuando se queire subir un proyecto como repositorio a Git Hub)

GIT REMOTE ADD ORIGIN (en este espacio se debe pegar la URL que se copia previamente del repositorio creado en GitHub, el cual se encuentra en la pestaña SSH)

Este comando agrega un repositorio remoto que esel origen del prpyecto. Con esto, el GIT del pc sabe a que repositorio subirá el proyecto. 

GIT ADD . (tener cuidado, el "." esta separado previamente por un "espacio"

GIT COMMIT -M "FIRST COMMIT"

Con este paso, ya se crean los archivos para subir a la plataforma de GitHub
El "COMMIT" lo que hace es tomar todos los archivos junto con sus cambios hasta ese momento y los alista para ser cargados a GitHib. (NOTA: Si posterior a este paso, se realizan cambios, estos no se subiran)

GIT PUSH -U ORIGIN MAIN

