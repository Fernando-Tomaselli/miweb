# GIT
historial completo de todo el codigo que hemos realizado en nuestra aplicacion.
Trabaja de manera descentralizada.

- Historial del trabajo realizado
- Almacenar codigo
- Trabajar en equipo
- Podemos ver Cuando se introdujo un error.

Instalar GIT:
Link: 

GIT BASH, es una terminal q nos permitira ejecutar los comandos de GIT
## Terminal
Configuracion:

git --version

git config --global

git config --global user.name "Fernando Tomaselli"

git config --global user.email tomasellif@hotmail.com

git config --global -e

git config -h


## Terminal
ls --> permite listar todos los archivos y carpetas de determinado directorio.

pwd --> indica la ubicacion de la carpeta donde nos encontramos acualmente.

cd carpetaX --> para moverme a otra ubicacion.

cd .. --> para salirme de la ubicacion de donde estoy, y volver una carpeta atras.

mkdir NombreCarpeta --> Crea una carpeta con el nombre indicado.

git init -- Para inicializar un repositorio

ls -a -- Podemos ver los archivos ocultos para ver si se inicio el repositorio creado.

cd .git

DETALLE DE IMPLEMENTACION (Como va almacenar el codigo)
$ ls -a
./  ../  config  description  HEAD  hooks/  info/  objects/  refs/

git status -- Para ver el estado de los archivos

git add nombreArchivo -- Para agregar algun archivo al repositorio

git commit -m "commit inicial" -- Tiene q ser un msj q tenga sentido, descriptivo de la tarea o los cambios realizados

git rm archivo.txt -- Elmina el archivo

git restore --staged archivo.txt

git restore archivo.txt

mv archivo.txt archivoModificado.txt -- Cambio el nombre del archivo

git mv archivo.txt archivoModificado.txt -- Cambio el nombre del archivo, y actuliza el estado

- Dentro del archivo .gitignore podemos indicar que archivos, carpetas no queremos agregar al repositorio.

git status -s -- Otra forma mas simple de ver los estados

git branch -- Para ver en q rama estamos parados

git checkout -b ramaX -- Crea una rama

git checkout master -- Vuelvo a la Rama Master

cat readme.md -- Me aparece en terminal todo el archivo readme
    Sirve para ver q tiene el archivo, si cambio de una rama a la otra.

git merge ramaX -- Asi traigo a la rama Master, todo lo q estaba en la ramaX  
