# Introducción y configuración de Git

El control de versiones es fundamental para registrar y gestionar los cambios realizados en un proyecto. Permite guardar de manera segura diferentes versiones de un proyecto, facilitando la recuperación de cualquier versión específica para el usuario. 

En el control de versiones, se utiliza el concepto de **Git**, que es una herramienta de control de versiones, que nos permite inicializar, distribuir y crear proyectos de una manera eficiente. 

* [Descargar Git](https://git-scm.com/downloads) > Elegir el sistema operativo. 🪟🍏🐧

Después de inicializar un repositorio local, para empezar a trabajar con las versiones del proyecto desde un reposiorio remoto, existen varias **plataformas**: 


1. Github [Visita Github](https://github.com)
2. Gitlab [Visita Gitlab](https://gitlab.com)
3. Bitbucket [Visita bitbucket](https://bitbucket.org/product/)

## Configuración Inicial de Git. 

Durante la instalación de Git, dejas las opciones por defecto que ofrece el instalador de git. 

1. Configurar el **nombre** de usuario y el **correo eléctrónico** para que se apliquen a todos los repositorios.

```shell
git config --global user.name "Juan Perez"
```

```shell
git config --global user.email "juanperez@gmail.com"
```
Con esta configuración, todos los cambios (commits) que se hagan a un repositorio usará esta información. 

2. Configurar clave SSH para tener acceso a los repositorios remotos (plataformas).




