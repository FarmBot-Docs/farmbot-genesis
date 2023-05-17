---
title: "Product Safety"
slug: "product-safety"
description: "Understand the potential safety hazards of FarmBot"
---

While FarmBot is an easy-to-use product suitable for home and classroom environments, it is important to recognize and understand the potential **safety hazards** associated with assembly and use of the machine. Refer to the non-exhaustive table below of the most common hazards before beginning assembly or using your FarmBot, especially with children.

{%
include callout.html
type="success"
title="Safety first"
content="Adhering to the recommended safety precautions can help prevent accidents and injuries."
%}

# Hazards

Not all hazards may apply to your specific FarmBot model or configuration, and other risks may exist that are not listed. If you have any questions or concerns about product safety, please [contact us](mailto:support@farm.bot).

|Hazard|Description|Precautions|
|------|-----------|-----------|
|Heavy boxes|The FarmBot may have shipped in one or more heavy boxes.|Use proper lifting techniques when moving the boxes and ask for help if you are unable to lift the boxes safely on your own.
|Sharp edges|The aluminum extrusions and other aluminum plates and brackets may have sharp edges that can cut skin.|Be careful when handling these parts and consider wearing light duty construction gloves during assembly. You may use a file or fine grit sandpaper to smooth out any sharp edges if desired.
|Tripping|The power and water lines can be a tripping hazard if not properly routed.|Route the power and water lines along the raised bed or along the ground in a way that does not create a tripping hazard.
|Pinch and entanglement points|There are a number of locations where fingers can be pinched and hair and clothing can become entangled in the machine during operation. These include but are not limited to the: motors, gantry wheel plates, cross-slide, leadscrew, rotary tool, and UTM.|Keep your hands, feet, clothing, hair, children, and pets away from pinch and entanglement points while the device is in operation. If you must perform maintenance on the device, E-stop the device or power it down first.
|Rotary tool debris|When the rotary tool is in operation it can produce debris such as soil, dust, and small rocks that can get ejected from the tool at high speeds. This debris can cause injury to the eyes and skin.|Inspect the rotary tool and attached accessories for any visible signs of damage or wear that could compromise its safety. Wear safety glasses and protective clothing or keep a safe distance when operating the rotary tool, especially near children and pets.
|Electrical shock|FarmBot operates at 24V DC and can be powered by a 120V or 240V AC power source. When the device is powered on, there is a risk of electrical shock inside the electronics box and at cable connections, the motors, peripherals, and the UTM.|Do not open the electronics box or plug or unplug cables while the device is plugged into a power source. Do not submerge FarmBot in water. Do not touch the power supply, electronics, or cabling with wet hands. Do not operate FarmBot if anything is damaged. Do not operate FarmBot if the power supply or electronics are not properly grounded. Power the device using a GFCI protected outlet.
|Flooding|If the watering nozzle is left on for an extended period of time, the raised bed can flood and overflow.|Do not leave the water supply on for extended periods of time. Exercise caution when using custom code or 3rd party integrations to control your FarmBot's watering system.

# Certifications

The table below shows the components of FarmBot that have been tested and **certified** for safety by a third party.

|Component|Certification|Description|
|---------|-------------|-----------|
|[[Power supply]]|CE|Complies with the essential health, safety, and environmental requirements set by the European Union and can be legally sold and distributed within the European Economic Area.
|<i></i>|IP67|The device is completely protected against dust and can withstand being immersed in water up to a depth of 1 meter for 30 minutes, making it highly resistant to both solid particles and liquid ingress.
|[[Raspberry Pi]]|RoHS, FCC, and more|See the [Raspberry Pi documentation](https://pip.raspberrypi.com/) for a complete list of certifications.
|[[Farmduino]]|CE|Complies with the essential health, safety, and environmental requirements set by the European Union and can be legally sold and distributed within the European Economic Area.
|<i></i>|RoHS|Complies with the Restriction of Hazardous Substances Directive for electronic products.

# Safety features

The following **safety features** have been engineered into the FarmBot to provide a safer user experience and help mitigate various hazards.

|Feature|Description|
|-------|-----------|
|E-stop [[push button]]|A physical E-stop button is located on top of the electronics box and can be pressed to immediately stop and unpower all motors and peripherals. This can be used in case of being pinched or entangled in the machine, or if the machine is behaving unexpectedly.
|Stall detection|FarmBot can detect motor stalls and will by default [E-stop if a movement error occurs](https://my.farm.bot/app/designer/settings?highlight=e-stop_on_movement_error) too many times in a row. This can prevent injury and potential damage to the machine.
|[[Fuse]]|A fuse is located on the Farmduino to protect the electronics from over-current conditions that may be caused by a short or other malfunction.
|[Pin guard](https://my.farm.bot/app/designer/settings?highlight=pin_guard)|FarmBot can be configured to set a peripheral to a certain state after a timeout period. This can act as a secondary precaution in case a poorly designed sequence or custom code instructs FarmBot to leave a peripheral in an unsafe state for an extended period of time, such as leaving the solenoid valve open for too long.

# What's next?

 * [Supporting Infrastructure](../supporting-infrastructure.md)
