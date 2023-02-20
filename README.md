# Guia_comandos_GIT

GIT STATUS

Este comando te muestra el estado en que se encuentra tu archivo que desas subir a GitHub (no es necesario usarlo todas las veces, pero en caso de no estar seguro de en que estado se encuentra el repositorio, se recomiendo escribir el comando seguido de la tecla "enter" para verificar el estado del repositorio)

GIT FETCH ORIGIN MAIN

Este comando agrega cambios desde un repositorio remoto a tu repositorio local. Te permitirá revisar los cmabios antes de subirlos a tu rama local.

GIT PULL ORIGIN MAIN

Obtiene los cambios previamente obtenidos del comando anterior y los incorpora en la copia local para que este este actualizado.


GIT ADD . (tener cuidado, el "." esta separado previamente por un "espacio" (NO DEBE SALIR "FATAL" o "ERROR")

Toma los archivos y los agrega.

GIT COMMIT -M "FIRST COMMIT"

Con este paso, ya se crean los archivos para subir a la plataforma de GitHub
El "COMMIT" lo que hace es tomar todos los archivos junto con sus cambios hasta ese momento y los alista para ser cargados a GitHib. (NOTA: Si posterior a este paso, se realizan cambios, estos no se subiran)

GIT PUSH -U ORIGIN MAIN

Este comando nos subirá nuestro repositorio, tomará todos nuestros archivos y los subirá a la rama main de GitHub.
La parte "-U" lo que hace es actualizar en caso de que existan cambios. (no es obligaotorio ponerlo pero se recomieda incluirlo)
