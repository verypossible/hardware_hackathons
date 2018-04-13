# MQTT Multisensor
Build an multisensor which sends its data to an MQTT broker.

This is a clone of the
[ESP MQTT JSON
Multisensor](https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor)
project, which is a great idea, but could use improvement.

## IoT Skills
* General wiring/soldering
* Analog sensors
* Digital sensors
* LED control via PWM
* MQTT messaging protocol
* Arduino/ESP8266 development on PlatformIO


## Supplies/Useful References
* See [ESP MQTT JSON
Multisensor](https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor)


## General Guidance
* Set up a [PlatformIO](http://docs.platformio.org/en/latest/) project in the
[already created repository](https://github.com/verypossible/mqtt_multisensor).
* Connect all your hardware as described in the [ESP MQTT JSON
Multisensor](https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor)
project.
* For each input, write a simple version of firmware that prints the sensor
value to the serial console.
* Get your device online via wifi credentials compiled into the firmware.
* Send your MQTT data to the office [Home Assistant](https://www.home-assistant.io/) MQTT broker.
* Pass wifi credentials a build flag or via a templated `secrets.h`
* Get fancy with a configuration web interface which saves the wifi credentials,
and any other configuration options.


