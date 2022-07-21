---
title: "Why is my FarmBot not moving?"
slug: "why-is-my-farmbot-not-moving"
description: "Problem description: FarmBot is having trouble with movements. This Troubleshooting document has been adapted from a post that was originally written by Marc Dingena on the FarmBot Community Forum."
---

This troubleshooting document guides you through a checklist of FarmBot settings, diagnostic tools, and hardware checks to help you get your FarmBot moving reliably. You will start out troubleshooting with simple actions. If these don’t work for you, you should continue through this guide and perform additional actions to troubleshoot your problem. Test your setup after completing each step to see if your problem is solved.

{%
include callout.html
type="success"
title="Inspect and clean the FarmBot and ensure it is free from debris"
content="Prior to following the steps of this troubleshooting guide, clean and inspect the FarmBot tracks, and belts and pulleys, and ensure there is nothing blocking or catching these components. If your FarmBot is located outdoors, there is a possibility that leaves, twigs, and other debris could prevent the proper movement of the FarmBot."
%}



# 1. Ensure FarmBot is connected

Your FarmBot must be connected to the internet and the web app to receive commands and download the resources you create such as sequences, plant locations, and events. If your bot is connected, the web app's **connectivity indicator** should be <span class="fa fa-circle green"></span> green. If your bot is not connected:

1. Confirm FarmBot is [connected to the internet](https://software.farm.bot/docs/connecting-farmbot-to-the-internet) (via WiFi or ethernet).
2. Confirm FarmBot is [connected to the web app](https://software.farm.bot/docs/connecting-farmbot-to-the-web-app).

The connectivity popup should show a [code 31 diagnosis code](https://software.farm.bot/docs/connectivity-codes#code-31) when communication is functioning. Refer to the [connectivity diagnosis codes](https://software.farm.bot/docs/connecting-farmbot-to-the-internet) page for additional help troubleshooting connectivity issues.

![0c09c78-Connectivity_1024x1024.png](_images/Connectivity_1024x1024.png)



# 2.  Equalize the gantry

An equalized gantry is one that is exactly perpendicular to the tracks such that it is not crooked, and so that the gantry is not being torqued. The X-axis tracks need to be aligned. If they are out of alignment they can cause a crooked or torqued gantry, which can cause creaking, extra wear on the v-wheels and motors, and introduce a high amount of friction into the system. These issues all decrease the overall reliability of the FarmBot system and decrease the lifespan of the components.



![ddb550d-d9de2b2-completed_tracks.JPG](_images/d9de2b2-completed_tracks.JPG)

The detailed instructions to build the raised bed supporting infrastructure for the FarmBot are located [here](../../FarmBot-Genesis-V1.4/supporting-infrastructure/building-a-raised-bed.md)

 The detailed instructions to install the tracks on the raised bed supporting infrastructure for the FarmBot are located [here](../../FarmBot-Genesis-V1.4/tracks.md)

## Test the gantry

1. To see if your gantry is equalized, ensure that the x-axis motors are **unpowered** by unplugging the motor cable and the rotary encoder cables from both the X1 and X2 motors,
2. Gently push or pull on the gantry from the **middle** of the gantry main beam such that it moves slowly along the tracks about 30cm. This process will remove any torque on the gantry, and ensure it is not crooked. If you push or pull the gantry from one of the gantry columns, or anywhere that is not the middle of the main beam, then you will torque the gantry and make it crooked.
3. It should be easy to push the gantry from one end of the x-axis to the other end.  If you sense that there is resistance going back and forth along the tracks, you will need to adjust the tracks or [adjust the eccentric spacers](../reference/eccentric-spacer-adjustment.md) to remove the resistance.
4. If you need to add a lubricant to lower the resistance at the V-wheels, use a **dry** lubricant such as powdered graphite. A dry lubricant will not collect dust or dirt and will not gum the wheels or bearings like liquid lubricants or grease will. **Do not use a liquid lubricant on the belts, pulleys, or v-wheels.**
5. Once you have removed the resistance from the tracks, you will need to re-connect the motor and rotary encoder cables. Then you will re-calibrate your FarmBot from the web app.

![Alignment.jpg](_images/Alignment.jpg)



{%
include callout.html
type="success"
title="Alignment is key"
content="For track plates that join two track extrusions together, position the extrusions tightly together at the middle of the plate. Make sure the top and bottom of the extrusions are flush so that the gantry can move across the tracks smoothly. Also make sure that the extrusions are straight, so there is no 'kink' in the tracks at the joint."
%}

Review the track assembly procedure [here](../../FarmBot-Genesis-V1.4/tracks.md).

# 3. Adjust the belt tension

It is possible for the belts to stretch or slip over time which can lead to missed steps, premature wearing, a gantry that binds on the tracks, as well as a loss of precision in FarmBot’s movements.

![wN8vhxVIT3GVxso0S8ma_IMG_20160324_161818.jpg](_images/IMG_20160324_161818.jpg)

Procedure for adjusting the belt tension:

1. Loosen the belt clip that holds the belt in place.
2. Pull the clip to tension the belt - **use a small amount of tension**
3. Re-tighten the clip.
4. Make sure to check all three belts: the two along the tracks, and the one across the gantry main beam.
The belts should not be under extreme tension. If they are, FarmBot’s motors will have difficulty in moving and will miss steps. **Use a small amount of tension - just enough so that there is no slack in the system.**
5. [Re-equalize the gantry](#2--equalize-the-gantry) to prevent binding.

![Belt_Tightening.png](_images/Belt_Tightening.png)



# 4. Adjust the eccentric spacers

Eccentric spacers are used for making fine adjustments to the spacing between the v-wheels on either side of an aluminum extrusion. Adjusting this spacing is key to achieving smooth and wobble-free movement of the gantry across the tracks, the cross-slide across the gantry main beam, and the z-axis up and down the cross-slide.

If the spacing between v-wheels is too little, then the extrusions will not fit between the v-wheels at all or there will be significant friction when moving. If the spacing is too great, then the connection will be wobbly and loose.

Follow our guide for [adjusting the eccentric spacers](../reference/eccentric-spacer-adjustment.md). After the eccentric spacers are adjusted, put the gantry back onto the tracks, [re-feed the belts through the drivetrain](../../FarmBot-Genesis-V1.4/gantry/feed-and-secure-the-belts.md), and secure the belts back into place for normal operation.



![f3db2da-Screen_Shot_2017-02-27_at_12.39.03_PM.png](_images/Screen_Shot_2017-02-27_at_12.39.03_PM.png)



# 5. Change the motor settings

If you are having trouble with the movements of the FarmBot, adjust settings and reduce hardware resistance for motor stalls. You can reduce the hardware resistance by cleaning the tracks and ensuring there is no dirt or debris on belts or the pulleys.  The stepper driver power should be last thing you should try to adjust because it's difficult to adjust and easy to mess up.

Another thing to remember when you are troubleshooting these NEMA 17 stepper motors is that the faster the step rate the lower the torque. This means that if you increase the minimum or maximum speed (mm/s) (AKA the step rate) you will decrease the torque and increase the likelihood of having the motor stall. More details on motor stalls are discussed in the next section of this document.

The default settings provided are the recommended settings for the motor hardware. If you wish to restore any of these settings back to their default value, you can see the default value in the setting's tooltip by hovering over the (?) icon. You can also [restore all settings](https://software.farm.bot/docs/hardware-settings#danger-zone).

![Default_motor_settings_.bmp](_images/Default_motor_settings_.bmp)

If you are getting motor stalls the FarmBot will stop for a second and then continue. If you know that the track is dirty or there are small slopes or imperfections in the tracks the FarmBot will need more speed (power) to move through these track imperfections with ease. Increase the minimum speed in steps of 50mm/s until your FarmBot has the power to overcome these imperfections.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FxXHt3GPACh4%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DxXHt3GPACh4&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FxXHt3GPACh4%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>

This is the same FarmBot with the minimum increased the speed to 200 mm/s. There is no stalling because the motors have the power to overcome the track imperfections.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FIMosnfJEi8A%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DIMosnfJEi8A&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FIMosnfJEi8A%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>

If increasing the minimum speed does not solve the problem, you can attempt the alternative strategy of decreasing the minimum speed and increase the number of "Accelerate for" steps.

# 6. Motor stalls

If you are having trouble with motor stalls adjust settings in the software and reduce hardware resistance.

When the motor stalls its because the motor does not have enough additional torque to overcome the mechanical resistance. When the motor stalls it will make a buzzing sound. The default motor max retries is 3 and this setting is adjustable but we recommend keeping it at 3 tries. The video below shows that the motor quickly tried to move three times and failed each time. If you listen carefully to the video, 6 seconds into the video you can hear the motor stall out three times in a row.  Then at the 12 second mark the operators attempt to move the Z-axis again and you can hear buzz of motor stalls.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F70PIuRYVZjk%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D70PIuRYVZjk&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F70PIuRYVZjk%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube" width="640" height="480" scrolling="no" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>

This issue stall issue on the z-axis was solved by decreasing the minimum speed value and increasing the number of "Accelerate for" steps.

The video below shows the motor accelerating and then stalling out. The FarmBot Y-Axis motors are accelerating to a resonant point and then stalling out likely because of vibrations increasing the maximum load on the system. You can see in this video the motors accelerate then stall and stop six times. In the end the system stops completely because it it it's max re-tries limit was hit.

The recommended corrective action was to take out any slack from the belts and lower the maximum speed. These actions fixed the stalling.


<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FvgtzimwKmGc%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DvgtzimwKmGc&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FvgtzimwKmGc%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube" width="640" height="480" scrolling="no" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>



# 7. Check the stepper drivers

These drivers convert step and direction signals from the microcontroller (Farmduino) into powerful electrical pulses sent to the NEMA 17 stepper motors to allow them to move.

**Stepper driver data:
**

Model A4988 Stepper Motor Driver Carrier (Header Pins Soldered)
Microstepping: full-step, half-step, 1/4-step, 1/8-step, and 1/16-step
Output Current: 1.5 A per phase without a heat sink or forced air flow (rated for up to 2.0 A per coil with sufficient additional cooling)
Protections: Over-temperature thermal shutdown, crossover-current protection, and under-voltage lockout, short-to-ground, and shorted-load
Adjustability: Current control lets you set the maximum current output with a potentiometer, which lets you use voltages above your stepper motor’s rated voltage to achieve higher step rates
Connectors: 0.1″ male header pins


![STEPPER_DRIVERS_.bmp](_images/STEPPER_DRIVERS_.bmp)

_The stepper drivers are located on the Farmduino board._

##Test the stepper drivers

It’s possible that your motors do not rotate at all, or that they are trying to rotate but failing to handle the load. In this section you’re going to check if your motors are working.



![Stepper_Drivers_Farmduino.jpg](_images/Stepper_Drivers_Farmduino.jpg)

1. If none of your motors are responding at all, check your cable carriers and all wiring to and from the motors. Make sure you have connected the motors to the Farmduino correctly.
2. If your motors are responding but struggling:
Check your belt tension again.
3. Check your software settings (speed, steps per mm, encoders, etc.).
4. Adjust the voltage of your stepper driver (see next section).
5. If one of your motors is not responding or struggling, but other motors are fine,  it is likely a problem with the stepper driver, swap the stepper driver of the faulty motor with the driver of a working motor.
**Logical Test:**
- If the problem persists on the same motor, your motor is faulty.
- If the problem moves to the new motor (which was working before), your stepper driver is faulty, or may need more power from the stepper driver (see next section).


It is possible for a stepper driver module to become damaged which may result in no movement at all along an axis. A common sign of a damaged stepper driver module is noticeable burn marks on the stepper driver chip or PCB. The photo below shows an example of burn marks on a stepper driver.



![Burnt_Stepper_Driver.jpg](_images/Burnt_Stepper_Driver.jpg)

If you suspect that one of your stepper drivers has been damaged, you can replace it with the extra 5th stepper driver module included in all kits. You can also order replacement stepper drivers.


# Adjust the stepper driver output power

It’s recommended you use a multimeter when performing these steps, and take extra care around your equipment with regards to electrostatic discharge.

The following YouTube video was produced by the manufacturers of the Pololu A4988 Stepper Motor Driver and it gives specific instruction on how to set the current limit on the stepper driver.



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F89BHS9hfSUk%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D89BHS9hfSUk&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F89BHS9hfSUk%2Fhqdefault.jpg&key=f2aa6fc3595946d0afc3d76cbbd25dc3&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe>

Your system needs to be powered while you perform these steps, so be careful.
Set your multimeter to read the appropriate DC voltage. The setting on your multimeter usually indicates the maximum voltage readout it will give. Your stepper drivers shouldn’t read out more than approximately 2 Volts, so set your multimeter appropriate for that.

![bd750a449a62ea998fae93fafbd9b9252ac64ec2.jpg](_images/bd750a449a62ea998fae93fafbd9b9252ac64ec2.jpg)

Put the black reading pin of your multimeter on the screw of the negative RAMPS power cable. If you wired it up as instructed in the FarmBot assembly manual, this should be the far-right screw, holding the black wire. This wire should be connected to the negative output on your power supply.

![1954334-Screen_Shot_2017-02-27_at_10.31.02_PM.png](_images/Screen_Shot_2017-02-27_at_10.31.02_PM.png)

Put the red reading pin of your multimeter on the stepper driver’s adjust screw.
Depending on your motors’ requirements, you may increase or decrease the current on the stepper drivers using that same screw you used to read the current.

![54b1854c42f63ebb35cbc1a426bab89424e47135.jpg](_images/54b1854c42f63ebb35cbc1a426bab89424e47135.jpg)

Itrip = Vref / (8xRs)
Rs is 0.1R, so with Vref at 0.6V, Itrip is 0.75A. This is reduced to 0.525A by the A4988 chip for full step operation. The motors are rated at 1.7A, which equates to a Vref of 1.36V (actually 1.9V when you allow for the full step current compensation by the A4988). So you have plenty of room to increase the Vref.



Model A4988 Stepper Motor Driver Datasheet

<iframe src="https://drive.google.com/viewerng/viewer?url=https%3A//www.pololu.com/file/0J450/a4988_DMOS_microstepping_driver_with_translator.pdf&embedded=true" width="600" height="780" style="border: none;"></iframe>



# What about the encoders not working?

Learn how to interpret and diagnose common encoder issues, what causes them and how to fix them in the troubleshooting document ["Are my encoders working?](are-my-encoders-working.md)
