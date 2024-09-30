# EJERCICIOS MEDIOS DE PHP

1. Crear un array asociativo llamado “CajonDeSastre” donde se almacenen un número indeterminado de elementos de diferentes tipos (al menos 10). A continuación, saca de uno en uno los elementos y muéstralos por pantalla.

Sugerencia: debes emplear la sentencia foreach para realizar este ejercicio de una manera eficiente.

2. Crea una biblioteca llamada "matematicas.php" que incluya una función que calcule el producto de 3 números.

3. Partiendo del ejercicio anterior, añade una nueva función a la librería que imprima por pantalla los primeros N números primos.

4. Usando dos arrays que contengan los valores: 4,12,-5,8,13,-9,0,3 y 1,-2,3,-6,4,12,-7,-8, calcular la media aritmética de cada uno empleando funciones y, posteriormente, mostrar por pantalla y separados por dos puntos “:” aquellos números que sean mayores a dicha media. Tómese como solución la siguiente referencia:

   Media 1 = 3.25

   4 : 12 : 8 : 13

   Media 2 = -0.375

   1 : 3 : 4 : 12

6. Escribir un programa PHP que muestre en pantalla números aleatorios entre 1 y 500 hasta que aparezca un múltiplo de 7. Al terminar el programa se mostrará el mensaje “Fin de programa”.

7. Crear un array unidimensional con 100 números aleatorios entre 1 y 100. Mostrar el array en forma de tabla HTML de 10 filas x 10 columnas y sombrear en color azul claro (lightblue) los números repetidos.

Sugerencia: emplear la función de PHP array_count_values para ver los números repetidos.

7. Crear un array bidimensional asociativo en el que la clave de la primera dimensión será el nombre de los equipos de la primera división de la liga de fútbol. Cada equipo contendrá un array de dos elementos, el primero, con clave “puntos” contiene la puntuación obtenida en la pasada liga. El segundo elemento con clave “posición” contendrá en número la posición en la tabla en la que finalizó el equipo la liga. Utilizando los bucles que necesites muestra en pantalla los nombres de los equipos, los puntos y la posición de los equipos que terminaron en las tres primeras posiciones de la liga.

8. Partiendo de la frase: “Programa siempre tu código como si el tipo que va a tener que mantenerlo en el futuro fuera un violento psicópata que sabe dónde vives, (Martin Goldin)”. Utiliza las funciones de string y/o arrays que quieras, para mostrar en pantalla:

El número de palabras que contiene la frase.
 La cuarta palabra de la frase.
 Número de veces que aparece la palabra “que”.
 La posición donde aparece la palabra psicópata.
Sustituye la palabra “Programa” por “Comenta”.
Número de palabras que comienzan por “fu”.
Todas las palabras que comienzan por la letra “s”.
El nombre del autor de la frase.
Sugerencia: Las funciones str_count_words(), str_replace(), strst()r, implode(), rtrim(), trim(), ltrim(), preg_match_all() te servirán para el desarrollo de este ejercicio.

Crear un array asociativo de dos dimensiones. La clave de la primera dimensión será el
código de empleado, que tendrá el formato “CExxxx” donde xxxx será un número de 4
cifras. La segunda dimensión del array tendrá por claves “nombre”, “edad” y “salario”
cuyo contenido será el nombre, la edad y el salario del empleado.

Hacer una función en PHP que reciba como parámetros el nombre, la edad y el salario
de un empleado, y calcula un nuevo salario para esa persona en base a su situación:

Si el salario es mayor de 2.000€, no cambiará.
Si el salario está entre 1.000 y 2.000€:
Si además la edad es mayor de 45 años se sube un 4%.
Si la edad es menor o igual que 45 años se sube un 10%.
Si el salario es menor de 1.000€:
Los menores de 30 años cobrarán a partir de entonces exactamente 1.500€.
De 30 a 45 años sube un 3%.
A los mayores de 45 años sube un 15%.
La función debe actualizar en el array los valores en caso de cambio y mostrar en pantalla los nombres y el nuevo salario de los que han sufrido modificaciones.
Crear un juego en el que el usuario deba adivinar un número entre el 1 y el 10 en 3 intentos. Si el usuario acierta dentro de los turnos de juego, se imprimirá por pantalla: “¡Felicidades, has acertado” en color verde. Si por el contrario se agotan los turnos, mostrará el texto: “¡Oh, mejor suerte la próxima vez!” en color rojo, junto a la solución.

