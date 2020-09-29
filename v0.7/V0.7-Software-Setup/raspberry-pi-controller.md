---
title: "Raspberry Pi Software"
slug: "raspberry-pi-controller"
excerpt: "Step-by-step instructions for installing the necessary FarmBot software onto the Raspberry Pi"
---

* toc
{:toc}

The Raspberry Pi is the brain of your FarmBot and has several pieces of software installed on it that allow it to:

* Communicate with the web application via meshblu over WiFi or ethernet in order to synchronize (download) the latest schedules and sequences, and upload the latest logs and sensor data.
* Communicate with the Arduino via [farmbot-serial](https://github.com/FarmBot/farmbot-serial) over USB to send G and F commands and receive sensor data
* Take photos with a USB web cam, and stream video back to the web application

The Raspberry Pi will need to have the following pieces of software installed in order for FarmBot to work:

1. An operating system - we recommend FarmBot OS (coming soon) which is just [Raspbian](https://www.raspbian.org/) with everything else FarmBot needs already bundled together.
2. [farmbot-raspberry-pi-controller](https://github.com/FarmBot/farmbot-raspberry-pi-controller)
3. [farmbot-serial](https://github.com/FarmBot/farmbot-serial) - This is a ruby gem, meaning it is automatically bundled in with the controller program. You will not need to manually download and install this unless you do everything from scratch.
4. Coming soon: [wifi-configurator](https://github.com/FarmBot/wifi-configurator) - this component will be optional, but make your life MUCH easier in the future. This piece of software allows the Pi to create its own wifi network whenever it cannot connect to the Internet. This allows you to enter wifi credentials, access a terminal, and view and change device settings from your laptop, phone, or tablet.

Below, we offer two methods for installing the necessary software. The first method is the easiest and fastest and meant for non-technical and advanced users alike. The second method will take much longer but is potentially a good learning experience for users wanting to know how to hack their FarmBot's Raspberry Pi. The second method is recommended for advanced users only.

{%
include callout.html
type="info"
title="Another computer is required"
content="Whicever method you choose, you will need another computer with a microSD card reader to install the Raspberry Pi software."
%}



# The Easy Method (Coming Soon)

In this method, we will install FarmBot OS (coming soon) - a version of [Raspbian](https://raspbian.org) with [farmbot-raspberry-controller](https://github.com/FarmBot/farmbot-raspberry-pi-controller), [farmbot-serial](https://github.com/FarmBot/farmbot-serial), and [wifi-configurator](https://github.com/FarmBot/wifi-configurator) (coming soon) bundled together in one package. Once you install FarmBot OS onto your Raspberry Pi, everything should be good to go.

# Step 1: Download FarmBot OS
Download FarmBot OS here (coming soon).

After downloading the .zip file, unzip it to get the image file (.img) for writing to your microSD card.

# Step 2. Write FarmBot OS to the microSD card

You need to use an image writing tool to install FarmBot OS onto your microSD card. Follow the instructions provided by RaspberryPi.org for your operating system:

* [Linux](https://www.raspberrypi.org/documentation/installation/installing-images/linux.md)
* [Mac OS](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md)
* [Windows](https://www.raspberrypi.org/documentation/installation/installing-images/windows.md)

# Step 3. Prepare the Raspberry Pi
* Plug your microSD card into the Raspberry Pi
* Plug your Arduino into the Raspberry Pi with a USB cable
* Plug an ethernet cord or a USB WiFi dongle into the Raspberry Pi
* Optional: plug in a USB camera to the Raspberry Pi

# Step 4. Turn on the Raspberry Pi
Plug in the power source to the Raspberry Pi. Depending on your setup, power will be coming from either a standard microUSB cable plugged into a standalone power supply, from a DC/DC buck converter coming from your RAMPS shield, or straight from your FarmBot's power supply. Note: The power supplied must be rated to 5V and at least 1A, though 2A is recommended.

# Step 5. Configure your FarmBot
Using a phone, tablet or laptop, search for the WiFi network 'FarmBot Wifi'.

{%
include callout.html
type="success"
title="Check the web app"
content="If all has gone well during your setup, you should now see your FarmBot 'Online' in the web application interface."
%}



# The Hard Method



{%
include callout.html
type="warning"
title="For advanced users only"
content="For hackers and software developers who want to know the ins and outs of installing and maintaining the FarmBot software on their Raspberry Pi, the following steps are for you. Non-technical users should use the 'The Easy Method' above"
%}

# Step 1: Download and install an OS
We recommend using [Raspbian](https://www.raspbian.org/) - the stock operating system most people use on their Raspberry Pi's. Follow the instructions provided from Raspbian or the OS of your choice to install the OS onto your microSD card.

# Step 2:
