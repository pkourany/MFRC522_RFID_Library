RFID
====

Update for Libraries 2.0 by Paul Kourany, Jan 2017 - v1.0.3
Adapted for Spark Core by Paul Kourany, May 2014

v0.1.2 - SOS bug fixed, now compatible with all Particle devices

Read a card using a mfrc522 reader on your SPI interface on your Arduino
* Pin layout should be as follows (on Spark Core):
* MOSI: Pin A5
* MISO: Pin A4
* SCK : Pin A3
* SS  : Pin A2	(Configurable)
* RST : Pin D2	(Configurable)
* 

Arduino RFID Library for MFRC522

Read a card using a mfrc522 reader on your SPI interface on your Arduino
* Pin layout should be as follows (on Arduino Uno):
* MOSI: Pin 11 / ICSP-4
* MISO: Pin 12 / ICSP-1
* SCK : Pin 13 / ISCP-3
* SS  : Pin 10 (Configurable)
* RST : Pin 9  (Configurable)
* 

* Pin layout should be as follows (on Arduino Mega):
* MOSI: Pin 51 / ICSP-4
* MISO: Pin 50 / ICSP-1
* SCK : Pin 52 / ISCP-3
* SS  : Pin 53 (Configurable)
* RST : Pin 5  (Configurable)
