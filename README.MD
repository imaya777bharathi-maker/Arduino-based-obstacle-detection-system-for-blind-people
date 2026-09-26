# WAVE RIDERS

# 

# Arduino-Based Obstacle Detection System for Blind People

## 1\. Statement

Visually impaired people may face difficulty detecting obstacles while walking. This project uses an Arduino Uno and an ultrasonic sensor to detect nearby obstacles and provide a visual indication using LEDs. It demonstrates a simple, low-cost obstacle detection system that can be further developed into an assistive device.

## 2\. Materials Required

Arduino Uno  
HC-SR04 Ultrasonic Sensor  
Green LED  
Orange LED  
2 × Resistors  
Breadboard  
Jumper wires  
USB cable / power supply

## 3\. Procedure

Connect the HC-SR04 ultrasonic sensor to the Arduino Uno.  
Connect the green and orange LEDs through suitable resistors.  
Upload the Arduino program to measure the distance of nearby objects.  
Continuously monitor the distance detected by the ultrasonic sensor.  
When the path is clear, the green LED indicates normal conditions.  
When an obstacle comes within the programmed distance, the orange LED provides a warning.  
The system can be mounted on a walking stick or wearable device for practical use.

## 4\. Notes

The ultrasonic sensor measures distance using ultrasonic sound waves.  
LED indication provides a simple visual demonstration; for real-world use by blind people, it can be extended with a buzzer or vibration motor.  
The detection range and warning distance can be adjusted through the Arduino program.  
This prototype is intended as an assistive technology demonstration, not a certified safety device.  
Future upgrades can include vibration feedback, voice alerts, rechargeable power, and a compact wearable design.

