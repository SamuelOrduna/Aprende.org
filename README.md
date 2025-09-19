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

Parte 2 (carpetas y estructura del repositorio/proyecto):
*
primero genero 2 carpetas con:
mkdir css public
luego:
cd public  
luego creo una carpeta para iconos de la marca y cosas así con:
mkdir brand
y creo una que se llame images usando:
mkdir images 
(esto para todo lo multimedia)
(a nivel raiz del repositorio) 
*
luego a nivel raiz creo el index.html
*
con estas carpetas vacías iniciales creo los archivos de css (global.css) y genero el código base de mi index.html
*
ahora hago un PR para merge a main, solo para que main tenga esto y cada que quiera hacer cambios fuertes ahora si usar ramas para todo y PR pero ya teniendo algo en main al menos.
*también renombro el texto en paréntesis a lado de Parte 2 para tener una mejor descricpcion mas detallada
*
hago:
git add .
y luego meto otro commit para indicar la creación de esta estructura base:
git commit -m "Carpetas, Estructura del repositorio y archivos base"

Parte 3 (Inicio del desarrollo):
*
*hago