---
title: "Assemble the Electronics Plate v2"
slug: "assemble-the-electronics-plate-v2"
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
* 3mm hex (allen) driver
* 2.5mm hex (allen) driver
* 2mm hex (allen) driver
* 1.5mm hex (allen) driver
* Small flat-bladed screwdriver
* Wire strippers

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|16                            |M2.5 x 4mm Screws
|8                             |M2.5 x 6mm Standoffs
|4                             |M3 x 4mm Screws
|6                             |M4 x 20mm Screws
|2                             |M5 x 12mm Screws
|2                             |M5 Tee Nuts
|1                             |Electronics Housing
|1                             |Electronics mounting plate
|1                             |Raspberry Pi 3 Model B
|1                             |MicroSD card
|1                             |Arduino Mega 2560
|1                             |RAMPS shield
|4                             |DRV8825 Stepper Drivers
|4                             |Stepper Driver Heatsinks
|1                             |USB cable (Type A male to Type B male)
|1                             |5V power adapter (UBEC DC/DC Step-Down (Buck) Converter - 5V @ 3A output)
|1                             |50mm Power jumper wire
|1                             |Power jumper wire
|2                             |3 connector lever nuts

# Step 2: Setup the Raspberry Pi
Follow the instructions on the [Raspberry Pi Software](https://software.farm.bot) page to install the necessary software onto the Raspberry Pi.

# Step 3: Mount the Raspberry Pi and Arduino


![IMG_6723.JPG](IMG_6723.JPG)

Attach eight **M2.5 x 4mm screws** and **M2.5 x 6mm standoffs** to the **electronics plate**.

![IMG_6736.JPG](IMG_6736.JPG)



![IMG_6739.JPG](IMG_6739.JPG)

Attach the **electronics mounting** plate to the **electronics housing** using four **M3 x 4mm screws**.

![IMG_6763.JPG](IMG_6763.JPG)



{%
include callout.html
type="danger"
title="Make sure nothing has power"
content="Before assembling or modifying your electronics in any way, be sure that nothing has electrical power. Tampering with the electronics when powered can cause electrical damage to the components and subject you to electrical shock."
%}

Attach the **Raspberry Pi** to the standoffs in the electronics plate with four **M2.5 x 4mm screws**.

![IMG_6768.JPG](IMG_6768.JPG)

Attach the **Arduino** to the standoffs in the electronics plate with four **M2.5 x 4mm screws**.

![IMG_6773.JPG](IMG_6773.JPG)

# Step 4: Connect the Arduino to the Raspberry Pi

Connect the **Arduino** to the **Raspberry Pi** with the **6 inch Type A male to Type B male USB cable**. It does not matter which USB port you you use on the Pi.

![IMG_6775.JPG](IMG_6775.JPG)

# Step 5: Add the RAMPS shield

![IMG_6777.JPG](IMG_6777.JPG)


Align the **RAMPS Shield** on top of your **Arduino Mega 2560**. The green connectors of the RAMPS shield should be on the same end of the board as the USB port of the Arduino.



![IMG_6787.JPG](IMG_6787.JPG)

Carefully press the two boards together. Make sure that you do not bend any of the pins.

![IMG_6788.JPG](IMG_6788.JPG)

_Press firmly._

# Step 6: Add the Stepper Drivers

**Stepper Drivers** are the small boards that mount on top of the **RAMPS shield** and power the stepper motors. The RAMPS shield has space for up to five drivers, but we're only going to use four for FarmBot. We'll use the spaces marked for the X, Y, and Z directions.

Expose the adhesive on the bottom of the **stepper driver heatsinks**.

![IMG_6779.JPG](IMG_6779.JPG)

Attach the heatsink to the chip on the **stepper driver**.

![IMG_6780.JPG](IMG_6780.JPG)



![IMG_6783.JPG](IMG_6783.JPG)

Mount your three **stepper drivers** on top of the **RAMPS shield**, being careful not to bend any pins.

![IMG_6790.JPG](IMG_6790.JPG)



{%
include callout.html
type="danger"
title="Orientation is important!"
content="The tuning screw on each stepper driver should be on the FAR end of the driver from the green connectors of the RAMPS shield. If you put your stepper drivers in backwards then you risk frying all of your electronics."
%}



![IMG_6793.JPG](IMG_6793.JPG)

#Step 7: Assemble power connectors

![IMG_6795.JPG](IMG_6795.JPG)

Open the screw terminals of the green power connectors of the RAMPS shield.

![IMG_6796.JPG](IMG_6796.JPG)

Insert the short jumper wires into the right two screw terminals and tighten the screws. The black wire (negative) should be on the far right.

![IMG_6798.JPG](IMG_6798.JPG)

Insert the free end of each of the jumper wires into the middle connection of two **lever nuts**:
 * Pull lever all the way up
 * Insert wire
 * Push lever down

![IMG_6801.JPG](IMG_6801.JPG)



![IMG_6805.JPG](IMG_6805.JPG)

Insert the **buck adapter** wires into the lever nuts.

![IMG_6807.JPG](IMG_6807.JPG)

Insert the incoming power wires (not currently connected to power!) into the remaining ports of the lever nuts.

![IMG_6810.JPG](IMG_6810.JPG)

Insert two more incoming power wires (not currently connected to power!) into the left two screw terminals and tighten the screws. Plug the green power connector into the RAMPS board.

![IMG_6812.JPG](IMG_6812.JPG)

Plug the **buck adapter** into the top right three GPIO pins of the Raspberry Pi. The empty header of the buck adapter should be over the upper right GPIO pin.

![IMG_6814.JPG](IMG_6814.JPG)



![IMG_6819.JPG](IMG_6819.JPG)

