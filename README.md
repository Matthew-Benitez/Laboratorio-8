# Laboratorio 8
1. OBJETIVOS
- Objetivo General:
   
   - Comprender el comportamiento de bobinas y capacitores en circuitos ca.
   
- Objetivos Específicos:
 
   - Determinar los diferentes voltajes que existen dentro de los circuitos ca. y cómo son medidos.
   - Comprender los diferentes efectos de las bobinas y capacitores dentro de los circuitos ca.
   - Comparar y determinar los resultados de dos tipos de circuitos, uno con capacitores y otro con inductores.
   
2. MARCO TEÓRICO
   
   ![0001 (10)](https://user-images.githubusercontent.com/76133212/112571149-7535f700-8db5-11eb-849e-77ffd878c3cf.jpg)
   ![0001 (9)](https://user-images.githubusercontent.com/76133212/112571156-7830e780-8db5-11eb-8c03-cdcf90ad42b6.jpg)

   
3. DIAGRAMAS
   
   ![Simulador 8_Página_1](https://user-images.githubusercontent.com/75439689/112569049-7d8c3300-8db1-11eb-90c5-30d3b1101517.jpg)
   ![Simulador 8_Página_2](https://user-images.githubusercontent.com/75439689/112569052-80872380-8db1-11eb-8d2b-0a85f2cc11e9.jpg)
   ![Simulador 8_Página_3](https://user-images.githubusercontent.com/75439689/112569068-84b34100-8db1-11eb-8320-3f1c7198ac45.jpg)
   ![Simulador 8_Página_4](https://user-images.githubusercontent.com/75439689/112569070-84b34100-8db1-11eb-9763-d028b36cfe7a.jpg)
   ![Simulador 8_Página_5](https://user-images.githubusercontent.com/75439689/112569073-854bd780-8db1-11eb-803e-e33a3ee3f4a7.jpg)
   ![Simulador 8_Página_6](https://user-images.githubusercontent.com/75439689/112569074-854bd780-8db1-11eb-9755-4bb522b21f8a.jpg)
   ![Simulador 8_Página_7](https://user-images.githubusercontent.com/75439689/112569065-841aaa80-8db1-11eb-811a-b680a3865ab6.jpg)
   ![Simulador 8_Página_8](https://user-images.githubusercontent.com/75439689/112569066-84b34100-8db1-11eb-875c-e6c380ec614c.jpg)

   
4. LISTA DE COMPONENTES
   
   ![image](https://user-images.githubusercontent.com/75439689/112568012-d0fd8180-8daf-11eb-9c98-ada8c7f6883e.png)
   
   *Figura 4.1*

5. EXPLICACIÓN

   5.1. Procedimiento
   
    - Ingresar ala plataforma dcaclab y seleccionar los elementos listados previamente dando los valores respectivos.
    - Conectar en serie la fuente de valor pico 10 V, con la resistencia de 100 ohm. y con una conexión en paralelo de dos capacitancias (y posteriormente con dos inductancias en lugar de ellas).
    - Conectar los extremos del osciloscopio a los extremos de la conexión en paralelo de las capacitancias (o inductancias).
    - Conectar el multímetro con la perilla en la opción 12V AC, que permitirá medir el voltaje rms en los mismos extremos de la conexión en paralelo mencionada anteriormente
    - Conectar en serie entre la fuente y la resistencia, un multímetro con la perilla en la opción de 3 A, que permitirá observar los valores de la corriente para la resistencia.
    - Colocar un valor de 0Hz a la frecuencia de la fuente y tomar las respectivas medidas.
    - Repetir el paso anterior pero con diferentes valores de frecuencia: 10 Hz, 50 Hz, 100Hz, 500Hz y 1000Hz.
    - Para tomar el valor de la corriente de la resistencia, es importante conocer que el multímetro no va a dar un valor fijo, sino que va a dar los valores según el tiempo, dado que es una corriente alterna. Por ello, se debe observar el mayor valor de entre todos los que se ven en el mulímetro y tomar dicho valor, el cual es el valor pico de la corriente.

   5.2. Análisis de Resultados
   
     ![image](https://user-images.githubusercontent.com/75439689/112569419-1f138480-8db2-11eb-8020-fd5d8867b814.png)
     ![image](https://user-images.githubusercontent.com/75439689/112569423-220e7500-8db2-11eb-9f39-554f6e1c49e6.png)
     
     Para el análisis de resultados se imprimieron dos tablas, una por cada circuito, donde los datos se distribuyen en 4 columnas: frecuencia, voltaje pico, voltaje rms y la corriente, cada dato fue tomado mediante el simulador dcac lab, y luego fueron puestos en estas tablas.
     
     Tabla Circuito con Capacitores Voltaje pico:
     
     Los voltajes pico tiene un valor casi aproximado al voltaje de fuente, pero a medida que la frecuencia aumenta, su voltaje pico va disminuyendo en relación al voltaje de fuente. Al principio la frecuenia de 0 Hz debería darnos un voltaje de 10v, sin embargo, el simulador no puede determinar esto.
     
     Tabla Circuito con Capacitores Voltaje rms:
     
     Los voltajes rms expresan el voltaje real que capta una carga, estos voltajes representan el 0.707 del voltaje pico de los medidos en la segunda columna de la primera tabla, esto es experimentado en las tablas, cada dato es al menos algo cercacno al 0.707 de cada voltaje pico respectivamente de cada frecuencia.
     
     Tabla Circuito con Capacitores Corriente:
     
     Los valores de corrientes se comportan de manera inversa a la de los voltajes; en cada voltaje, a medida que aumentaba la frecuencia, disminuía el voltaje, por otro lado, la corriente va en aumento a medida que la frecuencia aumenta, esto es evidenciado en la tabla donde los datos fueron sacados del simulador.
     
     Tabla Circuito con Inductores Voltaje pico:
     
     Los voltajes pico en la tabla de inductores se comportan de manera contraria a los voltajes de la tabla del circuito con capacitores, los voltajes pico empiezan cerca del 0, pero por cada frecuencia que va aumentando, los valores del voltaje se van acercando al valor del voltaje de fuente, como es evidenciado en la segunda columna de la tabla de inductores.
     
     Tabla Circuito con Inductores Voltaje rms:
     
     Los voltajes de la tercera columna cumplen la teoría de que valen el 0.707 del valor de voltaje pico, y como fue dicho antes, estos valores van en aumento a medida que la frecuencia va aumentando, al contrario de como se comportaba los voltajes rms en la tabla del circuito con capacitores.
     
     Tabla Circuito con Inductores Corriente:
     
     En esta tabla se evidencia la corriente que se pasa por parte de la resistencia, pero se puede observar que los valores que pasan por este se ven afectados de manera inversa por la frecuencia, es decir, por cada frecuencia que se va aumentando el valor de la corriente va disminuyendo, al contrario de la tabla de circuito con capacitores, hasta llegar al valor de 0 A.
     
   5.3. Preguntas
   
     1. ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?
         
     2. ¿Cómo se comportan la bobina y el capacitor en corriente alterna?
      
     3. ¿Qué cree usted que ocurriría con el voltaje Vo y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?
       
     4. ¿Qué son los valores eficaces de voltaje y corriente?
       

  

6. CONCLUSIONES

   -


7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
