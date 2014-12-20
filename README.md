Twin Cities Arduino CoderDojo
=======
Welcome! This area is for students and mentors that are participating in the Twin Cities CoderDojo sessions. Please let one of the mentors know if you have feedback that you think will help others.

We are currently using the [SparkFun Inventors Kit](https://www.sparkfun.com/products/12001) to guide our students. Although you are not required to follow the guidebook we encourage our new students to try these labs out first.

One of the reasons we selected this kit is because it has an excellent free [Guidebook PDF](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Kits/SFE-SIK-RedBoard-Guide-Version3.0-Online.pdf) which we encourage you to download and familiarize yourself with before you come to class.

Why Arduino?
======
Arduino began as a project in Italy in 2005 and since then has turned into an open source hardware movement. Arduino microcontrollers are relatively low cost (some as low as $2) and have a large library of open source software. Programming the Arduino reinforces basic computer programming concepts.

Bringing Your Own Computer
=======
We encourage students to bring their own computer. In order for you to get the most out of the class we encourage you to try the following three steps BEFORE you arrive.

Step 1: Download the Arduino IDE
------
Please try to pre-load the [Arduino Integrated Development Environment (IDE)](http://arduino.cc/en/Main/Software).  This free software will run on Windows, Mac and Linux systems. If you are familiar with Eclipse, this is a version of Eclipse that has been extensively customized for the Arduino. The IDE comes pre-loaded with many sample programs. If you have questions about how to use the application please see the Arduino web site. There are also many YouTube videos that show you how the Arduino system work.

Step 2: Download the Correct FT231 USB Driver
------
Note that the SparkFun kits do NOT use standard Arduino boards. They use [SparkFun RedBoard](https://www.sparkfun.com/products/12757) manufactured by SparkFun.  These boards use the same processor as standard Arduinos, however they use *different* USB interface chips and therefore will need a different USB driver.  If you bring your own laptop, please make sure that you load the USB drivers for the FTDI FT231X before you come.  You can get the [FTDI FT231X drivers here](http://www.ftdichip.com/Drivers/VCP.htm). Note that you will not be able to test this step until you get into the lab. When you connect the RedBoard to your computer via the USB cable you should see the the working driver under USB in the Windows Device Manager Program. If you see errors you will not be able to download new programs to the RedBoard.

Step 3: Download the SparkFun Inventors Kit Examples
------
We also would like you to pre-load the [SparkFun Inventors Kit Code Examples](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Kits/SIK%20Guide%20Code.zip) so the student doesn't need to type in the code.

1. Download the latest SIK Guide Code (http://sparkfun.com/sikcode)
2. Unzip the above file
3. Place the "SIK Guide Code" folder in the Arduino IDE "examples" directory:

    For PC: drag the "SIK Guide Code" folder into C:\program files\Arduino-x\examples
    
    For MAC: drag the "SIK Guide Code" folder into Arduino-x/Contents/Resource/Java/examples
    
    For Linux: see http://www.arduino.cc/playground/Learning/Linux
    
4. Start the Arduino IDE; the examples should be visible in File/Examples/SIK Guide Code

Advanced Labs
=======
You are not limited by the labs in the SparkFun Inventors Kit. Feel free to bring your own sensors and displays. Learning how to use the popular WS2811 addressible LED strips (NeoPixels) is a great example of a fun lab. The mentors will work with you to figure out how to use them.
