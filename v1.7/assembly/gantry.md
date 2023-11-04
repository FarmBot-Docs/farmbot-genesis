---
title: "Gantry"
slug: "gantry"
description: "Documentation and assembly instructions for the FarmBot Genesis gantry"
---


![back side of the gantry](_images/back_side_of_the_gantry.png)

{%
include callout.html
type="clock-o"
title="1 to 1.5 hours"
content="This is the estimated time it will take to assemble the gantry."
%}

# Step 1: Adjust the V-wheel spacing

The [[eccentric spacers]] on the lower wheels of each gantry wheel plate assembly are used for making fine adjustments to the spacing between the lower wheels and the upper wheels. Adjusting this spacing is the key to having your gantry move smoothly and wobble-free across the tracks.

If the spacing is too little, then the gantry will not fit onto the tracks at all or be tough to move. If the spacing is too great, then the gantry will be wobbly and loose. Adjust the [[eccentric spacers]] using the [eccentric spacer adjustment reference guide](../extras/reference/eccentric-spacer-adjustment.md).

# Step 2: Slide onto the tracks

{%
include callout.html
type="wrench"
title="Adjust the eccentric spacers first"
content="This step is assuming that you have already adjusted the [[eccentric spacers]] according to the [eccentric spacer adjustment guide](../extras/reference/eccentric-spacer-adjustment.md)."
%}

Slide the [[gantry columns]] onto the **tracks**. The direction that the wheel plates extend from the column is towards the front of FarmBot. Ensure that the cable carrier supports (mounted to the tracks) are on the left side of the FarmBot.

![slide the gantry columns onto the tracks](_images/slide_the_gantry_columns_onto_the_tracks.png)

# Step 3: Assemble the main beam

{%
include callout.html
type="info"
title="This step applies to XL kits only"
content="If you have a standard sized Genesis kit (1.5m wide), proceed to the [next step](#step-4-attach-the-cable-carrier-supports)."
%}

Place both [[gantry main beams]] on a flat surface such as a table or patio. Using two [[140mm nut bars]] and eight [[M5 x 10mm screws]], attach the [[gantry joining bracket]] to the *lower two slots* of both extrusions. The notch in the middle of the bracket should be aligned with the joint between the two extrusions.

![Attach the gantry joining bracket](_images/attach_the_gantry_joining_bracket.png)

# Step 4: Attach the cable carrier supports

Using [[M5 x 10mm screws]] and [[40mm nut bars]], attach six [[60mm horizontal cable carrier supports]] to the *middle slot* of the [[gantry main beam]] extrusion. For Genesis kits, there is only one main beam extrusion, so only six supports will be used.

![Cable carrier supports on a Genesis gantry](_images/cable_carrier_supports_on_a_genesis_gantry.png)

For Genesis (XL) kits, there are two main beam extrusions, so 12 supports will be used, and they should be positioned on the same side of the extrusions as the gantry joining bracket.

![Cable carrier supports on a Genesis XL gantry](_images/cable_carrier_supports_on_a_genesis_xl_gantry.png)

# Step 5: Attach the main beam

{%
include callout.html
type="users"
title="Grab a friend"
content="The next step requires an additional person to complete."
%}

Lift up the [[gantry main beam]] and position it onto the front of the **gantry corner brackets**. The cable carrier supports should be on the same side of the main beam as the gantry corner brackets. Secure the main beam in place using four [[60mm nut bars]] and [[M5 x 10mm screws]]. The nut bars should be positioned in the *lower two extrusion slots* of the main beam such that the top face of the main beam is 20mm *above* the top edges of the gantry corner brackets.

{% include gallery.html images="
![Attach the gantry main beam](_images/attach_the_gantry_main_beam_1.png)
![Attach the gantry main beam](_images/attach_the_gantry_main_beam_2.png)
" %}

Ensure that the gantry columns are vertical and form a 90 degree angle with the main beam. Then tighten the [[M5 x 10mm screws]]. Depending on the spacing of your tracks, the gantry main beam may extend beyond the corner brackets. This is ok.

![Ensure the gantry is square](_images/ensure_the_gantry_is_square.png)

_This image is from the front of FarmBot_

# Step 6: Feed the belts

Drop the ends of one of the **x-axis GT2 timing belts** down the two large openings of a [[gantry column]], ensuring that the belt teeth engage the [[pulley]]. Grab the ends of the **belt** at the bottom of the [[gantry column]] and feed them under the [[V-wheels]] of the [[gantry wheel plate]], then along the top of the [[track extrusions]] to the ends of the tracks. The flat side of the belt should be in contact with the V-wheels.

{%
include callout.html
type="warning"
title="Avoid twists"
content="When dropping the belt ends through the gantry column and feeding them along the tracks, ensure that there are no twists in the belt."
%}

{% include gallery.html images="
![belt around gantry motor pulley](_images/belt_around_gantry_motor_pulley.png)
![belt fed through gantry wheels](_images/belt_fed_through_gantry_wheels.png)
" %}

# Step 7: Secure the belts

Secure one end of the belt to the front end of the tracks by using a [[belt clip]], [[belt sleeve]], [[20mm nut bar]], and two [[M5 x 10mm screws]]. The belt must be wrapped through the clip as outlined in the [belt installation guide](../../extras/reference/belt-installation.md). Repeat for the other end of the belt on the other end of the tracks. Then repeat for the second x-axis belt on the other side of the FarmBot. Trim or coil any extra belt, if desired.

{% include gallery.html images="
![x-axis belt secured](_images/x-axis_belt_secured.png)
![x-axis belt both ends secured](_images/x-axis_belt_both_ends_secured.png)
" %}

# Step 8: Equalize the gantry

{%
include callout.html
type="info"
content="An **equalized gantry** is one that is exactly _perpendicular_ to the **tracks**.

A crooked or torqued gantry can cause creaking, extra wear on the v-wheels, and introduce a high amount of friction into the system. It also just looks bad."
%}

To equalize the gantry, first ensure that the x-axis motors are unpowered. For first time installation this will always be the case because we haven't yet added the wires or electronics! Then gently push or pull on the gantry **from the middle of the gantry main beam** such that it moves slowly along the tracks about 30cm. This process will remove any torque on the gantry, and ensure it is not crooked. If you push or pull the gantry from one of the gantry columns, or anywhere that is not the middle of the main beam, then you will torque the gantry and make it crooked. Don't do that.

If you were equalizing the gantry as part of routine maintenance, remember to <span class="fb-button fb-yellow">FIND HOME X</span> after equalization.


# What's next?

 * [Cross-Slide and Z-Axis](cross-slide-and-z-axis.md)
