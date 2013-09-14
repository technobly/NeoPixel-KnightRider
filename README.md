NeoPixel-KnightRider
====================

A highly configurable Knight Rider (larson display) routine for your [AdaFruit NeoPixel](http://www.adafruit.com/products/1138) (WS2812 RGB LED) using the Arduino.

![trail effect](https://raw.github.com/technobly/NeoPixel-KnightRider/master/trail_effect.jpg)

[Youtube Demo Video](http://youtu.be/4fjDWSFsv8o)

## Requirements
1. An [Arduino](http://www.arduino.cc) Development board.
2. (2x) [AdaFruit NeoPixel Stick](http://www.adafruit.com/products/1426) (or other NeoPixel products)
3. [Adafruit NeoPixel library](https://github.com/adafruit/Adafruit_NeoPixel)

## Instructions
1. Install [Adafruit NeoPixel library](https://github.com/adafruit/Adafruit_NeoPixel)
2. Connect the NeoPixel to ground and power.  Power requirements here: [AdaFruit NeoPixel](http://www.adafruit.com/products/1426) 
3. Connect the NeoPixel DIN to Analog Input #5 of the Arduino (we are using this A5 pin as a digital output).  A5 is nice because it's on the same side of the Arduino as the 5V and GND connections.  Connect NeoPixel ground to the ground of the Arduino (if not done already). [Reference image](http://i.imgur.com/Wj2UWJF.jpg)
4. Upload NeoPixel-KnightRider sketch to the board and run it.  You'll see a collection of demos, the first one is the default Knight Rider display ;-)

## Credit
Inspiration from: [Arduino Knight Rider Tutorial](http://www.arduino.cc/en/Tutorial/KnightRider) and [Doug Diego's KnightRiderNeoPixel Repo](https://github.com/dougdiego/KnightRiderNeoPixel) and of course the [Knight Rider TV Series Intro](http://www.youtube.com/watch?v=Mo8Qls0HnWo).

## License

See attached MIT License
