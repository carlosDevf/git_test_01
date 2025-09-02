- git init 
- git add . git add --archivo
- git commit -m 'descripcion corta de mis cambios'
- git remote * una solo vez para vincular el repo o mi carpeta actual con la remota
- git push origin <nombre de la rama>

*** comandos secundarios
git status
git log <ver todos los commits sin importar la rama actual>
git branch <ver todas las ramas del /proyecto/modulo/carpeta_local/app/repostirio>
git config --local ---edit  <modificar la configuracion de mi proyecto>
git switch -c <nombre de la ram> - crea una rama nueva y se cambia 
git switch - <cambia a una rama pasada>
git switch <nombre de la rama> -- cambia a la rama especifica

** Estudienlo ** 
git cherry pick
git stash ***peligro***
git restore -- nombre archivo *** 

## flujo una vez que ya tenemos un repositorio
- git add .
  * git add --archivo

- git commit -m 'descripcion corta de mis cambios'

** si ya quiero subirlo
- git push origin <nombre de la rama>

## Cuando trabajamos en equipo?
git clone <nombre de la ruta del repositorio> 