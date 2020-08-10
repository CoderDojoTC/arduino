# Arduino Glossary of Terms

#### Anode
The positive side of our LEDs.  Make sure you put a 330-ohm current limiting resistor between the LED and the digital output or a 5-volt connection.

#### Arduino

Arduino is the name of a popular open electronic learning platform based around a set of open standards.

#### Cathode
The negative side of our LEDs.  Make sure that the cathode always goes to the ground (GND) pin or rail.  It is a best practice to use a black wire to connect the cathode to ground.

##### Integrated Development Environment \(IDE\)

An integrated development environment \(IDE\) is a software program used for writing, checking and downloading software into the Arduino.

##### Pulse Wave Modulation \(PWM\)

A way of controlling the speed of a motor or the intensity of a light by changing the amount of time a signal is on.  On the Arduino only a subset of output pins can be used to send PWM signals.  On the Arduino Nano these are pins 3,5,6,9, 10 and 11.

## Arduino Nano
The original Arduino devices have a defect in that they are not compatible with standardized solderless breadboards.  We use a lower-cost version that can plug in directly to a solderless breadboard.
* [Hardware Web Page](http://arduino.cc/en/Main/ArduinoBoardNano)
* [Guide to the Arduino Nano](http://arduino.cc/en/Guide/ArduinoNano)

## CH340
The name of the low-cost USB interface chip that is use instead of the more expensive FTDI USB interface chip.
Although the chip is low cost, the driver is not usually included with the Arduino IDE and 
the driver is not digitally
sigined for the Mac.
<br/>See the [CH340 drivers here](http://www.wch.cn/download/CH341SER_ZIP.html)
<br/>See [Arduino Nano CH340 Instructable](http://www.instructables.com/id/Arduino-Nano-CH340/) for a good description of how to make the CH340 work on the Mac.

#### Light Emitting Diode
A solid-state device that emits light when a voltage is applied.  LEDs come in various colors such as red, green and blue.  In our labs we will use various colors of LEDs that all use around 20 milliamps of current.  To make sure that there is not too much current going through the LED we always use a 330-ohm resistor in series with the LEDs.
<br/>Also known as: LED
<br/>[Wikipedia Definition](http://en.wikipedia.org/wiki/Light-emitting_diode)

#### Moving Rainbow Kits
These are kits that combine three important aspects of learning: Color, Motion and Social Constructionism.  
Students are interested in sensing and changing the world around them.  
The use of low-cost LEDs and DC-motors can make these kits not only fun, 
but inexpensive enough that students can purchase them and take them home to share with friends.  A typical cost is around $15.00 USD.
<br/>Web site: [https://dmccreary.gitbooks.io/moving-rainbow/](https://dmccreary.gitbooks.io/moving-rainbow/)


#### Red-Green-Blue LED (RGB LED)
A single device that has three colors of LEDs.  One for red, one for blue and one for green.  By combining various intensities of each of these three colors we can create many additional colors.

#### NeoPixel
This is the name coined by Adafruit for an individually addressable LED.  
Adafruit also provides a high-quality open source library on github to drive these LEDs.
<br/>[NeoPixel on Adafruit Web Site](http://www.adafruit.com/category/168)

#### NeoPixel Library
The Arduino library used in these guides.  
We picked this library because of its popularity and the many on-line
tutorials about how to use them.
<br/>[NeoPixel Library Guide on the Adafruit Web Site]https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library
<br/>[NeoPixel Library on GitHub](https://github.com/adafruit/Adafruit_NeoPixel)

#### Physical Computing
Hardware and software that can sense and respond to changes in the world around us.
* [Wikipedia Definition](http://en.wikipedia.org/wiki/Physical_computing)

#### Servo Motor
A small electrical motor that we control the angular positions by sending digital pulses from the Arduino.  

#### Social Constructionism
Getting students to build things together in teams.  This style of teaching has many benefits over the standard lecture-style learning.
* [Wikipedia Definition](http://en.wikipedia.org/wiki/Social_constructionism)
* [Berkeley Web Site on Social Constructionism in Education](http://gsi.berkeley.edu/gsi-guide-contents/learning-theory-research/social-constructivism/)

#### WS2812B
A standard for addressable RGB LEDs
* [Data sheet from Adafruit](http://www.adafruit.com/datasheets/WS2812B.pdf)