---
title: "Vacuum Pump"
slug: "vacuum-pump"
description: "This 24V vacuum pump sucks air through the seeder's luer lock needle in order to suction-hold a seed on the needle tip during planting. It features a PCB direct-soldered onto the back of the motor to provide EMI filtering and smooth startup current draw."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/15121dfafb4b65c557b50593
price: $40.00
quantity:
  standard: 1
  xl: 1
specs:
  input voltage: 24V DC
  current draw: 0.5A
  connectors: Three 3/16" male quick-connect terminals (prior to January 2023)<br>Molex part <a href='https://www.molex.com/molex/products/part-detail/pcb_headers/0705430037'>70543-0037</a> (January 2023 and later)
  barb size: For 6mm ID tubing
  pcb: PCB with EMI filtering and soft-start circuitry soldered onto back of motor
  pcb color: Matte black with gold ENIG
internal-specs:
  internal-part-name: Vacuum Pump - 24V with EMI Filter
  rev: B
  vendor: LDO
  cost: $16.90
---

{%
include callout.html
type="success"
title="Thank you Réstep"
content="The EMI filter circuit included on the back of the v1.6 vacuum pump is based on Chris Arntzen's openly licensed [Réstep EMI Filter add-on for older versions of FarmBot's vacuum pump](https://www.restep.eco/emi-filter).

Thank you Chris for lending your expertise in electronics design to the FarmBot community with this fantastic open-source contribution!"
%}

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Performance  |Connect the vacuum pump to a 24V power source, vacuum air tube, UTM, and seeder tool.|The vacuum should exert enough suction to pick up a seed|N/A
|Terminal size|Connnect a vacuum pump cable.|The cable's connectors should connect to the terminals as expected|N/A
|PCB color    |Inspect the PCB's color.|Matte black|N/A
|Size         |Assembly a vacuum pump, vacuum pump mount plate, vacuum pump cover, and z-axis extrusion according to the FarmBot system design.|Vacuum pump should fit inside the housing without interference,|N/A
|Inlet size   |Connect a vacuum air tube to the vacuum pump's inlet.|Tube should connect as expected, requiring a small amount of force to remove.|N/A
