---
title: "Watering Nozzle"
slug: "watering-nozzle"
description: "Documentation for the FarmBot Genesis watering nozzle"
---

The **watering nozzle** accepts a concentrated stream of water coming from the [[UTM]] and turns it into a gentle shower for your plants.

{% include youtube.html id="xh7imhENpLQ" %}

![Watering nozzle being used](_images/watering_nozzle_being_used.jpg)

{%
include callout.html
type="success"
title="Pre-assembled for your convenience"
content="As of the v1.6 hardware release, the watering nozzle tool comes pre-assembled. In the next steps we'll hook up the rest of FarmBot's watering system."
%}

# Step 1: Assemble the solenoid valve and pressure regulator

Insert [[rubber gaskets]] into the female ends of the [[pressure regulator]], the [[garden hose to barb adapter]], and both [[NPT to barb adapters]]. Then screw one of the [[NPT to barb adapters]] onto the [[solenoid valve]] inlet, the [[pressure regulator]] onto the [[solenoid valve]] outlet, and the second [[NPT to barb adapter]] onto the [[pressure regulator]].

{%
include callout.html
type="info"
title=""
content="Note that the [[garden hose to barb adapter]] and [[NPT to barb adapters]] look very similar. If the threads don't engage correctly, you may have grabbed the wrong adapter."
%}

{% include gallery.html images="
![solenoid valve with barb adapter](_images/solenoid_valve_with_barb_adapter.png)
![solenoid valve with pressure regulator](_images/solenoid_valve_with_pressure_regulator.png)
![solenoid valve with pressure regulator and barb adapters](_images/solenoid_valve_with_pressure_regulator_and_barb_adapters.png)
" %}

# Step 2: Attach the solenoid valve
Attach the [[solenoid valve]] to the [[solenoid valve mount]] using two [[200mm zip ties]]. Then attach the [[solenoid valve mount]] to the **left gantry column** using two [[M5 x 10mm screws]] and [[tee nuts]]. Cables should be routed between the mount and the box.

{% include gallery.html images="
![solenoid valve attached to mount](_images/solenoid_valve_attached_to_mount.jpeg)
![solenoid valve mounted to gantry column](_images/solenoid_valve_mounted_to_gantry_column.png)
" %}

# Step 3: Wire up the solenoid valve

Connect the [[solenoid valve cable]] to the [[solenoid valve]] terminals. Note: in a few steps from now, you will connect the other end of the cable to the Farmduino.

![wired solenoid valve](_images/wired_solenoid_valve.png)

{%
include callout.html
type="info"
title="Do the quick-connect terminals not fit?"
content="Regretfully, some kits that shipped in August of 2022 included a solenoid valve cable with quick-connect terminals that are too small to fit onto the electrical tabs of the solenoid valve. If your cable does not fit, there should be two **quick connect terminals** of the correct size in a small plastic bag (shown below) that you can easily attach onto the cable with just a pair of scissors and needle nose pliers. Please refer to this troubleshooting document for [how to fix the solenoid valve cable](../../extras/troubleshooting/solenoid-valve-cable-fix.md) in about 5 minutes.

![quick connect terminals](_images/quick_connect_terminals.jpg)

If you are not comfortable modifying the cable yourself or do not have correct tools to do so, please email us at [support@farm.bot](mailto:support@farm.bot) with your original order number to request a free replacement. We apologize for this inconvenience."
%}

# Step 4: Connect the tubing

Push the **water tube** coming from the **y-axis cable carrier** onto the upper [[NPT to barb adapter]]. Then push the **water tube** coming from the **x-axis cable carrier** (where it is mounted to the gantry) onto the lower [[NPT to barb adapter]].

{% include gallery.html images="
![solenoid valve y-axis tubing](_images/solenoid_valve_y-axis_tubing.png)
![solenoid valve x-axis tubing](_images/solenoid_valve_x-axis_tubing.png)
" %}

# Step 5: Connect FarmBot to the water source

Screw the [[garden hose to barb adapter]] onto the **garden hose**. *Note that you will need to provide a garden hose of the appropriate length to connect FarmBot to your municipal water source - one is not provided with the FarmBot kits.* Then push the **water tube** coming from the bottom of the **x-axis cable carrier** onto the barb.

![Connect to the water source](_images/connect_to_the_water_source.png)

# What's next?

 * [Weeder](weeder.md)
