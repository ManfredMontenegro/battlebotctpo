# Propuesta Battlebot CTPO para Universidad CENFOTEC
Nuestra propuesta consiste en investigar sobre las competencias de robots, definir un reglamento de juego y diseñar  2 robots (uno con mazo y otro con una sierra) utilizando impresión 3D y corte lasér CNC, a demás, crear el diseño del dojo e implementar un control remoto  por medio de ESP Now.
Para nuestros Battlebots nos inspiramos en este vídeo: https://www.youtube.com/watch?v=1lOikKyGHfs 



Prototipo 1   
Lista de materiales

2 IdeaBoard

1 Neodymium Magnet Disk 5x3mm N35

1 Big Button

2 Micro Gearmotor

1 TowerPro SG-92R Micro Servo

1 MG996R Continuous Rotation Metal Gear Servo

1 Male to Female Jumper Wire (30 pcs )

2 llantas 3d

1 joystick

1 3PI N20 ball caster

2 Battery Holder - 4xAA



ServoMotores del brazo                                 


![image](https://github.com/user-attachments/assets/ec689165-71c0-4844-a3e6-8425533db629)

TowerPro SG-92R Micro Servo


Este servomotor puede girar aproximadamente 90 grados y funciona igual que los tipos estándar a los que estás acostumbrado, pero más pequeño.


Caracteristicas

Tamaño: 23x11x29mm
Voltaje: 3V a 6V CC
Peso: 9 g/0,32 oz
Velocidad: 0,12 seg/60 (a 4,8 V)
Par de torsión: 1,6 kg-cm
Temperatura de trabajo: -30C~60C
Buje de teflón, cable de 19 cm, motor sin núcleo, brazos servo y tornillo incluidos






![image](https://github.com/user-attachments/assets/3315614f-8bd6-4d78-8ea4-0aa9054c56a4)

        
MG996R Continuous Rotation Metal Gear Servo





funciona como un motor de rotación continua lo que lo hace perfecto para proyectos de robótica, pero al mismo tiempo esto significa que no es posible controlar la posición del eje del motor, solo la dirección de rotación y la velocidad.




Caracteristicas


Peso: 55g
Par de parada: 9,4 kg/cm (4,8 v); 11kg/cm (6,0v)
Velocidad de funcionamiento: 0,19 segundos/60 grados (4,8 v); 0,15 segundos/60 grados (6,0 v)
Voltaje de funcionamiento: 4,8 ~ 6,6 v
Corriente de funcionamiento normal: 600 mA - 1 A
Corriente de parada: 2.5A
Tipo de engranaje: Engranaje de metal, juego de engranajes y eje mejorados de aluminio 6061-T6, lo que lo hace más resistente y liviano que el cobre.
Rango de temperatura: 0- 55 grados
Longitud del cable del servo: 30 cm




ServoMotores de las ruedas



![image](https://github.com/user-attachments/assets/50bdac94-a11e-4fd4-bfad-4da76814e700)




Micro Gearmotor





Estos micromotores con engranajes son increíblemente resistentes y cuentan con engranajes completamente metálicos.



Caracteristicas


Voltaje: 6V
Eje en D de 3 mm
Corriente sin carga: 80 mA
Corriente de bloqueo: 360 mA (6 V)
1000 RPM 
CC reversible





Board


![image](https://github.com/user-attachments/assets/be1d01f8-a430-4b58-9cb9-5af552666882)



El IdeaBoard es un tablero educativo de desarrollo de Robótica e Internet de las Cosas creado por CRCibernetica.com en Costa Rica.


Caracteristicas

Microcontrolador ESP32-WROOM-32E ◦ 32bits @ 240MHz ◦ Lógica 3.3V ◦ 520KB SRAM ◦ 8MB FLASH ◦ WIFI 802.11b/g/n ◦ Bluetooth V4.2 BR/EDR y Bluetooth LE • Puentes H duales para control de motores (800mA para cada motor) • LED RGB programable multicolor (WS2812B) • Programable usando CircuitPython/Micropython o Arduino IDE (C/C++) • Interfaz USB-C para programación y depuración (convertidor serie CH340G) • Conectores estándar de 0,1" para una mayor comodidad interfaz con GND y Vcc para cada pin • Interfaz STEMMA/QWIIC de 4 pines para conexiones fáciles a los módulos Adafruit y Sparkfun i2c • Alimentación CC directa para batería o fuente de alimentación (5 VCC - 9 VCC) • 7 pines para servos u otras aplicaciones que requieren conexión directa alimentación • 14 pines de E/S de uso general en total (7 de alimentación directa, 7 con lógica de 3,3 V)











Competencia Battlebot   


Pasos para armar

Como primer paso se pondrá la ideaBoard y la caja de baterías a la base, para después ponerle los Micro Gearmotor para ponerle las llantas, para seguir con la ball caster que iría al frente, siguiendo con los soportes y poniendo la tapa encima atornillándola para que quede sujeto, en las ranuras que tiene la tapa irá atornillado el brazo.

  

Formato de Competición  

El torneo Battlebot se estructura como un torneo por eliminatoria.  

Dos Robots compiten en una “Jaula”. Es una pelea entre robots en donde se intentan quitar banderas. El que se quede sin banderas pierde  

Se define una llave previa donde los equipos serán asignados al azar.  

Los encuentros de dos robots los denominamos "Figth”  

Cada Figth consiste de 3 Rounds (Rondas) de un minuto, con una pausa de medio minuto entre juegos, para ajustes o cambios de estrategia  

La “Jaula” es un ring cuadrado de 2m x 2m , de fondo negro con Cedazo en la orilla. Esto es para que el robot no pueda salir antes de que termine el round   

  

Principios del juego   

La mesa de arbitraje revisará el robot para determinar que sigue las especificaciones requeridas  

Son tres "rounds" por figth , se gana de dos formas. Forma 1: Se quitan todas las banderas Forma 2: El que obtenga más puntos   

Cada batalla tiene una duración máxima de 1:00 minuto  

En caso de empate (no se hayan perdido banderas o quedaron igual), la mesa de arbitraje considerará ganador el robot con mayor número de ataques  

Las 2 acciones de batalla son atacar y defender  

La competencia es por eliminación, y van clasificando en pares hasta la final.  

Se documentará la estrategia de los 2 mejores, así asegurando un nivel más alto cada año   

  
  
Reglas del Juego   

Un fiscal revisará cada robot para asegurarse de que cumple con las especificaciones requeridas. En caso de duda, será verificado por jueces.  

Cada "Figth" consta de tres "rounds". El que quite una banderas obtendra puntos dependiendo del color de la misma. Bandera verde: 10 puntos Bandera amarilla: 5 puntos Bandera anaranjada: 3 puntos  

Al iniciar la figth, los equipos deben esperar a que suene el silbato para comenzar el round   

Un robot pierde si este pierde las 5 banderas, también si este mismo obtuvo un puntaje más bajo que el de su contrincante 

Cada figth tiene una duración máxima de 1 minuto  

La competencia inicia por grupos, y las siguientes rondas son por eliminación y los equipos avanzan en pares hasta la final.  

Cada competidor puede elegir como como iniciar la figth, son tres posiciones posibles y cada una se hará en elección de los competidores. Posición 1: Cada uno en una esquina, Posición 2: Espalda con espalda 

Posición 3: Uno en un lado y otro en otro lado del cuadrilátero   

Entre cada combate se tiene 30 segundos para revisar el robot y hacer posibles cambios  

En caso de que los robots pierdan la última bandera al mismo tiempo, se hará un round de 30 segundos con la bandera establecida por los jueces  

Si en una partida no se presenta uno de los equipos, ganará el que se presentó (el equipó que se presentó avanzara a la siguiente fase)  

Si un equipo llega tarde a la primera figth, puede seguir jugando los siguientes round, perdiendo el primer round y rebajándoseles una de las banderas amarillas  

Los equipos tendrán varios lugares donde colocar las banderas establecidos en la base   

En caso del robot quedar prensado con el ¨ring¨ se daran 5 segundos para que logre liberarse, de no ser posible se reacomodaran frente a frente en medio del ¨ring¨  

En caso de que el robot quede prensado y no se suelte solo, se le restara un punto por el conteo  

El ataque tiene que ser ejecutado en un lapso de dos segundos, despues del lapso de 2 segundos su ataque contara como un ¨extend punch¨ 

Si se ejecuta un ¨extend punch¨ y este bota una bandera, no contara la bandera botada y se reincorporara al robot que la perdio 

Despues de propiciar al rival 3 ¨extend punch¨ se hara un rebajo de un punto 

Agradecimientos
Universidad Cenfotec por darnos la oportunidad de hacer la pasantía 
Gabriela Urbina Hernández y Tomás De Camino Beck por su colaboración en la elaboración del proyecto
Ronald Fallas Rojas Profesor a cargo



  

  

  

  
