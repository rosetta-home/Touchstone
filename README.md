# Open Source Indoor Air Quality Sensor
An open hardware and software indoor air quality sensor provided by the [National Association of REALTORS](http://realtor.org) and [CRT Labs](https://crtlabs.org).

![](assets/Touchstone.jpg)
![bruh](assets/render.png)

Features:
* Atmel ATmega328P 16MHz 8-bit processor
* FTDI FT231XQ for serial communication
* Mini RGB LED for status and notification
* Programmable button for custom actions such as reset, configuration, etc.

Measurement Points:
* Temperature (Si7021)
* Relative Humidity (Si7021)
* VOC (Volatile Organic Compounds) (CCS811/IAQ-Core)
* CO2 (MH-z19)
* Particulate Matter, PM2.5 (PMS7003)
* Barometric Pressure (BMP280)
* Light Intensity (TSL2591)
* Sound Intensity (Electret Microphone)

Connectivity:
* FSK (RFM69HW 915MHz)
* USB (FTDI FX231XQ)

License:
Apache License Version 2.0

For the Raspberry Pi HAT, please visit the [PiAQ Website](http://piaq.io) and [repository](https://github.com/NationalAssociationOfRealtors/PiAQ)
