---
title: "Universal Tool Mount"
slug: "universal-tool-mount"
description: "Documentation for FarmBot Genesis V0.7 Universal Tool Mount"
---

The Universal Tool Mount (UTM) allows FarmBot Genesis to automatically switch tool is on the z-axis depending on the operation needing to be completed. The UTM is ncessary because it is not feasible to have all tools mounted on the z-axis at one time for several reasons:

  * This would be very heavy and create more stresses on all components, as well as necessitate a larger z-axis motor.
  * Most tools need to be the “lowest” thing on the z-axis in order to work. Having multiple tools competing for the lowest position (ex: a temperature probe and a seed injector) would not be ideal and may not work at all. The use of individual tool raising and lowering mechanisms, or a turret style mechanism would be complex, heavy, bulky, and limited in the number of tools it could support.
  * The Z-Axis’s size must be kept to a minimum in order for it to have minimal impact on the plants, especially when there is not very much space between them.
  * The UTM is a single 3D printed component that mounts to the Z-Axis aluminum extrusion using two M5 screws and tee nuts. It features 3 strong neodymium ring magnets to magnetically hold tools in place via washers or other magnets placed in the same configuration on the Tool. The magnets double as the keying system to ensure that tools are properly oriented in the UTM. The magnets also function as the passage ways for water, liquid amendments (eg: fertilizer), and vacuum or compressed air to pass through from the UTM (and the rest of FarmBot) to the Tool. In addition, the UTM has 4 spring loaded screws that make electrical connections with Tools. Two are for power (GND and +5V), and two are for data (0 to +5V).

## Universal Tool Mount Change Log
  * Electrical connections are now separated from the screws that hold the magnets in
  * There are now 12 spring loaded electrical connections
  * There is a single, central magnet
  * There are now six liquid/gas lines
  * The only points of contact between the UTM and a tool are now the o-rings and the electrical connections. Because the electrical connections are spring loaded, the o-rings are the component mechanically mating with the tool, allowing them to be maximally compressed and sealed.

## Photos

{% include gallery.html images="
![IMG_0098.JPG](_images/IMG_0098.JPG)
![IMG_0096.JPG](_images/IMG_0096.JPG)
" %}

## Pin Mapping

|UTM Pin                       |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|A                             |Ground (0V) on Arduino/RAMPS  |Ground
|B                             |+5V on Arduino/RAMPS          |Tool Verification
|C                             |Pin D16 on Arduino/RAMPS - Digital-In|Tool Verification
|D                             |Pin D17 on Arduino/RAMPS - Digital I/O|Data tool functions such as servo control or sensor reading
|E                             |Pin D23 on Arduino/RAMPS - Digital I/O|Data tool functions such as servo control or sensor reading
|F                             |Pin D8 on Arduino/RAMPS - High power output|High power tool functions such as motors or lasers
|G                             |Pin 20 on Arduino/RAMPS - I2C data (SDA)|Complex tooling requiring addressing of commands
|H                             |Pin 21 on Arduino/RAMPS - I2C clock (SCL)|Complex tooling requiring addressing of commands
|I                             |USB VCC (+5V)                 |USB based tools
|J                             |USB D- (Data -)               |USB based tools
|K                             |USB D+ (Data +)               |USB based tools
|L                             |USB Ground (0V)               |USB based tools


## Universal Tool Mount Issues and Proposed Solutions
  * Using the single centralized magnet is not provide enough magnetic pull force. Heavier tools cannot be used with this design. V0.8 will transition back to using a three magnet design.
  * Six liquid/gas lines is too many. It would be very unlikely to use more than one line for water, one line for compressed/vacuum air, and one line for liquid amendments. V0.8 will reduce the lumber of liquid/gas lines to three.
  * Six liquid/gas lines require six o-rings. With the lower pull force from the single magnet, and a higher number of o-rings for the force to be distributed over, none of the o-rings became sufficiently compressed to make a reliable seal with the tool. V0.8's three liquid/gas lines and transition back to a triple magnet design should remedy the o-ring sealing issue.
