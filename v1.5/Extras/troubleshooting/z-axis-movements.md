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

{%
include callout.html
type="warning"
title="Do not lubricate belts and pulleys"
content="In case you are reading this document and also have issues with movements on the X or Y axes, do not take this piece of advice (\"Lubricate the leadscrew\") and apply it to the belt-driven axes. Applying a lubricant to the belts may cause a chemical reaction that rapidly degrades the belt material. Furthermore, a lubricant between the belts and pulleys may cause the teeth engagement to slip."
%}

# 4. Adjust the stepper driver to deliver more power
For Genesis v1.5+ kits, increase the z-axis **[MOTOR CURRENT](https://my.farm.bot/app/designer/settings?highlight=motor_current)** by 100 or 200 milliamps. For v1.4 kits and below, you can adjust the **z-axis stepper driver** to deliver more power to the **z-axis motor** using the instructions at the bottom of [this post](https://forum.farmbot.org/t/why-is-my-farmbot-not-moving/2093).
