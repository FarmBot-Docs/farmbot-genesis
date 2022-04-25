---
title: "Electronics Assembly"
slug: "electronics-assembly"
description: "Step-by-step instructions for assembling your FarmBot Genesis V0.7 Electronics"
---


{%
include callout.html
type="info"
title="45 minutes"
content="This is the estimated time it will take to setup the Electronics."
%}



# Step 1: Setup the Raspberry Pi

Follow the instructions on the [Raspberry Pi Software](../V0.8-Software-Setup/raspberry-pi-controller.md) page to install the necessary software onto the Raspberry Pi.

# Step 2: Assemble the Arduino and RAMPS shield



{%
include callout.html
type="danger"
title="Make sure nothing has power"
content="Before assembling or modifying your electronics in any way, be sure that nothing has electrical power. Tampering with the electronics when powered can cause electrical damage to the components and subject you to electrical shock."
%}

Align the **RAMPS Shield** on top of your **Arduino Mega 2560**. The green connectors of the RAMPS shield should be on top of the USB port of the Arduino. Carefully press the two boards together. Make sure that you do not bend any of the RAMPS pins.

# Step 3: Add the Pololu Stepper Drivers

**Pololu Stepper Drivers** are the small boards that mount on top of the RAMPS shield and power the stepper motors. The RAMPS shield has space for up to five drivers, but we're only going to use three for FarmBot. We'll use the spaces marked for the X, Y, and Z directions.

Pololu drivers support *micro-stepping* which allows the stepper motors to be positioned *in between steps*. This provides smoother control of the stepper motors. To activate micro-stepping, add three **jumper pins** to each space on the **RAMPS shield** where a driver will rest, so nine jumper pins will be used altogether.

Now mount your three **Pololu drivers** on top of the **RAMPS shield**, being careful not to bend any pins. The tuning screw should be facing away from the green connectors of the RAMPS shield.

# Step 4: Connect the Arduino to the Raspberry Pi

Use a short **Type A male to Type B male USB cable** to connect the **Arduino** to the **Raspberry Pi**. It does not matter which USB port you you use on the Pi. Shorter cables (3 to 12 inches) are preferable so that they do not take up a lot of space in your electronics housing.

# Step 5: Add a Power Cord to your Power Supply

Attach a three pronged power cord to the power supply.

Do not plug in your power supply to the wall at this time.

# Step 6: Attach the RAMPS Shield to the Power Supply

Use 2-16 stranded wire (two stranded wires of 16 gauge) to connect the power supply to the RAMPS Shield. One wire should connect the Ground output of the power supply to the negative or ground input on the RAMPS shield. The other wire should connect the +12V output of the power supply to the positive input on the RAMPS shield.

# Step 6: Attach the DC/DC converter from the RAMPS Shield to the Pi

Note: This is optional: You can use a standard 5V micro USB cable and power supply to power your Raspberry Pi.

# Step 7: Plug in the Stepper Motors



# Step 8: Plug in the Power Supply

