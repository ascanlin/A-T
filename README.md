#include <Servo.h>

Servo myservo;

void setup() {
  myservo.attach(10);
  myservo.write(0); // Move servo to position 0 when the code is reset
}

void loop() {
  myservo.write(90);
  // Add any other code you need to run repeatedly in the loop
}
