# ESP32-C3-0.42 OLED

![image](https://github.com/ricardocplima/ESP-C3-0.42/blob/main/images/esp32c3_042_oled_pinout.webp)


# Getting started in PlatformIO:

Install VSCode and install the PlatformIO extension.

*Note that it is also required to install the C base requirements on your machine. For usage of C on VSCode, use the oficial site:
https://code.visualstudio.com/docs/languages/cpp

After instaling the extension, create a new project and select the board used in the project. Further testing is required, but the "Espressif ESP32-C3-DevKitM-1" board worked without problems so far.


# The following Arduino libraries need to be installed
You can install the libraries via the home page of PlatformIO

u8g2

OneBitDisplay

BitBang_I2C

SparkFun SCD4x Arduino Library

AnimatedGIF

thinger.io

Adafruit NeoPixel 


# Sending the code to the ESP:

Once the code is ready, click the "Build" button to verify if there are any errors. If no problem occurs, click the "Upload" button. The port should be automatically selected, but if problems occur it is recommended to check the COM port used.

To start, you can use the sample code included in the file "file".

# Source

This repository was created using the following repository as inspiration, but applying it to VSCode:
https://github.com/01Space/ESP32-C3-0.42LCD
