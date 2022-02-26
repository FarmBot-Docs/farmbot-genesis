---
title: "Rotary Tool Motor"
slug: "rotary-tool-motor"
description: "The muscle of the rotary tool is this 24V DC motor."
price: $15.00
quantity:
  standard: 1
  xl: 1
specs:
  connector: 3-pin JST XH plug
  wiring length: 75mm
  wiring: DC1 and DC2 leads soldered to motor terminals, PE soldered to motor housing
internal-specs:
  internal part name: Rotary Tool Motor - 24V, 500TB-12560
  rev: A
  cost: $1.90
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Form Factor  |Inspect the motor form factor.|`500TB-12560`|N/A
|Voltage      |Inspect the rated voltage.|24V|N/A
|FWD/REV      |Assemble the motor into a full Rotary Tool and test with a complete FarmBot.|Motor can be powered in forward and reverse at power/speed levels between 20% and 100%|N/A
|Load sense   |Assemble the motor into a full Rotary Tool and test with a complete FarmBot.|Farmduino/FBOS can detect motor load and stalls in realtime|N/A
|Wiring       |Inspect the wiring.|`DC1` (Black) soldered to motor<br>`DC2` (White) soldered to motor<br>`PE` (Clear) soldered to motor housing|N/A
|Wire lengths |Measure the length of the wires using digital calipers.|75mm|+/- 5mm
|Connector    |Inspect the connector type and plug into Rotary Tool PCB.|JST XH connector should attach as expected|N/A
|Screw mounts |Attach the motor to the Rotary Tool with M2.5 x 6mm screws.|Screws should thread correctly and secure the motor in place|N/A
|Shaft diameter|Measure the motor shaft diameter using digital calipers.|2mm|+/- 0.1mm
|Shaft length |Measure the motor shaft length using digital calipers.|8mm|+/- 0.5mm
|Implement fit|Attach the M5 Shaft Adapter to the motor.|Adapter should securely and concentrically attach|N/A
