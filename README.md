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
    a) USB/UART TTL Converter used here is 6 pins.
    b) USB to PC.
    
    c) DTR -> DTR ( of pro mini)
    d) Tx -> Rx (of pro mini)
    e) Rx -> Tx
    f) Vcc -> Vcc
    g) GND -> GND
    
 2. Connect RFID reader to Pro mini
    a) Vcc -> Vcc (of RFID)
    b) GND -> GND (of RFID)
    c) Digital pin 4 -> Tx (of RFID)  ----- Pin 4 of pro mini acts as input ( or receiver ) to receive RFID tag
    d) Digital pin 2 -> Rx( of RFID) 
    e) Antennas connected
