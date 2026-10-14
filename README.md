# Air Defense System — DIY Arduino

## Overview

This project is an Arduino-based educational simulation of an air defense system. It detects and tracks a moving light source using light-dependent resistors (LDRs), adjusts a launcher model with servo motors, and provides visual and audio alerts when the light intensity exceeds a predefined threshold.

## How It Works

1. **Light Detection:** Four LDR sensors measure light intensity from different directions.
2. **Target Tracking:** The Arduino compares sensor readings to determine the light source's direction.
3. **Servo Control:** Two servo motors adjust the launcher model horizontally and vertically to follow the light.
4. **Distance Measurement:** An HC-SR04 ultrasonic sensor measures the distance to an object and reports it through the Serial Monitor.
5. **Emergency Alerts:** When the average light reading exceeds the configured threshold, a red LED and buzzer activate, and the LCD displays an emergency warning.

## Technologies and Components

- **Microcontroller:** Arduino Uno
- **Programming Language:** Arduino C
- **Sensors:** Four LDRs, HC-SR04 ultrasonic sensor
- **Actuators:** Two servo motors
- **Output Components:** 16×2 LCD, red LED, buzzer
- **Electronics:** Breadboard, resistors, jumper wires
- **Libraries:** Servo, LiquidCrystal

## Key Features

- Directional light detection using four LDR sensors.
- Horizontal and vertical tracking using servo motors.
- Real-time ultrasonic distance measurement.
- LCD status messages and emergency warnings.
- Audio and visual alerts based on light intensity.
- Serial Monitor output for sensor readings and distance measurements.

## Project Objectives

- Demonstrate the integration of sensors, actuators, and embedded programming.
- Explore automated tracking using sensor feedback.
- Implement basic alert mechanisms with electronic components.
- Apply Arduino programming to a practical robotics and electronics project.

## Limitations and Future Improvements

- Implement and test distance-based response logic more fully.
- Improve tracking accuracy and servo movement limits.
- Add filtering to reduce sensor noise and unnecessary movement.
- Improve the LCD interface and system status reporting.
- Extend the simulation with more advanced control logic.
