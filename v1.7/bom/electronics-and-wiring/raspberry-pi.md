---
title: "Raspberry Pi"
slug: "raspberry-pi"
description: "This is the host computer of FarmBot. You might also call it FarmBot's brain. The Raspberry Pi runs FarmBot OS, communicates with the web application over ethernet or WiFi, and talks to the Farmduino over a USB serial connection."
cad: https://cad.onshape.com/documents/6626b842adca229e69544ad1/w/89ac2637f82d915f22c2bcd0/e/661f37ce8520518d51f10769
price: $50.00
quantity:
  standard: 1
  xl: 1
specs:
  Model: 3B+ (prior to July 2022)<br>4B - 1GB(July 2022 to December 2022)<br>4B - 2GB (January 2023 and later)
  CPU: 1.4Ghz Quad Core (prior to July 2022)<br>1.5Ghz Quad Core (July 2022 and later)
  RAM: 1GB (prior to January 2023)<br>2GB (January 2023 and later)
  WiFi: 2.4GHz Dual-Band 802.11ac (prior to July 2022)<br>2.4 GHz and 5.0 GHz 802.11b/g/n/ac (July 2022 and later)
  Ethernet: 1000
  USB: 4x USB 2.0 ports (prior to July 2022)<br>2x USB 3.0 and 2x USB 2.0 (July 2022 and later)
  Storage: MicroSD
  GPIO: 40-pin header
internal-specs:
  internal-part-name: Raspberry Pi 3B+ (production 1)<br>Raspberry Pi 4B - 1GB (production 2)<br>Raspberry Pi 4B - 2GB (production 3)
  cost: $95.00
  notes: Cost was $46.90 for production 1,$95.00 for production 2, and $45.00 for production 3
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Model        |Inspect the board for model number.|`Model 4B`|N/A
|Brand        |Inspect the board for the brand name.|`Raspberry Pi`|N/A
|Condition    |Inspect to ensure the product is not used or refurbished.|Product should be brand new|N/A
|GPIO pins    |Inspect the GPIO pins for damage.|No pins should be bent|N/A

{%
include callout.html
type="info"
title="Some v1.6 kits include different Raspberry Pi models"
content="Genesis and Genesis XL v1.6 kits shipped before July of 2022 included the Raspberry Pi Model 3B+, kits shipped during or after July of 2022 included the Raspberry Pi Model 4B - 1GB, and kits shipped in January 2023 and later included the Raspberry Pi Model 4B - 2GB."
%}