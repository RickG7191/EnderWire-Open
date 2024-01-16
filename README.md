# EnderWire-Open
This is another option for converting an Ender 3 Pro to a Voron Switchwire. Inspiration for this conversion came from the excellent work of others including [DaRk_dOg](https://github.com/boubounokefalos/Ender_SW/tree/main) and [Steve](https://github.com/stvptrsn).  
  
It is hoped that the 3D printing community will find some value in this work.
  
## Description
One of the key differences that sets this conversion apart from others is that it provides full use of the stock Ender 3 bed size (235x235). The cost of getting that little extra amount involves replacing the top and bottom frame cross members as well as the gantry extrusion with longer versions. One of the replaced 2020 extrusions can be reused as a forward cross member providing better support for the 4040 Y-Axis extrusion, thus it doesn't teeter on the single cross member making frame alignment a bit easier.  

### No Enclosure
This version of the conversion is called "EnderWire-Open" because it does <ins>not</ins> include provisions for an enclosure. For those wanting to print mostly PLA, this is fine as it offers a smaller footprint when not in use. Adaptation to an enclosed version is feasible using longer frame extensions and stretching the side skirts, however I have not endeavored to do so.

### Features
Features of this conversion include:
- Build volume of 235 x 235 x 210
- Optional 6mm or 9mm Y-belt
- Optional smooth idlers or toothed idlers for XY belts
- Optional left endstop, right endstop, or no endstop X-carriage
- XY motor mounts, idler blocks, and gantry blocks optimized for v-slot extrusion
- Shorter Clockwork 2 cable chain mount
- Front skirt option for Mini12864 display or no display
- Front skirt option for hexagon mesh
- Front skirt option to illuminate endcaps with Neopixels or use colored inlay
- Back skirt case fan mount that doesn't use tape (requires gluing 4 small tabs to skirt frame)
- Back skirt standard keystone jacks
- Optional servo actuated Z-probe dock with optional position sensor switches, deck mounted

### Advanced Builder Features
For advanced builders, the following optional features are available:
- Below deck Key-Bak assembly with tension adjustment
- Lightened stock bed plate plus alternate Y-carriage
- Custom Z-endstop switch and bracket
- See Build Notes below.

![EnderWire Open](/Images/EnderWire-Open.png)
![EnderWire Open](/Images/Back.png)

## Files

### CAD
Complete Fusion 360 files are included in the initial release. Beware, there a upwards of 100 files in the Fusion 360 Archive (.f3z).

### STLs
STL files for all components except Stealthburner and Mini12864 are included ini the STL folder.

## Build Notes
- The feet are from [Amazon](https://www.amazon.com/gp/product/B00S47D52G/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
- The Key-Bak assembly useds the spring and 36" Kevlar cord from the regular [13oz Key-Bak](https://www.amazon.com/dp/B0088MQA10?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- The servo used for the Z-probe dock is a TowerPro MG92B from [Adafruit](https://www.adafruit.com/product/2307). I believe an MG90s will also work.
- A modified version of the PCB Klicky probe body and dock are used. The probe has a guard plate that assists with clean docking. The guard plate fits 0.25in x 0.125in countersunk magnets rather than the spec 6mm x 3mm. This is the size I recieved with the kits I purchased. The guard just press fits around the magnets. Glue may be needed.
- The custom z-endstop currently requires a custom PCB to mount the microswitch. Additionally, the support arm for the z-endstop is fabricated from 3mm FR4 / G10 for stiffness.
