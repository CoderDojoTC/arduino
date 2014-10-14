Twin Cities Arduino CoderDojo
=======
Welcome!  This area is for students and mentors that are participating in the Twin Cities CoderDojo sessions.  Please let one of the mentors know if you have feedback that you think will help others.

We are currently using the [SparkFun Inventors Kit](https://www.sparkfun.com/products/12001) to guide our students.  Although you are not required to follow the guidebook we encourage our new students to try these labs out first.

One of the reasons we selected this kit because it has an excellent free to download [Guidebook PDF](http://dlnmh9ip6v2uc.cloudfront.net/datasheets/Kits/SFE-SIK-RedBoard-Guide-Version3.0-Online.pdf) which we encourage you to download and familiarize yourself with before you come to the classes.

Why Arduino?
======
Since 2007 the Arduino name has come to dominate beginning digital controllers.  They are relativly low cost (some as low as $2) and they have a strong library of open source software.  Concepts that you learn programming the Arduino can also be applied toward other computers..

Bringing Your Own Computer
=======
We encourage students to bring their own computer whenever possible.  Although we do have some computers, we don't have enough for everyone.  In order for you to get the most out of the class we encourage you to try the following three steps BEFORE you arrive.

Step 1: Download the Arduino IDE
------
Please try to pre-load the [Arduino Integrated Development Environment (IDE)](http://arduino.cc/en/Main/Software).  This free software will run on Windows, Macs and Linux systems.  If you are familiar with the Eclipse this is a version of Eclipse that have been extensivly customized for Arduinos.  The IDE comes pre-loaded with many sample programs.  If you have questions about how to use the application please see the Arduino web site.  There are also many YouTube videos that show you how the Arduino systems work.

Step 2: Download the Correct FT231 USB Driver
------
Note that the SparkFun kits do NOT use standard Arduino boards.  They use [SparkFun RedBoard](https://www.sparkfun.com/products/12757) manufactured by SparkFun.  These boards us the same processor as standard Ardunios, however they use *different* USB interface chips and therefor will need a different USB driver.  If you bring your own laptop, please make sure that you load the USB drivers for the FTDI FT231X before you come.  You can get the [FTDI FT231X drivers here](http://www.ftdichip.com/Drivers/VCP.htm).  Note that you will not be able to test this step until you get into the lab.  When you do connect the RedBoard to your computer via the USB cable you should see the the working driver under USB in the Windows Device Manager Program.  If you see errors you will not be able to download new programs to the RedBoard.

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
You are not limited by the labs in the SparkFun inventors kit.  Feel free to bring your own sensors and displays. Learning how to use the popular WS2811 addressible LED strips (NeoPixels) is a great example of a fun lab.  The mentors will work with you to figure out how to use them.
