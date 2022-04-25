---
title: "Install the UTM and Cover"
slug: "install-the-utm-and-cover"
---

# Step 1: Feed the Tubes and Cable
Push the **UTM cable** through the center hole in the **UTM cover** so that there is about 10cm of cabling beneath the cover. It may be difficult to do this because of the friction and tight seal created between the rubber seal and the cable. Be gentle and take your time. Some soapy water can facilitate the cable to slide through more easily, and will dry up within a day.


Push the **water tube** through *port A* on the **UTM cover** so that there is about 10cm of tubing beneath the cover.


Push the **vacuum tube** through *port B* on the **UTM cover** so that there is about 10cm of tubing beneath the cover.


Push the **extra peripheral tube** through *port C* on the **UTM cover** so that there is about 10cm of tubing beneath the cover.


# Step 2: Wire up the UTM
Use the **exacto blade** to remove 5cm of the **UTM cable** outer rubber insulation.

{%
include callout.html
type="warning"
title="Take your time"
content="When removing the outer insulation, it is easy to accidentally cut through some of the smaller wires inside the cable, or cut through their insulation. Take your time to avoid accidentally doing this.

If you do accidentally sever one of the smaller wires, you must cut the entire cable down to an uncut section and start over."
%}




Each small wire of the **UTM cable** is numbered with small white text. Fan out the wires and arrange them in order from 1 to 12.


 Use the **wire strippers** to remove 0.5 to 1cm of insulation from each small wire.


Use a **zip-tie** to secure each wire to the corresponding **M3 screw** on top of the **UTM**. Wire 1 should connect to UTM pin/screw 1, and so forth.





## Pin Mapping

|UTM Pin                       |is connected to               |and used for                  |
|------------------------------|------------------------------|------------------------------|
|1                             |Ground (0V) on Arduino/RAMPS  |Ground
|2                             |+5V on Arduino/RAMPS          |Tool Verification
|3                             |Pin D16 on Arduino/RAMPS - Digital-In|Tool Verification
|4                             |Pin D17 on Arduino/RAMPS - Digital I/O|Data tool functions such as servo control or sensor reading
|5                             |Pin D23 on Arduino/RAMPS - Digital I/O|Data tool functions such as servo control or sensor reading
|6                             |Pin D8 on Arduino/RAMPS - High power output|High power tool functions such as motors or lasers
|7                             |Pin 20 on Arduino/RAMPS - I2C data (SDA)|Complex tooling requiring addressing of commands
|8                             |Pin 21 on Arduino/RAMPS - I2C clock (SCL)|Complex tooling requiring addressing of commands
|9                             |USB VCC (+5V)                 |USB based tools
|10                            |USB D- (Data -)               |USB based tools
|11                            |USB D+ (Data +)               |USB based tools
|12                            |USB Ground (0V)               |USB based tools


# Step 3: Install the UTM and Cover onto the Z-Axis
Slide the **water tube** onto the *port A* **barb**, the **vacuum tube** onto the *port B* barb, and the **extra tube** onto the *port C* barb.


Slide the **UTM cover** down the tubes and cable until it sits flush against the top of the UTM.

{%
include callout.html
type="warning"
title="Keep it sealed"
content="The UTM cable's outer insulation must maintain contact with the UTM cover's rubber seal in order to keep rain out. It is best to keep 1cm or more of the cable's insulation inside of the cover."
%}




Insert two **M5 x 10mm screws** through the **UTM cover** mounting holes and then lightly thread an **M5 tee nut** onto each. Repeat for the **UTM**.


Slide the **UTM cover** and **UTM** onto the **z-axis** extrusion. The plastic brackets should be positioned on the backside of the extrusion. The bottom of the UTM should be flush with the bottom of the extrusion, and the bottom of the UTM cover should be flush with the top of the UTM.


Tighten all four **M5 screws** with the **3mm hex driver**.




{%
include callout.html
type="success"
title="Woo hoo!"
content="You just finished the most tedious and arguably difficult part of building your FarmBot. Take a deep breath, do a stretch, and grab a snack - you deserve it!"
%}

