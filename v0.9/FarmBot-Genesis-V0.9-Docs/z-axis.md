---
title: "Z-Axis"
slug: "z-axis"
description: "Documentation and Assembly Instructions for the FarmBot Genesis Z-Axis"
---


<iframe width="100%" height="480" src="https://sketchfab.com/models/a5d485221e584eba91c1a538b3f2e9e7/embed?ui_controls=0&amp;ui_infos=0&amp;ui_related=0" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel=""></iframe>



{%
include callout.html
type="info"
title="Rotate, pan, and zoom"
content="**Mouse and trackpad:** Left-click to rotate, right-click to pan, and scroll to zoom.
**Touchscreen:** Use one finger to rotate, two fingers to pan, and pinch to zoom."
%}



# Assembly Instructions



{%
include callout.html
type="info"
title="30 minutes"
content="This is the estimated time it will take to assemble the z-axis."
%}

## Step 1: Gather the Parts and Tools
Gather all the parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:

* 2mm hex (allen) wrench
* 3mm hex (allen) wrench

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|1                             |Z-Axis Extrusion (20mm x 20mm x 1m)
|1                             |NEMA 17 Stepper Motor
|1                             |Z-Axis Motor Bracket
|2                             |M5 x 10mm Screws
|2                             |Tee Nuts
|4                             |M3 x 10mm Screws

## Step 2: Attach the Stepper Motor to the Z-Axis motor bracket
Partially screw two **M5x10mm screws** and **tee nuts** into the **z-axis motor bracket**.

![V5_Z-Axis_1.jpg](_images/Axis_1.jpg)

Route the **stepper motor’s cable** through the slot opening on the top of the **z-axis motor bracket**.

{% include gallery.html images="
![V5_Z-Axis_2.jpg](_images/Axis_2.jpg)
![V5_Z-Axis_3.jpg](_images/Axis_3.jpg)
" %}

Attach the **stepper motor** to the **z-axis motor bracket** with four **M3 x 10mm screws**.

![V5_Z-Axis_4.jpg](_images/Axis_4.jpg)



# Troubleshooting and Maintenance



{%
include callout.html
type="info"
title="Don't forget about general maintenance"
content="The tips below apply specifically to the cross-slide and no other components of your FarmBot. Make sure to view the [General Maintenance](maintenance-guide.md) page as well for system-wide tips."
%}

## Clean and lubricate the Leadscrew
The z-axis leadscrew will become dirty after being outside for a prolonged period of time. Excessive dirt and grime on the leadscrew can cause premature wear, a loss of precision, and missed steps if not addressed.

{%
include callout.html
type="success"
title="Once a year"
content="Wipe the leadscrew clean with a damp rag or sponge. Applying a small amount of high quality synthetic lubricant to the leadscrew can help make motion through the delrin leadscrew block smoother and quieter. We recommend high quality synthetic lubricant such as that used for bicycle chains."
%}



# Change Log

  * Plates are now 5mm thick
  * Motor mount screws and flex coupling setscrews are now stainless steel

# Room for Improvement

* The rotary encoder protrudes outside of the boundary of the motor on the wire side, which prevents the motor housing from fitting. The solution is to make the motor housing larger to accommodate the encoder and the added wires.
* The motor housing currently sits loose on top of the motor and can shift around and vibrate easily. The next version should have a mounting flange for securing it to the z-axis extrusion.
* The motor housing is designed to fit the chosen motor and encoder. There should be extra vertical room in the housing to accommodate other motor and encoder combinations.
* The slot for the motor wire in the z-axis motor mount is just barely large enough to fit the encoder wire and the motor wire. The solution is to make the slot larger so that both wires (and connectors) can be easily fit through.
* The z-axis motor mount is a critical structural component that must be rigid and strong for accurate and robust z movements. An extra mounting flange should be added for added rigidity and strength in the mounts' connection to the z-axis extrusion.
