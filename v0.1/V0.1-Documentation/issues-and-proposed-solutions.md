---
title: "Issues and Proposed Solutions"
slug: "issues-and-proposed-solutions"
---

* toc
{:toc}

Genesis V0.1 was an initial prototype utilizing all off-the-shelf components from [OpenBuilds](http://openbuildspartstore.com). For this reason, it was a very quick and easy starting point for hardware design, allowing us to learn as much as we could as fast as possible with minimal design and part manufacturing effort. However, it also had many flaws being the first prototype and using no custom parts. Read on to see what we learned and what design changes we want to implement in FarmBot Genesis V2

## Track Installation
When filled with dirt, this straight track became bowed outward at the joint of the extrusions.
Issue: The track pieces were secured to a wooden raised bed made of 2×4 posts at the corners and 0.75″ thick planks on the sides. The tracks were attached to the planks using 5 hole Tee brackets. These brackets held the track extrusions flush to the planks. Because of this, the planks (and therefore the raised bed itself) had to be very square, with each track side parallel to the other. This was somewhat difficult to get right, but not impossible with the use of shims and elbow grease.

Proposed Solution: A system that allows for more flexibility when attaching the tracks to supporting infrastructure would be beneficial.

## Track Joint Buckling
Issue: Track pieces were connected end to end to form a longer track. Pieces were connected using double long tee nuts. The tracks started out straight, but upon filling the raised bed with soil and then a subsequent rain, the wood planks pushed out, exposing the track joint as a weak spot. The two track pieces become unaligned at this “kink” which later became so bad the high precision wheel assemblies did not want to move past the kink.

Proposed Solution: A system that allows for a stronger connection where track pieces meet would prevent kinking and allow wheels and other components to travel across easier. Designing the system to be more forgiving (lower tolerance) may be beneficial as well.

## Track Orientation
Issue: The orientation of the tracks was such that the wheels had to be on the sides of the tracks. However, the force from the weight of the gantry is directly downwards.

Proposed Solution: A more optimized orientation of the tracks would be so that the wheels ride on the top of them rather than the sides.

## Belt Configuration
Issue: The belts used to move the gantry along the tracks and the cross-slide along the gantry are oriented such that they “double back” and span the entire length of the tracks or gantry twice. In addition, it is nearly impossible to feed the belt through the center of more than 4m of extrusions as in the case with the tracks.

Proposed Solution: A “belt and pinion” style system, similar to a rack and pinion would be much cheaper, easier to install, and easier to tension.

## Gantry Complexity at Track Interface
Issue: Each end of the gantry attached to the track with two “mini-v plates” with four “min-v wheels” each, making a total of 16 wheels attaching the gantry to the tracks. This was both expensive and a lot of work to assemble. In addition, the screws attaching the plates to the extrusions are not accessible without removing the gantry from the tracks.

Proposed Solution: A simplified system with less components and all screws accessible would be better.

## Corner Bracket Strength and Size
These brackets are weak and concentrate force in a small area. Their small size makes accessing the screws difficult.
Issue: The small corner brackets used concentrate forces onto the bracket corner and provide very little strength and rigidity with such large structures. In addition, the brackets are so small that getting tools and hands into the right position for tightening screws or bolts is difficult.

Proposed Solution: Larger brackets that do not concentrate forces into small corners would be better.

## Dual Track Motors That are Fixed
Issue: There are two motors that drive the gantry. They need to be synchronized or they may torque and break the gantry. In addition, because all other electrical components move with the gantry, it is difficult to have extra wires extend to the fixed track motors mounted at the ends of the tracks.

Proposed Solution: A single track motor mounted to the gantry driving both sides would be better.

## Extrusion Sizes
Issue: The use of different extrusion sizes adds unnecessary complexity and little optimization.

Proposed Solution: The use of a single size extrusion will be more simple.

## Cross-Slide Plates
Issue: The cross-slide needs a larger plate that is specialized to FarmBot’s needs rather than the universal plate from OpenBuilds.

Proposed Solution: Custom plates will be designed to accommodate.

## Eccentric Spacers and Number of Wheels
Issue: We currently use four wheels at each interface, two with eccentric spacers for fine adjustment of the wheel spacing. This is both expensive and unnecessary. Many 3D printers using these components use a three wheel arrangement, with the single wheel utilizing an eccentric spacer.

Proposed Solution: Implementing tri-wheel designs will reduce cost and complexity. In addition, it may be possible to remove all eccentric spaces with the use of slots for adjustment.

## Universal Tool Mount
Issue: The original design places all tools on the tool head at once. This is cumbersome, heavy, and limited by space.

Proposed Solution: A universal tool mounting system that makes a physical and electrical connection would be beneficial. A tool holder or bay would also be necessary to store the unused tooling.

## Location of Seed Bays
Issue: The original location of the seed bays was mounted to the gantry with a motor to allow the bot to select the type of seed. This is unnecessary as the bot can utilized its X and Y movement to select from seed bays within its working area, rather than having an extra actuator.

Proposed Solution: On large scale installations, the existing design may save travel time for the bot, but on a small scale system, because seeding does not happen often, a simpler design would be better. The seed bays may be mounted on the tool bay for increased modularity and one less required actuator.

## Standardization of Screws and Component Sizes
Issue: Utilizing as few different types of screws, washers, spacers, and other component sizes (extrusions included) will make installation and manufacturability easier.

Proposed Solution: Use as few types of components as possible, even if it is marginally less optimized.
