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
Se edita aarchivo en windows, se agrega pantalla “HOLA”.
git add -A
git commit -m "Editanto Archivo 1.txt con HOLA"