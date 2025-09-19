# Aprende.org
Imitación página web con Bootstrap

Parte 1 (configuración y creación de ramas):

Lo primero que hice fue crear desde GitHub el repositorio nuevo para mi tarea y seleccioné la opción de añadir un readme.

Luego cloné el repo con:
git clone https://github.com/SamuelOrduna/Aprende.org.git

Después generé una nueva rama (de nombre READme) para poder hacer commits al README.md usando el comando:
git checkout -b READme

y luego verifiqué que estuviera parado en ella usando:
git branch

ahora ya podría trabajar en esta nueva rama para no hacer commits directo a la rama main...

-- aquí procedo a guardar estos cambios en un commit llamado "configuración inicial (Parte 1)" --
usando el commando: git commit -m "onfiguración inicial (Parte 1)".

*
*
*
Ahora publico la creación de mi rama en local en github usando el comando:
git push
*
Me marcó un error, pues traté de hacer push de los cambios de la rama que cree en local pero que no estaba en mi remoto de GitHub por lo que tuve que correr el comando:
git push -u origin READme
alternativamente pude haber corrido el comando:
git push --set-upstream READme pues con eso hacemos que git sepa que cuando haga un push desde la rama que sea si desde esa rama ahora solo hago git push pues ya sabe a donde subir los cambios me explico? y si no existe esa rama pues la crea.
*
*
Vuelvo a hacer otro commit para reportar este aprendizaje adquirido del push sin tener la rama en remoto. Uso el commando:
git commit -m "Push de rama local, indicando a GH que debe de crear y usar esa rama" eso de ahí en adelante cada que haga:
git push - así a secas..
" 
*
*
*
Me acabo de dar cuenta que hice dos commits pero pues nunca antes hice git add jaja
así que ahora hago:
git add README.md y luego git commit -m "trackeando READ.me"

Parte 2 (desarrollo del sitio):
