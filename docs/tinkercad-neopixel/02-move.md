# Neopixel Move
In this lab, our goal is to make a red LED appear to move up and down the LED strip.  We will do this by using a the main arduino loop to turn each pixel on and off.

## Circuit
We will use the same Arduino circuit at we used in the NeoPixel blink lab.

![Tinkercad Circuit](./img/led-strip-circuit.png)

## Code

### Preamble ans Setup
The preamble and setup will be identical to our blink lab.  Make sure you have the number of pixels set to 12 and the right pin number.

### The Main Loop
Our main loop will use a single for statuement.  The for statement has three parameters:

1. The initialization of the for loop where we set our index counter (i) to be 0.
2. The condition that we use to exit the for loop.  In this case we will be testing to see if our index is still less than the number of pixels NUMPIXELS
3. The function that we will run after each for loop finishes.  In this case we will increment our index by 1 with the **i++** operator.

Inside each loop we will turn on each pixel on for just 1/10 of a second.  This is done with the setPixelColor function that turns on the red LED to 255 followed by the pixels.show() function.  The delay(100) is for delaying the LED for 100 milliseconds or 1/10th of a full second.

We then turn off the red pixel value.

Here is the main loop code:

```C
void loop() {
  for(int i=0;i<NUMPIXELS;i++){
    pixels.setPixelColor(i, 255, 0, 0); // turn red on
    pixels.show(); // send to the LED strip
    delay(100); // delay 1/10th of a second
    pixels.setPixelColor(i, 0, 0, 0);  // turn red off
  }
}
```

### Full Program
```C
#include <Adafruit_NeoPixel.h>
#define PIN 2
#define NUMPIXELS 12
Adafruit_NeoPixel pixels = Adafruit_NeoPixel(NUMPIXELS, PIN, NEO_GRB + NEO_KHZ800);

void setup() {
  pixels.begin();
}

void loop() {
  for(int i=0;i<NUMPIXELS;i++){
    pixels.setPixelColor(i, 255, 0, 0);
    pixels.show();
    delay(100);
    pixels.setPixelColor(i, 0, 0, 0);
  }
}
```

## Link Working Example
[Link to Move Lab #2 on Tinkercad](https://www.tinkercad.com/things/hxn3KTqEdqn)

## Experiments