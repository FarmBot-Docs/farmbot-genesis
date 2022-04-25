---
title: "Change Log"
slug: "change-log"
description: "All of the changes we made to FarmBot Genesis since the last version"
---

# Plastic Parts
With v1.3 we built many more injection mold tools that allow us to manufacture plastic parts more quickly, at a lower cost, and at a higher quality than machining. The new injection molded parts include:
* Horizontal Cable Carrier Supports
* Vertical Cable Carrier Supports (reduced quantity to 4)
* Vacuum Pump Cover
* Cable Carrier Spacer Block
* Seeder
* Weeder
* Weeder Implements
* Watering Nozzle Top and Bottom
* Soil Sensor
* Seed Tray
* Camera Mounts

# Watering Nozzle
In addition to being injection molded, the watering nozzle top and bottom now feature a key, which makes aligning the top and bottom pieces very easy.

# Farmduino
The Farmduino is our very first electronics board. It largely mimics the functionality of the Arduino MEGA + RAMPS shield, but features a board layout and connectors that are optimized for FarmBot. Specifically, Farmduino has the following:
* Tab-locking, polarized encoder connectors that allow each encoder to be quickly connected in one go (backwards compatible with v1.2 encoder cables)
* Tab-locking, polarized motor connectors (backwards compatible with v1.2 motor cables)
* Replaced microstepping jumper pins with dip switches
* Pre-mounted and tested stepper drivers
* USB power output to the Raspberry Pi
* Single UTM connector with 0.1" (2.54mm) breakout headers
* Replaceable blade fuse
* Five polarized, easy-to-use peripheral connectors with high powered mosfets
* Polarized 2-channel power input connector
* 100% open-source

# Electronics Box
With v1.3 we designed and injection molded custom electronics boxes.
* Additional space inside the box makes working with the electronics and inserting/removing the microSD card much easier.
* Two latches make opening and closing the box effortless and quick.
* With the supergland, the box is better sealed against moisture, dust, and insects. The cables are also neatly organized.

# Cables
With the switch from RAMPS to Farmduino, we had the opportunity to select better quality connectors on many of the cables to make installation faster, easier, and more robust. The following cables have new connectors on the end that connects to the Farmduino:
* Solenoid Valve Cable
* Vacuum Pump Cable
* Power Supply Cable
* UTM Cable
* Encoder Cables (v1.2 is backwards compatible)
* Motor Cables (v1.2 is backwards compatible)

The motor and encoder cables now have labels on the Farmduino ends for easy identification.

# UTM cable
Features a new, single connector on the Farmduino end to make installation fast and easy. The UTM cable's internal wires are now color coded, which makes installation on the UTM end easier as well.

# Cable Carriers
The v1.3 cable carriers are now 10mm wider to make inserting and managing cables easier, and to provide additional room for FarmBot modifications/expansion by the user. This change required many other components such as the cross-slide and cable carrier supports to be modified.

The X and Y cable carriers are now the same length (85 links + end pieces). And the z-axis cable carrier is now 5 links shorter so that it fits better.

# Vacuum Pump
The vacuum pump has been moved to the z-axis extrusion. This allows the tube to the UTM to be shortened to just 0.4m, which allows for significantly greater suction at the seeder needle. Moving the pump to this location required the addition of an aluminum mounting bracket and plastic cover, as well as changing the length of the vacuum pump cable.

# Z-Axis Motor Mount and Cover
With the change to the wider cable carriers, we also needed to make the z-axis motor mount and cover larger. There is also now additional headroom in the motor cover to accommodate other encoders.

# Z-Axis Hardstops
These new small plates provide a more solid hard stop to the z-axis (instead of just the M5 screws and tee nuts).

# LED Strip
We included a 1.5m weatherized white LED strip with all v1.3 kits. The strip can be positioned along the gantry in the horizontal cable carrier supports.

# Power Supply
The new power supply is a 12V, 12.5A (150W) IP67 rated waterproof power supply. This allows it to be mounted outside without needing the additional rain-proof Sockit box. The power supply also features a universal voltage input.

# Weeder Implements
* We removed the weeder spike and replaced it with a narrow version of the weeder blade.
* A wide weeder blade size was added.
* Four of each sized blade have been included with each kit.
* The new blades are injection molded out of gray UV resistant plastic, and feature M3 threaded brass inserts for more secure attachment to the weeder base.

# Packaging
* The most prominent improvement to the kit packaging with v1.3 is that the FarmBot Genesis main carton has been packed more efficiently, allowing us to reduce its volume by 40%. The extrusion and leadscrew kit box has also been made slightly smaller. These optimizations eliminated the need for any expanded polystyrene foam. Instead, we are using exclusively recycled kraft paper to fill any small voids and to provide additional protection to the parts.
* Internal boxes have been made with thicker, stronger cardboard, and they are now of the single-top-flap style for convenience.
* The main carton now includes four edge protectors and black poly strapping for added protection.
* The plastic components are now separated from the metal components to avoid damage.
* The leadscrew has been placed inside a PVC tube for greater protection.
* The extrusions and leadscrew kit box has additional cardboard pieces on the inside ends to add further protection.

# Miscellaneaous
* We added a new sticker pack to each kit.
* The 8mm wrench is now a small, thin wrench that allows it to be used more effectively when adjusting eccentric spacers.
* The belt lengths are more appropriately​ sized.
* The gantry corner brackets and toolbays now feature small notches to help with vertical alignment (just like the track plates and gantry wheel plates).

# What's next?

 * [Assembly Preparation](assembly-preparation.md)
