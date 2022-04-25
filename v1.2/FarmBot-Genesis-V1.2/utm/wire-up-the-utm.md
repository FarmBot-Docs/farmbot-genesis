---
title: "Wire up the UTM"
slug: "wire-up-the-utm"
---

# Step 1: Feed the UTM cable through the UTM cover
Push the end of the **UTM cable** *without connectors* through the center **grommet** in the **UTM cover** so that the outer gray rubber of the cable extends about 5cm beneath the cover.

{%
include callout.html
type="warning"
title="Be gentle"
content="It may be difficult to do this because of the friction and tight seal created between the grommet and the cable. Be gentle and take your time. Some soapy water can facilitate the cable to slide through more easily, and will dry up within a day."
%}



![Screen Shot 2017-02-12 at 9.29.45 PM.png](_images/Screen_Shot_2017-02-12_at_9.29.45_PM.png)

The 1st thru 11th small wires of the **UTM cable** are numbered with small white text, while the 12th wire is colored yellow/green. Fan out the wires and arrange them in order from 1 to 12.

![Screen Shot 2017-02-12 at 9.34.42 PM.png](_images/Screen_Shot_2017-02-12_at_9.34.42_PM.png)

# Step 2: Feed the tubing through the UTM cover
Push the **vacuum tube** through the **grommet** nearest the FarmBot logo on the **UTM cover** so that there is about 10cm of tubing beneath the cover.

![Screen Shot 2017-02-12 at 9.44.36 PM.png](_images/Screen_Shot_2017-02-12_at_9.44.36_PM.png)

Push the **water tube** through the **grommet** nearest the **UTM cover** mounting flange so that there is about 10cm of tubing beneath the cover.

![Screen Shot 2017-02-12 at 9.47.04 PM.png](_images/Screen_Shot_2017-02-12_at_9.47.04_PM.png)

Insert the **UTM cover plug** into the remaining **grommet** in the **UTM cover**. This port is available for you to expand the functionality of your FarmBot if you desire.

![Screen Shot 2017-02-12 at 10.02.09 PM.png](_images/Screen_Shot_2017-02-12_at_10.02.09_PM.png)

# Step 3: Attach the tubes
Slide the **vacuum tube** and **water tube** onto the corresponding **barbs** on the **UTM**.

![Screen Shot 2017-02-12 at 10.15.26 PM.png](_images/Screen_Shot_2017-02-12_at_10.15.26_PM.png)

# Step 4: Wire up the UTM
Use a **zip-tie** to secure each UTM cable wire to the **M3 screw** on top of the **UTM** according to the pin mapping table below. The copper wires must make good contact with the screw threads.

![Screen Shot 2017-02-12 at 10.13.03 PM.png](_images/Screen_Shot_2017-02-12_at_10.13.03_PM.png)

## Pin mapping

{%
include callout.html
type="success"
title="Room for expansion"
content="Only four of the 12 wires/UTM pins are currently mapped. This is because the currently available FarmBot tools only need these four pins to function, which means that the other eight pins are ready for you to map however you desire. Dreaming of a USB, I2C, or PWM based tool? Go right ahead and expand upon your FarmBot's abilities with custom tools of your own!"
%}



|UTM Pin/UTM Wire              |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|A/1                           |+5V on Arduino/RAMPS          |Soil sensor
|B/2                           |Ground (0V) on Arduino/RAMPS  |Ground
|C/3                           |Pin D63 on Arduino/RAMPS - Digital-In|Tool verification
|D/4                           |Pin D59 (A5) on Arduino/RAMPS - Analog-In|Soil sensor and other analog signal tools
|E/5                           |Your choice                   |Anything you want
|F/6                           |Your choice                   |Anything you want
|G/7                           |Your choice                   |Anything you want
|H/8                           |Your choice                   |Anything you want
|I/9                           |Your choice                   |Anything you want
|J/10                          |Your choice                   |Anything you want
|K/11                          |Your choice                   |Anything you want
|L/12 (yellow/green)           |Your choice                   |Anything you want



{%
include callout.html
type="info"
title="Note"
content="As of the v4.0.0 software released on June 21, 2017, the UTM Pin/Wire A/1 should be connected to +5V on Arduino/RAMPS, while B/2 should be connected to Ground. This change is because the tool verification pin now uses the pull-up resistor in the firmware, so it should be jumped to Ground, instead of +5V. Note: you should double check the wiring of your soil sensor as well."
%}

# Step 5: Slide down the UTM cover
Slide the **UTM cover** down the tubes and cable until it sits flush against the top of the **UTM**. Ensure that no wires or tubes become disconnected and that there is sealing between the cable and the grommet.

![Screen Shot 2017-02-12 at 10.22.13 PM.png](_images/Screen_Shot_2017-02-12_at_10.22.13_PM.png)

# Step 6: Install the UTM and cover onto the Z-axis
Position the **UTM cover** and **UTM** onto the **z-axis extrusion**. The mounting flanges should be positioned on the backside of the extrusion. The bottom of the UTM should be flush with the bottom of the extrusion, and the bottom of the UTM cover should be flush with the top of the UTM. Tighten all four **M5 screws** with the **3mm hex driver**.

![Screen Shot 2017-02-12 at 10.34.04 PM.png](_images/Screen_Shot_2017-02-12_at_10.34.04_PM.png)



{%
include callout.html
type="success"
title="Woo hoo!"
content="You just finished the most tedious and arguably difficult part of building your FarmBot. Take a deep breath, do a stretch, and grab a snack - you deserve it!"
%}


# What's next?

 * [Electronics](../electronics.md)
