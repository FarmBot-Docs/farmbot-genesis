---
title: "Motors"
slug: "motors"
description: "These powerful 200 resolution stepper motors allow FarmBot to move precisely in the X, Y, and Z directions. Download the [motor spec sheet](https://drive.google.com/file/d/1Ehqu20q84Lyycn1fOj6dvWKbrMLvoNv4/view?usp=sharing) and [encoder spec sheet](https://drive.google.com/file/d/15dSqr_hQTXAQGIvw-YeDLIOC6dB0Y26n/view?usp=sharing)."
price: $60.00
quantity: 4
specs:
  Motor Resolution: 200 steps/revolution (1.8 deg/step)
  Winding Type: Bipolar
  Voltage: 12V
  Current Draw: 1.68A max
  Shaft Diameter: 5mm diameter
  Mount Hole Pattern: 4x M3 holes, standard NEMA 17 pattern
  Motor Connector: 6-pin connector (only 4 pins used)
  Encoder Connector: 8-pin connector
  Encoder Resolution: 360 lines/revolution
  Encoder Output: Differential
internal-specs:
  Internal Part Name: NEMA 17 Stepper Motor w/ Rotary Encoder
  Vendor: Motor - LDO<br>Encoder - Honest Sensor
  $/pc: $29.40
  Notes: Logo engraving must NOT be stretched. Please send photo of first samples to verify.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Motor length |Measure the length of the motor body (no encoder or shaft) using digital calipers.|47.3mm|+/- 0.5mm
|Motor housing fit|Mount a motor to the cross-slide plate with a horizontal motor housing.<br><br>Mount a motor to the z-axis motor mount and cover with the vertical motor housing.|Motor should fit inside housing|N/A
|Shaft        |Mount a GT2 pulley onto the motor shaft according to the FarmBot system design.|Pulley should mount as expected|N/A
|Shaft length |Measure the length of the motor shaft using digital calipers.|22mm|+/- 0.5mm
|Mounting holes|Mount a motor to a cross-slide plate according to the FarmBot system design.|Screws should thread into motor as expected|N/A
|Motor operation|Connect the motor to a Farmduino and issue a movement command.|Motor should operate as expected|N/A
|Encoder      |Connect the motor and encoder to a Farmduino, issue a movement command, and inspect the encoder position in the web app.|Encoder position values should update as expected|N/A
|Engraving    |Inspect the FarmBot logo engraving.|Must not be stretched|N/A
