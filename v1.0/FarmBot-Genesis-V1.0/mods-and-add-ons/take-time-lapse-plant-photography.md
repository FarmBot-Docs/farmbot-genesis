---
title: "Take Time Lapse Plant Photography"
slug: "take-time-lapse-plant-photography"
description: "DIY instructions for using FarmBot to control camera equipment for time lapse photography of your plants growing"
---

* toc
{:toc}

Want to make cool time lapse videos of your food growing? FarmBot can help you do this in a variety of ways.
## Time Lapse Examples
### Individual Plant Time Lapse
Plant a seed in the ground and then use the camera tool to take a photo from the plant's X and Y coordinates with a sufficient amount of Z-height for the plant to fully grow. Move back to this location every day at the same time to take another photo. You'll end up with a time lapse of that individual plant growing - perfect for Instagram.

![giphy.gif](_images/giphy.gif)



{%
include callout.html
type="success"
title="Pro tip"
content="Use the sequence builder and event scheduler of the web app to easily automate the daily process of mounting the camera tool, moving to the plant's location, taking the photo, and the dismounting the camera tool."
%}

### Fly-Over Time Lapse
On day 1, position your camera tool at one end of the tracks, halfway across the gantry, and at the maximum Z-height to snap a photo. The next day, move to the same position but a small distance away from the end of the tracks (maybe 2 to 3cm) and take another photo. Repeat this each day until you reach the end of the tracks. You'll end up with a cool "fly-over" style video of your entire garden growing!

# Camera Options

## Z-Axis Mounted Raspberry Pi Camera
The [Raspberry Pi Camera Module](https://www.raspberrypi.org/products/camera-module-v2/) is a small camera board that connects to the Raspberry Pi via a ribbon cable. This camera is used as a part of FarmBot. Installation instructions are provided in [Tools: Camera](../../FarmBot-Genesis-V1.0/tools/camera.md).

![1367-07.jpg](_images/07.jpg)



{%
include callout.html
type="success"
title="Pros"
content="This camera installation method is easy, always connected, and low cost. Because it does not use the UTM, it can be used at the same time as other tools."
%}



{%
include callout.html
type="warning"
title="Cons"
content="This camera installation takes up extra space on the Z-axis which can potentially interfere with other components of FarmBot or the plants themselves. Additionally, the camera's point of view cannot be at the UTM's X and Y center, rather it will be offset by some amount. Also, the camera is mounted at a fixed angle--pointed directly down."
%}

## Mount a USB Webcam
If you want additional camera angles, you can buy a USB Webcam and mount it to the gantry. You'll need to protect the camera from rain either by waterproofing it with a silicon sealant or by 3D printing a plastic rain cover. You can then run the USB cable through FarmBot's cable carriers to the Raspberry Pi.

## Build a USB Based Camera Tool (Difficult)
In addition to being connected to the Arduino, FarmBot's UTM is also connected via USB to the Raspberry Pi. This means that you can hack a USB webcam into a standard FarmBot tool blank, and then utilize the existing UTM wiring to power the webcam and send and receive data. A pan-tilt mechanism could be added for adjustable camera angles using servos and the UTM wire connections.

{%
include callout.html
type="success"
title="Pros"
content="Your camera tool will be able to take photos from the UTM's X and Y center - optimal for time lapses from directly above where seeds are planted. The camera tool can be dismounted and stored in the tool bay when not in use in order to save power and computing resources. A pan-tilt mechanism could allow adjustable camera angles."
%}



{%
include callout.html
type="warning"
title="Cons"
content="The camera cannot be used when other tools are being used."
%}

