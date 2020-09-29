---
title: "High Level Overview"
slug: "high-level-overview"
excerpt: "Bird's eye view of what FarmBot is all about"
---

* toc
{:toc}


![v1.1.png](v1.1.png)

Genesis is a small scale FarmBot primarily constructed from V-Slot aluminum extrusions and aluminum plates and brackets. Genesis is driven by NEMA 17 stepper motors, an Arduino MEGA with a RAMPS shield, and a Raspberry Pi 3 computer. These electronics were chosen for their great availability, support, and usage in the DIY 3D printer world. Genesis can vary in size from a planting area as little as 1m<sup>2</sup> to a maximum of 4.5m<sup>2</sup>, while accommodating a maximum plant height of about 1m. With additional hardware and modifications we anticipate the Genesis concept to be able to scale to approximately 50m<sup>2</sup> and a maximum plant height of 1.5m.

{%
include callout.html
type="success"
title="Not your typical product"
content="We've gone through great lengths to design FarmBot Genesis to be durable, easily assembled and modified with common tools, constructed from largely off-the-shelf components, and manufactured with readily available processes and materials. Nothing about FarmBot speaks obsolescence or proprietary.

We've done this because at our core, we're makers and hackers just like you. We enjoy tearing apart our gadgets and gizmos to fix them, improve them, and make them different and unique. So that's what FarmBot Genesis is all about - empowering you to truly own FarmBot technology inside and out.

Go ahead and make your tracks longer, design a tool that electrocutes weeds, program FarmBot to spray water at the local cats, grow mushrooms, flowers, hydroponically, or on your living room wall! We can't wait to see what you do with FarmBot.

We hope you'll find our documentation useful and a great starting point for working with FarmBot and making it your own. If you ever have any questions, please head on over to the [forum](http://forum.farmbot.org). Cheers!"
%}

# Tracks
Tracks are one of the components that really differentiate FarmBot technology from traditional free-driving wheeled tractors. The tracks are what allow the system to have great precision in an efficient and simple manner. There are many reasons of why Tracks are superior, a few of which are listed below.
1. Tracks provide great precision and allow the the FarmBot to return to the same position repeatedly
2. Any type of packing structure of plants can be created and managed
3. Tracks take up less area than paths for tractor wheels and do not compact the soil

# Gantry
The Gantry is the the structural component that bridges the two Tracks and moves in the X-direction via an X-Direction Drive System. Typically, it serves as a linear guide for the Cross-Slide and a base for the Y-Direction Drive System that moves the Cross-Slide across the Gantry in the Y-direction. It can also serve as a base for mounting other tools, electronics, supplies, and/or sensors.

# Cross-Slide
The Cross-Slide moves in the Y-Direction across the Gantry. This motion provides the second major degree of freedom for FarmBots and allows operations such as planting to be done anywhere in the XY plane. The Cross-Slide is moved using a Y-Direction Drive System and functions as the base for the Tool Mount and Z-Direction Drive System.

# Z-Axis
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
  border: 1px solid #d0d0d0;
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

# Raised Tracks vs Low Tracks
For FarmBots to properly grow taller plants, the Gantry, Cross-Slide, Z-Axis, and Tools must have adequate vertical clearance from the plants. This can generally be accomplished in two ways:

1. Using raised tracks and a low-profile gantry
2. Using low tracks with a tall gantry

In general, using low tracks with a tall gantry is the better design, especially for larger applications because it saves on material cost, is less of an eyesore, blocks less sunlight, and would be easier to maintenance. However, in the case of a FarmBot being installed in a greenhouse or other structure, utilizing the existing walls to support the tracks higher may be a better solution.

<div class="hardware-overview-image">
  <a href="Raised_Tracks_vs_Low_Tracks.png">
  <img src="https://cloud.githubusercontent.com/assets/12681652/15698343/672605a4-2778-11e6-9d69-5b27df2bab3a.png" />
  </a>
  <p style="top:5%;left:8%;width:350px;">Raised Tracks with Low-Profile Carriage</p>
  <p style="top:5%;left:53%;width:100px;">vs.</p>
  <p style="top:5%;left:65%;width:250px;">Low Tracks with Raised Carriage</p>
</div>

<style>
img {
  width: 100%;
}
.hardware-overview-image { 
	position: relative; 
  width: 100%;
  border: 1px solid #d0d0d0;
}
.hardware-overview-image p {
  position: absolute; 
  font-size: 16px;
  font-weight: bold;
  text-align: center;
}
</style>

