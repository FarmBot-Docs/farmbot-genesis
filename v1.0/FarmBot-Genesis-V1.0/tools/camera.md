---
title: "Camera"
slug: "camera"
description: "Documentation and assembly instructions for the FarmBot Genesis Camera"
---

* toc
{:toc}

The camera is not a typical FarmBot tool in the sense that it does not mount onto the universal tool mount and it is not stored in the tool bay. Instead, it remains fixed in place on the z-axis next to the UTM and can be used at any time, even when other tools are mounted.

The camera itself is the [v2 Raspberry Pi Camera](https://www.raspberrypi.org/products/camera-module-v2/). It is connected directly to the raspberry pi and can take photos for weed detection, [time lapse photography](../../FarmBot-Genesis-V1.0/mods-and-add-ons/take-time-lapse-plant-photography.md) of your plants growing, and video for live streaming what is happening at the UTM.

![giphy.gif](_images/giphy.gif)



# Assembly Instructions

## Step 1: Gather the Parts and Tools
Gather all the camera parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:

  * 3mm hex (allen) driver

|Qty                           |Component                     |
|------------------------------|------------------------------|
|1                             |Raspberry Pi Camera
|1                             |Camera Mount
|1                             |Camera Cover
|2                             |Ribbon Cable to HDMI Cable Adapter
|1                             |HDMI Cable
|2                             |Ribbon Cable
|4                             |M2 Screws
|4                             |M2 Nuts
|1                             |Cable Tie
|2                             |M5 x 16mm Screws
|2                             |M5 Tee Nuts

## Step 2: Attach the Camera to the Mount
Use the four **M2 screws** and **M2 nuts** to attach the **Raspberry Pi camera** to the **camera mount**.


## Step 3: Wire it up
Insert a **ribbon cable** into the **camera** and one of the **ribbon cable to HDMI adapters**.


Insert the **HDMI cable** into the **ribbon cable to HDMI adapter**.


Insert the other end of the **HDMI cable** into the other **ribbon cable to HDMI adapter**, and then the other **ribbon cable** into that adapter too.


Plug the remaining **ribbon cable** end into the **Raspberry Pi**.


## Step 4: Mount Everything to the Z-Axis
Align the **camera cover** and the **camera mount**.


Use two **M5 x 10mm screws** and **M5 tee nuts** to attach the **camera cover** and **camera mount** to the **Z-axis extrusion**




# Borescope Prototype

The first camera we tried using was an inexpensive [USB borescope](https://smile.amazon.com/dp/B016KUGVJC) attached onto the z-axis extruision with a small 3D printed mount. The camera was waterproof, affordable, high resolution, compact, and even had a 5m built-in USB cable. Everything about the camera was perfect except for the focus. Because borescopes are designed for inspecting the insides of plumbing and other hard to access locations, the focus of the borescope is extremely close. Realistically we could only use this camera for taking macro shots of the soil - there is no way it could be used to detect weeds or monitor plant growth. Perhaps one day we will find a wider angle borsecope with an adjustable focus that we can use, but so far we have been unable to source such a device.

# Change Log

* Prototyped using a borescope camera
* Switched to Raspberry Pi Camera with new mount.

# Room for Improvement

* The size of the raspberry pi camera board is significant, and once it is inside a protecting housing with the HDMI adapter boards and ribbon cables it feels very obtrusive to the aesthetic of the z-axis and UTM, and its bulk may also interfere with plants in certain situations. Ideally we will find a way to minimize the spatial impact of the camera.
* The ribbon cable to HDMI cable to ribbon cable system is costly and complex. We will try to find either a USB based camera to use, or a more elegant system of connecting the camera to the Raspberry Pi.
