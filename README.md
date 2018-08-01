# Arduino-Sonar-Radar
## Overview
This Arduino Project just uses an Ultrasonic Sensor for detecting the objects, a small hobbyist Servo Motor for rotating the sensor and an Arduino Board for controlling them. 

## Components Used:
* Ultrasonic sensor HC
* Servo Motor
* Arduino Board
* Breadboard and Jump Wires

## Circuit Schematics

![alt text][circuit]

[circuit]: https://github.com/yashgoenka/Arduino-Sonar-Radar/blob/master/Arduino%20Radar%20Circuit%20Github.png

## How does it work

### Arduino Board Code
*The github source code for the Arduino Board has description for each line.*
*Check out Arduino_Radar_servo/Arduino_Radar_servo.ino*

### Processing IDE Code
The program will receive the values for the angle and the distance measured by the sensor from the Arduino Board into the Processing IDE using the SerialEvent() function which reads the data from the Serial Port and we will put the values of the angle and the distance into the variables iAngle and iDistance. These variable will be used for drawing the radar, the lines, the detected objects and some of the text.

![alt text][live_data]

[live_data]: https://github.com/yashgoenka/Arduino-Sonar-Radar/blob/master/live_data.png

## Video of Radar in operation

*the video is yet to be made*
