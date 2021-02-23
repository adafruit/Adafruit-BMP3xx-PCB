## Adafruit BMP3xx - Precision Barometric Pressure and Altimeter PCB

<a href="http://www.adafruit.com/products/3966"><img src="assets/3966-STEMMA.jpg?raw=true" width="500px"><br/>
<a href="http://www.adafruit.com/products/3966"><img src="assets/3966.jpg?raw=true" width="500px"><br/>
<a href="http://www.adafruit.com/products/4816"><img src="assets/4816.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit BMP388 - Precision Barometric Pressure and Altimeter. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/3966
* https://www.adafruit.com/product/4816

### Description

Bosch has been a leader in barometric pressure sensors, from the [BMP085](https://www.adafruit.com/product/1603), [BMP180](https://www.adafruit.com/product/1603), and [BMP280](https://www.adafruit.com/product/2651)... now we've got the next generation, the **Adafruit BMP3xx Precision Barometric Pressure sensor**. As you would expect, this sensor is similar to its earlier versions but even better. The BMP388 has better precision than ever, which makes it excellent for environmental sensing or as a **precision altimeter**. It can even be used in either I2C and SPI configurations.

The BMP388 is the next-generation of sensors from Bosch, and is the upgrade to the BMP280 - with a low altitude noise as low as 0.1m and the same fast conversion time. And like the previous BMP280, you can use I2C or SPI. For simple easy wiring, go with I2C. If you want to connect a bunch of sensors without worrying about I2C address collisions, go with SPI.

The BMP390 is the next-generation of sensors from Bosch and is the upgrade to the BMP280 and BMP388 - with a low-altitude noise as low as 0.1m and the same fast conversion time. And like the previous BMP280, you can use I2C or SPI. For simple easy wiring, go with I2C. If you want to connect a bunch of sensors without worrying about I2C address collisions, go with SPI.

This sensor has a relative accuracy of 8 Pascals, which translates to about ± 0.5 meter of altitude (compare to the BMP280's 12 Pascal/ ±1 meter). The datasheet sort of implies they intend this sensor to be used for drones and quadcopters, to keep altitude stable, but you could also use this for wearables or any project that wants to track height-above-sea-level. Note that for absolute height you'll still need to enter in the barometric pressure at sea level, if the weather changes, but that's true of every altimeter sensor that uses pressure. You can also measure temperature with ±0.5°C accuracy.

Nice sensor right? So we made it easy for you to get right into your next project. The surface-mount sensor is soldered onto a PCB and comes with a 3.3V regulator and level shifting so you can use it with a 3V or 5V logic microcontroller without worry. [Check out the Arduino library to get data out in under 10 minutes!](https://github.com/adafruit/Adafruit_BMP3XX)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
