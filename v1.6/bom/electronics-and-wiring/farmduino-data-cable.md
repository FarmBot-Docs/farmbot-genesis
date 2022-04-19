---
title: "Farmduino Data Cable"
slug: "farmduino-data-cable"
description: "This USB cable is used as a serial connection between the Raspberry Pi and the Farmduino."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/9aec84ac1796932e638c27a2?renderMode=0&uiState=6255d9ec46b4a5023f0ae117
price: $5.00
quantity:
  standard: 1
  xl: 1
specs:
  connector 1: Right-angle USB 2.0 Type A Male
  connector 2: Right-angle USB 2.0 Type B Male
  length: 150mm
  color: Black
internal-specs:
  internal-part-name: Farmduino Data Cable
  rev: A
  cost: $1.30
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Cable        |Inspect the cable spec.|`Shielded 28AWG/1p + 24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Connectors   |Connect the cable to a Raspberry Pi and Farmduino inside a fully assembled electronics box.|The cable should connect to both circuit boards without interference from the box or other components.|N/A
|Length       |Measure the length using a measuring tape.|150mm|+/- 10mm
|Color        |Inspect the color of the cable.|Black|N/A
