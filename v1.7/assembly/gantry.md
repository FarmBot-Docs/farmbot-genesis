---
title: "Gantry"
slug: "gantry"
description: "Documentation and assembly instructions for the FarmBot Genesis gantry"
---


![assembled gantry](_images/assembled_gantry.png)

{%
include callout.html
type="clock-o"
title="1 to 1.5 hours"
content="This is the estimated time it will take to assemble the gantry."
%}

# Step 1: Slide the columns onto the tracks

The [[eccentric spacers]] on the lower two [[V-wheels]] of each [[gantry wheel plate]] are used for making fine adjustments to the spacing between the lower wheels and the upper wheels. Adjusting this spacing is the key to having your gantry move smoothly and wobble-free across the tracks.

If the spacing is too little, then the gantry will not fit onto the tracks at all or be tough to move. If the spacing is too great, then the gantry will be wobbly and loose.

{%
include callout.html
type="wrench"
title="Adjust the eccentric spacers"
content="Adjust the [[eccentric spacers]] according to the [eccentric spacer adjustment guide](../extras/reference/eccentric-spacer-adjustment.md)."
%}

Once the spacers have been adjusted, slide the [[gantry columns]] onto the **tracks**. The direction that the wheel plates extend from the column is towards the front of FarmBot. Meanwhile, the gantry column with the electronics box should be the left side of the supporting infrastructure that includes the wood cable carrier supports.

![slide the gantry columns onto the tracks](_images/slide_the_gantry_columns_onto_the_tracks.png)

# Step 2: Assemble the main beam

{%
include callout.html
type="info"
title="This step applies to XL kits only"
content="If you have a standard sized Genesis kit (1.5m wide), proceed to the [next step](#step-3-attach-the-cable-carrier-supports)."
%}

Place both [[gantry main beams]] on a flat surface such as a table or patio. Using two [[140mm nut bars]] and eight [[M5 x 10mm screws]], attach the [[gantry joining bracket]] to the *lower two slots* of both extrusions. The notch in the middle of the bracket should be aligned with the joint between the two extrusions.

![Attach the gantry joining bracket](_images/attach_the_gantry_joining_bracket.png)

# Step 3: Attach the cable carrier supports

Using [[M5 x 10mm screws]] and [[40mm nut bars]], attach five [[60mm horizontal cable carrier supports]] to the *middle slot* of the [[gantry main beam]] extrusion. For Genesis kits, there is only one main beam extrusion, so only five supports will be used.

![Cable carrier supports on a Genesis gantry](_images/cable_carrier_supports_genesis.png)

For Genesis (XL) kits, there are two main beam extrusions, so 10 supports will be used, and they should be positioned on the same side of the extrusions as the [[gantry joining bracket]].

![Cable carrier supports on a Genesis XL gantry](_images/cable_carrier_supports_genesis_xl.png)

# Step 4: Attach the main beam

{%
include callout.html
type="users"
title="Grab a friend"
content="The next step requires an additional person to complete."
%}

Lift up the [[gantry main beam]] and position it onto the front of the **gantry corner brackets**. The cable carrier supports should be on the same side of the main beam as the gantry corner brackets. Slide a [[60mm nut bar]] into each end of the *lowest two extrusion slots* and use [[M5 x 10mm screws]] to loosely attach the main beam to the corner brackets.

{%
include callout.html
type="success"
content="The top face of the main beam should be 20mm *above* the top edges of the gantry corner brackets."
%}

{% include gallery.html images="
![Attach the gantry main beam](_images/attach_the_gantry_main_beam_1.png)
![Attach the gantry main beam](_images/attach_the_gantry_main_beam_2.png)
" %}

Ensure that the gantry columns are **vertical** and form a **90 degree angle** with the main beam. Then tighten the [[M5 x 10mm screws]]. Depending on the spacing of your tracks, the gantry main beam may extend beyond the corner brackets. This is ok.

![Ensure the gantry is square](_images/ensure_the_gantry_is_square.png)

# Step 5: Connect the X2 motor and encoder cables

Connect the `X2` [[motor cable]] and `X2` [[encoder cable]] (highlighted orange in the images below) to the X2 [[motor]] and [[encoder]] on the left side of FarmBot (when looking at the device from the back) by feeding the cables through the slots in all of the [[60mm horizontal cable carrier supports]] along the [[gantry main beam]].

{%
include callout.html
type="info"
content="You will plug the LED light strip into the Farmduino in a few steps from now."
%}

![x2 motor cable from back](_images/x2_motor_cable_from_back.png)

# Step 6: Install the LED light strip

Feed the [[LED strip]] (highlighted orange in the image below) through the [[60mm horizontal cable carrier supports]] on the [[gantry main beam]]. You can secure the end of the strip to the final cable carrier support using a [[100mm zip tie]].

{%
include callout.html
type="info"
content="You will plug the LED light strip into the Farmduino in a few steps from now."
%}

![lights](_images/lights.png)

# Step 7: Feed the belts

Drop the ends of one of the *longer* [[belts]] down the large opening in a [[gantry column]], ensuring that the belt teeth engage the [[pulley]].

![belt around gantry motor pulley](_images/belt_around_gantry_motor_pulley.png)

Grab the ends of the belt at the bottom of the gantry column and feed them under the [[V-wheels]] of the [[gantry wheel plate]], then along the top of the [[track extrusions]] to the ends of the tracks. The flat side of the belt should be in contact with the V-wheels.

{%
include callout.html
type="warning"
title="Avoid twists"
content="When dropping the belt ends through the gantry column and feeding them along the tracks, ensure that there are no twists in the belt."
%}

![belt fed through gantry wheels](_images/belt_fed_through_gantry_wheels.png)

# Step 8: Secure the belts

Secure one end of the belt to the tracks by using a [[belt clip]], [[belt sleeve]], [[20mm nut bar]], and two [[M5 x 10mm screws]]. The belt must be wrapped through the clip as outlined in the [belt installation guide](../extras/reference/belt-installation.md), with the tab of the belt clip extending over the outside of the bed. Repeat for the other end of the belt on the other end of the tracks.

{%
include callout.html
type="scissors"
content="Trim any extra belt length if desired."
%}

{% include gallery.html images="
![x-axis belt secured](_images/x-axis_belt_secured.png)
![x-axis belt both ends secured](_images/x-axis_belt_both_ends_secured.png)
" %}

Repeat steps 7 and 8 for the second x-axis belt on the other side of the FarmBot.

# Step 9: Mount the cable carrier

Lay the **x-axis cable carrier** onto the supporting infrastructure's cable carrier support. Connect the end of the cable carrier _without an end piece_ to the **end piece** that is pre-mounted on the bottom of the left gantry column.

{%
include callout.html
type="success"
content="It is easier to connect the cable carrier by pushing it into the end piece at an angle, engaging the first circular hinge point, and then straightening the cable carrier to engage the second hinge point. Ensure both hinge points are snapped in all the way."
%}

![Connect the x-axis cable carrier to the gantry](_images/mount_x_cc.png)

Fasten the other end of the cable carrier to the wood cable carrier support using two [[T10 flathead wood screws]].

![Mount the x-axis cable carrier to the supporting infrastructure](_images/mount_x_cc_2.png)

# Step 10: Connect the tubing

Push the [[water tube]] coming from the [[x-axis cable carrier]] onto the lower [[NPT to barb adapter]] beneath the [[solenoid valve]].

![solenoid valve x-axis tubing](_images/solenoid_valve_x-axis_tubing.png)

Screw the [[garden hose to barb adapter]] onto the **garden hose**. Then push the [[water tube]] coming from the bottom of the [[x-axis cable carrier]] onto the barb.

{%
include callout.html
type="info"
content="You will need to provide a garden hose of the appropriate length to connect FarmBot to your municipal water source - one is not provided with the FarmBot kits."
%}

![Connect to the water source](_images/connect_to_the_water_source.png)

# Step 10: Attach the seed trough holder

Attach the [[seed trough holder]] to the [[seed trough holder mount]] using two [[M5 x 30mm screws]] and [[M5 flange locknuts]]. Then place the two [[seed troughs]] into the holder. Optionally, you may store up to three luer lock needles in the holder as well.

![Mounted seed trough holder](_images/mounted_seed_trough_holder.png)

# Step 11: Equalize the gantry

{%
include callout.html
type="info"
content="An **equalized gantry** is one that is exactly _perpendicular_ to the **tracks**. If the gantry is not equalized, it can cause creaking, extra wear on the V-wheels, and stalling when FarmBot moves along the tracks."
%}

To equalize the gantry, first ensure that the x-axis motors are unpowered. For first time installation this will always be the case. Then gently push or pull on the gantry **from the middle of the gantry main beam** such that it moves slowly along the tracks about 30cm. This process will remove any torque on the gantry, and ensure it is not crooked.

If you were equalizing the gantry as part of routine maintenance, remember to <span class="fb-button fb-yellow">FIND HOME X</span> after equalization. Otherwise, proceed with the assembly process.


# What's next?

 * [Cross-Slide and Z-Axis](cross-slide-and-z-axis.md)
