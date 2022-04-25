---
title: "Electronics and Wiring"
slug: "electronics-and-wiring"
description: "Tech specs for the electronics and wiring in FarmBot Genesis. Visit [our shop](http://shop.farm.bot) to purchase parts."
---


|Qty.                          |Component                     |$/Unit                        |Subtotal                      |
|------------------------------|------------------------------|------------------------------|------------------------------|
|1                             |[Electronics Box](#electronics-box)|$95.00                        |$95.00
|1                             |[Electronics Mounting Plate](#electronics-mounting-plate)|$15.00                        |$15.00
|1                             |[Power Supply](#power-supply)|$60.00                        |$60.00
|1                             |[Raspberry Pi 3](#raspberry-pi-3)|$40.00                        |$40.00
|1                             |[MicroSD Card](#microsd-card)|$15.00                        |$15.00
|1                             |[Farmduino](#farmduino)|$90.00                        |$90.00
|5                             |[Stepper Drivers](#stepper-drivers)|$6.00                         |$30.00
|1                             |[Raspberry Pi Power Cable](#raspberry-pi-power-cable)|$5.00                         |$5.00
|1                             |[Farmduino Data Cable](#farmduino-data-cable)|$5.00                         |$5.00
|1                             |[USB Adapter Cable](#usb-adapter-cable)|$5.00                         |$5.00
|12                            |[Jumper Wires](#jumper-wires)|$0.25                         |$3.00
|4                             |[NEMA 17 Stepper Motors with Rotary Encoders](#nema-17-stepper-motors-with-rotary-encoders)|$60.00                        |$240.00
|4                             |[Motor Cables](#motor-cables)|$20.00                        |$80.00
|4                             |[Encoder Cables](#encoder-cables)|$25.00                        |$100.00
|2                             |[1.7m Cable Carriers](#17m-cable-carrier)|$50.00                        |$100.00
|1                             |[0.74m Cable Carrier](#074m-cable-carrier)|$30.00                        |$30.00
|1                             |[Universal Tool Mount Cable](#universal-tool-mount-cable)|$35.00                        |$35.00
|1                             |[Soil Sensor PCB](#soil-sensor-pcb)|$6.00                         |$6.00
|3                             |[Soil Sensor Jumpers](#soil-sensor-jumpers)|$0.50                         |$1.50
|1                             |[Solenoid Valve](#solenoid-valve)|$8.00                         |$8.00
|1                             |[Vacuum Pump](#vacuum-pump)|$15.00                        |$15.00
|1                             |[Vacuum Pump Cable](#vacuum-pump-cable)|$15.00                        |$15.00
|1                             |[Solenoid Valve Cable](#solenoid-valve-cable)|$15.00                        |$15.00
|1                             |[Borescope Camera](#borescope-camera)|$35.00                        |$35.00
|4                             |[Jumper Links](#jumper-links)|$0.25                         |$1.00
|1                             |[LED Strip](#led-strip)|$25.00                        |$25.00
|**56**                        |**TOTALS**                    |                              |**$1,069.50**

# Electronics Box
This rainproof box protects FarmBot's electronics from rain and debris. It features an easy-to-use tool-less double latch design for quickly opening and closing the box, a rubber gasket to keep moisture out, and a custom gland for all of FarmBot's cables to be passed through. The lid, latches, and box are made of UV stabilized materials.

|                              |                              |
|------------------------------|------------------------------|
|**Materials**                 |Box - Delrin 127 UV (Natural Acetal Homopolymer)<br>Lid - Makrolon 2407-550115 (Clear PC)<br>Latches - Lexan 925U-701 (Black PC)<br>Gasket - Santoprene 111-35 (Black TPV)<br>Supergland - Santoprene 111-35 (Black TPV)<br>Screws and Nuts - 18/8 Stainless Steel
|**Rainproof?**                |Yes
|**Colors**                    |Box - White<br>Lid - Bluish Clear<br>Latches - Black<br>Gasket - Black<br>Supergland - Black
|**Outer Dimensions**          |
|**Inner Dimensions**          |
|**Cover Type**                |Hinged with latches
|**Hinge Type**                |18/8 M3 x 35mm screws with locknuts
|**Price**                     |$95.00
|**Quantity**                  |1

{% include gallery.html images="
![v1.3-Electronics-Box-1.jpg](_images/v1.3-Electronics-Box-1.jpg)
![v1.3-Electronics-Box-2.jpg](_images/v1.3-Electronics-Box-2.jpg)
![v1.3-Electronics-Box.jpg](_images/v1.3-Electronics-Box.jpg)
" %}

# Electronics Mounting Plate
This acrylic plate allows you to mount the v1.3 Farmduino and Raspberry Pi 3 into the v1.3 Electronics Box. Note: the plate comes with a brown protective film which you can peel off to reveal the clear acrylic.

|                              |                              |
|------------------------------|------------------------------|
|**Material**                  |Acrylic
|**Color**                     |Clear
|**Quantity**                  |1
|**Price**                     |$15.00



![v1.3-Electronics-Mounting-Plate.jpg](_images/v1.3-Electronics-Mounting-Plate.jpg)

# Power Supply
This universal input IP67 waterproof power supply provides FarmBot with all the electricity it needs.

|                              |                              |
|------------------------------|------------------------------|
|**Output Power**              |12 volt, 12.5 amp DC split among 2 channels
|**Output Cable**              |Two 4m long 2-core 16 AWG black cables with one [Molex Part Number 39-01-3045 Connector](https://www.molex.com/molex/products/datasheet.jsp?part=active/0039013045_CRIMP_HOUSINGS.xml)
|**Input Power**               |110 or 220 volt AC
|**Input Cable**               |0.3m long black cable with standard US 3-prong plug
|**Waterproof Rating**         |IP67
|**Brand**                     |Weho
|**Dimensions**                |
|**Price**                     |$60.00
|**Quantity**                  |1

{% include gallery.html images="
![PSU1.JPG](_images/PSU1.JPG)
![PSU.JPG](_images/PSU.JPG)
![PSU2.JPG](_images/PSU2.JPG)
" %}

# Raspberry Pi 3
This is the "host computer" of FarmBot. You might also call it FarmBot's brain. The Raspberry Pi runs FarmBot OS, communicates with the web application over ethernet or WiFi, and talks to the Farmduino over a USB serial connection.

|                              |                              |
|------------------------------|------------------------------|
|**CPU**                       |1.2Ghz Quad Core Broadcom BCM2837 64-bit ARMv8 processor
|**RAM**                       |1GB LPDDR2 (900 MHz)
|**WiFi**                      |2.4GHz 802.11n wireless, BCM43143 chip
|**Bluetooth**                 |Bluetooth 4.1 Classic, Bluetooth low energy (BLE)
|**Ethernet**                  |Built-in 10/100 Ethernet
|**USB**                       |4x USB 2.0 ports
|**Storage**                   |MicroSD
|**GPIO**                      |40-pin header
|**Price**                     |$40.00
|**Quantity**                  |1



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FjF8q6WAS-rU%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DjF8q6WAS-rU&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FjF8q6WAS-rU%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

{% include gallery.html images="
![Pi.JPG](_images/Pi.JPG)
![Pi 2.JPG](_images/Pi_2.JPG)
![Pi 3.JPG](_images/Pi_3.JPG)
" %}

# MicroSD Card
The microSD card holds FarmBot OS and is inserted into the Raspberry Pi.

|                              |                              |
|------------------------------|------------------------------|
|**Form Factor**               |MicroSD
|**Capacity**                  |8GB
|**Brand**                     |SanDisk
|**Price**                     |$15.00
|**Quantity**                  |1



![MicroSD.JPG](_images/MicroSD.JPG)

# Farmduino
The Farmduino is an electronics board that combines the functionality of an Arduino MEGA 2560 microcontroller and a RAMPS shield. It features a board layout and connectors that are optimized for FarmBot. It receives G-code commands from the Raspberry Pi and then moves the motors, reads sensors, activate peripherals, and more.

{%
include callout.html
type="success"
title="Farmduino is open-source"
content="[Click here to download](https://drive.google.com/drive/folders/0B-wExYzQcnp3V3lwcGFuQURsWGc?usp=sharing) the Farmduino schematic, board layout, and source files. Please note: you will need Adobe Acrobat to view the 3D PDF of the board layout."
%}



|                              |                              |
|------------------------------|------------------------------|
|**Microcontroller**           |ATmega2560
|**Input Voltage**             |12V
|**Power Connector**           |[Molex Part Number 46207-0004](https://www.molex.com/molex/products/datasheet.jsp?part=active/0462070004_PCB_HEADERS.xml)
|**Peripheral Connectors**     |[Molex Part Number 151048-1206](https://www.molex.com/molex/products/datasheet.jsp?part=active/1510481206_PCB_HEADERS.xml)
|**DC Current per I/O Pin**    |40 mA
|**DC Current for 3.3V Pin**   |50 mA
|**Flash Memory**              |256 KB (8 KB used by bootloader)
|**SRAM**                      |8 KB
|**EEPROM**                    |4 KB
|**Clock Speed**               |16 MHz
|**Price**                     |$90.00
|**Quantity**                  |1

{% include gallery.html images="
![Farmduino.JPG](_images/Farmduino.JPG)
![Farmduino2.JPG](_images/Farmduino2.JPG)
![Farmduino 3.JPG](_images/Farmduino_3.JPG)
" %}

# Stepper Drivers
These drivers convert step and direction signals from the microcontroller into powerful electrical pulses sent to the NEMA 17 stepper motors to allow them to move. All of the stepper drivers have been pre-mounted and tested on Farmduino.

|                              |                              |
|------------------------------|------------------------------|
|**Trade Name**                |A4988 Stepper Motor Driver Carrier (Header Pins Soldered)
|**Microstepping**             |full-step, half-step, 1/4-step, 1/8-step, and 1/16-step
|**Output Current**            |1.5 A per phase without a heat sink or forced air flow (rated for up to 2.0 A per coil with sufficient additional cooling)
|**Protections**               |Over-temperature thermal shutdown, crossover-current protection, and under-voltage lockout, short-to-ground, and shorted-load
|**Adjustable?**               |Current control lets you set the maximum current output with a potentiometer, which lets you use voltages above your stepper motor’s rated voltage to achieve higher step rates
|**Connectors**                |0.1″ male header pins
|**Price**                     |$6.00
|**Quantity**                  |5 (1 extra)



![Pololu.JPG](_images/Pololu.JPG)

# Raspberry Pi Power Cable
This USB cable provides power to the Raspberry Pi from the Farmduino's built-in 12v to 5v to USB circuitry.

|                              |                              |
|------------------------------|------------------------------|
|**Connector 1**               |Right-angle USB 2.0 Type A Male
|**Connector 2**               |Right-angle microUSB 2.0 Male
|**Length**                    |300mm
|**Color**                     |Black
|**Price**                     |$5.00
|**Quantity**                  |1



![Pi Power Cable.jpg](_images/Pi_Power_Cable.jpg)

# Farmduino Data Cable
This USB cable is used as a serial connection between the Raspberry Pi and the Farmduino

|                              |                              |
|------------------------------|------------------------------|
|**Connector 1**               |Right-angle USB 2.0 Type A Male
|**Connector 2**               |Right-angle USB 2.0 Type B Male
|**Length**                    |150mm
|**Color**                     |Black
|**Price**                     |$5.00
|**Quantity**                  |1



![Farmduino Data Cable.jpg](_images/Farmduino_Data_Cable.jpg)

# USB Adapter Cable
Connects the Raspberry Pi to the Borescope Camera.

|                              |                              |
|------------------------------|------------------------------|
|**Connector 1**               |Right-angle USB 2.0 Type A Male
|**Connector 2**               |USB 2.0 Type A Female
|**Length**                    |100mm
|**Color**                     |Black
|**Price**                     |$5.00
|**Quantity**                  |1



![USB Adapter Cable.jpg](_images/USB_Adapter_Cable.jpg)

# Jumper Wires
Use these jumper wires to connect the UTM headers on Farmduino to other pins such as I2C, PWM, or more digital or analog I/O.

|                              |                              |
|------------------------------|------------------------------|
|**Length**                    |180mm
|**Connectors**                |Single 2.54mm pitch female dupont contact with heatshrink
|**Color**                     |Black
|**Price**                     |$0.25
|**Quantity**                  |12



![Jumper Wires.jpg](_images/Jumper_Wires.jpg)

# NEMA 17 Stepper Motors with Rotary Encoders
These powerful 200 resolution stepper motors allow FarmBot to move precisely in the X, Y, and Z directions. Download the [motor spec sheet](https://drive.google.com/file/d/1Ehqu20q84Lyycn1fOj6dvWKbrMLvoNv4/view?usp=sharing) and [encoder spec sheet](https://drive.google.com/file/d/15dSqr_hQTXAQGIvw-YeDLIOC6dB0Y26n/view?usp=sharing).

|Motor Specs                   |                              |
|------------------------------|------------------------------|
|**Motor Resolution**          |200 steps/revolution (1.8 deg/step)
|**Winding Type**              |Bipolar
|**Voltage**                   |12V
|**Current Draw**              |1.68A max
|**Shaft Diameter**            |5mm diameter
|**Mount Hole Pattern**        |4x M3 holes, standard NEMA 17 pattern
|**Motor Connector**           |6-pin connector (only 4 pins used)
|**Encoder Connector**         |8-pin connector
|**Encoder Resolution**        |360 lines/revolution
|**Encoder Output**            |Differential
|**Price**                     |$60.00
|**Quantity**                  |4



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F_gMozmqbavk%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D_gMozmqbavk&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F_gMozmqbavk%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

{% include gallery.html images="
![Motor1.JPG](_images/Motor1.JPG)
![Motor 2.JPG](_images/Motor_2.JPG)
![Motor3.JPG](_images/Motor3.JPG)
" %}

# Motor Cables
These 4-wire cables connect each NEMA 17 stepper motor to the Farmduino. They are labelled on the Farmduino end `X1`, `X2`, `Y`, and `Z`.

|                              |                              |
|------------------------------|------------------------------|
|**Lengths**                   |0.95m (X1)<br>2.6m (X2)<br>3.1m (Y)<br>4.8m (Z)
|**Cores**                     |4
|**Gauge**                     |18
|**Motor Connector**           |6 pin connector (only 4 pins used)
|**Farmduino Connector**       |2.54mm pitch 4 pin dupont connector with locking tab
|**Outer Color**               |Black
|**Price**                     |0.95m - $15.00<br>2.6m - $18.00<br>3.1m - $20.00<br>4.8m - $27.00



![v1.3-Motor-Cables.jpg](_images/v1.3-Motor-Cables.jpg)

# Encoder Cables
These cables connect the four rotary encoders to the Farmduino. They are labelled on the Farmduino end `X1`, `X2`, `Y`, and `Z`.

|                              |                              |
|------------------------------|------------------------------|
|**Lengths**                   |0.95m (X1)<br>2.6m (X2)<br>3.1m (Y)<br>4.8m (Z)
|**Cores**                     |7
|**Gauge**                     |20
|**Encoder Connector**         |8 pin connector
|**Farmduino Connector**       |2.54mm pitch 7-pin dupont connector with locking tab
|**Outer Color**               |Black
|**Price**                     |0.95m - $20.00<br>2.6m - $23.00<br>3.1m - $25.00<br>4.8m - $32.00



![v1.3-Encoder-Cables.jpg](_images/v1.3-Encoder-Cables.jpg)

# Cable Carrier
These hollow plastic chains are used throughout FarmBot to manage cables and tubing along each of the three axes.

|                              |                              |
|------------------------------|------------------------------|
|**Material**                  |Nylon PA66
|**Lengths**                   |X-Axis - 1.7m (85 links + end pieces)<br>Y-Axis - 1.7m (85 links + end pieces)<br>Z-Axis - 0.74m (37 links + end pieces)
|**Inside Height**             |15mm
|**Inside Width**              |40mm
|**Outside Height**            |20mm
|**Outside Width**             |48.2mm
|**Pitch**                     |20mm
|**Bending Radius**            |28mm
|**Price**                     |X-Axis - $50.00<br>Y-Axis - $50.00<br>Z-Axis - $30.00
|**Quantity**                  |1 for each axis

## 1.7m Cable Carrier

{% include gallery.html images="
![CClong1.JPG](_images/CClong1.JPG)
![CClong2.JPG](_images/CClong2.JPG)
" %}

## 0.74m Cable Carrier

{% include gallery.html images="
![CCshort1.JPG](_images/CCshort1.JPG)
![CCshort2.JPG](_images/CCshort2.JPG)
" %}

# Universal Tool Mount Cable
This 12-wire cable connects the Farmduino to the UTM. It provides Ground, 5V, digital and analog I/O, and can be configured at the Farmduino to provide I2C, PWM, and more.

|                              |                              |
|------------------------------|------------------------------|
|**Number of Wires**           |12
|**Wire Colors**               |All different
|**Shielded?**                 |No
|**Wire Gauge**                |20
|**Length**                    |4m
|**Outer Diameter**            |9.5mm
|**Outer Color**               |Black
|**Price**                     |$35.00
|**Quantity**                  |1



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2Fh_3c8-A966E%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Dh_3c8-A966E&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2Fh_3c8-A966E%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

{% include gallery.html images="
![UTM Cable 0.jpg](_images/UTM_Cable_0.jpg)
![UTM Cable.jpg](_images/UTM_Cable.jpg)
" %}

# Soil Sensor PCB
The Soil Moisture Sensor is a simple breakout for measuring the moisture in soil and similar materials. The soil moisture sensor is pretty straight forward to use. The two large exposed pads function as probes for the sensor, together acting as a variable resistor. The more water that is in the soil means the better the conductivity between the pads will be and will result in a lower resistance, and a higher SIG out.

|                              |                              |
|------------------------------|------------------------------|
|**Sensor Type**               |Capacitive
|**Input Voltage**             |--
|**Input Current**             |--
|**Output Type**               |Analog
|**Price**                     |$6.00
|**Quantity**                  |1

{% include gallery.html images="
![soilsensor1.JPG](_images/soilsensor1.JPG)
![soilsensor2.JPG](_images/soilsensor2.JPG)
" %}

# Soil Sensor Jumpers
These short wires connect the soil sensor PCB to the M3 electronic screws on the soil sensor base.

|                              |                              |
|------------------------------|------------------------------|
|**Length**                    |75mm
|**Wire Type**                 |20AWG stranded copper
|**Colors**                    |Red, White, Black
|**End A**                     |5mm of insulation pre-stripped
|**End B**                     |M3 insulated ring terminal
|**Price**                     |$0.50
|**Quantity**                  |Red - 1<br>White - 1<br>Black - 1



![soil sensor wires.JPG](_images/soil_sensor_wires.JPG)

# Solenoid Valve
This 12V valve controls the flow of water from your garden hose to FarmBot's tubing.

|                              |                              |
|------------------------------|------------------------------|
|**Inlet**                     |3/4" NPT (National Pipe Thread)
|**Outlet**                    |3/4" NPT (National Pipe Thread)
|**Operation**                 |Normally closed
|**Working Pressure Range**    |0.02 to 0.8 Mpa (3 to 116 PSI)
|**Flow Direction**            |One-way, indicated by an arrow molded into the plastic
|**Input Voltage**             |12V
|**Current Draw**              |320mA
|**Power Consumption**         |3.84 Watts
|**Price**                     |$8.00
|**Quantity**                  |1



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FMkIYGSv_tdA%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DMkIYGSv_tdA&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FMkIYGSv_tdA%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

{% include gallery.html images="
![Solenoid Valve.JPG](_images/Solenoid_Valve.JPG)
![Solenoid Valve 2.JPG](_images/Solenoid_Valve_2.JPG)
![Solenoid Valve 3.JPG](_images/Solenoid_Valve_3.JPG)
" %}

# Vacuum Pump
This 12V vacuum pump sucks air through the seeder's luer lock needle in order to suction-hold a seed on the needle tip during planting.

|                              |                              |
|------------------------------|------------------------------|
|**Input Voltage**             |12V DC
|**Current Draw**              |1A
|**Price**                     |$15.00
|**Quantity**                  |1

{% include gallery.html images="
![Vacuum Pump.JPG](_images/Vacuum_Pump.JPG)
![Vacuum Pump 2.JPG](_images/Vacuum_Pump_2.JPG)
" %}

# Vacuum Pump Cable
This cable connects the vacuum pump to the Farmduino.

|                              |                              |
|------------------------------|------------------------------|
|**Length**                    |4.3m
|**Gauge**                     |18 AWG
|**Wire Type**                 |Stranded copper
|**Number of Wires**           |2
|**Rated Voltage**             |300V
|**Inner Colors**              |Red and black
|**Outer Color**               |Black
|**Connector 1**               |[Molex Part Number 151049-2206](https://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml)
|**Connector 2**               |Two 3/16" female shielded quick-connect terminals
|**Price**                     |$15.00
|**Quantity**                  |1



![Vacuum Pump Cable.jpg](_images/Vacuum_Pump_Cable.jpg)

# Solenoid Valve Cable
This cable connects the solenoid valve to the Farmduino.

|                              |                              |
|------------------------------|------------------------------|
|**Length**                    |3m
|**Gauge**                     |18 AWG
|**Wire Type**                 |Stranded copper
|**Number of Wires**           |2
|**Rated Voltage**             |300V DC
|**Inner Colors**              |Red and black
|**Outer Color**               |Black
|**Connector 1**               |[Molex Part Number 151049-2206](https://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml)
|**Connector 2**               |Two 1/4" female shielded quick-connect terminals
|**Price**                     |$15.00
|**Quantity**                  |1



![Solenoid Valve Cable.jpg](_images/Solenoid_Valve_Cable.jpg)

# Borescope Camera
The camera is mounted on the z-axis and allows FarmBot to take photos of the garden and plants for weed detection and other future use cases such as plant growth tracking.

|                              |                              |
|------------------------------|------------------------------|
|**Resolution**                |1024 x 768
|**Waterproof?**               |Yes
|**Focal Distance**            |1m
|**Outer Diameter**            |9mm
|**Camera Length**             |38mm
|**Cable Length**              |5m
|**Connection**                |USB
|**Price**                     |$35.00
|**Quantity**                  |1



<iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F-6rKclV82EQ%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D-6rKclV82EQ&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F-6rKclV82EQ%2Fhqdefault.jpg&key=02466f963b9b4bb8845a05b53d3235d7&type=text%2Fhtml&schema=youtube" width="854" height="480" scrolling="no" frameborder="0" allowfullscreen></iframe>

{% include gallery.html images="
![Camera.JPG](_images/Camera.JPG)
![Camera 2.JPG](_images/Camera_2.JPG)
" %}

# Jumper Links
These connect the Grounded electronic pin to the Digital In pin, allowing FarmBot to detect when a tool has been mounted or dismounted correctly.

|                              |                              |
|------------------------------|------------------------------|
|**Material**                  |Aluminum
|**Thickness**                 |1mm
|**Hole Sizes**                |M3
|**Price**                     |$0.25
|**Quantity**                  |4



![Jumper Links.jpg](_images/Jumper_Links.jpg)

# LED Strip
This LED strip is strung through the gantry's horizontal cable carrier supports so that you can light up your garden at night to show friends or for easy harvesting. Please note: this is not a "grow light".

|                              |                              |
|------------------------------|------------------------------|
|**Light Color**               |White 6000K
|**Strip Length**              |1.5m
|**Lead Length**               |1m
|**Connector**                 |[Molex Part Number 151049-2206](https://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml)
|**Price**                     |$25.00
|**Quantity**                  |1



![LED Strip.jpg](_images/LED_Strip.jpg)

