# Glosario de comandos basicos bash
------------------------------------------------------------------------------------------------------------------------------------------------
help: Puedes utilizar el comando help en cualquier momento para obtener más información sobre el uso y la sintaxis de un comando especifico, como qué opciones están disponibles y cómo estructurar realmente el comando para usar sus diversas opciones. También proporciona información en línea sobre los comandos disponibles y el entorno de shell.

cd: cambia de directorio 
cd .. Regresa de directorio 

ls:muestra los ficheros en el directorio actual.

pwd: imprime el nombre del directorio actual integrando a su vez la ruta completa tomando como origen la raíz (/).

mkdir: crear un nuevo subdirectorio o carpeta del sistema de archivos.

echo: echo es un comando para la impresión de un texto en pantalla.

rm: elimina un archivo, -rf para forzar que se elimine.

history: averigua los últimos comandos que se han ejecutado en un Servidor.

git --version/-v: muestra la version de git instala.

git init: crea un nuevo repositorio de Git.

code: Abre Visual Studio Code (. code)

git status: mostrará los diferentes estados de los archivos en tu directorio de trabajo y área de ensayo. Qué archivos están modificados y sin seguimiento y cuáles con seguimiento pero no confirmados aún. En su forma normal, también te mostrará algunos consejos básicos sobre cómo mover archivos entre estas etapas.
Git status: El comando de git status nos da toda la información necesaria sobre la rama actual.


git add: añade contenido del directorio de trabajo al área de ensayo (staging area o 'index') para la próxima confirmación. Cuando se ejecuta el comando git commit, éste, de forma predeterminada, sólo mira en esta área de ensayo, por lo que git add se utiliza para fabricar exactamente lo que te gustaría fuese tu próxima instantánea a confirmar.


git diff: se utiliza cuando deseas ver las diferencias entre dos árboles. Esto prodría ser la diferencia entre tu entorno de trabajo y tu área de ensayo (git diff por sí mismo), entre tu área de ensayo y tu última confirmación o commit (git diff --staged), o entre dos confirmaciones (git diff master branchB).


git restore: se utiliza sobre todo para deshacer las cosas, como posiblemente puedes deducir por el verbo. Se mueve alrededor del puntero HEAD y opcionalmente cambia el index o área de ensayo y también puede cambiar opcionalmente el directorio de trabajo si se utiliza --hard. Esta última opción hace posible que este comando pueda perder tu trabajo si se usa incorrectamente, por lo que asegúrese de entenderlo antes de usarlo.

git commit: toma todos los contenidos de los archivos a los que se les realiza el seguimiento con git add y registra una nueva instantánea permanente en la base de datos y luego avanza el puntero de la rama en la rama actual.

git config --global user.email/user.name: Se ingresa  el correo y nombre de usuario de quien estara trabajando en el repositorio

git log --oneline: muestra una lista de los commits que se han realizado en el repositorio

git log: explora el historial del repositorio. Este comando se usa cuando necesitas buscar una versión concreta de un proyecto o saber los cambios que se introducirán mediante la fusión en una rama de función.

clear: limpia la consola 

git branch:  Usando ramas, varios desarrolladores pueden trabajar en paralelo en el mismo proyecto simultáneamente. Podemos usar el comando git branch para crearlas, listarlas y eliminarlas.

git checkout: Usaremos git checkout principalmente para cambiarte de una rama a otra. También lo podemos usar para chequear archivos y commits. 

git clone: descarga el código fuente existente desde un repositorio remoto.

Git merge: integra las características de tu rama con todos los commits realizados a las ramas dev (o master).



------------------------------------------------------------------------------------------------------------------------------------------------
