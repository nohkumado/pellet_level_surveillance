# pellet level surveillance

A system to keep an eye on the level of a pellet tank, 
as sensor we will use a HC SR04 (cheap) Ultrasonic sensor, that will need to be protected from
dust with e.g. a SG90 servo driven cover.

For piloting the whole thing, an ESP32 that transmits the data back through MQTT.

using:

- [HC SR04 mockup](https://github.com/nohkumado/sensor_cases)
- [Servo mockup](https://github.com/ledalert/cadmodel-sg90)
- [MQTT and ESP32 tutorial](https://randomnerdtutorials.com/esp32-mqtt-publish-subscribe-arduino-ide/) 
