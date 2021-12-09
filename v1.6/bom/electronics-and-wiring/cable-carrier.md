---
title: "Cable Carrier"
slug: "cable-carrier"
description: "Tech specs for the cable carrier in FarmBot Genesis. Visit [our shop](http://shop.farm.bot) to purchase parts."
---

* toc
{:toc}

# Cable Carrier

These hollow plastic chains are used throughout FarmBot to manage cables and tubing along each of the three axes.

![Cable Carrier](_images/cable_carrier.jpg)

## Specs

specs:
  Material: Black Nylon PA66
  Lengths: enesis**<br>X-Axis - 1.7m (85 links) + end pieces<br>Y-Axis - 1.7m (85 links) + end pieces<br>Z-Axis - 0.74m (37 links) + end pieces<br><br>**Genesis XL**<br>X-Axis - 3.2m (160 links) + end pieces<br>Y-Axis - 3.2m (160 links) + end pieces<br>Z-Axis - 0.74m (37 links) + end pieces
  Inside Height: 15mm
  Inside Width: X-Axis - 20mm<br>Y-Axis - 50mm<br>Z-Axis - 50mm
  Outside Height: 20mm
  Outside Width: X-Axis - 30mm<br>Y-Axis - 60mm<br>Z-Axis - 60mm
  Pitch: 20mm
  Bending Radius: 28mm
  End Piece Configuration: X-Axis - `X configuration` (see image below)<br>Y-Axis - `Y configuration` (see image below)<br>Z-Axis - `Z configuration` (see image below)
price: enesis**<br>X-Axis - $50.00<br>Y-Axis - $50.00<br>Z-Axis - $30.00<br><br>**Genesis XL**<br>X-Axis - $80.00<br>Y-Axis - $80.00<br>Z-Axis - $30.00
quantity: 1 for each axis
internal-specs:
  Internal Part Name: enesis**<br>X-Axis - `15 x 20 x 1700mm (85 links + end pieces in X configuration)`<br>Y-Axis - `15 x 50 x 1700mm (85 links + end pieces in Y configuration)`<br>Z-Axis - `15 x 50 x 740mm (37 links + end pieces in Z configuration)`<br><br>**Genesis XL**<br>X-Axis - `15 x 20 x 3200mm (160 links + end pieces in X configuration)`<br>Y-Axis - `15 x 50 x 3200mm (160 links + end pieces in Y configuration)`<br>Z-Axis - `15 x 50 x 740mm (37 links + end pieces in Z configuration)`
  Vendor: JFLO
  Vendor Part Number: enesis and Genesis XL**<br>X-Axis - `J15BF.1.20N R28`<br>Y-Axis - `J15BF.1.50N R28`<br>Z-Axis - `J15BF.1.50N R28`
  $/pc: enesis**<br>X-Axis - $11.20<br>Y-Axis - $13.10<br>Z-Axis - $5.90<br><br>**Genesis XL**<br>X-Axis - $19.90<br>Y-Axis - $24.50<br>Z-Axis - $5.90

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Size         |Inspect the size marking embossed into the plastic.|See BOM spec|N/A
|Length       |Measure the length of the cable carrier using a measuring tape.|See BOM spec|0
|End pieces   |Inspect the orientation of the end pieces.|Oriented according to FarmBot system design|N/A
|Mount fit    |Connect the end pieces to the appropriate cable carrier mounts/supports using the appropriate hardware.|Should fit as expected|N/A
|Contents fit |Inert all cables and tubing into each cable carrier according to FarmBot system design.|Should fit as expected|N/A

## End piece configuration

{%
include callout.html
type="info"
title="Configuration of the end pieces"
content="The images below labelled `X-Axis`, `Y-Axis`, and `Z-Axis` illustrate the configuration of the end pieces. They are not representative of the actual length of the cable carriers."
%}

{% include gallery.html images="
![End pieces configuration - X](_images/cable_carrier_end_piece_configuration_x.jpg)
![End pieces configuration - Y](_images/cable_carrier_end_piece_configuration_y.jpg)
![End pieces configuration - Z](_images/cable_carrier_end_piece_configuration_z.jpg)
" %}