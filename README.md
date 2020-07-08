# LABORATORIO # 05

TEMA: TEOREMA DE THÉVENIN
## 1. OBJETIVOS

**1,1.- GENERAL** 

* Comprobar experimentalmente el Teorema de Thévenin en un circuito resistivo.

**1,2.-ESPECÍFICOS**

* Examinar el funcionamiento de un circuito lineal con fuentes variables.

* Comparar los valores medidos con los valores calculados en el circuito y establecer el porcentaje de error resultante.

* Reconocer circuitos que se annalicen mediante el Teorema de Superposición.


## 2. PLANTEAMIENTO DEL PROBLEMA

Este proyecto consistió en la implementación de un circuito mixto lineal, en un programa online denominado Tinkercad con la finalidad de experimentarel análisis mediante el Teorema de Superposición. Se crea el circuito utilizando resistencias en serie y paralelo conetadas a fuentes variables, la cuál es la característica principal para poder utilizar el Teorema de superposición como un método de solución factible.


## 3. MARCO TEÓRICO 

**TEOREMA DE THÉVENIN**

El teorema de Thévenin determina que un circuito eléctrico con dos fuentes de alimentación es equivalente a un circuito formado por una fuente de tensión Vth (Voltaje de Thévenin) en serie con una resistencia Rth (Resistencia de Thévenin).
  
![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/Thevenin.png)

Para aplicar este método primero tenemos que tomar en cuenta que:
* Las fuentes de voltaje se cierran.
* Las fuentes de corriente se abren.
* La resistencia a la cual vamos a calcular su voltaje y corriente, se abre.

Para aplicar el teorema correctamente, se deben realizar estos pasos:

1.	Al eliminar las fuentes de tensión o fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thévenin. Se procede a calcular el valor de la resistencia total existente entre los punto A y B donde se encuentre conectada la resistencia de carga.

2.	Para el caso de hallar la tensión de Thévenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde ésta se encontraba.

3.	Construimos el circuito equivalente utilizando la tensión de Thévenin y la resistencia de Thévenin en serie y procedemos a conectar la resistencia de carga entre los puntos de conexión abiertos.

4.	Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

## 4. DIAGRAMAS

Se simula un circuito lineal, es un circuito mixto con cuatro resistencias en paralelo y corriente conectadas a dos fuentes de voltaje de corriente directa.

![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/Diagrama5.png)


Comprobación del Teorema de Thévenin

![](https://github.com/BriandaLema/Laboratorio5/blob/master/img/Comprobaci%C3%B3n%20del%20teorema%20de%20Th%C3%A9venin.png)





## 5. LISTA DE COMPONENTES

| CANTIDAD| ELEMENTO |
| ------- | -------------|
| 2       | Fuente de Voltaje C.D.  |
| 2       | Multímetros digital  |
| 1       | Resistor de 560 kΩ   |
| 1       | Resistor de 4.7 kΩ   |
| 1       | Resistor de 330 Ω  |
| 1       | Resistor de 100 Ω|
| 1       | Resistor de 1 kΩ|
| 1       | Protoboard                    |

## 6. MAPA DE VARIABLES 

Variables eléctricas: 

* Voltaje
* Corriente 
* Resistores


## 7. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 
El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 8. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Fundamentalmente los prerrequisitos que requiere este laboratorio sería: un dispositivo tegnológico (sea un teléfono, una pc, un tableta, entre otras); pues trabajamos en un simulador online, nuestro segundo requisito es acceso a internet y finalmente tener conocimientos básicos sobre las leyes aplicadas, los componentes, elementos y variables que se utiliza para la creación del circuito.


## 9.APORTACIONES

Para complementar la correcta cuantificacion de valores calculados y valores medidos se baso en videos de la plataforma online YouTube, y se implemento el circuito en el simulador multisim para confirmar los valores.

## 10. CONCLUSIONES

**ANÁLISIS DE RESULTADOS Y CÁLCULO DEL ERROR**

VALORES DEL CIRCUITO EQUIVALENTE DE THÉVENIN

* **VTH (V)**

| CALCULADO | MEDIDO  | 
|----------|------|
| 3.47 V | 3.63 V |

* **RTH Ω**

| CALCULADO | MEDIDO  | 
|----------|------|
| 248 Ω | 298.86 Ω |

COMPROBACIÓN DEL TEOREMA DE THÉVENIN 

 * **CIRCUITO ORIGINAL **

* VOLTAJE (V)

| CALCULADO | MEDIDO  | 
|----------|------|
| 2.89 V | 2.67 V |

* CORRIENTE (mA)

| CALCULADO | MEDIDO  | 
|----------|------|
|  2.89 mA | 2.67 mA |

* **CIRCUITO EQUIVALENTE DE THÉVENIN**

* VOLTAJE (V)

| CALCULADO | MEDIDO  | 
|----------|------|
|  2.77 V | 2.79 V |

* CORRIENTE (mA)

| CALCULADO | MEDIDO  | 
|----------|------|
|  2.77 mA| 2.79 mA  |

- **CÁLCULO DEL ERROR DE LA CORRIENTE**

Corriente total calculado= 0.0255 A

Corriente total medido= 0.0255 A

%error=((Valor teórico-Valor medido)/Valor teórico)* 100

%error=((0.0255 A - 0.0255 A)/ 0.0255 A)* 100

%error= 0 % 

- **CÁLCULO DEL ERROR DEL VOLTAJE**

Voltaje total calculado= 0.952 V

Voltaje medido= 0.94 V

%error=((Valor teórico-Valor medido)/Valor teórico)* 100

%error=((0.952 V - 0.94 V)/ 0.952 )* 100

%error= 0.0126 % 

Como podemos observar los valores calculados (Ix y Va) son casi identicos a mis valores simulados mediante del Tinkercad, Se esto debido a que mi porcentaje de error es casi nulo la cual establece que los datos no se differencian en mucho.

Habiendo simulado y creado el circuito, Podemos observar que aunque hemos calculado los datos de una manera distinta, hemos podido comprobar que este metodo es valida y muy efectiva para los calculos buscados.

Con esto se puede concluir, que mis datos finales muestran una pequeña diferencia entre los valores medidos y calculados, y se podría dar esto de de la differencia por dos razones : al momento de calcular con el multímetro los valores, intervienen las tolerancias de las resistencias, y esto podría afectar a los valores obtenidos; mientras que en los valores medidos tal vez intervenga el hecho que no habiamos usado todos los decimales presentados en la calculadora, la cual aunque poco afecta los valores obtenidos. 



## 11. RECOMENDACIONES

Recomendamos que se debe asegurarse de tomar cálculos de una manera clara y ordenada,para asi no equivocarse en el hecho remplazar y tener como consecuencia un % de error excesivo. En este caso especificamente, se debe en tener en cuenta de desconectar las fuentes de poder paso segundo y tercer caso respectivamente.

Se debe tener en mente, de si se equivoca al traducir el circuito teorico al simulador esto podria causarle problemas en sus calculos, entonces recomendable siempre calcular tus datos manualmente y de ahi proceder a ser el circuito simulado.

Para terminar, sugerimos acordarse para calcular el voltaje de una region se le conecta al circuito directamente y para calcular intensidad se debe tratar al multimetro como un elemento del circuito y conectarle en serie.


## 12. CRONOGRAMA

![](https://github.com/BriandaLema/Laboratorio4/blob/master/img/Cronograma4.png)

https://trello.com/b/CRvRVdmQ/cronograma

## 13. BIBLIOGRAFÍA

* Carakenio73. (2019, Noviembre 8). Recuperado de: https://dademuch.com/2019/11/08/principio-de-superposicion-analisis-de-circuitos-electricos/

* Willi, M. (s.f.). KHAN ACADEMY. Obtenido de https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-superposition

*Teorema de superposición para solución de circuitos eléctricos. (2012, Julio 18). Recuperado de: https://www.ecured.cu/Teorema_de_superposici%C3%B3n_para_soluci%C3%B3n_de_circuitos_el%C3%A9ctricos



## 14.- ANEXOS
https://github.com/BriandaLema/Laboratorio4/blob/master/Anexos/ANEXOS4.pdf






