---
title: "Seeds"
slug: "seeds"
description: "Tips for selecting seeds to use with FarmBot"
---

There are three main considerations when choosing what to plant with FarmBot:
1. [Plant size and shape](#plant-size-and-shape)
2. [Crop requirements](#crop-requirements)
3. [Seed size](#seed-size)

# Plant size and shape



{%
include callout.html
type="success"
title="The optimal choice"
content="The most optimal crops for FarmBot are small to medium in size and grow in a relatively predictable shape. For example: Kale, Spinach, Lettuce, Arugula, Chard, Beets, and Bok Choy."
%}



{%
include callout.html
type="warning"
title="Tall crops and FarmBot's gantry don't mix"
content="Tall crops such as Corn or Sunflowers that will grow to exceed the ~0.5m height of the gantry are not recommended to be grown in the main space of the FarmBot's raised bed. Such crops may prevent FarmBot from moving, or the FarmBot may destroy the plants once they are too tall.

You _can_ grow tall crops at the very ends of the bed, where they will not prevent the Gantry from moving. Or, they may be planted nearby the FarmBot and taken care of with additional peripherals. For example, an extra solenoid valve could be used to control a drip irrigation system next to the bed. For more ideas see [Mods and Add-Ons](../mods.md)."
%}



{%
include callout.html
type="warning"
title="Use caution with indeterminate crops"
content="Crops that grow in an indeterminate fashion such as Watermelon or Pumpkin may cause interference with FarmBot's movements because the plants may grow in unexpected directions or fruit in unexpected locations. Indeterminate crops may also cause issues with weed detection, with the potential to significantly hinder performance or create false detections. Vining plants such as Tomatoes may grow to interfere with FarmBot's tracks and gantry system, causing a hardware jam.

You _can_ grow indeterminate crops at the very ends of the bed, where they can be trained (by hand) to grow out and away from the FarmBot's mechanical systems."
%}



# Crop requirements

As with all methods of growing, you will need to choose crops that are well suited for your geographic location, FarmBot location, soil conditions, and the time of year. Specific things to consider include:

* Sun requirements (full sun, partial sun, etc)
* Optimal soil properties (well draining, high carrying capacity, etc)
* Minimum and maximum temperatures
* Threat of frost, high winds, birds, harmful insects, etc
* Planting depth
* Recommended planting season
* Transplanting/thinning needs

{%
include callout.html
type="success"
title="Tap into local knowledge"
content="We recommend visiting your local nursery, hardware store, or gardening club and talking to an expert for your area. They will be able to recommend crops based on your conditions. If there are no experts available, use the information on the back of the seed packets and get ready to experiment!"
%}



# Seed size

## Planting with FarmBot

The seeder uses a luer lock needle implement design, so different needle diameters can be used for different sizes of seed. Lettuces, Kale, and Chard seeds will all work fine. Extremely small seeds have the possibility of being sucked into the vacuum system, while very large/heavy seeds may be difficult to pick up. Remember that FarmBot can only plant seeds, so starter plants and bulbs can only be used if planted [manually](#manual-planting).

## Pelleted seeds
Many seeds are very small, lightweight, and/or irregularly shaped. Seeds of this nature can be difficult for FarmBot to work with:

* Too many seeds may get sucked onto the needle at once.
* Seeds may get sucked through the needle and clog the vacuum pump.
* Irregular seed surfaces may prevent reliable suction holding power.

If you encounter problems with the seeds you want to use, we recommend purchasing **pelleted seeds**. Pelleted seeds are seeds coated with a biodegradable material that ensures they are of a uniform size and shape (usually a sphere). Pelleted seeds are specifically designed for use with farming equipment because they are easier and more reliable for machines to work with. When using pelleted seeds with FarmBot, your FarmBot will be able to more reliably pick up one seed at a time and place it in its intended location.

There are many online suppliers of pelleted seeds, such as [Johnny's Seeds](https://www.johnnyseeds.com/featured/pelleted-seeds/) and [High Mowing Seeds](https://www.highmowingseeds.com/pelleted-seed-varieties.html). You may also be able to find pelleted seeds locally.

## Manual planting

If a seed won't work with any size of luer lock seeder needle, you can still grow it with FarmBot. Examples include tubers, bulbs, or very small seeds like those of an Orchid.

For manual planting, we recommend first adding the plants to your Farm Design in the web app. Then, you can instruct FarmBot to move to each plant location and either point or poke a hole in the ground where the plant should be. Then you can either drop some seeds in the hole, or dig and plant a bulb.

{%
include callout.html
type="success"
title="Share your experience"
content="Tried out a new crop? Share how things went on the [community forum](http://forum.farmbot.org)!"
%}

