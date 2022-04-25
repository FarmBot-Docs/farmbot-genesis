---
title: "High Level Software Overview"
slug: "high-level-software-overview"
description: "Description of the FarmBot Software Toolchain"
---

As shown below, there are six main components of the FarmBot software tool chain. Read the descriptions of each to understand the system as a whole, and then dive into setting up the necessary components for your FarmBot system.

1. [The FarmBot Web Application](https://github.com/FarmBot/farmbot-web-app) allows you to program and control your FarmBot from a web browser. You can host the web application yourself on your own servers, or use the [My FarmBot](http://my.farmbot.cc) service.
2. [Meshblu](https://github.com/FarmBot/meshblu) is a cloud application that acts as an intermediary between the FarmBot web application and FarmBot devices. It handles socket connections, device identification, and authentication. You can host a version of meshblu yourself or use the one already linked to the [My FarmBot](http://my.farmbot.cc) service.
3. The Raspberry Pi uses a piece of software called [farmbot-raspberry-pi-controller](https://github.com/FarmBot/farmbot-raspberry-pi-controller). This maintains a connection and synchronizes with the web application via meshblu, in order to download scheduled events and commands, and upload logs and sensor data.
4. The Raspberry Pi uses [farmbot-serial](https://github.com/FarmBot/farmbot-serial) to communicate G and F code commands to the Arduino over USB.
5. The Arduino runs [Farmbot Arduino Firmware](https://github.com/FarmBot/farmbot-arduino-controller) allowing it to move motors, read and write pins, and communicate with the Raspberry Pi over USB via farmbot-serial.
6. Coming soon: The Raspberry Pi has a utility called [wifi-configurator](https://github.com/FarmBot/wifi-configurator) allowing you to easily login to the Pi from a wifi enabled device to access a terminal and some configuration settings when the Pi cannot connect to the Internet.
