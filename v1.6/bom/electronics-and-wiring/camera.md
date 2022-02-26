---
title: "Camera"
slug: "camera"
description: "The camera is mounted on the z-axis and allows FarmBot to take photos of the garden and plants for weed detection and tracking plant growth."
price: $30.00
quantity:
  standard: 1
  xl: 1
specs:
  resolution: 0.3MP
  waterproof?: Yes
  focal distance: 0.5m (custom set)
  outer diameter: 9mm
  camera length: 38mm
  cable: Shielded 28AWG/1p + 24AWG/2c<br><br>1p = 1 twisted pair (for data)<br>2c = 2 core (for power)
  cable length: 1m
  connector: 4-pin male 90 degree waterproof connector
  label: CAM
internal-specs:
  internal part name: Camera
  rev: B
  vendor: Shibang
  cost: $19.90
  notes: Inspect the camera module to ensure there are no obstructions in front of the lens, such as foam or glue.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Resolution   |Take a photo and inspect the resolution.|1.3MP|N/A
|Focus        |Take a photo of an object 50cm away.|The object should appear sharp|N/A
|Diameter     |Measure the diameter of the camera module using digital calipers.|11mm|+/- 0.5mm
|Mount compatibility|Mount the camera to an extrusion using two camera mount halves.|The camera should be able to be firmly mounted in place|N/A
|Function     |Connect the camera to a Raspberry Pi using a Genesis XL camera cable and take a photo from the FarmBot web app.|Photo taking should work as expected (no black images, no failures)|N/A
|Camera module length|Measure the length of the camera module using digital calipers.|38mm|+/- 2mm
|Cable        |Inspect the spec of the cable.|`Shielded 28AWG/1p + 24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Cable length |Measure the length of the cable using a tape measure.|1m|+/- 2cm
|Label        |Inspect the connector end for the label.|Should be labeled "CAM"|N/A
|Sealing      |Inspect the sealing where the cable enters the camera module housing.|The cable should be well sealed|N/A
|Lens         |Inspect the camera lens for obstructions and straightness.|The camera lens should be free of obstructions and point straight out of the camera module.|N/A
|Color        |Inspect the color of the cable.|Black|N/A
