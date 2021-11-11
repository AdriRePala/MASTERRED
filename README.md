¿Qué es GitHub?
- Es un repositorio online que permite la gestión de versiones de los
repositorios git subidos a esta plataforma. El sistema permite descargar,
clonar y subir archivos de forma gratuita a la plataforma a través de git
siempre que los tengas vinculados desde git bash

Instalación de Git
- Para instalar git, iremos a su página oficial para descargar el instalador. U>
vez descargado, lo ejecutamos y seguimos el asistente. Una vez instalado ya
podremos abrir git bash y empezar a crear y editar repositorios con git. Antes
de empezar, nos registraremos con los comandos
o git config --global user.name "Nombre de usuario"
o git config --global user.email "Correo"

Creación de una cuenta en github
- Entraremos a la página oficial de GitHub. Arriba a la derecha daremos en sign
in, nos pedirá correo nombre de usuario y contraseña. IMPORTANTE: El corre
debe ser verdadero porque nos pedirá verificación. Una vez estemos dentro
podremos empezar a crear archivos y repositorios en la plataforma online.

Manejo de Git.
Para comenzar crearemos una carpeta de forma normal o a través de la consola de
git con el comando mkdir carpeta. Una vez creada, entramos a ella con cd
nombre_carpeta y ejecutaremos el comando git init para convertirla en un reposi>
de git. Y dentro de la carpeta empezamos a crear archivos o directorios según
nuestra necesidades.
Para crear un archivo en git bash escribiremos nano nombre.extension e
introducimos algo de texto

Para añadir el nuevo archivo al repositorio usaremos git add nombre.extension

Para guardar los cambios usaremos git commit -m”comentario

Para observar los cambios realizados usaremos git log

Para crear una nueva rama utilizaremos git branch “nombre

Para cambiar de rama utilizaremos git checkout nombre_rama
