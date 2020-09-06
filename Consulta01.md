# Consulta 01: Git, Gradle y Maven

# Git
![](Source/img/git01.png)

[Git](https://git-scm.com/) es un software de **control de versiones** diseñado por [**Linus Torvalds**](https://es.wikipedia.org/wiki/Linus_Torvalds), pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un **gran número de archivos de código fuente**. Es decir **Git** nos proporciona las herramientas para desarrollar un trabajo en equipo de manera inteligente y rápida y por *trabajo* nos referimos a algún software o página que implique código el cual necesitemos hacerlo con un grupo de personas.

En cuanto a derechos de autor Git es un **software libre** distribuible bajo los términos de la versión 2 de la [Licencia Pública General de GNU](https://www.gnu.org/licenses/gpl-3.0.html).

<br />

![](Source/img/git02.jpg)

## ¿Qué es control de versiones?

Pues bien, se define como control de versiones a la gestión de los diversos cambios que se realizan sobre los elementos de algún producto o una configuración del mismo es decir a la gestión de los diversos cambios que se realizan sobre los elementos de algún producto o una configuración, y para los que aún no les queda claro del todo, control de versiones es lo que se hace al momento de estar desarrollando un software o una página web. Exactamente es eso que haces cuando subes y actualizas tu código en la nube, o le añades alguna parte o simplemente le editas cosas que no funcionan como deberían o al menos no como tú esperarías.

## Y, entonces ¿A qué le llamamos *sistema de control de versiones*?

Muy sencillo, son todas las herramientas que nos permiten hacer todas esas modificaciones antes mencionadas en nuestro código y hacen que sea más fácil la administración de las distintas versiones de cada producto desarrollado; es decir Git.

![](Source/img/git03.png)
<br/>
[Sobre el Control de Versiones.](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Fundamentos-de-Git)
<br/>

### Algunas de las características más importantes de Git son:

- Rapidez en la gestión de ramas, debido a que Git nos dice que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente.

- Gestión distribuida; Los cambios se importan como ramas adicionales y pueden ser fusionados de la misma manera como se hace en la rama local.

- Gestión eficiente de proyectos grandes.

- Realmacenamiento periódico en paquetes.

## Los Tres Estados

Git tiene tres estados principales en los que se pueden encontrar tus archivos: confirmado (committed), modificado (modified), y preparado (staged). Confirmado: significa que los datos están almacenados de manera segura en tu base de datos local. Modificado: significa que has modificado el archivo pero todavía no lo has confirmado a tu base de datos. Preparado: significa que has marcado un archivo modificado en su versión actual para que vaya en tu próxima confirmación.

Esto nos lleva a las tres secciones principales de un proyecto de Git: El directorio de Git (Git directory), el directorio de trabajo (working directory), y el área de preparación (staging area).

![](Source/img/git04.png)
<br/><br/>

## Funcionamiento de Git

Básicamente, Git funciona del siguiente modo:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**1.** Crea un “repositorio” (proyecto) con una herramienta de alojamiento de git (como Bitbucket).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2.** Copia (o clona) el repositorio en tu equipo local.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**3.** Añade un archivo en tu repositorio local y “confirma” (guarda) los cambios.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**4.** “Envía” tus cambios a la rama maestra.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**5.** Realiza un cambio en tu archivo con una herramienta de alojamiento de git y confírmalo.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**6.** “Incorpora” los cambios en tu equipo local.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**7.** Crea una “rama” (versión), haz un cambio y confírmalo.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**8.** Abre una “solicitud de incorporación de cambios” (propón cambios en la rama maestra).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**9.** “Fusiona” tu rama con la rama maestra.  

![](Source/img/git05.png)

## Comandos Básicos

> "Añadir" se refiere a agregar archivos al *Staging Area* de git, es decir que git ya le estaría haciendo seguimiento a los cambios en dichos archivos

- Iniciar un repositorio vacío en unas carpeta específica:  
`git init`
- Añadir un archivo especifico:  
`git add <nombre_archivo>`
- Añadir todos los archivos del directorio "actual":  
`git add .`
- Guardar/confirmar cambios de los archivos que se encuentren en el *Staging Area*. El agregado `-m` es para añadir un mensaje **descriptivo** al commit:  
`git commit -m "<mensaje>"`
- Es el equivalente a hacer `git add .` y `git commit -m` juntos:  
`git commit -am "<mensaje>"`
- Lista todos los `commits` realizados a lo largo de nuestro proyecto:  
`git log`
- Sube la rama “nombre_rama” al servidor remoto:  
`git push origin <nombre_rama>`
- Descarga los cambios realizados en el repositorio remoto:  
`git fetch`
- Incluye en la rama que te encuentras parado, los cambios realizados en la rama “nombre_rama”:  
`git merge <nombre_rama>`
- Unifica los comandos `fetch` y `merge` en un único comando:  
`git pull`
- Muestra el estado actual de la rama, como los cambios que hay sin commitear:  
`git status`
- Crea una rama a partir de la que te encuentres parado con el nombre “nombre_rama_nueva”, y luego salta sobre la rama nueva, por lo que quedas parado en esta última:  
`git checkout -b <nombre_rama_nueva>`
- Si existe una rama remota de nombre “nombre_rama”, al ejecutar este comando se crea una rama local con el nombre “nombre_rama” para hacer un seguimiento de la rama remota con el mismo nombre:  
`git checkout -t origin/<nombre_rama>`
- Lista todas las ramas locales:  
`git branch`
- Lista todas las ramas locales y remotas:  
`git branch -a`
- Elimina la rama local con el nombre “nombre_rama”:  
`git branch -d <nombre_rama>`
- Actualiza tu repositorio remoto en caso que algún otro desarrollador haya eliminado alguna rama remota:  
`git remote prune origin`
- Elimina los cambios realizados que aún no se hayan hecho commit:  
`git reset --hard HEAD`
- Revierte el commit realizado, identificado por el “hash_commit”:  
`git revert <hash_commit>`


[comment]: <> (Cristhian)



## Github, Gitlab y Bitbucket
[comment]: <> (Alejandro)


# Gradle
[comment]: <> (Janer)



# Maven
[comment]: <> (Hernan)
