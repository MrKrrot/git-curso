# Comandos GIT

```bash
# Inicializa un repositorio vacío de Git
$ git init

# Ver el estado del repositorio
$ git status

# Agrega los archivos seleccionados al área de preparación o Staging Area
$ git add <archivos>

# Restablece los cambios realizados en el archivo por el último cambio realizado en el historial
$ git restore <archivos>

# Elimina del área de preparación los archivos seleccionados
$ git restore --staged <archivos>

# Realiza un cambio que se guardará en el historial de cambios
$ git commit -m "Mensaje"

# Visualiza el historial de cambios realizados en el repositorio
$ git log

# Visualiza el historial de cambnios realizados en el repositorio de manera compacta
$ git log --oneline

# Visualiza las ramas existentes
$ git branch

# Crea una nueva rama
$ git branch <nombre_rama>

# Te mueves a la rama escrita
$ git checkout <nombre_rama>

# Crea una nueva rama y te mueves a ella
$ git checkout -b <nombre_rama>

# Elimina la rama escrita
$ git branch -d <nombre_rama>
```
