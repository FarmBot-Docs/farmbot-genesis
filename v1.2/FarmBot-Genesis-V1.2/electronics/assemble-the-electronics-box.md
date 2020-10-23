---
title: "Assemble the Electronics Box"
slug: "assemble-the-electronics-box"
---

* toc
{:toc}


{%
include callout.html
type="info"
title="1.5 hours"
content="This is the estimated time it will take to setup the Electronics."
%}

# Step 1: Gather the parts and tools
Gather all the parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:

* [2mm hex driver](../../Extras/bom/miscellaneous.md#2mm-hex-driver)
* [3mm hex driver](../../Extras/bom/miscellaneous.md#3mm-hex-driver)
* [Bladed screwdriver](../../Extras/bom/miscellaneous.md#bladed-screwdriver)

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|16                            |[M2.5 x 4mm Screws](../../Extras/bom/fasteners-and-hardware.md#m25-screws)
|4                             |[M2.5 x 6mm Standoffs](../../Extras/bom/fasteners-and-hardware.md#m25-standoffs)
|4                             |[M2.5 x 16mm Standoffs](../../Extras/bom/fasteners-and-hardware.md#m25-standoffs)
|4                             |[M3 x 5mm Screws](../../Extras/bom/fasteners-and-hardware.md#m3-screws)
|6                             |[M4 x 16mm Screws](../../Extras/bom/fasteners-and-hardware.md#m4-screws)
|2                             |[M5 x 10mm Screws](../../Extras/bom/fasteners-and-hardware.md#m5-screws)
|2                             |[M5 Tee Nuts](../../Extras/bom/fasteners-and-hardware.md#m5-tee-nuts)
|1                             |[Electronics Housing](../../Extras/bom/electronics-and-wiring.md#electronics-housing)
|1                             |[Electronics Mounting Plate](../../Extras/bom/plastic-parts.md#electronics-mounting-plate)
|1                             |[Raspberry Pi 3](../../Extras/bom/electronics-and-wiring.md#raspberry-pi-3)
|1                             |[MicroSD Card](../../Extras/bom/electronics-and-wiring.md#microsd-card)
|1                             |[Arduino Mega 2560](../../Extras/bom/electronics-and-wiring.md#arduino-mega-2560)
|1                             |[RAMPS shield](../../Extras/bom/electronics-and-wiring.md#ramps-shield)
|4                             |[Stepper Drivers](../../Extras/bom/electronics-and-wiring.md#stepper-drivers)
|4                             |[Stepper Driver Heatsinks](../../Extras/bom/electronics-and-wiring.md#stepper-drivers)
|1                             |[USB cable (Type A male to Type B male)](../../Extras/bom/electronics-and-wiring.md#usb-cable)
|1                             |[5V power adapter](../../Extras/bom/electronics-and-wiring.md#5v-power-adapter)
|2                             |[Wire Nuts](../../Extras/bom/electronics-and-wiring.md#wire-nuts)

# Step 2: Install FarmBot OS
Follow the instructions on the [Raspberry Pi software](https://software.farm.bot/docs/farmbot-os) page to install FarmBot OS onto the **microSD card**. Then insert the microSD card into the slot in the backside of the **Raspberry Pi**.

![Screen Shot 2017-02-14 at 4.04.20 PM.png](_images/Screen_Shot_2017-02-14_at_4.04.20_PM.png)

# Step 3: Mount the Arduino
Use four **M2.5 x 4mm screws** to attach four **M2.5 x 6mm standoffs** to the **electronics mounting plate**. The screws should be on the backside of the plate while the standoffs should be on the front.

{%
include callout.html
type="warning"
title=""
content="The **electronics mounting plate** shipped with the Genesis kits come with a protective cover. Gently peel it off to expose the clear plastic underneath, if desired."
%}



![Screen Shot 2017-02-13 at 3.52.25 PM.png](_images/Screen_Shot_2017-02-13_at_3.52.25_PM.png)

Attach the **Arduino** to the **standoffs** using four **M2.5 x 4mm screws**.

![Screen Shot 2017-02-13 at 3.55.01 PM.png](_images/Screen_Shot_2017-02-13_at_3.55.01_PM.png)

# Step 4: Mount the Raspberry Pi
Use four **M2.5 x 4mm screws** to attach four **M2.5 x 16mm standoffs** to the **electronics mounting plate**. The standoffs should be on the same side of the plate as the Arduino.

![Screen Shot 2017-02-13 at 4.05.49 PM.png](_images/Screen_Shot_2017-02-13_at_4.05.49_PM.png)

Attach the **Raspberry Pi** to the **standoffs** using four **M2.5 x 4mm screws**.

![Screen Shot 2017-02-14 at 4.02.54 PM.png](_images/Screen_Shot_2017-02-14_at_4.02.54_PM.png)

# Step 5: Connect the Arduino to the Raspberry Pi
Connect the **Arduino** to the **Raspberry Pi** with the **USB cable**. It does not matter which USB port you plug into on the Pi. If using a short cable, the lower right port is recommended.

![USB.png](_images/USB.png)

# Step 6: Mount the plate in the housing
Attach the **electronics mounting plate** to the **electronics housing** using four **M3 x 5mm screws**.

![IMG_6775.JPG](_images/IMG_6775.JPG)

# Step 7: Add the RAMPS shield
Align the **RAMPS shield** on top of the **Arduino**. The green connectors of the RAMPS shield should be on the same end of the board as the USB port of the Arduino.



![IMG_6787.JPG](_images/IMG_6787.JPG)

Carefully press the two boards together.

{%
include callout.html
type="warning"
title="Take your time"
content="Make sure that you do not bend any of the RAMPS board pins, and that all of the pins are being inserted into the corresponding black pin headers on the Arduino."
%}



![IMG_6788.JPG](_images/IMG_6788.JPG)

_Press firmly._

# Step 8: Add the stepper drivers

{%
include callout.html
type="info"
title=""
content="**Stepper drivers** are the small circuit boards that mount on top of the **RAMPS shield** and provide power to the **stepper motors**. The RAMPS shield has space for up to five drivers, but we're only going to use four for FarmBot. We'll use the spaces marked X, Y, Z, and E0."
%}

Expose the adhesive on the bottom of the **stepper driver heatsinks**.

![IMG_6779.JPG](_images/IMG_6779.JPG)

Attach the heatsink to the black chip on the **stepper driver**.

{% include gallery.html images="
![IMG_6780.JPG](_images/IMG_6780.JPG)
![IMG_6783.JPG](_images/IMG_6783.JPG)
" %}

Mount the four **stepper drivers** on top of the **RAMPS shield**, being careful not to bend any of the pins.

{%
include callout.html
type="danger"
title="Orientation is important!"
content="The **tuning screw** on each **stepper driver** should be on the FAR end of the driver from the **green power connectors** of the RAMPS shield. If you put your stepper drivers in backwards then you risk frying all of your electronics. Inspect the following photos closely to ensure you insert the drivers correctly."
%}

{% include gallery.html images="
![IMG_6790.JPG](_images/IMG_6790.JPG)
![IMG_6793.JPG](_images/IMG_6793.JPG)
" %}

{%
include callout.html
type="danger"
title="Better safe than sorry"
content="We cannot stress this enough: If your stepper drivers are incorrectly installed then you risk frying all of your electronics. **Double check the photo above one more time to ensure you have mounted your drivers correctly.** "
%}

# Step 9: Connect the RAMPS power cable
Use the **bladed screwdriver** to open the two screw terminals on the right side of the **green power connector** of the **RAMPS shield**. Then insert the **RAMPS power cable's wires** and tighten. The black wire (negative) should be in the right-most terminal.

{%
include callout.html
type="info"
title=""
content="Note that the green power connector can be removed from the RAMPS shield to ease the installation of the power wires. If you remove the connector, make sure to plug it back in after you connect the wires."
%}



![Screen Shot 2017-02-27 at 10.31.02 PM.png](_images/Screen_Shot_2017-02-27_at_10.31.02_PM.png)



{%
include callout.html
type="info"
title=""
content="Note that we included an extra RAMPS power cable that you can optionally connect between the power supply and the remaining two ports on the green power connector. You will need to use this if you want to use the high power D8 outputs for an additional peripheral such as [LED lights](../../Extras/mods/control-lights-with-farmbot.md)."
%}

# Step 10: Connect the Raspberry Pi power cable
Plug the **buck adapter** into the top right three GPIO pins of the **Raspberry Pi**. The empty header of the buck adapter should be "connected" to the upper right GPIO pin.

{% include gallery.html images="
![Screen Shot 2017-02-27 at 10.27.28 PM.png](_images/Screen_Shot_2017-02-27_at_10.27.28_PM.png)
![Screen Shot 2017-02-27 at 10.29.21 PM.png](_images/Screen_Shot_2017-02-27_at_10.29.21_PM.png)
" %}

Twist together the free red wire from the **buck adapter** with the red wire from the **Raspberry Pi power cable**. Then screw on a **wire nut**. Repeat for the black wires.

{% include gallery.html images="
![Screen Shot 2017-02-27 at 10.34.03 PM.png](_images/Screen_Shot_2017-02-27_at_10.34.03_PM.png)
![Screen Shot 2017-02-27 at 10.25.59 PM.png](_images/Screen_Shot_2017-02-27_at_10.25.59_PM.png)
" %}

{%
include callout.html
type="success"
title="Double check your wiring"
content="It can be easy to accidentally connect wires incorrectly or insert something in the wrong orientation. Because electronics are less forgiving to mistakes, take your time to double check that everything looks right. If so, proceed to the next step!"
%}



![Screen Shot 2017-02-27 at 10.37.20 PM.png](_images/Screen_Shot_2017-02-27_at_10.37.20_PM.png)


# What's next?

 * [Attach the Electronics Box](attach-the-electronics-box.md)
