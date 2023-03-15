# DEVSECOPS2023

DIPLOMADO SEGURIDAD EN DEVOPS 2023

## Manual básico comandos git

<image src="https://th.bing.com/th/id/OIP.piAMkLAjuBhL3mIPbPgROgHaDm?pid=ImgDet&rs=1" alt="Imagen git">

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



