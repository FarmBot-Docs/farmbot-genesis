---
title: "Z-Axis Movements"
slug: "z-axis-movements"
description: "The z-axis frequently stalls when moving upwards. Movements may fail to complete, and in some cases the z-axis may even stall and then begin moving in the opposite direction."
---

* toc
{:toc}

# 1. Adjust the z-axis speed and acceleration

Try lowering the z-axis **[MAX SPEED](https://my.farm.bot/app/designer/settings?highlight=max_speed)** and **[ACCELERATE FOR](https://my.farm.bot/app/designer/settings?highlight=accelerate_for)** a longer distance. You may try halving the default max speed and doubling the default acceleration distance as a starting point, but because every FarmBot installation is a bit different, you will need to experiment to find the best values for you.

# 2. Check the z-axis eccentric spacers

Check the **eccentric spacers** on the **cross-slide** that are used to adjust the **v-wheels** that support the **z-axis extrusion**. If the eccentric spacers are adjusted too tightly, then they will exert too much force onto the z-axis extrusion which can make it difficult or impossible for the z-axis motor to raise the z-axis. With the FarmBot powered off, you should be able to rotate the leadscrew by hand without too much effort. If the eccentric spacers are too tight, this will be very difficult to do.

# 3. Lubricate the leadscrew

It is possible that dust and debris can build up on the **leadscrew** causing additional friction between the leadscrew and the **leadscrew block**. Clean the leadscrew with a rag and then add some lubricant which can be purchased from a local hardware store.

We recommend using a dry graphite lubricant spray which will coat the surface with a fast drying coating of graphite to create a slippery surface that reduces the resistance of movement through the leadscrew block and also may decrease any noise from the leadscrew.

We have found a product called [Jig-a-Loo Graphite Lubricant](https://www.amazon.com/dp/B08285N7LG/) that can help reduce friction on the FarmBot Z-axis leadscrew. Here is a [YouTube video](https://youtu.be/lyZ465jdO2Y) that shows how the product is used and the typical applications.

Apply enough graphite lubricant so that the hue of the screw looks significantly darker than the original silver metallic color. You should use enough graphite lubricant so that the screw should appear black or dark grey. This will allow the screw to operate without friction and vibrations. Please apply the graphite lubricant to the bottom 90% of the lead screw leaving the very top 10% unlubricated so that a sturdy grip can be applied to leadscrew by the coupler.

{%
include callout.html
type="warning"
title="Do not use oil, silicon, or lithium based lubricants"
content="These types of lubricants will attract dust and gum up causing poor performance. Only graphite lubricants are acceptable."
%}

{%
include callout.html
type="warning"
title="Do not lubricate belts and pulleys"
content="In case you are reading this document and also have issues with movements on the X or Y axes, do not take this piece of advice (\"Lubricate the leadscrew\") and apply it to the belt-driven axes. Applying a lubricant to the belts may cause a chemical reaction that rapidly degrades the belt material. Furthermore, a lubricant between the belts and pulleys may cause the teeth engagement to slip."
%}

# 4. Adjust the stepper driver to deliver more power

For Genesis v1.5+ kits, increase the z-axis **[MOTOR CURRENT](https://my.farm.bot/app/designer/settings?highlight=motor_current)** by 100 or 200 milliamps. For v1.4 kits and below, you can adjust the **z-axis stepper driver** to deliver more power to the **z-axis motor** using the instructions at the bottom of [this post](https://forum.farmbot.org/t/why-is-my-farmbot-not-moving/2093).
