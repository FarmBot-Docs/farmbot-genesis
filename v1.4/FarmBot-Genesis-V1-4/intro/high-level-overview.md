---
title: "High Level Overview"
slug: "high-level-overview"
excerpt: "Bird's eye view of FarmBot Genesis and Genesis XL"
---

* toc
{:toc}

FarmBot Genesis and Genesis XL are small scale FarmBots primarily constructed from V-Slot aluminum extrusions and aluminum plates and brackets. They are driven by four NEMA 17 stepper motors with rotary encoders, the Farmduino microcontroller, and a Raspberry Pi 3 computer.

Current models can cover growing areas as small 1m<sup>2</sup> up to a maximum of 18m<sup>2</sup>, and plants as tall as 1m. With additional hardware and modifications, it may be possible to scale the Genesis concept to cover approximately 50m<sup>2</sup> and a maximum plant height of 1.5m, though at this time we do not offer kits with such capacity.


![FarmBot Genesis v1-4.jpg](FarmBot_Genesis_v1-4.jpg)

_FarmBot Genesis v1.4_



![FarmBot Genesis XL v1-4.jpg](FarmBot_Genesis_XL_v1-4.jpg)

_FarmBot Genesis XL v1.4_



{%
include callout.html
type="success"
title="Not your typical product"
content="We've gone through great lengths to design FarmBot Genesis to be durable, easily assembled and modified with common tools, constructed from largely off-the-shelf components, and manufactured with readily available processes and materials. Nothing about FarmBot speaks obsolescence or proprietary.

We've done this because at our core, we're makers and hackers just like you. We enjoy tearing apart our gadgets and gizmos to fix them, improve them, and make them different and unique. So that's what FarmBot Genesis is all about - empowering you to truly own FarmBot technology inside and out.

Go ahead and make your tracks longer, design a tool that electrocutes weeds, program FarmBot to spray water at the local cats, grow mushrooms, flowers, hydroponically, or on your living room wall! We can't wait to see what you do with FarmBot.

We hope you'll find our documentation useful and a great starting point for working with FarmBot and making it your own. If you ever have any questions, please head on over to the [forum](http://forum.farmbot.org). Cheers! 🍻"
%}

# Tracks
Tracks are one of the components that really differentiate FarmBot technology from traditional free-driving wheeled tractors. The tracks are what allow the system to have great precision in an efficient and simple manner. There are many reasons of why tracks are superior, a few of which are listed below.
1. Tracks provide great precision and allow the the FarmBot to return to the same position repeatedly
2. Any type of packing structure of plants can be created and managed
3. Tracks take up less area than paths for tractor wheels and do not compact the soil

# Gantry
The Gantry is the the structural component that bridges the two Tracks and moves in the X-direction via an X-Direction Drive System. Typically, it serves as a linear guide for the Cross-Slide and a base for the Y-Direction Drive System that moves the Cross-Slide across the Gantry in the Y-direction. It can also serve as a base for mounting other tools, electronics, supplies, and/or sensors.

# Cross-slide
The Cross-Slide moves in the Y-Direction across the Gantry. This motion provides the second major degree of freedom for FarmBots and allows operations such as planting to be done anywhere in the XY plane. The Cross-Slide is moved using a Y-Direction Drive System and functions as the base for the Tool Mount and Z-Direction Drive System.

# Z-axis
The Z-axis attaches to the Cross-Slide and provides the FarmBot with Z-Direction movement. It serves as the base for attaching the Universal Tool Mount and other Tools.

<div class="tracks-image">
  <a href="FarmBot_Coordinate_System_and_Major_Components.png">
  <img src="https://cloud.githubusercontent.com/assets/12681652/15699379/4f90ce66-2781-11e6-8c02-f2d913ec1e2c.png" />
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
img {
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
For FarmBots to properly grow taller plants, the Gantry, Cross-Slide, Z-Axis, and Tools must have adequate vertical clearance from the plants. This can generally be accomplished in two ways:

1. Using raised tracks and a low-profile gantry
2. Using low tracks with a tall gantry

In general, using low tracks with a tall gantry is the better design, especially for larger applications because it saves on material cost, is less of an eyesore, blocks less sunlight, and would be easier to maintain. However, in the case of a FarmBot being installed in a greenhouse or other structure, utilizing the existing walls to support the tracks higher may be a better solution.

<div class="hardware-overview-image">
  <a href="Raised_Tracks_vs_Low_Tracks.png">
  <img src="https://cloud.githubusercontent.com/assets/12681652/15698343/672605a4-2778-11e6-9d69-5b27df2bab3a.png" />
  </a>
  <p style="top:5%;left:8%;width:350px;">Raised Tracks with Low-Profile Gantry</p>
  <p style="top:5%;left:52%;width:100px;">vs.</p>
  <p style="top:5%;left:62%;width:250px;">Low Tracks with Raised Gantry</p>
</div>

<style>
img {
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

*Note that the costs below do not account for [supporting infrastructure](../../FarmBot-Genesis-V1-4/supporting-infrastructure.md), which will also increase in cost as the device size increases.*

|Model                         |Track Length                  |Gantry Width                  |Growing Area                  |Cost                          |Cost/m^2                      |
|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|
|Genesis                       |1.5m *                        |1.5m                          |2.25m<sup>2</sup>             |~$2,700                       |$1,200
|Genesis                       |3m                            |1.5m                          |4.5m<sup>2</sup>              |~$2,700                       |$600
|Genesis XL                    |3m *                          |3m                            |9m<sup>2</sup>                |~$4,000                       |$444
|Genesis XL                    |4.5m *                        |3m                            |13.5m<sup>2</sup>             |~$4,000                       |$296
|Genesis XL                    |6m                            |3m                            |18m<sup>2</sup>               |~$4,000                       |$222

** indicates tracks that are shorter from the stock kit. Please note that at this time we do not sell kits with shorter tracks, so these calculations are for someone who does not utilize all of the components in their kit.*
