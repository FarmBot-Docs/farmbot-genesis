---
title: "UTM Pin Mapping"
slug: "utm-pin-mapping"
description: "Pin mapping for the FarmBot Genesis UTM"
---

|UTM Pin|UTM Wire                                      |Farmduino Pin                |Use         |
|-------|----------------------------------------------|-----------------------------|------------|
|**A**  |<span class="cable-color red">red</span>      |+5V                          |Soil sensor power
|**B**  |<span class="cable-color yellow">yellow</span>|GND (0V)                     |Ground
|**C**  |<span class="cable-color green">green</span>  |D63 - Digital-In             |Tool verification
|**D**  |<span class="cable-color black">black</span>  |D59 (A5) - Analog-In         |Soil sensor readings
|**E**  |<span class="cable-color white">white</span>  |BDC2 (GND or 24V via DRV8876)|Rotary tool motor
|**F**  |<span class="cable-color brown">brown</span>  |---                          |---
|**G**  |<span class="cable-color blue">blue</span>    |---                          |---
|**H**  |<span class="cable-color grey">grey</span>    |BDC1 (GND or 24V via DRV8876)|Rotary tool motor
|**I**  |<span class="cable-color orange">orange</span>|---                          |I2C SCL
|**J**  |<span class="cable-color purple">purple</span>|---                          |I2C SDA
|**K**  |<span class="cable-color pink">pink</span>    |---                          |---
|**L**  |<span class="cable-color cyan">cyan</span><br>(shunted to shield with dark gray heatshrink)|PE|Protected Earth ground
