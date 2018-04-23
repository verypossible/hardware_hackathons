# Verybot IRL
Build a two-wheeled robot that avoids obstacles.

## IoT Skills
* General wiring/soldering
* Digital Inputs/Outputs
* DC motor control via PWM
* Elixir/Nerves development on the RPi3


## Supplies
* 1 [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)
* 1 [Adafruit Robot Chassis Kit](https://www.adafruit.com/product/2939)
* 1 [Adafruit Stepper and DC Motor Hat](https://www.adafruit.com/product/2345)
* N [Ultrasonic Rangefinders](https://www.amazon.com/HC-SR04-Ultrasonic-Distance-MEGA2560-ElecRight/dp/B01MA4O5G5/)
* 1-2 [Battery Packs](https://www.adafruit.com/product/830)
* 1 [DC Voltage Regulator](https://www.amazon.com/4-PACK-LM2596-DC-DC-Adjustable-Converter/dp/B07BF8SSY5)


## Useful References
* [Adafruit Motor Hat Tutorial](https://learn.adafruit.com/adafruit-dc-and-stepper-motor-hat-for-raspberry-pi)
* [Adafruit Robot Tutorial](https://learn.adafruit.com/bluefruit-feather-robot/overview) -- substitute RPI for feather where applicable
* [RPi Ultrasonic Sensor Tutorial](https://www.modmypi.com/blog/hc-sr04-ultrasonic-range-sensor-on-the-raspberry-pi)

## General Guidance
* Set up a [Nerves](https://hexdocs.pm/nerves/getting-started.html) project in the
[already created repository](https://github.com/verypossible/verybot_irl).
* Start by using a current limited power supply instead of batteries.
* Connect your hardware as recommended in the various tutorials above
project.
* Begin by driving a motor forward/backward via the motor driver hat.
* Determine how to interpret data from ultrasonic range sensor.
* Control motors based on range finder data.
* Make the robot mobile with batteries/voltage regulators.


