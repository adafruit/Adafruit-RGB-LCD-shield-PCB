# RGB LCD Shield Kit

<a href="http://www.adafruit.com/products/714"><img src="assets/board.jpg?raw=true" width="500px"></a>

This new Adafruit shield makes it easy to use a 16x2 Character LCD. We really like the RGB LCDs we stock in the shop both the [RGB negative](http://www.adafruit.com/products/399) and [RGB positive](http://www.adafruit.com/products/398). Unfortunately, these LCDs do require quite a few digital pins, 6 to control the LCD and then another 3 to control the RGB backlight for a total of 9 pins. That's half of the pins available on a classic Arduino!

With this in mind, we wanted to make it easier for people to get these LCD into their projects so we devised a shield that lets you control __a 16x2 Character LCD, up to 3 backlight pins AND 5 keypad pins using only the two I2C pins on the Arduino!__ The best part is you don't really lose those two pins either, since you can stick i2c-based sensors, RTCs, etc and have them share the I2C bus. This is a super slick way to add a display without all the wiring hassle.

This shield is perfect for when you want to build a stand-alone project with its own user interface. The 4 directional buttons plus select button allows basic control without having to attach a bulky computer.

The shield is designed for 'classic' Arduinos such as the Uno, Duemilanove, Diecimilla, etc. It uses the I2C pins at Analog 4 and Analog 5. It will also work perfectly with Arduino Mega R3's which have the extra SDA/SCL I2C pins broken out. Earlier Mega's have the I2C pins in a different location and will require you to solder two wires from the I2C pins on the shield and plug them into the different I2C locations at Digital 20 & 21. This shield will not fit easily on top of an Arduino Ethernet because of the Ethernet jack height. [You can use a set of stacking headers to give the shield more 'lift' above the jack](http://www.adafruit.com/products/85).

__This product comes as a kit!__ Included is a high quality, USA-made PCB and all the components (buttons, header etc). This product comes with a [16x2 RGB negative](http://www.adafruit.com/products/399). Assembly is easy, even if you've never soldered before and the kit can be completed in 30 minutes. [Check the product tutorial page for assembly instructions before purchasing](http://learn.adafruit.com/rgb-lcd-shield).

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
