---
title: "Take Time Lapse Plant Photography"
slug: "take-time-lapse-plant-photography"
excerpt: "DIY instructions for using FarmBot to control camera equipment for time lapse photography of your plants growing"
---

* toc
{:toc}

Want to make cool time lapse videos of your food growing? FarmBot can help you do this in a variety of ways.
## Time Lapse Examples
### Individual Plant Time Lapse
Plant a seed in the ground and then use the camera tool to take a photo from the plant's X and Y coordinates with a sufficient amount of Z-height for the plant to fully grow. Move back to this location every day at the same time to take another photo. You'll end up with a time lapse of that individual plant growing - perfect for Instagram.

![giphy.gif](giphy.gif)



{%
include callout.html
type="success"
title="Pro tip"
content="Use the sequence builder and event scheduler of the web app to easily automate the daily process of mounting the camera tool, moving to the plant's location, taking the photo, and the dismounting the camera tool."
%}

### Fly-Over Time Lapse
On day 1, position your camera tool at one end of the tracks, halfway across the gantry, and at the maximum Z-height to snap a photo. The next day, move to the same position but a small distance away from the end of the tracks (maybe 2 to 3cm) and take another photo. Repeat this each day until you reach the end of the tracks. You'll end up with a cool "fly-over" style video of your entire garden growing!

# Camera Options

## Mount a USB Webcam onto the Z-Axis (Easy)
The easiest way to get started is by buying a [USB webcam](http://www.amazon.com/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=usb+web+cam&rh=i%3Aaps%2Ck%3Ausb+web+cam) and moutning it onto the Z-axis. You'll need to protect the camera from rain either by waterproofing it with a silicon sealant or by 3D printing a plastic rain cover. You can then run the USB cable through FarmBot's cable carriers to the Raspberry Pi.

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
content="This camera installation takes up extra space on the Z-axis which can potentially interfere with other components of FarmBot or the plants themselves. Additionally, the camera's point of view cannot be at the UTM's X and Y center, rather it will be offset by some amount. This can make taking photos from directly above where seeds are planted more difficult."
%}

## Build a USB Based Camera Tool (Difficult)
In addition to being connected to the Arduino, FarmBot's UTM is also connected via USB to the Raspberry Pi. This means that you can hack a USB webcam into a standard FarmBot tool blank, and then utilize the existing UTM wiring to power the webcam and send and receive data.

{%
include callout.html
type="success"
title="Pros"
content="Your camera tool will be able to take photos from the UTM's X and Y center - optimal for time lapses from directly above where seeds are planted. The camera tool can be dismounted and stored in the tool bay when not in use in order to save power and computing resources."
%}



{%
include callout.html
type="warning"
title="Cons"
content="The camera cannot be used when other tools are being used."
%}

## Gantry Mounted Raspberry Pi Camera (Easy)
The [Raspberry Pi Camera Module](https://www.raspberrypi.org/products/camera-module/) is a small camera board that connects to the Raspberry Pi via a ribbon cable. You can mount this camera to the gantry to get a sideways viewpoint of your plants and the UTM/tools. You'll need to 3D print a small plastic mount and housing to protect this camera from the rain.

You can also buy a [NoIR filter version](https://www.raspberrypi.org/products/pi-noir-camera/), which can be used at night in combination with Infrared LED lights for some cool night vision of your plants!

![1367-07.jpg](07.jpg)



{%
include callout.html
type="success"
title="Pros"
content="Always connected and supported natively by the Raspberry Pi. Can also be used at night (with the NoIR filter version and IR LEDs)"
%}



{%
include callout.html
type="warning"
title="Cons"
content="Because of cable flexibility and length limitations, this camera can only be mounted on the Gantry - not on the Z-axis. This camera cannot be hacked into a FarmBot tool, at least not easily!"
%}

