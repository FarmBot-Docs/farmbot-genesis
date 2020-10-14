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



![UTM 3.JPG](_images/UTM_3.JPG)



![UTM1.JPG](_images/UTM1.JPG)

# Pin mapping

|UTM Pin/UTM Wire              |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|**A** /<span class="cable-color red">red</span>|+5V                           |Soil sensor
|**B** /<span class="cable-color yellow">yellow</span>|Ground (0V)                   |Ground
|**C** /<span class="cable-color green">green</span>|Pin D63 - Digital-In          |Tool verification
|**D** /<span class="cable-color black">black</span>|Pin D59 (A5) - Analog-In      |Soil sensor and other analog signal tools
|**E** /<span class="cable-color white">white</span>|Pin D48                       |Anything you want
|**F** /<span class="cable-color brown">brown</span>|Your choice                   |Anything you want
|**G** /<span class="cable-color blue">blue</span>|Your choice                   |Anything you want
|**H** /<span class="cable-color grey">grey</span>|Your choice                   |Anything you want
|**I** /<span class="cable-color orange">orange</span>|Your choice                   |Anything you want
|**J** /<span class="cable-color purple">purple</span>|Your choice                   |Anything you want
|**K** /<span class="cable-color pink">pink</span>|Your choice                   |Anything you want
|**L** /<span class="cable-color cyan">cyan</span>|Your choice                   |Anything you want



{%
include callout.html
type="info"
title="Room for expansion"
content="Only four of the 12 wires/UTM pins are currently mapped. This is because the currently available FarmBot tools only need these four pins to function, which means that the other eight pins are ready for you to map however you desire. Dreaming of a USB, I2C, or PWM based tool? Go right ahead and expand upon your FarmBot's abilities with custom tools of your own!"
%}



{%
include callout.html
type="success"
title="Want to make your own UTM compatible tools?"
content="Check out the [tool spec](../../Extras/mods/tool-spec.md) to learn how to design and manufacture your own custom tools. We provide examples, CAD models, tech specs, and links to purchase parts."
%}

# Step 1: Install the UTM onto the Z-axis
Insert two **M5 x 16mm screws** and **tee nuts** into the **UTM**, and then position the UTM onto the **z-axis extrusion**. The mounting flanges should be positioned on the backside of the extrusion. The bottom of the UTM should be flush with the bottom of the extrusion. Tighten the two screws with the **3mm hex driver**.

![Screen Shot 2018-08-08 at 1.17.51 PM.png](_images/Screen_Shot_2018-08-08_at_1.17.51_PM.png)

# Step 2: Connect the UTM Cable
Insert the two UTM Cable Connectors into the top of the UTM. Note: The black and yellow connectors of the cable correspond to the black and yellow pin headers inside the UTM.

{%
include callout.html
type="success"
title="Ensure correct connection orientation"
content="Each connector and pin header have one missing pin in the corner to indicate the correct connection orientation.

Look into the UTM to see where the missing pin is located on each pin header. Then look where the individual UTM cable wires enter the connectors to see where the corresponding missing pin is located in the connectors. 

Use this information to ensure you insert both connectors in the correct orientation."
%}



![Screen Shot 2018-08-08 at 1.45.27 PM.png](_images/Screen_Shot_2018-08-08_at_1.45.27_PM.png)



![Screen Shot 2018-08-08 at 1.46.29 PM.png](_images/Screen_Shot_2018-08-08_at_1.46.29_PM.png)

Slide the **UTM cable's shroud** down such that it fully covers the opening in the top of the **UTM**.

![Screen Shot 2018-08-08 at 1.46.59 PM.png](_images/Screen_Shot_2018-08-08_at_1.46.59_PM.png)

Note: in a few steps from now, you will connect the other end of the cable to the Farmduino.

# Step 3: Connect the Water and Vacuum Tubes
Push the **water tube** onto the **barb** on top of the **UTM** that is closest to the **z-axis extrusion**.

![Screen Shot 2018-08-08 at 5.16.58 PM.png](_images/Screen_Shot_2018-08-08_at_5.16.58_PM.png)

Push the **vacuum pump tube** onto the **barb** on top of the **UTM** that is closest to the FarmBot logo.

![Screen Shot 2018-08-08 at 5.17.17 PM.png](_images/Screen_Shot_2018-08-08_at_5.17.17_PM.png)


# What's next?

 * [Camera](camera.md)
