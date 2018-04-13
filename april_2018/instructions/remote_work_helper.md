# Remote Work Helper
Build a remote work helper that sends keyboard inputs to your computer via
arcade-style buttons.

Send keyboard input to mute computer microphone when on-board microphone detects
loud noise.  Toggle this functionality on/off with an arcade button.

Send volume up/down commands based on potentiometer input.

Be creative with other buttons/LEDs!

This is project is inspired by the
[DIY Hotkey Panel](http://www.instructables.com/id/Arduino-Hot-Key-Panel/)
project, but it would be great to have one tailored toward Very employees.

## IoT Skills
* General wiring/soldering
* Analog Inputs
* Digital Inputs
* LED control via PWM
* Arduino development on PlatformIO


## Supplies
* 1 [Sparkfun Pro Micro](https://www.sparkfun.com/products/12640) or equivalent.
* N [Arcade Style Buttons](https://www.amazon.com/EG-Buttons-Multicade-Pinball-Accessories/dp/B01N5DVINY)
* 1 [Microphone](https://www.amazon.com/DAOKI-Sensitivity-Microphone-Detection-Arduino/dp/B00XT0PH10)
* 1 [Potentiometer](https://www.amazon.com/Gikfun-Knurled-Linear-Potentiometer-Arduino/dp/B06VVJ68PM/)

## Useful References
* [Arduino analog input tutorial](https://www.arduino.cc/en/Tutorial/AnalogInput)
* [Arduino non-blocking led control](https://www.arduino.cc/en/Tutorial/BlinkWithoutDelay)
* [Arduino button tutorial](https://www.arduino.cc/en/Tutorial/Button)
* [Arduino keyboard tutorial](https://www.arduino.cc/reference/en/language/functions/usb/keyboard/)

## General Guidance
* Set up a [PlatformIO](http://docs.platformio.org/en/latest/) project in the
[already created repository](https://github.com/verypossible/remote_work_helper).
* Connect your hardware as recommended in the various tutorials above
project.
* For each input/output write a simple version of firmware that prints the
result to the serial console.
* Hard code keystrokes for each of the inputs.
* Get fancy and build a command line (or other method) app that can configure
the arduino through serial communication.


