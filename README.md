This source code handles a arduino weather-station with humidity, temperature and pressure sensors. 
This following Sensor i use for my Porject:

"BMP180" pressure sensor  
"DHT22" humidity and temperature sensor 

The output is actually made via the serial monitor. 
Later I want to output the values to an LCD-display

Special thank to Adafruit and oksbwn for give me a lot of the source code i need for this project. 






Library descriptions: 

# Adafruit AM2320 Library [![Build Status](https://travis-ci.org/adafruit/Adafruit_AM2320.svg?branch=master)](https://travis-ci.org/adafruit/Adafruit_AM2320)

<img src="https://cdn-shop.adafruit.com/970x728/1947-05.jpg" height="300"/>

This is a library for the Adafruit AM2320 Temperature & Humidity Unified Sensor
  * https://www.adafruit.com/products/3721

Also supports AM2320 chips (and maybe other compatible chips!)
 
Check out the links above for our tutorials and wiring diagrams. This chip uses I2C to communicate

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
MIT license, all text above must be included in any redistribution



This is an Arduino library for the DHT series of low cost temperature/humidity sensors.

Tutorial: https://learn.adafruit.com/dht

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder DHT. Check that the DHT folder contains DHT.cpp and DHT.h. Place the DHT library folder your <arduinosketchfolder>/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.

# Adafruit DHT Humidity & Temperature Unified Sensor Library

This library also includes an optional class for the
[DHT humidity and temperature sensor](https://learn.adafruit.com/dht/overview)
which is designed to work with the [Adafruit unified sensor library](https://learn.adafruit.com/using-the-adafruit-unified-sensor-driver/introduction).

You must have the following Arduino libraries installed to use this class:

- [Adafruit Unified Sensor Library](https://github.com/adafruit/Adafruit_Sensor)
