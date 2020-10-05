---
title: "Universal Tool Mount"
slug: "universal-tool-mount"
description: "Documentation and assembly instructions for the FarmBot Genesis Universal Tool Mount"
---

* toc
{:toc}

The Universal Tool Mount (UTM) allows FarmBot Genesis to automatically switch which tool is on the z-axis depending on the operation needing to be completed. The UTM is necessary because it is not feasible to have all tools mounted on the z-axis at one time for several reasons:

  * This would be very heavy and create more stresses on all components, as well as necessitate a larger z-axis motor.
  * Most tools need to be the “lowest” thing on the z-axis in order to work. Having multiple tools competing for the lowest position (ex: a temperature probe and a seed injector) would not be ideal and may not work at all. The use of individual tool raising and lowering mechanisms, or a turret style mechanism would be complex, heavy, bulky, and limited in the number of tools it could support.
  * The Z-Axis’s size must be kept to a minimum in order for it to have minimal impact on the plants, especially when there is not very much space between them.
  * The UTM is a single 3D printed component that mounts to the Z-Axis aluminum extrusion using two M5 screws and tee nuts. It features 3 strong neodymium ring magnets to magnetically hold tools in place via washers or other magnets placed in the same configuration on the Tool. The magnets double as the keying system to ensure that tools are properly oriented in the UTM. The magnets also function as the passage ways for water, liquid amendments (eg: fertilizer), and vacuum or compressed air to pass through from the UTM (and the rest of FarmBot) to the Tool. In addition, the UTM has 4 spring loaded screws that make electrical connections with Tools. Two are for power (GND and +5V), and two are for data (0 to +5V).

<iframe width="100%" height="480" src="https://sketchfab.com/models/555a50936d5d4f6d835a3daf9fd48c95/embed?ui_controls=0&amp;ui_infos=0&amp;ui_related=0" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel=""></iframe>



{%
include callout.html
type="info"
title="Rotate, pan, and zoom"
content="**Mouse and trackpad:** Left-click to rotate, right-click to pan, and scroll to zoom.
**Touchscreen:** Use one finger to rotate, two fingers to pan, and pinch to zoom."
%}






{%
include callout.html
type="success"
title="Want to make your own UTM compatible tools?"
content="Check out the [Tool Spec](../FarmBot-Genesis-V0.9-Docs/tool-spec.md) to learn how to design and manufacture your own custom tools. We provide examples, CAD models, tech specs, and links to purchase parts."
%}



# Assembly Instructions



{%
include callout.html
type="info"
title="45 minutes"
content="This is the estimated time it will take to assemble the Universal Tool Mount."
%}

## Step 1: Gather the Parts and Tools
Gather all the UTM parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:

* 2mm hex (allen) driver
* 3mm hex (allen) driver
* 6mm wrench
* 8mm wrench
* Exacto blade
* Wire strippers

|Part Name                     |Description                   |Qty.                          |
|------------------------------|------------------------------|------------------------------|
|M5x12mm Screws                |Stainless, 0.8 thread pitch, low-profile 3mm hex heads|2
|Tee Nuts                      |Stainless steel, for attaching M5 screws to OpenBuilds aluminum extrusions|2
|Universal Tool Mount          |3D printed                    |1
|Springs                       |Metric Compression Spring, Stainless Steel, 9.4 mm Overall, 5.5 mm OD, .50 mm Wire|12
|M3 Locknuts                   |Stainless steel, .5MM Pitch, nylon insert|24
|M3 Flag Ring Terminals        |Noninsulated, 22-18 AWG Wire Size, #6 Screw/Stud|12
|Cable                         |Continuous-Flex Cable Unshielded, 20 Gauge, 12 Wires, 300V AC, 10 ft. Length|1
|Barbs                         |Miniature Stainless Steel Barbed Tube Fitting, Straight for 1/4" Tube ID X 10-32 UNF Male Pipe|3
|O-rings                       |Multipurpose Chemical-Resistant O-Ring, Viton(R) Fluoroelastomer, 1.5MM Wide, 7MM ID|3
|Ring Magnets                  |15mm OD x 5mm ID x 5mm thick  |3
|M5 x 30mm Screws              |Stainless steel type 316, 0.8 thread pitch, low-profile 3mm hex heads|3
|M5 Locknuts                   |Stainless steel with nylon insert, 0.8mm thread pitch|3

## Step 2: Install the magnets

{%
include callout.html
type="info"
title="Opposites attract"
content="For the UTM to correctly mount tools, all magnets on the UTM and all tools must have the same polar orientation. For example, all of the magnets could have the North pole/face of the magnet facing towards the ground. This way, the North pole/face of the *UTM* magnets (which face the ground) will be attracted to the South pole/face of the *tool* magnets (which face the sky).

Which side is North and which is South does not matter. The important part is that the orientation of all the magnets are the same."
%}

Insert an **M5 x 30mm screw** through one of the **ring magnets**. For the first magnet, the orientation does not matter.


Insert the magnet/screw combo into the **UTM** and  use the **3mm hex driver** and the **8mm wrench** to tighten an **M5 locknut** onto the screw.


Repeat the process above for the two remaining UTM magnets.

{%
include callout.html
type="success"
title="Before tightening the last two locknuts..."
content="Ensure that the polar orientation of all the UTM magnets are the same. You can do this by holding a fourth magnet near the UTM magnets. Without flipping the magnet in your hand, it should either be attracted to all of the UTM magnets, or repelled from all of the UTM magnets. Again, it doesn't matter which way they are installed, as long as they are all the same with respect to each other."
%}

## Step 3: Install the Barbs
Use the **8mm wrench** to screw in the three **barbs** to the **UTM**. The barbs should be inserted in the holes labelled A, B, and C.


## Step 4: Install the o-rings
Slide three **o-rings** onto the **UTM** A, B, and C port cones. Each o-ring should be "seated" in the small groove at the base of the port cone.

## Step 5: Install the electronic contact screws
Place a **spring** on an **M3 x 40mm screw**, and then insert the screw into the **UTM**.


Using the **2mm hex driver** and the **6mm wrench**, attach an **M3 locknut** onto the screw. Tighten the locknut until the spring is slightly compressed.


## Step 6: Prepare the UTM Cover
Insert four **rubber seals** into the **UTM cover**. Ensure that the seal flanges are not folded or caught under themselves.


Insert two **M5 x 10mm screws** through the **UTM cover** mounting holes and then lightly thread a **tee nut** onto each screw.


Insert the **UTM plug** into *port C* of the UTM cover. This port will not be used with the standard kit, but you may expand your FarmBot's capabilities in the future to use it.


Push the **UTM cable** through the center hole in the **UTM cover** so that there is about 10cm of cabling beneath the cover. It may be difficult to do this because of the friction and tight seal created between the rubber seal and the cable. Be gentle and take your time. Some soapy water can facilitate the cable to slide through more easily, and will dry up within a day.


Push the **water tube** through *port A* on the **UTM cover** so that there is about 10cm of cabling beneath the cover.


Push the **vacuum tube** through *port B* on the **UTM cover** so that there is about 10cm of cabling beneath the cover.


## Step 7: Wire up the UTM
Use the **exacto blade** to remove 5cm of the **UTM cable** outer rubber insulation.

{%
include callout.html
type="warning"
title="Take your time"
content="When removing the outer insulation, it is easy to accidentally cut through some of the smaller wires inside the cable, or cut through their insulation. Take your time to avoid accidentally doing this.

If you do accidentally sever one of the smaller wires, you must cut the entire cable down to an uncut section and start over."
%}




Each small wire of the **UTM cable** is numbered with small white text. Fan out the wires and arrange them in order from 1 to 12.


 Use the **wire strippers** to remove 0.5 to 1cm of insulation from each small wire.


Use a **zip-tie** to secure each wire to the corresponding **M3 screw** on top of the **UTM**. Wire 1 should connect to UTM pin/screw 1, and so forth.





### Pin Mapping

|UTM Pin                       |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|1                             |Ground (0V) on Arduino/RAMPS  |Ground
|2                             |+5V on Arduino/RAMPS          |Tool Verification
|3                             |Pin D16 on Arduino/RAMPS - Digital-In|Tool Verification
|4                             |Pin D17 on Arduino/RAMPS - Digital I/O|Data tool functions such as servo control or sensor reading
|5                             |Pin D23 on Arduino/RAMPS - Digital I/O|Data tool functions such as servo control or sensor reading
|6                             |Pin D8 on Arduino/RAMPS - High power output|High power tool functions such as motors or lasers
|7                             |Pin 20 on Arduino/RAMPS - I2C data (SDA)|Complex tooling requiring addressing of commands
|8                             |Pin 21 on Arduino/RAMPS - I2C clock (SCL)|Complex tooling requiring addressing of commands
|9                             |USB VCC (+5V)                 |USB based tools
|10                            |USB D- (Data -)               |USB based tools
|11                            |USB D+ (Data +)               |USB based tools
|12                            |USB Ground (0V)               |USB based tools

## Step 8: Install the UTM Cover and UTM on the Z-Axis
Slide the **water tube** onto the *port A* **barb**, and the **vacuum tube** onto the *port B* barb.


Slide the **UTM cover** down the tubes and cable until it sits flush against the top of the UTM.

{%
include callout.html
type="warning"
title="Keep it sealed"
content="The UTM cable's outer insulation must maintain contact with the UTM cover's rubber seal in order to keep rain out. It is best to keep 1cm or more of the cable's insulation inside of the cover."
%}




Slide the **UTM cover** and **UTM** onto the **z-axis** extrusion. The plastic brackets should be positioned on the backside of the extrusion. The bottom of the UTM should be flush with the bottom of the extrusion, and the bottom of the UTM cover should be flush with the top of the UTM.


Tighten all four **M5 screws** with the **3mm hex driver**.




{%
include callout.html
type="success"
title="Woo hoo!"
content="You just finished the most tedious and arguably difficult part of building your FarmBot. Take a deep breath, do a stretch, and grab a snack - you deserve it!"
%}



# Troubleshooting and Maintenance



{%
include callout.html
type="info"
title="Don't forget about general maintenance"
content="The tips below apply specifically to the UTM and no other components of your FarmBot. Make sure to view the [General Maintenance](../FarmBot-Genesis-V0.9-Docs/maintenance-guide.md) page as well for system-wide tips."
%}

## Inspect the Seals
It is possible that intense temperature and adverse weather cycles could degrade the rubber seals between the UTM cover and the cables and tubing connected to the UTM.

{%
include callout.html
type="success"
title="Once per year"
content="Inspect the rubber seals to ensure they are not cracked, broken, or otherwise degraded to the point of sealing ineffectively. If any damage is found, replace them as soon as possible."
%}

## Remove Magnetic Debris Buildup
It is possible for dust, soil, and other debris to magnetically attract to the UTM's magnets and build up over time. This debris can prevent the UTM from correctly mounting tools.

{%
include callout.html
type="success"
title="Once per year"
content="inspect the UTM's magnets for debris. If any is found, remove the M5 locknut and screw holding the magnet in place and remove the magnet for cleaning."
%}



# Change Log

  * Repositioned the magnets and liquid/gas lines for aesthetic purposes
  * Switched from flag terminals to zip ties to save space on the electrical connections and ease the assembly process

# Room for Improvement

* Decrease the distance between the UTM magnets and the tool magnets by using lower profile head screws. This will increase magnetic holding power.
