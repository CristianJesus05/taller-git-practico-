# REFLEXIÓN FINAL - TALLER PRÁCTICO DE GIT

### 1. ¿Qué fue lo más difícil de la actividad? ¿Qué te costó más entender?
Lo más desafiante fue comprender la diferencia entre rebase e integración por fusión (merge), así como aprender a resolver manualmente los conflictos de código quitando los marcadores (<<<<<<<, =======, >>>>>>>).

### 2. ¿Cuál de todos los comandos crees que usarás con más frecuencia y por qué?
Los comandos de uso diario son `git status`, `git add`, `git commit` y `git push`, ya que son la base para preparar, guardar y sincronizar cualquier cambio en el flujo de trabajo.

### 3. ¿En qué situaciones usarías el comando que deshace el último commit eliminando cambios frente al que crea un commit inverso?
Usaría `git reset --hard` únicamente en mi entorno local para descartar código de prueba que no sirve. En cambio, usaría `git revert` cuando trabaje en ramas compartidas o públicas para no alterar la historia de commits de mis compañeros.

### 4. ¿Cuándo preferirías descargar cambios sin fusionar (fetch) en lugar de descargar y fusionar (pull)?
Usaría `git fetch` cuando quiera revisar o inspeccionar lo que subieron otros miembros del equipo al servidor remoto antes de integrar esos cambios a mi código local, evitando sorpresas o conflictos inesperados.

### 5. ¿Por qué es peligroso usar el comando que fuerza el push (push --force)?
Porque sobreescribe de forma destructiva el historial del repositorio remoto con lo que tengo en mi máquina local, lo que puede borrar permanentemente commits o avances que otros compañeros hayan subido.

### 6. ¿Qué aprendiste que no sabías antes de esta actividad?
Aprendí a rescatar commits borrados usando `git reflog`, a preparar únicamente líneas específicas de un archivo mediante `git add -p` y a traer commits puntuales de otras ramas con `git cherry-pick`.
