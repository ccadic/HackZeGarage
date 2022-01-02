# HackZeGarage
ESP32-S2 and CC1101S 433Mhz usb stick to record and send car gates/garages data keys and open stuff

![alt text](https://github.com/ccadic/HackZeGarage/blob/main/images/20220101_232418.jpg)


**HackZeGarage

@sulfuroid / Dr CADIC Philippe
Portable USB Stick to replace garage doors and gate doors remote controls into one single 433 Mhz C1101 transceiver device. Data bank of gates digital signatures. 

The ESP32 C1101 USB stick to ease the access to garages and parkings using 433 Mhz remote keys. HackZeGarage is a USB stick with ESP32 S2, battery and charging module with 3 buttons and a SSD1306 Oled display. This item can also be used as a passwords data bank.

**UPLOADING SKETCHES**

Uploading sketches onto an ESP32S2 is a bit tricky. You have to plug the device onto the USB port of the PC running Arduino IDE. Then, you have to press RST and BOOT micro switch respecting this order :
1.	Press both  RESET & BOOT switches
2.	Release RESET switch
3.	Then release BOOT
If it is done properly , you should ear the computer recognize the device and a COMx port should appear.

