# Morse-Encoder (Arduino)

## About  
A simple Morse-code encoder that — given a text input — converts it into Morse code and outputs signals via an LED and a buzzer.  
This project is implemented using Arduino, and demonstrates basic text-to-Morse translation and signaling.

## Features  
- Convert alphabetic and numeric text to Morse code  
- Output via LED blink and buzzer sound  
- Easy to extend / modify for additional features (e.g. different output methods, adjustable timing)  

## Hardware Requirements  
- Arduino board (e.g. Arduino Uno / Nano)  
- LED (with appropriate resistor)  
- Buzzer / Piezo speaker  
- (Optional) Power supply / USB for Arduino  

## Software Requirements  
- Arduino UNO  

## Usage / How to Use  

1. Connect the LED and buzzer to the designated Arduino pins.  
2. Upload the provided code (e.g. `morse1.ino`) to the Arduino.  
3. Open Serial Monitor (if required) and send the desired text input.  
4. The Arduino will blink the LED and sound the buzzer according to the Morse-code representation of the input text.
