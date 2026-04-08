#include <Servo.h>

Servo servo1; // naming as servo1
Servo servo2; // naming as servo2 

int pos1 = 0;   // angle of the 1st servo
int pos2 = 180;  // angle of the 2nd servo

void setup() {
  servo1.attach(9);  // pin servo1 is attached
  servo2.attach(10); // pin servo2 is attached 

}

void loop() {
  // servo1 moves forward, servo2 moves backward
  for(int i = 0; i <= 180; i += 5){
    servo1.write(i);      // angle increased in servo1
    servo2.write(180-i);  // angle reduced in servo2
    delay(25);            // pace of the servo movement
  }

  // servo1 moves backward, servo2 moves forward
  for(int i = 180; i >= 0; i -= 5){
    servo1.write(i);       // angle reduced in sero1
    servo2.write(180-i);   // angle increased in servo2
    delay(25);             // pace of servo movement
  }
} // servo needs 5v to operate
