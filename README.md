# Propuesta Battlebot CTPO para Universidad CENFOTEC
Nuestra propuesta consiste en investigar sobre las competencias de robots, definir un reglamento de juego y diseñar  2 robots (uno con mazo y otro con una sierra) utilizando impresión 3D y corte lasér CNC, a demás, crear el diseño del dojo e implementar un control remoto  por medio de ESP Now.
Para nuestros Battlebots nos inspiramos en este vídeo: https://www.youtube.com/watch?v=1lOikKyGHfs 



Prototipo 1   


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



![image](https://github.com/user-attachments/assets/01155925-a228-4bae-82c7-e5e050c6d4ef)




Ruedas


70mm Wheel 1 pair ( works with DG01D gearmotors) 

Rueda de 70mm x 2





![image](https://github.com/user-attachments/assets/be1d01f8-a430-4b58-9cb9-5af552666882)



Board



El IdeaBoard es un tablero educativo de desarrollo de Robótica e Internet de las Cosas creado por CRCibernetica.com en Costa Rica.


Caracteristicas

ESP32-WROOM-32E microcontroller
        ◦ 32bits @ 240MHz
        ◦ 3.3V logic
        ◦ 520KB SRAM
        ◦ 8MB FLASH
        ◦ WIFI 802.11b/g/n
        ◦ Bluetooth V4.2 BR/EDR y Bluetooth LE
    • Dual H-Bridges for motor control (800mA for each motor)
    • Multi-color programmable RGB LED (WS2812B)
    • Programmable using CircuitPython/Micropython or the Arduino IDE (C/C++)
    • USB-C interface for programming and debugging (CH340G serial converter)
    • Standard .1" headers for convenient interfacing with GND and Vcc for each pin
    • STEMMA/QWIIC 4-pin interface for easy connections to Adafruit and Sparkfun i2c modules
    • Direct DC power for battery or power supply (5VDC - 9VDC)
    • 7 pins for servos or other applications that require direct power
    • 14 General Purpose I/O pins in total (7 direct power -- 7 with 3.3v logic)

