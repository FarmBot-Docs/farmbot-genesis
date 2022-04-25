---
title: "Maintenance Guide"
slug: "maintenance"
description: "Use these techniques to keep your FarmBot running smooth for years to come"
---

In this section we'll go over maintenance tips and techniques that can keep your FarmBot operating like the day you installed it.

# General

## Keep FarmBot clean

FarmBot is a farmer that works and lives all day and night outside with the rain, sun, bugs, birds, and dirt. At the same time, FarmBot is a precision CNC machine with a lot of parts that allow it to move with millimeter accuracy to grow your food. Most would say these things can't co-exist. But they can with regular cleaning of your device.

{%
include callout.html
type="success"
title="FarmBot enjoys a good sponge bath"
content="Every three months, use a brush, sponge, broom, and a little water to clean off your FarmBot. Remove built up bird poop, mud, spider webs, and other debris. Clean out the hard to reach places, cut its nails, and treat it to a massage. Your FarmBot will appreciate your loving care and pay you back with years of vegetables."
%}

## Tighten loose screws

Every three months, inspect your hardware for loose screws. You can do this by grabbing a component such as an extrusion and attempting to wiggle it with a small amount of force. If you can feel or hear anything rattling, a screw somewhere needs to be tightened. Use the appropriate wrench to tighten any screws that you find to be loose.

{%
include callout.html
type="info"
title="Why are my screws loose?"
content="Under normal operating circumstance, your screws can become loose from vibrations, thermal expansion and contraction, rain, and even high winds. If a particular screw becomes loose multiple times in a short period of time, you can try putting a small amount of blue loctite onto the threads to prevent future loosening."
%}

## Keep eccentric spacers properly adjusted

The eccentric spacers are used for making fine adjustments to the spacing between the v-wheels on the gantry and cross-slide. This spacing is critical for FarmBot to move smoothly and wobble-free.

Over time, it is possible for your wheels to wear down slightly which can cause wobbling and a loss of precision in your device. It is also possible for your wheels to 'settle' and fall out of their optimal positioning, which can also cause wobbling.

{%
include callout.html
type="success"
title="Every three months"
content="Check your eccentric spacers for proper adjustment, and make adjustments as necessary using the [eccentric spacer adjustment reference guide](../FarmBot-Genesis-V1.3/reference/eccentric-spacer-adjustment.md)."
%}

## Keep belts tensioned
It is possible for the belts to stretch or slip over time which can lead to missed steps, premature wearing, a gantry that binds on the tracks, as well as a loss of precision in FarmBot's movements.

{%
include callout.html
type="success"
title="Every three months"
content="Check belts for proper tension. If you notice extra slack, loosen the **belt clip** that holds the belt in place, pull the clip to tension the belt, and then re-tighten the clip. Make sure to check all three belts: the two along the tracks and the one across the gantry main beam."
%}



{%
include callout.html
type="danger"
title="Do not over-tension"
content="The belts should not be under extreme tension. If they are, FarmBot's motors will have difficulty in moving and will miss steps. Use a small amount of tension - just enough so that there is no slack in the system."
%}



{%
include callout.html
type="warning"
title="Not done yet"
content="If you had to re-tension one or both of the belts along the tracks, the you must [re-equalize and synchronize the gantry](../FarmBot-Genesis-V1.3/gantry/feed-and-secure-the-belts.md#step-3-equalize-the-gantry) to prevent binding."
%}

## Inspect for damage

Every three months, inspect your hardware for visible damage such as corrosion, bending, or cracking of components. Under normal circumstances your hardware will be just fine because it is designed to withstand normal operating forces and built with corrosion and UV resistant materials.

However, certain conditions and accidents can cause damage such as:
* An unusually corrosive environment such as that near an ocean
* High temperature differences between the day and night can cause cracking
* Accidental impacts with the hardware that causes something to bend or break, such as tripping on the tracks, falling branches, children.

If you notice any damaged parts, promptly replace the components. If the component is not replaced, you risk damaging other components out of negligence.

{%
include callout.html
type="success"
title="Let us know"
content="If you suspect damage has occurred as a fault of our design or manufacturing, let us know. We're here to work with you to make it right and improve future FarmBot hardware for everyone. Get in touch with us at [support@farm.bot](mailto:support@farm.bot)."
%}


# Tracks
## Clean track surfaces
Once a month, inspect your tracks for an accumulation of mud, dirt, and other debris. Because the tracks are so low to the ground, it is common for them to accumulate unwanted materials. This can create unnecessary friction for the gantry when moving across the tracks, ultimately leading it to bind up if the tracks are not cleaned.

{%
include callout.html
type="success"
title="Regularly"
content="Use a brush, broom, sponge, compressed air, and/or hose to clean the surfaces of your tracks."
%}



{%
include callout.html
type="warning"
title="Be gentle"
content="Do not apply excessive force in order to avoid misaligning extrusions or bending plates."
%}

## Maintain track alignment
FarmBot's tracks need to be very straight and parallel with each other in order for the gantry to move smoothly across them. With time, the tracks may move and twist due to a variety of factors such as:
* Screws becoming loose
* Thermal expansion and contraction due to large temperature swings
* Deterioration of supporting infrastructure such as wood posts
* Supporting infrastructure shifting due to soil expansion and contraction
* Falling branches, earthquakes, or other cataclysmic events

Misaligned tracks can cause the system to creak and ultimately bind as the gantry attempts to move across the tracks. This can prevent FarmBot from working and even cause damage to other components. If you notice your tracks have become misaligned, work to fix them as soon as possible with the following suggestions.

### Realigning track plates
Signs of a misaligned track plate include misaligned track extrusions (see below), twisted track extrusions, difficulty in the gantry moving across extrusion joints, and even visual misalignment.

{%
include callout.html
type="success"
title="To realign track plates..."
content="Try loosing their screws and re-tightening them. You may need to insert a washer or other shim in between the track plate and supporting infrastructure to adequately tighten the plate while maintaining alignment."
%}

### Realigning track extrusions
It is possible for a track extrusion to loosen and then become misaligned with an adjacent extrusion. Even small misalignments can prevent the gantry from smoothly moving across joints. Inspect for misalignment by running your fingers across track joints.

{%
include callout.html
type="success"
title="Smooth to the touch"
content="If you can feel one extrusion noticeably higher than another, then loosen the M5 screws attaching it to the track plate, realign the extrusion by hand, and re-tighten the screws."
%}


# Gantry

## Equalize and synchronize the gantry
It is possible for the gantry to become twisted such that is not perpendicular to the tracks. This is usually caused by an obstruction on one track that stalls that side of the gantry and misaligns the system, or a loose belt on one track.

If a belt is loose, tighten according to [these instructions](maintenance.md#keep-belts-tensioned).

If the belts are tight and the gantry is twisted, re-equalize and synchronize the gantry using instructions on the [gantry page](../FarmBot-Genesis-V1.3/gantry/feed-and-secure-the-belts.md#step-3-equalize-the-gantry).

{%
include callout.html
type="success"
title="Preventative > reactive"
content="Even if your belts are tight and the gantry moves across the tracks fine, the gantry could still be twisted and causing unnecessary stress and wear to the components. It is recommended to equalize and synchronize the gantry twice a year to ensure that it stays perpendicular to the tracks, even if it is not noticeably twisted."
%}


# Cross-Slide
## Inspect the delrin leadscrew block
Over time, it is possible for the delrin leadscrew block to wear down. This can introduce play into the system that decreases z-axis precision, which can cause issues with the mounting and dismounting of tools.

{%
include callout.html
type="success"
title="Once per year"
content="Inspect the delrin ledscrew block for signs of wear. You can do this by gently pushing and pulling up and down on the leadscrew to see if you can feel any looseness in the system. If you detect there to be a large amount of play, replace the leadscrew block as soon as possible."
%}


# Z-Axis
## Clean and lubricate the leadscrew
The z-axis leadscrew will become dirty after being outside for a prolonged period of time. Excessive dirt and grime on the leadscrew can cause premature wear, a loss of precision, and missed steps if not addressed.

{%
include callout.html
type="success"
title="Every 6 months"
content="Wipe the leadscrew clean with a damp rag or sponge. Applying a small amount of high quality synthetic lubricant to the leadscrew can help make motion through the delrin leadscrew block smoother and quieter. We recommend high quality synthetic lubricant such as that used for bicycle chains."
%}

# UTM and Tools
## Inspect the UTM grommets and o-rings
It is possible that intense temperature and adverse weather cycles could degrade the rubber grommets in the UTM cover and the o-rings on the bottom of the UTM.

{%
include callout.html
type="success"
title="Once per year"
content="Inspect the rubber grommets and o-rings to ensure they are not cracked, broken, or otherwise degraded to the point of sealing ineffectively. If any damage is found, replace them as soon as possible."
%}

## Remove magnet debris
It is possible for dust, soil, and other debris to magnetically attract to the UTM and Tool magnets and build up over time. This debris can prevent the UTM from correctly mounting tools.

{%
include callout.html
type="success"
title="Every three months"
content="Inspect the UTM and Tool magnets for debris. If any is found, remove the M5 locknut and screw holding the magnet in place and remove the magnet for cleaning."
%}

## Remove internal needle debris
It is possible for dust, soil, and other debris to become stuck inside of seed injector's luer loock needles. This can cause a loss of seed suction power and prevent the seed injector from working reliably.

{%
include callout.html
type="success"
title="Every three months"
content="Wash out the inside of the seed injector needle by running warm water through it. If debris becomes permanently lodged inside the needle you will need to replace the needle."
%}

## Dissolve mineral buildup in the watering nozzle
It is possible - depending on your water source - for the watering nozzle to slowly become clogged with mineral buildup and other deposits. This can prevent FarmBot from watering the correct amount for each plant and can also cause uneven spray.

{%
include callout.html
type="success"
title="Every 6 months"
content="Inspect the watering nozzle for any deposits or unusual spray patterns. To remove mineral buildup, soak your watering nozzle in a bowl of distilled white vinegar and hot water for a few hours. This should dissolve most things. If needed, use a toothpick, thumbtack, or paperclip to remove any debris left in the nozzle holes."
%}

## Remove weeder and soil sensor debris
It is possible for dirt and other debris to become stuck between the weeder implements or build up on the contacts of the soil sensor which could cause inaccurate readings.

{%
include callout.html
type="success"
title="Every 3 months"
content="Clean the tools of any debris using a damp rag. Ensure that the soil sensor PCB is dry before using it after cleaning."
%}
