---
title: "Seed Injector"
slug: "seed-injector"
description: "Documentation and assembly instructions for the FarmBot Genesis Seed Injector"
---

The V0.9 seed injector works by using a strong vacuum pump to suction-hold a single seed onto the plastic tip. It is made of a single 3D printed plastic piece with a few other components screwed onto it for magnetic coupling and electronic verification with the UTM.

<iframe width="100%" height="480" src="https://sketchfab.com/models/8b911ee71b9346e592a1e5d64135e4a1/embed?ui_controls=0&amp;ui_infos=0&amp;ui_related=0" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel=""></iframe>






# Assembly Instructions



{%
include callout.html
type="info"
title="15 minutes"
content="This is the estimated time it will take to assemble the seed injector"
%}

## Step 1: Gather the parts and tools
Gather all the seed injector parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:
* 2mm hex (allen) driver
* 3mm hex (allen) driver
* 6mm wrench
* 8mm wrench
* Wire strippers

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|1                             |Seed Injector Base
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
content="For the seed injector to correctly mount to the UTM, all magnets on the seed injector must be attracted to the magnets in the UTM.

To find the correct orientation for a seed injector magnet, hold it near the mounting side of the UTM. Flip it around in your hand until you feel it attracting to the UTM's magnets. This is the correct orientation for mounting to the seed injector base."
%}

Secure the three **ring magnets** to the top of the **seed injector base** using three **M5 x 25mm** screws and **M5 locknuts**. The screw head should be on the magnet side of the seed injector base. Use the **3mm hex driver** and **8mm wrench** to tighten the components.


## Step 3: Install the Electrical Screws
Use the **2mm hex driver** and **6mm wrench** to attach two **M3 x 16mm screws** and **M3 locknuts** into the holes labelled 2 and 3 on the **seed injector base**. The screw heads should be on the same side of the base as the magnets.


## Step 4: Add the Jumper Wire
Use **wire strippers** to remove 1cm of insulation from both ends of the **jumper wire**.


Attach the **jumper wire** to the **M3 screws** using two **zipties**.




# Troubleshooting and Maintenance



{%
include callout.html
type="info"
title="Don't forget about general maintenance"
content="The tips below apply specifically to the seed injector and no other components of your FarmBot. Make sure to view the [General Maintenance](maintenance-guide.md) page as well for system-wide tips."
%}

## Remove internal debris buildup
It is possible for dust, soil, and other debris to become stuck inside of the plastic seed injector tip. This can cause a loss of seed suction power and prevent the seed injector from working reliably.

{%
include callout.html
type="success"
title="Every three months"
content="Wash out the inside of the seed injector tip by running warm water through the seed injector."
%}

## Remove Magnetic Debris Buildup
It is possible for dust, soil, and other debris to magnetically attract to the seed injector's magnets and build up over time. This debris can prevent the seed injector from correctly mounting to the UTM.

{%
include callout.html
type="success"
title="Every three months"
content="Inspect the seed injector's magnets for debris. If any is found, use your fingers or a brush to remove it."
%}



# Change Log

* The seed injector tip was repositioned to the front, center of the tool for aesthetic purposes.
* The tip was extended to better reach into the seed bins.

# Room for Improvement

* For most tools, it makes sense to attempt to have the end effector of the tool positioned in the X/Y center of the tool/UTM. This will allow that tool to be used at the precise locations that other tools are used at without the need for offsets. The current seed injector design has an offset injection tip. In the next version we will re-design it so the tip is in the center of the tool.
* The vacuum pump based seed injector is prone to sucking up soil and other debris. Over time this clogs the injector, the UTM pass-through ports, tubing, and causes damage to the vacuum pump. To alleviate this problem most easily, the seed injector tip should have a filtering cloth or other material that allows air to enter, but no other debris. With such a change, the injector tips' conical barrel can be reduced to a simple consistently sized passageway.
