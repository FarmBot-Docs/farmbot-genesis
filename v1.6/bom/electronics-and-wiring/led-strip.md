---
title: "LED Strip"
slug: "led-strip"
description: "Tech specs for the LED strip in FarmBot Genesis. Visit [our shop](http://shop.farm.bot) to purchase parts."
---

* toc
{:toc}

# LED Strip

This LED strip is strung through the gantry's horizontal cable carrier supports so that you can light up your garden at night to show friends or for easy harvesting. Please note: this is not a "grow light".

![LED Strip](_images/led_strip.jpg)

specs:
  Light Color: White 6000K
  Strip Length: Genesis - 1.5m<br>Genesis XL - 3m
  Lead Length: 1m
  Cable Color: Black
  Connector: Black 2-pin ([Molex Part Number 151049-2206](https://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml))
price: 1.5m - $25.00<br>3m - $50.00
quantity: 1
internal-specs:
  Internal Part Name: Genesis: `24V LED Strip - 1.5m strip w/ 0.7m lead`<br>Genesis XL: `24V LED Strip - 3.0m strip w/ 0.7m lead`
  $/pc: Genesis (1.5m) - $6.00<br>Genesis XL (3m) - $11.00
  Notes: LED strip should NOT have an adhesive backing. Cut end must be dipped in silicon to seal.

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connector    |Connect the LED strip to a Farmduino peripheral plug.|Part should connect as expected|N/A
|Cable color  |Inspect the color of the cable.|Black|N/A
|Cable length |Measure the length of the cable using a measuring tape.|1m|+/- 20mm
|LED color    |Turn on an LED strip and inspect the color of the light.|Cool white (6000K)|N/A
|LED strip length|Measure the length of the LED strip using a measuring tape.|See BOM spec|+/- 30mm
|LED strip cut end|Inspect the cut end of the LED strip.|Cut end should be sealed with silicon rubber|N/A
|Double-sided tape|Inspect the LED strip for double-sided tape.|The part should not have any tape or other adhesives along its length|N/A