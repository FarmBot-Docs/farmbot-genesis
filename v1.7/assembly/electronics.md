---
title: "Electronics"
slug: "electronics"
description: "Documentation for FarmBot Genesis electronics"
---

The [[Farmduino]] and [[Raspberry Pi]] are the central components of the FarmBot from an electronic systems perspective. The diagram below shows how the other electronic components connect to these boards, as well as how the two are connected to each other.

The Farmduino microcontroller uses Arduino architecture and it communicates with the Raspberry Pi using a G-code like language. The Farmduino controls the stepper drivers and motors, as well as the UTM and peripherals. The Farmduino provides power and control to all the electronic components of the FarmBot. The board has a layout and connectors that are optimized for FarmBot's various peripherals and motor requirements.

![farmbot electrical system diagram](_images/farmbot-electrical-system-diagram.jpg)

Meanwhile, the Raspberry Pi is the web-connected brain that keeps track of FarmBot's plants, sequences, regimens, events, and settings. Additionally, the Raspberry Pi is responsible for taking photos with the USB camera, and monitoring and controlling the push buttons and LEDs on top of the electronics box via the Pi adapter board.

![Raspberry Pi electrical diagram](_images/raspberry_pi_electrical_diagram.png)

# Step 1: Connect the peripherals

{%
include callout.html
type="danger"
content="The power supply should still be **unplugged** at this time."
%}

{%
include callout.html
type="info"
title="All cables go through the slot"
content="Before proceeding with plugging everything in, remove the black rubber **supergland** from the slot in the bottom of the **electronics box**.

When plugging in cables in the following steps, ensure that you pass **every cable** through the slot in the bottom of the electronics box. Once everything is connected to the electronics, you will organize all of the cables into the supergland, and then push the supergland back into the slot."
%}

* Connect the [[y vacuum pump cable]] (with gray heat shrink) to the [[Farmduino]] peripheral connector labelled `VACUUM` (the top right connector on Farmduino). The connector will only fit in one direction.
* Connect the [[solenoid valve cable]] (with blue heat shrink) to the [[Farmduino]] peripheral connector labelled `WATER` (directly underneath the vacuum connector). The connector will only fit in one direction.
* Connect the [[LED strip]] to the [[Farmduino]] peripheral connector labelled `LIGHTING` (directly underneath the water connector). The connector will only fit in one direction.

{% include gallery.html images="
![farmduino vacuum connector](_images/farmduino_vacuum.png)
![farmduino water connector](_images/farmduino_water.png)
![farmduino lighting connector](_images/farmduino_lighting.png)
" %}

# Step 2: Plug in the stepper motors and rotary encoders

Plug in the **motor and encoder cables** to the [[Farmduino]]. Each cable is labelled with a white sleeve, which corresponds to the connectors on the Farmduino. From left to right, the connectors on Farmduino are `X1`, `X2`, `Y`, and `Z`. Each connector can only be inserted in one direction, and has a locking tab to prevent it from falling out.

{% include gallery.html images="
![farmduino motor connectors](_images/farmduino_motors.png)
![farmduino encoders connectors](_images/farmduino_encoders.png)
" %}

{%
include callout.html
type="info"
title="Need to remove a cable?"
content="Each connector has a locking tab which must be pressed in before a cable can be removed from the Farmduino. Be delicate when removing cables, as excessive force could damage the Farmduino.

We recommend slightly pushing the connector away from the locking tab (while you are pressing the locking tab in) to facilitate the tab and connector coming free."
%}

# Step 3: Plug in the camera

Plug the [[camera cable]] into the [[Raspberry Pi]]. The exact USB port chosen does not matter.

![pi usb port](_images/pi_usb_port.png)

# Step 4: Plug in the UTM cable

Plug in the [[UTM cable]] to the [[Farmduino]]. The connector will only fit in one direction.

![farmduino utm connector](_images/farmduino_utm.png)

# Step 5: Plug the power supply into the Farmduino

Connect the **3-pin power supply connector** to the **Farmduino's power input**. The connector will only fit in one direction.

![farmduino power connector](_images/farmduino_power.png)

# Step 6: Insert the supergland

Insert one half of the **supergland** into the slot in the bottom of the [[electronics box]]. The left-most hole in the supergland should be small (it is for the camera) while the right-most hole should be medium-sized (it is for the power supply).

![supergland](_images/supergland.png)

Organize and position the **cables** into the **supergland**. From left to right, the cables should be: camera, UTM, motors, encoders, peripherals, power supply.

Once the cables are all inserted into the first supergland half, gently insert the second half of the supergland into the slot in the electronics box. Ensure that the flanges of both supergland halves are on either side of the electronics box wall.

{%
include callout.html
type="warning"
title="Be gentle"
content="Do not pull any cables away from the electronics box during this process as you could damage a connector or cable."
%}

![supergland with cables installed](_images/supergland_with_cables_installed.jpg)

# Step 7: Mount the power supply

Mount the [[power supply]] to your **supporting infrastructure** using four [[wood screws]].

{%
include callout.html
type="info"
content="The power supply is **IP67 rated**, so it can withstand rain and the elements."
%}

![mounted power supply](_images/mounted_power_supply.jpg)

# Step 8: Plug in the power supply

Connect the [[power supply cable]] to the **power supply output**.

![power supply connector](_images/power_supply_connector.png)

Before plugging the power supply into an outlet or an extension cord, please read the precaution below.

{%
include callout.html
type="danger"
title="Beware of electrical shock"
content="Remember that once you plug in the power supply, your system will be powered. Once powered, you cannot add, remove, or change any motor cables, peripheral cables, etc, or you risk frying the electronics and/or being electrically shocked.

If you need to make any changes, you must first unplug the power supply from the wall. This will minimize the risk of electrical shock and the potential to permanently damage your electronics."
%}

If everything looks good, and you understand the precautions needed around powered electronics, go ahead and plug the power supply into a **GFCI outlet**.

If an appropriate outlet is not close enough to plug in directly, use an extension cord and the provided green outdoor electrical connection protector.

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
content="If anything seems wrong, **immediately unplug the power supply from the wall** and contact us at [support@farm.bot](mailto:support@farm.bot)."
%}

# What's next?

 * [Final steps](final-steps.md)
