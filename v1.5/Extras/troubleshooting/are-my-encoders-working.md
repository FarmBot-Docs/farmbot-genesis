---
title: "Are my encoders working?"
slug: "are-my-encoders-working"
excerpt: "Problem description: FarmBot is having trouble with measuring movements. Learn how to interpret and diagnose common encoder issues, what causes them, and how to fix them."
---

* toc
{:toc}

A rotary encoder, also called a shaft encoder, is an electro-mechanical device that converts the angular position or motion of a shaft or axle to analog or digital output signals.  The output of the FarmBot encoder provides information about the motion of the shaft, which is processed by the Farmduino into information such as position, speed and acceleration. The FarmBot Genesis

![NEMA_17_Stepper_Motor_w_rotary_encoder.jpg](NEMA_17_Stepper_Motor_w_rotary_encoder.jpg)

_FarmBot Genesis v1.4 NEMA 17 Stepper Motor with  pre-mounted rotary encoders_

In this case you have enabled the encoders in the Hardware widget on the Device page and are experiencing movement issues. For movement issues with encoders disabled, see the troubleshooting document [Why is my FarmBot not moving?](why-is-my-farmbot-not-moving.md). Make sure movement works well with encoders disabled before proceeding with this troubleshooting guide.



# Symptoms of encoders not working

1. The motors keep moving and don’t stop when hitting the end of an axis.
2. The encoders always display 0 in Controls page Move widget, even when motors do not.

![Encoder_menu.png](Encoder_menu.png)

_Image credit: @Ascend_

3. The displayed position in the Farm Designer (or Move widget motor coordinates) resets to zero after a movement to a non-zero location is complete.
4. If you send a command to move an axis in one direction from about the middle of the axis, then push it back manually in the opposite direction while it’s moving, it continues trying to move and doesn’t pause to retry the movement.
5. If you unplug the motor cables and move the motors slowly by hand, the encoders always display 0 in Controls page Move widget as shown in the screenshot above.

# Potential solutions for encoders not working

1. Check to make sure encoders are plugged in to the correct axes.
2. Check the encoder connections ( FarmBot Genesis v1.3+) (Pay special attention to the black and dark gray wires if using FarmBot Genesis v1.2) and ensure the connectors are securely in place. Test the continuity of each cable wire with a multi-meter.
2. Make sure the firmware version selected matches the kit hardware version you have. (Arduino: v1.2, Farmduino with black power connector: v1.3, Farmduino with red power connector: v1.4)
3. Unplug and plug back in the power supply to reset the firmware.
4. Reflash the firmware by factory resetting and configuring FarmBot OS again. (Alternatively, select a different FIRMWARE in the Device widget and then select the desired firmware again. You should see logs indicating that the firmware has been flashed.)

# Symptoms of encoders working, but incorrect settings

1. Moving an axis, or pressing Home axis or Calibrate axis results in an immediate stop.
2. Moving an axis results in the motor starting and immediately stopping several times. With the default number of movement retries, the motor will appear to pulse three times with little to no movement of the axis.
3. Disabling encoders results in correct movement.

# Potential solutions for encoders working poorly

1. Try inverting the encoders in the Hardware settings widget.
2. Reduce the maximum motor speed to 80 (or 16 for z-axis) in Hardware settings.
3. Increase the number of steps used for acceleration to 100 (or 20 for z-axis). (Alternatively, try a zero or near zero value.)
4. Decrease the minimum speed to 10 (or 2 for z-axis). (Alternatively, increase the minimum speed to 40 (or 8 for z-axis).)



# Advanced troubleshooting of rotary encoders using oscilloscopes

If you have access to an oscilloscope you may be able to troubleshoot the encoder and determine if it is faulty or performing poorly. Common symptoms of poorly performing rotary encoders include extended encoder pulses, encoder signal jitters, low amplitude signals, and other types irregular signals.

The graphic below is an excerpt from the Honest Sensor HS28A Encoder module data sheet (NEMA 17 - FarmBot Genesis v1.4) and it shows how the signals should look as the shaft goes in the counter clockwise direction.

There are other resources, documentation and diagnostic available online to help with advanced troubleshooting of rotary encoders. Check out this page by Dynapar on [Encoder Signal Overview & How to Troubleshoot Common Issues](https://www.dynapar.com/knowledge/encoder_issues/encoder_signal/)


![Wave_Form_Information.bmp](Wave_Form_Information.bmp)



False

