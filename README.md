# ESP32-C3-0.42 OLED

![image](https://github.com/ricardocplima/ESP-C3-0.42/blob/main/images/S9a67326dfe534c50bcd9dc4f1a2fe5774.webp)


# Getting started in PlatformIO:
Install VSCode and install the PlatformIO extension.

![image](https://github.com/ricardocplima/ESP32-C3-0.42OLED_VSCode/blob/main/images/PlatformIO_Extension.png)

*Note that it is also required to install the C base requirements on your machine. For usage of C on VSCode, use the oficial site:
https://code.visualstudio.com/docs/languages/cpp


After instaling the extension, create a new project and select the board used in the project. Further testing is required, but the "Espressif ESP32-C3-DevKitM-1" board worked without problems so far.

![image](https://github.com/ricardocplima/ESP32-C3-0.42OLED_VSCode/blob/main/images/PlatformIO_NewProject.png)

![image](https://github.com/ricardocplima/ESP32-C3-0.42OLED_VSCode/blob/main/images/PlatformIO_SelectBoard.png)


# The following Arduino libraries need to be installed
You can install the libraries via the home page of PlatformIO

![image](https://github.com/ricardocplima/ESP32-C3-0.42OLED_VSCode/blob/main/images/PlatformIO_Libraries.png)

u8g2

OneBitDisplay

BitBang_I2C

SparkFun SCD4x Arduino Library

AnimatedGIF

thinger.io

Adafruit NeoPixel 


# Sending the code to the ESP:

Once the code is ready, click the "Build" button to verify if there are any errors.

![image](https://github.com/ricardocplima/ESP32-C3-0.42OLED_VSCode/blob/main/images/PlatformIO_Build.png)


If no problem occurs, click the "Upload" button. The port should be automatically selected, but if problems occur it is recommended to check the COM port used.

![image](https://github.com/ricardocplima/ESP32-C3-0.42OLED_VSCode/blob/main/images/PlatformIO_Upload.png)


To start, you can use the sample code included in the file "HelloWorld_Sample".


# Source

This repository was created using the following repository as inspiration, but applying it to VSCode:  https://github.com/01Space/ESP32-C3-0.42LCD
