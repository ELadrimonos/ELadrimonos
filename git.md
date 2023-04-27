# Ordenes git básicas

---

### `git init`
Genera un repositorio git en la carpeta actual

### `git commit`
Crea un nuevo commit

### `git commit -m "Comentario"`
Crea un nuevo commit con un nombre vinculado a este

### `git branch`
Te muestra la rama actual

### `git branch nuevaRama`
Crea una nueva rama en el repositorio

### `git checkout rama`
Cambia tu posición (HEAD) a otra rama

### `git checkout commit`
Cambia tu posición a un commit específico

### `git merge rama`
Fusiona una rama con la rama actual

### `git init --bare`
Así podemos crear repositorios que vayan a ser usados remotamente

### `git clone repositorio`
Clona el repositorio remoto al directorio actual

### `git pull`
Actualiza el repositorio local para coincidir con el remoto y cambia los datos de los ficheros que estén desactualizados

### `git fetch`
Actualiza el repositorio local, pero no sobreescribe los ficheros hasta que ocurre un merge

### `git push repositorioRemoto rama`
Empuja los cambios a otro repositorio

### `git push -u repositorioRemoto ramaNueva`
Si has creado una nueva rama tendrás que posicionarte en ella y subirla con el parámetro `-u`