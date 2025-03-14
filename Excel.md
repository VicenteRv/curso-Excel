## Sección 2: Introducción a Excel

### Video 5: Celdas, columnas y filas en Excel

> [!Tip]
> Para poder movernos mas rápido entre datos de las columnas o filas donde tenemos información podemos presionar las teclas `ctrl + ->`, `ctrl + <-`,`ctrl + "Flecha arriba"`, `ctrl + "Flecha abajo"` lo que nos hara mas rapido el desplazamiento entre nuetros datos

### Video 6: Manejo de rangos en Excel

Para comenzar este video comenzaremos investigando que es un [[rango]], una vez entendido esto pasamos a la practica
<br>
> [!Tip]
> Para poder seleccionar varias celdas rápido entre datos de las columnas o filas donde tenemos información podemos presionar las teclas `ctrl + shift + ->`, `ctrl + shift + <-`,`ctrl + shift + "Flecha arriba"`, `ctrl + shift + "Flecha abajo"` lo que nos hará mas rápido la seleccion de varios elementos 

 Aquí una foto de como se vería seleccionado cierta parte de la hoja
 ![[Pasted image 20250313032313.png]]
 Además de que a este rango le podemos asignar un nombre, como se mostrara a continuación
 ![[Pasted image 20250313032504.png]]
 Además de que este se va a guardar y si en algún momento queremos trabajar con esto solo podemos ir a donde se nombran, dar clic en la flecha para visualizar todo y seleccionar el nombre del rango que queremos
 ![[Pasted image 20250313032724.png]]
Y, al seleccionarlo automáticamente se nos van a seleccionar las casillas que pusimos como parte del rango nombrado como `rango1`
![[Pasted image 20250313032504.png]]
También se pudo asignar un nombre al rango si seleccionamos ciertos datos, y vamos a la pestaña de  `Formulas` y después damos clic en la parte de `asignar nombre` o en `Administrador de nombres` que es donde nos va a mostrar todos los nombres que tenemos asignados en los rangos o celdas
![[Pasted image 20250313033243.png]]
Si damos clic en la parte de asignar nombre, podemos observar que nos muestra el nombre: `primer_texto`, nos pregunta un ámbito (en que lugar podemos utilizar el rango, en ese caso pone que en el libro, así que dentro de todo el libro se puede utilizar ese rango), se le puede agregar un comentario, posteriormente en la parte de `S refiere a: =nuevaHoja1!$A$1:$I$7` donde se le asigna en primer lugar el nombre de la hoja y después las celdas seleccionadas de ese rango
![[Pasted image 20250313033515.png]]
Podemos darnos cuenta de que nos da otras opciones que vienen siendo las otras hojas de nuestro libro
![[Pasted image 20250313033926.png]]
Ahora, si le damos clic en el apartado de administrar nombres
![[Pasted image 20250313033243.png]]
Podemos ver que se nos muestran los rangos
![[Pasted image 20250313034432.png]]

### Video 7:  Ejercicio manejo de celdas
Para comenzar con esto es un ejercicio que se nos deja ya que recién terminamos de ver este tema
Para ello se nos confía la siguiente tarea
![[Pasted image 20250313034745.png]]
Para comenzar con el primer punto vamos a cerrar cualquier libro abierto, para lo cual nos vamos a a pestaña de `archivo` y damos clic en cerrar
![[Pasted image 20250313035048.png]]
Para crear un nuevo libro nuevamente vamos a la pestaña de `archivo` y damos clic en la parte de `libro en blanco`
![[Pasted image 20250313035210.png]]
Para cambiar el nombre del archivo a `PracticaCeldas.xlsx` vamos a guardar el archivo con ese mismo nombre y esa extensión, ahora sigue renombrar la hoja con el nombre de `PracticaCeldas` también.
![[Pasted image 20250313041056.png]]
Después nos pide asignar ciertos valores a ciertas celdas, por lo que colocamos esos valores en sus respectivas celdas
![[Pasted image 20250313041556.png]]
Y por ultimo se nos pide seleccionar todo el rango de las celdas desde `A1:D6` y ponerle a ese rango el nombre `PrimerRango`.
![[Pasted image 20250313041916.png]]
Para comprobar que se hizo bien vamos a darle clic sobre el rango `PrimerRango` y ver que este seleccione todo nuestro rango
![[Pasted image 20250313042031.png]]


## Sección 3: Manejo de datos en Excel

### Video 9: Manejo de datos en Excel

En esta parte del curso vamos a comenzar creando un nuevo libro y llamando `Manejo datos` y vamos a copiar la información que se nos proporciona en nuestra hoja de Excel

 >[!tip]
 >Como buenas practicas vamos a evitar espacios y acentos, para los espacios podremos sustituirlo por un `_` esto aplica para los nombres de las hojas, los nombres de los libros o tabien el nombre de la columnas

![[Pasted image 20250314033318.png]]

Una vez capturados pasamos al siguiente video

### Video 10: Autorellenado de datos en Excel

A partir de los datos capturados podemos ver que Excel nos puede autocompletar campos que tienen una secuencia, como por ejemplo en el campo de id tenemos una secuencia ya que van aumentando desde el numero 1 al 3 y si seleccionamos aunque sea los primero dos y arrastramos hacia abajo podemos observar como se nos va a autocompletar los datos
![[Pasted image 20250314034005.png]]
Ahora, si quisiéramos que en lugar de aumentar de 1 en 1 los registros podríamos poner que vaya de 100 en 100 y también nuevamente podría hacerse
![[Pasted image 20250314034120.png]]

> [!nota]
> Si por alguna razon no se visualizaran certos datos y en lugar de ellos nos aparecieran `###` significa que la celda no tiene el suficiete espacio para mostrar el dato completo por lo que abria que darle mas espacio a esa celda o columna en general
> 
![[Pasted image 20250314034824.png]]

Otros datos que podria Excel consderar como una secuencia y ayudarnos a repetirlo serian los meses y los dias, como se puede ver en la siguiente imagen
![[Pasted image 20250314035120.png]]
y a la hora de seleccionar algunos y bajar a mas celdas se autocompletan
![[Pasted image 20250314035205.png]]
Incluso podemos observar que para la parte de la secuencia de los dia llegando al dia domingo, comienza a repetirse nuevamente desde el lunes, lo mismo aplicaría para los meses, aunque también sirve para agregar un mismo dato a mas celdas como se mostrara a continuación
![[Pasted image 20250314035543.png]]
y podemos observar que se puede realizar esto también de manera horizontal

### Video 11: Mostrar u ocultar celdas

En esta seccion veremos la forma pra ocultar informacion que no queremos mostrar pero que quiza nos podra servir en el futuro y por lo tanto no la queremos eliminar completamente del archivo
![[Pasted image 20250314035850.png]]
En este caso vamos a ocultar la información de ejemplo del auto rellenado, para ello debeos seleccionar todas las columnas que queremos ocultar en este caso y dar clic derecho para dar clic en la opción de ocultar
![[Pasted image 20250314040126.png]]
De esta manera podemos ver que se ocultaron esas columnas, ya que no aparece su letra correspondiente a su columna
![[Pasted image 20250314040204.png]]
Si posteriormente quisiéramos mostrar nuevamente esas columnas, simplemente seleccionamos las columnas de a sus extremos y damos clic derecho para darle en la opción de mostrar
![[Pasted image 20250314040555.png]]
y con esto esa información se mostraría nuevamente
![[Pasted image 20250314040626.png]]
esta misma acción se puede aplicar a los renglones, después procedemos a borrar ahora si esos dato extras que teníamos

### Video 12: Formato de diseño de celdas en Excel

En esta lección se va a ver el tema del formato, se nos explica que una forma rápida de darle estilo y formato a nuestros datos, pero para ello nuestra información debe tener el formato de tabla, ya que de momento nuestros datos están en crudo, para ello nos vamos a la parte de inicio y vamos a la opción de estilos y damos clic sobre la opción de dar formato como tabla
![[Pasted image 20250314041640.png]]
Luego de dar clic veremos que nos salen distintos formatos para poder aplicar a la tabla, pudiendo seleccionar cualquier opción
![[Pasted image 20250314041831.png]]

Después de seleccionar una opción, nos va a salir una ventana en donde vamos a poder seleccionar los datos de la tabla que queremos agregar al formato de tabla (salen automáticamente pero se pueden seleccionar manualmente dando clic en el icono de la flechita hacia arriba)
![[Pasted image 20250314042117.png]]
para seleccionar manualmente borramos la información que aparece subrayada y damos clic en la flechita hacia arriba, después seleccionamos todas las celdas que queremos en la tabla y damos `ENTER` 
![[Pasted image 20250314042326.png]]
Ademas seleccionamos la opción de que la tabla va a tener cabecera ya que por eso la primer celda de cada columna tiene un nombre y damos en aceptar
![[Pasted image 20250314042654.png]]
Una vez dando en aceptar podemos observar que ya se le ha aplicado el diseño de la tabla a nuestros datos
![[Pasted image 20250314042907.png]]
y podemos autocompletar mas id´s y tendrá el mismo formato de la tabla
![[Pasted image 20250314042956.png]]
Ahora en dado caso de que quisiéramos agregar mas celdas a la tabla podremos expandir la misma arrastrando desde la esquina inferior derecha a mas campos
![[Pasted image 20250314043257.png]]
y extenderlo en una sola dirección, en este caso a la derecha
![[Pasted image 20250314043340.png]]
obteniendo como resultado, mas columnas con el mismo formato de la tabla principal
![[Pasted image 20250314043358.png]]

### Video 13: Aplicando formatos a celdas de manera manual

