# AESase-RFID-Josephrexon

Low Level Abstraction - RFID Access control system

This project is to implement the automatic door access control to the registered users and to avoid intruder detection. Since this is low level abstraction, the main focus is on hardware and microcontroller coding. 

# Architecture:

Please refer the block diagram in AESase-RFID-Josephrexon/Architecture

# Prerequisites:
1. RFID reader RDM6300
2. Arduino pro mini ATMega 168, 3.3V, 8MHz
3. Arduino uno
4. Jumper wires
5. USB to UART TTL converter ( to connect pro mini to PC )

# Hardware connections

1. Connect Pro mini to USB/UART converter.
    1. USB/UART TTL Converter used here is 6 pins.
    2. USB to PC.
    
    3. DTR -> DTR ( of pro mini)
    4. Tx -> Rx (of pro mini)
    5. Rx -> Tx
    6. Vcc -> Vcc
    7. GND -> GND
    
 2. Connect RFID reader to Pro mini
    1. Vcc -> Vcc (of RFID)
    2. GND -> GND (of RFID)
    3. Digital pin 4 -> Tx (of RFID)  ----- Pin 4 of pro mini acts as input ( or receiver ) to receive RFID tag
    4. Digital pin 2 -> Rx( of RFID) 
    5. Antennas connected


# Reference
https://www.mschoeffler.de/2018/01/05/arduino-tutorial-how-to-use-the-rdm630-rdm6300-rfid-reader/
