### git log
Muestra todo el historial de commits del proyecto

'git log --pretty=format:"%h - %an, %ar : %s"'
Muestra el historial con el formato que indicamos.

### Limitar la salida del historial
'git log -n': cambiamos la n por cualquier numero entero,
por ejemplo: 'git log -2' nos mostrará los 2 commit mas recientes.

'git log --after="2022-01-26 00:00:00"': muestra los commits realizados después de la fecha especificada.

'git log --before=2022-01-26 00:00:00"':muestra los commits realizados antes de la fecha especificada.

Las banderas del comando 'git log' se pudeden usar juntas según nos convenga, por ejemplo:
'git log --after="2022-01-25 12:00:00" --before="2022-01-25 12:30:00"'