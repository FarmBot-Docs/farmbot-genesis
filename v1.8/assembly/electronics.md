---
title: "Electronics"
slug: "electronics"
description: "Documentation for FarmBot Genesis electronics"
---

The [[Farmduino]] and [[Raspberry Pi]] are the central components of the FarmBot from an electronic systems perspective. The diagram below shows how the other electronic components connect to these boards, as well as how the two are connected to each other.

The Farmduino microcontroller uses Arduino architecture and it communicates with the Raspberry Pi using a G-code like language. The Farmduino controls the stepper drivers and motors, as well as the UTM and peripherals. The Farmduino provides power and control to all the electronic components of the FarmBot. The board has a layout and connectors that are optimized for FarmBot's various peripherals and motor requirements.

![farmbot electrical system diagram](_images/farmbot-electrical-system-diagram.jpg)

Meanwhile, the Raspberry Pi is the web-connected brain that keeps track of FarmBot's plants, sequences, regimens, events, and settings. Additionally, the Raspberry Pi is responsible for taking photos with the USB camera, and monitoring the push buttons on top of the electronics box via the [[Pi adapter board]].

![Raspberry Pi electrical diagram](_images/raspberry_pi_electrical_diagram.jpg)

# Step 1: Prep

{%
include callout.html
type="danger"
content="The power supply should still be **unplugged** at this time."
%}

Remove the black rubber [[supergland]] from the slot in the bottom of the [[electronics box]].

![remove supergland](_images/remove_supergland.png)

{%
include callout.html
type="info"
title="All cables go through the slot"
content="When plugging in cables in the following steps, ensure that you **pass every cable through the slot** in the bottom of the electronics box. Once everything is connected to the electronics, you will organize all of the cables into the supergland, and then push the supergland back into the slot."
%}

# Step 2: Connect the peripherals

Connect the following cables to the [[Farmduino]] peripheral connectors:

* [[Y vacuum pump cable]] labelled `VAC` to the connector labelled `VACUUM`.
* [[solenoid valve cable]] labelled `H2O` to the connector labelled `WATER`.
* [[LED strip]] labelled `LED` to the connector labelled `LIGHTING`.

{%
include callout.html
type="success"
content="All connectors are keyed and will only fit in one direction. If you are having trouble inserting a connector, do not force it. Instead, double check that you are inserting it in the correct orientation."
%}

{% include gallery.html images="
![farmduino vacuum connector](_images/farmduino_peripherals_1.png)
![farmduino vacuum connector](_images/farmduino_peripherals_2.png)
" %}

# Step 3: Plug in the stepper motors and rotary encoders

Plug in the `X2`, `Y`, and `Z` [[motor cables]] and [[encoder cables]] to the [[Farmduino]].

{%
include callout.html
type="info"
content="The `X1` cables will already be connected."
%}

{% include gallery.html images="
![farmduino motor and encoder connectors](_images/farmduino_motors_and_encoders_1.png)
![farmduino motor and encoder connectors](_images/farmduino_motors_and_encoders_2.png)
" %}

{%
include callout.html
type="warning"
title="Need to remove a cable?"
content="Each connector has a locking tab which must be pressed in before a cable can be removed from the Farmduino. Be delicate when removing cables, as excessive force could damage the Farmduino.

We recommend slightly pushing the connector away from the locking tab (while you are pressing the locking tab in) to facilitate the tab and connector coming free."
%}

# Step 4: Plug in the camera

Plug the [[camera cable]] into the [[Raspberry Pi]]. The exact USB port chosen does not matter.

![pi usb port](_images/pi_usb_port.png)

# Step 5: Plug in the UTM cable

Plug in the [[UTM cable]] to the [[Farmduino]].

{% include gallery.html images="
![farmduino utm connector](_images/farmduino_utm_1.png)
![farmduino utm connector](_images/farmduino_utm_2.png)
" %}

# Step 6: Plug the power supply into the Farmduino

Connect the [[power supply cable]]to the **Farmduino's power input**.

{% include gallery.html images="
![farmduino power connector](_images/farmduino_power_1.png)
![farmduino power connector](_images/farmduino_power_2.png)
" %}

# Step 7: Insert the supergland

Insert one half of the **supergland** into the slot in the bottom of the [[electronics box]]. The left-most hole in the supergland should be small (it is for the camera) while the right-most hole should be medium-sized (it is for the power supply).

![supergland](_images/supergland.png)

Organize and position the **cables** into the **supergland**. From left to right, the cables should be: camera, UTM, motors, encoders, peripherals, power supply.

Once the cables are all inserted into the first supergland half, gently insert the second half of the supergland into the slot in the electronics box. Ensure that the flanges of both supergland halves are on either side of the electronics box wall.

{%
include callout.html
type="warning"
title="Be gentle"
content="Pulling cables too aggressively away from the electronics box can cause damage."
%}

![supergland with cables installed](_images/supergland_with_cables_installed.png)

# Step 8: Install FarmBot OS

Follow [these instructions](https://software.farm.bot/docs/farmbot-os) on the software documentation hub to install **FarmBot OS** onto the [[micro SD card]].

{%
include callout.html
type="search"
content="The [[micro SD card]] will be located in the [[Raspberry Pi]]. When installing FarmBot OS, you may need to use the [[micro SD card adapter]] located in the clear plastic storage case."
%}

{% include gallery.html images="
![microSD card in raspberry pi](_images/micro_sd_card_in_pi.png)
![microSD card in case](_images/micro_sd_card_in_case.jpeg)
" %}

# Step 9: Equalize the gantry

{%
include callout.html
type="info"
content="An **equalized gantry** is one that is exactly _perpendicular_ to the **tracks**. If the gantry is not equalized, it can cause creaking, extra wear on the V-wheels, and stalling when FarmBot moves along the tracks."
%}

To equalize the gantry, first ensure that the x-axis motors are unpowered. For first time installation this will always be the case. Then gently push or pull on the gantry **from the middle of the gantry main beam** such that it moves slowly along the tracks about 30cm. This process will remove any torque on the gantry, and ensure it is not crooked.

If you were equalizing the gantry as part of routine maintenance, remember to <span class="fb-button fb-yellow">FIND HOME X</span> after equalization. Otherwise, proceed with the software portion of the setup.

# Step 10: Mount the power supply

Mount the [[power supply]] to your **supporting infrastructure** using four [[wood screws]].

{%
include callout.html
type="info"
content="The power supply is **IP67 rated**, so it can withstand rain and the elements."
%}

![mounted power supply](_images/mounted_power_supply.png)

# Step 11: Plug in the power supply

Connect the [[power supply cable]] to the [[power supply]] **output**.

![power supply connector](_images/power_supply_connector.png)

{%
include callout.html
type="danger"
title="Before plugging into an outlet..."
content="Note that once you plug in the power supply to an outlet or extension cord, your system will be **powered**. When powered, do not add, remove, or change any motor cables, peripheral cables, etc, or you risk damaging the electronics and/or being electrically shocked.

If you need to make any changes, first unplug the power supply from the wall."
%}

If everything looks good, and you understand the precautions needed around powered electronics, go ahead and plug the [[power supply]] into a **GFCI outlet**.

If an appropriate outlet is not close enough to plug in directly, use an extension cord and the provided [[power cord protector]].

{% include gallery.html images="
![cord protector](_images/cord_protector.jpg)
![cord protector with cord inside](_images/cord_protector_with_cord_inside.jpg)
" %}

{%
include callout.html
type="success"
content="If all has gone well, the Raspberry Pi and Farmduino should boot up and you should see blinking lights!"
%}

{%
include callout.html
type="warning"
content="If anything seems wrong, **immediately unplug the power supply from the wall** and contact us at [contact@farm.bot](mailto:contact@farm.bot)."
%}

# What's next?

 * [Final steps](final-steps.md)
