# Taller de Git

Este es un ejemplo de archivo markdown para documentar un repositorio Git.

## Configurar git local


	git config --global user.name "[name]"
	git config --global user.email "[email address]"

## Crear repositorio

	git init

## Crear archivos y agregarlos al repositorio

	touch readme.md
	git add readme.md
	git commit -m "Mesaje"
	
## Subir repositorio a github

1. Crear el repositorio en github
2. subir el contenido de la rama master

		git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git
		git push -u origin master
