# Object_detection_alarm
The system uses an ultrasonic sensor to detect objects within a specified distance. If an object is detected within the defined safety distance, a buzzer is activated along with an LED, signaling that the object is too close.

Code Explanation:
The code is written in C++ using the Arduino framework. It configures the ultrasonic sensor to measure the distance of nearby objects. If the object is detected within the safety distance (e.g., 8 cm), the buzzer and LED are turned on to signal the detection. The measured distance is also printed to the Serial Monitor for real-time monitoring.

Setup:
1.Connect the ultrasonic sensor, buzzer, and LED to the Arduino as per the pin configuration.
2.Upload the provided code to the Arduino using the Arduino IDE.
3.Open the Serial Monitor to view the distance measurements.
4.The system will alert when an object is within the safety distance.
