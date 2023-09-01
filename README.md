# Ultrasonic-Distance-Measurement-raspberry-pi
Ultrasonic distance measurement is a popular method for measuring distances using a Raspberry Pi. This can be done using an ultrasonic sensor, such as the HC-SR04, which is relatively inexpensive and easy to interface with a Raspberry Pi. Here's a step-by-step guide to setting up ultrasonic distance measurement with a Raspberry Pi:

Hardware Required:

Raspberry Pi (any model with GPIO pins)
HC-SR04 Ultrasonic Sensor
Jumper wires
Breadboard (optional)
Software Required:

Raspbian or Raspberry Pi OS installed on your Raspberry Pi
Python (pre-installed on most Raspberry Pi OS versions)
Step 1: Wiring the Ultrasonic Sensor
Connect the HC-SR04 ultrasonic sensor to your Raspberry Pi as follows:

VCC to 5V (Pin 2 or Pin 4)
Trig to GPIO (e.g., GPIO23, Pin 16)
Echo to GPIO (e.g., GPIO24, Pin 18)
GND to Ground (Pin 34)
Make sure the connections are secure.
![image](https://github.com/AhMedMubarak20/Ultrasonic-Distance-Measurement-raspberry-pi/assets/76844219/672c0d2a-d2f4-42fa-9c5b-b9a5bf7e232f)

Step 2: Python Script for Distance Measurement

Here's a Python script that uses the RPi.GPIO library to measure distances using the ultrasonic sensor. Create a Python file (e.g., ultrasonic_distance.py) and paste the following code:

python Code.

Step 3: Run the Script
Save the script and run it using the following command:

bash:
python ultrasonic_distance.py
The script will continuously measure the distance and display it in centimeters.

Keep in mind that this is a basic example. You can modify the script to suit your specific needs, such as incorporating it into a project or adding more features. Additionally, you may need to install the RPi.GPIO library if it's not already installed on your Raspberry Pi. You can do this with the pip command:

bash:
pip install RPi.GPIO
Remember to power off your Raspberry Pi and ensure proper connections before starting the project.
