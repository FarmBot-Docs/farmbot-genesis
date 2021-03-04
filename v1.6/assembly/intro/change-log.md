---
title: "Change Log"
slug: "change-log"
description: "All of the changes we made to FarmBot Genesis since the last version"
---

* toc
{:toc}

# Rotary Tool

New in this version of FarmBot Genesis is the inclusion of a **Rotary Tool** - a weed whacker style tool powered by a 24V DC motor and designed to help abate weeds. The tool is powered by a 24V connection to the UTM via `Pin F`.

# Farmduino

The latest revision of our custom **Farmduino** electronics board includes a new 24V MOSFET connected to UTM `Pin F` to power the new Rotary Tool. This new output includes load detection circuitry like all other powered peripheral outputs. We have also increased the `USB OUT` voltage that supplies the Raspberry Pi to mitigate low voltage issues that have affected the CPU, WiFi, and Camera in past versions. Last, the board now includes a more appropriately specced `7.5A` fuse instead of a 15A fuse.

# Modularized UTM cable

Building on the progress made in v1.5, the v1.6 kit includes a two-piece modularized **UTM cable**, with one section running through the y-axis cable carrier and the other section running through the z-axis cable carrier. The two sections are joined by a 12-pin 90-degree waterproof screw-together connector. This makes assembly and disassembly of the FarmBot much easier because now all cables and tubing can be disconnected at the Y/Z cable carrier junction.

# Smaller x-axis cable carrier

The **x-axis cable carrier** has been reduced in size to have `15mm x 20mm` internal dimensions. This saves significant weight and reduces friction when moving along the X axis. With this change comes new **30mm horizontal cable carrier supports** and a new **35mm horizontal cable carrier mount**, adding to overall material, weight, and cost reductions in the kit.

# Tool pre-assembly

All tools (the **Watering Nozzle**, **Seeder**, **Weeder**, **Soil Sensor**, and new **Rotary Tool**) now come pre-assembled and packed individually in small boxes. This reduces the burden of FarmBot assembly required by the user.

# Deprecated FarmBot Genesis MAX

Due to low demand, **FarmBot Genesis MAX** (introduced in v1.5) was [cancelled](https://farm.bot/blogs/news/putting-farmbot-genesis-max-and-express-max-on-hold) and is no longer supported in the v1.6 documentation.

# Miscellaneous

* The **camera** and **camera cables** are now manufactured with shielded USB 2.0 cable (`28AWG/1p+24AWG/2c`) to reduce intereference problems that affected some v1.5 installations.
* Shortened the **X1 motor cable** and **X1 encoder cable** to reduce amount of extra cabling underneath the electronics box.
* Changed the **5mm to 8mm shaft coupling screws** to have a 2mm hex drive in order to remove the **2.5mm hex key** from the kit.
* Removed unnecessary features from the **leadscrew block** design.
* Removed the **USB adapter cable**, **5.5mm wrench**, **2.5mm hex key**, **bladed screwdriver**, **phillips screwdriver**, and extra **pogo pin/jam nuts** from the kit.
* Updated some part quantities to reduce the number of extra pieces at the end of assembly.
* Added numerous documented QA checks to our manufacturing processes.
* Made improvements to the sustainability of packaging materials.
