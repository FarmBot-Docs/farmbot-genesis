---
title: "Watering Nozzle"
slug: "watering-nozzle"
excerpt: "Documentation and assembly instructions for the FarmBot Genesis Watering Nozzle"
---

* toc
{:toc}

The watering nozzle is a single 3D printed component with a few extra parts for magnetic coupling and electronic verification with the UTM. It works as a simple diffuser nozzle by accepting a concentrated stream of water coming from the UTM and turning it into a gentle shower.

<iframe width="100%" height="480" src="https://sketchfab.com/models/d343f37909c1491b9fba49fe39b71065/embed?ui_controls=0&amp;ui_infos=0&amp;ui_related=0" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel=""></iframe>






# Assembly Instructions



{%
include callout.html
type="info"
title="15 minutes"
content="This is the estimated time it will take to assemble the Watering Nozzle"
%}

## Step 1: Gather the parts and tools
Gather all the watering nozzle parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:
* 2mm hex (allen) driver
* 3mm hex (allen) driver
* 6mm wrench
* 8mm wrench
* Wire strippers

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|1                             |Watering Nozzle Base
|3                             |Ring Magnets (15 x 15 x 5mm)
|3                             |M5 x 25mm Screws
|3                             |M5 Locknuts
|2                             |M3 x 16mm Screws
|2                             |M3 Locknuts
|1                             |Jumper Wire (18 guage, 5cm length)
|2                             |Zipties

## Step 2: Install the Magnets

{%
include callout.html
type="info"
title="Opposites attract"
content="For the watering nozzle to correctly mount to the UTM, all magnets on the watering nozzle must be attracted to the magnets in the UTM.

To find the correct orientation for a watering nozzle magnet, hold it near the mounting side of the UTM. Flip it around in your hand until you feel it attracting to the UTM's magnets. This is the correct orientation for mounting to the watering nozzle base."
%}

Secure the three **ring magnets** to the top of the **watering nozzle base** using three **M5 x 25mm** screws and **M5 locknuts**. The screw head should be on the magnet side of the watering nozzle base. Use the **3mm hex driver** and **8mm wrench** to tighten the components.


## Step 3: Install the Electrical Screws
Use the **2mm hex driver** and **6mm wrench** to attach two **M3 x 16mm screws** and **M3 locknuts** into the holes labelled 2 and 3 on the **watering nozzle base**. The screw heads should be on the same side of the base as the magnets.


## Step 4: Add the Jumper Wire
Use **wire strippers** to remove 1cm of insulation from both ends of the **jumper wire**.


Attach the **jumper wire** to the **M3 screws** using two **zipties**.




# Troubleshooting and Maintenance



{%
include callout.html
type="info"
title="Don't forget about general maintenance"
content="The tips below apply specifically to the UTM and no other components of your FarmBot. Make sure to view the [General Maintenance](../FarmBot-Genesis-V0-9-Docs/maintenance-guide.md) page as well for system-wide tips."
%}

## Remove Magnetic Debris Buildup
It is possible for dust, soil, and other debris to magnetically attract to the watering nozzle's magnets and build up over time. This debris can prevent the watering nozzle from correctly mounting to the UTM.

{%
include callout.html
type="success"
title="Every three months"
content="Inspect the watering nozzle's magnets for debris. If any is found, use your fingers or a brush to remove it."
%}



# Change Log

* The water intake was repositioned

# Room for Improvement

* Standard municipal water pressure is so high that it causes the watering nozzle's shower to be closer to a jet stream and can introduce leaking at the seal between the nozzle and the UTM as well as at the UTM barb and the watering tube conncetion. A standard 25 psi inline pressure regulator used in drip irrigation systems should be placed between the house water faucet and the hose connecting to FarmBot.
