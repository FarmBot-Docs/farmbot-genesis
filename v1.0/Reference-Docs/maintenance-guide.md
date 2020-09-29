---
title: "Maintenance Guide"
slug: "maintenance-guide"
excerpt: "Use these techniques to keep your FarmBot running smooth for years to come"
---

* toc
{:toc}

In this section we'll go over maintenance tips and techniques that can keep your FarmBot operating like the day you installed it.

# General

## Keep FarmBot Clean

FarmBot is a farmer that works and lives all day and night outside with the rain, sun, bugs, birds, and dirt. At the same time, FarmBot is a precision CNC machine with a lot of parts that allow it to move with millimeter accuracy to grow your food. Most would say these things can't co-exist. But they can with regular cleaning of your device.

{%
include callout.html
type="success"
title="FarmBot enjoys a good sponge bath"
content="Once a month, use a brush, sponge, broom, and a little water to clean off your FarmBot. Remove built up bird poop, mud, spider webs, and other debris. Clean out the hard to reach places, cut its nails, and treat it to a massage. Your FarmBot will appreciate your loving care and pay you back with years of vegetables."
%}

## Tighten Loose Screws

Once a month, you should inspect your hardware for loose screws. You can do this by grabbing a component such as an extrusion and attempting to wiggle it with a small amount of force. If you can feel or hear anything rattling, a screw somewhere needs to be tightened. Use the appropriate wrench to tighten any screws that you find to be loose.

{%
include callout.html
type="info"
title="Why are my screws loose?"
content="Under normal operating circumstance, your screws can become loose from vibrations, thermal expansion and contraction, rain, and even high winds. If a particular screw becomes loose multiple times in a short period of time, you can try putting a small amount of blue loctite onto the threads to prevent future loosening."
%}

## Keep Eccentric Spacers Properly Adjusted

Your eccentric spacers are used for making fine adjustments to the spacing between the wheels of your moving parts (Gantry, Cross-Slide, and Z-Axis). The spacing is key to having your parts move smoothly and wobble-free.

Over time, it is possible for your wheels to wear down slightly which can cause wobbling and a loss of precision in your device. It is also possible for your wheels to 'settle' and fall out of their optimal positioning, which can also cause wobbling.

Once every three months, check your eccentric spacers for proper alignment, and make adjustments as necessary.

### Adjusting the eccentric spacer
1. Grab a 8mm wrench and slide it onto the eccentric spacer. Turn the spacer about 1/32 of a turn. Depending on the direction you turn the spacer, and the current orientation of the spacer, your spacing will either increase or decrease. Your goal is to adjust the spacer in the direction you need, so do some experimentation to find out which direction to turn it.
2. Once you have adjusted the spacer 1/32 of a turn, inspect for fit.
3. Continue the steps above until your components move smoothly and are wobble-free.

{%
include callout.html
type="danger"
title="Don't over tighten"
content="Be careful not to over tighten your wheels. This can cause a screw or plate to bend, introduce significant friction to the system, or cause a wheel to deform."
%}



{%
include callout.html
type="success"
title="The perfect fit"
content="The perfect fit is subjective and you'll need to play around to get it just right. Here is our best tip: Adjust your wheel spacing so that it is as large as possible without inducing wobbling or rattling. This will ensure you are not over tightening your wheels and risking damage.

You would rather have a wobbly wheel that you can tighten than damaged components.

Don't expect your components to roll like a ball down a hill. A well fitted system will have a little bit of friction. Again, just play around with the spacing and use your best judgement."
%}

## Keep Belts Tensioned
It is possible for the belts to stretch or slip over time which can lead to missed steps, premature wearing, a gantry that binds on the tracks, as well as a loss of precision in FarmBot's movements.

{%
include callout.html
type="success"
title="Every three months"
content="Check belts for proper tension. If you notice extra slack, loosen the **belt clip plate** that holds the belt in place, pull the plate to tension the belt, and then re-tighten the plate. Make sure to check all three belts: the two along the tracks and the one across the gantry main beam."
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
content="If you had to re-tension one or both of the belts along the tracks, the you must re-equalize and synchronize the gantry to prevent binding. Follow the instructions for this in the assembly instructions section on the [gantry page](../FarmBot-Genesis-V1.0/gantry.md)."
%}

## Inspect for Damage

Once a month, inspect your hardware for visible damage such as corrosion, bending, or cracking of components. Under normal circumstances your hardware will be just fine because it is designed to withstand normal operating forces and built with corrosion and UV resistant materials.

However, certain conditions and accidents can cause damage such as:
* An unusually corrosive environment such as that near an ocean
* High temperature differences between the day and night can cause cracking
* Accidental impacts with the hardware that causes bending (tripping, falling branches, etc)

If you notice any damaged parts, promptly replace the components. If the component is not replaced, you risk damaging other components out of negligence.

{%
include callout.html
type="success"
title="Let us know"
content="If you suspect damage has occurred as a fault of our design or manufacturing, let us know. We're here to work with you to make it right and improve future FarmBot hardware for everyone."
%}





# Gantry

## Re-Equalize and Synchronize the Gantry
It is possible for the gantry to become twisted such that is not perpendicular to the tracks. This is usually caused by an obstruction on one track that stalls that side of the gantry and mis-aligns the system, or a loose belt on one track.

If a belt is loose, follow the maintenance tip above for tightening the belts.

If the belts are tight and the gantry is twisted, re-equalize and synchronize the gantry using instructions on the [gantry page](../FarmBot-Genesis-V1.0/gantry.md).

{%
include callout.html
type="success"
title="Preventative > Reactive"
content="Even if your belts are tight and the gantry moves across the tracks fine, the gantry could still be twisted and causing unnecessary stress and wear to the components. It is recommended to re-equalize and synchronize the gantry twice a year to ensure that it stays perpendicular to the tracks, even if it is not noticeably twisted."
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

## Clean and lubricate the Leadscrew
The z-axis leadscrew will become dirty after being outside for a prolonged period of time. Excessive dirt and grime on the leadscrew can cause premature wear, a loss of precision, and missed steps if not addressed.

{%
include callout.html
type="success"
title="Once per year"
content="Wipe the leadscrew clean with a damp rag or sponge. Applying a small amount of high quality synthetic lubricant to the leadscrew can help make motion through the delrin leadscrew block smoother and quieter. We recommend high quality synthetic lubricant such as that used for bicycle chains."
%}



# UTM

## Inspect the Seals
It is possible that intense temperature and adverse weather cycles could degrade the rubber seals between the UTM cover and the cables and tubing connected to the UTM.

{%
include callout.html
type="success"
title="Once per year"
content="Inspect the rubber seals to ensure they are not cracked, broken, or otherwise degraded to the point of sealing ineffectively. If any damage is found, replace them as soon as possible."
%}

## Remove Magnetic Debris Buildup
It is possible for dust, soil, and other debris to magnetically attract to the UTM's magnets and build up over time. This debris can prevent the UTM from correctly mounting tools.

{%
include callout.html
type="success"
title="Once per year"
content="Inspect the UTM's magnets for debris. If any is found, remove the M5 locknut and screw holding the magnet in place and remove the magnet for cleaning."
%}



# Tools

## All Tools

### Remove Magnetic Debris Buildup
It is possible for dust, soil, and other debris to magnetically attract to a tool's magnets and build up over time. This debris can prevent the tool from correctly mounting to the UTM.

{%
include callout.html
type="success"
title="Every three months"
content="Inspect the tool's magnets for debris. If any is found, use your fingers or a brush to remove it. Remove debris immediately if a tool is dropped into the soil"
%}

## Seeder

### Remove internal debris buildup
It is possible for dust, soil, and other debris to become stuck inside of the plastic seed injector tip. This can cause a loss of seed suction power and prevent the seed injector from working reliably.

{%
include callout.html
type="success"
title="Every three months"
content="Wash out the inside of the seed injector tip by running warm water through the seed injector."
%}

