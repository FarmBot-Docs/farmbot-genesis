---
title: "Camera Cable"
slug: "camera-cable"
description: "This cable connects the camera to the Raspberry Pi through the y-axis cable carrier."
price: Genesis - $15.00<br>Genesis XL - $20.00
quantity:
  genesis: 1
  xl: 1
specs:
  Length: Genesis - 2.6m<br>Genesis XL - 4.1m
  Cable: Shielded 28AWG/1p+24AWG/2c<br><br>1p = 1 twisted pair (for data)<br>2c = 2 core (for power)
  Connector 1: 4-pin female waterproof 90 degree connector
  Connector 2: Right-angle USB Type A connector
internal-specs:
  Internal Part Name: Genesis - Camera Cable - 2.6m<br>Genesis XL - Camera Cable - 4.1m
  $/pc: Genesis (2.6m) - $3.50<br>Genesis XL (4.1m) - $4.30
  Notes: Cable must be shielded USB cable or there will be EMI issues.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length of the cable using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the diameter of the cable using digital calipers.|5mm|+/- 0.5mm
|Cable        |Inspect the spec of the cable.|Shielded 28AWG/1p+24AWG/2c<br><br>1p = 1 twisted pair (for data)<br>2c = 2 core (for power)|N/A
|Color        |Inspect the color of the cable.|Black|N/A
|Function     |Use the camera cable to connect a camera to a Raspberry Pi. Take a photo using the web app.|Image should be captured as expected|N/A
|90 degree connector|Connect the 90 degree connector to a camera and submerge into a cup of water. Take a photo using the web app.|The connector should make a waterproof connection, allowing an image to be captured as expected|N/A
|Electronics box fit|Connect the camera cable to the Raspberry Pi in a fully assembled electronics box.|Cable and connector should fit|N/A
