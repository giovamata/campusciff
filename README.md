Creaci�n de Directorio

Clonar Repositorio en Local
$ git clone git@github.com:giovamata/campusciff.git
Cloning into 'campusciff'...
Enter passphrase for key '/c/Users/Giovanni/.ssh/id_rsa':
warning: You appear to have cloned an empty repository.
Checking connectivity... done.

Creaci�n archivo README
echo "README.MD"> README.md

PUSH Inicial
git push git@github.com:giovamata/campusciff.git

IGNORAR CAMBIOS
echo "Archivo Privado" > ArchivoPrivado.txt
mkdir privada
touch .gitignore

Se edita .gitignore y se incluyen directorios y archivos para no subir a github

git add -A
git commit -m "subida Ignorando Cambios"
git push git@github.com:giovamata/campusciff.git


Crear fichero 1.txt
touch 1.txt
git add 1.txt
git commit -m "subir archivo 1.txt"

Crear TAG
Se sube archivo y se le crea un Tag

git tag v0.1

SUBIR TAG v0.1
git push git@github.com:giovamata/campusciff.git


Cuenta GITHUB
1.Poner Foto en Perfil GitHub
   Ver archivo Pantallas.docx

2.Poner Doble factor de validacion en cuenta
   Ver archivo Pantallas.docx

3.Clave publica del ordenador
   Ver archivo Pantallas.docx 




USO Social GITHUB
1.Buscar Companeros de Clase
   Ver archivo Pantallas.docx
2.	Seguir compa�eros de Clase
   Ver archivo Pantallas.docx 
3.	A�adir una estrella a los repositorios campusciff del resto de tus compa�eros.
   Ver archivo Pantallas.docx 


Crear Tabla
1. Crear una tabla de este estilo en el fichero README.md con la informaci�n de varios de tus compa�eros de clase:
| Header | Header   |
| ------ | --------:|
| Nombre |< https://github.com/juangarciaciff >| 
| nombre |< https://github.com/araceliMacia >| 



FIN







