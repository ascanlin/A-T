#include <Servo.h>

Servo myservo;


void setup() {
  myservo.attach(10);

//  pinMode(buttonPin, INPUT);
}

void loop() {
  //(digitalRead(buttonPin) == HIGH) {
    myservo.write(180);
  // }else {
  //   myservo.write(180);
  // }
}
