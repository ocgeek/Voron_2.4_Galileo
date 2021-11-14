**Galileo Clockwork**

Please go to the original repository for Galileo Clockwork (as it is actively maintened there)
https://github.com/JaredC01/Galileo
 
 
**Galileo driven Z-Drives**

The source components are from the great **project and design** of **JaredC01** (see Voron Discord)

**Mind that these components are by design of the author a TIGHT FIT** 
Some pressing in of the bearings is expected and IMHO intended.
I used a long exagonal key driver (M10) to press them in by my body weight..

You can reach out in Voron Discord i'm **oc_geek V2.1064 V2.1820**

This is goint to be my second Voron 2.4 build 
and il will be equipped with Galileo Z Gearboxes and Galileo Extruder (and few other mods :-) ) 

I made some chages to his design (was tailored for Voron 2.2 in ~ 2020)
- Fixed the hole height of M5x40 screw to grab 5mm on the M5 post insert nut
- The Mount has a larger center hole (now ID is 8.6mm) to allow the bearing removal and avoid D shaft rubbing plastic
- Reduced the 4xM3 holes in the Mount to ID 3.4 mm (from 4.2) for a snug alignment to the Gearbox shelve
- The Mount (aka Foot) is now 10 mm taller to better suite a V2.4 build bottom height (it does not change the belts lenght)
- Stepper Spacer has now a hook (with M5x20 BH) to the inner frame extrusion so stepper Motor weight does not load on Gearbox. A hole for the M3 pass through screw has been added to the spacer for mounting the Gearbox shelve
- Added skirts for V2.4 300mm including a rotating gear (pressure) mounted on the D-Shaft protruding out of Mount front (~ 3mm)

I developed all those changes in **Fusion 360**
The **CAD file** is too large so i uploaded it on Google Drive (lates update 11st July 2021)
https://drive.google.com/drive/folders/1DQNbAXy60l3uwEx9qxdZTg94INP0bn9f?usp=sharing

**Z Gearbox** BOM
_Quantity is for ONE (1) Gearbox_
- 10T metal Spur Gear x1 - <<https://www.aliexpress.com/item/4000299898525.html>>
- 5x4mm Heat inserts x8 (Voron BOM)
- 60mm Long 5mm OD D-shaft (Voron BOM)
- 16T "Prusa Stile" Pulley with Base H=6mm (thinner than POWGE) x1 - e.g. <<https://www.amazon.it/gp/product/B07T5CYBJW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1>>
- 1.0mm shim M5 washers x2 (or 0.5mm if you wanna play finer) 
- F695 2RS Bearing x4 (Carrier and Gearbox)
- F625 2RS Bearing x1 (Mount)
- M3x12mm SHCS screws x4 (to close the gear Shelves)
- M5x16mm BHCS screws x3 (gears to carrier)
- M3x18mm SHCS screws x4 (connect to the Stepper)
- M3x20mm SHCS screws x4 (connect Mount to gear Front Housing)

Mounting a Z-Drive to the frame requires:
- M5x40mm SHCS screw x1 (Mount to Frame)
- M5x16mm BHCS screws x3 (Mount to Frame)
- M5x20mm BHCS screws x1 (Spacer to Frame)

See in the **Assembly folder** there are some notes on how i did put these things together :)

![image](https://user-images.githubusercontent.com/76037248/136663762-35a79e73-ab10-4854-ac85-7c31087a9545.png)

These are the assembled GearBoxes

![image](https://user-images.githubusercontent.com/76037248/125200150-eff22780-e269-11eb-85b3-807b5a5e1603.png)

I modified the spacer so that it hooks onto the frame and sustains the Stepper weight. 
Also it sists in the center of mass of the assembly
This is reccomended works very well

![image](https://user-images.githubusercontent.com/76037248/125200206-42cbdf00-e26a-11eb-9690-d2a79d3ae327.png)

I amended the Mount (foot) to be 10mm taller and better suited to the Voron 2.4 (the change does not change the belt lenghts) 

![image](https://user-images.githubusercontent.com/76037248/125200221-56774580-e26a-11eb-8fd4-dabff086de4f.png)

![image](https://user-images.githubusercontent.com/76037248/125197641-d5ff1780-e25e-11eb-9f1c-6b353727444d.png)

![image](https://user-images.githubusercontent.com/76037248/125197650-ddbebc00-e25e-11eb-9f4b-6601d3c0f62b.png)

![IMG_20210810_165939](https://user-images.githubusercontent.com/76037248/130490119-4ad001e6-39cc-45e0-86db-aeb21689f9a6.jpg)

![IMG_20210814_064714 (1)](https://user-images.githubusercontent.com/76037248/130490158-3c083f67-136f-455f-872a-24abb6e97e01.jpg)

![IMG_20210814_100610](https://user-images.githubusercontent.com/76037248/130490170-ab85e14c-1111-4b2c-9ca7-47625fba2b5a.jpg)


**This is a list of what i ended up installing in this build :)**

**Frame and Panels:**
- 4mm thick polycarbonate panels (including the bottom deck to view through the electronics)
- Doors with hinges
- Handles 2x on top and 2x at bottom sides (it's 50Kg this thing...)

**Control Electronics and cabling**
- Duet Mini 5+ Wifi
- Duet 2+ expansion (to reach 7 drivers)
- Prepared for an additional Duet 5+ (not yet installed for ERCF MMU unit - future) via FD-CAN bus
- Duet Tool Board 1LC (v1.1 with included accelerometer) mounted on the tool head side and connected via FD-CAN bus
- Heluflon FEP wires (AWG 18, 20, 24)
- MDPC-X sleeve (used out of the chains)
- Wago 221 connectors
- Chamber temp / humidity sensor (DHT21)
- Ambient temp thermistor
- Various cable management brackets (made in Fusion360) and cables routing guide out of the cables hole in the back

**Mechanics and movement:**
- OMC Steppers-online motors
- 1.8* on Z axis (4)
- 0.9* on X-Y axis (2)
- LDO pancake for Galileo Clockwork Extruder
- Galileo gear-boxes for Z movement (required redesign of the entire skirts)
- Galileo Clockwork (Coupler Edition) for Extruder
- MGN-12 single rail on X axis
- AB-BN 30 tool body with 5015 work cooling fan
- Hall effect end stops for X/Y
- MGC5 spherical Z joints
- Klicky probe (instead of the inductive Z sensor) for bed leveling and final Z0 setting
- Pin mod on all bearings / idlers (5mm pins replace M5 screws - requires specific printed parts)

**Air Filtering**
- Nevermore Micro recirculating active carbon filter (dual 5015 fan located under the heated bed; also serves as quick chamber heat distribution in the pre-print phase)

**Lights:**
- WS2811 (aka neopixel) addressable LED strips with controllable brightness and color for each LED on each strip
- 15 LEDs on front, 18 LEDs each side top

**Others:**
- Purge bucket with scrub
- Align stands for the steel flex plate (two embedded in the Purge bucket body)

