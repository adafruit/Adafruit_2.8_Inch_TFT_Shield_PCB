# 2.8" TFT Touch Shield for Arduino 

<a href="http://www.adafruit.com/products/376"><img src="assets/board.jpg?raw=true" width="500px"></a>

We've discontinued this version of the shield (which was expensive and difficult to make) and [replaced it with a version 2: its got a better price, uses way fewer pins, is Mega/Leonardo compatible and has a great touchscreen controller built in. Wow! Check it out here.](http://www.adafruit.com/products/1651)

Spice up your Arduino project with a beautiful large touchscreen display shield with built in microSD card connection. This TFT display is big (2.8" diagonal) bright (4 white-LED backlight) and colorful (18-bit 262,000 different shades)! 240x320 pixels with individual pixel control. It has way more resolution than a black and white 128x64 display. As a bonus, this display has a resistive touchscreen attached to it already, so you can detect finger presses anywhere on the screen.

__The shield is fully assembled, tested and ready to go. No wiring, no soldering! Simply plug it in and load up our library - you'll have it running in under 10 minutes!__ Works best with any classic Arduino (UNO/Duemilanove/Diecimila). This shield does work with the Mega Arduinos __but its going to be half the speed of the Uno-type boards__ because of the way the Mega rearranges all the pins (there is no way to get around this!) This shield is not Leonardo-compatible

This display shield has a controller built into it with RAM buffering, so that almost no work is done by the microcontroller. The shield does require a lot of pins: 12 lines total for the display, 13 total if you use the microSD card

[Of course, we wouldn't just leave you with a datasheet and a "good luck!" - we've written a full open source graphics library that can draw pixels, lines, rectangles, circles and text. We also have a touch screen library that detects x, y and z (pressure) and example code to demonstrate all of it. The code is written for Arduino but can be easily ported to your favorite microcontroller!](http://learn.adafruit.com/2-8-tft-touch-shield).

If you are not using an Arduino-shaped microcontroller, [check out our 2.8" TFT breakout board which can be easily wired up to any processor](http://www.adafruit.com/products/335) the breakout board version does not have microSD holder.

### TECHNICAL DETAILS

- 2.8" diagonal LCD TFT display
- 240x320 resolution, 18-bit (262,000) color
- ILI9325 (datasheet) or ILI9328 (datasheet) or HX8347 (datasheet) controller with built in video RAM buffer
- 8 bit digital interface, plus 4 control lines
- Uses digital pins 5-13 and analog 0-3. That means you can use digital pins 2, 3 and analog 4 and 5. Pin 12 is available if not using the microSD
- Works with any Arduino '328 or Mega (Leonardo not supported yet)
- 5V compatible! Use with 3.3V or 5V logic
- Onboard 3.3V @ 300mA LDO regulator
- 4 white LED backlight. On by default but you can connect the transistor to a digital pin for backlight control
- 4-wire resistive touchscreen

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
