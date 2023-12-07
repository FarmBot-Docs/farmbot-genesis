---
title: "Soil Sensor PCB"
slug: "soil-sensor-pcb"
description: "The Soil Moisture Sensor is a simple breakout for measuring the moisture in soil and similar materials. The soil moisture sensor is pretty straight forward to use. The two large exposed pads function as probes for the sensor, together acting as a variable resistor. The more water that is in the soil means the better the conductivity between the pads will be and will result in a lower resistance, and a higher SIG out."
cad: https://cad.onshape.com/documents/6626b842adca229e69544ad1/w/89ac2637f82d915f22c2bcd0/e/6fdb9c0dc0d864c8b23ad7b7
price: $10.00
quantity:
  standard: 1
  xl: 1
specs:
  Sensor Type: Capacitive (moisture)<br>IC (temperature)
  Output Type: Analog SIG for moisture<br>I2C for temperature
  PCB color: Black
  Wire Colors: VCC - Red<br>GND - Black<br>SIG - Yellow<br>SDA - Green<br>SCL - White
  Wire Lengths: 50mm
  Ring Terminals: Insulated M3
internal-specs:
  internal-part-name: Soil Moisture and Temperature Sensor PCB
  rev: A
  vendor: LDO
  cost: $5.90
  notes: What is the part number for the connector?
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Function     |Connect the PCB to a test fixture and take readings in dry and wet conditions.|Functions as expected|N/A
|Wiring       |Inspect the wire colors.|VCC - Red<br>GND - Black<br>SIG - Yellow<br>SDA - Green<br>SCL - White|N/A
|Wiring length|Measure the length of the wires using digital calipers.|50mm|+/- 5mm
|Terminals    |Attach a terminal to the soil sensor plastic part using an M3 screw.|Terminal should attach as expected|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A
