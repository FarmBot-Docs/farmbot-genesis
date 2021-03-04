---
title: "Seed Injector"
slug: "seed-injector"
description: "Documentation for the FarmBot Genesis seed injector"
---

* toc
{:toc}

The seed injector works by using a vacuum pump to suction-hold a single seed at the end of a needle.

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FnXFdJIQaQB4%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DnXFdJIQaQB4&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FnXFdJIQaQB4%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

![seeder](_images/seeder.png)

# Step 1: Install the basic tool hardware

Install the **magnets** and tool verification **jumper link** using the instructions in the [basic tool hardware reference guide](../../extras/reference/basic-tool-hardware.md).

![seeder with basic tool hardware](_images/seeder_with_basic_tool_hardware.png)

# Step 2: Add the luer lock adapter

Screw the **luer lock adapter** into the brass insert on the bottom of the **seeder**.

![seeder with luer lock adapter](_images/seeder_with_luer_lock_adapter.png)

# Step 3: Selecting a luer lock needle

We've shipped all of the FarmBots with three different **luer lock needle** sizes so that you can experiment and find the best needle for your needs.

|Size                          |Gauge                         |Inner Diameter                |Good for                      |
|------------------------------|------------------------------|------------------------------|------------------------------|
|Large                         |14                            |1.72mm (0.067")               |Large seeds (eg: pumpkin)
|Medium                        |19                            |0.83mm (0.032")               |Most seeds
|Small                         |22                            |0.48mm (0.019")               |Small seeds (eg: lettuce)

Once you've selected a needle, attach it to the **luer lock adapter** with a 1/4 turn. At any time you can quickly swap the needle out for another size or replace a damaged one.

![seeder with needle](_images/seeder_with_needle.png)

# Step 4: Connect the vacuum tubes and filter

{%
include callout.html
type="info"
content="For the next two steps, it can be helpful to temporarily unscrew the **vacuum pump mount** from the **z-axis extrusion** and slide it (and the vacuum pump) out from the housing."
%}

Slide one of the **vacuum tubes** onto the _inlet barb_ of the **vacuum pump**. The inlet will be marked with an arrow pointing into the pump. The inlet may be on the left or the right side of the pump depending on when your kit was purchased. Please refer to the arrows on your pump to ensure the tube is connected correctly.

Then slide the **inline air filter** onto the end of the first tube and connect the second vacuum tube between the air filter and the **barb** on top of the **UTM** closest to the FarmBot logo.

{% include gallery.html images="
![Connect the first vacuum pump tube](_images/vacuum_tube_1.png)
![Connect the inline air filter](_images/air_filter.png)
![Connect the second vacuum tube](_images/vacuum_tube_2.png)
" %}

{%
include callout.html
type="info"
title="Is your seeder blowing?"
content="If you find during testing that there is air blowing out of the seeder tool, you may try connecting the tube to the other port. We use parts from different suppliers and the vacuum pump configuration may be different on your model."
%}

# Step 5: Wire up the vacuum pump

Connect the **vacuum pump cable** to the **vacuum pump's** terminals. While the cable has red/black wires, the vacuum pump has no polarity. Thus, you can connect the red/black wires to either terminal without changing the operation of the pump. In a few steps from now, you will connect the other end of the cable to the Farmduino.

![Wire up the vacuum pump](_images/wire_up_vacuum_pump.png)

# Step 6: Attach the seed trough holder

Attach the **seed trough holder** to the **seed trough holder mount plate** using two **M5 x 30mm screws** and **M5 flange locknuts**. Then mount the assembly to the **left gantry column** using a **40mm nut bar** and two **M5 x 10mm screws**. 

Place the two **seed troughs** into the holder. Optionally, you may store up to three **luer lock needles** in the holder as well.

{% include gallery.html images="
![Attach the seed trough holder to the mount](_images/seed_trough_mount_plate.png)
![Mounted seed trough holder](_images/mounted_seed_trough_holder.png)
" %}

# Step 7: Understanding the seed containers

<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FguJK9498ZA4%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DguJK9498ZA4&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FguJK9498ZA4%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

We offer the following types of seed containers, each optimized for different purposes.

## Seed bins
The **seed bins** are for holding large amounts of one type of seed. This is best used when planting many plants of the same crop, for example: when growing microgreens. To use a seed bin, simply slide it into the **toolbay** and fill it with seeds. Then run a planting sequence from the web app with the corresponding seed bin sequence and location.

![seed bin](_images/seed_bin.jpg)

If desired, you can mix a variety of seed types into one seed bin and have FarmBot plant whatever it happens to grab. Keep in mind though that FarmBot will have no way of knowing which seeds it grabs, so only use this technique when you will be taking care of all those plants identically. An example for this again might be when growing microgreens - you can grow three different types in the same area at the same time, all in the same way, without having to do three planting sequences or otherwise treat them differently.

## Seed trays

The **seed trays** have 16 small area for holding seeds. They are best used when planting many different crops, and when the number of seeds per hole needs to be strictly controlled.

![seed trays](_images/seed_trays.jpg)

## Seed troughs

The **seed troughs** are small seed containers that are stored in the **seed trough holder**, which is mounted on the gantry. This allows FarmBot to bring seeds with it along the x-axis, reducing the time to sow an entire bed.

![seed troughs](_images/seed_troughs.jpeg)

# What's next?

 * [Watering Nozzle](watering-nozzle.md)
