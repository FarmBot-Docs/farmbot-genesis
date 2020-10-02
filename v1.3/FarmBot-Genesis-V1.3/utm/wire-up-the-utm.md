---
title: "Wire up the UTM"
slug: "wire-up-the-utm"
---

* toc
{:toc}

# Step 1: Feed the UTM cable through the UTM cover
Push the end of the **UTM cable** *without a connector* through the center **grommet** in the **UTM cover** so that the outer black rubber of the cable extends about 5cm beneath the cover.

{%
include callout.html
type="warning"
title="Be gentle"
content="It may be difficult to do this because of the friction and tight seal created between the grommet and the cable. Be gentle and take your time. Some soapy water can facilitate the cable to slide through more easily, and will dry up within a day."
%}



![Screen Shot 2017-02-12 at 9.29.45 PM.png](Screen_Shot_2017-02-12_at_9.29.45_PM.png)

The individual wires of the **UTM cable** are color coded. Fan out the wires in preparation for connection.

![Screen Shot 2017-02-12 at 9.34.42 PM.png](Screen_Shot_2017-02-12_at_9.34.42_PM.png)

# Step 2: Feed the tubing through the UTM cover
Push the **vacuum tube** (the short tube) through the **grommet** nearest the FarmBot logo on the **UTM cover** so that there is about 10cm of tubing beneath the cover.

![Screen Shot 2017-02-12 at 9.44.36 PM.png](Screen_Shot_2017-02-12_at_9.44.36_PM.png)

Push the **water tube** (the long tube) through the **grommet** nearest the **UTM cover** mounting flange so that there is about 10cm of tubing beneath the cover.

![Screen Shot 2017-02-12 at 9.47.04 PM.png](Screen_Shot_2017-02-12_at_9.47.04_PM.png)

Insert the **UTM cover plug** into the remaining **grommet** in the **UTM cover**. This port is available for you to expand the functionality of your FarmBot if you desire.

![Screen Shot 2017-02-12 at 10.02.09 PM.png](Screen_Shot_2017-02-12_at_10.02.09_PM.png)

# Step 3: Attach the tubes
Slide the **vacuum tube** and **water tube** onto the corresponding **barbs** on the **UTM**.

![Screen Shot 2017-02-12 at 10.15.26 PM.png](Screen_Shot_2017-02-12_at_10.15.26_PM.png)

# Step 4: Wire up the UTM
Use a **63.7mm zip-tie** to secure each UTM cable wire to the **M3 screw** on top of the **UTM** according to the pin mapping table below. The wire strands must make good contact with the screw threads.

![Screen Shot 2017-02-12 at 10.13.03 PM.png](Screen_Shot_2017-02-12_at_10.13.03_PM.png)

## Pin mapping

{%
include callout.html
type="success"
title="Room for expansion"
content="Only four of the 12 wires/UTM pins are currently mapped. This is because the currently available FarmBot tools only need these four pins to function, which means that the other eight pins are ready for you to map however you desire. Dreaming of a USB, I2C, or PWM based tool? Go right ahead and expand upon your FarmBot's abilities with custom tools of your own!"
%}



|UTM Pin/UTM Wire              |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|**A** /<span class="cable-color red">red</span>|+5V                           |Soil sensor
|**B** /<span class="cable-color yellow">yellow</span>|Ground (0V)                   |Ground
|**C** /<span class="cable-color green">green</span>|Pin D63 - Digital-In          |Tool verification
|**D** /<span class="cable-color black">black</span>|Pin D59 (A5) - Analog-In      |Soil sensor and other analog signal tools
|**E** /<span class="cable-color white">white</span>|Your choice                   |Anything you want
|**F** /<span class="cable-color brown">brown</span>|Your choice                   |Anything you want
|**G** /<span class="cable-color blue">blue</span>|Your choice                   |Anything you want
|**H** /<span class="cable-color grey">grey</span>|Your choice                   |Anything you want
|**I** /<span class="cable-color orange">orange</span>|Your choice                   |Anything you want
|**J** /<span class="cable-color purple">purple</span>|Your choice                   |Anything you want
|**K** /<span class="cable-color pink">pink</span>|Your choice                   |Anything you want
|**L** /<span class="cable-color cyan">cyan</span>|Your choice                   |Anything you want

# Step 5: Slide down the UTM cover
Slide the **UTM cover** down the tubes and cable until it sits flush against the top of the **UTM**. Ensure that no wires or tubes become disconnected and that there is sealing between the cable and the grommet.

![Screen Shot 2017-02-12 at 10.22.13 PM.png](Screen_Shot_2017-02-12_at_10.22.13_PM.png)

# Step 6: Install the UTM and cover onto the Z-axis
Position the **UTM cover** and **UTM** onto the **z-axis extrusion**. The mounting flanges should be positioned on the backside of the extrusion. The bottom of the UTM should be flush with the bottom of the extrusion, and the bottom of the UTM cover should be flush with the top of the UTM. Tighten all four **M5 screws** with the **3mm hex driver**.

![Screen Shot 2017-02-12 at 10.34.04 PM.png](Screen_Shot_2017-02-12_at_10.34.04_PM.png)



{%
include callout.html
type="success"
title="Woo hoo!"
content="You just finished the most tedious and arguably difficult part of building your FarmBot. Take a deep breath, do a stretch, and grab a snack - you deserve it!"
%}


# What's next?

 * [Electronics](../../FarmBot-Genesis-V1.3/electronics.md)
