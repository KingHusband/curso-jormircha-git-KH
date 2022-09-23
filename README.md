# Curso de _Git_ & _GitHub_

Hola, Daniel, recuerda que este README es para describir resumidamente el contenido del repositorio.

Este commit es para oficializar nuestra versión **1.0.0**.

<!-- Cambios -->

<!-- Para hacer un cambio a un commit, puedes realizarlo mientras no hayas hecho un push al repositorio remoto. Porque si no habría que crear otro commit especificando que hubo conflictos y se resolvieron. Así, al revisar el historial de cambios, se podría entender fácilmente lo que sucedió.

Sólo debemos ejecutar el comando git push cuando estamos seguros de que los cambios que realizamos están correctos y no van a tener conflicto con algún archivo del repositorio.

Si por error cambiamos algo que no debía ser así, y agregamos el cambio al staging, lo que debemos hacer es hacer un hard reset al HEAD~1 para volver al commit anterior, y allí poder escribir el código correctamente. -->

<!-- Registro del historial -->

<!-- git log nos permite conocer todo el historial de un proyecto, con la información de la fecha, el autor y id de cada cambio. Para obtener más información, recurrir a la documentación del comando git log, con los comandos de ayuda de git: git 'comando' -h y git help 'comando'. -->

<!-- git log

# muestra en una sola línea por cambio
git log --oneline

# guarda el log en la ruta y archivo que especifiquemos
git log > commits.txt

# muestra el historial con el formato que indicamos
git log --pretty=format:"%h - %an, %ar : %s"

# cambiamos la n por cualquier número entero y mostrará los n cambios recientes
git log -n

# muestra los cambios realizados después de la fecha especificada
git log --after="2019-07-07 00:00:00"

# muestra los cambios realizados antes de la fecha especificada
git log --before="2019-07-08 00:00:00"

# muestra los cambios realizados en el rango de fecha especificado
git log --after="2019-07-07 00:00:00" --before="2019-07-08 00:00:00"

# muestra una gráfica del historial de cambios, rama y fusiones
git log --oneline --graph --all

# muestra todo el registro de acciones del log
# incluyendo inserciones, cambios, eliminaciones, fusiones, etc.
git reflog

# diferencias entre el Working Directory y el Staging Area
git diff -->