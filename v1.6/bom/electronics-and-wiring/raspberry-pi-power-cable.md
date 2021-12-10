---
title: "Raspberry Pi Power Cable"
slug: "raspberry-pi-power-cable"
description: "This USB cable provides power to the Raspberry Pi from the Farmduino's built-in 12v to 5v to USB circuitry."
price: $5.00
quantity:
  genesis: 1
  xl: 1
specs:
  Connector 1: Right-angle USB 2.0 Type A Male
  Connector 2: Right-angle microUSB 2.0 Male
  Length: 300mm
  Color: Black
internal-specs:
  Internal Part Name: Raspberry Pi Power Cable
  $/pc: $1.19
  Notes: Samples received in July 2020
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Cable        |Inspect the cable spec.|`Shielded 28AWG/1p+24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Connectors   |Connect the cable to a Raspberry Pi and Farmduino inside a fully assembled electronics box.|The cable should connect to both circuit boards without interference from the box or other components.|N/A
|Length       |Measure the length using a measuring tape.|300mm|+/- 10mm
|Voltage drop |Use USB voltage monitors to check the voltage before and after the cable.|Less than 5% voltage drop|4.9V output minimum
|Color        |Inspect the color of the cable.|Black|N/A
