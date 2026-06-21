# Arduino Assignment 1 — Smart Countdown

Assignment 1 submission for Programming C++ for Engineers Using Arduino, Ghana Communication Technology University (GCTU).

## What this program does

Counts down from 5 to 1 using a while loop. No shortcuts, no copy-paste — every line typed and tested by hand.

On each step:
- Prints "Count: N" to the Serial Monitor.
- Blinks the on-board LED N times via a function I wrote, flashLED(int times).

When the countdown hits 0, it prints "=== Countdown Complete ===" and stops.

## Concepts demonstrated

- Variables (int)
- Functions with parameters (flashLED)
- The while loop
- Digital output (digitalWrite, pinMode)
- Serial communication (Serial.begin, Serial.print, Serial.println)

## How to run it

1. Open the .ino file in the Arduino IDE.
2. Connect an Arduino Uno via USB.
3. Tools > Board > Arduino Uno, then select the correct Port.
4. Upload, then open Tools > Serial Monitor at 9600 baud.

## Author

Emmanuel Vondee  2526403735, BCE Level 100A, Faculty of Engineering, GCTU
