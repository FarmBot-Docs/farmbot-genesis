---
title: "Electronics Box"
slug: "electronics-box"
description: "Tech specs for the electronics box, push buttons, and LED indicators in FarmBot Genesis. Visit [our shop](http://shop.farm.bot) to purchase parts."
---

* toc
{:toc}

# Electronics Box

This rainproof box protects FarmBot's electronics from rain and debris. It features an easy-to-use tool-less double latch design for quickly opening and closing the box, a rubber gasket to keep moisture out, and a custom gland for all of FarmBot's cables to be passed through. The lid, latches, and box are made of UV stabilized materials.

{% include gallery.html images='
<iframe width="854" height="480" src="https://www.youtube.com/embed/r6vjSrMhUc0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
![Closed Electronics Box](_images/closed_electronics_box.jpg)
![Opened Electronics Box](_images/opened_electronics_box.jpg)
![Upright Electronics Box](_images/upright_electronics_box.jpg)
' %}

specs:
  Materials: Box, Lid, and Latches - UV stabilized ABS<br>Gasket and Supergland - Rubber<br>Screws and Nuts - Stainless steel
  Rainproof?: Yes
  Colors: Box - White<br>Lid - Frosted clear<br>Latches, Gasket, and Supergland - Black
  Cover Type: Hinged with latches
  Hinge Type: M3 x 35mm screws with locknuts
  Price: $95.00
  Quantity: 1
internal-specs:
  Internal Part Name: Genesis Electronics Box (Box) Rev A`<br>`Genesis Electronics Box (Lid) Rev A`<br>`Genesis Electronics Box (Gasket) Rev A`<br>`Genesis Electronics Box (Supergland) Rev A`<br>`Electronics Box (Latches) Rev A
  Vendor: 
  $/pc: Box - $10.60<br>Lid - $5.40<br>Gasket - $1.20<br>Supergland - $0.70<br>Latches - $0.80

# LED Indicator

These waterproof LED indicator lights come pre-mounted on the top of the electronics box. The blue light is reserved for connectivity status, the green light for sync status, and the two white lights are user-customizable. Each light includes a wiring harness and comes pre-connected to the Pi adapter board.

{% include gallery.html images="
![LED Indicators Front](_images/led_indicators_front.jpg)
![LED Indicators Back](_images/led_indicators_back.jpg)
![LED Indicator Wiring Harness](_images/led_indicator_wiring_harness.jpg)
![LED Indicators installed, eternal view](_images/push_buttons_installed_external_view.jpg)
![LED Indicators installed, internal view](_images/push_buttons_installed_internal_view.jpg)
" %}

specs:
  Color: Blue - 1<br>Green - 1<br>White - 2
  Material: Stainless steel and plastic
  Waterproof?: Yes
  O-Ring?: Included
  Wiring?: Included
  Price: $5.00
  Quantity: 4 total
internal-specs:
  Internal Part Name: Blue LED Indicator`<br>`Green LED Indicator`<br>`White LED Indicator
  Vendor: 
  $/pc: Indicator: $0.99<br>Wiring: $0.50

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Diameter     |Measure the diameter of the threaded section using digital calipers.|11.8mm|+/- 0.2mm
|Electronics box fit|Check fit in electronics box.|LED should fit with minimal play such that o-ring is guaranteed to seal.|N/A
|Length       |Measure the overall length using digital calipers.|24mm|+/- 1mm
|O-ring       |Inspect for the presence of an O-ring under the top flange.|Present|N/A
|Waterproof   |Drill a hole in a small plastic tub. Fasten the LED indicator to the hole and fill the tub with water.|The LED indicator should continue to operate when submerged, and prevent water from leaking.|N/A
|Wiring harness|Connect wiring harness between LED and Pi Adapter Board.|LED should work, harness should be of adequate length, and connectors should stay firmly attached.|N/A
|Material     |Ensure the material will not rust by holding a magnet to the part.|Stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.
|Illumination |Power on FarmBot.|The Sync and Connectivity indicators should be illuminated|N/A

# Push Button

These waterproof push buttons come pre-mounted on the top of the electronics box. The red button is reserved for E-STOP, the yellow for UNLOCK, and the three white ones are user-customizable. Each button includes a wiring harness and comes pre-connected to the Pi adapter board.

{% include gallery.html images="
![Push Buttons Front](_images/push_buttons_front.jpg)
![Push Buttons Back](_images/push_buttons_back.jpg)
![Push Button Wiring Harness](_images/push_button_wiring_harness.jpg)
![Push Buttons installed, external view](_images/push_buttons_installed_external_view.jpg)
![Push Buttons installed, internal view](_images/push_buttons_installed_internal_view.jpg)
" %}

specs:
  Color: Yellow - 1<br>Red - 1<br>White - 3
  Material: Stainless steel and plastic
  Waterproof?: Yes
  O-Ring?: Included
  Wiring?: Included
  Price: $7.00
  Quantity: 5 total
internal-specs:
  Internal Part Name: Yellow LED Push Button`<br>`Red LED Push Button`<br>`White LED Push Button
  Vendor: 
  $/pc: Button: $2.49<br>Wiring: $1.00

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Diameter     |Measure the diameter of the threaded section using digital calipers.|21.8mm|+/- 0.2mm
|Electronics box fit|Check fit in electronics box.|Button should fit with minimal play such that o-ring is guaranteed to seal.|N/A
|Length       |Measure the overall length using digital calipers.|40mm|+/- 1mm
|O-ring       |Inspect for the presence of an O-ring under the top flange.|Present|N/A
|Waterproof   |Drill a hole in a small plastic tub. Fasten the button to the hole and fill the tub with water.|The button should continue to operate when submerged, and prevent water from leaking.|N/A
|Wiring harness|Connect wiring harness between button and Pi Adapter Board.|Button should work, harness should be of adequate length, and connectors should stay firmly attached.|N/A
|Material     |Ensure the material will not rust by holding a magnet to the part.|Stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.
|Function     |Bind a button to a sequence and press the button.|FarmBot should execute the sequence|N/A
|Illumination |Power on FarmBot.|The E-stop button should be illuminated|N/A
