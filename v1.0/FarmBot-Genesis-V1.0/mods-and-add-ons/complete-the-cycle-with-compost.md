---
title: "Complete the Cycle with Compost"
slug: "complete-the-cycle-with-compost"
excerpt: "DIY instructions for using a dual chamber compost tumbler with FarmBot"
---

* toc
{:toc}

No matter how well FarmBot tends to your plants, they won't do well without nutrient-rich soil. Adding compost is an easy and low-cost way to build healthy soil using yard and kitchen waste. Examples of compostable materials include food scraps, leaves, papers, grass clippings and other yard waste, and dead or otherwise unwanted plants.

# Setting up a Composter

First find a location for your composter. Ideally it should be located near your FarmBot and in direct sunlight so that you can easily and quickly move plants and yard waste into it and so that the sun helps to cook the compost. The area should also be flat, and have adequate space around it so that the composter can be accessed and tumbled easily. You might also consider positioning it near your kitchen or other major sources of organic material that you plan on composting.

![FarmBot SOlar Compost.jpg](FarmBot_SOlar_Compost.jpg)

_Can you spot the composter?_



# What to put in the Composter

The composting process works best when nitrogen-rich moist **greens** are mixed with carbon-rich dry **browns**.
## Example Greens
* Kitchen scraps
* Grass clippings
* Garden and house plants

## Example Browns
* Leaves/twigs
* Straw/hay
* Sawdust/mulch

{%
include callout.html
type="success"
title="Ratio matters"
content="The mixing ratio should be **2 parts greens** to **1 part browns**."
%}



{%
include callout.html
type="warning"
title="Do not compost"
content="* Meats/fats/bones
* Dairy products
* Trash/plastic
* Invasive plants/weeds"
%}



# How to Compost in Batches

Because the composting process takes anywhere between 2 weeks and 3 months to go from raw material (greens and browns) to compost, it is advantageous to create compost in batches. We're using a **dual chamber** composter that allows us to do this easily with the following steps:

1. Add raw material (greens and browns) to one chamber of the composter. When you start a batch, you may want to add a little bit of soil too.
2. Tumble the composter 5-10 times after every deposit of materials or every 2-3 days. During this time, check the moisture level by squeezing a handful of compost. If it feels like a damp sponge, then the moisture level is good. If it feels dry, add a little water and give it a few more tumbles to mix in.
3. When the first chamber is full, let it cure (ie: do not add any new materials to it). Instead, start adding new raw materials to the second chamber, following steps 1 and 2.
4. When the second chamber is full, it should be time for you to remove the compost from the first chamber. The compost should be a very dark, moist, earthy smelling soil that is high in nutrients. If it doesn't look ready, keep it in the composter for a few more weeks. To get the compost out, rotate the tumbler so that the door is on the bottom. Place a bucket or tarp under the door and then open it to dump the contents out.
5. Repeat the process by adding new raw materials to the first chamber while letting the second chamber cure.

{%
include callout.html
type="success"
title="Using the compost"
content="Distribute the compost in your garden by mixing it into the soil with a trowel. You should never plant things directly in compost. Rather, you should use at most a 50/50 mix of compost/native soil."
%}



{%
include callout.html
type="info"
title="Composting produces heat"
content="When you strike the right balance of moisture, greens, browns, and tumbling, your compost should become hot. This heat is produced from the microorganisms multiplying and decomposing the materials, and is a sign that your compost is doing well. The hotter your compost gets, the quicker it will break down."
%}



# Composting Tips

## Follow the 3 rules of composting
1. Use quality materials and the proper ratio of 2 parts greens (nitrogen) to one part browns (carbon)
2. Keep the moisture level consistent so that the mix feels like a damp sponge
3. Allow good air circulation and aeration by turning the composter every few days after the batch heats up

## Smaller pieces decompose faster
Small shredded materials have more surface area which allows more microorganisms, water, and oxygen to contact the material for faster decomposition. Consider cutting up kitchen scraps, crumbling leaves, and breaking up twigs to speed up the composting process.

# Troubleshooting

## Compost does not heat up
* Mix is too wet - add dry browns
* Mix is too dry - add water
* mix ratio is off - check greens/browns ratio and adjust accordingly

## Odor
* Ammonia smell means there is too much nitrogen (greens) in the mix - add dry browns
* Putrid smell (like rotten eggs) means the mix is too wet and/or there is not enough oxygen - add dry browns to absorb excessive moisture and turn the composter, open air vents

## Pests and Insects
* Rodents are attracted to meat and fatty foods - remove them from the composter
* Flies and insects are attracted to uncovered raw material, especially kitchen scraps - mix or cover with browns, finished compost, or native soil

# Hack Your Composter!

If you're looking for a fun weekend project, consider hacking your composter! Here are some project ideas:
## Auto-Tumble
Use a motor, some 3D printed parts, and FarmBot's Arduino to auto-rotate your compost bin every few days. You can use the sequence builder and event scheduler of the web app to specify for how long and how often the bin should be tumbled.
## Monitor Temperature
Use a thermistor and some wire to monitor the temperature of your compost. You can plug directly into the Arduino's analog inputs and then pump the data to your web app dashboard!
## Monitor Moisture and Auto-Add Water
Hack an off-the-shelf moisture meter to plug directly into FarmBot's Arduino and pump the data to the web app. Add some misters inside of your composter and hook them up to a water source with a solenoid valve. You can use the sequence builder and event scheduler of the web app to specify for how long and how often the misters should be active for, and even use an IF statement block to make misting conditional based on the current moisture level!

{%
include callout.html
type="success"
title="Build something awesome or have ideas to share?"
content="Share with us and the entire FarmBot community in the [forum](http://forum.farmbot.org)!"
%}

