---
title: "Weeder"
slug: "weeder"
description: "Documentation and assembly instructions for the FarmBot Genesis Weeder"
---

* toc
{:toc}

The weeding tool is a single 3D printable component magnetically mounts onto FarmBot's UTM like any other tool. It works by driving the tool vertically into the soil in order to push any small weeds under the soil, and disrupt their young fragile root systems.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2Fec9a1a4b27a743d98c51bc78307937e0%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2Fec9a1a4b27a743d98c51bc78307937e0&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2Fec9a1a4b27a743d98c51bc78307937e0%2Fdist%2Fthumbnails%2F16a6dad6cc7f48b0b01cbff5d6b09a98%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>



{%
include callout.html
type="success"
title="Weeding early and often"
content="This tool, and FarmBot in general, is designed for removing weeds early and often such that the weeds are always **small, young, and fragile**, and therefore easily removed.

What makes this possible is FarmBot's diligence. FarmBot has 24 hours a day to maintain your garden meticulously. It can be configured to remove weeds every single day that a human would never waste their time with. This prevents weeds from even having a chance at becoming a real problem.

If you configure FarmBot well, you will never even notice weeds in your garden because they will never have a chance to survive beyond germination. Over time, the number of weed seeds in your growing area will approach zero."
%}



{%
include callout.html
type="info"
title="Not designed for large, established weeds"
content="Do not expect this tool, or FarmBot in general, to be able to remove large, established weeds. Instead, configure your FarmBot to weed more often so that weeds do not have a chance at becoming large and established."
%}






# Design Comparison

With V1.0 hardware we experimented with six different weeding tool designs. They all operate on the same basic principle - push the weeds under the soil and disrupt their root systems. Some of the designs include plastic fins with the intention to grab the soil and lift it up during retraction in order to further disrupt the roots and soil.

The primary problem with most of the designs is that they were too difficult to push through the soil's surface because the spikes and/or fins provided too much surface area. Even in extremely soft, airy soil, many of these designs did not work as intended - rather they would simply smash the surface of the soil. A secondary problem was that the designs with close together fins became clogged with soil. Third, some of the designs are difficult to print with hobby level FDM 3D printers.

The **[Four Spike Weeder](#four-spike-weeder)** proved to be the best design because its small surface area allows it to easily push into the soil surface, and the tapered spikes without fins are not conducive to clogging.

|Design                        |Pros                          |Cons                          |
|------------------------------|------------------------------|------------------------------|
|Four Spike Weeder             |Easy to push into the soil surface, not conducive to clogging, easy to print|-
|Weeder with Many Spikes       |Easy to print                 |Could not push into the soil surface
|Small Weeder with Center Fins |-                             |Difficulty pushing into the soil surface, less easy to print
|Big Weeder with Center Fins   |-                             |Could not push into the soil surface, dificult to print
|Small Weeder with Fins, no Center|-                             |Difficulty pushing into the soil surface, became clogged with soil, less easy to print
|Large Weeder with Fins, no Center|-                             |Could not push into the soil surface, difficult to print

## Four Spike Weeder

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2Fec9a1a4b27a743d98c51bc78307937e0%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2Fec9a1a4b27a743d98c51bc78307937e0&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2Fec9a1a4b27a743d98c51bc78307937e0%2Fdist%2Fthumbnails%2F16a6dad6cc7f48b0b01cbff5d6b09a98%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>

## Weeder with Many Spikes

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2F59a08526f8c3415a9daeb9aa2040bf6a%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2F59a08526f8c3415a9daeb9aa2040bf6a&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2F59a08526f8c3415a9daeb9aa2040bf6a%2Fdist%2Fthumbnails%2F0b8120f493e54cb3919ca7f3eb36707e%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>

## Small Weeder with Center Fins

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2F731a33f5b2f841bb99a60b13bc9b071b%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2F731a33f5b2f841bb99a60b13bc9b071b&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2F731a33f5b2f841bb99a60b13bc9b071b%2Fdist%2Fthumbnails%2Fd8a218ca581548eea36d4ea1cc8bd590%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>

## Big Weeder with Center Fins

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2F5ad59189cff54aa4bdab3ae46c9ce5f3%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2F5ad59189cff54aa4bdab3ae46c9ce5f3&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2F5ad59189cff54aa4bdab3ae46c9ce5f3%2Fdist%2Fthumbnails%2F8cd67229c60240b1bfe21a33ca0db9d1%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>

## Small Weeder with Fins, no Center

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2Fecf7744a51724a5480c772e4177527ae%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2Fecf7744a51724a5480c772e4177527ae&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2Fecf7744a51724a5480c772e4177527ae%2Fdist%2Fthumbnails%2F43b69b0d4a804b40ad38626a06eb7eb8%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>

## Large Weeder with Fins, no Center

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fsketchfab.com%2Fmodels%2F5bbe511564d340d7b1dc6244756d6fe0%2Fembed&url=https%3A%2F%2Fsketchfab.com%2Fmodels%2F5bbe511564d340d7b1dc6244756d6fe0&image=https%3A%2F%2Fd35krx4ujqgbcr.cloudfront.net%2Furls%2F5bbe511564d340d7b1dc6244756d6fe0%2Fdist%2Fthumbnails%2Fa905f9e2375a46eb8b6015e637fc26ed%2F640x360.jpeg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=sketchfab" width="640" height="360" scrolling="no" frameborder="0" allowfullscreen></iframe>



# Assembly Instructions



{%
include callout.html
type="info"
title="15 minutes"
content="This is the estimated time it will take to assemble the weeder.."
%}

## Step 1: Gather the parts and tools
Gather all the weeding tool parts from the table below and lay them out in a logical manner. To complete the assembly, you will also need the following tools:
* 2mm hex (allen) driver
* 3mm hex (allen) driver
* 6mm wrench
* 8mm wrench
* Wire strippers

|Qty.                          |Component                     |
|------------------------------|------------------------------|
|1                             |Weeder Base
|2                             |M3 x 16mm Screws
|2                             |M3 Locknuts
|3                             |M5 x 25mm Screws
|3                             |M5 Locknuts
|3                             |15 x 15 x 5mm Ring Magnets
|1                             |18 guage x 5cm Jumper Wire
|2                             |Zipties

## Step 2: Install the Magnets

{%
include callout.html
type="info"
title="Opposites attract"
content="For the weeder to correctly mount to the UTM, all magnets on the weeder must be attracted to the magnets in the UTM.

To find the correct orientation for a magnet, hold it near the mounting side of the UTM. Flip it around in your hand until you feel it attracting to the UTM's magnets. This is the correct orientation for mounting to the weeder's plastic base."
%}

Secure the three **ring magnets** to the top of the **weeder base** using three **M5 x 25mm** screws and **M5 locknuts**. The screw head should be on the magnet side of the weed suppressor base. Use the **3mm hex driver** and **8mm wrench** to tighten the components.


## Step 3: Install the Electrical Screws
Use the **2mm hex driver** and **6mm wrench** to attach two **M3 x 16mm screws** and **M3 locknuts** into the holes labelled 2 and 3 on the **weeder base**. The screw heads should be on the same side of the base as the magnets.


## Step 4: Add the Jumper Wire
Use **wire strippers** to remove 1cm of insulation from both ends of the **jumper wire**.


Attach the **jumper wire** to the **M3 screws** using two **zipties**.




# Change Log

* Designed multiple variants for different soil conditions

# Room for Improvement

Nothing to see here!
