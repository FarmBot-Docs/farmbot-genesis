---
title: "Arduino Firmware"
slug: "arduino-firmware"
excerpt: "Step-by-step instructions for installing farmbot-arduino-firmware onto the Arduino"
---

* toc
{:toc}

The [Farmbot Arduino Firmware](https://github.com/FarmBot/farmbot-arduino-firmware) performs the following tasks:

 * Physically controls the FarmBot hardware by sending electrical pulses to the stepper motor drivers, reading voltages from pins, and outputting voltages and data to the Universal Tool Mount
 * Communicates with the Raspberry Pi via a serial connection over a USB cable in order to receive G-code and F-code commands and send back log and collected data.
 * Monitors the rotary encoders as a closed-loop feedback control system to ensure that the stepper motors have not missed any steps. (Coming soon)

Below, we describe three methods for installing the Arduino Firmware onto the Arduino. Most users will use the first method.

{%
include callout.html
type="success"
title="Help Improve the Arduino Firmware"
content="Found some bugs? Have a feature request or improved code you would like to contribute? Let us know by opening up an issue or submitting a pull request on the [GitHub repository for the FarmBot Arduino Firmware](https://github.com/FarmBot/farmbot-arduino-firmware)."
%}



{%
include callout.html
type="info"
title="Want to Hack?"
content="There is more technical documentation about the FarmBot Arduino Firmware in the [README file](https://github.com/FarmBot/farmbot-arduino-firmware/blob/master/README.md)."
%}



# Installation from the Web App (Easiest Method, Coming Soon!)



{%
include callout.html
type="info"
title="Requires FarmBot OS"
content="This firmware installation method is for people who installed FarmBot OS on their Raspberry Pi. If you installed a different OS, then you will need to use one of the other firmware installation methods below."
%}

1. Plug your Arduino into the Raspberry Pi using a USB cable.
2. Login to the FarmBot Web Application and go to the **Device** page.
3. In the **Software** widget, click the **Update** button next to the Arduino version. This will tell the Raspberry Pi to download the latest Arduino firmware and install it onto the Arduino. Note: This may take a few minutes. Do not press the Update button more than once.
4. Once the installation process is complete, the software widget on the web application should show that the latest firmware is installed. There is no need to 'start' the firmware program because as long as the Arduino has power and a connection to the Raspberry Pi, the firmware will be running.

{%
include callout.html
type="success"
title="It's ALLIIIIVVVEEEEE!!!"
content="Go the **Manual Control** page of the web application and click a movement button. If everything is working, FarmBot should move. Go ahead and have some fun with the manual controls! You're FarmBot is almost ready for growing plants! Muahahaha!!"
%}



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F0VkrUG3OrPc%3Ffeature%3Doembed&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D0VkrUG3OrPc&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F0VkrUG3OrPc%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>



# Installation from the Command Line



{%
include callout.html
type="info"
title="For advanced users"
content="This firmware installation method is to be used by people who installed an OS other than FarmBot OS onto the Raspberry Pi."
%}

# Step 1: Install the Command Line Flash Tool onto the Pi

First, we need to install some software onto the Raspberry Pi that will allow us to flash (load) the Arduino firmware onto the Arduino. This is an important step because it will allow you to easily update the Arduino firmware from the web application in the future!

From a terminal on the Raspberry Pi, enter the following commands:


__Install the Command Line Flash Tool:__

```text
sudo apt-get install gcc-avr avr-libc avrdude python-configobj python-jinja2 python-serial
mkdir tmp
cd tmp
git clone https://github.com/miracle2k/python-glob2
cd python-glob2
wget https://bootstrap.pypa.io/ez_setup.py -O - | sudo python
sudo python setup.py install
git clone git://github.com/amperka/ino.git
cd ino
sudo make install
```

# Step 2: Clone the Arduino Firmware Repository

Now we need to download (clone) the latest Ardiuno firmware onto the Raspberry Pi. From a terminal on the Raspberry Pi, enter the following command:


__Clone the Arduino Firmware Repository:__

```text
git clone https://github.com/FarmBot/farmbot-arduino-firmware.git
```

# Step 3: Install the Arduino Firmware

Now we're going to tell the Raspberry Pi to flash (load) the Arduino firmware onto the Arduino.

Plug your Arduino into the Raspberry Pi using a USB cable. From a terminal on the Raspberry Pi, enter the following commands:


__Install the Arduino Firmware:__

```text
cd farmbot-arduino-firmware
ino build
ino upload
```



{%
include callout.html
type="success"
title="All Done!"
content="If all went smoothly, you should receive a confirmation in the terminal that the firmware has uploaded correctly. From here on out, whenever the Arduino has power, the firmware will be running - there is no need to 'start the firmware'. Just make sure there is power and a good connection with the Raspberry Pi.

Furthermore, your Raspberry Pi is now capable of updating the Arduino firmware with one click from the Web App. Just go to the Device page, and look for the Update button in the Software widget."
%}



# Installation from the Arduino IDE

If you did not install FarmBot OS and you do not want to install the command line flash tool you can still install the Arduino Firmware by using the standard Arduino IDE with the steps below.

{%
include callout.html
type="warning"
title="Manual Updates Only"
content="Note that this method is not recommended because in the future you will not be able to update the Arduino firmware with one click from the FarmBot web application. Instead, you will have to manually download the latest firmware and manually install it with the Arduino IDE each time there is a new release of the software."
%}

1. Download and install the [Arduino IDE](https://www.arduino.cc/en/Main/Software) onto your computer
2. Download and unzip the latest [FarmBot Arduino Firmware](https://github.com/FarmBot/farmbot-arduino-firmware/archive/master.zip)
3. In the firmware folder you just unzipped, go to the **src** sub-folder and open up **src** with the Arduino IDE. Note: this file is blank, but there are many other file tabs that should be automatically opened as well.
4. Connect your Arduino to your computer with a USB cable
5. From the IDE, click Tools > Board, and then select Arduino Mega 2560
6. Now click File > Upload. This will flash the firmware onto your Arduino
