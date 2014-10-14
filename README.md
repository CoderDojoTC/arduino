Twin Cities Arduino CoderDojo
=======
We are currently using the [SparkFun Inventors Kit](https://www.sparkfun.com/products/12001).  One of the reasons we selected this kit because it has an excellent [Guidebook PDF](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Kits/SFE-SIK-RedBoard-Guide-Version3.0-Online.pdf) which we encourage you to download and familiarize yourself with before you come to the classes.

Bringing Your Own Computer
=======
We encourage you to bring your own computer.  Although we do have some computers, we don't have enough for everyone.

Step 1: Download the Arduino IDE
------
pre-load the [Arduino IDE](http://arduino.cc/en/Main/Software)

Step 2: Download the Correct FT231 USB Driver
------
Note that the SparkFun kits do NOT use standard Arduino boards.  They use [SparkFun RedBoard](https://www.sparkfun.com/products/12757) manufactured by SparkFun.  These boards us the same processor as standard Ardunios, however they use *different* USB interface chips and therefor will need a different USB driver.  If you bring your own laptop, please make sure that you load the USB drivers for the FTDI FT231X before you come.  You can get the [FTDI FT231X drivers here](http://www.ftdichip.com/Drivers/VCP.htm).  Note that you will not be able to test this step until you get into the lab.  When you do connect the RedBoard to your computer via the USB you should see the the driver in the Windows device Manager.

Step 3: Download the SparkFun Inventors Kit Examples
------
We also would like you to pre-load the the [SparkFun Inventors Kit Code Examples](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Kits/SIK%20Guide%20Code.zip) so the students do not need to type in the code.  These example program should be copied to:

1. Download the latest SIK Guide Code (http://sparkfun.com/sikcode)
1. Unzip the above file.
1. Place the "SIK Guide Code" folder in the Arduino IDE "examples" directory:

    For a PC: drag the "SIK Guide Code" folder into C:\program files\Arduino-x\examples
    
    For MAC: drag the "SIK Guide Code" folder into Arduino-x/Contents/Resource/Java/examples
    
    For Linux: see http://www.arduino.cc/playground/Learning/Linux
    
1. Start the Arduino IDE; the examples should be visible in File/Examples/SIK Guide Code

Advanced Labs
=======
You are limited by the labs in the SparkFun inventors kit.  Feel free to bring your own sensors and displays and the mentors will work with you to figure out how to use them.
