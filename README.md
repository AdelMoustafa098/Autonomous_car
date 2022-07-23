# Overview
This is a team-based project, Cairo University, 2021 Class.

# Files description: 
1) "arduino_code.ino": is the code used to receive orders from the ESP chip and move the motors.
2) "esp_code.ino": is the code used to connect to each of the android applications and python code and depending on the received data the ESP sends the order to Arduino to move the car.
3) "Processor.py": is the code used to receive the image from the web socket server (android phone) and do image processing on the recovered image to detect lanes, and sends to the ESP chip the angel of movements.
4) "Auto_pilot_mode.": is the android application which is used to open the camera and
Creates a web socket server on the android phone, and sends the frames whenever the clients 
Requests it, up to 15 frames per second.	
5) "CarsRemoteControl": is the android application that is used to send orders to the ESP to
 control the car as a remotes control.
6) "client": is a plus android application that is used to receive images that are sent from the
"Auto_pilot_mode.rar" application to see the same images which are sent to the python code.

# Demo
You can watch the demo [here](https://www.youtube.com/watch?v=p4k6ANMX9f0)
