git init "crea el repositorio local"

git commit "guarda un registro de lo que se va a subir"

git status "si los archivos estan en rojo es porque no se han agregado"
git add . "sube los archivos al escenario para ser subidos"

git commit -m ""  "entre las comillas el titulo del commit"

git checkout -- . "reconstruye todo mi sitio a la version del ultimo commit"

git diff    "nos dice que cambios hubo.. ejemplo me fui a almorzar y no me acuerdo de lo que hice al llegar"

git diff --staged    "me dice que cambios hubo si hice commit pero no push, esto puede pasar si deje el commit y me fui a mi casa a seguir trabajando pero no hice push desde el trabajo"

git reset HEAD "nombre del archivo.extension"    "elimina ese archivo del commit"


/--------------------------------------/
Posible error/warning que tienen algunos
Posible warning que tengan unos de ustedes.

Si les aparece este warning:
Pueden configurar ese salto de carrete así
git config core.autocrlf true
Para que ya no les aparezca esa advertencia molesta.
/--------------------------------------/


git reset --mixed 11111111    "de esta manera nos movemos al commit anterior, donde 11111111 es el commit"

asdkljasd

adsasdasdasd


cambiar el nombre de mi git "no el usuario si no el nickname por asi decirlo"

git config --global user.name "jefreysanchez"

prueba git 
el stash se hace sin hacer merge.. simplemente guarda los estados trabajados en una memoria alterna
devuelve al anterior despliegas y luego si quieres regresas con unstash

wip in stash... work in progress
git stash pop recupera el trabajo


fork toma repositorio original y lo sube a un usuario personal
