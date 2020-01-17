## Adafruit LIS3MDL Triple-axis Magnetometer PCB

<a href="http://www.adafruit.com/products/4479"><img src="assets/4479.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit LIS3MDL Triple-axis Magnetometer. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4479

### Description

Sense the magnetic fields that surround us with this handy triple-axis magnetometer (compass) module. Magnetometers can sense where the strongest magnetic force is coming from, generally used to detect magnetic north, but can also be used for measuring magnetic fields. This sensor tends to be paired with a 6-DoF (degree of freedom) accelerometer/gyroscope to create a 9-DoF inertial measurement unit that can detect its orientation in real-space thanks to Earth's stable magnetic field. It's a great match for the LSM6DSOX from ST!

We based this breakout on ST's LIS3MDL, a great general purpose magnetometer. This compact sensor uses I2C to communicate and its very easy to use. Simply download our library and connect the SCL pin to your I2C clock pin, and SDA pin to your I2C data pin and upload our test program to read out magnetic field data. If you'd like, you can also use SPI to receive data (we just happen to prefer I2C here)

This sensor can sense ranges from +-4 gauss (+- 400 uTesla) up to +-16 gauss (+- 16uTesla). For ultra high precision, 155 Hz update rate is recommended - but if you don't mind a little loss of precision, the sensor can output at 1000 Hz.

To make life easier so you can focus on your important work, we've taken the LIS3MDL and put it onto a breakout PCB along with support circuitry to let you use this little wonder with 3.3V (Feather/Raspberry Pi) or 5V (Arduino/ Metro328) logic levels. Additionally since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro and you can use our CircuitPython/Python or Arduino drivers to easily interface with the LIS3MDL and get magnetic measurements ASAP.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
