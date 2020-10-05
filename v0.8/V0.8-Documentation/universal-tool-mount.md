---
title: "Universal Tool Mount"
slug: "universal-tool-mount"
description: "Documentation for FarmBot Genesis V0.8 Universal Tool Mount"
---

* toc
{:toc}

The Universal Tool Mount (UTM) allows FarmBot Genesis to automatically switch tool is on the z-axis depending on the operation needing to be completed. The UTM is ncessary because it is not feasible to have all tools mounted on the z-axis at one time for several reasons:

  * This would be very heavy and create more stresses on all components, as well as necessitate a larger z-axis motor.
  * Most tools need to be the “lowest” thing on the z-axis in order to work. Having multiple tools competing for the lowest position (ex: a temperature probe and a seed injector) would not be ideal and may not work at all. The use of individual tool raising and lowering mechanisms, or a turret style mechanism would be complex, heavy, bulky, and limited in the number of tools it could support.
  * The Z-Axis’s size must be kept to a minimum in order for it to have minimal impact on the plants, especially when there is not very much space between them.
  * The UTM is a single 3D printed component that mounts to the Z-Axis aluminum extrusion using two M5 screws and tee nuts. It features 3 strong neodymium ring magnets to magnetically hold tools in place via washers or other magnets placed in the same configuration on the Tool. The magnets double as the keying system to ensure that tools are properly oriented in the UTM. The magnets also function as the passage ways for water, liquid amendments (eg: fertilizer), and vacuum or compressed air to pass through from the UTM (and the rest of FarmBot) to the Tool. In addition, the UTM has 4 spring loaded screws that make electrical connections with Tools. Two are for power (GND and +5V), and two are for data (0 to +5V).

## Change Log
  * Reverted back to the three magnet design
  * Moved down from six liquid/gas lines to three so that each o-ring makes a better seal
  * Slightly enlarged to accommodate the three magnet design
  * Designed a 3D printable rain cover for the UTM
  * Switched from straight ring terminals to flag terminals to save space on the electrical connections

# Photos






# Pin Mapping



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



# Bill of Materials



|Part Name                     |Description                   |Source                        |$/unit                        |Qty.                          |Subtotal                      |
|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|
|M5x12mm Screws                |Stainless, 0.8 thread pitch, low-profile 3mm hex heads|[McMaster Carr](http://mcmaster.com)|$0.18                         |2                             |$0.36
|Tee Nuts                      |Stainless steel, for attaching M5 screws to OpenBuilds aluminum extrusions|                              |$0.30                         |2                             |$0.60
|Universal Tool Mount          |3D printed                    |[Shapeways](http://shapeways.com)|$56.15                        |1                             |$56.15
|Springs                       |Metric Compression Spring, Stainless Steel, 9.4 mm Overall, 5.5 mm OD, .50 mm Wire|[Amazon](http://www.amazon.com/Compression-Spring-Stainless-Compressed-Capacity/dp/B005S4HP6K/ref=sr_1_7?s=industrial&ie=UTF8&qid=1437506716&sr=1-7&keywords=spring&refinements=p_n_feature_eleven_browse-bin%3A3622111011%2Cp_n_feature_seven_browse-bin%3A5485702011)|$1.21                         |12                            |$14.52
|M3 Locknuts                   |Stainless steel, .5MM Pitch, nylon insert|[McMaster Carr](http://mcmaster.com)|$0.04                         |24                            |$0.96
|M3 Flag Ring Terminals        |Noninsulated, 22-18 AWG Wire Size, #6 Screw/Stud|[McMaster Carr](http://mcmaster.com)|$0.12                         |12                            |$1.44
|Cable                         |Continuous-Flex Cable Unshielded, 20 Gauge, 12 Wires, 300V AC, 10 ft. Length|[McMaster Carr](http://mcmaster.com)|$19.20                        |1                             |$19.20
|Barbs                         |Miniature Stainless Steel Barbed Tube Fitting, Straight for 1/4" Tube ID X 10-32 UNF Male Pipe|[McMaster Carr](http://mcmaster.com)|$5.60                         |3                             |$16.80
|O-rings                       |Multipurpose Chemical-Resistant O-Ring, Viton(R) Fluoroelastomer, 1.5MM Wide, 7MM ID|[McMaster Carr](http://mcmaster.com)|$0.23                         |3                             |$0.69
|Ring Magnets                  |15mm OD x 5mm ID x 5mm thick  |[Apex Magnets](http://www.apexmagnets.com/magnets/rings)|$1.69                         |3                             |$5.07
|M5 x 30mm Screws              |Stainless steel type 316, 0.8 thread pitch, low-profile 3mm hex heads|[McMaster Carr](http://mcmaster.com)|$0.37                         |3                             |$1.11
|M5 Locknuts                   |Stainless steel with nylon insert, 0.8mm thread pitch|[McMaster Carr](http://mcmaster.com)|$0.08                         |3                             |$0.24
|                              |                              |                              |                              |Total                         |$119.18



{%
include callout.html
type="success"
title="We sell parts too"
content="Make sure to check out our [FarmBot Shop](http://go.farmbot.it/shop/) to purchase premium quality components that you can be sure will work with your hardware."
%}



# Issues and Proposed Solutions

  * Using the single centralized magnet is not provide enough magnetic pull force. Heavier tools cannot be used with this design. V0.8 will transition back to using a three magnet design.
  * Six liquid/gas lines is too many. It would be very unlikely to use more than one line for water, one line for compressed/vacuum air, and one line for liquid amendments. V0.8 will reduce the lumber of liquid/gas lines to three.
  * Six liquid/gas lines require six o-rings. With the lower pull force from the single magnet, and a higher number of o-rings for the force to be distributed over, none of the o-rings became sufficiently compressed to make a reliable seal with the tool. V0.8's three liquid/gas lines and transition back to a triple magnet design should remedy the o-ring sealing issue.
