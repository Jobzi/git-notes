# Stash

Git tiene un área llamada "stash" donde puedes almacenar temporalmente una captura de tus cambios sin enviarlos al repositorio. Está separada del directorio de trabajo (working directory), del área de preparación (staging area), o del repositorio.

Esta funcionalidad es útil cuando has hecho cambios en una rama que no estás listo para realizarle commit, pero necesitas cambiar a otra rama.
 
````bash
git stash #Stashinng changes
````
````bash
git stash save "mensaje opcional para ti" #Stashinng changes
````
````bash
git stash list #list of stashes
````
````bash
git stash show -p stash@{0} #show stash
````
````bash
git stash apply #Apply last stashed change, puedes ver un resumen 
````
`git stash apply NOMBRE-DEL-STASH` aplica los cambios y deja una copia en el stash
`git stash pop NOMBRE-DEL-STASH` aplica los cambio y elimina los archivos del stash
````bash
git stash drop NOMBRE-DEL-STASH # remover los cambios guardados en stash sin aplicarlos
````
````bash
git stash clear #clear all stashes
````
