---
title: "High Level Overview"
slug: "high-level-overview"
excerpt: "Bird's eye view of FarmBot Genesis, Genesis XL, and Genesis MAX"
---

* toc
{:toc}

**FarmBot Genesis**, **Genesis XL**, and **Genesis MAX** are primarily constructed from V-slot aluminum extrusions and aluminum plates and brackets. They are driven by four NEMA 17 stepper motors with rotary encoders, the Farmduino electronics board, and a Raspberry Pi 3 computer.  Current models cover growing areas as small 1m<sup>2</sup> up to a maximum of 54m<sup>2</sup>, and plants as tall as 1m.

![FarmBot Genesis v1.5.png](FarmBot_Genesis_v1.5.png)

_FarmBot Genesis v1.5_



![FarmBot Genesis XL v1.5.png](FarmBot_Genesis_XL_v1.5.png)

_FarmBot Genesis XL v1.5_



![FarmBot Genesis MAX v1.5.png](FarmBot_Genesis_MAX_v1.5.png)

_FarmBot Genesis MAX v1.5_



{%
include callout.html
type="success"
title="Not your typical product"
content="We've gone through great lengths to design FarmBot Genesis to be durable, easily assembled and modified with common tools, and upgradeable. Nothing about FarmBot speaks obsolescence or proprietary.

We've done this because at our core, we're makers and hackers just like you. We enjoy tearing apart our gadgets and gizmos to fix them, improve them, and make them different and unique. So that's what FarmBot Genesis is all about - empowering you to truly own FarmBot technology inside and out.

Go ahead and make your tracks longer, design a tool that electrocutes weeds, program FarmBot to spray water at the local cats, grow mushrooms, flowers, hydroponically, or on your living room wall! We can't wait to see what you do with FarmBot.

We hope you'll find our documentation useful and a great starting point for working with FarmBot and making it your own. If you ever have any questions, please head on over to the [forum](http://forum.farmbot.org). Cheers! 🍻"
%}

# Tracks
**Tracks** are one of the components that really differentiate FarmBot Genesis from traditional free-driving wheeled tractors. The tracks are what allow the system to have great precision in an efficient and simple manner. There are many reasons of why tracks are superior, a few of which are listed below.
1. Tracks provide great precision and allow the FarmBot to return to the same position repeatedly
2. Any type of packing structure of plants can be created and managed
3. Tracks take up less area than paths for tractor wheels and do not compact the soil

# Gantry
The **gantry** is the the structural component that bridges the two tracks and moves along the x-axis via a belt and pulley drive system. It also serves as a linear guide for the cross-slide to move across the gantry along the y-axis. The gantry can also serve as a base for mounting other tools, electronics, supplies, and/or sensors.

# Cross-slide
The **cross-slide** moves across the gantry along the y-axis. This motion provides the second major degree of freedom for FarmBots and allows operations such as planting to be done anywhere in the X/Y plane. The cross-slide is moved using a belt and pulley drive system and serves as the base for the z-axis to attach to.

# Z-axis
The **z-axis** attaches to the cross-slide and provides the FarmBot with movement along the z-axis. It serves as the base for attaching the universal tool mount and other tools.

<div class="tracks-image">
  <a href="FarmBot_Coordinate_System_and_Major_Components.png">
  <img class="fb" src="https://cloud.githubusercontent.com/assets/12681652/15699379/4f90ce66-2781-11e6-8c02-f2d913ec1e2c.png" />
  </a>
  <p style="top:1%;left:35%;width:100px;background:#9fc5e8;border: 2px solid #0b5394;">Z-Axis</p>
  <p style="top: 1%;left: 52%;width: 100px;background: #ea9999;border: 2px solid #660000;">Cross-Slide</p>
  <p style="top: 1%;left: 67%;width: 100px;background: #93c47d;border: 2px solid #274e13;">Gantry</p>
  <p style="top: 37%;left: 55%;width: 100px;background: #f9cb9c;border: 2px solid #b45f06;">Universal Tool Mount</p>
  <p style="top: 63%; left: 37%;width: 100px;background: #b7b7b7;border: 2px solid #434343;">Tracks</p>
  <p style="top: 70%; left: 50%;width: 100px;color: #274e13;">X-Direction</p>
  <p style="top: 77%; left: 40%;width: 100px;color: #486a8a;">Z-Direction</p>
  <p style="top: 89%; left: 28%;width: 100px;color: #975656;">Y-Direction</p>
</div>

<style>
img.fb {
  width: 100%;
}
.tracks-image { 
  position: relative; 
  width: 100%;
  border-radius: 3px;
}
.tracks-image p {
  position: absolute; 
  font-size: 16px;
  font-weight: bold;
  text-align: center;
  border-radius: 10%;
  color: black;
}
</style>

# Raised tracks vs low tracks
For FarmBots to properly grow taller plants, the gantry, cross-slide, z-axis, and tools must have adequate vertical clearance from the plants. This can generally be accomplished in two ways:

1. Using raised tracks and a low-profile gantry
2. Using low tracks with a tall gantry

In general, using low tracks with a tall gantry is the better design, especially for larger applications because it saves on material cost, is less of an eyesore, blocks less sunlight, and would be easier to maintain. However, in the case of a FarmBot being installed in a greenhouse or other structure, utilizing the existing walls to support the tracks higher may be a better solution.

<div class="hardware-overview-image">
  <a href="Raised_Tracks_vs_Low_Tracks.png">
  <img class="fb" src="https://cloud.githubusercontent.com/assets/12681652/15698343/672605a4-2778-11e6-9d69-5b27df2bab3a.png" />
  </a>
  <p style="top:5%;left:8%;width:350px;">Raised Tracks with Low-Profile Gantry</p>
  <p style="top:5%;left:52%;width:100px;">vs.</p>
  <p style="top:5%;left:62%;width:250px;">Low Tracks with Raised Gantry</p>
</div>

<style>
img.fb {
  width: 100%;
}
.hardware-overview-image { 
	position: relative; 
  width: 100%;
  border: 3px solid #eee;
  border-radius: 3px;
}
.hardware-overview-image p {
  position: absolute; 
  font-size: 16px;
  font-weight: bold;
  text-align: center;
}
</style>

# Economies of scale
The table below shows the cost/m<sup>2</sup> of growing area based on the size of your FarmBot. Predictably, the larger your FarmBot is, the lower the cost will be per square meter of growing area. Thus, we recommend installing the largest possible FarmBot in your space in order to get the most value out of the device.

*Note that the costs below do not account for [supporting infrastructure](../../FarmBot-Genesis-V1.5/supporting-infrastructure.md), which will also increase in cost as the device size increases.*

|Model                         |Track Length                  |Gantry Width                  |Growing Area                  |Cost                          |Cost/m^2                      |
|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|
|Genesis                       |3m                            |1.5m                          |4.5m<sup>2</sup>              |~$2,600                       |$578
|Genesis XL                    |6m                            |3m                            |18m<sup>2</sup>               |~$4,000                       |$222
|Genesis MAX                   |18m                           |3m                            |54m<sup>2</sup>               |~$6,000                       |$111

