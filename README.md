# DEVSECOPS2023

DIPLOMADO SEGURIDAD EN DEVOPS 2023

## Manual básico comandos git

<image src="https://th.bing.com/th/id/OIP.piAMkLAjuBhL3mIPbPgROgHaDm?pid=ImgDet&rs=1" alt="Imagen git">

#### ¿Que es GIT?
Git es un sistema de control de versiones distribuido, lo que significa que un clon local del proyecto es un repositorio de control de versiones completo. Estos repositorios locales plenamente funcionales permiten trabajar sin conexión o de forma remota con facilidad. Los desarrolladores confirman su trabajo localmente y, a continuación, sincronizan su copia del repositorio con la copia en el servidor. Este paradigma es distinto del control de versiones centralizado, donde los clientes deben sincronizar el código con un servidor antes de crear nuevas versiones.

### Los comandos básicos en git son:
`git init`:
- Crea un repositorio

`git checkout`:
- Permite movernos entre ramas

`git checkout -b`:
- Permite crear una nueva rama a base de la rama HEAD y cambiara a ella instantaneamente
    - `git checkout -b new_branch existing_branch`:
        - Permite crear una nueva rama a base de una rama existente y cambiara a ella instantaneamente

`git branch`
- Permite listar las ramas existentes
    - `git branch new_branch`
        - Permite crear una nueva rama


### Los comandos principales en git son:

`git status`:
- Lista los archivos que han tenido un cambio frente al último commit HEAD
    - Muestra los archivos en dos estados:
        - Los archivos que se han agregado para un commit 
        - Los archvivos que no se han agregado para un commit

`git add`:
- Agrega archivos y los deja listos para un próximo commit. Estos se pueden agregar de dos formas:
    - `git add .`:
        - Agrega todos los archivos que detecte con algun cambió frente al ultimo commit HEAD
    - `git add <archivo especifico>`:
        - Agrega un archivo especifico, sin la necesidad de agregar todos aquellos que hayan tenido algún cambio

`git commit -m 'message'`:
- Se confirman los cambios agregados y se agrega un comentario a este (el comentario es obligatorio), enviandolo al repositorio local

`git push`:
- Verifica los cambios confirmados en el repositorio local y los envía al repositorio remoto

`git fetch`:
- Actualiza el repositorio local a base del repositoio remoto

`git merge`:
- Combina los cambios de dos ramas

`git pull`
- Actualiza el repositorio local y ejecuta git merge



