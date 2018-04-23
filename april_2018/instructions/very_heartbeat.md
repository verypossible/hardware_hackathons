# Very Heartbeat
Build an LED matrix which visualizes company slack activity via the slack real
time API.


## IoT Skills
* General wiring/soldering
* Digital Inputs/Outputs
* LED matrix control via digital multiplexing
* Elixir/Nerves development on the RPi3


## Supplies
* 1 [Raspberry Pi 3](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/).
* 1 [LED Matrix Driver Hat](https://www.adafruit.com/product/2345)
* 1 [LED Matrix Display](https://www.adafruit.com/product/2026)

## Useful References
* [Adafruit LED Matrix Tutorial](https://learn.adafruit.com/32x16-32x32-rgb-led-matrix/)
* [Adafruit LED Matrix Hat Tutorial](https://learn.adafruit.com/adafruit-rgb-matrix-plus-real-time-clock-hat-for-raspberry-pi)

## General Guidance
* Set up a [Nerves](https://hexdocs.pm/nerves/getting-started.html) project in the
[already created repository](https://github.com/verypossible/heartbeat).
* Connect your hardware as recommended in the various tutorials above
project.
* Begin by writing to a single color to a single multiplexed channel.
* Multiplex the signal so that the whole display writes that color.
* Expand to full color (r, g, b) control.
* Use your web elixir skills and hook into the slack API and color LEDs
based on (sentiment of?) slack messages.


