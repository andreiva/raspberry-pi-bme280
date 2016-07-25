
This piece of code was combined from several sources:

https://github.com/adafruit/Adafruit_BME280_Library
https://cdn-shop.adafruit.com/datasheets/BST-BME280_DS001-10.pdf
https://projects.drogon.net/raspberry-pi/wiringpi/i2c-library/

Tested on RASPBIAN JESSIE LITE
https://www.raspberrypi.org/downloads/raspbian/

Dependencies
sudo apt-get install libi2c-dev i2c-tools wiringpi

Compiling
gcc -Wall -std=c99 -o bme280 bme280.c -lwiringPi -lm

