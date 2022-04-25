---
title: "Universal Tool Mount"
slug: "universal-tool-mount"
description: "Documentation and assembly instructions for the FarmBot Genesis Universal Tool Mount"
---

The Universal Tool Mount (UTM) allows FarmBot Genesis to automatically switch which tool is on the z-axis depending on the operation needing to be completed. The UTM is necessary because it is not feasible to have all tools mounted on the z-axis at one time for several reasons:

  * This would be very heavy and create more stresses on all components, as well as necessitate a larger z-axis motor.
  * Most tools need to be the “lowest” thing on the z-axis in order to work. Having multiple tools competing for the lowest position (ex: a temperature probe and a seed injector) would not be ideal and may not work at all. The use of individual tool raising and lowering mechanisms, or a turret style mechanism would be complex, heavy, bulky, and limited in the number of tools it could support.
  * The Z-Axis’s size must be kept to a minimum in order for it to have minimal impact on the plants, especially when there is not very much space between them.

The UTM is a single 3D printed component that mounts to the Z-Axis aluminum extrusion using two M5 screws and tee nuts.
It features:
* 3 strong neodymium ring magnets to magnetically hold tools in place via other magnets placed in the same configuration on the tool.
* Passage ways for water, liquid amendments (eg: fertilizer), and vacuum or compressed air to pass through from the UTM (and the rest of FarmBot) to the tool.
* 12 spring loaded screws that make electrical connections with tools. (See: [Pin Mapping](#pin-mapping))

<iframe width="100%" height="480" src="https://sketchfab.com/models/555a50936d5d4f6d835a3daf9fd48c95/embed?ui_controls=0&amp;ui_infos=0&amp;ui_related=0" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel=""></iframe>






{%
include callout.html
type="success"
title="Want to make your own UTM compatible tools?"
content="Check out the [tool spec](tools.md) to learn how to design and manufacture your own custom tools. We provide examples, CAD models, tech specs, and links to purchase parts."
%}



# Change Log

* Switched from low-profile M5 socket head screws to M5 button-head style screws. The new screws still have 3mm hex drives, but have a lower profile (2.75mm instead of 3.5mm) that provides better clearance between lower gantry v-wheel screws and track plates. They also have larger diameter heads (9.5mm from 8.5mm) that distribute loads more evenly and provide more secure connections, especially for the plastic components.
* Modified the UTM base so that the magnets lie closer to the tool for an increase in holding force. This modification was possible due to the switch to the lower-profile button head M5 screws.
* Made the UTM base significantly shorter and shortened the M5 and M3 screws that pass through it accordingly.
* Increased the height of the UTM cover to allow for the UTM wires to have more space.
* Moved the FarmBot logo from the UTM base to the UTM cover.
* Removed the o-ring groove on the UTM's liquid/gas ports and re-designed the ports to be injection mold-able.
* Switched from circular profile o-rings to square profile o-rings for more direct sealing of the liquid/gas ports and for compatibility with the new port design.

# Room for Improvement

Nothing to see here!
