---
title: "Electronics"
slug: "electronics"
description: "Documentation for FarmBot Genesis electronics"
---

* toc
{:toc}

The **Farmduino** and **Raspberry Pi** are the central components of the FarmBot from an electronic systems perspective. The diagram below shows how the other electronic components connect to these boards, as well as how the two are connected to each other.

The Farmduino microcontroller uses Arduino architecture and it communicates with the Raspberry Pi using a G-code like language. The Farmduino controls the stepper drivers and motors, as well as the UTM and peripherals. The Farmduino provides power and control to all the electronic components of the FarmBot. The board has a layout and connectors that are optimized for FarmBot's various peripherals and motor requirements.

![FarmBot_System_Diagram.png](_images/FarmBot_System_Diagram.png)

Meanwhile, the Raspberry Pi is the web-connected brain that keeps track of FarmBot's plants, sequences, regimens, events, and settings. Additionally, the Raspberry Pi is responsible for taking photos with the USB camera, and monitoring and controlling the push buttons and LEDs on top of the electronics box via the Pi adapter board.

![Raspberry_Pi_Diagram_.png](_images/Raspberry_Pi_Diagram_.png)



# Step 1: Attach the electronics box to the gantry

Attach the pre-assembled **electronics box** to the **left gantry column** using six **M5 x 10mm screws** and **drop-in tee nuts**. The top flange of the box should be butted against the bottom edge of the **gantry corner bracket**.

![Screen Shot 2020-02-17 at 3.44.04 PM.png](_images/Screen_Shot_2020-02-17_at_3.44.04_PM.png)

# Step 2: Connect the peripherals


{%
include callout.html
type="danger"
title=""
content="The power supply should still be **unplugged** at this time."
%}



{%
include callout.html
type="info"
title="All cables go through the slot"
content="Before proceeding with plugging everything in, remove the black rubber **supergland** from the slot in the bottom of the **electronics box**.

When plugging in cables in the following steps, ensure that you pass **every cable** through the slot in the bottom of the electronics box. Once everything is connected to the electronics, you will organize all of the cables into the supergland, and then push the supergland back into the slot."
%}

* Connect the **LED lights** to the **Farmduino** peripheral connector labelled `LIGHTING` (the top right connector on Farmduino). The connector will only fit in one direction.
* Connect the **solenoid valve cable** (with blue heat shrink) to the **Farmduino** peripheral connector labelled `WATER` (directly underneath the lighting connector). The connector will only fit in one direction.
* Connect the **vacuum pump cable** (with gray heat shrink) to the **Farmduino** peripheral connector labelled `VACUUM` (directly underneath the water connector). The connector will only fit in one direction.

![Screen Shot 2020-02-17 at 3.51.08 PM.png](_images/Screen_Shot_2020-02-17_at_3.51.08_PM.png)

_The peripheral connectors are highlighted in orange_



{%
include callout.html
type="info"
title=""
content="See [Farmduino Peripheral Pin Numbers](../Extras/reference/farmduino-peripheral-pin-numbers.md) for information about controlling the peripherals from the web app."
%}

# Step 3: Plug in the stepper motors and rotary encoders
Plug in the **motor and encoder cables** to the **Farmduino**. Each cable is labelled with a white sleeve, which corresponds to the connectors on the Farmduino. From left to right, the connectors on Farmduino are `X1`, `X2`, `Y`, and `Z`. Each connector can only be inserted in one direction, and has a locking tab to prevent it from falling out.

![Screen Shot 2020-02-17 at 3.51.51 PM.png](_images/Screen_Shot_2020-02-17_at_3.51.51_PM.png)

_The motor and encoder connectors are highlighted in orange_



{%
include callout.html
type="info"
title="Need to remove a cable?"
content="Each connector has a locking tab which must be pressed in before a cable can be removed from the Farmduino. Be delicate when removing cables, as excessive force could damage the Farmduino.

We recommend slightly pushing the connector away from the locking tab (while you are pressing the locking tab in) to facilitate the tab and connector coming free."
%}

# Step 4: Plug in the camera
Plug in the **camera** to the **Raspberry Pi**.

![Screen Shot 2020-02-17 at 3.52.48 PM.png](_images/Screen_Shot_2020-02-17_at_3.52.48_PM.png)

_The USB port on the Raspberry Pi is highlighted in orange_

# Step 5: Plug in the UTM cable
Plug in the **UTM cable** to the **Farmduino**. The connector will only fit in one direction.

![Screen Shot 2020-02-17 at 3.53.22 PM.png](_images/Screen_Shot_2020-02-17_at_3.53.22_PM.png)

_The UTM connector is highlighted in orange_

# Step 6: Plug the power supply into the Farmduino
Connect the red **2-pin power supply connector** to the **Farmduino's power input**. The connector will only fit in one direction.

![Screen Shot 2020-02-17 at 3.53.59 PM.png](_images/Screen_Shot_2020-02-17_at_3.53.59_PM.png)

_The power input connector is highlighted in orange_

# Step 7: Insert the supergland
Insert one half of the **supergland** into the slot in the bottom of the **electronics box**. The left-most hole in the supergland should be small (it is for the camera) while the right-most hole should be medium-sized (it is for the power supply).

![Supergland.JPG](_images/Supergland.JPG)

Organize and position the **cables** into the **supergland**. From left to right, the cables should be: camera, UTM, motors, encoders, peripherals, power supply.

Once the cables are all inserted into the first supergland half, gently insert the second half of the supergland into the slot in the electronics box. Ensure that the flanges of both supergland halves are on either side of the electronics box wall.

{%
include callout.html
type="warning"
title="Be gentle"
content="Do not pull any cables away from the electronics box during this process as you could damage a connector or cable."
%}



![4509f77-IMG_20170923_131922.jpg](_images/IMG_20170923_131922.jpg)

# Step 8: Install FarmBot OS onto the microSD card
Follow [these instructions](https://software.farm.bot/docs/farmbot-os) on the software documentation hub to install **FarmBot OS** onto the **microSD card**.

# Step 9: Mount the power supply
Mount the **power supply** to your **supporting infrastructure** using four **25mm wood screws**. The power supply is IP67 rated, so it can withstand rain and the elements.

![Mounted PSU.JPG](_images/Mounted_PSU.JPG)

# Step 10: Plug in the power supply
Connect the **waterproof screw-together 2-pin connector** of the **power supply cable** into the **power supply output**.

![Screen Shot 2018-08-10 at 6.14.43 PM.png](_images/Screen_Shot_2018-08-10_at_6.14.43_PM.png)

Before plugging the power supply into an outlet or an extension cord, please read the precaution below.

{%
include callout.html
type="danger"
title="Beware of electrical shock"
content="Remember that once you plug in the power supply, your system will be powered. Once powered, you cannot add, remove, or change any motor cables, peripheral cables, stepper drivers, etc, or you risk frying the electronics and/or being electrically shocked.

If you need to make any changes, you must first unplug the power supply from the wall. This will minimize the risk of electrical shock and the potential to permanently damage your electronics."
%}

If everything looks good, and you understand the precautions needed around powered electronics, go ahead and plug the power supply into a GFCI outlet.

If an appropriate outlet is not close enough to plug in directly, use an extension cord and the provided green outdoor electrical connection protector.

![Cord Protect.JPG](_images/Cord_Protect.JPG)



![Cord protect clear.JPG](_images/Cord_protect_clear.JPG)



{%
include callout.html
type="success"
title="The mark of success"
content="If all has gone well, the Raspberry Pi and Farmduino should boot up and you should revel in the blinking lights!"
%}



{%
include callout.html
type="warning"
title="Smell smoke or heard a loud pop?"
content="If anything seems suspicious or hazardous, **immediately unplug the power supply from the wall** and contact us at [support@farm.bot](mailto:support@farm.bot)."
%}


# What's next?

 * [Tools](tools.md)
