# Arduino Blink Lab

In this lab, we will learn how to make a Light Emitting Diode (LED) turn on and off at various speeds.  The Blink lab is kind of like "hello world" in Arduino: it is the first program most students learn.

## LED Connectors
The LED has two connectors on it.  But you should never connect both the wires directly to power.  That will burn out the LED.  The LED has a negative side (called the Cathode) and a positive site (called the Anode).  It is important that you don't confuse these two sides.  If you don't hook them up correctly your circuit will not work!

Here is a picture of the cathode and anode of an LED.

![LED Cathode and Anode](./img/01-led-cathode-anode.png)

## Remembering Cathode and Anode

Sometimes you can use a picture to help you remember which end is the cathode and which one is the anode.  I try to think of a short black "cat" to remember the negative cathode.  I also try to think of my friend Ann who is tall and loves red when I think of the Anode.  Here is a picture that you can use to remember this idea:
![Remembering Cathode and Anode](./img/01-cat-and-ann.png)


Sometimes it is hard to remember which side is which.  You 



## Circuit Diagram
Here is the circuit diagram we will use for our blink lab.


You can create this using the following steps:

Step 1: Go to the left navigation area and click the Circuits and press the green Create New Circuit button:
![left nav](./img/01-left-nav.png)![Create New Circuit](./img/01-create-circuit.png)
Step 2: Go to the right search area and type in "Arduino".  You should see the following image:
![Arduino Search](./img/01-search-arduino.png)
![LED Search](./img/01-led.png)
![Add Resistor](./img/01-resistor.png)

![Set Resistor Value](./img/01-set-resistor.png)

![Connect LED to GND](./img/01-connect-led-gnd.png)

Now drag the 330 ohm resistor so it connect to the right pin of the LED
![Connect LED Resistor and to 13](./img/01-connect-led-gnd.png)

![Blink Circuit diagram](./img/blink.png)

## Code
```C
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000);
}
```

## Experiments



