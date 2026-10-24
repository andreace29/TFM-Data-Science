# INSTRUCCIONES A SEGUIR

## Instalar Git en Windows
Primero, se hace clic en el enlace https://git-scm.com/install/windows y se instala el que corresponda. Si se tiene otro sistema operativo, se selecciona dicho sistema en vez de Windows.


## Configurar usuario Git
Si es la primera vez que se utiliza Git, hay que configurar el nombre y el correo electrónico:
    1. `git config --global user.name "Nombre Usuario"`
    2. `git config --global user.email "correo@ejemplo.com"`

En caso de que se quiera comprobar la configuración, se usa el comando `git config --global --list`

## Subir código al repositorio
Primero, se va a la ruta donde se tenga el código del proyecto con `cd "C:\Desktop\Master\Data Science"`
A continuación, se inicializa Git usando `git init`
Ahora, se añadirán los archivos con el comando `git add .`
Seguidamente, se crea el primer comit usando `git commit -m "Comentario del commit"`
El siguiente paso es conectar la carpeta con el repositorio de GitHub, con `git remote add origin https://github.com/andreace29/TFM-Data-Science.git`
Finalmente, para subir los archivos empleamos `git push -u origin main`
