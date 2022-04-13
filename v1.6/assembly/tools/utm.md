---
title: "Universal Tool Mount"
slug: "utm"
description: "Documentation and assembly instructions for the FarmBot Genesis universal tool mount"
---

* toc
{:toc}

The Universal Tool Mount (UTM) allows FarmBot Genesis to automatically switch tools in order to perform different operations. It is a plastic component that mounts to the z-axis aluminum extrusion using two M5 screws and tee nuts. It features:

* 3 strong neodymium ring magnets to magnetically hold tools in place via other magnets placed in the same configuration on the tool.

* Passageways for water, liquid amendments (eg: fertilizer), and vacuum or compressed air to pass through from the UTM (and the rest of FarmBot) to the tool.

* 12 pogo pins that make electrical connections with tools. (See: [Pin Mapping](#pin-mapping))

{%
include callout.html
type="success"
title="Pre-assembled for your convenience"
content="As of the v1.4 hardware release, the UTM comes pre-assembled so all you need to do is mount it and connect the cable and tubes!"
%}

{% include gallery.html images="
![utm with barbs](_images/utm_with_barbs.jpg)
![utm side and bottom view](_images/utm_side_and_bottom_view.jpg)
" %}

# Pin mapping

|UTM Pin/UTM Wire                                     |is connected to          |and used for|
|-----------------------------------------------------|-------------------------|------------|
|**A** /<span class="cable-color red">red</span>      |+5V                      |Soil sensor
|**B** /<span class="cable-color yellow">yellow</span>|Ground (0V)              |Ground
|**C** /<span class="cable-color green">green</span>  |Pin D63 - Digital-In     |Tool verification
|**D** /<span class="cable-color black">black</span>  |Pin D59 (A5) - Analog-In |Soil sensor and other analog signal tools
|**E** /<span class="cable-color white">white</span>  |DC 1                     |Rotary tool
|**F** /<span class="cable-color brown">brown</span>  |Your choice              |Anything you want
|**G** /<span class="cable-color blue">blue</span>    |Your choice              |Anything you want
|**H** /<span class="cable-color grey">grey</span>    |DC 2                     |Rotary tool
|**I** /<span class="cable-color orange">orange</span>|Your choice              |Anything you want
|**J** /<span class="cable-color purple">purple</span>|Your choice              |Anything you want
|**K** /<span class="cable-color pink">pink</span>    |Your choice              |Anything you want
|**L** /<span class="cable-color cyan">cyan</span><br>(shunted to the cable shielding with dark dray heatshrink)|Earth Ground|Earth Ground

{%
include callout.html
type="info"
title="Room for expansion"
content="The unassigned UTM pins are available for you to custom map. Dreaming of a USB, I2C, or PWM based tool? Go right ahead and expand upon your FarmBot's abilities with custom tools of your own!"
%}

{%
include callout.html
type="success"
title="Want to make your own UTM compatible tools?"
content="Check out the [tool spec](../../extras/mods/tool-spec.md) to learn how to design and manufacture your own custom tools. We provide examples, CAD models, tech specs, and links to purchase parts."
%}

# Step 1: Install the UTM onto the Z-axis

Insert two **M5 x 16mm screws** and **tee nuts** into the **UTM**, and then position the UTM onto the [[z-axis extrusion]]. The mounting flanges should be positioned on the backside of the extrusion. The bottom of the UTM should be flush with the bottom of the extrusion. Tighten the two screws with the **3mm hex driver**.

![utm mounted on z-axis](_images/utm_mounted_on_z-axis.png)

# Step 2: Connect the UTM Cable

Insert the two UTM Cable Connectors into the top of the UTM. Note: The black and yellow connectors of the cable correspond to the black and yellow pin headers inside the UTM. Then slide the **UTM cable's shroud** down such that it fully covers the opening in the top of the **UTM**.

{%
include callout.html
type="success"
title="Ensure correct connection orientation"
content="Each connector and pin header have one missing pin in the corner to indicate the correct connection orientation.

Look into the UTM to see where the missing pin is located on each pin header. Then look where the individual UTM cable wires enter the connectors to see where the corresponding missing pin is located in the connectors.

Use this information to ensure you insert both connectors in the correct orientation."
%}

{% include gallery.html images="
![utm pcb connectors](_images/utm_pcb_connectors.png)
![utm with cable connected](_images/utm_with_cable_connected.png)
![utm with cable covered](_images/utm_with_cable_covered.png)
" %}

{%
include callout.html
type="info"
content="You will connect the other end of the cable to the Farmduino in a few steps from now."
%}

# Step 3: Connect the Water Tube

Push the **water tube** onto the **barb** on top of the **UTM** that is closest to the [[z-axis extrusion]].

![utm water tube connection](_images/utm_water_tube_connection.png)

{%
include callout.html
type="info"
content="You will connect the vacuum pump tube in a few steps from now."
%}

# What's next?

 * [Camera](camera.md)
