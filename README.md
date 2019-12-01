# I2C/IIC/I²C-VHDL-Model
This is my Final year project, it consists on developping a VHDL Model of the I2C Bus.
We are going to start this project with defining the different components, functionalities, specificities and drivers that need to be considered while creating the models.
## I2C-Bus: What’s that?
The I2C bus was designed to allow easy communication between components (low-speed devices like microcontrollers, EEPROMs, A/D and D/A converters, I/O interfaces and other similar peripherals in embedded systems) which reside on the same circuit board.  
![FACV3E9JK10S48J LARGE](https://user-images.githubusercontent.com/35849581/69913430-6ac55080-1440-11ea-91ee-bdce19c7cfd2.jpg)  
I2C Bus is easy to use, most significant features are:  
 * Only 2 wires with pull-up resistors are needed to connect unlimited number of I2C devices:  
      1.SDA: Serial Data line controlled by Master and Slave  
      2.SCL: Serial Clock generated by Master.  
 * Synchronous and Half duplex.
 * A true multi-master and multi-slave bus.  
 * Each device connected to the bus is software-addressable by a unique address.    
 ## Communication Mode ( Baude Rate)  
  * Slow Mode: 100Kb/sec  
  * Fast Mode: 400Kb/sec  
  * High Speed Mode: 3.4Mbit/sec  
  * Fast Mode Plus 1Mhz  
  * Ultra Fast Mode 5Mhz ( is no real I2C).  
  
 
