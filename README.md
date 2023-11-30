# RFID-DOOR-Lock-system
The RFID Door Lock System offers secure access with RFID cards or key fobs. Swipe or tap for quick entry, eliminating traditional keys. Enhance security effortlessly.

# What is RFID?
Radio Frequency Identification (RFID) is a wireless use of radiofrequency waves to transfer data. Using RFID tags allows users to autonomously and uniquely identify and track inventory and assets. RFID makes auto-ID technology much more feasible by allowing tags to be read without a line of sight and, depending on the type of RFID, having a read range between a few centimeters to over 20+ meters.

RFID has been innovated a lot from its first use of identifying airplanes as friends or enemies in World War II. Not only does the technology continue to improve year over year, but it is becoming more economical with each passing day, making RFID more cost-effective and efficient. 

# Working Concept
At a rudimentary level, RFID systems consist of three main components: an RFID tag or smart label, an RFID reader, and an antenna. RFID tags contain an IC and an antenna, which are used to transmit data to the RFID reader (also called an interrogator). Each RFID tag has its key. So when the RFID tag has been scanned by the reader, it tries to find whether the key of the tag matches the authorized key. If the key matches, then it can be assigned a specific function. This has to be done via changes in the code in Arduino IDE. 

So once the key matches, the RFID reader sends the signal to the Arduino board. The board in turn sends another signal to the SG90 micro servo. The micro servo is attached to the door handle in such a way that whenever the servo rotates the door opens.

# What is ARDUINO?
➢ The Arduino UNO is an open-source microcontroller board based on the Microchip ATmega328P microcontroller and developed by Arduino.cc. The board is equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards (shields) and other circuits.
➢ The board has 14 Digital pins, 6 Analog pins, and programmable with the Arduino IDE (Integrated Development Environment) via a type B USB cable. It can be powered by a USB cable or by an external 9-volt battery, though it accepts voltages between 7 and 20 volts. It is also similar to the Arduino Nano and Leonardo.
➢ The hardware reference design is distributed under a Creative Commons Attribution Share-Alike 2.5 license and is available on the Arduino website. Layout and production files for some versions of the hardware are also available. "Uno" means one in Italian and was chosen to mark the release of Arduino Software (IDE) 1.0.
➢ The Uno board and version 1.0 of Arduino Software (IDE) were the reference versions of Arduino, now evolved to newer releases. The Uno board is the first in a series of USB Arduino boards and the reference model for the Arduino platform. The ATmega328 on the Arduino Uno comes preprogrammed with a bootloader that allows uploading new code to it without the use of an external hardware programmer. It communicates using the original STK500 protocol. The Uno also differs from all preceding boards in that it does not use the FTDI USB-to-serial driver chip. Instead, it uses the Atmega16U2 programmed as a USB-to-serial converter.

# LCD MODULE
LCD modules are very commonly used in most embedded projects, the reason being its cheap price, availability and programmer friendly. Most of us would have come across these displays in our day to day life, either at PCO’s or calculators. The appearance and the pinouts have already been visualized above now let us get a bit technical. 16×2 LCD is named so because; it has 16 Columns and 2 Rows. There are a lot of combinations available like 8×1, 8×2, 10×2, 16×1, etc. but the most used one is the 16×2 LCD. So, it will have (16×2=32) 32 characters in total and each character will be made of 5×8 Pixel Dots.

# SERVO MOTOR
A servo motor is an electrical device which can push or rotate an object with great precision. If you want to rotate an object at some specific angles or distance, then you use a servo motor. It is just made up of a simple motor which runs through a servo mechanism. If the motor is used is DC powered then it is called DC servo motor, and if it is AC powered motor then it is called an AC servo motor. We can get a very high torque servo motor in a small and lightweight package. Due to these features, they are being used in many applications like a toy car, RC helicopters, and planes, Robotics, Machine, etc.
Servo motors are rated in kg/cm (kilogram per centimeter) most hobby servo motors are rated at 3kg/cm or 6kg/cm or 12kg/cm. This kg/cm tells you how much weight your servo motor can lift at a particular distance. For example, A 6kg/cm Servo motor should be able to lift 6kg if the load is suspended 1cm away from the shaft of the motor, the greater the distance the lesser the weight carrying capacity.
The position of a servo motor is decided by an electrical pulse and its circuitry is placed beside the motor.

# IR Sensor
An infrared sensor is an electronic device, that emits in order to sense some aspects of the surroundings. An IR sensor can measure the heat of an object as well as detects the motion. These types of sensors measure only infrared radiation, rather than emitting it that is called a passive IR sensor. Usually, in the infrared spectrum, all the objects radiate some form of thermal radiations. These types of radiations are invisible to our eyes, that can be detected by an infrared sensor. The emitter is simply an IR LED (Light Emitting Diode) and the detector is simply an IR photodiode which is sensitive to IR light of the same wavelength as that emitted by the IR LED.
When IR light falls on the photodiode, The resistances and these output voltages, change in proportion to the magnitude of the IR light received.

# Components used
1) Plastic Box
2) Rfid Module
3) 12V solenoid Lock
4) Arduino nano
5) 1ch Relay Module
6) Some Jumper Wire
7) 5V TO 12v CONVERTOR
8) DC Socket
9) 5V adapter
   
# Codes used
1) The First Code is used to scan RFID TAGs and UID is generated.
2) The Second Code basically scans and checks if the UID aligns with the stored UID.
3) Tip before running any code make sure to install I2C, SPI, and RFID libraries.
