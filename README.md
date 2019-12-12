# Cacerola-Bot
Cacerola Bot usando Arduino - Creado por Ideo Maker

<img src="https://github.com/ideomaker/Cacerola-Bot/blob/master/img/cacerola-esquema.png" />


<img src="https://github.com/ideomaker/Cacerola-Bot/blob/master/img/cacerola-gif.gif" />

Código:

```C++
/*
Codigo CacerolaBot

Ideo Maker
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
grados1 = 23; //Grados Servo
motor1.write (grados1);
delay(150); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(100); //Tiempo de Espera

//Golpe 4
grados1 = 23; //Grados Servo
motor1.write (grados1);
delay(150); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(100); //Tiempo de Espera

//Golpe 5
grados1 = 23; //Grados Servo
motor1.write (grados1);
delay(150); //Tiempo de Espera
grados1 = 0; //Grados Servo
motor1.write (grados1);
delay(400); //Tiempo de Espera
}
```
