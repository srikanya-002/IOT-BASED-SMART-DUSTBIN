# IOT-BASED-SMART-DUSTBIN
This project measures an object's distance using an ultrasonic sensor (HC-SR04), which then automatically activates a servo motor when the object enters a predetermined range. Based on the time it takes for the ultrasonic pulse to return to the sensor, the system calculates distance using the theory of sound wave reflection.

The mechanism turns on if the measured distance is less than 30 cm:

A pin on a digital output becomes HIGH.

Servo motor rotation (e.g., 190°)

The motor returns to its starting position after a delay.
