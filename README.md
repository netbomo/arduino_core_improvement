# arduino_core_improvement

This is a small improvement for the arduino core.

It permit to use the timer2 for micro and millis fonction and free the timer0.

It's writed on core from arduino 1.6.20 because I'm using the IDE sloeber 4.2.

## use it
To use it copy wiring.c and Arduino.h in your arduino/hardware/avr/1.6.20/cores/arduino/ repository.

Uncomment the line 65 : #define CORE_USE_TIMER2

Have fun.