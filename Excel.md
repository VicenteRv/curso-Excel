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

> [!note]
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

Comenzamos con la parte donde se nos explica que podemos utilizar lo anterior para darle el formato a los datos, pero podemos quitar el tratamiento de la tabla pero manteniendo el formato, para ello vamos a seleccionar nuestra tabla, damos clicl derecha sobre esta, seleccionamos la opcion de tabla y damos en la opcion que sale en convertir en rango
![[Pasted image 20250315202909.png]]
y nos pregunta si queremos convertir esa tabla en un rango normal a lo que indicamos que si
![[Pasted image 20250315202930.png]]
esto es una forma rapida de agregar formato a nuestras columnas y celdas, pero ahora vamos a tratar de hacerlo de manera manual, para ellos vamos a copiar y pegar la información que ya tenemos en la otra tabla creada y podemos hacer clic derecho y seleccionar la opción de pegar solo los valores para que no venga con el mismo formato de la tabla de abajo
![[Pasted image 20250315203545.png]]
o bien una vez seleccionada la parte a copiar con `ctrl + c` vamos a inicio y damos clic en la parte de pegar donde nos saldrán varios tipos y seleccionamos la primera opción de `pegar valores` 
![[Pasted image 20250315204046.png]]
Una vez hecho esto vamos a seleccionar todos los títulos de las columnas (id, nombre, apellido, salario...) y nos vamos a la parte de inicio y luego a estilos seleccionando la opción de `estilo de celda`, donde observamos que hay muchos estilos para aplicar.
![[Pasted image 20250315204834.png]]
Elegimos el azul de `Énfasis1` y agregamos el estilo de negritas y tenemos algo como lo siguiente
![[Pasted image 20250315205158.png]]
ahora seleccionamos toda la segunda fila y volvemos a aplicar un nuevo estilo de celdas para que se parezca a nuestra primera tabla, dejamos una celda sin estilo y nos saltamos a la siguiente hasta obtener algo así
![[Pasted image 20250315205416.png]]
Sin embargo podemos notar que es mucho trabajo, sobre todo si tenemos miles de datos, lo mismo aplicando los bordes y dándoles color y tenemos un resultado mas rápido aplicando el formato de tabla que editándolo nosotros mismos

## Video 14: Aplicando Formatos de moneda y fecha

En esta lección vamos a ver varios formatos que podemos aprovechar ya que observamos cuando cambiamos de la tabla a los datos con el puro valor la fecha se modifico y perdimos el formato de la fecha 
![[Pasted image 20250315210301.png]]
para ellos seleccionamos todas las celda de fecha y vamos a la parte de inicio>numero y seleccionamos en general para desplegar las opciones y seleccionar fecha
![[Pasted image 20250315210449.png]]
Lo mismo para el formato de salario, le aplicamos el formato de moneda y quedaría como se muestra a continuación
![[Pasted image 20250315210742.png]]
si por alguna razón estuviéramos manejando otro tipo de moneda, podemos ir a inicio>numero y seleccionar el pequeño recuadro en su esquina inferior derecha
![[Pasted image 20250315210935.png]]
al dar clic, se nos desplegara un menú en donde podremos cambiar el símbolo de la moneda que queremos utilizar o su prefijo por ejemplo de moneda mexicana `MXN`
![[Pasted image 20250315211122.png]]
y con esto seleccionamos el simbolo de moneda o prefijo y damos e aceptar y veremos los cambios
![[Pasted image 20250315211519.png]]
## Video 15: Guardando estilos personalizados

En esta clase vamos a aprender a crear nuestros propios estilos, para ello comenzamos copiando y pegando sin el formato la tabla que nos quedo anteriormente
![[Pasted image 20250315211824.png]]
Luego de esto vamos a aplicar un estilo de nuestro agrado a la celda de id o cualquier celda con titulo de preferencia, agregando un tipo de letra, tamaño, bordes, en negritas, color de la letra, color de relleno ... finalmente a mi me quedo asi
![[Pasted image 20250315212124.png]]
Después vamos a la parte de inicio>estilos>estilos de celda y seleccionamos hasta abajo de las opciones la que dice nuevo estilo de celda
![[Pasted image 20250315212249.png]]
De ahí nos saldrá una ventana donde saldrán cada una de las caracteristicas que le aplicamos a nuestro estilo
![[Pasted image 20250315212354.png]]
le ponemos un nombre y en el botón de formato saldrá otra ventana que contendrá toda la información que se ha aplicado y damos clic en aceptar.
Ahora para aplicar nuestro estilo, seleccionamos las celdas, y vamos a inicio>estilos>estilo de celda y lo encontraremos en la parte de personalizado damos clic sobre el y se aplicara a nuestras celdas seleccionadas
![[Pasted image 20250315212816.png]]
Para editar un estilo volvemos a ir a inicio>estilos>estilos de celda y sobre nuestro estilo creado damos clic derecho y nos saldrán opciones y seleccionaremos la de modificar
![[Pasted image 20250315213149.png]]
Se nos abrirá la ventana con las características de nuestro estilo, nos vamos a formato y cambiamos lo que deseemos
![[Pasted image 20250315213301.png]]

> [!Note]
> Lo mismo se puede hacer con otros estilos ya creados, los podemos editar

## Video 16: Tarea/ejercicio 

Para esta clase se nos va a dejar hacer el siguiente ejercicio
![[Pasted image 20250315213859.png]]
y que luzca de esta manera
![[Pasted image 20250315213959.png]]
Así que vamos a comenzar cerrando todo y creando una nueva tabla y dándole un nombre al nuevo libro, después de esto vamos a copiar los datos que nos dan hasta febrero y la parte de marzo tiene que ser de manera autocompletada, una vez hecho eso vamos a darle formato de contabilidad a los valores de ventas y gastos y de fecha corta al mes, ya con esto ahora solo vamos a inicio>estilos>estilos de celda y damos un color parecido o lo podemos poner desde inicio>fuente>color de relleno y quedaría así
![[Pasted image 20250315235456.png]]

## Sección 4: manejo de celdas, formulas y funciones

### Video 18: Manejo de formulas

Vamos a retomar el archivo de la sección anterior, donde tenemos los campos del mes, ventas y gastos, y le vamos a agregar una nueva columna llamada ganancias, y en sus celdas vamos a poner la formula de las diferencias entre las ventas y los gastos, para comenzar a escribir una formula lo primero que debemos de hacer es escribir el símbolo de `=` y hacer las operaciones entre celdas que ocupemos en este caso es la resta de las celdas
![[Pasted image 20250317004115.png]]
por lo que el resultado nos da $50 y para no tener que escribir esa formula en cada celda de esa columna podemos arrastrar esta de la celda que ya la tiene hasta la que necesitamos dando clic y desplazando del recuadro que aparece en la parte inferior derecha de la celda
![[Pasted image 20250317004407.png]]
ahora también podemos aplicar esto tanto de manera horizontal como vertical, ahora calcularemos el total de ventas y el total de gastos sumando todas las celdas, ponemos el simbolo de igual y sumamos 1 a 1 las celdas
![[Pasted image 20250317005129.png]]
una vez hecho esto se sumaran las celdas y después podemos desplazar esa celda a la derecha para que calcule la parte de gastos
![[Pasted image 20250317005236.png]]
posteriormente le damos un estilo a la tabla y nos queda como se muestra a continuación
![[Pasted image 20250317005416.png]]

### Video 19: Manejo de funciones

Seguiremos trabajando con el archivo anterior pero ahora con la diferencia de que usaremos una [[función]] para realizar lo mismo, ya que si tuviéramos miles de datos seria muy tardado seleccionar dato por dato, para ello primero vamos a seleccionar la celda donde vamos a poner nuestra formula y vamos a la parte de formulas>insertar función 
![[Pasted image 20250317011108.png]]
y se nos va a desplegar una ventana en donde podremos buscar las formulas que necesitemos, en este caso la función de suma damos en ir y nos aparecerán diferentes formas de utilizar la suma
![[Pasted image 20250317011310.png]]
de igual manera si quisiéramos saber mas de como manipular esta función podemos ir a la documentación dando clic en la parte de `Ayuda sobre esta función` que se encuentra en la parte inferior izquierda de la ventana
![[Pasted image 20250317011452.png]]
Después de dar en aceptar nos abrirá una nueva ventana donde podremos agregar las celdas o rangos a sumar, y como se puede ver igual nos da los valores que contiene esa celda antes de sumar todo, damos en aceptar
![[Pasted image 20250317011927.png]]
> [!danger]
> El rango en la foto esta mal, ya que solo era hasta la celda B4 y no hasta la B5

Continuando con la función podemos ver que nos da el mismo resultado, y al pasarle la misma formula a la celda de gastos y ganancias
![[Pasted image 20250317013456.png]]

> [!tip]
> Podemos hacer lo mismo si solo seleccionamos la celda y escribimos `=SUMA()` y seleccionamos la celda B2, presionando la tecla de `shift` y seleccionamos hasta la celda B4 y presionamos enter
> ![[Pasted image 20250317013735.png]]

### Video 20: Selección de rangos

En esta lección veremos que cuando seleccionamos algún rango, Excel automáticamente nos arroja información de este rango que hemos seleccionado, por ejemplo si seleccionamos el siguiente rango
![[Pasted image 20250317014219.png]]
en la parte inferior, bajo la barra de desplazamiento horizontal podremos encontrar dicha información 
![[Pasted image 20250317014333.png]]
que es el promedio, cuantas celdas con valores seleccionamos y la suma de todas ellas, pero podemos agregar mas datos nosotros dando clic derecho sobre esta barra y nos saldrán mas opciones como se muestra a continuación
![[Pasted image 20250317014707.png]]
donde podremos habilitar o deshabilitar algunas operaciones que se nos da por default cuando seleccionamos un rango, otra cosa extra sobre los rango es que podemos seleccionar un rango o mas aunque estén separados por una celda, seleccionando primero un rango y después presionando la tecla `ctrl` seleccionar otro rango, además de que si usamos la tecla de `tab` podemos desplazarnos entre las celdas de los rangos seleccionados 
![[Pasted image 20250317015215.png]]

### Video 21: Precedencia de operadores

Para comprender bien este tema debemos de saber que es la [[precedencia]] 

### Video 22: Mas sobre manejo de celdas

Para comenzar vamos a copiar y pegar los datos de la tabla que venimos manejando para simular 2 tiendas diferentes
![[Pasted image 20250318024608.png]]
una vez hecho esto vamos a agregar una nueva fila sobre el nombre de la parte que dice mes, ventas, gastos y ganancias, para poner un titulo a estas, para ello seleccionamos el renglón completo y damos clic derecho para abrir las opciones y seleccionamos en insertar
![[Pasted image 20250318024953.png]]
Con esto vamos a agregar un nuevo renglón sobre ambas tablas
![[Pasted image 20250318025154.png]]
si quisiéramos que solo se agregue sobre una tabla en especial, seleccionamos el renglón de los títulos de la primera tabla y damos clic derecho para desplegar el menú
![[Pasted image 20250318025216.png]]
damos clic en insertar, con esto se nos abrirá una nueva ventana con varias opciones sobre en donde insertar una nueva columna o fila
![[Pasted image 20250318025421.png]]
vamos a seleccionar la opción de `Desplazar las celdas hacia abajo` y se nos va a agregar una fila arriba de la primer tabla pero solo de esa misma
![[Pasted image 20250318030144.png]]

>[!note]
>Si seleccionamos la opción de `Desplazar celdas hacia la derecha` obtenemos lo siguiete
>![[Pasted image 20250318025854.png]]
>Si seleccionamos la opción de `Toda la fila` obtenemos lo siguiente
>![[Pasted image 20250318030008.png]]
>Si seleccionamos la opción de `Toda la columna` obtenemos lo siguiente
>![[Pasted image 20250318030106.png]]

Para eliminar pasa los mismo que con `intertar`, seleccionamos las celdas a eliminar y la acción
![[Pasted image 20250318030321.png]]
Ahora le damos un nombre a cada tabla en la fila que agregamos y para que se vea mejor seleccionamos todas las celdas de encima la tabla y vamos a inicio>alineación>combinar y centrar aunque hay mas opciones, elegimos la de combinar y centrar.
![[Pasted image 20250318030750.png]]
Con esto podemos observar que le titulo de la primer tabla mejoro ya que todas las celdas seleccionadas se combinaron y se centro el titulo, aplicamos lo mismo para la segunda tabla y le damos un estilo de celda
![[Pasted image 20250318031117.png]]
Ahora vamos a agregar una nueva fila para la tabla 1 donde agregaremos el mes de abril automáticamente sin agregar esta a la segunda fila, y como se agrego una nueva fila hay que agregar esta nueva fila a las formulas que ya están.
![[Pasted image 20250318032231.png]]

### Video 23: Manejar varias hojas

Con las tablas del video pasado ahora vamos a tener una hoja para cada sucursal, para ellos vamos a cambiar el nombre de la hoja actual y agregar una nueva hoja con el nombre de `sucursal2` 
![[Pasted image 20250318032524.png]]
una vez hecho esto vamos a pasar la información de la sucursal2 a la hoja 2, cortándola de la primer hoja y pegándola en la segunda utilizando las teclas de `ctrl + x` y `ctrl + v` para pegar esa información
![[Pasted image 20250318032932.png]]
ahora con esto ya tenemos dividida nuestra información en dos hojas diferentes 

### Video 24: Manejo de celdas en distintas hojas

Ahora ya con nuestras dos tablas separadas en una hojas vamos a crear una nueva hoja con el total de los gastos, ventas y ganancias de cada una de las sucursales. Para ello nos creamos una nueva hoja que se llamara `totales` 
![[Pasted image 20250318033619.png]]

>[!note]
>Para cambiar de hojas en excel podemos usar las teclas de `ctrl + RePág` o `ctrl + AvPág` para poder cambiar de hoja mas rapido
>En algunas podria tener que agregarse la tecla `fn` siendo ahora `ctrl + fn + RePág` o `ctrl + fn + AvPág`

Después de crear la nueva hoja vamos a agregarle la siguiente información
![[Pasted image 20250318034008.png]]
y ahora para obtener la información de una hoja diferente vamos s seleccionar la celda donde vamos a poner el valor escribimos el símbolo de `=` y seleccionamos la hoja de donde queremos tomar el dato y después la celda, podemos observar como se selecciona esto con el valor de la hoja y celda separados por un símbolo de admiración
![[Pasted image 20250318034304.png]]
y al presionar `ENTER` podemos ver que el dato en la hoja de `totales` cambio al valor que tiene la sucursal 1 en las ventas
![[Pasted image 20250318034541.png]]
hacemos esto para las demás celdas, a este tipo de datos se les conoce como [[consolidado de datos]], además le damos algún estilo al gusto y agregamos un nuevo campo llamado total
![[Pasted image 20250318035639.png]]
Para automatizar la parte de la suma seleccionamos la celda donde ira el valor de la suma, después de esto vamos a formulas>biblioteca de funciones>autosuma y damos clic sobre este
![[Pasted image 20250318035931.png]]
Podemos ver que nos seleccionan todos los datos que están sobre esta celda y los pone dentro de la función de suma, hacemos estos para las otras dos celdas o podemos arrastrar la formula
![[Pasted image 20250318040235.png]]

### Video 25: Referencias relativas y absolutas

Vamos a comenzar con la parte de [[referencias relativas-absolutas]],comenzamos copiando y pegando el valor del total de ventas de cualquier hoja y pegando el valor en otra parte, pero nos daremos cuenta que que no obtenemos valor alguno ya que esta referenciado como un valor relativo
![[Pasted image 20250318042310.png]]
ahora si seleccionamos la celda donde pegamos el valor podemos ver las celdas que esta tomando para realizar la formula de la celda que copiamos
![[Pasted image 20250318042358.png]]
si queremos realizar esta suma pero con los valores de cierta columna en este caso el del total de ventas de las sucursales, vamos a editar la formula y vamos a seleccionar el rango de las filas y columnas que deseamos pero con un símbolo de `$` antes de cada letra y numero `$B$2` de esta manera estamos diciendo que siempre tome esas mismas posiciones ósea que los convertimos en una referencia absoluta
![[Pasted image 20250318042733.png]]
al dar enter podemos ver que obtenemos el mismo valor que el que aparece en el total de ventas de la tabla, y ahora si copiamos y pegamos esta celda en otro lado obtenemos el mismo valor ya que esta referenciado de manera absoluta
![[Pasted image 20250318043020.png]]

### Video 26: Comentarios

Para agregar un comentario a una celda, primero seleccionamos la celda en donde queremos agregar este y vamos a revisar>comentarios>nuevo comentario
![[Pasted image 20250318043604.png]]
y se nos abrirá una ventana en donde podremos colocar un comentario 
![[Pasted image 20250318043659.png]]
Donde igual nos indica quien esta haciendo el comentario, presionamos enter para terminar el comentario, de igual manera si en algún momento necesitamos imprimir estos mensajes del archivo vamos a archivo>imprimir>configurar pagina y aquí seleccionamos la parte de comentarios y notas 
![[Pasted image 20250318044158.png]]
donde se nos despliegan esas opciones, si seleccionamos la opción de `como se muestra en la hoja` no nos aparece nada pero si seleccionamos la opcion de `Al final de la hoja` tendremos lo siguiente
![[Pasted image 20250318044637.png]]

### Video 27,28,29: Atajos

Atajos basicos
- Guardar archivo: `ctrl + g`  
- Abrir archivo: `ctrl + a`
- Crear un nuevo libro: `ctrl + u`
- Cerrar archivo: `ctrl + r`
- Imprimir: `ctrl + p`
- Cerrar Excel: `alt + f4`
- Seleccionar una columna: `ctrl + espacio`
- Seleccionar una fila: `shift + espacio`
- Agregar una celda: `ctrl + +`
- Regresar una acción: `ctrl + y` (funciona como si fuera un `ctrl + shitf + z`)

Atajos medios
- Agregar una columna: `ctrl + espacio` luego `ctrl + +` (seleccionar primero la columna, problemas cuando tenemos una tabla con rangos)
- Eliminar una columna: `ctrl + espacio` luego `ctrl + -` (seleccionar primero la columna, problemas cuando tenemos una tabla con rangos)
- Agregar una fila: `shift + espacio` luego `ctrl + +` 
- Eliminar una fila: `shift + espacio` luego `ctrl + -` 
- Agregar una columna/fila: `ctrl + +`
- Eliminar una columna/fila: `ctrl + -` 
- Cambiar de hoja: `ctrl + AvPág`
- Regresar a la hoja anterior: `ctrl + RePág`
- Seleccionar un rango: `ctrl + shift + flecha(arriba-abajo-derecha-izquierda)`
- Seleccionar todo un rango: `ctrl + e`
- Seleccionar toda la hoja: `ctrl + e` luego `ctrl + e`
- Ir al limite derecho: `ctrl + flecha(arriba-abajo-derecha-izquierda)`
- Zoom: `ctrl + rueda del raton` o `ctrl + ambos dedos en el touchpad deslizando arriba/abajo`

Atajos avanzados
- Convertir una referencia en absoluta: `F4` 
> [!Example]
> Para que esto funcione debemos de dar clic sobre la formula que queremos hacer absoluta
> ![[Pasted image 20250319022232.png]]
- Cambiar de libro(si tenemos mas abiertos): `ctrl + F6`
- Abrir la caja de formato: `ctrl + 1`
- Ocultar una columna: `ctrl + 0`

Formato de textos
- Negritas: `ctrl + n`
- Cursiva: `ctrl + k`
- Subrayado: `ctrl + s`

### Video 30: Ejercicio control de ingresos-egresos

En este video se nos deja un ejercicio y debemos de replicarlo lo mayor posible con el siguiente diseño y archivos, todo con la fuente de `Dubai`, para la primer hoja llamada `Primer año` tenemos al siguiente estilo y datos
![[Pasted image 20250319024127.png]]
Para la siguiente hoja llamada `Reporte mensual primer año` tenemos:
![[Pasted image 20250319024355.png]]
Para la siguiente hoja que es lo mismo que la primera pero del segundo año tenemos:
![[Pasted image 20250319024651.png]]
![[Pasted image 20250319024706.png]]
Y finalmente tenemos la ultima hoja llamada `Totales` 
![[Pasted image 20250319024725.png]]

Con esta información debemos de recrear todo el documento lo mas parecido alas imágenes, asi que comenzamos
Para comenzar nos vamos a crear un nuevo libro, si tenemos uno abierto lo guardamos con `ctrl + g` y después para cerrarlo con `ctrl + r`, y para crear un nuevo libro usamos `ctrl + u` ya hecho esto escribimos el titulo de la tabla y centramos y combinamos las celdas como se muestra
![[Pasted image 20250319025412.png]]
después seleccionamos toda el libro con `ctrl + e` para aplicar la misma fuente a toda la hoja(Dubái), después para seleccionar el color, seleccionamos la celda a darle color y usamos el atajo de `ctrl + 1`, se nos abrirá una ventana y vamos a la parte de Relleno y a Más colores...
![[Pasted image 20250319025858.png]]
Una ves en mas colores vamos a personalizado y agregamos los datos RGB
![[Pasted image 20250319025954.png]]
Ya que sabemos como agregar un color con rgb ahora vamos a seguir dando el formato al documento como se ve
![[Pasted image 20250320022045.png]]
la parte de ingresos se realizo con a función suma de las celdas de monto de la tabla Ingresos
![[Pasted image 20250321005503.png]]
al igual que la parte de egresos que es la suma de los datos de la tabla de egresos
![[Pasted image 20250321005540.png]]
y a todos los datos de numero se les dio el tipo de formato de `Contabilidad`
![[Pasted image 20250321005653.png]]
ya con esto podemos pasar a la segunda hoja que llamaremos `reporte mensual primer año`, y pondremos el siguiente formato, además usaremos la función suma pero para sumar dos valores que se encuentran en la otra hoja como se puede ver, y así mismo sumar los valores de las columnas y filas
![[Pasted image 20250321010216.png]]
lo mismo para las otras dos tablas, solo que debemos de actualizar la información que viene par el segundo año y ademas en el reporte del segundo año modificar el valor de la suma de ingresos y egeresos ya que hacen referencia al primer año porque copiamos y pegamos, una vez hecho esto tenemos lo siguiente
![[Pasted image 20250321011950.png]]
Segundo año
![[Pasted image 20250321012012.png]]
reporte segundo año 
comenzamos con la parte de totales, dándole el formato asi
![[Pasted image 20250321012430.png]]
Ahora que ya tenemos esto podemos usar la función suma para sumar los valores de las dos hojas de cada año para los ingresos, después de seleccionar la celda del primer año escribimos el símbolo de `+` y vamos a la segunda celda y la seleccionamos, una vez seleccionado damos `ENTER`
![[Pasted image 20250321012643.png]]
y podremos ver el resultado y la formula, lo mismo aplica para el de egresos y para la parte de saldo total simplemente restamos ambas celdas de totales, obteniendo algo asi
![[Pasted image 20250321013144.png]]

## Sección 4

### Video 36: Inmovilizar paneles

Para comenzar vamos a descargar un archivo de Excel que ya contiene documentos, este lo adjuntare en la carpeta de `Material` y lleva el nombre de `04-01-ListaDatos-inicial-CUE` 
La problemática aquí es que a medida de que vamos deslizando hacia abajo perdemos el nombre de las columnas, para ello Excel cuenta con la opción de inmobilizar que se encuentra en vista>ventana>inmovilizar y nos dice su función
![[Pasted image 20250321014651.png]]
asi que damos clic ahi, seleccionamos una celda despes de donde queremos que se nos inmovilicen los datos, en este caso sera la celda `B2` ya que esta despues de la fila que queremos mantener y la columna de id que queremos tambien inmovilizar y damos en la primer opcion que dice `inmovilizar paneles`
![[Pasted image 20250321014747.png]]
![[Pasted image 20250321015321.png]]
con esto podemos desplazarnos hacia abajo y seguir mirando el nombre de las columnas
![[Pasted image 20250321015404.png]]lo mismo sucede cuando nos desplazamos hacia la derecha
![[Pasted image 20250321015447.png]]
Para volver a movilizar los paneles seleccionamos la misma opcion
![[Pasted image 20250321015614.png]]
y ahora vemos que nos aparece la opción de `movilizar paneles`
> [!Note]
> Hay que tener cuidado con que celda esta seleccionada a la hora de realizar esto ya que a partir de esta es de donde se inmovilizan las demás celdas

### Video 37: Ordenamiento de celdas

Para esto seguiremos trabajando con el mismo archivo, para comenzar podremos notar en los datos que no estan ordenados ya sea en roden ascendete o descendente, por letra o fechas etc.
Para ello tenemos una herramienta en la parte de inicio>edicion>ordenar y filtrar
![[Pasted image 20250321020157.png]]
Y si damos clic podemos observar la opciones
![[Pasted image 20250321020250.png]]
Por ejemplo si seleccioamos alguna celda de la columna de id y damos en ordenar de menor a mayor
![[Pasted image 20250321020424.png]]
podremos ver que se ordenan los numero en forma ascendente
![[Pasted image 20250321020452.png]]
también tenemos otra opción en la sección de datos>ordenar y filtrar
![[Pasted image 20250321020606.png]]
también podemos ordenar por mas elementos seleccionando en ordenar y nos saldrá una ventana
![[Pasted image 20250321020734.png]]
donde podremos elegir por que columna ordenar
![[Pasted image 20250321020929.png]]
en este caso seleccionamos por nombre despues elegimos el tipo de ordenamiento que queremos seguir
![[Pasted image 20250321021026.png]]
donde nos salen esas opciones pero de momento vamos a trabajar con el valor de las celdas y por ultimo viene el criterio de ordenamiento
![[Pasted image 20250321021139.png]]
elegimos la primera opcion y damos en aceptar
![[Pasted image 20250321021331.png]]
podemos observar que se ordeno de la A-Z y ahora podemos ordenar también por apellido, por lo que seleccionamos nuevamente el botón de ordenar y ahora vamos a dar clic en `agregar nivel`
![[Pasted image 20250321021505.png]]
seleccionamos ahora el campo de apellido y dejamos los mismos valores
![[Pasted image 20250321021557.png]]
y damos en aceptar, obteniendo el nombre y apellido ordenados de manera alfabética

### Video 38: Aplicar filtro a una lista

Utilizando el mismo archivo vamos a ver como poder filtrar elementos dentro de la lista, para ello vamos a ir a datos>ordenar y filtrar>filtro
![[Pasted image 20250321022241.png]]
Damos clicl sobre este y nos apareceran unos iconos en los nombres de la columnas, presionando estos iconos podemos observar que tenemos las opciones de ordenamiento 
![[Pasted image 20250321022520.png]]
Además de que en la parte de abajo podemos filtrar por apellidos, un ejemplo podemos filtrar la columna de nombres por solo algunos como se muestra
![[Pasted image 20250321022722.png]]
y al dar aceptar podremos ver que solo nos salen los nombres que queríamos
![[Pasted image 20250321022823.png]]
además para borrar un filtro o varios podemos dar clic en borrar
![[Pasted image 20250321023100.png]]
que se encuentra al lado del icono de filtro
Podemos seguir jugando con estas opciones y descubrir sobre filtrar otros datos

### Video 39: Quitar elementos duplicados de una lista

Ahora vamos a ver como eliminar duplicados de una lista ya que en la lista existen varios elementos duplicados, asi que lo primero que debemos de hacer es ordenar los datos y si tuvieramos una columna con datos unicos seria mas sencillo eliminar datos duplicados, por ejemplo la columna de id, para ello vamos a ordenar sus elementos de manera ascendente
![[Pasted image 20250321024406.png]]
y podemos observar que tenemos registros duplicados, sin embargo no es o mas opctimo cuando tenemos miles de registros para ello exite una manera mas simple de eliminar elementos duplicados, para ello vamos a la sección de datos>herramientas de datos>quitar duplicados
![[Pasted image 20250321024716.png]]
y cuando damos clic nos sale una ventana
![[Pasted image 20250321024839.png]]
donde nos pregunta cual es la columna que queremos seleccionar para buscar los elementos duplicados, quitamos todos los elementos y solo seleccionamos el id y dejamos seleccionada la casilla que dice `Mis datos tienen encabezados` para que no tome en cuenta el primer dato que encuentre y lo elimine también, damos clic en acpetar y nos aparece que ha encontrado 8 valores duplicados 
![[Pasted image 20250321025128.png]]
y podemos observar que el segundo elemento de 4 ha sido eliminado pero sin borrar el previo a este. Ahora para otra prueba damos `ctrl + z` y vamos a seleccionar el nombre tambien el nombre, agregamos el nombre de JUAN al segundo que ya existia
![[Pasted image 20250321025357.png]]
y ahora seleccionamos las columnas de id y nombre
![[Pasted image 20250321025430.png]]
damos clic y nos avisa del siguiente mensaje
![[Pasted image 20250321025450.png]]
y podemos observar que no elimino las celdas con el id 4 ya que el nombre no se repitió también
![[Pasted image 20250321025557.png]]
por eso debemos de tener en consideración que los datos que seleccionemos deben de ser completamente iguales para eliminarlos

### Video 40: Filtro avanzados

Ya sabemos como aplicar un filtro a nuestra listas, sin embargo, la manera en que los aplicamos son de manera individual en cada columna, pero también se pueden aplicar filtros mas complejos que se localizan en datos>ordenar y filtrar>avanzadas
![[Pasted image 20250321030045.png]]
y al dar clic nos despliega sus opciones
![[Pasted image 20250321030247.png]]
Donde tenemos el rango de nuestra lista pero tambien debemos de tener un rango de criterios, asi que vamos a crearnos uno para poder aplicar el siguiente, en este caso queremos aplicar un filtro a la columna apellido  
![[Pasted image 20250321030555.png]]
agregamos una nueva columna y le damos el nombre de la columna y el valor que queremos filtrar, ahora damos clic en la parte de avanzadas nuevamente y seleccionamos en el rango de criterios, la tabla que agregamos de Apellido
![[Pasted image 20250321030716.png]]
al dar clic en aceptar se aplican los cambios para el filtro por apellido GONZALEZ
![[Pasted image 20250321030929.png]]
Ademas podemos agregar mas filtro, como se muestra
![[Pasted image 20250321031152.png]]
> [!Note]
> Una manera rápida de copiar el valor de una celda es presionar `ctrl` y seleccionar la celda y apuntar hacia su parte inferior hasta que salga el icono de una flechita y podemos arrastrar esa información hasta donde queramos

nuevamente seleccionamos la opcion de avanzadas y seleccionamos el rango de los criterios y damos aceptar
![[Pasted image 20250321031420.png]]
y podemos apreciar que si esta filtrando por los valores que se le dio
![[Pasted image 20250321031513.png]]
también además de por apellido, podemos agregar la columna de pesos
![[Pasted image 20250321031738.png]]
Aplicando para Gonzales el peso de 61 y así sucesivamente, aplicamos el filtro avanzadas y damos estos rangos nuevamente
![[Pasted image 20250321031853.png]]
al dar aceptar nos mostrara los que cuenten con estos filtros
![[Pasted image 20250321031945.png]]
en este caso solo dos cumplieron los filtros 

## Sección 6

### Video 41: Tablas

Para esta sección vamos a trabajar con el archivo de nombre `05-01-Tabla-inicial-CUE` de la carpeta de `Material`, abrimos el archivo y podemos observar que es una lista de datos, pero ahora vamos a trabajar con el concepto de tablas y vamos a ver las [[diferencias entre una lista y una tabla]], pero para comenzar vamos a transformar una lista a una tabla seleccionando alguna celda dentro de esta y usamos el comando de `ctrl + t` para que excel nos genere la tabla y nos indica el rango de datos donde se encuentra la tabla
![[Pasted image 20250322033345.png]]
Podemos observar que esta utilizando referencia absolutas, y además nos pregunta si tenemos encabezados, otra manera de agregar una tabla es yendo a insertar>tablas>tabla 
![[Pasted image 20250322033945.png]]
Una vez seleccionado vemos que nos aparece una ventana con los mismo datos del rango de la tabla y pregunta si tenemos un renglón de encabezado, damos clic en aceptar y podemos visualizar que de manera automática se le aplicar un diseño a la tabla y se abre la sección de diseño
![[Pasted image 20250322034237.png]]
Una característica de una tabla es que los encabezados de la tabla tienen la propiedad como si los hubiéramos inmovilizado, además podemos notar que también podemos ordenar los datos y aplicar un filtro y por ultimo podemos cambiar el estilo de la tabla en la sección de  diseño>estilos de tabla>estilos rápidos
![[Pasted image 20250322034727.png]]
y asi podemos elegir de forma rapido el estilo de nuestra tabla
![[Pasted image 20250322034838.png]]
y de manera automática se aplica el diseño a la tabla

### Video 42: Segmentacion de datos de una tabla

Seleccionando cualquier celda de la tabla, se nos despliega la sección de diseño, y tenemos varias opciones
![[Pasted image 20250322035136.png]]
por ejemplo cambiar el nombre de la tabla o el tamaño
![[Pasted image 20250322035231.png]]
igual tenemos la opción de quitar duplicados (esta función ya la vimos unos videos atrás con el tema de listas), convertir en rango (en el caso de que ya no queramos usar los datos como tabla lo podemos convertir en un rango) 
![[Pasted image 20250322035549.png]]
y también tenemos la opción de `insertar segmentacion de datos`
![[Pasted image 20250322035656.png]]
Si damos clic en esta, podemos observar que nos aparecen las columnas que tenemos en la tabla y si seleccionamos alguna de estas columnas en este caso la columna de departamento 
![[Pasted image 20250322035846.png]]
podemos observar que nos muestra todas las opciones que tiene esa columna de departamento
![[Pasted image 20250322040016.png]]
y esta opción nos sirve para filtrar datos, por ejemplo si quereos filtrar por `SISTEMAS` damos clic sobre sistemas y se nos filtrara por este
![[Pasted image 20250322040207.png]]
podemos cambiar el filtro simplemente dando clic sobre otra opción
![[Pasted image 20250322040340.png]]
o elegir mas de 1 opción presionando `ctrl + clic` sobre la opción que queremos agregar al filtro
![[Pasted image 20250322040446.png]]
y podemos ver que se agrego el filtro de `FINANZAS` y `SISTEMAS`, además, podemos agregar varios segmentos en la misma hoja y podemos agregarle un formato a nuestros segmentos, seleccionando el segmento de departamento y vamos a la sección de `segmentación` y podemos ver que en segmentación>estilos de segmentación podemos seleccionar un nuevo estilo para nuestro segmento
![[Pasted image 20250322041032.png]]
Ahora vamos a agregar otro segmento yendo a diseño de la tabla>herramientas>insertar segmentación de datos y seleccionamos la nueva columna que queremos agregar (peso(KG))
![[Pasted image 20250322041323.png]]
damos en aceptar y ahora vemos que tenemos todas las opciones de peso
![[Pasted image 20250322041434.png]]
ahora podemos iniciar el filtrado de datos por departamento y peso como se ve acontinuación y los datos que nos arroja (seleccionamos Finanzas y Sistemas en el segmento de deartamento y en blanco en el segmento de Peso(KG))
![[Pasted image 20250322041704.png]]
Para eliminar un segmento simplemente damos clic derecho sobre este y damos en la opción de `Borrar filtro`
![[Pasted image 20250322042102.png]]
y dando clic podremos ver que ya no estamos filtrando por un segmento, pero si ya lo queremos borrar simplemente lo seleccionamos y damos en `supr` o con clic derecho y dar en `Quitar "peso(kg)"`
![[Pasted image 20250322042339.png]]
y podemos observar que ya se elimino.
También tenemos mas opciones para aplicar a la tabla en diseño de la tabla>opciones de estilo de tabla 
![[Pasted image 20250322042730.png]]
por ejemplo mostrar una fila de totales
![[Pasted image 20250322042847.png]]
que muestra una fila al final de la tabla con el numero total de registros (cambia si seleccionamos algún filtro de un segmento)
![[Pasted image 20250322043340.png]]

### Video 43: Buscar y reemplazar texto

Seguiremos trabajando con el mismo archivo, para ello comenzamos a buscar un texto pulsando las teclas de `ctrl + b`, y escribiendo la palara a buscar en nuestro caso `Finanzas` y damos clic en buscar todos
![[Pasted image 20250322044551.png]]
y podemos observar que nos muestra datos de donde se encuentra esa palabra
![[Pasted image 20250322044719.png]]
como el libro donde se encuentra ese texto, la hoja, el nombre de la celda y el valor.
Con esto podemos encontrar un texto dentro de la hoja de calculo, también podemos encontrar textos en diferentes hojas y libros, si damos clic en la parte de buscar siguiente podemos ver que en la tabla se mueve al siguiente resultados encontrado
![[Pasted image 20250322045127.png]]
Ahora vamos a ver el caso en el que quisiéramos reemplazar un texto, por ejemplo reemplazar recursos humanos por recursos_humanos, ahora vamos a la parte de reemplazar y no de buscar
![[Pasted image 20250322045340.png]]
ahora en la parte de buscar ingresamos la palabra a reemplazar y en la siguiente cajita agregamos el valor que queremos agregar por el anterior
![[Pasted image 20250322045503.png]]
y un poco mas abajo nos aparecen estas opciones
![[Pasted image 20250322045606.png]]
y damos en reemplazar todos, una vez hecho esto nos saldrá una notificación que nos dira cuantos datos fueron reemplazados
![[Pasted image 20250322045722.png]]
Cerramos las pestañas abiertas y podremos ver que fueron modificados esos campos con el nuevo valor
![[Pasted image 20250322045843.png]]
ahora si queremos ver la parte avanzada de reemplazar presionamos nuevamente `ctrl + b`, vamos a la opción de reemplazar y en Opciones>>>
![[Pasted image 20250322050027.png]]
y podremos ver las opciones mas avanzadas que se tiene para buscar o reemplazar información
![[Pasted image 20250322050210.png]]
Por ejemplo buscar información dentro de una hoja o libro, por filas o columnas, por formulas y marcar la opciones de coincidir mayúsculas y minúsculas

### Video 44: Validación de datos usando una lista

Lo que vamos a hacer en esta clase es validar las celdas de una lista para que solo se puedan ingresar ciertos datos, un ejemplo es que por error escribamos una palabra y se nos valla un numero de mas etc.
Para ello primero seleccionamos la celda, en este caso vamos a trabajar con la parte de los departamentos.
![[Pasted image 20250328145208.png]]
Después vamos a datos>Herramientas de datos>validación de datos
![[Pasted image 20250328145350.png]]
damos clic y nos sale una ventana en donde tenemos 3 opciones diferentes
![[Pasted image 20250328150102.png]]
seleccionamos la opción de `validación de datos` y nos sale una nueva
![[Pasted image 20250328150224.png]]
vemos que tenemos los criterios para realizar la validación, pero por default en Excel cualquier celda puede permitir cualquier valor y si queremos restringir el valor que un usuario puede asignarle a una celda podemos agregarle una restricción donde clic sobre el spinner debajo de permitir
![[Pasted image 20250328150522.png]]
Donde se nos muestran las restricciones que podemos aplicarle a una celda incluso una validación personalizada ahora vamos a agregar una validación de tipo lista
![[Pasted image 20250328150739.png]]
Dejamos seleccionadas la opciones que nos aparecen , además agregaos las opciones que el usuario puede seleccionar escribiéndolas en la parte de origen
![[Pasted image 20250328151120.png]]
damos clic en aceptar y podemos ver que la celda ya tiene una validación
![[Pasted image 20250328151209.png]]
presionamos el icono de la flechita hacia abajo 
![[Pasted image 20250328151244.png]]
y podemos observar que se despliegan las dos opciones que colocamos en la parte de origen, pero no podemos introducir un dato distinto a esos valores ya que si lo hacemos recibiremos esta alerta
![[Pasted image 20250328151414.png]]
ahora para aplicar esto a todos los demás campos, no podemos copiar y arrastrar la celda ya que pasa lo siguiente
![[Pasted image 20250328151710.png]]
todos nuestros campos obtienen el valor de finanzas, para esto seleccionamos las celdas faltantes con `ctrl + shit + flecha abajo` a partir de la siguiente celda que ya tiene las restricciones y vamos nuevamente a la parte de validación de datos, le damos el criterio de validación de lista y escribimos los valores validos de la lista
![[Pasted image 20250328152049.png]]
damos clic en aceptar y ahora podemos ver que no nos borro ningún dato y respeto los que ya teníamos
![[Pasted image 20250328152149.png]]
por ultimo vamos a tomar información de esa lista desde otra hoja, para ello nos creamos la nueva hoja llamada `DEPARTAMENTO`
> [!SUMMARY]
> Básicamente en lugar de escribir en origen las palabras, nos creamos un a nueva hoja en donde vamos a colocar todo los departamentos que hay para tomarlo de ahi en vez de estarlos escribiendo cada vez
 
![[Pasted image 20250328153053.png]]
Podemos agregar mas opciones, pero de momento solo vamos a tener estas, guardamos los cambios y regresamos a la hoja anterior, y ahora en vez de agregar directamente los valores, vamos a tomarlos de la nueva hoja, seleccionamos todas las celdas de esa columna, vamos a la parte de datos>herramientas de datos>validar datos
![[Pasted image 20250328153623.png]]
como de momento ya teníamos validaciones nos saldrá esa notificación y damos en aceptar para que se elimine la configuración actual, damos la restricción de lista
![[Pasted image 20250328153812.png]]
y ahora damos clic en el icono de la flechita y seleccionamos los campos que tenemos en la hoja de `DEPARTAMENTOS`
![[Pasted image 20250328153940.png]]
damos enter y podemos ver las celdas que seleccionamos y ya no los valores
![[Pasted image 20250328154025.png]]
igual en las pestañas de `Mensaje de entrada` y  `Mensaje de error` podemos personalizar los mensajes que se mandan al usuario, en caso de error en la validación a mandar un mensaje extra en el mensaje de entrada de validación de datos, de momento no lo vamos a ver a fondo y damos enter, para aplicar los cambios 
![[Pasted image 20250328154436.png]]
y ahora si seleccionamos la opción de las celdas para desplegar la lista podemos ver los valores que obtenemos de la hoja de  `DEPARTAMENTOS`
![[Pasted image 20250328154613.png]]

## Seccion 7

### Video 45: Impresión (encabezado y pie de pagina)

En esta lección vamos a usar un archivo que descargamos del curso con el nombre de `06-01-OpcionesImpresion-CUE-inicial.xlsx` que podemos encontrar en la parte de la carpeta de `Material`, para comenzar observamos unos iconos en la parte inferior derecha que son las vistas de impresión como se muestra en la siguiente imagen
![[Pasted image 20250410211057.png]]
Son los 3 iconos como cuadritos, si seleccionamos alguno diferente al ya seleccionado podemos ver que la vista cambia, por ejemplo al dar clic al siguiente icono la vista nos va a cambiar a la siguiente manera
![[Pasted image 20250410211218.png]]
y tenemos una visualización de como se va a ver nuestra impresión en hoja de Excel, y podemos ver que nos aparecen dos apartados que tienen la leyenda `agregar encabezado/agregar pie de pagina`, en esta lección nos vamos a centrar en configurar algunas de las opciones para la impresión de la hoja, así que vamos a ir a insertar>texto>Encabezado de pie de pagina
![[Pasted image 20250428155852.png]]
damos clic y veremos que se nos habilitan mas opciones para el encabezado y pie de pagina
![[Pasted image 20250428160257.png]]
ahora podemos ver que al querer escribir en el encabezado este se divide en 3 partes
![[Pasted image 20250428160453.png]]
y en cada una de estas secciones se puede agregar información, por ejemplo las que se muestran en Encabezado de pie de pagina>elementos de encabezado de pie de pagina
![[Pasted image 20250428160734.png]]
ahora en la división de en medio vamos a poner la opción de nombre del archivo y veremos que se agrega una variable 
![[Pasted image 20250428161032.png]]
pero si damos clic en otra parte veremos el nombre del archivo
![[Pasted image 20250428161117.png]]
ahora si vamos a la parte del pie de pagina tendremos las de mismas divisiones y le podemos seleccionar los mismo elementos que al encabezado, en este ejemplo vamos a agregar en la parte de en medio la parte de numero de pagina
![[Pasted image 20250428161451.png]]
pero si quisiéramos poner el numero de pagina del total de las paginas escribimos `de` y seleccionamos la opción del elemento de numero de paginas como se muestra a continuación
![[Pasted image 20250428161816.png]]
y nos mostraría el siguiente resultado
![[Pasted image 20250428161859.png]]
tambien podemos ver las opciones preconfiguradas para el encabezado y pie de pagina si vamos a encabezado y pie de pagina
![[Pasted image 20250428162347.png]]
y damos clic sobre encabezado podemos ver algunas opciones
![[Pasted image 20250428162425.png]]
lo mismo para el pie de pagina, por ultimo tenemos que si queremos que la primer pagina se configure de manera distinta a la segunda o demas paginas vamos a ir a
![[Pasted image 20250428163229.png]]
y dar clic en cualquiera de esas opciones

### Video 46: Ajustar elementos de una hoja

En esta lección vamos a aprender a meter toda nuestra información en una sola hoja para cuando se imprime para no tener que imprimir 2 hojas por cada pagina ya que no caben en la misma hoja.
La primera opción es imprimir de manera horizontal para ello vamos al menú de disposición de pagina>configurar pagina>orientación>horizontal
![[Pasted image 20250428174551.png]]
al modificarlo podemos ver que ya cabe la mayoria de la información de las columnas 
![[Pasted image 20250428175540.png]]
pero como podemos ver no cabe todo el texto así que no es una opción que resuelva en este caso el problema, así que vamos a regresar a la orientación vertical y vamos a utilizar el 3er icono el cual hace la vista previa del salto de pagina 
![[Pasted image 20250428175903.png]]
ahora podremos ver una previsualización de nuestra pagina y sus cortes
![[Pasted image 20250428180050.png]] 
y ahora el siguiente paso para que toda la información quepa dentro de la misma pagina simplemente vamos a arrastrar la linea punteada hasta la parte donde terminan los datos
![[Pasted image 20250428180513.png]]
y para ver las modificaciones podemos regresar a un opción  de diseño de pagina en la parte inferior derecha, que seria el icono de en medio y así podremos visualizar como se vería y cambio a la hora de imprimir
![[Pasted image 20250430193952.png]]
y se visualiza de la siguiente manera
![[Pasted image 20250430194340.png]]
aunque aun tenemos el problema de que si visualización como en la vista horizontal, pero esto lo podemos ajustar reduciendo el tamaño de una celda o celdas a como se ve en la siguiente imagen
![[Pasted image 20250430195816.png]]
Esto se conoce como escalamiento que también lo podemos modificar en Disposición de pagina>Ajustar área de impresión>Escala
![[Pasted image 20250430201019.png]]
Podemos observar que la escala se modifico de manera automática al 70% y lo podemos modificar manualmente para que la información quepa dentro de la pagina

### Video 47: Impresión de títulos

Seguimos con el mismo archivo y si vamos a la sección de archivo y luego la opción de imprimir, veremos algunas opciones que ya hemos manejado pero algunas opciones son nuevas, por ejemplo podemos seleccionar el tipo de impresora 
![[Pasted image 20250430201548.png]]
también tenemos mas opciones por ejemplo podemos imprimir la hoja activa, imprimir todo el libro o imprimir una sola selección que ya hemos escogido previamente 
![[Pasted image 20250430201739.png]]
de igual manera podemos imprimir solo ciertas paginas, intercalar o no las paginas a la hora de imprimir, la orientación (vertical, horizontal), tipo de hoja a imprimir, margenes, personalizar la escala
![[Pasted image 20250430202211.png]]
y por ultimo, si aun queremos mas opciones damos clic en Configurar pagina donde nos va a salir una ventana que contiene casi lo mismo que se ve en la imagen anterior, ahora en una problemática en donde los encabezados de las columnas no se muestran mas que en la primer hoja y nosotros necesitamos que se visualicen en todas las hojas vamos a regresar al archivo, después vamos a disposición de pagina>Configurar pagina>Imprimir títulos
![[Pasted image 20250430202719.png]]
cuando damos clic sobre imprimir títulos, nos saldrá una ventana como la siguiente
![[Pasted image 20250430202846.png]]
y vamos a dar clic en el icono de la flechita hacia arriba de la opción repetir filas en extremo superior y seleccionamos el renglón que queremos que se repita en la impresión de cada una de las paginas, podemos seleccionar uno o varios renglones, pero en este cazo como solo queremos los títulos de la tabla solo seleccionamos la primer fila
![[Pasted image 20250430203314.png]]
y damos enter para seleccionarlo, una vez hecho esto tendremos la vista siguiente en donde podemos dar en aceptar o en vista preliminar
![[Pasted image 20250430203430.png]]
si damos clic sobre vista preliminar nos va a llevar al apartado de impresión para poder visualizar los cambios para imprimir los titulos
![[Pasted image 20250430203619.png]]
como podemos ver tenemos los títulos en la ultima hoja en donde los datos ya no llenan la hoja completa pero tienen los títulos de cada columna, lo mismo se puede hacer para la parte de repetir las columnas 
