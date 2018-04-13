# Plant Minder
Build an internet connected soil moisture meter.

## IoT Skills
* General wiring/soldering
* Analog sensors
* Arduino/ESP8266 development on PlatformIO


## Supplies Needed
* 1 Micro USB Cable
* 1 [ESP8266 Development Board](https://www.amazon.com/HiLetgo-Internet-Development-Wireless-Micropython/dp/B010O1G1ES)
* 1 [Soil Moisture Sensor](https://www.amazon.com/Hygrometer-Humidity-Detection-Moisture-Arduino/dp/B01N06BLR2)

## Useful References
* [Arduino analog input tutorial](https://www.arduino.cc/en/Tutorial/AnalogInput)
* [Node MCU Pinout](https://github.com/verypossible/very_iot_toolkit/blob/master/esp8266/nodemcu_pins.png)

## General Guidance
* Set up a [PlatformIO](http://docs.platformio.org/en/latest/) project in the
[already created repository](https://github.com/verypossible/plant_minder).
* Determine how to connect your soil moisture meter to your development board.
* Build some firmware that prints your moisture readings to the serial monitor.
* Get your device online via wifi credentials compiled into the firmware.
* Post data to a test endpoint such as: http://httpbin.org/post
* Pass wifi credentials a build flag or via a templated `secrets.h`
* Experiment with a status LED and/or button for a user interface.
* Get fancy with wifi configuration, building a backend, or using something like
[Home Assistant](https://www.home-assistant.io/) as a backend.


