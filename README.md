
# Informe de laboratorio de circuitos
Trabajo grupal sobre la segunda practica de laboratorio

### PRÁCTICA No. 3 TEOREMA DE SUPERPOSICIÓN

#### OBJETIVO GENERAL
- Saber emplear el teorema de superposición simuladamente como teórica dentro de un circuito.

#### OBJETIVO ESPECIFICO
-	Realizar simuladamente el teorema de superposición comparando los resultados de la practica con los teóricos.

-	Verificar la importancia del teorema de superposición en la simplificación de circuitos.

-	Conocer los fundamentos importantes del teorema de superposición.

#### MARCO TEORICO
![image](https://user-images.githubusercontent.com/76060654/104999583-180b7700-59fb-11eb-9a63-2b2b659a3846.png)

![image](https://user-images.githubusercontent.com/76060654/104999571-12ae2c80-59fb-11eb-8e0a-788122d55fd4.png)

#### DIAGRAMA

![image](https://user-images.githubusercontent.com/76060654/104999547-09bd5b00-59fb-11eb-9a77-d664758032d2.png)

### INFORMACION GENERAL

Uno de los métodos que se aplica en el análisis de circuitos eléctricos que cuentan con varias fuentes, es el Teorema de Superposición que establece que: 
El voltaje o corriente a través de cualquier elemento del circuito puede obtenerse sumando algebraicamente todos los voltajes o corrientes individuales generados por cada fuente actuando por sí sola, con todas las demás fuentes igualadas a cero.
Las fuentes de voltaje igualadas a cero equivalen a un corto circuito, mientras que las fuentes de corriente igualadas a cero equivalen a un circuito abierto.

#### LISTA DE COMPONENTES
|CANTIDAD|ELEMENTO|
|:---:|:---:|
|2|Fuente de voltaje de C.D|
|2|Multímetro Digital|
|1|Resistor de 1 KΩ|
|1|Resistor de 2.2 KΩ|
|1|Resistor de 1 kΩ|
|1|Resistor de 820 Ω|
|1|Resistor de 470 Ω|
|1|Protoboard|

#### EXPLICACION

Realizamos el circuito en el simulador recomendado de Tinkercat, con los materiales necesarios como el protoboard,4 resistencias,2 multimetros , una para poder medir lo que es el voltaje y la otra para medir la corriente, conectamos todo muy bien y nos sale los resultados.
Con los resultados obtenidos procedemos a realizar los calculos y comparamos que los calculos y los resultados simulados concuerden, y colocamos los valores en las tablas propuestas.


### TABLAS

-	Tabla 4.1. Medición de voltaje aplicando superposición.

|VOLTAJE TOTAL (VA)|VOLTAJE TOTAL (VA) CAUNDO V2=0 | VOLTAJE TOTAL (VA) CAUNDO V1=0|
| :---: | :---: | :---: |
| Calculado\| Medido|	Calculado\| Medido| Calculado\| Medido|
| 952V\| 952V|	5.69V\| 7.48V| 6.56V\| 6.53V|


-	Tabla 4.2. Medición de corriente aplicando superposición.

|VOLTAJE TOTAL (IX)|VOLTAJE TOTAL (IX) CAUNDO V2=0 | VOLTAJE TOTAL (IX) CAUNDO V1=0|
| :---: | :---: | :---: |
| Calculado\| Medido|	Calculado\| Medido| Calculado\| Medido|
| 24.4 mA \| 24.4 mA |	6.95 mA \| -9.12 mA | 33.53mA\| 33.5mA|


### CALCULOS:

![image](https://user-images.githubusercontent.com/76060654/105065458-e1118180-5a4b-11eb-833d-8e721354f475.png)
![image](https://user-images.githubusercontent.com/76060654/105065477-e79ff900-5a4b-11eb-9ead-50f0c9f30b81.png)


#### DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN


Para el tema de superposición se requiere un alto entendimiento en circuitos básicos, solo se puede aplicar en casos de circuitos eléctricos lineales, solo circuitos formados únicamente por componentes lineales donde la corriente que los atraviesa es proporcional a la diferencia de tensión entre sus terminales. En principio, el teorema de superposición puede utilizarse para calcular circuitos haciendo cálculos parciales. Pero eso no presenta ningún interés práctico porque la aplicación del teorema alarga los cálculos en lugar de simplificarlos.
Para comprender el teorema de superposición se establece que, en un circuito lineal con varias fuentes, la corriente y el voltaje para cualquier elemento en el circuito es la suma de las corrientes y voltajes producidos por cada fuente que actúa de manera independiente. Para calcular la contribución de cada fuente de forma independiente, todas las demás fuentes deben eliminarse y reemplazarse sin afectar el resultado final. Al eliminar una fuente de voltaje, su voltaje debe establecerse en cero, lo que equivale a reemplazar la fuente de voltaje con un cortocircuito. Al eliminar una fuente de corriente, su corriente debe establecerse en cero, lo que equivale a reemplazar la fuente de corriente con un circuito abierto.

#### APORTACIONES

El teorema de superposición ayuda a encontrar:
- Valores de tensión, en un nodo de un circuito, que tiene más de una fuente independiente.
- Valores de corriente, en un circuito con más de una fuente independiente.
Este teorema establece que el efecto que dos o más fuentes tienen sobre una impedancia es igual, a la suma de cada uno de los efectos de cada fuente tomados por separado, sustituyendo todas las fuentes de tensión restantes por un corto circuito, y todas las fuentes de corriente restantes por un circuito abierto.
El verdadero enfoque de la superposición es su teoría. El teorema justifica métodos de trabajo con circuitos que simplifican verdaderamente los cálculos.
También ayuda a la descomposición de una señal no sinusoidal en suma de señales sinusoidal. Se reemplaza una fuente de tensión o de corriente por un conjunto (tal vez infinito) de fuentes de tensión en serie o de fuentes de corriente en paralelo. Cada una de las fuentes corresponde a una de las frecuencias de la descomposición. El resultado final será la suma de los resultados obtenidos remplazando, en el cálculo único, la frecuencia por cada una de las frecuencias de la serie de Fourier. El enorme interés de esto es el de poder utilizar el cálculo con el formalismo de impedancias cuando las señales no son sinusoidales.

#### CONCLUSIONES

- Para poder proceder a realizar la práctica de laboratorio de circuitos, hubo la necesidad de comprender teóricamente todo sobre los circuitos lineales y el teorema de superposición que se comprendió que su fuerte y objetivo no son los ejercicios en si ya que este los alarga más que cualquier otro método, su verdadero objetivo fue el análisis teórico de los circuitos lineales 

- La práctica realizada fue con relación al teorema de superposición que al realizarlas nos dio resultados prácticos y exactos sobre todo en el diagrama, aunque existió problemas leves sobre conocimientos prácticos y teóricos en el ejercicio, el resultado final dio los resultados esperados y correctos.

-  Esta práctica dio a reconocer los entendimientos sobre la resolución de ejercicios sobre circuitos lineales (Sobre todo su parte teórica ya que más bien alargo innecesariamente la resolución de ejercicios) y cómo proceder a analizarlos (Sobre todo su análisis ya que el teorema se enfoca en una parte teórica de los circuitos lineales) y poder recordar/razonar las fórmulas para poder realizarlos sin ninguna pérdida de tiempo. 

#### BIBLIOGRAFIA

Teorema de la superposicion. (2020, June 2). TINA Design Suite. https://www.tina.com/es/superposition-theorem/

colaboradores de Wikipedia. (2020, March 19). Teorema de superposición. Wikipedia, La Enciclopedia Libre. https://es.wikipedia.org/wiki/Teorema_de_superposici%C3%B3n

Carlos G, J. (2015). ✔️ 【 Teorema de superposición 】 Análisis y Ejercicios resueltos. Todito LED. https://toditoled.com/electronica/teorema-de-superposicion

Teorema de superposición. (2018). Innovacionumh. https://repositorio.innovacionumh.es/Proyectos/P_19/Tema_1/UMH_05.htm

A. (2019, September 11). Superposicion. La Fisica y Quimica. https://lafisicayquimica.com/teorema-de-superposicion/


#### ANEXOS
![image](https://user-images.githubusercontent.com/76060654/104999488-ee525000-59fa-11eb-9309-84d776fb152c.png)

![image](https://user-images.githubusercontent.com/76060654/104999501-f3170400-59fa-11eb-91cc-dca8666e0129.png)

![image](https://user-images.githubusercontent.com/76060654/104999510-f611f480-59fa-11eb-8cbe-325d97ab2c14.png)

![image](https://user-images.githubusercontent.com/76060654/104999460-e09cca80-59fa-11eb-9f52-ebf7bc3dd102.png)
