---
title: "Electronics"
slug: "electronics"
description: "Documentation for FarmBot Genesis V0.8 Electronics"
---

* toc
{:toc}

V0.8 hardware integrates [Rotary Encoders](http://wiki.farmbot.cc/wiki/Rotary_Encoders) onto the back of each of the stepper motors. This is important to ensure that FarmBot always knows where it is in the circumstances when it has been inadvertently moved (by kids or pets) or it tries to move but is prevented from doing so due to some obstruction (rocks, branches, kids, pets). Unfortunately, there are no readily accessible add-on rotary encoders from popular sites like Adafruit or Sparkfun (as of September 2014), however, there are a handful of companies who do produce small, add-on encoders that mount nicely to the back panel of the stepper motor and hook onto a second shaft coming from the motor. The encoders modeled in the renderings below are based on those offered by [Schneider Electric](http://motion.schneider-electric.com/downloads/datasheets/17_mtr.pdf).

As of prototpying V0.8 hardware, low-cost rotary encoders have not yet been found or tested. Furthermore, the Arduino firmware does not yet support closed-loop feedback control.

# Bill of Materials



|Part Name                     |Description                   |Source                        |$/unit                        |Qty.                          |Subtotal                      |
|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|------------------------------|
|Host Computer                 |Raspberry Pi 2 Model B        |[Adafruit](http://adafruit.com)|$40.00                        |1                             |$40.00
|Microcontroller and Stepper Drivers|Arduino Mega 2560 R3, RAMPS shield, Pololu Stepper Drivers, USB cable|[Sainsmart](http://sainsmart.com)|$49.99                        |1                             |$49.99
|Power Supply                  |12V, 30Amp Output             |[OpenBuilds](http://openbuildspartstore.com)|$35.00                        |1                             |$35.00
|5V power adapter              |UBEC DC/DC Step-Down (Buck) Converter - 5V @ 3A output|[Adafruit](http://www.adafruit.com/products/1385)|$9.95                         |1                             |$9.95
|Electronics Housing           |Waterproof                    |[McMaster Carr](http://mcmaster.com)|$32.34                        |1                             |$32.34
|M5x10mm Screws                |M5 machine screws, 10mm length, 0.8 thread pitch, low-profile 3mm hex heads|[McMaster Carr](http://mcmaster.com)|$0.18                         |2                             |$0.36
|Tee Nuts                      |Stainless steel, for attaching M5 screws to OpenBuilds aluminum extrusions|                              |$0.30                         |2                             |$0.60
|                              |                              |                              |                              |Total                         |$169.64



{%
include callout.html
type="success"
title="We sell parts too"
content="Make sure to check out our [FarmBot Shop](http://go.farmbot.it/shop/) to purchase premium quality components that you can be sure will work with your hardware."
%}

