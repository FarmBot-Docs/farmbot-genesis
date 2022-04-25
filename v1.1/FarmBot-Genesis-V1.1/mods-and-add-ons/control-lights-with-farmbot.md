---
title: "Control Lights with FarmBot"
slug: "control-lights-with-farmbot"
description: "DIY instructions for installing and controlling LED or grow lights with FarmBot"
---

Want to light up your FarmBot at night so you can more easily harvest dinner-time veggies? Or maybe you want to experiment with growth rates by using specialized grow lights? Whatever the reason you want to have lights on your FarmBot, we'll show you how to do it in this easy tutorial.




# Purchase Components



|Component                     |Recommended Supplier          |Cost                          |
|------------------------------|------------------------------|------------------------------|
|Waterproof 12V Flexible LED Strip Lights|[Amazon](http://smile.amazon.com/Waterproof-Flexible-Lights-Daylight-Lumens/dp/B00JQV6U7Q/ref=redir_mobile_desktop?ie=UTF8&*Version*=1&*entries*=0)|$10.15



# Assembly Instructions

## Step 1: Connect the lights to the RAMPS shield
FarmBot's RAMPS shield provides multiple 12V outputs which can be used to power the LED lights. Strip 5mm of insulation off of the red and black wires coming from the LED strip.


Attach the wires to one of the RAMPS shield 12V outputs, making sure the red wire is hooked up to the positive output, while the black wire is hooked up to the negative output. Take note of the pin number you are connecting to as it will be used to control the lights from the web app later.


## Step 2: Mount or route the lights wherever desired
The LED strip we recommend purchasing is easily routed through the driveshaft supports as follows. This configuration will cast light down from the gantry onto your plants. If you would like to mount your lights elsewhere, you can use the included adhesive backing, zipties, double sided foam tape, or other means to secure the lights as desired.







# Usage

In general there are two ways to use your newly installed LED lights:
## Method 1: Manually Control the Lights with the Tools Widget
From the **FarmBot Web App**, navigate to the **Controls** page. Click the **Edit** button in the header of the **Tools** widget.


Create a new tool named "Lights" and assign it the Pin number that you hooked the LED wires to on the RAMPS shield.


Click the **Save** button in the widget header and then turn on your lights with the new toggle switch!





{%
include callout.html
type="success"
title="Light at the end of the tunnel"
content="If all has gone well, your lights should be shining! Turn them on to impress your friends, for more easily harvesting veggies at night, or for night time photography!"
%}




## Method 2: Systematically Use the Lights in Your Sequences and Regimens
Because your lights are hooked up to a pin on the Arduino, you can easily create sequences that utilized the lights. Simply add a **Write Pin** step into your sequence to turn the lights on with a *pin value* of "1" and off with a *pin value* of "0". Make sure you set the *pin mode* to "0" and the *pin number* to whichever pin number you hooked up the wires to on the RAMPS shield.




{%
include callout.html
type="info"
title="Make it rave"
content="Here's a fun test you can try out: Make a new sequence called \"Rave!\" and add these four steps to it:
* Write Pin - to turn *on* the lights
* Wait - with a value of 250ms
* Write Pin - to turn *off* the lights
* Wait - with a value of 250ms

Now press the **Execute** button a ton of times as fast as you can and enjoy the #FarmBotRave with your plants!"
%}




