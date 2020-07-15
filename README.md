# TEOREMA-DE-THEVENIN

1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos el teorema de thevernin el cual nos permite nos facilita resolver un circuito eléctrico complejo a un sencillo, obteniendo el voltaje y la resistencia del teorema.

2. OBJETIVOS

* Aplicar los conceptos teóricos del teorema thévenin, mediante la realización de la practica en el simulador TINKERCAD, para la resolución o análisis de los circuitos con el fin de encontrar los valores la fuente y la resistencias llamadas como (thévenin).

* Encontrar un circuito equivalente de manera simple y rápida aun en circuitos de naturaleza complicados, tomando en cuenta que al menos se debe tener una fuente independiente.

* Comprobar que los resultados de voltaje y corriente calculados son iguales a los medidos en nuestra simulación

* Comparar los porcentajes de error entre el valor calculado y el medido en el simulador TINKERCAD.

3. MARCO TEÓRICO 

El teorema de Thévenin fue enunciado por primera vez por el científico alemán Hermann von Helmholtz en el año 1853 pero fue redescubierto en 1883 por el ingeniero de telégrafos francés Léon Charles Thévenin (1857–1926), de quien toma su nombre. El teorema de Thévenin es el dual del teorema de Norton.

En la teoría de circuitos eléctricos, el teorema de Thévenin establece que si una parte de un circuito eléctrico lineal está comprendida entre dos terminales A y B, esta parte en cuestión puede sustituirse por un circuito equivalente que esté constituido únicamente por un generador de tensión en serie con una resistencia, de forma que al conectar un elemento entre los dos terminales A y B, la tensión que queda en él y la intensidad que circula son las mismas tanto en el circuito real como en el equivalente.

El teorema de Thevenin es uno de los enunciados básicos de la teoría de circuitos. A través de este, es posible calcular y simplificar un sistema eléctrico. Aplicando este teorema, se puede convertir un circuito complejo, el cual cuenta con dos terminal, a uno simple, compuesto por una sola fuente de voltaje en serie con una resistencia.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/12.JPG)

En la teoría de circuitos, el teorema de Thevenin es uno de los postulados que más se suele aplicar, ya que ofrece  mayores facilidades al momento de trabajar con circuitos complejos:

* Al permitir crear un circuito equivalente de uno más grande, se puede calcular en menos tiempo el valor de voltajes, la corriente o hasta la potencia de un circuito una vez que se conecta una carga.
* Es aplicable a cualquier elemento del circuito, siempre que este cuente con una fuente independiente.
* Es posible encontrar un circuito equivalente simple hasta del circuito más complejo.

Calcular la resistencia de Thevenin:
Para obtener el valor de la resistencia de Thevenin (RTH), es necesario realizar reemplazar cada una de las fuentes de tensión que integran el circuito original a través de un cortocircuito, mientras que en el caso de las fuentes de corriente pasarán a ser circuito abierto. A partir de aquí se procede a calcular la resistencia total del circuito. En el momento en que se vaya a realizar el cálculo de la resistencia de Thevenin, se pueden usar diversos métodos. El más común es agrupando las resistencias en paralelo, transformándolas en una sola. De esta manera, el circuito equivalente solo deberá contener resistencias en serie. Estas deberán ser sumadas, lo que nos dará como resultado la resistencia de Thevenin. Si estamos ante un circuito de corriente alterna, entonces será necesario realizar el cálculo de la impedancia equivalente.

Calcular la tensión de Thevenin: 
En el circuito original se calcula la tensión existente entre los puntos A y B. La mejor manera es realizando la suma y resta de los valores de las fuentes de tensión. Lo mismo será con las caídas de tensión en las resistencias, pero aplicando en este caso las leyes de Kirchhoff, la ley de ohm u otro método válido para el procedimiento.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/13.jpg)

Pasos para aplicar el teorema de Thevenin

Cuando se construye un circuito equivalente de Thevenin, es posible realizar cálculos más sencillos y en menos tiempo que al trabajar con el circuito completo original. Para lograr aplicar el teorema correctamente, se deben realizar estos pasos:

* Al eliminar las fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thevenin. Luego se deberá calcular el valor de la resistencia total que existe entre los punto A y B donde se encuentre conectada la resistencia de carga.
* Para el caso de hallar la tensión de Thevenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde esta se encontraba.
* Construye el circuito equivalente utilizando la tensión de Thevenin y la resistencia de Thevenin en serie. Conecta la resistencia de carga entre los puntos de conexión abiertos de este circuito.
* Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

4. DIAGRAMAS

Circuito Eléctrico

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Diagrama_circuito.png)

Fig 2. Circuito eléctrico, identificando sus respectivas fuentes de voltaje

Descripción del circuito

* En el diagrama se observa dos fuentes independientes de voltaje, conectadas a los extremos del circuito.
* Además, dentro del circuito se aprecia 4 resistencias medidas en KOhms y Ohms.
* Al momento de unir dos elementos eléctricos, se forman nodos que para el caso del circuito de la práctica reconocemos 3 nodos principales.
* Se tiene que la resistencia de 1 KOhm forma nodo con las resistencias de 820 Ohm y 2.2 KOhm. La resistencia de 820 Ohm forma un nodo con las resistencias de 470 Ohm y con la segunda fuente de voltaje. Como nodo de referencia o tierra es toda la sección de abajo del circuito eléctrico.
* Además se puede identificar 3 mallas, que para el análisis se denotará como I1, I2, I3 todas en sentido de las manecillas del reloj(Anexos).

Circuito Eléctrico hecho en Tinkercad

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Circuito_TINKERCAD.png)

Fig 3. Implementación del circuito eléctrico en el simulador Tinkercad

Circuito Eléctrico hecho en Tinkercad (Medición de voltaje en el resitor de carga)

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_voltaje.png)

Fig 4. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al primer caso 

Circuito Eléctrico hecho en Tinkercad (Medición de corriente en el resitor de carga)

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_corriente.png)

Fig 5. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al segundo caso

Circuito Eléctrico hecho en Tinkercad (Medición de voltaje en el circuito abierto)

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_voltaje_sin_R5.png)

Fig 6. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al tercer caso

Circuito Eléctrico hecho en Tinkercad (Medición de la resistencia equivalente)

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_resistencia_sin_R5.png)

Fig 7. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al tercer caso

Circuito equivalente de Thévenin hecho en Tinkercad (Medición de voltaje en el circuito equivalente de Thévenin)

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Circuito_Thevenin_voltaje.png)

Fig 8. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al tercer caso

Circuito equivalente de Thévenin hecho en Tinkercad ((Medición de corriente en el circuito equivalente de Thévenin)

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Circuito_Thevenin_corriente.png)

Fig 9. Implementación del circuito eléctrico en el simulador Tinkercad. Con mediciones referentes al tercer caso

5. LISTAS DE COMPONENTES

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Lista_componentes.png)

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

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_Mediciones_generales.png)

Tabla 1. Medición de voltaje aplicando superposición.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_circuito_Th%C3%A9venin.png)

Tabla 2. Medición de corriente aplicando superposición.              

8. PORCENTAJE DE ERROR.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_porcentaje_de_error.png)

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

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Cronograma.png)

12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
