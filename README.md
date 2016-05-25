Creación de Directorio

Clonar Repositorio en Local
$ git clone git@github.com:giovamata/campusciff.git
Cloning into 'campusciff'...
Enter passphrase for key '/c/Users/Giovanni/.ssh/id_rsa':
warning: You appear to have cloned an empty repository.
Checking connectivity... done.

Creación archivo README
echo "README.MD"> README.md

PUSH Inicial
git push git@github.com:giovamata/campusciff.git

IGNORAR CAMBIOS
echo "Archivo Privado" > ArchivoPrivado.txt
mkdir privada
touch .gitignore

Se edita .gitignore y se incluyen directorios y archivos para no subir a github












