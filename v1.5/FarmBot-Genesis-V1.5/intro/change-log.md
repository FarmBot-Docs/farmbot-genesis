---
title: "Change Log"
slug: "change-log"
excerpt: "All of the changes we made to FarmBot Genesis since the last version"
---

* toc
{:toc}

# FarmBot Genesis MAX
The most notable change from v1.4 is that v1.5 devices are now available in the FarmBot Genesis MAX size, covering an area 3m wide and 18m in length (3x larger than XL and 12x larger than the smallest size). The additional hardware needed for the MAX version includes more track extrusions and track joining plates, a longer power cable, water tube, belts, and cable carrier, and additional screws, tee nuts, and dowel pins.

{%
include callout.html
type="info"
title="May 18, 2020 Update"
content="Due to low demand, [FarmBot Genesis MAX has been cancelled](https://farm.bot/blogs/news/putting-farmbot-genesis-max-and-express-max-on-hold) and will not be manufactured. While the documentation for it will remain, we will not be providing support for that product."
%}

# Farmduino
The v1.5 kits include a new revision to our custom electronics board, the Farmduino. The board now features integrated Trinamic TMC2130 stepper drivers that are controlled with a SPI interface. These new drivers can deliver more current to the motors, offer significantly quieter operation, and can be tuned via software instead of DIP switches and screws. The new board also adds load detection circuitry to all of the peripherals, which can be used to detect peripheral disconnection, malfunction, and performance.

# Modularized cables and tubing
In the v1.5 update we were able to modularize almost all of the cable and tubing connections at the junction between the y-axis cable carrier and the z-axis cable carrier. The water tube has been split in half and now includes a 90 degree barb. Meanwhile, the z-axis motor and encoder cables, camera cable, and vacuum pump cable have all also been split into y-axis and z-axis sections, and get joined together by 90-degree waterproof screw-together connectors. This makes assembly and disassembly of the FarmBot much easier, because these cables and tubes are not one continuous component running through so much cable carrier. The final remaining cable that needs to be modularized is the UTM cable, which we hope to do in a future version of Genesis.

# Nut bars and flange locknuts
Genesis v1.5 features new stainless steel M5 flange locknuts that replace the functionality of the locknuts + washers from past versions. Combining these parts into one makes assembly faster and easier and reduces the overall part count. Additionally, v1.5 foregoes many drop-in style tee nuts in favor of stainless steel nut bars. Each nut bar replaces two to three individual tee nuts, lending to a faster assembly process and providing a more robust joint with the extrusion. The nut bars also do not suffer from the primary failure mode of drop-in tee nuts, which can fail to rotate in the slot and grip the extrusion. Many of the plate hole layouts were simplified to accommodate nut bars, also reducing overall part count.

# Improved peripheral mounts
The vacuum pump mount is now an injection molded plastic component which helps absorb motor vibrations, reduces cost, and makes the z-axis lighter weight. Meanwhile, the solenoid valve is now mounted to a plastic injection molded part that combines the functionality of the mount and the cable guides.

# Smaller x-axis cable carrier
The x-axis cable carrier has been reduced in size to have a 15mm x 30mm internal size. This saves significant weight and reduces friction when moving in the X direction. The horizontal cable carrier supports and mounts have been modified as well to accommodate the smaller carrier, adding to overall material, weight, and cost reductions in the kit.

# Pi adapter board
The new Pi Adapter Board features a real-time clock, allowing FarmBot to accurately keep track of time in the absence of a network connection. This greatly improves the performance of offline/off-grid FarmBot operation.

# Soil sensor
The new soil sensor PCB features the same soil moisture sensing capabilities, but adds soil temperature sensing as well. This measurement is read using an I2C interface. The new PCB has a matte-black finish, and is 100% open-source.

# Miscellaneous
* Extrusions are now sandblasted before being clear anodized.
* Included a new sticker pack.
* Added an inline air filter to the vacuum pump tube to help prevent clogging.
* Switched to a stainless steel, M5 threaded luer lock adapter.
* Solenoid Valve electrical tabs now face the inlet side for cleaner wire routing.
* The kit now includes a camera calibration card instead of objects.
* Improved the z-axis motor mount to include a recessed lip for better mating with the vertical motor housing.
* Combined the garden hose adapter and barbed adapter into one component.
* The motors are now packed independently of the cables, allowing the same motor kit to be used in all three sizes of Genesis.
