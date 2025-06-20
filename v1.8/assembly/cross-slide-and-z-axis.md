---
title: "Cross-Slide and Z-Axis"
slug: "cross-slide-and-z-axis"
description: "Documentation and assembly instructions for the FarmBot Genesis cross-slide and Z-axis"
---

![Cross-slide and Z-axis](_images/cross_slide_and_z_axis.png)

{%
include callout.html
type="clock-o"
title="30 minutes"
content="This is the estimated time it will take to assemble the cross-slide and Z-axis onto the gantry."
%}

# Step 1: Add the cable carrier mount

Attach the [[60mm cable carrier mount]] to the [[cross-slide plate]] using two [[M5 x 16mm screws]] and [[M5 flange locknuts]].

![Attach the cable carrier mount](_images/cross_slide_cable_carrier_mount.png)

# Step 2: Mount the vacuum pump

Attach the pre-assembled [[vacuum pump]] subassembly to the [[cross-slide plate]] using two [[M5 x 16mm screws]] and [[M5 flange locknuts]].

![Mount the vacuum pump](_images/mount_the_vacuum_pump.png)

Then connect the [[inline air filter]] and [[vacuum tube]] between the pump and the tube coming from the Z-axis cable carrier.

{%
include callout.html
type="info"
content="Ensure you connect the tubing to the **inlet** port of the vacuum pump, as denoted by the arrow pointing up."
%}

![Connect the inline air filter](_images/inline_air_filter.png)

# Step 3: Slide the cross-slide onto the gantry main beam

In order for the cross-slide to slide smoothly and wobble-free on the gantry main beam, you must adjust the [[eccentric spacers]] of the bottom two V-wheels. Adjust the [[eccentric spacers]] using the [eccentric spacer adjustment reference guide](../extras/reference/eccentric-spacer-adjustment.md).

![Adjust the eccentric spacers](_images/adjust_cross-slide_eccentric_spacers.png)

Then slide the cross-slide onto the gantry main beam from the side opposite the electronics box.

{%
include callout.html
type="info"
content="You may need to manually rotate the [[leadscrew]] to raise the Z-axis so it clears the [[gantry wheel plate]]."
%}

![Adjust the eccentric spacers](_images/cross_slide_on_gantry.png)

{%
include callout.html
type="success"
content="The cross-slide should move easily across the full width of the gantry. If you feel any significant resistance, re-adjust the eccentric spacers so that there is less resistance to movement.

Pay special attention to the joint(s) between the gantry main beam extrusions. If there is any significant bump or resistance to movement at a joint, use **150 grit sand paper** to sand away the bump."
%}

# Step 4: Feed and secure the belt

Secure one end of the *short* [[belt]] to a [[belt clip]] using a [[belt sleeve]] and then attach the clip to the end of the gantry main beam using two [[M5 x 10mm screws]] and a [[20mm nut bar]]. The tab of the belt clip should be oriented towards the front of the FarmBot. Refer to the [belt installation guide](../extras/reference/belt-installation.md) for reference.

![Secure one end of the belt](_images/y_axis_belt_beginning.png)

Feed the belt under the first [[V-wheel]] of the cross-slide, then over the [[pulley]] and under the remaining two [[V-wheels]]. The flat side of the belt should be in contact with the V-wheels while the toothed side should engage with the teeth on the pulley.

{%
include callout.html
type="warning"
content="Make sure that the belt is not twisted anywhere."
%}

![Feed the belt](_images/y_axis_belt_around_pulley.png)

Secure the belt at the other end of the gantry with another [[belt clip]], [[20mm nut bar]], and two [[M5 x 10mm screws]]. Ensure there is a small amount of tension on the belt once everything is in place.

![Secure the other end of the belt](_images/y_axis_belt_end.png)

# Step 5: Attach the cable carrier

Lay the [[y-axis cable carrier]] onto the [[extruded 40mm horizontal cable carrier supports]] on the [[gantry main beam]] such that the end with the **90-degree** connectors will connect to the **cross-slide**. Attach the cable carrier to the [[60mm cable carrier mount]] using two [[M5 x 16mm screws]] and [[M5 flange locknuts]]. The screws should thread firmly through the cable carrier end piece.

![Mount the cable carrier](_images/attach_y_cc.png)

# Step 6: Connect the water tubing

Push the y-axis [[water tube]] onto the [[90-degree barb]] and the [[NPT to barb adapter]] on top of the [[solenoid valve]].

{% include gallery.html images="
![Connect the Y water tube to the 90 degree barb](_images/connect_y_water_tube_1.png)
![Connect the Y water tube to the NPT adapter](_images/connect_y_water_tube_2.png)
" %}

# Step 7: Connect the cabling

Connect the [[Y vacuum pump cable]] (`VAC`) to the [[vacuum pump]].

![Vacuum pump cable](_images/vacuum_pump_cable.png)

Connect the [[Y UTM cable]] and [[Z UTM cable]] (`UTM`) together with the 12-pin connectors.

![90 degree connectors](_images/90_degree_connectors_1.png)

Connect the Y-axis and Z-axis sections of the following cables together:

  * `ZY` [[encoder cable]] to `ZZ` [[encoder cable]] with the 7-pin connectors
  * `ZY` [[motor cable]] to `ZZ` [[motor cable]] with the 4-pin connectors
  * [[Camera]] (`CAM`) to [[camera cable]] (`CAM`) with the 4-pin connectors

{%
include callout.html
type="danger"
title="Some cables use the same 4-pin connectors"
content="Double check you have connected:

* `CAM` to `CAM`
* `ZY` to `ZZ`

**Take your time. A mistake here could cause damage to the electronics.**"
%}

![90 degree connectors](_images/90_degree_connectors_2.png)

Ensure you fully inserted the 90-degree connectors together. This may require a multi-step process of pushing together, slightly tightening the thumb screws, pushing together again, and tightening some more.

{% include youtube.html id="rPqgmoE3PbI" %}

# Step 8: Connect the y-axis motor and encoder

Connect the `Y` [[motor cable]] and `Y` [[encoder cable]] to the y-axis [[motor]] and [[encoder]].

{%
include callout.html
type="warning"
content="Use zip ties and plenty of slack to ensure the motor and encoder wires do not rub against the belt."
%}

{% include gallery.html images="
![Connect the y-axis motor and encoder cables](_images/feed_y_cables_1.png)
![Connect the y-axis motor and encoder cables](_images/feed_y_cables_2.png)
" %}

# Step 9: Remove slack

Reduce the amount of extra tubing and wiring between the [[y-axis cable carrier]] and the [[z-axis cable carrier]] by gently pulling any extra cable or tubing length through the [[y-axis cable carrier]]. It can be difficult to coax the contents around the bend of the cable carrier, so take your time and ensure that you are not pulling anything too hard.

{%
include callout.html
type="warning"
content="Never pull any cables by their connectors."
%}

![Remove slack](_images/remove_y_z_slack.png)

# What's next?

 * [Toolbays](toolbays.md)
