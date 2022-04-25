---
title: "Arduino Firmware"
slug: "arduino-controller"
description: "Step-by-step instructions for installing the farmbot-arduino-controller software onto the Arduino"
---

[The Farmbot Arduino Firmware](https://github.com/FarmBot/farmbot-arduino-controller) performs the following tasks:

 * Physically controls the device by sending electrical pulses to the motor drivers, reading voltages from pins, and outputting voltages and data to the Universal Tool Mount
 * Communicates with the Raspberry Pi over USB cable in order to receive commands and send back log and collected data.

# Step 1: Install the Arduino Firmware

The FarmBot Arduino Firmware can be flashed onto the device using a standard Raspberry Pi or Linux desktop computer.

To install the firmware:

 1. Connect the Arduino to the Raspberry Pi via USB cable.
 2. Open the `LXTerminal` application.
 3. Follow the instructions listed at the [official Github repository](https://github.com/FarmBot/farmbot-arduino-controller#command-line-flash-tool-installation)
