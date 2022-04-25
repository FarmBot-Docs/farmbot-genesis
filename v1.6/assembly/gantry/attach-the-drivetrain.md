---
title: "Attach the Drivetrain"
slug: "attach-the-drivetrain"
---

# Step 1: Attach the gantry motors

Slide a [[motor]] into a [[horizontal motor housing]], ensuring that the shaft of the motor is coming out of the housing and that the motor and encoder connectors are facing down through the open bottom of the housing. Then attach the motor and housing to a [[gantry corner bracket]] with four [[M3 x 12mm screws]]. Repeat for the second motor on the other gantry corner bracket.

{% include gallery.html images="
![motor in housing](_images/motor_in_housing.png)
![both_gantry_motors_attached](_images/both_gantry_motors_attached.png)
" %}

Slide [[pulleys]] onto the **motor shafts** and tighten the two **set screws (pre-inserted)** with the 2mm hex driver. Make sure that the setscrews contact the *flat areas* on the motor shafts.

{%
include callout.html
type="lock"
title="Optionally use blue thread locker"
content="It is possible for the setscrews to loosen over time which will disengage the pulley from the motor shaft. If this happens, you may further secure the setscrews in place using **blue thread locker**. To apply thread locker, back the setscrew out as far as possible, apply the thread locker, then retighten."
%}

![gantry motor attached](_images/gantry_motor_attached.png)

# Step 2: Feed the belts

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

# Step 3: Secure the belts

Secure one end of the belt to the front end of the tracks by using a [[belt clip]], [[belt sleeve]], [[20mm nut bar]], and two [[M5 x 10mm screws]]. The belt must be wrapped through the clip as outlined in the [belt installation guide](../../extras/reference/belt-installation.md). Repeat for the other end of the belt on the other end of the tracks. Then repeat for the second x-axis belt on the other side of the FarmBot. Trim or coil any extra belt, if desired.

{% include gallery.html images="
![x-axis belt secured](_images/x-axis_belt_secured.png)
![x-axis belt both ends secured](_images/x-axis_belt_both_ends_secured.png)
" %}

# Step 4: Equalize the gantry

{%
include callout.html
type="info"
content="An **equalized gantry** is one that is exactly _perpendicular_ to the **tracks**.

A crooked or torqued gantry can cause creaking, extra wear on the v-wheels, and introduce a high amount of friction into the system. It also just looks bad."
%}

To equalize the gantry, first ensure that the x-axis motors are unpowered. For first time installation this will always be the case because we haven't yet added the wires or electronics! Then gently push or pull on the gantry **from the middle of the gantry main beam** such that it moves slowly along the tracks about 30cm. This process will remove any torque on the gantry, and ensure it is not crooked. If you push or pull the gantry from one of the gantry columns, or anywhere that is not the middle of the main beam, then you will torque the gantry and make it crooked. Don't do that.

If you were equalizing the gantry as part of routine maintenance, remember to <span class="fb-button fb-yellow">FIND HOME X</span> after equalization.

{%
include callout.html
type="success"
title="Congrats! 🎉"
content="You're now done building your FarmBot's gantry."
%}

# What's next?

 * [Cross-Slide](../cross-slide.md)
