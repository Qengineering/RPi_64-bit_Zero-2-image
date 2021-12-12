# Raspbeery Pi Zero 2 64-bit OS image
![output image]( https://qengineering.eu/images/SDcard16GBZero2.webp )<br/>
## A Raspberry Pi Zero 2 64-bit OS Buster with OpenCV, TensorFlow Lite and ncnn
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
The installation of the 64-bit operating system on the new Raspberry Pi Zero 2 is somewhat cumbersome.<br/>
We have all the hard work done for you. Enjoy!

------------

## Installation.

- Get a 16 GB SD-card which will hold the image. 
- Download the image RPi_64OS_DNN.zip (3.5 GByte!) from our [Gdrive](https://drive.google.com/file/d/1wJeuIGhs-49lcPQDJoM-AF-IdkAODVYe/view?usp=sharing) site.
- Flash the image on the SD-card with the [Imager](https://www.raspberrypi.org/software/) or [balenaEtcher](https://www.balena.io/etcher/).
- Insert the SD-card in your Raspberry Pi Zero 2 and enjoy.
- No WiFi installed. Password: ***3.14***

------------

## Remarks.

* You can [overclock the Raspberry Pi Zero 2](https://qengineering.eu/install-64-os-on-raspberry-pi-zero-2.html) if your SD-card is not too worn out. 1200 MHz is no problem. Most deep learning examples even work at 1300 MHz.<br/>
* If you are in need of extra space, you can delete the opencv and the opencv_contrib folder from the SD-card. There are no longer needed since all libraries are placed in the /usr/local directory.
* Use a tool like [GParted](https://gparted.org/) `sudo apt-get install gparted` to expand the 16 GB image to larger SD-cards.
* Chromium, just like FireFox, will not work due to graphic rendering issues.
* Please note, the Raspberry Pi Zero 2 is a very new device. Lost of (software) updates can be expected in the coming months.
* We commit several deep learning benchmarks. Read all about them at our [site](https://qengineering.eu/install-64-os-on-raspberry-pi-zero-2.html)<br/>
* Most worrying was stuttering behaviour while working with the 64-bit operating system on the Raspberry Pi Zero 2. It wasn't snappy at all. Below compile times of gcc. Look at the 94 seconds it takes to do the job on the 64-bit version, as where the 32-bit OS can do it in 22. You can imagine we are not over-enthusiastic about the current 64-bit Bullseye version on a Raspberry Pi Zero 2.<br/>

![output image](https://qengineering.eu/images/gcc_timing.png)<br/>
Hopefully, the Pi team will release a genuine Zero 2 64-bit version.

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

