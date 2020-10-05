---
title: "Plug Everything In"
slug: "plug-everything-in"
---

* toc
{:toc}

# Step 1: Attach the RAMPS power cable to the power supply

{%
include callout.html
type="danger"
title=""
content="The power supply should still be **unplugged** and **unpowered** at this time."
%}

Attach the red (positive) wire from the **RAMPS power cable** to one of the available positive outputs on the **power supply** and tighten the screw.

Attach the black (negative) wire from the **RAMPS power cable** to one of the available negative outputs on the **power supply** and tighten the screw.

![RAMPS_power.png](_images/RAMPS_power.png)

# Step 2: Attach the Raspberry Pi power cable to the power supply
Attach the red (positive) wire from the **Raspberry Pi power cable** to one of the available positive outputs on the **power supply** and tighten the screw.

Attach the black (negative) wire from the **Raspberry Pi power cable** to one of the available negative outputs on the **power supply** and tighten the screw.

![RAMPS_and_Pi_power.png](_images/RAMPS_and_Pi_power.png)

# Step 3: Connect the peripherals
Connect the **solenoid valve cable** to the positive and negative terminals labelled **D9** on the **RAMPS shield**.

![Screen Shot 2017-02-27 at 11.12.33 PM.png](_images/Screen_Shot_2017-02-27_at_11.12.33_PM.png)

Connect the **vacuum pump cable** to the positive and negative terminals labelled **D10** on the **RAMPS shield**.

![Screen Shot 2017-02-27 at 11.13.48 PM.png](_images/Screen_Shot_2017-02-27_at_11.13.48_PM.png)

# Step 4: Plug in the stepper motors and rotary encoders
Plug in the **motor and encoder cables** to the **RAMPS shield** according to the following diagram.

![RAMPS_wiring_diagram.png](_images/RAMPS_wiring_diagram.png)



{%
include callout.html
type="info"
title="Plugging in the correct black wire"
content="The encoder cables have two black wires. The thinner black wire is the **ground** wire, which needs to be plugged into the RAMPS board. The slightly thicker black wire is connected to the cable's **shielding**, which does not need to be connected to RAMPS."
%}



{%
include callout.html
type="info"
title="Motor Cable Orientation"
content="You can plug the stepper motor cables into the RAMPS board in either direction: _black-red-white-yellow_ or _yellow-white-red-black_ top-to-bottom. Changing the direction that the motor wire connector is plugged in will change the direction that the motor moves. So if a motor is moving right when it should be moving left, you can change the orientation of the stepper motor wire connector on the RAMPS board.

Since the X1 and X2 motors need to be moving in opposite directions for the gantry to move, the motor wire connectors for X1 and X2 should be plugged in opposite each other (for example, yellow on top for X1 and yellow on bottom for X2)."
%}



{%
include callout.html
type="info"
title="Second X-Axis Encoder"
content="Only one x-axis encoder is currently implemented in the firmware, so the X2 encoder wires do not need to be plugged in to the RAMPS board at this time."
%}

# Step 5: Plug in the UTM cable's connectors
Plug in the UTM's wires to the RAMPS shield according to the [pin mapping table](../../FarmBot-Genesis-V1.2/utm.md).


|UTM Pin/UTM Wire              |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|A/1                           |+5V on Arduino/RAMPS          |Soil sensor
|B/2                           |Ground (0V) on Arduino/RAMPS  |Ground
|C/3                           |Pin D63 on Arduino/RAMPS - Digital-In|Tool verification
|D/4                           |Pin D59 (A5) on Arduino/RAMPS - Analog-In|Soil sensor and other analog signal tools



{%
include callout.html
type="info"
title="Note"
content="As of the v4.0.0 software released on June 21, 2017, the UTM Pin/Wire A/1 should be connected to +5V on Arduino/RAMPS, while B/2 should be connected to Ground. This change is because the tool verification pin now uses the pull-up resistor in the firmware, so it should be jumped to Ground, instead of +5V. Note: you should double check the wiring of your soil sensor as well."
%}

# Step 6: Add the power cord to the power supply
Attach the **FarmBot power plug** to the **power supply** inputs according to the following image.

![power cord.png](_images/power_cord.png)



![power_supply_connections.png](_images/power_supply_connections.png)

# Step 7: Set the power supply input voltage
The power supply can accept both 110V and 220V power input.

{%
include callout.html
type="danger"
title="Mandatory"
content="You **MUST** set the power supply's input voltage switch to the correct setting before you plug it in otherwise you risk destroying the power supply."
%}

Set the switch to the correct input voltage. The voltage label you see must match your country's power infrastructure.

![voltage_selector.png](_images/voltage_selector.png)

# Step 8: Plug in the power supply

{%
include callout.html
type="danger"
title="Before plugging in..."
content="Double check all of your connections, component orientations, input voltage switch, and ensure there are not any loose wires that could short circuit."
%}



{%
include callout.html
type="danger"
title="Beware of electrical shock"
content="Remember that once you plug in the power supply, your system will be powered. Once powered, you cannot add, remove, or change any motor cables, peripheral wires, stepper drivers, etc, or you risk frying your electronics and/or being electrically shocked.

Once powered, be especially careful working around the power supply's exposed inputs and outputs, and the exposed electronics boards. **Do not touch or handle any exposed contacts or other electrical components.**"
%}

If everything looks good, and you understand the precautions needed around powered electronics, go ahead and plug FarmBot into the wall.

{%
include callout.html
type="success"
title="The mark of success"
content="If all has gone well, your Raspberry Pi should boot up and you should revel in the little blinking red and green lights!"
%}



{%
include callout.html
type="info"
title="Something wrong?"
content="See smoke? Heard a loud *pop*? If anything seems suspicious or hazardous, **immediately unplug the power supply from the wall** and contact us at [support@farmbot.io](mailto:support@farmbot.io)."
%}



{%
include callout.html
type="warning"
title="Need to make changes?"
content="If you need to add, remove, or change any of the wiring now or in the future, you **MUST** unplug the power supply from the wall first. This will minimize the risk of electrical shock and the potential to permanently damage your electronics."
%}

# Step 9: Keep power supply in outdoor box

The power supply lives inside the weatherproof **[SockitBox](http://www.sockitbox.com/size-option/285/#ad-image-3)**, along with the vacuum pump.

![power_supply_box.png](_images/power_supply_box.png)



![box_location.png](_images/box_location.png)


# What's next?

 * [Tools](../../FarmBot-Genesis-V1.2/tools.md)
