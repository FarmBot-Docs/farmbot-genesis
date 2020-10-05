---
title: "Electronics"
slug: "electronics"
description: "Documentation for FarmBot Genesis Electronics"
---

* toc
{:toc}

V0.8 hardware integrates [Rotary Encoders](http://wiki.farmbot.cc/wiki/Rotary_Encoders) onto the back of each of the stepper motors. This is important to ensure that FarmBot always knows where it is in the circumstances when it has been inadvertently moved (by kids or pets) or it tries to move but is prevented from doing so due to some obstruction (rocks, branches, kids, pets). Unfortunately, there are no readily accessible add-on rotary encoders from popular sites like Adafruit or Sparkfun (as of September 2014), however, there are a handful of companies who do produce small, add-on encoders that mount nicely to the back panel of the stepper motor and hook onto a second shaft coming from the motor. The encoders modeled in the renderings below are based on those offered by [Schneider Electric](http://motion.schneider-electric.com/downloads/datasheets/17_mtr.pdf).

As of prototpying V0.8 hardware, low-cost rotary encoders have not yet been found or tested. Furthermore, the Arduino firmware does not yet support closed-loop feedback control.

# Assembly Instructions



{%
include callout.html
type="info"
title="45 minutes"
content="This is the estimated time it will take to setup the Electronics."
%}

## Step 1: Gather the parts and tools
Gather all the parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:
* 3mm hex (allen) driver
* Wire strippers

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|1                             |Raspberry Pi 2 Model B
|1                             |Arduino Mega 2560
|1                             |RAMPS shield
|3                             |Pololu Stepper Drivers
|1                             |USB cable (Type A male to Type B male)
|1                             |Power Supply (12V, 30Amp)
|1                             |5V power adapter (UBEC DC/DC Step-Down (Buck) Converter - 5V @ 3A output)
|1                             |Electronics Housing
|2                             |M5 x 10mm Screws
|2                             |Tee Nuts

## Step 2: Setup the Raspberry Pi
Follow the instructions on the [Raspberry Pi Software](../FarmBot-Genesis-V0.9-Docs/intro.md) page to install the necessary software onto the Raspberry Pi.

## Step 3: Assemble the Arduino and RAMPS shield

{%
include callout.html
type="danger"
title="Make sure nothing has power"
content="Before assembling or modifying your electronics in any way, be sure that nothing has electrical power. Tampering with the electronics when powered can cause electrical damage to the components and subject you to electrical shock."
%}

Align the **RAMPS Shield** on top of your **Arduino Mega 2560**. The green connectors of the RAMPS shield should be on top of the USB port of the Arduino.


Carefully press the two boards together. Make sure that you do not bend any of the pins.


## Step 4: Add the Pololu Stepper Drivers

**Pololu Stepper Drivers** are the small boards that mount on top of the **RAMPS shield** and power the stepper motors. The RAMPS shield has space for up to five drivers, but we're only going to use three for FarmBot. We'll use the spaces marked for the X, Y, and Z directions.

Mount your three **Pololu drivers** on top of the **RAMPS shield**, being careful not to bend any pins.

{%
include callout.html
type="danger"
title="Orientation is important!"
content="The tuning screw on each Pololu Driver should be facing AWAY from the green connectors of the RAMPS shield. If you put your Pololu drivers in backwards then you risk frying all of your electronics."
%}







## Step 5: Connect the Arduino to the Raspberry Pi

Use a short **Type A male to Type B male USB cable** to connect the **Arduino** to the **Raspberry Pi**. It does not matter which USB port you you use on the Pi. Short cables (3 to 12 inches) are preferable so that they do not take up a lot of space in your electronics housing.


## Step 6: Add a Power Cord to your Power Supply

Attach a three pronged power cord to the power supply.




{%
include callout.html
type="danger"
title="Keep it un-powered"
content="Do not plug in your power supply to the wall at this time."
%}

## Step 7: Attach the RAMPS Shield to the Power Supply

Use **2-16 stranded wire** (two stranded wires of 16 gauge) to connect the **power supply** to the **RAMPS shield**. One wire should connect the ground output of the power supply to the negative/ground input on the RAMPS shield. The other wire should connect the +12V output of the power supply to the positive input on the RAMPS shield.





## Step 8: Attach the DC/DC converter from the RAMPS Shield to the Pi

{%
include callout.html
type="info"
title="This is optional"
content="Alternatively, you can use a standard 5V micro USB cable and power supply to power your Raspberry Pi."
%}




## Step 9: Plug in the Stepper Motors


## Step 10: Plug in the Power Supply

{%
include callout.html
type="danger"
title="Before plugging in..."
content="Double check all of your connections, component orientations, and ensure there are not any exposed wires that could short circuit or cause electrical shock."
%}






# Troubleshooting and Maintenance



{%
include callout.html
type="info"
title="Don't forget about general maintenance"
content="The tips below apply specifically to the electronics and no other components of your FarmBot. Make sure to view the [General Maintenance](../FarmBot-Genesis-V0.9-Docs/maintenance-guide.md) page as well for system-wide tips."
%}



# Change Log

No changes were made

# Room for Improvement

* Upgrade to a Raspberry Pi 3
