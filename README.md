# Arduino 3 Buttons and 3 LEDs Project

This is a simple Arduino circuit simulation created on [Tinkercad](https://www.tinkercad.com/things/ayZ6CnrMXzN-arduino-3-buttons-3-leds?sharecode=0m-7-naTe1vmDzvx1tMi3w2zJYxrUtvjW7npNn9JzgM).

## Project Overview

The project demonstrates how to control three individual LEDs using three separate push buttons connected to an Arduino Uno. When a button is pressed, the corresponding LED lights up.

## Components Used

- Arduino Uno  
- 3 Push Buttons  
- 3 LEDs (different colors)  
- 3 Resistors (for LEDs, usually 220Ω)  
- 3 Pull-down resistors (10kΩ) for buttons  
- Breadboard and jumper wires  

## How It Works

- Each button is connected to a digital input pin on the Arduino, with a pull-down resistor to ensure the input reads LOW when the button is not pressed.  
- Each LED is connected to a digital output pin with a current-limiting resistor.  
- Pressing a button sets the corresponding input pin HIGH, turning the associated LED ON.

## Arduino Pin Assignments

| Button Pin | LED Pin |  
|------------|---------|  
| 2          | 8       |  
| 3          | 9       |  
| 4          | 10      |  

## Arduino Code Summary

- Reads the state of each button using `digitalRead`.  
- Turns ON or OFF the corresponding LED using `digitalWrite`.

## Usage

1. Open the project on Tinkercad using the link above.  
2. Start the simulation.  
3. Press any of the three buttons to see the corresponding LED light up.

## Learning Outcomes

- Understanding digital input and output in Arduino.  
- Using buttons as input devices with pull-down resistors.  
- Controlling LEDs with Arduino pins.  
- Basic circuit building and simulation in Tinkercad.
