#Práctica 3 - GitHub y repositorio remoto
##Dani Alarcón

##Parte 1: Preparación del Proyecto

### 1. Crear directorios y archivos:

![ex1](./img/cap1.png)

### 2. Inicializa Git:

![ex1-2](./img/cap2.png)

- **¿Qué es el archivo .gitignore y para que sirve?**Es un archivo oculto para indicar lo que tiene que ignorar el repositorio

![e1-3](./img/cap3.png)

### 3. Primera confirmación:

![ex1-4](./img/cap4.png)

## Parte 2: Colaboración en Equipo

## 1.Configura del repositorio remoto:

- **¿Qué pasa si creo un repositorio con el archivo README.md desde GitHub?** Sale el repositorio solo con el archivo README.md.
- **¿Qué pasa si crea un repositorio sin el archivo README.md desde GitHub?** Sale el repositorio vacio con un enlace para copiarlo y poder clonarlo.

	echo "# Practica3-GitHub" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/Dani-Alarcon/Practica3-GitHub.git
	git push -u origin main

## 2. Actualización del Proyecto:

![ex2-1](./img/cap5.png)

## Parte 3: Gestión de Archivos y Cambios

### 1.Ediciones rápidas:

	**git status**
![ex3-1](./img/cap6.png)

	**git log --oneline --graph --decorate --color**
![ex3-2](./img/cap7.png)

	**git status --short**
![ex3-3](./img/cap8.png)

## 2.Borrado y recuperación:
