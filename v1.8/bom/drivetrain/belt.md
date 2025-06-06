---
title: "Belt"
slug: "belt"
description: "Tech specs for the belts in FarmBot Genesis. Visit [our shop](http://shop.farm.bot) to purchase parts."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/e5135dbeb93a2518b9691de0?configuration=List_5lsI64D1Sj098C%3DY_Axis%3BList_MZgFp5WPsrheRr%3DDefault&renderMode=0&uiState=6255c6a046b4a5023f0a83cd
variants: 1.7m|3.2m|4.5m|7.5m
price: $20.00|$30.00|$40.00|$70.00
quantity:
  standard: 1|0|2|0
  xl: 0|1|0|2
specs:
  material: Neoprene with fiberglass cords
  length: 1.7m|3.2m|4.5m|7.5m
  Width: 5.8 to 6.0mm
  thickness: 1.25mm
  Pitch: GT2 (2mm)
  color: Black (no markings)
internal-specs:
  internal-part-name: GT2 Timing Belt - [length]
  cost: $1.10|$2.10|$2.90|$4.70
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length of the belt using a measuring tape.|See BOM spec.|+/- 1cm
|Width        |Measure the width of the belt using digital calipers.|5.8mm|+/- 0.2mm
|Extrusion fit|Lay the belt into the V-slot of an extrusion.|The belt should pass through the narrowest section and lay flat in the bottom of the slot.|N/A
|Pitch        |Measure the distance between one tooth and another one 50 teeth away using digital calipers, then divide by 50.|2mm|+/- 0.02mm (1%)
|Pulley fit   |Engage the belt to a GT2 pulley.|The belt should fully engage with the pulley's teeth.|N/A
|Thickness    |Measure the thickness of the belt using digital calipers.|1.25mm|+/- 0.1mm
|Belt sleeve fit|Assemble the belt to a belt clip and secure with a belt sleeve.|The belt sleeve should fit snugly over the two belt sections and provide adequate holding force.|N/A
|Stretch      |Tie a belt to a fixture 1.5m or more off the ground. Mark the belt just below the knot and then add a second mark exactly 1000mm below the first. Hang a 10kg weight from the belt (below the 1000mm mark) and measure the distance between the two marks.|1000m|+ 10mm (1%)
|Strength     |Use a tensile testing machine to measure the equivalent hung weight at which the belt will break.|100kg|- 20kg
|Color        |Inspect the belt for any discoloration or markings|Black, no markings.|N/A
{:.internal}
