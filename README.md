# TEOREMA-DE-THEVENIN

1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos el teorema de superposición el cual es solo aplicable en circuitos eléctricos lineales, ya que nos permite calcular la corriente o el voltaje en cualquier rama de un circuito estimulado por varias fuentes de energía, ya sean de corriente o de voltaje. De acuerdo a este teorema, el valor de la corriente o del voltaje en una rama de un circuito estimulado por varias fuentes se produce por la superposición de los estímulos de cada una de ellas.

2. OBJETIVOS

* Aplicar los conceptos teóricos del teorema superposición, mediante la realización de la practica en el simulador TINKERCAD, para la resolución o análisis de los circuitos con el fin de encontrar los valores de voltaje y corriente.

* Analizar los pasos que se requieren para aplicar el teorema de superposición.

* Comprobar que los resultados de voltaje y corriente calculados son iguales a los medidos en nuestra simulación

* Comparar los porcentajes de error entre el valor calculado y el medido en el simulador TINKERCAD.

3. MARCO TEÓRICO 

Es uno de los más importantes y de mayor aplicación. Sea un circuito lineal, en el que puede haber de todo, R, L, C, M, fuentes de tensión y corriente, independientes y dependientes. Distinguimos dos bornes A y B de ese circuito y conectamos una impedancia exterior Z

Se trata de calcular la corriente que circula por esa impedancia, sin resolver todo el circuito. Hacemos una hipótesis más: no hay mutua entre Z y el resto del circuito

1. Voltaje de Vacío o de Circuito Abierto: VAB Es el voltaje que aparece entre A y B cuando no existe la impedancia Z Es el que mediría un voltímetro "ideal" (ideal en el sentido de que al conectarse no modifica el voltaje que existía antes entre esos puntos. Ya precisaremos lo que esto significa). En Laplace, el voltaje de vacío será VAB(s).

2. Impedancia Vista: ZAB Para definirla, anulemos todas las fuentes. Queda un circuito "pasivo" (mejor dicho: sin fuentes) ¿Qué quiere decir "anular las fuentes"? Las fuentes de tensión se cortocircuitan; las de corriente se abren. ¿Cuáles? Las independientes y datos previos; no así las dependientes que no son generadores sino vínculos. Una vez anuladas las fuentes, aplicamos una fuente de tensión E entre A y B.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Diagrama_circuito.png)

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
