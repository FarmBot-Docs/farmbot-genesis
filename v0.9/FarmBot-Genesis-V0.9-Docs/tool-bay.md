---
title: "Tool Bay"
slug: "tool-bay"
description: "Documentation and assembly instructions for the FarmBot Genesis Tool Bay"
---

* toc
{:toc}

FarmBot Genesis comes with two tool bays. These simple hardware components act as holsters for your tools and are shaped in such a way that FarmBot can automatically mount and dismount tools from the bay.

<div></div>

<style></style>






# Assembly Instructions



{%
include callout.html
type="info"
title="40 minutes"
content="This is the estimated time it will take to assemble both tool bays"
%}

## Step 1: Gather the parts and tools
Gather all the tool bay parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:

* 3mm hex (allen) driver
* Drill with a #2 phillips driver bit or a #2 phillips screwdriver

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|2                             |Tool Bay Plates
|2                             |20 x 40 x 300mm Aluminum Extrusion
|4                             |Tool Bay Mounting Plates
|16                            |M5 x 10mm Screws
|16                            |M5 Tee Nuts
|8                             |Wood Screws

## Step 2: Attach a tool bay plate to the extrusion
Use four **M5 x 10mm screws** and **M5 tee nuts** to attach the **tool bay plate** to one of the 20mm sides of the **aluminum extrusion**.





## Step 3: Attach the tool bay mounting plates to the extrusion
Use four **M5 x 10mm screws** and **M5 tee nuts** to attach the **tool bay mounting plates** to  the 40mm side of the **aluminum extrusion** that is underneath the tool bay plate.





## Step 4: Mount the Tool Bay
Attach the tool bay to your supporting infrastructure using the four wood screws.

{%
include callout.html
type="info"
title="Orientation matters"
content="Keep in mind that FarmBot's tools are designed to be mounted by the UTM in only one orientation so that the electrical pins and magnets match up. The text on the front of the tools should line up with the FarmBot logo on the front of the UTM. Because tools can only slot into the tool bay in two orientations, **you must orient your tool bay with the longer edge parallel to the gantry main beam**.

Note: It is possible to orient the long edge parallel with the tracks, though that would require changing the orientation of the UTM by 90 degrees as well."
%}



{%
include callout.html
type="success"
title="Within reach and squared up"
content="Ensure that you mount the tool bay in a location that FarmBot's UTM can get to. Keep in mind that the UTM needs to be able to slide tools **all the way into the bay**, **all the way out**, and be able to mount and dismount tools **from above**. Make sure you verify this for each of the tool bay's slots.

The tool bay plate must be **square** with the rest of FarmBot (all three axes) in order for tools to be properly mounted and dismounted. Use shims or extra washers to make fine adjustments to the angle of your tool bay."
%}




## Step 5: Repeat steps 2 through 4 for the second tool bay




{%
include callout.html
type="success"
title="Two bays not enough?"
content="If you are interested in using more than six tools and seeds bins at once, you will need to purchase or make more tool bays. Check out our [online shop](https://farmbot.io/shop)!"
%}



# Troubleshooting and Maintenance

## Tools are unable to be mounted or dismounted

# Change Log

No changes were made from the V0.8 tool bay.

# Room for Improvement

* All of FarmBot's plates are going to be tumble polished. The existing tool bay plate is very large (100 x 500mm) which means it will have trouble being properly polished and is at risk of being damaged in the tumbler. The solution is to make the plate smaller and hold fewer tools, and then have multiple tool bays.
* The tool bay is currently mounted in a fashion determined by the user. Because stored tools hang below the plate, the plate must be elevated sufficiently above any other surface such as the soil. This prevents the tool bay plate from being mounted directly to the top of the raised bed unless the soil level were to be very low. A solution is to provide some additional hardware that allows the bay to be more easily mounted.
