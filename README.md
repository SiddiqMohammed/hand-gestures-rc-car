# hand-gestures-rc-car
The project is also known as "MAGIC", which stands for "Motion Activated and Gesture Initiated control"





This project was built upon the hand gesture code written by Sadaival [https://github.com/Sadaival/Hand-Gestures]
Libraries used in the project - openCV, & Serial


Controlling an rc car using just jand gestures in front of a webcam

The goal of this project was to make control a remote controlled car using nothing but hand gestures in front of the camera.

The goal was achieved using openCV & Python to recognise the hand gestures and then sending this data over to the Arduino wirelessly which then controls the car.

A custom Radio transmitter and receiver was built for communicating between the car and the arduino and thus the radio signals work well in traffic and upto a range of 25m [that's the max we've tested]

