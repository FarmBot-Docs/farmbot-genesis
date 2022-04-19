---
title: "Motor Cable"
slug: "motor-cable"
description: "These 4-wire cables connect each NEMA 17 stepper motor to the Farmduino. They are labelled on the Farmduino end X1, X2, Y, and ZY. The Z-axis cable is split into a Y-axis section labelled ZY and a Z-axis section labelled ZZ that connect with a 90-degree screw-together waterproof connection at the cross-slide."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/32e8a0490e24b015a1cafbe3?configuration=default&renderMode=0&uiState=6255db0c46b4a5023f0ae54e
variants: X1, 0.7m|X2, 2.3m|Y, 2.7m|ZY, 2.6m|X2, 3.8m|Y, 4.2m|ZY, 4.1m|ZZ, 1.8m
price: $20.00|$23.00|$25.00|$27.00|$28.00|$30.00|$32.00|$24.00
quantity:
  standard: 1|1|1|1|0|0|0|1
  xl: 1|0|0|0|1|1|1|1
specs:
  length: 0.7m|2.3m|2.7m|2.6m|3.8m|4.2m|4.1m|1.8m
  Cores: 4
  Gauge: 18
  Motor connector: 6 pin connector (only 4 pins used)
  Intermediate connector: 4-pin waterproof screw together 90 degree connectors. (female connector on the Y-Axis sections, male connector on the Z-Axis section)
  Farmduino connector: 2.54mm pitch 4-pin connector with locking tab (<a href="https://www.molex.com/molex/products/part-detail/crimp_housings/0050579404">Molex Part 50579404</a>)
  Outer color: Black
  Inner Colors: Black, Red, Yellow, White
  Label: X1|X2|Y|ZY|X2|Y|ZY|ZZ
internal-specs:
  internal-part-name: "Motor Cable - X1, 0.7m (Genesis and Genesis XL)|
  Motor Cable - X2, 2.3m (Genesis)|
  Motor Cable - Y, 2.7m (Genesis)|
  Motor Cable - ZY, 2.6m (Genesis)|
  Motor Cable - X2, 3.8m (Genesis XL)|
  Motor Cable - Y, 4.2m (Genesis XL)|
  Motor Cable - ZY, 4.1m (Genesis XL)|
  Motor Cable - ZZ, 1.8m (Genesis and Genesis XL)|"
  cost: $1.60|$2.10|$2.30|$3.90|$2.90|$3.10|$4.70|$3.80
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the cable's diameter using digital calipers.|5mm|+/- 1mm
|Connectors   |Use a motor cable to connect a motor to the Farmduino. Issue some movement commands.|The motor should operate as expected|N/A
|Label        |Inspect the shrinkwrap labels.|X1, X2, Y, ZY, and ZZ|N/A
|Cable        |Inspect the cable's spec.|24AWG-4C stranded copper cable|N/A
|Color        |Inspect the color of the cable.|Black|N/A
