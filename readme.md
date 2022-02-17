# GIT

## Comandos: 

### Comando globales:

+ git --version:
   > Me muestra mi versión actual de git.
+ git config --global user.name "usuario"
   > Asigna mi usurio a mi compu.
+ git config --global user.email "correo que corresponde al usuario"
+ git config user.name
    >nos enseña el usuario actual.
+ git config user.email
    >Nos enseña el correo del usuario actual.
+ ls
    >Nos muestra la lista de archivos que estan en la carpeta que estemos.

### Comandos de repositorio:

+ git init
    >Inicia el repositorio (agrega la palabra master en celeste a la ruta)
+ git status
    >Muestra el estado que se encuentra los archivos
    + Rojo: Untracked
    + Verde: Stage
+ git add
    > (incluir el nombre del archivo si solo quiero uno)
+ git add .
   > Agrega a Stage todo los archivos de una sola vez
+ git commit -m "descripción"
    >Agrega al repositorio todo lo que esta en stage con un nombre y marca de tiempo (automatico)
+ git log
    >Muestra el historial e información de los commit

### Comandos de repositorio remoto (github):
+ git remote add origin https://github.com/ClaudiaL18/hola-mundo.git
    >Agrega con el nombre origin la ruta remota
+ git push -u origin master
    >Empuja la rama master a la ruta remota
+ git pull origin
    >Jala el repositorio desde la ruta remota