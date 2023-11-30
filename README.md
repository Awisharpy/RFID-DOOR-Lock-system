# RFID-DOOR-Lock-system
The RFID Door Lock System offers secure access with RFID cards or key fobs. Swipe or tap for quick entry, eliminating traditional keys. Enhance security effortlessly.

# What is RFID?
Radio Frequency Identification (RFID) is a wireless use of radiofrequency waves to transfer data. Using RFID tags allows users to autonomously and uniquely identify and track inventory and assets. RFID makes auto-ID technology much more feasible by allowing tags to be read without a line of sight and, depending on the type of RFID, having a read range between a few centimeters to over 20+ meters.

RFID has been innovated a lot from its first use of identifying airplanes as friends or enemies in World War II. Not only does the technology continue to improve year over year, but it is becoming more economical with each passing day, making RFID more cost-effective and efficient. 

# The working concept of the RFID door lock
At a rudimentary level, RFID systems consist of three main components: an RFID tag or smart label, an RFID reader, and an antenna. RFID tags contain an IC and an antenna, which are used to transmit data to the RFID reader (also called an interrogator). Each RFID tag has its key. So when the RFID tag has been scanned by the reader, it tries to find whether the key of the tag matches the authorized key. If the key matches, then it can be assigned a specific function. This has to be done via changes in the code in Arduino IDE. 

So once the key matches, the RFID reader sends the signal to the Arduino board. The board in turn sends another signal to the SG90 micro servo. The micro servo is attached to the door handle in such a way that whenever the servo rotates the door opens.

# Codes used
1) The First Code is used to scan RFID TAGs and UID is generated.
2) The Second Code basically scans and checks if the UID aligns with the stored UID.
