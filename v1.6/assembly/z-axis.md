---
title: "Z-Axis"
slug: "z-axis"
description: "Documentation and assembly instructions for the FarmBot Genesis z-axis"
---

* toc
{:toc}


![z-axis](_images/z-axis.png)

{%
include callout.html
type="info"
title="1 hour"
content="This is the estimated time it will take to assemble the z-axis."
%}

# Step 1: Attach the stepper motor to the Z-axis motor mount

Attach a **stepper motor** to the **z-axis motor mount** using four **M3 x 12mm screws**. The motor and encoder connectors should be facing the back flange of the mount.

![z-axis motor mount with motor](_images/z-axis_motor_mount_with_motor.png)

# Step 2: Attach the motor mount to the Z-axis extrusion

{%
include callout.html
type="warning"
title="Handle with care"
content="The aluminum extrusions may have sharp corners and edges."
%}

Attach the **z-axis motor mount** to the **z-axis extrusion** using a **60mm nut bar** and **M5 x 10mm screws**. The top face of the motor mount should be 80mm from the end of the extrusion.

![z-axis motor and mount attached to extrusion](_images/z-axis_motor_and_mount_attached_to_extrusion.png)

# Step 3: Attach the shaft coupling

Slide the **5mm to 8mm shaft coupling** onto the **motor shaft** and tighten the top screw with the **2.5mm hex key**.

{%
include callout.html
type="warning"
title="Mind the gap"
content="Make sure there is a small gap (about 2mm) between the shaft coupling and the z-axis motor mount. You might use a credit card to help provide the correct spacing needed."
%}

![z-axis motor with coupling](_images/z-axis_motor_with_coupling.png)

# Step 4: Attach three cable carrier supports

Attach three **60mm vertical cable carrier supports** to the **z-axis extrusion** using **40mm nut bars** and **M5 x 10mm screws**. Space the supports along the extrusion as shown.

![z-axis with motor and cc supports](_images/z-axis_with_motor_and_cc_supports.png)

# Step 5: Attach the vacuum pump cover

Attach the **vacuum pump cover** to the **z-axis extrusion** using two **M5 drop-in tee nuts** and **M5 x 10mm screws**. The cover should be butted up against the lowest **cable carrier support**.

![z-axis with motor cc supports and vacuum pump cover](_images/z-axis_with_motor_cc_supports_and_vacuum_pump_cover.png)

# Step 6: Attach the vacuum pump

Fasten the **vacuum pump** to the **vacuum pump mount** using two **200mm zip ties**. Then attach the vacuum pump mount to the **z-axis extrusion** using a **60mm nut bar** and two **M5 x 16mm screws**. The mount should be butted up against the **vacuum pump cover**.

{% include gallery.html images="
![vacuum pump attached to mount](_images/vacuum_pump_attached_to_mount.png)
![vacuum pump mounted to z-axis](_images/vacuum_pump_mounted_to_z-axis.png)
" %}

# Step 7: Attach one more cable carrier support

Attach one more **60mm vertical cable carrier support** using a **40mm nut bar** and two **M5 x 10mm screws**. The support should be butted up against the **vacuum pump mount**.

![z-axis last cable carrier support](_images/z-axis_last_cable_carrier_support.png)

# Step 8: Attach the z-axis to the cross-slide

Screw the **leadscrew** halfway into the **leadscrew block**.

![leadscrew in cross-slide](_images/leadscrew_in_cross-slide.png)

Slide the **z-axis extrusion** through the v-wheels on the **cross-slide** until the **leadscrew** inserts into the **5mm to 8mm shaft coupling**. Then tighten the coupling's lower **screw** with the **2.5mm hex key**.

{%
include callout.html
type="wrench"
title="Adjust the eccentric spacers as needed"
content="In order to slide the z-axis through the v-wheels you will need to adjust the **[eccentric spacers](../extras/bom/fasteners-and-hardware/spacers.md#m5-x-6mm-eccentric-spacers)** of the three v-wheels on the right side of the cross-slide. Refer to the [eccentric spacer adjustment reference guide](../extras/reference/eccentric-spacer-adjustment.md) for how to do this."
%}

{% include gallery.html images="
![z-axis in cross-slide](_images/z-axis_in_cross-slide.png)
![z-axis motor and leadscrew connection](_images/z-axis_motor_and_leadscrew_connection.png)
" %}

# Step 9: Install the hardstops

Attach the **z-axis hardstops** onto the back side of the **z-axis extrusion** approximately 200mm from the top of the extrusion and 100mm from the bottom of the extrusion using **M5 x 10mm screws** and **tee nuts**. Later, you can quickly adjust these to physically prevent FarmBot from moving too low or too high within its working space.

{% include gallery.html images="
![z-axis top hardstop](_images/z-axis_top_hardstop.png)
![z-axis bottom hardstop](_images/z-axis_bottom_hardstop.png)
" %}

# Step 10: Add the vertical motor housing (optional)

If you plan on stopping assembly after this page, it is recommended to attach the **80mm vertical motor housing** to the **z-axis extrusion** using **M5 x 10mm screws** and **tee nuts** now. This will protect the motor from rain and other hazards until you resume assembly at a later point. Once you resume assembly, you will need to remove the housing.

If you do not plan on stopping the assembly process now, you can skip this step and install the housing after the z motor and encoder cables have been connected in the next step.

![z-axis motor housing installed](_images/z-axis_motor_housing_installed.png)


# What's next?

 * [Cables and Tubing](cables-and-tubing.md)
