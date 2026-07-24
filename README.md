# Servo Control System Using a Potentiometer

## Overview

This project demonstrates how to control the position of an SG90 servo motor using a 10kΩ potentiometer and an Arduino Uno. As the potentiometer is rotated, the Arduino reads the analog input and maps it to a servo angle between 0° and 180°, allowing for smooth, real-time control.

## Features

- Real-time servo position control
- Analog input using a potentiometer
- Smooth 0°–180° servo movement
- Simple and beginner-friendly Arduino project

## Components Used

- Arduino Uno
- SG90 Servo Motor
- 10kΩ Potentiometer
- Breadboard
- Jumper Wires
- USB Cable

## Wiring

### Servo

| Servo Wire | Arduino |
|------------|----------|
| Brown | GND |
| Red | 5V |
| Orange | Digital Pin 9 |

### Potentiometer

| Potentiometer Pin | Arduino |
|-------------------|----------|
| Outer Pin | 5V |
| Middle Pin | A0 |
| Outer Pin | GND |

## How It Works

The Arduino continuously reads the voltage from the potentiometer using analog pin A0. The analog value (0–1023) is 
converted into an angle between 0° and 180° using the `map()` function. The calculated angle is then sent to the SG90 servo, 
causing it to rotate to the corresponding position.

## Learning Outcomes

Through this project I learned:

- How analog sensors work with Arduino
- How to read analog values using `analogRead()`
- How to control a servo motor using the Servo library
- How to convert sensor data into mechanical movement using the `map()` function
- Basic breadboard wiring and circuit assembly

## Author

-Eyad

