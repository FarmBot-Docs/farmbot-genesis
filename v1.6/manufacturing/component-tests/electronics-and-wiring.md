---
title: "Electronics and Wiring Tests"
slug: "electronics-and-wiring"
---

* toc
{:toc}

Each component in the electronics and wiring category has its own unique tests.

# Cable Carrier

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Size         |Inspect the size marking embossed into the plastic.|See BOM spec|N/A
|Length       |Measure the length of the cable carrier using a measuring tape.|See BOM spec|0
|End pieces   |Inspect the orientation of the end pieces.|Oriented according to FarmBot system design|N/A
|Mount fit    |Connect the end pieces to the appropriate cable carrier mounts/supports using the appropriate hardware.|Should fit as expected|N/A
|Contents fit |Inert all cables and tubing into each cable carrier according to FarmBot system design.|Should fit as expected|N/A

# Camera

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Resolution   |Take a photo and inspect the resolution.|1.3MP|N/A
|Focus        |Take a photo of an object 50cm away.|The object should appear sharp|N/A
|Diameter     |Measure the diameter of the camera module using digital calipers.|11mm|+/- 0.5mm
|Mount compatibility|Mount the camera to an extrusion using two camera mount halves.|The camera should be able to be firmly mounted in place|N/A
|Function     |Connect the camera to a Raspberry Pi using a Genesis XL camera cable and take a photo from the FarmBot web app.|Photo taking should work as expected (no black images, no failures)|N/A
|Camera module length|Measure the length of the camera module using digital calipers.|38mm|+/- 2mm
|Cable        |Inspect the spec of the cable.|`Shielded 28AWG/1p+24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Cable length |Measure the length of the cable using a tape measure.|1m|+/- 2cm
|Sealing      |Inspect the sealing where the cable enters the camera module housing.|The cable should be well sealed|N/A
|Lens         |Inspect the camera lens for obstructions and straightness.|The camera lens should be free of obstructions and point straight out of the camera module.|N/A
|Color        |Inspect the color of the cable.|Black|N/A

# Camera Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length of the cable using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the diameter of the cable using digital calipers.|5mm|+/- 0.5mm
|Cable        |Inspect the spec of the cable.|`Shielded 28AWG/1p+24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Color        |Inspect the color of the cable.|Black|N/A
|Function     |Use the camera cable to connect a camera to a Raspberry Pi. Take a photo using the web app.|Image should be captured as expected|N/A
|90 degree connector|Connect the 90 degree connector to a camera and submerge into a cup of water. Take a photo using the web app.|The connector should make a waterproof connection, allowing an image to be captured as expected|N/A
|Electronics box fit|Connect the camera cable to the Raspberry Pi in a fully assembled electronics box.|Cable and connector should fit|N/A

# Camera Calibration Card

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Print size   |Measure the center-to-center distance between two white dots in the same row using digital calipers or a measuring tape.|30mm|+/- 0.5mm
|Contrast     |Inspect the card for good contrast between the background and the white dots.|Black and white (no gray)|N/A
|Paper thickness|Measure the thickness of the paper using digital calipers.|0.43mm (16pt)|+/- 0.1mm
|Sheen        |Inspect the sheen of the card.|Matte|N/A
|Function     |Use the card to perform camera calibration.|Camera should calibrate in a variety of common lighting conditions.|N/A

# Encoder Cables

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the cable's diameter using digital calipers.|5mm|+/- 1mm
|Connectors   |Use a motor and encoder cable to connect to the Farmduino. Issue some movement commands.|The encoder should report motor position as expected|N/A
|Label        |Inspect the shrinkwrap labels.|`X1`, `X2`, `Y`, `ZY`, and `ZZ`|N/A
|Cable        |Inspect the cable's spec.|28AWG-3P shielded stranded copper cable|N/A
|Color        |Inspect the color of the cable.|Black|N/A

# Farmduino

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Pins         |Inspect the pins for damage.|No pins should be bent|N/A
|Fuse         |Ensure the blade fuse is inserted and of the correct amperage.|7.5 Amps|N/A
|USB power out|Read the voltage coming from the `POWER OUT` USB connector.|5.25V|+/- 0.1V
|UTM shunts   |Inspect for the presence of the UTM pin shunts.|Present on Pins `A`-`H`|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A
|Functionality|Use the factory test firmware to test motor, encoder, and periperhal functions.|All functions work|N/A
|Encoder tracking|Move all motor axes with manual controls, by hand, and with forced stalls.|Encoder positions should be accurately tracked in all scenarios.|N/A
|Encoder tracking range|Using stock encoder scaling, move to +/- 10,000mm on the X and Y axes and +/- 2,000mm on the Z axis.|STM32 should accurately track encoder positions through the range of movement.|N/A
|STM32 reset  |Set `pin 49` low and then high.|Encoder tracking should reset.|N/A
|SPI comms    |Move motors to random positions and then modify Trinamic TMC2130 parameters (eg: motor current)|Parameters should update and encoder tracking should maintain position.|N/A

# Farmduino Data Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Cable        |Inspect the cable spec.|`Shielded 28AWG/1p+24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Connectors   |Connect the cable to a Raspberry Pi and Farmduino inside a fully assembled electronics box.|The cable should connect to both circuit boards without interference from the box or other components.|N/A
|Length       |Measure the length using a measuring tape.|150mm|+/- 10mm
|Color        |Inspect the color of the cable.|Black|N/A

# Jumper Links

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Hole size    |Measure the size of the holes using digtial calipers.|3.25mm|+/- 0.1mm
|Fit          |Assemble a jumper link into a tool using M3 screws and locknuts according to the FarmBot system design.|Part should fit without interference|N/A
|Thickness    |Measure the thickness using digital calipers.|1mm|+/- 0.2mm
|Material     |Ensure the material will not rust by holding a magnet to the part.|Aluminum (no magnetic attraction)|N/A
|ELectrical conductivity|Connect an ohm meter to both ends of a jumper link.|Less than 1 ohm|N/A

# Jumper Wires

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connectors   |Connect a jumper wire to two GPIO pins.|It should connect as expected.|N/A
|Wire         |Inspect the wire spec.|20AWG|N/A
|Length       |Measure the length using a measuring tape.|180mm|+/- 10mm
|Color        |Inspect the color of the cable and shrinkwrap.|Black|N/A

# LED Indicators

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Diameter     |Measure the diameter of the threaded section using digital calipers.|11.8mm|+/- 0.2mm
|Electronics box fit|Check fit in electronics box.|LED should fit with minimal play such that o-ring is guaranteed to seal.|N/A
|Length       |Measure the overall length using digital calipers.|24mm|+/- 1mm
|O-ring       |Inspect for the presence of an O-ring under the top flange.|Present|N/A
|Waterproof   |Drill a hole in a small plastic tub. Fasten the LED indicator to the hole and fill the tub with water.|The LED indicator should continue to operate when submerged, and prevent water from leaking.|N/A
|Wiring harness|Connect wiring harness between LED and Pi Adapter Board.|LED should work, harness should be of adequate length, and connectors should stay firmly attached.|N/A
|Material     |Ensure the material will not rust by holding a magnet to the part.|Stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.
|Illumination |Power on FarmBot.|The Sync and Connectivity indicators should be illuminated|N/A

# LED Strip

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connector    |Connect the LED strip to a Farmduino peripheral plug.|Part should connect as expected|N/A
|Cable color  |Inspect the color of the cable.|Black|N/A
|Cable length |Measure the length of the cable using a measuring tape.|1m|+/- 20mm
|LED color    |Turn on an LED strip and inspect the color of the light.|Cool white (6000K)|N/A
|LED strip length|Measure the length of the LED strip using a measuring tape.|See BOM spec|+/- 30mm
|LED strip cut end|Inspect the cut end of the LED strip.|Cut end should be sealed with silicon rubber|N/A
|Double-sided tape|Inspect the LED strip for double-sided tape.|The part should not have any tape or other adhesives along its length|N/A

# MicroSD Card

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Brand        |Inspect the card for the brand name.|`SanDisk`|N/A
|Capacity     |Inspect the card for capacity rating.|8GB|N/A
|Condition    |Inspect to ensure the product is not used or refurbished.|Product should be brand new|N/A
|Software     |Power on the FarmBot.|FarmBot OS should boot into configurator.|N/A

# Motor Cables

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the cable's diameter using digital calipers.|5mm|+/- 1mm
|Connectors   |Use a motor cable to connect a motor to the Farmduino. Issue some movement commands.|The motor should operate as expected|N/A
|Label        |Inspect the shrinkwrap labels.|`X1`, `X2`, `Y`, `ZY`, and `ZZ`|N/A
|Cable        |Inspect the cable's spec.|24AWG-4C stranded copper cable|N/A
|Color        |Inspect the color of the cable.|Black|N/A

# NEMA 17 Stepper Motors with Rotary Encoders

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

# Peripheral Leads

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connector and continuity|Connect the lead to a Farmduino and power the peripheral. Use a voltmeter to measure the voltage at the exposed leads.|The cable's connectors should connect as expected and the voltage should be 24V.|N/A
|Length       |Measure the length using a tape measure.|10cm|+/- 1cm
|Cable        |Inspect the cable's spec.|18AWG-2C stranded copper cable|N/A
|Shrinkwrap   |Inspect the color of the shrinkwrap.|Black|N/A
|Color        |Inspect the color of the cable.|Black outer, black and red inner|N/A

# Pi Adapter Board

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Pins         |Inspect the pins for damage.|No pins should be bent|N/A
|RTC battery  |Ensure the RTC battery is inserted.|Included|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A

# Power Cord Protector

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Plug fit     |Connect a power supply to an extension cord, place the connection inside the power cord protector, and close the power cord protector fully.|The plugs should fit inside as expected|N/A
|Color        |Inspect the color of the part.|Green|N/A

# Power Supply

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Brand        |Inspect the name plate for the brand name.|`WEHO`|N/A
|Model        |Inspect the name plate for the model number.|`LPVF-150-24`|N/A
|Input        |Inspect the name plate for the input specs.|AC 100-265V<br>50/60Hz|N/A
|Input cable length|Measure the lenght of the input cable using a tape measure.|30cm|+/- 3cm
|Input plug   |Inspect the input plug.|Standard US 3-prong plug (NEMA 5-15 plug)|N/A
|Cord protector fit|Connect the input to an extension cord and insert into the power cord protector.|Cord protector should be able to fully close|N/A
|Output       |Inspect the name plate for the output specs.|DC 24V<br>DC 6.25A<br>150W|N/A
|Output cable length|Measure the lenght of the input cable using a tape measure.|20cm|+/- 3cm
|Output connector|Connect the output cable's screw-together connector to a power supply cable.|Should connect|N/A
|Waterproof   |Inspect the name plate for waterproof rating.|IP67|N/A
|Function     |Connect the power supply to complete FarmBot and power up the device.|FarmBot should be able to operate the motors and peripherals as expected.|N/A

# Power Supply Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the cable's length using a tape measure.|See BOM spec|+/- 3cm
|Diameter     |Measure the cable's diameter using digital calipers.|6mm|+/- 1mm
|Cable        |Inspect cable spec.|18AWG-3C stranded copper cable|N/A
|Connector 1  |Connect the cable's screw-together connector to the power supply.|Should connect|N/A
|Connector 2  |Inspect the connector type.|Should be a 3-pin plug ([Molex 2004561213](https://www.molex.com/molex/products/part-detail/crimp_housings/2004561213)|N/A
|Cable carrier fit|Insert the cable and a water tube through the X-axis cable carrier (including through the end pieces).|Should fit|N/A
|Electronics box fit|Insert the cable and connector 2 through the slot in the bottom of the electronics box and then insert the supergland.|Should fit|N/A
|Farmduino fit|Connect the cable to the Farmduino's `24V POWER IN` connector.|Should connect and power the board|N/A
|Color        |Inspect the part's colors.|Black cable<br>Black Molex connector|N/A

# Push Buttons

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Diameter     |Measure the diameter of the threaded section using digital calipers.|21.8mm|+/- 0.2mm
|Electronics box fit|Check fit in electronics box.|Button should fit with minimal play such that o-ring is guaranteed to seal.|N/A
|Length       |Measure the overall length using digital calipers.|40mm|+/- 1mm
|O-ring       |Inspect for the presence of an O-ring under the top flange.|Present|N/A
|Waterproof   |Drill a hole in a small plastic tub. Fasten the button to the hole and fill the tub with water.|The button should continue to operate when submerged, and prevent water from leaking.|N/A
|Wiring harness|Connect wiring harness between button and Pi Adapter Board.|Button should work, harness should be of adequate length, and connectors should stay firmly attached.|N/A
|Material     |Ensure the material will not rust by holding a magnet to the part.|Stainless steel (no magnetic attraction)|Weak attraction to stainless steel is permissible.
|Function     |Bind a button to a sequence and press the button.|FarmBot should execute the sequence|N/A
|Illumination |Power on FarmBot.|The E-stop button should be illuminated|N/A

# Raspberry Pi

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Model        |Inspect the board for model number.|`Model 3B+`|N/A
|Brand        |Inspect the board for the brand name.|`Raspberry Pi`|N/A
|Condition    |Inspect to ensure the product is not used or refurbished.|Product should be brand new|N/A
|GPIO pins    |Inspect the GPIO pins for damage.|No pins should be bent|N/A

# Raspberry Pi Power Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Cable        |Inspect the cable spec.|`Shielded 28AWG/1p+24AWG/2c`<br><br>`1p` = 1 twisted pair (for data)<br>`2c` = 2 core (for power)|N/A
|Connectors   |Connect the cable to a Raspberry Pi and Farmduino inside a fully assembled electronics box.|The cable should connect to both circuit boards without interference from the box or other components.|N/A
|Length       |Measure the length using a measuring tape.|300mm|+/- 10mm
|Voltage drop |Use USB voltage monitors to check the voltage before and after the cable.|Less than 5% voltage drop|4.9V output minimum
|Color        |Inspect the color of the cable.|Black|N/A

# Rotary Tool Motor

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Form Factor  |Inspect the motor form factor.|`500TB-12560`|N/A
|Voltage      |Inspect the rated voltage.|24V|N/A
|FWD/REV      |Assemble the motor into a full Rotary Tool and test with a complete FarmBot.|Motor can be powered in forward and reverse at power/speed levels between 20% and 100%|N/A
|Load sense   |Assemble the motor into a full Rotary Tool and test with a complete FarmBot.|Farmduino/FBOS can detect motor load and stalls in realtime|N/A
|Wiring       |Inspect the wiring.|`DC1` (Black) soldered to motor<br>`DC2` (White) soldered to motor<br>`PE` (Clear) soldered to motor housing|N/A
|Wire lengths |Measure the length of the wires using digital calipers.|75mm|+/- 5mm
|Connector    |Inspect the connector type and plug into Rotary Tool PCB.|JST XH connector should attach as expected|N/A
|Screw mounts |Attach the motor to the Rotary Tool with M2.5 x 6mm screws.|Screws should thread correctly and secure the motor in place|N/A
|Shaft diameter|Measure the motor shaft diameter using digital calipers.|2mm|+/- 0.1mm
|Shaft length |Measure the motor shaft length using digital calipers.|8mm|+/- 0.5mm
|Implement fit|Attach the M5 Shaft Adapter to the motor.|Adapter should securely and concentrically attach|N/A

# Rotary Tool PCB

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|FWD/REV      |Assemble the PCB into a full Rotary Tool and test with a complete FarmBot.|Allows motor to be powered in forward and reverse at power/speed levels between 20% and 100%|N/A
|Load sense   |Assemble the PCB into a full Rotary Tool and test with a complete FarmBot.|PCB circuitry does not interfere with load sense readings or stall detection|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A

# Soil Sensor PCB

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Function     |Connect the PCB to a test fixture and take readings in dry and wet conditions.|Functions as expected|N/A
|Wiring       |Inspect the wire colors.|`VCC` - Red<br>`GND` - Black<br>`SIG` - Yellow<br>`SDA` - Green<br>`SCL` - White|N/A
|Wiring length|Measure the length of the wires using digital calipers.|50mm|+/- 5mm
|Terminals    |Attach a terminal to the soil sensor plastic part using an M3 screw.|Terminal should attach as expected|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A

# Solenoid Valve

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Threads      |Screw an NPT to barb adapter (with rubber gasket) onto the inlet. Connect a tube to the barb and pressurize the system with municipal water.|Adapter should thread on as expected and the system should hold water without leaking.|N/A
|Voltage      |Connect the solenoid valve to a Farmduino and test operation.|Opens and does not get hot with 24V input|+/- 3V
|Terminal size|Connnect a solenoid valve cable.|The cable's connectors should connect to the terminals as expected|N/A
|Terminal direction|Inspect the direction the terminals face.|Terminals should face the inlet|N/A

# Solenoid Valve Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connectors and continuity|Use the cable to connect a solenoid valve to a Farmduino.|The cable's connectors should connect as expected and the valve should be operable.|N/A
|Length       |Measure the length using a tape measure.|0.5m|+/- 20mm
|Cable        |Inspect the cable's spec.|18AWG-2C stranded copper cable|N/A
|Shrinkwrap   |Inspect the color of the shrinkwrap.|Blue|N/A
|Color        |Inspect the color of the cable.|Black outer, black and red inner|N/A

# UTM Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Length       |Measure the length using a measuring tape.|See BOM spec|+/- 20mm
|Diameter     |Measure the diameter of the cable using digital calipers.|7mm|+/- 0.5mm
|Connectors   |Connect a UTM to the Farmduino using the cable.|Connectors should fit as expected.|N/A
|Continuity   |Use a multimeter to check pinout and continuinty for each core through complete cable (Y and Z sections).|All cores are connected correctly|N/A
|Cable        |Inspect the cable's spec.|24AWG-12C shielded stranded copper cable|N/A
|Shroud       |Inspect the shroud and test fit on UTM.|Shroud should snugly fit on top of UTM|N/A
|Color        |Inspect the color of the cable.|Black|N/A
|Function     |Mount and dismount the Rotary Tool and Soil Sensor. Use a tools to verify cable function.|Tools work as expected|N/A

# UTM PCB

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Pins         |Inspect the pins for damage.|No pins should be bent|N/A
|Fit          |Mount the PCB into a UTM.|The PCB should fit as expected|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A

# Vacuum Pump

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Performance  |Connect the vacuum pump to a 24V power source, vacuum air tube, UTM, and seeder tool.|The vacuum should exert enough suction to pick up a seed|N/A
|Terminal size|Connnect a vacuum pump cable.|The cable's connectors should connect to the terminals as expected|N/A
|PCB color    |Inspect the PCB's color.|Matte black|N/A
|Size         |Assembly a vacuum pump, vacuum pump mount plate, vacuum pump cover, and z-axis extrusion according to the FarmBot system design.|Vacuum pump should fit inside the housing without interference,|N/A
|Inlet size   |Connect a vacuum air tube to the vacuum pump's inlet.|Tube should connect as expected, requiring a small amount of force to remove.|N/A

# Vacuum Pump Cable

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connectors and continuity|Use the cable to connect a vacuum pump to a Farmduino.|The cable's connectors should connect as expected and the vacuum pump should be operable.|N/A
|Length       |Measure the length of the two sections of cable using a tape measure.|See BOM spec|+/- 20mm
|Cable        |Inspect the cable's spec.|18 guage, 2 core|N/A
|Shrinkwrap   |Inspect the color of the shrinkwrap.|Gray|N/A
|Color        |Inspect the color of the cable.|Black outer, black and red inner|N/A
