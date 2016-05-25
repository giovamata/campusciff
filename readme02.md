Ejercicio 2


Creacion de Readme para Ejercicio 2
touch readme02.md
git add -A
git commit -m "Subir Readme Segundo Ejercicio"
git push git@github.com:giovamata/campusciff.git



Crear una rama v0.2 y posicionarse en ella
git branch v0.2
git checkout v0.2



Añadir fichero 2.txt
touch 2.txt




Crear rama remota v0.2
git add -A
git commit -m "Archivo 2.txt en branch"
git push git@github.com:giovamata/campusciff.git




Hacer MERGE Directo
git checkout master
git merge v0.2



Merge con conflicto
Se edita archivo en windows, se agrega pantalla “HOLA”.
git add -A
git commit -m "Editanto Archivo 1.txt con HOLA"

Se hace los mismos pasos anteriores para branch v0.2 pero se edita archivo y se agrega “Adios”
Se efectúa el merge y da conflicto:
$ cat 1.txt
<<<<<<< HEAD
Hola
=======
ADIOS
>>>>>>> v0.2

Se edita y se deja lo que se desea.


Lista ramas con y sin merge
Giovanni@Giovanni MINGW64 ~/campusciff (master|MERGING)
$ git branch --merged
* master

Giovanni@Giovanni MINGW64 ~/campusciff (master|MERGING)
$ git branch --no-merged
  V0.2




Crear Tag y Borrar rama v0.2
git tag v0.2
git branch -d 1.NoMerge




Listado de Cambios

Giovanni@Giovanni MINGW64 ~/campusciff (master|MERGING)
$ git log
commit ddd4e9ae6cecfaf97ad01e36b3a96ee6c7af70b6
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 21:35:42 2016 +0200

    Editanto Archivo 1.txt con HOLA

commit 651f54715aeff7a34c57405c4ae6bb0f40053879
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 21:28:14 2016 +0200

    Archivo 2.txt en branch

commit 40b502879c0a4ea70c88b25ecb63e594d80f1160
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 21:23:18 2016 +0200

    Archivo 2.txt en branch

commit 09db2b557e39c8ac16bc086bd16c4205a182c072
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 21:11:43 2016 +0200

    Subir Readme Segundo Ejercicio

commit 40b9a3ce00b2ff62aaa29e289a0c9ea06aafeeb7
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 20:59:40 2016 +0200

    final readme.md

commit 73ca849e739125741bda6410a36f70a8dcda4a43
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 20:52:58 2016 +0200

    final readme.md

commit ae8c5d01fce45a080a4386daed3bc6735f6ae45b
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 20:11:13 2016 +0200

    subir archivo 1.txt

commit 877956b782fe0dc68c439b0dcded4378fd686af7
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 20:03:19 2016 +0200

    subida Ignorando Cambios

commit 26de826b51f8e264223655fd76da0dc4840a00f9
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 19:31:30 2016 +0200

    commit inicial archivo readme.md

commit 4137ca9505048162703276029bf29af0cb6cde21
Author: Giovanni Gonzalez <giovamata@gmail.com>
Date:   Wed May 25 19:20:06 2016 +0200

    commit inicial README.md

Giovanni@Giovanni MINGW64 ~/campusciff (master|MERGING)
$




Crear una organización
	ver Pantallas02.docx

Crear equipos
	ver Pantallas02.docx

Crear un index.html
	ver Pantallas02.docx