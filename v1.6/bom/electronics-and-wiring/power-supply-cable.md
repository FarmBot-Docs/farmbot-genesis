---
title: "Power Supply Cable"
slug: "power-supply-cable"
description: "This modular 3-wire cable connects the power supply to the Farmduino. It features a waterproof 3-pin connector to attach to the power supply, and a black molex connector to attach to the Farmduino."
variants: 3m|4.5m
quantity:
  genesis: 1|0
  xl: 0|1
price: $25.00|$35.00
specs:
  cable: 18AWG-3C
  cable color: Black
  connector 1: 3-pin waterproof screw-together connector
  connector 2: 3-pin black connector (<a href="https://www.molex.com/molex/products/part-detail/crimp_housings/2004561213">Molex Part 2004561213</a>)
  length: 3m|4.5m
internal-specs:
  internal part name: Power Supply Cable - 3m|Power Supply Cable - 4.5m
  rev: B|B
  cost: $6.70|$8.50
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the cable's length using a tape measure.|See BOM spec|+/- 3cm
|Diameter     |Measure the cable's diameter using digital calipers.|6mm|+/- 1mm
|Cable        |Inspect cable spec.|18AWG-3C stranded copper cable|N/A
|Connector 1  |Connect the cable's screw-together connector to the power supply.|Should connect|N/A
|Connector 2  |Inspect the connector type.|Should be a 3-pin plug ([Molex 2004561213](https://www.molex.com/molex/products/part-detail/crimp_housings/2004561213)|N/A
|Cable carrier fit|Insert the cable and a water tube through the X-axis cable carrier (including through the end pieces).|Should fit|N/A
|Electronics box fit|Insert the cable and connector 2 through the slot in the bottom of the electronics box and then insert the supergland.|Should fit|N/A
|Farmduino fit|Connect the cable to the Farmduino's 24V POWER IN connector.|Should connect and power the board|N/A
|Color        |Inspect the part's colors.|Black cable<br>Black Molex connector|N/A
