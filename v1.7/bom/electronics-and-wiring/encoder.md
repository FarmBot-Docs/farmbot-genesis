---
title: "Encoder"
slug: "encoder"
description: "These rotary encoders provide closed-loop feedback of the motor positions in realtime, allowing FarmBot to perform automatic homing and calibration, and detect stalls. Download the [encoder spec sheet](https://drive.google.com/file/d/15dSqr_hQTXAQGIvw-YeDLIOC6dB0Y26n/view?usp=sharing)."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/721ea5b310ba257b355c62ae?renderMode=0&uiState=6255db2446b4a5023f0ae580
price: $0.00
quantity:
  standard: 4
  xl: 4
specs:
  connector: 8-pin connector
  resolution: 360 lines/revolution
  output: Differential
internal-specs:
  internal-part-name: NEMA 17 Stepper Motor w/ Rotary Encoder
  vendor: Honest Sensor
  cost: $0.00
  notes: "---"
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Motor housing fit|Mount a motor to the cross-slide plate with a horizontal motor housing.<br><br>Mount a motor to the z-axis motor mount and cover with the vertical motor housing.|Motor should fit inside housing|N/A
|Encoder      |Connect the motor and encoder to a Farmduino, issue a movement command, and inspect the encoder position in the web app.|Encoder position values should update as expected|N/A
