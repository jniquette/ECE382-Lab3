ECE382-Lab2 MSP430 SPI I/O
======================================

##Purpose
This project demonstrates how to use the MSP430's built in Serial Peripheral Interface to interact with a slave device. In this lab, the slave device is a STE2007 (96 x 68 Single Chip LCD Controller/Driver) attached to a Nokia 1202 LCD Boosterpack. We will demonstrate use of the SPI by transmitting commands from our MSP430G2553 to the LCD to draw a square on the screen. Additionally, in/out procedures will be demonstrated by using the SPI to poll for button events from the Boosterpack.

##Prelab
The Mega Prelab for this lab can be found in Lab 3 Prelab.docx

##Code
All code for this project can be found in code/lab3.asm.

##Logic Analyser Screenshots:
####Reset:
![alt text](https://github.com/jniquette/ECE382-Lab3/blob/master/img/RESET.png "Reset")
####S3, Byte 1:
![alt text](https://github.com/jniquette/ECE382-Lab3/blob/master/img/S3_byte1.png "S3_Byte1")
####S3, Byte 2:
![alt text](https://github.com/jniquette/ECE382-Lab3/blob/master/img/S3_byte2.png "S3_Byte2")
####S3, Byte 3:
![alt text](https://github.com/jniquette/ECE382-Lab3/blob/master/img/S3_byte3.png "S3_Byte3")
####S3, Byte 4:
![alt text](https://github.com/jniquette/ECE382-Lab3/blob/master/img/S3_byte4.png "S3_Byte4")

##Drawing Modes
![alt text](https://github.com/jniquette/ECE382-Lab3/blob/master/img/Drawing%20Modes.png "Drawing Modes")

##Observations
Even when using 0xFF as the data byte when writing to the LCD, only 6 pixels are displayed.


##Documentation Statement
Nothing to report.