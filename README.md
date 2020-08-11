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
    USB/UART TTL Converter used here is 6 pins.
    USB to PC.
    
    DTR -> DTR ( of pro mini)
    Tx -> Rx (of pro mini)
    Rx -> Tx
    Vcc -> Vcc
    GND -> GND
    
 2. Connect RFID reader to Pro mini
    Vcc -> Vcc (of RFID)
    GND -> GND (of RFID)
    Digital pin 4 -> Tx (of RFID)  ----- Pin 4 of pro mini acts as input ( or receiver ) to receive RFID tag
    Digital pin 2 -> Rx( of RFID) 
    Antennas connected
