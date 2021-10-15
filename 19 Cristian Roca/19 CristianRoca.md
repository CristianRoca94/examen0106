# Proyecto colaborativo en GitHub (ramificando la rama principal)  
#### Cristian Roca Flores, 1 DAW


Dentro del desarrollo del software, es importante tener un workflow claro y ordenado; y en GitHub podemos hacerlo teniendo repositorios colaborativos y ramificaciones del proyecto principal para tener una mejor visualizacion de los cambios realizados

Los pasos a seguir son:

1. Hacer un fork al repositorio main (el usuario propietario debe hacerte colaborador)

![haciendofork](C:\Users\1daw3\Documents\19 Cristian Roca\examen0106\19 Cristian Roca\19 IMG\1.png)

![haciendofork](C:\Users\1daw3\Documents\19 Cristian Roca\examen0106\19 Cristian Roca\19 IMG\2.png)

2. Estando en nuestro repositorio, vamos a clonarlo este repositorio y para ello vamos a crear una carpeta en terminal y abrir la ubicacion donde vamos a clonar, como aparece en la imagen. Copiaremos el enlace de nuestro repositorio:

![](C:\Users\1daw3\Documents\19 Cristian Roca\examen0106\19 Cristian Roca\19 IMG\3.png)

![](C:\Users\1daw3\Documents\19 Cristian Roca\examen0106\19 Cristian Roca\19 IMG\4.png)

![](C:\Users\1daw3\Documents\19 Cristian Roca\examen0106\19 Cristian Roca\19 IMG\5.png)

3. Creamos una rama de trabajo con git checkout -b rama01

4. Creamos la estructura completa de arbol (carpetas)

5. Una vez terminemos de editar nuestros archivos, hacemos en terminal un git add -A

6. Luego haremos un commit, escribiendo en terminal git commit -m "Mensaje a poner"

7. Posteriormente enviaremos estos cambios a nuestro repositorio en GitHub con el comando git push -u rama01

8. Accederemos a nuestro GitHub, y haremos el merge de nuestros cambios enviados desde el clon local. 

9. Una vez hecho esto, el propietario verá los cambios y hará el merge en el proyecto original 



