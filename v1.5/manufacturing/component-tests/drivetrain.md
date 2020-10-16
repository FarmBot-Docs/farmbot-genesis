---
title: "Drivetrain Tests"
slug: "drivetrain"
---

* toc
{:toc}

Each component in the drivetrain category has its own unique tests.

# V-wheel

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Outer diameter|Measure the outer diameter of the v-wheel with digital calipers.|23.89mm|+/- 0.1mm
|Inner diameter|Measure the inner diameter of the v-wheel (where the bearings will sit) with digital calipers.|15.974|+/- 0.05mm
|Width        |Measure the width of the v-wheel with digital calipers.|10.23mm|+/- 0.1mm
|Smoothness   |Inspect the wheel to ensure there are no eroneous grooves, cuts, or knicks|No blemishes|N/A

# GT2 Timing Belt

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length of the belt using a measuring tape.|See BOM spec.|+/- 1cm
|Width        |Measure the width of the belt using digital calipers.|5mm|+/- 0.25mm
|Pitch        |Measure the distance between one tooth and another one 50 teeth away using digital calipers, then divide by 50.|2mm|+/- 0.02mm (1%)
|Thickness    |Measure the thickness of the belt using digital calipers.|0.75mm|+/- 0.05mm
|Stretchiness |Tie a belt to a fixture 1.5m or more off the ground. Mark the belt just below the knot and then add a second mark exactly 1000mm below the first. Hang a 10kg weight from the belt (below the 1000mm mark) and measure the distance between the two marks.|1000m|+ 10mm (1%)
|Strength     |Use a tensile testing machine to measure the equivalent hung weight at which the belt will break.|100kg|- 20kg
|Color        |Inspect the belt for any discoloration or markings|Black, no markings.|N/A

# GT2 Pulley

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Number of teeth|Count the number of teeth on the pulley.|20|+/- 0
|Pitch        |Mate the pulley with a belt and inspect tooth engagement|The pulley should fully engage the belt's teeth at all points of contact.|N/A
|Tooth width  |Measure the width of the teeth using digital calipers.|7mm|+/- 0.5mm
|Overall length|Measure the overall length using digital calipers.|14mm|+/- 0.5mm
|Outer Diameter|Measure using digital calipers.|15mm|+/- 0.5mm
|Hole diameter|Measure the diameter of the motor shaft hole using digital calipers.|5mm|+ 0.05mm
|Number of setscrews|Count the number of setscrews.|2|N/A
|Setscrew drive size|Use a hex driver to validate the drive size of the setscrews.|2mm|N/A
|Material     |Ensure the material is aluminum and stainless steel and will not rust by holding a magnet to the part.|Aluminum and stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.

# Belt Sleeve

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Inner width  |Measure using digital calipers.|7.5mm|+/- 0.1mm
|Inner height |Measure using digital calipers.|2.15mm|+/- 0.05mm
|Outer width  |Measure using digital calipers.|10mm|+/- 0.2mm
|Outer height |Measure using digital calipers.|5mm|+/- 0.2mm
|Length       |Measure using digital calipers.|10mm|+/- 0.5mm
|Material     |Ensure the material is aluminum and will not rust by holding a magnet to the part.|Aluminum (no magnetic attraction)|N/A
|Sandblasting |Inspect for thorough sandblasting coverage.|100%|-1%
|Anodization  |Inspect for thorough annodization coverage.|100%|-1%
|Deburred     |Inspect for burrs.|No burrs|0

# 5mm to 8mm Shaft Coupling

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Inner diameters|Measure using digital calipers.|5mm and 8mm|+/- 0.05mm
|Outer diameter|Measure using digital calipers.|18mm|+/- 0.5mm
|Length       |Measure using digital calipers.|25mm|+/- 0.5mm
|Setscrew drive size|Use a hex driver to validate the drive size of the setscrews.|2mm|N/A
|Material     |Ensure the material is aluminum or stainless steel and will not rust by holding a magnet to the part.|Aluminum and stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.
|Fits motor shaft|Connect the coupling to a motor shaft.|The coupling should be easy to connect and resist pulling off by hand once tightened.|N/A
|Fits leadscrew|Connect the coupling to a leadscrew.|The coupling should be easy to connect and resist pulling off by hand once tightened.|N/A

# Leadscrew

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|800mm|+/- 3mm
|Threads      |Thread the leadscrew into the delrin leadscrew block.|The leadscrew should thread as expected without significant resistance.|N/A
|Straightness |Place the leadscrew on a reference table with a flatness tolerance of 0.5mm per 1m or better.|0mm deviation|+ 2mm
|Deburred     |Inspect for burrs, especially on the cut ends.|No burrs|0
|Material     |Ensure the material is stainless steel and will not rust by holding a magnet to the part.|Stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.

# Leadscrew Block

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Size         |Measure the outer dimensions of the block with digital calipers.|34mm x 20mm x 12mm|+/- 0.5mm
|Threads      |Thread a leadscrew into the block.|The leadscrew should thread as expected without significant resistance.|N/A
|Hole diameter|Measure the hole diameter using digital calipers|5.25mm|+/- 0.1mm
|Hole spacing |Attach the block to a cross-slide plate according to the FarmBot system design.|The block should attach without screw/hole interference.|N/A
