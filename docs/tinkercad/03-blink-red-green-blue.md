# Arduino Blink Three LEDs Lab

In this lab, we will learn how to make three LEDs of different color blink on and off.  We will be replicating the same blink circuit in the prior lab for a red, a green and a blue LED.

## LED Connections
The LED circuit is below.  Just like the blink lab, each LED will have a black wire from the cathode of the LED to GND.  The Anode of each LED will go through a resistor before it connects to one of the Arduino digital output pins.  We will be using pin 13, 12 and 11 (left to right) on the Arduino.

Here is a picture of red, green, blue LED circuit.

![LED Red Green Blue Circuit](./img/02-red-green-blue-leds.png)

## Circuit Diagram
Here is the circuit diagram we will use for our blink lab.

## Code

### The Setup Function
Our setup function will be similar to the blink lab except instead of just one output pin, we will have three.  The pins are 13, 12 and 11.
```C
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}
```

### The Loop Function
The loop function will first turn on and off the red LED on pin 13, just like in the blink lab.  We can then copy and paste the four lines of code right after itself to control the red LED on pin 12.  After we paste code in we will need to change the pin number from 13 to 12.  We will repeat this process and copy and paste four lines for pin 11, the blue pin.

```C
void loop()
{
  // turn the red LED on pin 13 on and off
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);

  // turn the green LED on pin 12 on and off
  digitalWrite(12, HIGH);
  delay(1000);
  digitalWrite(12, LOW);
  delay(1000);

  // turn the blue LED on pin 11 on and off
  digitalWrite(11, HIGH);
  delay(1000);
  digitalWrite(11, LOW);
  delay(1000);
}
```

### The Full Program

Here is the full program:

```C
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop()
{
  // turn the red LED on pin 13 on and off
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);

  // turn the green LED on pin 12 on and off
  digitalWrite(12, HIGH);
  delay(1000);
  digitalWrite(12, LOW);
  delay(1000);

  // turn the blue LED on pin 11 on and off
  digitalWrite(11, HIGH);
  delay(1000);
  digitalWrite(11, LOW);
  delay(1000);
}
```
You can type this into the Tinkercad program or do a copy here and paste it into the code area.

## Working example on Tinkercad

[Blink Three LEDs](https://www.tinkercad.com/things/2akE4amGGae-blink-three-leds)

## Experiments

1. What happens if you change the delay times (currently set at 1000) to be 100?
2. What happens if you change the delay times to be 50?
3. What happens if you change the delay times to be 20?
4. What happens if you change the delay times to be 10?  Can you still see the blinking at all?


## Food for thought
Most movies are shown around shown at 24 frames per second?  Why do you think they picked this speed?

If you hook up a photo sensor to a florescent light bulb you will see that it flickers 120 times per second.  Household current runs at half this rate (60 times per second).  Why do you think that the light flicker rate is twice the frequency?  Hint: draw a wave that goes positive and negative.  Look up [Sine Wave](https://en.wikipedia.org/wiki/Sine_wave) in Wikipedia.

What did you learn about the human eye?

If you would like to learn more about LED circuits here is a [Wikipedia Article on LED Circuits](https://en.wikipedia.org/wiki/LED_circuit)
