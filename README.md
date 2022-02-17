# Raspbeery Pi Zero 2 64-bit OS image
![output image]( https://qengineering.eu/images/SDcard16GBZero2.webp )<br/>
## A Raspberry Pi Zero 2 64-bit OS Bullseye with OpenCV, TensorFlow Lite and ncnn
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/>
## Installation.

- Get a SD-card which will hold the image (min 16 GB). 
- Download the image RPi_64OS_Zero_2.xz (1.7 GByte!) from our [Gdrive](https://drive.google.com/file/d/1VPpalGylbriNlVggF35PeVApsVFXwlHv/view?usp=sharing) site.
- Flash the image on the SD-card with the [Imager](https://www.raspberrypi.org/software/) or [balenaEtcher](https://www.balena.io/etcher/).
- Insert the SD-card in your Raspberry Pi Zero 2.
- Wait a few minutes, while the image will expand to the full size of your SD card.
- No WiFi installed. Password: ***3.14***

------------

## Remarks.

* You can [overclock the Raspberry Pi Zero 2](https://qengineering.eu/install-64-os-on-raspberry-pi-zero-2.html) if your SD-card is not too worn out. 1200 MHz is no problem. Most deep learning examples even work at 1300 MHz.<br/>
* If you are in need of extra space, you can delete the opencv and the opencv_contrib folder from the SD-card. There are no longer needed since all libraries are placed in the /usr/local directory.
* Please note, the Raspberry Pi Zero 2 is a very new device. Lost of (software) updates can be expected in the coming months.
* We commit several deep learning benchmarks. Read all about them at our [site](https://qengineering.eu/install-64-os-on-raspberry-pi-zero-2.html)<br/>
* As explained on the website, you have only 100 MB of free RAM for your applications left once the 64-bit Bullseye is loaded. To enlarge the amount of RAM to more practical sizes, we use a large swapping space. It will wear your SD card when used intensively. It also slows down the performance, as you can see in the graph below. The 64-bit Ubuntu server was faster, but it doesn't have a graphical desktop. Only a terminal input. And for those unfamiliar with Ubuntu, the desktop is only possible with 4 GB of RAM onboard.<br/>

![output image](https://qengineering.eu/images/gcc_timing4.png)<br/>

------------

## Pre-installed frameworks.

- [OpenCV](https://qengineering.eu/deep-learning-with-opencv-on-raspberry-pi-4.html) 4.5.4
- [ncnn](https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) 20210124
- [TensorFlow-Lite](https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-64-os.html) 2.6.0

------------

## WiFi.

Since everyone has a unique password on their WiFi connection, we have not activated the WiFi.<br/>
To enable the wireless LAN follow the next steps:<br/>

1) Left click on the Ethernet symbol.<br/><br/>
![image](https://user-images.githubusercontent.com/44409029/124445112-8eb8e880-dd7f-11eb-80e6-121dc31fd0b8.png)<br/><br/>
2) Click "Turn on wireless LAN", and wait a few seconds. Your RPi will scan for available networks.<br/><br/>
![image](https://user-images.githubusercontent.com/44409029/124445876-39310b80-dd80-11eb-97ff-1ef8f8c477e8.png)<br/><br/>
3) Left click again on the Ethernet symbol and choose your network.<br/><br/>
![image](https://user-images.githubusercontent.com/44409029/124446101-64b3f600-dd80-11eb-9385-eee4fd730268.png)<br/><br/>
4) Give your key, and wait a couple of seconds to let the RPi establish the connection.<br/><br/>
![image](https://user-images.githubusercontent.com/44409029/124447227-74800a00-dd81-11eb-9c47-bee6b2b84bc1.png)<br/><br/>
5) Success! <br/><br/>
![image](https://user-images.githubusercontent.com/44409029/124446775-063b4780-dd81-11eb-9fd8-2d597ad31cee.png)

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 

