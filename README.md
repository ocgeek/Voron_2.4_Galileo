Repository of Voron 2.4 build equipped with Galileo Z Gearboxes and Galileo Extruder
Please mind this is a WIP and the STL(s) are beeing updated
The source components are from the great project of **JaredC01** (see Voron Discord)

I made some chages to his design (was tailored for Voron 2.2 in ~ 2020)
- Fixed the hole height of M5x40 screw to grab 5mm on the M5 post insert nut
- The Mount has a larger center hole (now ID is 8.6mm) to allow the bearing removal and avoid D shaft rubbing plastic
- Reduced the 4xM3 holes in the Mount to ID 3.4 mm (from 4.2) for a snug alignment to the Gearbox shelve
- The Mount (aka Foot) is now 10 mm taller to better suite a V2.4 build bottom height (it does not change the belts lenght)
- Stepper Spacer has now a hook (with M5x20 BH) to the inner frame extrusion so stepper Motor weight does not load on Gearbox. A hole for the M3 pass through screw has been added to the spacer for mounting the Gearbox shelve
- Added skirts for V2.4 300mm including a rotating gear (pressure) mounted on the D-Shaft protruding out of Mount front (~ 3mm)

The CAD is too large so i uploaded it here (lates update 11st July 2021)
https://drive.google.com/drive/folders/1DQNbAXy60l3uwEx9qxdZTg94INP0bn9f?usp=sharing

**Elecronics :**
- Duet Mini 5+
- Duet Mini 2+
- Duet 1LC Toolboard 1.1

**Z Gearbox** BOM
_Quantity is for ONE (1) Gearbox_
- 10T metal Spur Gear x1 - <<https://www.aliexpress.com/item/4000299898525.html>>
- 5x4mm Heat inserts x8 (Voron BOM)
- 16T "Prusa Stile" Pulley with Base H=6mm (thinner than POWGE) x1 - <<https://www.amazon.com/gp/product/B07DBN8KFT>>
- 1.0mm shim M5 washers x2 (or 0.5mm if you wanna play finer) 
- F695 2RS Bearing x4 (Carrier and Gearbox)
- F625 2RS Bearing x1 (Mount)
- M5x16mm BHCS screws x3 (2x Mount, 1x Spacer)
- M5x40mm SHCS screw x1 (Mount)
- M3x18mm SHCS screws x4 (connect to the Stepper)
- M3x12mm SHCS screws x4 (to close the gear Shelves)
- M3x20mm SHCS screws x4 (connect Mount to gear Front Housing)

These are the GearBoxes mounted 
![image](https://user-images.githubusercontent.com/76037248/125200150-eff22780-e269-11eb-85b3-807b5a5e1603.png)

I modified the spacer so that it hooks onto the frame and sustains the Stepper weight. Also it sists in the center of mass of the assembly
![image](https://user-images.githubusercontent.com/76037248/125200206-42cbdf00-e26a-11eb-9690-d2a79d3ae327.png)

I made a talled Mount (foot) more suited to the Voron 2.4
![image](https://user-images.githubusercontent.com/76037248/125200221-56774580-e26a-11eb-8fd4-dabff086de4f.png)

This is the model i developed in Fusion 360 for the Skirts

![image](https://user-images.githubusercontent.com/76037248/125197641-d5ff1780-e25e-11eb-9f1c-6b353727444d.png)
![image](https://user-images.githubusercontent.com/76037248/125197650-ddbebc00-e25e-11eb-9f4b-6601d3c0f62b.png)
