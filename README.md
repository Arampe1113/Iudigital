# Iudigital
 Ejercicio 1
Una función en la mayoría de los casos describe un comportamiento que permite identificar puntos en donde se dé respuesta a un interrogante, estos puntos generalmente son los máximos y mínimos de la función y dan solución a los problemas planteados. La función detallada a continuación describe el comportamiento de un material para su temperatura (eje y) a lo largo del tiempo (eje x):

f(x)=x^4−8x^2+3 

La gráfica de la función es la siguiente
Para el presente ejercicio se debe crear un ciclo que recorra los valores de x con una precisión del 0.001 en el espacio comprendido entre -3 y 3, incluídos ambos límites: [-3, 3]. Se deben almacenar en una lista o diccionario los valores tanto de x como de y. Finalmente, con ayuda de condicionales, hay que buscar los puntos resaltados en rojo en la gráfica (con sus respectivos valores en x y y, los cuales corresponden a un máximo local y a dos mínimos.

Nota: no se permite el uso de funciones max o min de las Built-in functions o el uso de cualquier librería que tenga los mismos fines. Tampoco se permite encontrar los valores máximos y mínimos usando derivadas o integrales, aunque queda como opción para verificar los resultados obtenidos con los ciclos.


<<<<<Ejercicio 3>>>>>
El juego HuyPues
Para jugarlo, los participantes se sientan en un círculo. El jugador designado para ir primero dice el número "1", y luego los jugadores siguientes en orden de las manecillas del reloj cuentan hacia arriba por turnos.

Sin embargo, cualquier número divisible por tres se reemplaza por la palabra “Huy” y cualquier número divisible por cinco por la palabra “Pues”. Los números divisibles por tres y cinco se convierten en un “HuyPues”. Un jugador que duda o comete un error es eliminado.

Por ejemplo, una ronda típica de “HuyPues” comenzaría de la siguiente manera: 1, 2, Huy, 4, Pues, Huy, 7, 8, Huy, Pues, 11, Huy, 13, 14, HuyPues, 16, 17, Huy, 19, Pues, Huy,…,n

Realiza un algoritmo que permita, mediante ciclos, realizar el juego “HuyPues” para una cantidad cualquiera n de iteraciones.