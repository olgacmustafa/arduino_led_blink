# Arduino LED On Project

This is a simple Arduino project that turns an LED on using digital pin 8. It demonstrates how to control a digital output pin on an Arduino board.

## Components Used
- Arduino Uno (or compatible board)
- 1x LED
- 1x 220 ohm resistor
- Breadboard and jumper wires

## Circuit Diagram
The longer leg (anode) of the LED is connected to pin 8 through a 220 ohm resistor. The shorter leg (cathode) is connected to GND.

## Code
```cpp
int led1=8;
void setup() {
  pinMode(led1, OUTPUT);
}

void loop() {
  digitalWrite(led1, HIGH); // Turn the LED on
  delay(1000);
  digitalWrite(led1,LOW);
  dealy(1000);
}

