---
title: "Plastic Parts"
slug: "plastic-parts"
description: "Tech specs for the plastic parts in FarmBot Genesis. Visit [our shop](http://shop.farm.bot) to purchase parts."
---

* toc
{:toc}

|Component|$/Unit|Genesis Qty|Genesis Subtotal|XL Qty|XL Subtotal|MAX Qty|MAX Subtotal|
|---------|------|-----------|----------------|------|-----------|-------|------------|
|[40mm Horizontal Cable Carrier Support](plastic-parts/cable-carrier-supports.md#40mm-horizontal-cable-carrier-support)|$3.00|12|$36.00|24|$72.00|72|$216.00
|[60mm Horizontal Cable Carrier Support](plastic-parts/cable-carrier-supports.md#60mm-horizontal-cable-carrier-support)|$3.00|6|$18.00|12|$36.00|12|$36.00
|[60mm Vertical Cable Carrier Support](plastic-parts/cable-carrier-supports.md#60mm-vertical-cable-carrier-support)|$3.00|4|$12.00|4|$12.00|4|$12.00
|[60mm Cable Carrier Spacer Block](plastic-parts/cable-carrier-supports.md#60mm-cable-carrier-spacer-block)|$3.00|1|$3.00|1|$3.00|1|$3.00
|[75mm Horizontal Motor Housing](plastic-parts/motor-housings.md#75mm-horizontal-motor-housing)|$10.00|3|$30.00|3|$30.00|3|$30.00
|[80mm Vertical Motor Housing](plastic-parts/motor-housings.md#80mm-vertical-motor-housing)|$12.00|1|$12.00|1|$12.00|1|$12.00
|[Camera Mount Half](plastic-parts/camera-mount.md#camera-mount-half)|$3.00|2|$6.00|2|$6.00|2|$6.00
|[Seeder](plastic-parts/seeder.md#seeder)|$7.00|1|$7.00|1|$7.00|1|$7.00
|[Seed Bin](plastic-parts/seed-containers.md#seed-bin)|$7.00|1|$7.00|1|$7.00|1|$7.00
|[Seed Tray](plastic-parts/seed-containers.md#seed-tray)|$7.00|2|$14.00|2|$14.00|2|$14.00
|[Seed Trough](plastic-parts/seed-containers.md#seed-trough)|$3.00|2|$6.00|2|$6.00|2|$6.00
|[Seed Trough Holder](plastic-parts/seed-containers.md#seed-trough-holder)|$8.00|1|$8.00|1|$8.00|1|$8.00
|[Soil Sensor](plastic-parts/soil-sensor.md#soil-sensor)|$7.00|1|$7.00|1|$7.00|1|$7.00
|[Solenoid Valve Mount](plastic-parts/solenoid-valve-mount.md#solenoid-valve-mount)|$6.00|1|$6.00|1|$6.00|1|$6.00
|[Universal Tool Mount](plastic-parts/utm.md#universal-tool-mount)|$30.00|1|$30.00|1|$30.00|1|$30.00
|[Vacuum Pump Housing](plastic-parts/vacuum-pump.md#vacuum-pump-housing)|$15.00|1|$15.00|1|$15.00|1|$15.00
|[Vacuum Pump Mount](plastic-parts/vacuum-pump.md#vacuum-pump-mount)|$6.00|1|$6.00|1|$6.00|1|$6.00
|[Watering Nozzle Top](plastic-parts/watering-nozzle.md#watering-nozzle-top)|$7.00|1|$7.00|1|$7.00|1|$7.00
|[Watering Nozzle Bottom](plastic-parts/watering-nozzle.md#watering-nozzle-bottom)|$5.00|1|$5.00|1|$5.00|1|$5.00
|[Weeder](plastic-parts/weeder.md#weeder)|$7.00|1|$7.00|1|$7.00|1|$7.00
|[Weeder Blades](plastic-parts/weeder.md#weeder-blades)|$2.00|12|$24.00|12|$24.00|12|$24.00
|**TOTALS**||**53**|**$246.00**|**71**|**$300.00**|**119**|**$444.00**

<iframe width="854" height="480" src="https://www.youtube.com/embed/ODUmjM1LhTA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Component tests

## Size and shape

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Overall size |Measure the overall length, width, and height with digital calipers.|See spec in CAD models.|+/- 0.5mm
|M3 hole size |Measure the diameter of M3 holes using digital calipers.|3.25mm nominal|+/- 0.1mm
|M5 hole size |Measure the diameter of M5 holes using digital calipers.|5.25mm nominal|+/- 0.1mm
|Injection completeness|Inspect part to ensure injection process completed without air pockets.|100%|- 1%
|Shrink       |Inspect part for shrinkage.|No shrunken spots|Minor shrink on non-critical faces is permissible
|Ejector pins |Inspect ejector pin sites for dimensionally significant artifacts.|0mm deviation from intended shape|+/- 0.2mm

## Material and appearance

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Color        |Inspect parts for discoloration.|See part spec|N/A
|Surface texture|Inspect for thorough texture coverage on applicable surfaces.|100%|- 1%

## Function

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Brass inserts|Check for presence and size of brass inserts.|All inserts must be present and of the correct threads and depth.|N/A
|M3 screws    |Insert M3 screws into M3 holes to ensure fit.|Screws should be insertable without interference.|N/A
|M5 screws    |Insert M5 screws into M5 holes to ensure fit.|Screws should be insertable without interference.|N/A
|Nut bars     |Fasten nut bars of appropriate lengths between holes according to FarmBot system design.|Nut bars should be fastenable without screw/hole interference.|N/A
|Extrusion fit|Fasten part to an extrusion according to FarmBot system design.|Part should mate with extrusion slot as intended.|N/A
|Cable carrier fit|Fasten cable carrier end pieces to cable carrier supports.|End pieces should fasten flush to mounting surface and have adequate clearance on sides.|N/A
|Vacuum pump fit|Fasten together the vacuum pump, vacuum pump mount, vacuum pump housing, and the z-axis extrusion according to the FarmBot system design.|The vacuum pump and mount should fit inside the housing without interference.|N/A
