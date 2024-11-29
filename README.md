# raspberry_pi_attendance
Raspberry Pi attendace system that I set up in 2020 for my Automatic Data Capture course.

This is a project that I completed to better understand how RFID sensors play a role in the industry today. However, through completing this project in full, it introduced me to a broad range of related areas in hardware and software such as the setup and installation of Python 3 and SQL from a CLI, installing and updating packages from a CLI, locating IP and MAC addresses within a network through the use of ARP commands, building a RFID reader circuit with a strong understanding of breadboard vs. GPIO pin functionality, ability to interpret wire diagrams, and just simply trobleshooting common issues. From bar coding to bluetooth, the internet of things is a diverse subject, so this project highlights most of the requirements necessary to set up a similar system. I navigated through the directions from Pi up my life and this project is the proof of its functionality. The two options for displaying data on this project were through the use of a simple web interface or from an embedded LCD. This project follows the Web Interface option to display data. All code was cloned from Github and can be found in the links below for reference.
-----
See excerpt below for References: https://github.com/pimylifeup/rfid-attendance-system-raspberry-pi & https://pimylifeup.com/raspberry-pi-rfid-attendance-system/#comment-24580

DEPRECATED LIBRARY. Adafruit Python CharLCD
This library has been deprecated! We are leaving this up for historical and research purposes but archiving the repository.

We are now only supporting the use of our CircuitPython libraries for use with Python.

Check out this guide for info on using character LCDs with the CircuitPython library: https://learn.adafruit.com/character-lcds/python-circuitpython

Adafruit_Python_CharLCD

Python library for accessing Adafruit character LCDs from a Raspberry Pi or BeagleBone Black.

Designed specifically to work with the Adafruit character LCDs ----> https://learn.adafruit.com/character-lcds/overview

For all platforms (Raspberry Pi and Beaglebone Black) make sure you have the following dependencies:

sudo apt-get update
sudo apt-get install build-essential python-dev python-smbus python-pip
For a Raspberry Pi make sure you have the RPi.GPIO library by executing:

sudo pip install RPi.GPIO
For a BeagleBone Black make sure you have the Adafruit_BBIO library by executing:

sudo pip install Adafruit_BBIO
Install the library by downloading with the download link on the right, unzipping the archive, navigating inside the library's directory and executing:

sudo python setup.py install
See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Tony DiCola for Adafruit Industries.
