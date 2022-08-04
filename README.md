# IoT Project

This is a collection of complete code to use in interfacing Arduino/NodeMCU/ESP8266 with various sensors

The basic templates are taken from the Arduino IDE and are modified for various IoT, Robotics and mechanical projects.
These projects are suitable for a home or apartment complex.

MQTT is the protocol used for communicating between the clients and sensors. Adafruit provides a free MQTT broker with impressive features to monitor, track and control your sensors and devices. Visit <https://io.adafruit.com> for more information.

Many of the methods used here require downloading and including the ESP8266Wifi, Adafruit_MQTT and Adafruit_MQTT_Client libraries in your Arduino IDE.

<h2>Contents</h2>
1. <a href="https://github.com/CraftyWiz/ESP-Projects/blob/main/MQ9.ino">MQ Sensors</a> - Uses the MQ series of gas sensors to detect and measure the quantity of smoke and impurities (depending on the model of the sensor) present in the air. This example uses the MQ-9 sensor but any sensor would work on making appropriate changes to the threshold value.
2. <a href="https://github.com/CraftyWiz/ESP-Projects/blob/main/MQ9.ino">PIR Motion Sensors</a> - Uses the PIR motion sensor to detect motion in the terrace. Will send a signal to the cloud when motion is detected and subsequently, when it ends. <br>
3.  <a href="https://github.com/CraftyWiz/ESP-Projects/blob/main/MQ9.ino">nodeMCU</a> - The project uses the nodeMCU as the microcontroller 


