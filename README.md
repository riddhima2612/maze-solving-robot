# maze-solving-robot
Obstacle Avoidance Robot using Arduino
A robot designed to autonomously detect and avoid obstacles using ultrasonic sensors and motor control. This project is implemented using Arduino and features real-time obstacle detection and decision-making for navigation.

Key Features:
Uses ultrasonic sensors for distance measurement on three sides (front, left, and right).
Implements obstacle detection and avoidance logic to navigate safely.
Controls motors through an H-Bridge for smooth movement and direction changes.
Adjustable parameters for distance threshold and motor speed.
Technologies and Components:
Microcontroller: Arduino Uno (or compatible board)
Sensors: Ultrasonic sensors (e.g., HC-SR04)
Motor Driver: L298N H-Bridge
Programming: Arduino C/C++
How It Works:
Ultrasonic sensors measure distances to detect obstacles in the path.
The robot decides to turn left, right, or reverse based on sensor input.
Motors are controlled to execute movement commands in real-time.
