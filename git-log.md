### git log
Muestra todo el historial de commits del proyecto
` git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos.

### Limitar la salida del Historial
`git log -n` : Cambiamos la n por cualquier número entero.

`git log --after="2016-04-07 00:00:00"` : Muestra los commits realizados después de la fecha específicada.

`git log --before="2016-04-07 00:00:00"` : Muestra los commits realizados antes de la fecha específicada.

Las banderas del comando `git log se pueden usar juntas según convengan`

git log --decorate --oneline --all --graph
Este comando nos muestra el historial en una sola linea por commit.    
