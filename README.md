# Titulo: GitHub
## Autor: Alexandru Stefan Gheorghe
## Introducción: 
GitHub es una plataforma que permite a los desarrolladores la posibilidad de almacenar y comprartir sus trabajos de forma directa en la nube, como la posiblidad de trabajar en equipo en un repositorio, con seguimiento sobre los diferentes cambios realizados y la posibilidad de restablecer versiones anteriores.
## Instalación GitHub en Linux/Ubuntu y creación de archivos:
Para la instalación mediante el terminal, acutualizaremos el administrador de paquetes e instalaremos Git, luego revisaremos la versión de Git para ver si se ha instalado correctamente.

$ sudo apt update
$ sudo apt install git
$ git --version

A continuación crearemos un directorio y un archivo de prueba, acto seguido se podrá  editar mediante un editor de texto como "gedit" o "nano".

$ mkdir pruebaGitHub
$ cd pruebaGitHub
$ touch prueba.c
$ gedit prueba.c

Configurar el Git en local:

$ git config --global user.email “<miCorreoElectrónicoEnGitHub>”
$ git config --global user.name “<miNombreEnGitHub>”

Iniciar repositorio de GitHub y subir:

$ git init
$ git add .
$ git commit -m “Subida del archivo de prueba”
$ git push


## Conclusión:
Aparte de ser una plataforma gratuita, cumple a nivel de seguridad y la posibilidad del agilizar el trabajo en equipo.

