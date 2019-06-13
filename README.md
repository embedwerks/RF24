
**See http://tmrh20.github.io/RF24 for all documentation**

embedwerks Fork of RF24
=======================

This fork is designed for better support for ARM based microprocessors, specifically the Nordic nRF52832 as found on the Adafruit Bluefruit Feather nRF52832. So far the following changes have been made:

* Lowered SPI bus speed to 4Mhz to match the bus speed as defined in SPI.h inside of the Adafruit BSP
