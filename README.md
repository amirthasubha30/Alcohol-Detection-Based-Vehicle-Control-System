
Alcohol Detection Based Vehicle Control System
Overview
This project aims to create a system for controlling vehicle speed based on alcohol detection. The system utilizes an Arduino board along with various sensors to monitor vehicle count, detect alcohol presence, and adjust speed limits accordingly.

Hardware Requirements
Arduino board (Uno, Nano, etc.)
IR sensor module
Rain sensor module
Liquid Crystal Display (LCD) with I2C interface
Jumper wires
Resistors
Software Requirements
Arduino IDE
LiquidCrystal_I2C library
Installation Instructions
Connect the IR sensor module to the digital pin 2 of the Arduino board.
Connect the Rain sensor module to the digital pin 4 of the Arduino board.
Connect the LCD display with I2C interface to the Arduino board.
Install the LiquidCrystal_I2C library in the Arduino IDE.
Upload the provided code to the Arduino board.
Usage
Ensure all connections are properly set up.
Power on the Arduino board.
The LCD display will show the count of vehicles and the current speed limit.
The system monitors the IR sensor to count vehicles passing by.
If alcohol is detected by the IR sensor, the system increments the count and adjusts the speed limit accordingly.
If the road is wet, the system automatically reduces the speed limit to 50 km/h.
Monitor the LCD display for real-time updates on vehicle count and speed limit.
Code Explanation
The code initializes the IR sensor, rain sensor, and LCD display.
It continuously loops to monitor vehicle count and adjust speed limits based on the count.
If alcohol is detected, the count is incremented, and speed limits are adjusted.
If the road is wet, the speed limit is set to 50 km/h.
Real-time updates are displayed on the LCD.
