# Neopixel Moving Red Green and Blue
In this lab, our goal is to make a single-pixel move down the LED strip and then change color from red to green and blue.

## Circuit

![Tinkercad Circuit](./img/led-strip-circuit.png)

## Code
We will use the same code that we used in the Move lab.  But we will repeat the for loop three times, one loop for each color.

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
    pixels.show();
  }
  
  for(int i=0;i<NUMPIXELS;i++){
    pixels.setPixelColor(i, 0, 255, 0);
    pixels.show();
    delay(100);
    pixels.setPixelColor(i, 0, 0, 0);
    pixels.show();
  }
  
  for(int i=0;i<NUMPIXELS;i++){
    pixels.setPixelColor(i, 0, 0, 255);
    pixels.show();
    delay(100);
    pixels.setPixelColor(i, 0, 0, 0);
    pixels.show();
  }
}
```

## Link Working Example
https://www.tinkercad.com/things/9N27JUfFSCe

## Experiments