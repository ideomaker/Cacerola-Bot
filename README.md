# Cacerola-Bot
Cacerola Bot usando Arduino - Creado por Ideo Maker

<img src="https://github.com/ideomaker/Cacerola-Bot/blob/master/img/cacerola-esquema.png" />


<img src="https://github.com/ideomaker/Cacerola-Bot/blob/master/img/cacerola-gif.gif" />

Código:

```CSS
#include <Servo.h>
Servo motor1;
int grados1 = 0;
void setup() {
motor1.attach (9);
}
void loop()
{
grados1 = 25;
motor1.write (grados1);
delay(80);
grados1 = 0;

motor1.write (grados1);
delay(400);
grados1 = 25;
motor1.write (grados1);
delay(80);
grados1 = 0;
motor1.write (grados1);
delay(420);
grados1 = 12;
motor1.write (grados1);
delay(150);
grados1 = 0;
motor1.write (grados1);
delay(100);
grados1 = 12;
motor1.write (grados1);
delay(150);
grados1 = 0;
motor1.write (grados1);
delay(100);
grados1 = 12;
motor1.write (grados1);
delay(150);
grados1 = 0;
motor1.write (grados1);
delay(400);
}
```
