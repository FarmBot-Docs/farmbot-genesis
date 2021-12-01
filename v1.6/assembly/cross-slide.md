---
title: "Cross-Slide"
slug: "cross-slide"
description: "Documentation and assembly instructions for the FarmBot Genesis cross-slide"
---

* toc
{:toc}

{% include gallery.html images="
![View of the cross-slide from the front of FarmBot](_images/cross-slide_1.png)
![View of the cross-slide from the back of FarmBot](_images/cross-slide_2.jpg)
" %}

{%
include callout.html
type="info"
title="1 hour"
content="This is the estimated time it will take to assemble the cross-slide."
%}

# Step 1: Add the gantry V-wheels

Attach four **V-wheels** with **[standard spacers](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-spacers)** to the **cross-slide plate** using **M5 x 30mm screws** and **M5 flange locknuts**.

{%
include callout.html
type="warning"
content="Make sure you attach the V-wheels to the correct side of the cross-slide plate"
%}

![Add the gantry v-wheels with normal spacers](_images/gantry_v-wheels_with_normal_spacers.jpg)

Attach three **V-wheels** with **[eccentric spacer](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-eccentric-spacers)** to the holes shown using **M5 x 30mm screws** and **M5 flange locknuts**.

![Add the gantry v-wheels with eccentric spacers](_images/cross_slide_with_gantry_v_wheels.jpg)

# Step 2: Add the Z-axis V-wheels

Flip the cross-slide over so that all of the V-wheels you have added so far are facing away from you.

![Flip the cross-slide over](_images/flip_the_cross-slide_over.jpg)

Attach two **V-wheels** with **[standard spacers](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-spacers)** to the holes shown using **M5 x 30mm screws** and **M5 flange locknuts**.

![Add the z-axis v-wheels with normal spacers](_images/cross_slide_with_z_axis_v_wheels_with_normal_spacers.jpg)

Attach three **V-wheels** with **[eccentric spacers](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-eccentric-spacers)** to the holes shown using **M5 x 30mm screws** and **M5 flange locknuts**.

![Add the z-axis v-wheels with eccentric spacers](_images/cross_slide_with_z_axis_v_wheels.jpg)

# Step 3: Add the leadscrew block

Attach the **leadscrew block** to the **cross-slide plate** using **M5 x 30mm screws** and **M5 flange locknuts**.

![Attach the leadscrew block](_images/attach_the_leadscrew_block.png)

# Step 4: Add the stepper motor

Insert a **stepper motor** into a **horizontal motor housing** such that the motor and encoder connectors are facing down, out the open face of the housing. Then attach the motor and housing to the **cross-slide plate** with four **M3 x 12mm screws**.

{%
include callout.html
type="warning"
title="Orientation is key"
content="The motor and housing should be on the same side of the cross-slide plate as the delrin leadscrew block and the motor and encoder connectors should be facing down towards the delrin leadscrew block."
%}

{% include gallery.html images="
![Insert the motor into the housing](_images/motor_in_housing.png)
![Mount the motor and housing to the plate](_images/cross_slide_with_motor.jpg)
" %}

Slide a **GT2 pulley** onto the **motor shaft**. Make sure that both setscrews are lined up with the flat spots of the motor shaft. Then tighten the setscrews with the **2mm driver**.

{%
include callout.html
type="warning"
title="Mind the gap"
content="There should be a small gap (about 1mm) between the pulley and the plate to allow the motor to spin freely."
%}

![Mount a GT2 pulley onto the motor shaft](_images/cross_slide_with_pulley.jpg)

# Step 5: Add the cable carrier mount

Attach the **80mm cable carrier mount** to the **cross-slide plate** using **M5 x 16mm screws** and **M5 flange locknuts**. The bracket should be on the opposite side of the plate as the motor.

![Add the cable carrier mount](_images/cross_slide_with_cc_mount.jpg)

# Step 6: Slide the cross-slide onto the gantry main beam

In order for the cross-slide to slide smoothly and wobble-free on the gantry main beam, you must first adjust the **[eccentric spacers](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-eccentric-spacers)** of the bottom three V-wheels. Adjust the **[eccentric spacers](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-eccentric-spacers)** using the [eccentric spacer adjustment reference guide](../extras/reference/eccentric-spacer-adjustment.md).

Once you have adjusted the eccentric spacers, slide the cross-slide onto the gantry main beam.

![Adjust the eccentric spacers](_images/cross_slide_on_gantry.png)

The cross-slide should move easily across the full width of the gantry. If you feel any significant resistance, re-adjust the eccentric spacers so that there is less resistance to movement. On Genesis XL models, pay special attention at the connection point between the two gantry main beams. If there is any significant bump or resistance to movement at the joint, you may use sand paper to sand away the bump.

# Step 7: Feed and secure the belt

Attach a **belt clip** to the end of the gantry main beam using two **M5 x 10mm screws** and a **20mm nut bar**. Then secure one end of the **y-axis GT2 timing belt** (2m long for Genesis, 3.5m long for XL) to the belt clip using the [belt installation](../extras/reference/belt-installation.md) reference guide.

![Secure one end of the belt](_images/y_axis_belt_beginning.png)

Feed the **belt** under the end **V-wheel** of the cross-slide, then over the **GT2 pulley** and under the remaining three **V-wheels**. The flat side of the belt should be in contact with your V-wheels while the toothed side should engage with the teeth on the pulley.

{%
include callout.html
type="warning"
title=""
content="Make sure that the belt is not twisted anywhere."
%}

![Feed the belt](_images/y_axis_belt_around_pulley.png)

Secure the belt at the other end of the gantry with another **belt clip**, **20 mm nut bar**, and two **M5 x 10mm screws**. Ensure there is a small amount of tension on the belt once everything is in place.

![Secure the other end of the belt](_images/y_axis_belt_end.png)

# What's next?

 * [Z-Axis](z-axis.md)
