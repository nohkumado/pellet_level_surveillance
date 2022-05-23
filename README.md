# pellet level surveillance

A system to keep an eye on the level of a pellet tank, 
as sensor we will use a HC SR04 (cheap) Ultrasonic sensor, that will need to be protected from
dust with e.g. a SG90 servo driven cover.

For piloting the whole thing, an ESP32 that transmits the data back through MQTT.

To draw the diagram , please use something like fritzing

using:

- [HC SR04 mockup](https://github.com/nohkumado/sensor_cases)
- [Servo mockup](https://github.com/ledalert/cadmodel-sg90)

tutorials:

- [MQTT and ESP32 tutorial](https://randomnerdtutorials.com/esp32-mqtt-publish-subscribe-arduino-ide/) 
- [SG90 and ESP32 tutorial](https://www.techcoil.com/blog/how-to-control-a-servo-motor-with-an-esp32-development-board/)

tech information:

- [distance sensors](https://www.seeedstudio.com/blog/2019/12/23/distance-sensors-types-and-selection-guide/)
- [Esp32 VL53L1X(4m version) demo](https://github.com/Tollbringer/Esp32_8266-VL53L1X-demo)

cheating:

- https://nerdiy.de/howto-espeasy-vl53l0x-vl53l1x-distanzsensor-an-den-esp8266-esp32-anschliessen-und-auslesen/
