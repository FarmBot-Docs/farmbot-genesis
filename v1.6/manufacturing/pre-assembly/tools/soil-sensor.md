---
title: "Soil Sensor"
slug: "soil-sensor"
description: "Pre-assembly and packing instructions for the soil sensor"
---

* toc
{:toc}

![soil sensor](_images/soil_sensor.png)

# Component list

|Component                     |Qty  |
|------------------------------|-----|
|Soil Sensor                   |1
|Soil Sensor PCB               |1
|Magnets                       |3
|M5 x 16mm Screws              |3
|M5 Flange Locknuts            |3
|M3 x 12mm Screws              |8
|M3 Locknuts                   |8
|Jumper Link                   |1
|Soil Sensor Box               |1
|Soil Sensor Box Insert        |1

# Step 1: Install the magnets

Install *only* the **magnets** using the instructions in the [basic tool hardware reference guide](../../../extras/reference/basic-tool-hardware.md).

![soil sensor with magnets](_images/soil_sensor_with_magnets.png)

# Step 2: Install the soil sensor PCB

Attach the **soil sensor PCB** to the **soil sensor** using two [[M3 x 12mm screws]] and [[M3 locknuts]]. The sensor should be on the front side of the base's mounting tabs. The heads of the screws should be on the PCB's front side while the locknuts should be on the mounting tabs' back side. Do not over tighten the screws as this could damage the circuit board.

![soil sensor with pcb](_images/soil_sensor_with_pcb.png)

# Step 3: Install the electronic screws

Use the **2mm hex driver** and **5.5mm box wrench** to secure the following **ring terminals** to the **soil sensor** with [[M3 x 12mm screws]] and [[M3 locknuts]]. The screw heads should be on the same side as the magnets.

|Soil Sensor Position|Wire Color                                    |Connected to|
|--------------------|----------------------------------------------|------------|
|A                   |<span class="cable-color red">red</span>      |`VCC`
|D                   |<span class="cable-color yellow">yellow</span>|`SIG`
|I                   |<span class="cable-color white">white</span>  |`SCL`
|J                   |<span class="cable-color green">green</span>  |`SDA`

{%
include callout.html
type="info"
title="Don't jump the gun"
content="The <span class='cable-color black'>black</span> (GND) wire will be connected differently in the next step."
%}

![soil sensor wire bolts](_images/soil_sensor_wire_bolts.png)

_The screws and nuts are highlighted orange_

# Step 4: Install the jumper link

Attach a **jumper link** to positions **B** and **C** using two [[M3 x 12mm screws]] and [[M3 locknuts]]. The screw in the **B** position should hold the ring terminal of the **<span class="cable-color black">black</span> (GND) wire**.

![soil sensor with jumper link](_images/soil_sensor_with_jumper_link.png)

# Step 5: Pack

Place the **soil sensor box insert** into the **soil sensor box**. Then insert the **pre-assembled soil sensor** into the box and close the lid.

# Box specifications

|                                |                              |
|--------------------------------|------------------------------|
|**Box style**                   |Top flap (standard FarmBot box design)
|**Inner dimensions (L x W x H)**|
|**Outer dimensions (L x W x H)**|
|**Material**                    |Cardboard
|**Color**                       |Brown
|**Printing**                    |**[SOIL SENSOR.pdf](http://docs.farm.bot)** <i class="fa fa-file-pdf-o">
|**Fill**                        |Cardboard insert
