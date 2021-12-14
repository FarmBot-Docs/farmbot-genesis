---
title: "Vacuum Pump"
slug: "vacuum-pump"
description: "This 24V vacuum pump sucks air through the seeder's luer lock needle in order to suction-hold a seed on the needle tip during planting. It features a PCB direct-soldered onto the back of the motor to provide EMI filtering and smooth startup current draw."
price: $40.00
quantity:
  genesis: 1
  xl: 1
specs:
  Input Voltage: 24V DC
  Current Draw: 0.5A
  Connectors: Three 3/16" male quick-connect terminals for 24V, GND, and PE (protected earth)
  Barb Size: For 6mm ID tubing
internal-specs:
  Internal Part Name: 24V Vacuum Pump with EMI Filter
  Vendor: LDO
  $/pc: $16.90
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Performance  |Connect the vacuum pump to a 24V power source, vacuum air tube, UTM, and seeder tool.|The vacuum should exert enough suction to pick up a seed|N/A
|Terminal size|Connnect a vacuum pump cable.|The cable's connectors should connect to the terminals as expected|N/A
|PCB color    |Inspect the PCB's color.|Matte black|N/A
|Size         |Assembly a vacuum pump, vacuum pump mount plate, vacuum pump cover, and z-axis extrusion according to the FarmBot system design.|Vacuum pump should fit inside the housing without interference,|N/A
|Inlet size   |Connect a vacuum air tube to the vacuum pump's inlet.|Tube should connect as expected, requiring a small amount of force to remove.|N/A
