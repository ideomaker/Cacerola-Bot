# Cacerola-Bot
Cacerola Bot usando Arduino - Creado por Ideo Maker

<img src="https://github.com/ideomaker/Cacerola-Bot/blob/master/img/cacerola-esquema.png" />


<img src="https://github.com/ideomaker/Cacerola-Bot/blob/master/img/cacerola-gif.gif" />

## Materiales:

- Arduino UNO ![](https://fablabolmue.cl/_files/200000510-0a5a80b516/arduino-uno-r3-8.jpg)

- Servo Motor SG90 ![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvaiAum8GfJMFVFnVa3TjRY0og04VB7fzi8_vmW8K3mBXcTaqn&s)

- Jumpers Macho - Macho ![](https://img.clasf.mx/2019/08/16/Cable-Jumpers-Dupont-M-m-65-Pzas-Protoboard-Arduino-20190816022429.5678570015.jpg)




### Código:

--------

```C++
/*
Codigo CacerolaBot
Creado por Ideo Maker
www.ideomaker.cl
*/

#include <Servo.h> // Libreria Servo
Servo motor1;
int grados1 = 0; // Valor de Origen del Servo

void setup() {
motor1.attach (9); // Pin Señal Servo
}
void loop()
{

//Golpe 1
grados1 = 25; //Grados Servo
motor1.write (grados1);
delay(80); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(400); //Tiempo de Espera

//Golpe 2
grados1 = 22; //Grados Servo
motor1.write (grados1);
delay(80); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(420); //Tiempo de Espera

//Golpe 3
grados1 = 20; //Grados Servo
motor1.write (grados1);
delay(150); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(100); //Tiempo de Espera

//Golpe 4
grados1 = 20; //Grados Servo
motor1.write (grados1);
delay(150); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(100); //Tiempo de Espera

//Golpe 5
grados1 = 20; //Grados Servo
motor1.write (grados1);
delay(150); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(400); //Tiempo de Espera
}
```
