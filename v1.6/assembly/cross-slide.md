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

{%
include callout.html
type="warning"
title="Before beginning: check the dimensions of the cross-slide plate"
content="Unfortunately we have identified that some Genesis and Genesis XL kits shipped after December 1, 2020 included an incorrect **cross-slide plate**.

We have pro-actively remedied this issue by sending replacement plates to all kit owners or by including an extra plate in every kit shipped in mid-December 2020 or later.

**Before beginning the assembly steps on this page, please ensure you are using the correct plate.** The correct plate should measure 180mm wide by 150mm tall, and have a hole layout that exactly matches this image:

![correct cross-slide plate](_images/correct_cross_slide_plate.jpg)
"
%}

# Step 1: Add the gantry V-wheels

Use four **M5 x 30mm screws** and **M5 flange locknuts** to attach four **V-wheels** with **normal 6mm spacers** to the **cross-slide plate**.

{%
include callout.html
type="warning"
title=""
content="Make sure you attach the V-wheels to the correct side of the cross-slide plate as shown."
%}

{% include gallery.html images="
![Bare cross-slide plate](_images/bare_cross-slide_plate.jpg)
![Add the gantry v-wheels with normal spacers](_images/gantry_v-wheels_with_normal_spacers.jpg)
" %}

_Wheels with normal spacers._

Use three **M5 x 30mm screws** to attach three **V-wheels** with **eccentric 6mm spacers** to the holes shown. The V-wheels should be secured with an **M5 flange locknut** on the other side.

![Add the gantry v-wheels with eccentric spacers](_images/cross_slide_with_gantry_v_wheels.jpg)

_Bottom three wheels with eccentric spacers._

# Step 2: Add the Z-axis V-wheels

Flip the cross-slide over so that all of the V-wheels you have added so far are facing away from you.

![Flip the cross-slide over](_images/flip_the_cross-slide_over.jpg)

Use two **M5 x 30mm screws** to attach two **V-wheels** with **normal 6mm spacers** to the holes shown. Secure these wheels with an **M5 flange locknut** on the other side of the plate.

![Add the z-axis v-wheels with normal spacers](_images/cross_slide_with_z_axis_v_wheels_with_normal_spacers.jpg)

_Wheels with normal spacers._

Use three **M5 x 30mm screws** to attach three **V-wheels** with **eccentric 6mm spacers** to the holes shown. The V-wheels should be secured with an **M5 flange locknut** on the other side.

![Add the z-axis v-wheels with eccentric spacers](_images/cross_slide_with_z_axis_v_wheels.jpg)

_Right three wheels with eccentric spacers._

# Step 3: Add the leadscrew block

Attach the **leadscrew block** to the **cross-slide plate** using two **M5 x 30mm screws** and **M5 flange locknuts**.

![Attach the leadscrew block](_images/attach_the_leadscrew_block.png)

# Step 4: Add the stepper motor

Insert the **stepper motor** into the **horizontal motor housing** such that the motor and encoder connectors are facing down, out the open face of the housing.

![Insert the stepper motor into the housing](_images/stepper_motor_in_housing.png)

Use four **M3 x 12mm screws** to attach the **stepper motor** and **motor housing** to the **cross-slide plate**.

{%
include callout.html
type="warning"
title="Orientation is key"
content="The motor and housing should be on the same side of the cross-slide plate as the delrin leadscrew block and the motor and encoder connectors should be facing down towards the delrin leadscrew block."
%}

![Mount the motor and housing to the plate](_images/cross_slide_with_motor.jpg)

Slide a **GT2 pulley** onto the **stepper motor** shaft. Make sure that both setscrews are lined up with the flat spots of the motor shaft. Then tighten the setscrews with the **2mm driver**.

![Mount a GT2 pulley onto the motor shaft](_images/cross_slide_with_pulley.jpg)

# Step 5: Add the cable carrier mount

Use two **M5 x 16mm screws** and **M5 flange locknuts** to secure the **80mm cable carrier mount** to the **cross-slide plate**. The bracket should be on the opposite side of the plate as the motor.

![Add the cable carrier mount](_images/cross_slide_with_cc_mount.jpg)

# Step 6: Adjust the eccentric spacers

In order for the cross-slide to slide smoothly and wobble-free on the gantry main beam, you must first adjust the eccentric spacers of the bottom three V-wheels. Adjust the eccentric spacers using the [eccentric spacer adjustment reference guide](../extras/reference/eccentric-spacer-adjustment.md).# Step 7: Slide the cross-slide onto the gantry main beam
Once you have adjusted the eccentric spacers, slide the cross-slide onto the gantry main beam.

![Adjust the eccentric spacers](_images/cross_slide_on_gantry.png)

_This is a view of the attached cross slide_

The cross slide should easily move across the gantry. If you feel any significant resistance you need to re-adjust your eccentric spacers so that there is less resistance to movement. On the XL models you should pay special attention at the connection point between the two tracks. If there is any significant bump or resistance to movement at the connection point please use some sand paper and sand away the bump.

![View of the attached cross slide looking up at the Y-Axis motor](_images/cross_slide_y_axis_motor.jpg)

_This is a view of the attached cross slide looking up at the Y-Axis motor_

# Step 8: Feed and secure the belt

Attach a **belt clip** to the end of the gantry main beam using two **M5 x 10mm screws** and a **20mm nut bar**. Then secure one end of the **y-axis GT2 timing belt** (2m long for Genesis, 3.5m long for XL or MAX) to the belt clip using the [belt installation](../extras/reference/belt-installation.md) reference guide.

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
