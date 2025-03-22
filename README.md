MiniMech - A Multifunctional Humanoid Robot

Overview

MiniMech is a multifunctional humanoid robot designed to perform basic human-like gestures and interact with its environment through various sensors. The robot integrates environmental monitoring, gesture-based control, and obstacle detection to enhance automation and human-robot interaction.

Features

Sensor Integration: Equipped with DHT11 (temperature & humidity), PIR motion sensor, ultrasonic sensor (obstacle detection), and MQ2 gas sensor (air quality monitoring).

Human-like Gestures: Powered by 7 servo motors, MiniMech can wave, point, and lift its arms dynamically.

Bluetooth Control: Wireless control via a smartphone application for remote operation.

LCD Display: Provides real-time feedback on sensor data, such as environmental conditions and system status.

Home Security & Assistance: Detects motion, monitors air quality, and assists in daily tasks with interactive gestures.

Components Used

Microcontroller: Arduino Mega 2560

Sensors:

DHT11 (Temperature & Humidity)

PIR Motion Sensor

Ultrasonic Sensor

MQ2 Gas Sensor

Actuators:

7 Servo Motors

DC Motors for mobility

Communication: HC-05 Bluetooth Module

Display: 16x2 LCD Screen

Power Supply: External battery or adapter

Installation & Setup

Hardware Setup: Assemble the components according to the circuit diagram provided in the project documentation.

Software Requirements:

Arduino IDE

Required Libraries: Servo.h, LiquidCrystal_I2C.h, DHT.h

Upload Code: Flash the provided Arduino sketch onto the Arduino Mega 2560.

Mobile Control: Use a Bluetooth terminal app to send commands to the robot for remote operation.

Usage

Power on the MiniMech humanoid robot.

Monitor environmental conditions through the LCD display.

Control the robot’s gestures and movements using the mobile app via Bluetooth.

Observe obstacle detection and automated motion responses.

Applications

Personal Assistance: Helps in basic household tasks.

Security: Monitors motion and air quality, providing alerts.

Education & Research: Demonstrates robotics and IoT concepts.

Future Enhancements

AI & Machine Learning: Improve decision-making and autonomous behavior.

Speech Recognition: Enable voice command control.

Advanced Navigation: Implement path planning for better mobility.
