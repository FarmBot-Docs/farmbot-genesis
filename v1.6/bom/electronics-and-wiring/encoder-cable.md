---
title: "Encoder Cable"
slug: "encoder-cable"
description: "These cables connect the four rotary encoders to the Farmduino. They are labelled on the Farmduino end X1, X2, Y, and ZY. The Z-axis cable is split into a Y-axis section labelled ZY and a Z-axis section labelled ZZ that connect with a 90-degree screw-together waterproof connection at the cross-slide."
variants: X1, 0.7m|X2, 2.3m|Y, 2.7m|ZY, 2.6m|X2, 3.8m|Y, 4.2m|ZY, 4.1m|ZZ, 1.8m
price: $20.00|$23.00|$25.00|$27.00|$28.00|$30.00|$32.00|$24.00
quantity:
  standard: 1|1|1|1|0|0|0|1
  xl: 1|0|0|0|1|1|1|1
specs:
  length: 0.7m|2.3m|2.7m|2.6m|3.8m|4.2m|4.1m|1.8m
  Cores: 7
  Gauge: 20
  Encoder connector: 8 pin connector
  Intermediate connector: 7-pin waterproof screw together 90 degree connectors. (female connector on the Y-Axis sections, male connector on the Z-Axis section)
  Farmduino connector: 2.54mm pitch 7-pin connector with locking tab (<a href="https://www.molex.com/molex/products/part-detail/crimp_housings/0050579407">Molex Part 50579407</a>)
  Outer color: Black
  Label: X1|X2|Y|ZY|X2|Y|ZY|ZZ
internal-specs:
  internal part name: "Encoder Cable - X1, 0.7m (Genesis and Genesis XL)|
  Encoder Cable - X2, 2.3m (Genesis)|
  Encoder Cable - Y, 2.7m (Genesis)|
  Encoder Cable - ZY, 2.6m (Genesis)|
  Encoder Cable - X2, 3.8m (Genesis XL)|
  Encoder Cable - Y, 4.2m (Genesis XL)|
  Encoder Cable - ZY, 4.1m (Genesis XL)|
  Encoder Cable - ZZ, 1.8m (Genesis and Genesis XL)|"
  cost: $1.80|$2.50|$3.00|$6.50|$3.50|$4.10|$6.90|$6.00
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the cable's diameter using digital calipers.|5mm|+/- 1mm
|Connectors   |Use a motor and encoder cable to connect to the Farmduino. Issue some movement commands.|The encoder should report motor position as expected|N/A
|Label        |Inspect the shrinkwrap labels.|X1, X2, Y, ZY, and ZZ|N/A
|Cable        |Inspect the cable's spec.|28AWG-3P shielded stranded copper cable|N/A
|Color        |Inspect the color of the cable.|Black|N/A
