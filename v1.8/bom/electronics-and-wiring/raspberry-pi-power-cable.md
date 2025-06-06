---
title: "Raspberry Pi Power Cable"
slug: "raspberry-pi-power-cable"
description: "This USB cable provides power to the Raspberry Pi from the Farmduino's built-in 12v to 5v to USB circuitry."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/39fd9b15b6fd66bc8bbef108?configuration=List_UkTucQjOe0Ti5f%3DType_C&renderMode=0&uiState=6255dbcb46b4a5023f0aea65
price: $5.00
quantity:
  standard: 1
  xl: 1
specs:
  connector 1: Right-angle USB 2.0 Type A plug
  connector 2: Right-angle USB-C plug
  length: 300mm
  color: Black
  cable: 28AWG/1p+24AWG/2c Shielded USB 2.0
internal-specs:
  internal-part-name: Raspberry Pi Power Cable - Type C
  rev: C
  cost: $1.19
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Cable        |Inspect the cable spec.|`Shielded 28AWG/1p + 24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Connectors   |Connect the cable to a Raspberry Pi and Farmduino inside a fully assembled electronics box.|The cable should connect to both circuit boards without interference from the box or other components.|N/A
|Length       |Measure the length using a measuring tape.|300mm|+/- 5mm
|Voltage drop |Use USB voltage monitors to check the voltage before and after the cable.|Less than 5% voltage drop|4.9V output minimum
|Color        |Inspect the color of the cable.|Black or White|N/A
