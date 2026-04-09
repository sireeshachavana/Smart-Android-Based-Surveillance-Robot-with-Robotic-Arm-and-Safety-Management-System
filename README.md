# Smart-Android-Based-Surveillance-Robot-with-Robotic-Arm-and-Safety-Management-System
This project focuses on designing and developing a smart surveillance robot that can be controlled using an Android device. The system integrates multiple safety and monitoring features such as fire detection, metal detection, and real-time video surveillance. 
A Wi-Fi camera module is used to provide live video streaming, allowing the user to monitor remote or hazardous environments in real time. The robot can be controlled wirelessly through a mobile application.
For safety management, a flame sensor is used to detect fire. When fire is detected, the system automatically activates a water pump using a relay module to extinguish it. A metal detector is also included to identify metallic objects, which can be useful in security or military applications.
The robot is equipped with a robotic arm, enabling it to pick and place objects in risky or unreachable areas. Motors and motor drivers (such as L298N) are used for movement and control of wheels and arm mechanisms.
A buck converter is used to regulate voltage and ensure proper power distribution to different components. The system is designed to operate efficiently with battery power, making it portable and suitable for real-world applications.
Overall, this project provides an advanced solution for surveillance, hazard detection, and emergency response, reducing human risk in dangerous environments such as fire accidents, industrial zones, and security operations.
# Introduction
This project is designed to develop a multi-functional surveillance robot that can monitor environments, detect hazards, and respond automatically. It helps reduce human effort and risk in dangerous situations like fire accidents, security threats, and industrial hazards.
# Objectives
To design a wireless surveillance robot using ESP32
To provide live video monitoring through a mobile device
To detect fire using a flame sensor
To automatically control a water pump using relay
To detect metal objects for security purposes
To implement a robotic arm for object handling
To ensure proper power management using a buck converter
# Components Used
ESP32 Microcontroller
Wi-Fi Camera (e.g., Imou camera / ESP camera)
Flame Sensor
Metal Detector Sensor
Relay Module
L298N Motor Driver
DC Motors (for movement)
Submersible Water Pump
Robotic Arm (Servo Motors)
Battery
Buck Converter
Connecting Wires & Breadboard
# Working Principle
The ESP32 controls the entire system.
The robot is controlled through an Android application via Wi-Fi
The camera provides real-time video streaming
When the flame sensor detects fire, it sends a signal to ESP32
ESP32 activates the relay module, which turns ON the water pump
The metal detector identifies metallic objects and sends alerts
The robot moves using motors controlled by L298N motor driver
The robotic arm performs pick-and-place operations
The buck converter regulates voltage to protect components
