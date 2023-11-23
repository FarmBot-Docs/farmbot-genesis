---
title: "Tool Spec"
slug: "tool-spec"
description: "Design and build your own tools for FarmBot"
---

Want to design and make your own tools for FarmBot? Follow these instructions to ensure compatibility with the universal tool mount (UTM), a toolbay, and your FarmBot's electronics.

![3d printing a tool](_images/3d_printing_a_tool.jpg)

{%
include callout.html
type="lightbulb-o"
title="Unlimited possibilities"
content="The following recommendations should be followed to ensure your tool works with a stock FarmBot. However, don't shy away from experimentation and the possibility of modifying your UTM, toolbay, or electronics to accommodate your desired tool design. FarmBot is yours to play with and modify!"
%}

# Hardware

Design your tools to meet these hardware specifications to ensure compatibility with FarmBot. Additionally you will need to design your tool so that it can be produced with the equipment, processes, and materials availabe to you, as well as stand up to the outdoor environment and other expected stresses.

|                      |                  |
|----------------------|------------------|
|**Base**              |3D printed plastic
|**Magnets**           |Three 15 x 5 x 5 mm [[standard magnets]] secured with M5 screws and locknuts
|**Tool verification** |[[Jumper link]] secured with M3 screws and locknuts
|**Total weight**      |0.5 kg or less
|**Overall height**    |200 mm or less
|**Overall diameter**  |100 mm or less

Tools must have the correct physical dimensions and component layout on the top face so that they can correctly couple and de-couple with the [[UTM]] as well as slide in and out of a [[toolbay]].

{%
include callout.html
type="success"
title="Start with a CAD model"
content="[Download or copy the CAD model](../cad.md) of an existing tool as a starting point for your own design."
%}

# Electrical

In addition to tool verification, tools can make other electrical connections with components in the electronics box via the [[UTM]]. See [UTM pin mapping](../reference/utm-pin-mapping.md) for existing and available connections.

{%
include callout.html
type="warning"
title="At your own risk"
content="Building your own tools that utilize the electrical contacts of the UTM could result in damage if improperly designed. Proceed at your own risk. If you would like help building custom tools, consider posting in the [community forum](http://forum.farmbot.org)."
%}

# Example projects

Below are some example projects from university teams that have developed their own FarmBot tools.

## Weed trimmer tool

A senior design team at the Liberty University School of Engineering partnered with FarmBot Inc to design and prototype a weed trimming tool.

{% include youtube.html id="nfteqo_ALzo" %}

{%
include callout.html
type="success"
content="This project was further developed by FarmBot Inc and commercialized in Genesis v1.6 with the introduction of the [rotary tool](../../assembly/tools.md#rotary-tool)."
%}

## Gripper tool

An interdisciplinary team of students at Curio, a vocational school in the Netherlands, have developed a prototype FarmBot gripper tool for harvesting crops.

{% include youtube.html id="zcnqI28tzAg" %}

## Seeder pod tool

A senior design team at the Liberty University School of Engineering partnered with FarmBot Inc to design and prototype a seeder pod tool.

{% include youtube.html id="URjMCEnDowc" %}


# What's next?

 * [Review Included Tools](../../assembly/tools.md)
 * [Included Tool Assembly](../../manufacturing/pre-assembly/tools.md)
 * [Basic Tool Hardware](../reference/basic-tool-hardware.md)
