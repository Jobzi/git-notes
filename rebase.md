# rebase 
interactively your last 3 commits
````bash
git rebase -i HEAD~3
````
example of rebase with a specific commit
````vim
pick 2c08ac6 add readme
pick 5890e92 readme add rebase
````
apply changes
````vim
pick 2c08ac6 add readme
f 5890e92 readme add rebase    #"rebase the commit '2c08ac6' y se mantiene el commit '5890e92'"
````
````
# Commands:
# p, pick <commit> = use commit
# r, reword <commit> = use commit, but edit the commit message
# e, edit <commit> = use commit, but stop for amending
# s, squash <commit> = use commit, but meld into previous commit
# f, fixup <commit> = like "squash", but discard this commit's log message
# x, exec <command> = run command (the rest of the line) using shell
# b, break = stop here (continue rebase later with 'git rebase --continue')
# d, drop <commit> = remove commit
# l, label <label> = label current HEAD with a name
# t, reset <label> = reset HEAD to a label
# m, merge [-C <commit> | -c <commit>] <label> [# <oneline>]
# .       create a merge commit using the original merge commit's
# .       message (or the oneline, if no original merge commit was
# .       specified). Use -c <commit> to reword the commit message.
#
# These lines can be re-ordered; they are executed from top to bottom.
#
# If you remove a line here THAT COMMIT WILL BE LOST.
#
# However, if you remove everything, the rebase will be aborted.
#
````

## vim commands
- i: entrar al modo de inserción
- v: entrar al modo visual (selección de palabras)
- V: entrar al modo visual (selección de líneas)
- w: avanzar al principio de la siguiente palabra
- e: avanzar al final de la siguiente palabra
- b: retroceder al principio de la palabra anterior
- y: copiar (yank) se usa con otros comando para seleccionar texto a copiar
- d: borrar (el texto borrado se copia al portapapeles, o sea que también hace la función de cortar)
- p: pegar
- u: deshacer
- :w: guardar fichero actual
- :q: salir
- :tabe : abrir nueva pestaña con un archivo, si se omite se abre un nuevo buffer vacío
- gt: mover a la siguiente pestaña
- gT: mover a la anterior pestaña
- h, j, k, l: mover cursor una posición a la izquierda, abajo, arriba y a la derecha

