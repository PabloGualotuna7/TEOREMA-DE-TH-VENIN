# TEOREMA-DE-SUPERPOSICION

1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos el teorema de superposición el cual es solo aplicable en circuitos eléctricos lineales, ya que nos permite calcular la corriente o el voltaje en cualquier rama de un circuito estimulado por varias fuentes de energía, ya sean de corriente o de voltaje. De acuerdo a este teorema, el valor de la corriente o del voltaje en una rama de un circuito estimulado por varias fuentes se produce por la superposición de los estímulos de cada una de ellas.

2. OBJETIVOS

* Aplicar los conceptos teóricos del teorema superposición, mediante la realización de la practica en el simulador TINKERCAD, para la resolución o análisis de los circuitos con el fin de encontrar los valores de voltaje y corriente.

* Analizar los pasos que se requieren para aplicar el teorema de superposición.

* Comprobar que los resultados de voltaje y corriente calculados son iguales a los medidos en nuestra simulación

* Comparar los porcentajes de error entre el valor calculado y el medido en el simulador TINKERCAD.

3. MARCO TEÓRICO 

El teorema de superposición, en circuitos eléctricos, establece que el voltaje entre dos puntos, o la corriente a través de ellos, es la suma algebraica de los voltajes (o de las corrientes si es el caso), debidos a cada fuente, como si cada una actuara de manera independiente.
Este teorema permite analizar circuitos lineales que contengan más de una fuente independiente, ya que solamente se requiere calcular la contribución de cada una por separado.

La dependencia lineal es determinante para que el teorema se aplique. Un circuito lineal es aquel cuya respuesta es directamente proporcional a la entrada.

Por ejemplo, la ley de Ohm aplicada a una resistencia eléctrica establece que V = i.R, donde 

V=voltaje 
R=resistencia
i=corriente. Se trata entonces de una dependencia lineal del voltaje y la corriente en una resistencia.

En circuitos lineales, el principio de superposición se aplica teniendo en cuenta lo siguiente:

* Hay que considerar cada fuente de voltaje independiente por separado y para ello es necesario apagar todas las demás fuentes. Basta con poner a 0 V todas las que no estén bajo análisis o bien sustituirlas en el esquema con un cortocircuito.
* Si la fuente es de corriente entonces hay que abrir el circuito.
* Cuando se considera la resistencia interna de las fuentes tanto de corriente como de voltaje, estas deben permanecer en su lugar, formando parte del resto del circuito.
* Si existen fuentes dependientes, no se deben tocar y deben quedar tal cual como aparecen en el circuito.

Además, el teorema de superposición ayuda a encontrar:

* Valores de tensión, en una posición de un circuito, que tiene más de una fuente de tensión y/o corriente.
* Valores de corriente, en un circuito con más de una fuente de tensión y/o voltaje.

Pasos a realizar:

a) Se anulan todas las fuentes menos una:

NOTA: 

* Anular una fuente de tensión es cortocircuitarla.
* Anular una fuente de corriente es dejarla en circuito abierto.

b) Se calcula la respuesta del circuito (tensión o corriente) a la única fuente que hemos dejado.

c) Se repiten los pasos 1 y 2 con cada fuente.

d) Se suman las respuestas de cada fuente.

![](https://raw.githubusercontent.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/master/img/TEOREMA%20SUPERPOSICI%C3%93N.jpg)

Fig 1. Equivalenetes de fuentes independientes de voltaje y corriente al momento de aplicar el teorema de superposición.

Podemos observar como se apaga las distintas fuentes(izquierda fuente de voltaje y en la derecha fuente de corriente), cabe recalcar que una fuente dependiente esa se le deja tal y como está. 

4. DIAGRAMAS

Circuito Eléctrico

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Diagrama%20del%20circuito.png)

Fig 2. Circuito eléctrico, identificando sus respectivas fuentes de voltaje

Descripción del circuito

* En el diagrama se observa dos fuentes independientes de voltaje, conectadas a los extremos del circuito.
* Además, dentro del circuito se aprecia 4 resistencias medidas en KOhms y Ohms.
* Al momento de unir dos elementos eléctricos, se forman nodos que para el caso del circuito de la práctica reconocemos 3 nodos principales.
* Se tiene que la resistencia de 1 KOhm forma nodo con las resistencias de 820 Ohm y 2.2 KOhm. La resistencia de 820 Ohm forma un nodo con las resistencias de 470 Ohm y con la segunda fuente de voltaje. Como nodo de referencia o tierra es toda la sección de abajo del circuito eléctrico.
* Además se puede identificar 3 mallas, que para el análisis se denotará como I1, I2, I3 todas en sentido de las manecillas del reloj(Anexos).

Circuito Eléctrico hecho en Tinkercad

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Circuito%20armado.png)

Fig 3. Implementación del circuito eléctrico en el simulador Tinkercad

Circuito Eléctrico hecho en Tinkercad (Primer caso)

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Primer%20caso.png)

Fig 4. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al primer caso 

Circuito Eléctrico hecho en Tinkercad (Segundo caso)

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Segundo%20caso.png)

Fig 5. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al segundo caso

Circuito Eléctrico hecho en Tinkercad (Tercer caso)

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Tercer%20caso.png)

Fig 6. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al tercer caso 

5. LISTAS DE COMPONENTES

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Lista%20de%20componentes.png)

Fig 7. Descripción de los componenetes usados en el simulador Tinkercad.

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la práctica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard).

* Se selecciona y se conecta al protoboard los suministros de energía asignándole el valor de 20 y 12 V.

* Escogemos cinco resistencias y las conectamos siguiendo el diagrama visto en el archivo de la práctica, que en este caso son 4 de valores de 1 KOhm, 0.47 KOhm, 2.2 KOhm y 0.82 KOhm.

* Haciendo clic izquierdo en los pines del protoboard conectamos con cables las resistencias y pasamos corriente a donde hace falta.

* Colocamos un multímetro y conectamos en paralelo con el circuito, el color negro es el negativo mientras que el color rojo es el positivo. 

* Realizamos las mediciones de volatje y resistencia, aplicando el teorema de superposición, pedidas en la guía.

* Anotamos los valores obtenidos en las tablas de la guía de laboratorio.

* Guardamos y salimos.

7. TABLAS DE MEDICIONES Y CÁLCULOS 

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Tabla_voltaje.png)

Tabla 1. Medición de voltaje aplicando superposición.

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Tabla_corriente.png)

Tabla 2. Medición de corriente aplicando superposición.              

8. PORCENTAJE DE ERROR.

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Porcentaje%20de%20error.png)

Tabla 3. Porcentaje de error al momento de realizar la práctica.

9. CONCLUSIONES 

* Se concluye que experimentalmente, para encontrar el voltaje "VA" y corriente "Ix" de nuestro circuito mediante el teorema de superposcición es igual la suma de los voltajes y corrientes independientes de los dos circuitos analizados cuando V2=0 y V1=0. 

* En la práctica realizada en el simulador para suprimir las fuentes ideales de tensión se ponen uniones donde debería ir conectada esa fuente, de ese modo estariamos cumpliendo con la teoria donde, una fuente de voltaje se reemplaza por un cortocircuito. 

* Este método se vuelve más fácil para analizar el circuito debido a que se toma un voltaje de referencia el cuál siempre es igual a cero y nos elimina una variable para calcular, permitiéndonos una resolución más rápida del ejercicio.

* El porcentaje error nos demuestra que el informe se ha desarrollado de manera correcta y este caso nos da un 0.04% de error entre el calculado y el medido, el cual es un porcentaje bajo y no afecta a los resultados, esto debido también a que no sabemos con cuantos decimales trabaja el simulador TINKERCAD.
 
10. RECOMENDACIONES 

* Se recomienda cambiar el color de los cables a rojo y negro para de esta manera identificar cuáles son positivos o negativos, y no crear una confusión al momento de conectar el circuito.

* Tener en cuenta y verificar los valores de la fuente así como también el valor de las resistencias ya que muchas veces se equivoca al poner KOhm o Ohm.

* Recomendamos una vez obtenido el sistema de ecuaciones en cada caso del analisis, utilizar el método de determinantes, ya que es una forma mas dinámica y rapida para poder resolver este tipo ejercicios.

11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/Edgar1Gallegos/TEOREMA-DE-SUPERPOSICION/blob/master/img/Cronograma.png)

12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
