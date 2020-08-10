# Arduino Glossary of Terms

#### Anode
The positive side of our LEDs.  Make sure you put a 330-ohm current limiting resistor between the LED and the digital output or a 5-volt connection.

#### Arduino
Arduino is the name of a popular open electronic learning platform for teaching [Physical Computing](#physical-computing) based around a set of open standards.  Devices cost as little as $2.50 US.  There are over 2 million YouTube videos on Arduino projects.  An Arduino is programmed using a PC and a USB cable.  Once an Arduino program is uploaded into a device it can be disconnected.

#### Cathode
The negative side of our LEDs.  Make sure that the cathode always goes to the ground (GND) pin or rail.  It is a best practice to use a black wire to connect the cathode to ground.

#### Concept Cards
Small laminated cards that describe a specific concept.  They are often spread out on a table near the entrance to CoderDojo events.  Each card
has
1. a concept name
2. a concept difficulty level (Beginning, Intermediate or Advanced)
3. an image to promote recall
4. a challenge text on the front of the card
5. answers to the challenge on the back of the card
<br/> See [Designing Concept Cards](https://coderdojotc.github.io/CoderDojoTC/designing-concept-cards/)

##### Integrated Development Environment
An integrated development environment is a software program used for writing, checking, debugging and downloading software into the Arduino.  Some IDEs also have data visualization tools for plotting the output of sensors.
<br/> See also: IDE

##### Pulse Wave Modulation
A way of controlling the speed of a motor or the intensity of a light by changing the amount of time a signal is on.  On the Arduino only a subset of output pins can be used to send PWM signals.  On the Arduino Nano these are pins 3,5,6,9, 10 and 11.
<br/> See also: PWM

#### Arduino Nano
The original Arduino devices have a defect in that they are not compatible with standardized solderless breadboards.  We use a lower-cost version that can plug in directly to a solderless breadboard.
* [Hardware Web Page](http://arduino.cc/en/Main/ArduinoBoardNano)
* [Guide to the Arduino Nano](http://arduino.cc/en/Guide/ArduinoNano)

#### CH340 Drivers
The name of the low-cost USB interface chip that is use instead of the more expensive FTDI USB interface chip.
Although the chip is low-cost, the driver is not usually included with the Arduino IDE and the driver may not digitally sigined for the Mac.
<br/> [SparkFun guide to installing the CH340 drivers](https://learn.sparkfun.com/tutorials/how-to-install-ch340-drivers/all)
<br/>See the [CH340 drivers here](http://www.wch.cn/download/CH341SER_ZIP.html)
<br/>See [Arduino Nano CH340 Instructable](http://www.instructables.com/id/Arduino-Nano-CH340/) for a good description of how to make the CH340 work on the Mac.

#### H-Bridge
A device that takes in pulse width modulation signals from an Arduino controller and controls the forward and reverse speed of a motor.
We use the L293D chip in many of our motor control labs.

#### l293D motor driver
A device for controlling two motors with an Arduino.  We use this device in many of our labs and to drive our robots.  A low-cost breakout of this chip with headers costs about $1.50 on ebay.
<br/>[Mini Motor Drive Shield Expansion Board L293D Module For Arduino UNO MEGA2560 R3](Mini Motor Drive Shield Expansion Board L293D Module For Arduino UNO MEGA2560 R3)

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

#### Red-Green-Blue LED
A single device that has three colors of LEDs.  One for red, one for blue and one for green.  We use common cathode LEDs in CoderDojo labs.  By combining various intensities of each of these three colors we can create many additional colors.
<br/>Also known as: RGB LED

#### NeoPixel
This is the name coined by Adafruit for an individually addressable LED.  
Adafruit also provides a high-quality open source library on github to drive these LEDs.
<br/>[NeoPixel on Adafruit Web Site](http://www.adafruit.com/category/168)
<br>Also known as: [#ws2812B]

#### NeoPixel Library
The Arduino library used in these guides to program our LED strips.  We picked this library because of its popularity and the many on-line
tutorials about how to use them.
<br/>[NeoPixel Library Guide on the Adafruit Web Site]https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library
<br/>[NeoPixel Library on GitHub](https://github.com/adafruit/Adafruit_NeoPixel)

#### Physical Computing
Hardware and software that can sense and respond to changes in the world around us.
* [Wikipedia Definition](http://en.wikipedia.org/wiki/Physical_computing)

#### Photoresistor
A small electrical component that changes its resistance based on the amount of light that is present.  We use this device in our introductory Aruduino labs.

#### Servo Motor
A small electrical motor that we control the angular positions by sending digital pulses from the Arduino.  

#### Social Constructionism
Getting students to build things together in teams.  This style of teaching has many benefits over standard lecture-style learning.  Social
constructionism is one of the core techniques taught in CoderDojo.
* [Wikipedia Definition](http://en.wikipedia.org/wiki/Social_constructionism)
* [Berkeley Web Site on Social Constructionism in Education](http://gsi.berkeley.edu/gsi-guide-contents/learning-theory-research/social-constructivism/)

#### WS2812B
A standard for addressable RGB LEDs
* [Data sheet from Adafruit](http://www.adafruit.com/datasheets/WS2812B.pdf)