---
title: "Change Log"
slug: "change-log"
description: "All of the changes we made to FarmBot Genesis since the last version"
---

* toc
{:toc}

# FarmBot Genesis XL
The most notable change from FarmBot Genesis v1.3 is that v1.4 devices are now available in the larger FarmBot Genesis XL size, covering an area 3m wide and 6m in length (400% larger than the smaller FarmBot Genesis). In addition to including the obvious additional hardware needed for the XL version (more track extrusions, longer cables, additional screws, etc), each XL kit also includes:
* A new machined aluminum part named the "Gantry Joining Bracket" that connects two 20mm x 60mm x 1500mm aluminum extrusions end-to-end in order to create a 3m wide gantry.
* Three 1-slot toolbays that offer the user more tool storage capacity and flexibility. Some users may wish to mount toolbays on both ends of their raised bed.

# Farmduino
The v1.4 kits include a new revision to our custom electronics board, the Farmduino. The new board features an STM32 co-processor dedicated to monitoring the rotary encoders. This processor has hardware counters and a much higher clock speed that make it ideal for monitoring the four rotary encoders, even at high motor speeds. This computationally frees up the Atmega 2560 chip to be dedicated to driving the motors and carrying out the other functions of FarmBot. The two processors communicate with each other over SPI. Additionally, the new Farmduino features:
* 24V operation, enabling more power to be delivered to the motors and peripherals while minimizing power loss over longer cable lengths (such as in FarmBot Genesis XL).
* A new 2-pin polarized red power connector that is the same style (but keyed differently) than the peripheral connectors.
* Vertical orientations for the two USB ports, allowing for plugging and unplugging those cables in a smaller electronics box.
* Addition of pre-installed pin jumpers to connect the UTM to the Atmega 2560 with the default configuration.
* Improved board layout for easier removal and insertion of the stepper drivers and access to the microstepping dip switches.
* Additional circuitry to better handle back-current from manually moved motors.
* Matte-black circuit board finish :sunglasses:
* Switched to a single blade fuse (from two fuses in the previous version).
* Still 100% open-source.

# Electronics Box
With v1.4 we made significant improvements to the electronics box:
* Added five push-buttons and four LED indicator lights to the top of the box. Two push-buttons are reserved for E-STOP and UNLOCK functionality while the other three can be user-customized to perform other actions or execute a sequence. Two LED indicator lights are reserved to show sync status and FarmBot's connection to the web app.
* We introduced a new circuit board that attaches to the Raspberry Pi's GPIO pin header and provides connectors for all of the push-buttons and LED indicators.
* The entire electronics box now comes completely pre-assembled including the box itself, all of the circuit boards, buttons, LED indicators, and internal wiring. This is a big step in reducing the time, skill, and confidence required to assemble a FarmBot.
* Molded into the box are 14 M2.5 brass inserts allowing for the the Farmduino and Raspberry Pi to be mounted directly into the box (without an intermediary acrylic plate), while still preserving the option to use an electronics mounting plate for custom additions.
* The box has been made slightly narrower due to the design of the new Farmduino board.
* The front cover features a frosted surface finish with a clear logo.
* The latches have been modified to prevent rain water from collecting in them.

# UTM and Cable
The UTM has been completely redesigned as a single injection molded component. It features:
* A PCB with gold-plated pogo pins that allows for a better electrical connection between the UTM and the tools.
* Pin headers on top of the PCB that allow the UTM cable to be easily attached and detached. This is a huge improvement over the zip-tied electrical connections from previous UTM designs.
* Higher quality surface appearance due to the use of injection molding vs machining.
* M5 brass inserts for the barbs and the screws that hold the magnets and PCB in place.
* Eliminated the need for a separate UTM cover, grommets, and the UTM plug.
* Improved barb design that is now metric in size, provides better grip on the tubes, and allows for a zip-tie to be used for more permanently securing tubing onto the barb.
* The UTM cable now features pre-installed connectors for attaching directly to the UTM PCB.
* A new rubber shroud creates a rainproof seal between the cable and the UTM.
* The entire UTM comes pre-assembled, allowing the user to simply mount it on the z-axis and plug in the tubes and cable.
* The new UTM is 100% backwards compatible with the v1.2 and v1.3 tools.

# Power Supply
The new power supply features:
* 24V, 6.25A (150W) output over a single channel (instead of two channels in v1.3).
* The power supply's output cable is now short (30cm) and features a waterproof screw-together 2-pin connector. This connector attaches to a modular power cable that runs between the power supply and the Farmduino, allowing the same power supply to be used with both the Genesis and the Genesis XL models (just the modular cable length is changed). Additionally, it allows for easier installation and maintenance because  the power supply can be disconnected from the FarmBot while the cable remains inside the x-axis cable carrier.
* The power supply is still IP67 rated waterproof with universal voltage input.

# Extrusions
All of the aluminum extrusions in the FarmBot kits are now clear anodized instead of black anodized. This minimizes the temperature that the extrusions become when exposed to direct sunlight. We implemented this change in order to minimize the risk of being burned when touching the FarmBot, and to minimize the amount of thermal expansion and contraction of the extrusions which is particularly important when working with many extrusions end-to-end as in the case with Genesis XL tracks.

# Dowel Pins
A common issue with previous kits has been the difficulty associated with aligning the track extrusions end-to-end such that the gantry can travel smoothly across the joints. With v1.4 kits, we included stainless steel dowel pins to be inserted into the holes in each extrusion during assembly. This helps properly align the extrusions, and keep them aligned.

# Solenoid Valve
The solenoid valve has been relocated to the gantry column and is mounted with the same plate design used to mount the vacuum pump on the z-axis extrusion. This allows for:
* A shorter solenoid valve cable to be used because this cable is no longer routed through the x-axis cable carrier.
* Greater modularity because there are now two water tubes (one routed through the x-axis cable carrier and one through the y- and z-axis cable carriers) which can be disconnected from each other at the location of the solenoid valve. Previously, a single tube was routed through all three cable carriers.

# LED Strip
The new LED strips do not have the standard double-sided tape included on most LED strips of this kind. The tape went unused in v1.3 kits because it is unsuitable for the outdoor environment and the intended mounting options on the FarmBot.

# 24V Peripherals
The new vacuum pump, solenoid valve, and LED light strip all operate at 24V.

# V-Wheels
All V-wheels now come pre-assembled to reduce the time required by the user to put together their FarmBot. Additionally, this helps prevent assembly errors that cost the user significant time.

# Tubing
* We switched to using silicon tubing to prevent any kind of chemical reactions between the tubing and other materials and to increase the tubing lifespan when exposed to direct sunlight.
* All tubing is now metric.

# Packaging
* Internal and external packaging is now made of more robust cardboard material allowing for more secure transport to customers, especially for international shipments.
* The vacuum pump and solenoid valve boxes now feature printed graphics indicating their contents.
* The pre-assembled UTM comes in its own custom box with a foam insert.
* The electronics box comes wrapped to minimize scratches.

# Miscellaneous
* v1.4 kits features a new sticker pack.
* We included a 2mm allen wrench that can be used to tighten the set screws in the other tools, should they come loose.
* We included a small, thin, 5.5mm wrench that may be useful for replacing pogo pins in the new UTM.
* All kits include two short cables with the appropriate Farmduino peripheral connector pre-installed. These can be used for more easily connecting custom peripherals.
* The mold for the horizontal cable carrier supports has been modified to fix an issue where the mounting holes were slightly too small in some cases.
* The motors are now mounted with 12mm long M3 screws (up from 10mm) to ensure proper thread engagement.
* All kits now include a small outdoor extension cord connection protector.
* The red plugs have been removed in favor of red stakes that can be inserted into the soil.

# What's next?

 * [Assembly Preparation](assembly-preparation.md)
