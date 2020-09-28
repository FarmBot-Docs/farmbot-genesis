---
title: "Control Lights with FarmBot"
slug: "control-lights-with-farmbot"
excerpt: "DIY instructions for installing and controlling LED or grow lights with FarmBot"
---

* toc
{:toc}

Want to light up your FarmBot at night so you can more easily harvest dinner-time veggies? Or maybe you want to experiment with growth rates by using specialized grow lights? Whatever the reason you want to have lights on your FarmBot, we'll show you how to do it in this easy tutorial.

{%
include callout.html
type="success"
title="Lights are included with v1.3+ kits"
content="We have included a 1.5m long strip of white LED lights with all v1.3+ FarmBot Genesis kits, and a 3m long strip with Genesis XL kits. ([Connection instructions](../../FarmBot-Genesis-V1-4/electronics.md#step-1-connect-the-peripherals)) You might want to use these instructions for adding more lights on your own, if you're building a FarmBot on your own, or you have an older kit."
%}



{%
include callout.html
type="info"
title="Inspiration only"
content="Please use the following information for *inspiration* only. The instructions are not necessarily complete or guaranteed to work, and may not satisfy your needs. If you would like help in modifying/adding-on to your FarmBot, consider posting in the [community forum](http://forum.farmbot.org)."
%}



![Lights.jpg](Lights.jpg)



# Step 1: Purchase components



|Component                     |Recommended Supplier          |Cost                          |
|------------------------------|------------------------------|------------------------------|
|Waterproof 12V Flexible LED Strip Lights|[Amazon](http://smile.amazon.com/Waterproof-Flexible-Lights-Daylight-Lumens/dp/B00JQV6U7Q/ref=redir_mobile_desktop?ie=UTF8&*Version*=1&*entries*=0)|$10.15



# Step 2: Connect the lights to the Farmduino

Farmduino provides multiple 12V outputs which can be used to power the LED lights.


Attach the wires to one of the 12V outputs, making sure the red wire is hooked up to the positive output, while the black wire is hooked up to the negative output. [These connectors](http://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml) can be used to attach peripherals to the Farmduino.

Take note of the pin number you are connecting to as it will be used to control the lights from the web app later. Peripheral 4 can be controlled with pin 10, and peripheral 5 can be controlled with pin 12 via the web app.




# Step 3: Mount or route the lights wherever desired

The LED strip we recommend purchasing is easily routed through the horizontal cable carrier supports as shown. This configuration will cast light down from the gantry onto your plants. If you would like to mount your lights elsewhere, you can use the included adhesive backing, zipties, double sided foam tape, or other means to secure the lights as desired.




# Step 4: Use the lights

In general there are two ways to use your newly installed LED lights:
## Method 1: Manually control the lights with the peripherals widget
From the **FarmBot Web App**, navigate to the **Controls** page. Click the **Edit** button in the header of the **Peripherals** widget. Create a new peripheral named "Lights" and assign it the pin number that you hooked the LED wires to on the Farmduino. Then click the **Save** button in the widget header and you will now have a shiny new toggle switch to operate your lights!

![Screen Shot 2017-02-27 at 2.47.36 PM.png](Screen_Shot_2017-02-27_at_2.47.36_PM.png)




## Method 2: Systematically use the lights in your sequences and regimens
Because your lights are hooked up to a peripheral on the Farmduino, you can easily create sequences that utilized the lights. Simply add a **Write Pin** step into your sequence to turn the lights on with a *pin value* of "ON" and off with a *pin value* of "OFF". Make sure you set the *pin mode* to "DIGITAL" and the *pin number* to whichever peripheral pin number you hooked up the wires to on the Farmduino.

![light_flash.png](light_flash.png)

