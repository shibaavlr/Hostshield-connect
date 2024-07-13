Here is how you can connect an Arduino Leonardo with a USB Host Shield to send X and Y coordinates via UDP for controlling movements, such as in Valorant.

Components Needed:
Arduino Leonardo
USB Host Shield
USB cable
Computer with Arduino IDE installed
Steps:
Connect the USB Host Shield to the Arduino Leonardo:

Attach the USB Host Shield on top of the Arduino Leonardo.
Install the Required Libraries:

Open the Arduino IDE and install the USBHost and Ethernet2 libraries if they are not already installed. The USBHost library will allow you to interface with USB devices.
Write the Code:

Use the following code to set up UDP communication and send X and Y coordinates.
