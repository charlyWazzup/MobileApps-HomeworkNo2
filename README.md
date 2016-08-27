###### Tarea No. 2 -- Carlos Emmanuel Botello Ovalle

###### `Git Rebase` y sus aplicaciones en un `Pull Request`

Cuando tenemos una serie de _commits_ que queremos juntar, el comando `rebase` mantiene una historia de _commits_ un poco mas limpia. Con `rebase` es posible juntar uno o mas _commits_ en uno solo. El procedimiento que se sigue es localizar la rama o el `hash` anterior al primer _commit_ que queremos aregar. Se utiliza el comando `git rebase -i`

###### `Pull` utilizando `Rebase`

Cuando hacemos un `pull` con _git pull_, agarramos los cambios del repositorio que elijamos. Junto con este podemos utilizar `rebase`.

Cuando se hace un `pull`, lo que en realidad ocurre es un `fetch` junto con un `merge`. Al hacer un `rebase`, git intentara tomar todos los cambios y despues aplicar las modificaciones que hayamos hecho en vez de hacer un `merge` desde el punto en el que nos encontrabamos. Esto hara que todo quede mas limpio y entendible.
