Steps to getting the program running:
1. Download the Arduino Software from their website.
2. Download this repo to your computer.
3. Download this library to your computer: https://github.com/rambo/I2C
4. Open "Flextrack.ino". This is the file that we will actually upload to the Arduino.
5. Change values as necessary in the file such as upload interval and callsign.
6. Connect Arduino board and upload. 


## BELOW INFORMATION IS FROM DAVEAKE'S FLEXTRACK REPO

## FlexTrack 

Flexible Arduino-based tracker software for RTTY, LoRa and APRS.

This fork is configured for Habduino V4.X boards. 

This code provides simultaneous (where legal and supported by the hardware installed) transmission of radio telemetry via RTTY and APRS on Habduino Arduino addon boards for High Altitude Ballooning.

## Libraries

To build FlexTrack for use with a HABDuino or other tracker using I2C communications, you need to install this library into your Arduino IDE:

[https://github.com/rambo/I2C](https://github.com/rambo/I2C) 

## Disclaimer

The FlexTrack code is provided as is with no guarantees of performance or operation. 

If you decide to use this code under a balloon it’s your responsibility to ensure you comply with the local legislation and laws regarding meteorological balloon launching and radio transmission in the air. 
The Radiometrix NTX2B 434Mhz is NOT license exempt in the United States of America and does need a radio amateur license.

Use of APRS requires a radio amateur license in all countries and a number of countries don’t permit the airborne use of APRS under any circumstances. 

It is YOUR responsibility to ensure Habduino hardware and code is used safely and legally please review the safety section on the website. 

## Further Reading on High Altitude Ballooning

Please read this http://www.daveakerman.com/?p=1732

## License

The hardware design & code for Habduino is released under a Creative Commons License 3.0 Attribution-ShareAlike License : http://creativecommons.org/licenses/by-sa/3.0/
