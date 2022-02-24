---
title: "Solenoid Valve"
slug: "solenoid-valve"
description: "This 24V valve controls the flow of water from your garden hose to FarmBot's tubing."
price: $15.00
quantity:
  genesis: 1
  xl: 1
specs:
  Inlet: 3/4" NPT (National Pipe Thread)
  Outlet: 3/4" NPT (National Pipe Thread)
  Operation: Normally closed
  Working Pressure Range: 0.02 to 0.8 Mpa (3 to 116 PSI)
  Flow Direction: One-way, indicated by an arrow molded into the plastic
  Input Voltage: 24V
  Current Draw: 160mA
  Power Consumption: 3.84 watts
  Electrical Tabs Direction: Facing towards the inlet
internal-specs:
  internal part name: Solenoid Valve - 24V, 3/4" NPT
  cost: $2.60
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Threads      |Screw an NPT to barb adapter (with rubber gasket) onto the inlet. Connect a tube to the barb and pressurize the system with municipal water.|Adapter should thread on as expected and the system should hold water without leaking.|N/A
|Voltage      |Connect the solenoid valve to a Farmduino and test operation.|Opens and does not get hot with 24V input|+/- 3V
|Terminal size|Connnect a solenoid valve cable.|The cable's connectors should connect to the terminals as expected|N/A
|Terminal direction|Inspect the direction the terminals face.|Terminals should face the inlet|N/A
|Normal state |Try to blow air through the solenoid valve when it is unplugged/inactive.|Air should not pass through (the valve should be closed)|N/A
|Pressure Range|Inspect the label on the solenoid valve for the working pressure range.|0.02 to 0.8 Mpa<br>(3 to 116 PSI)|N/A
