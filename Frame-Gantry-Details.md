# Frame and Gantry Details
## Frame and Gantry Alteration and Assembly Details
Alterations of the stock Ender 3 Pro frame and gantry includes:
- Replace 2020 Top Cross Member with new 2020 × 360mm v-slot extrusion
- Replace 4040 Main Cross Member with new 2040 × 280mm v-slot extrusion
- Replace 2020 Gantry with new 2020 × 340mm v-slot extrusion
- Repurpose existing 2020 gantry extrusion as new Forward Cross Member
- Add 40×40×13mm Main Bed Beam Spacer and 20×40×13mm Forward Bed Beam Spacer
- Shift 4040 Bed Beam extrusion 20mm forward

The following frame members are used as-is, with the exception of some drilling and tapping as necessary:
- Left & Right Base Members
- Left & Right Columns
- Bed Beam

Reference [Frame Parts](/Images/Frame-Gantry-Details/Frame-Parts.png) for identification of each frame member.  
Reference [Frame Alterations](/Images/Frame-Gantry-Details/Frame-Alterations.png) for overview of new and modified frame members.  

### Bed Beam Spacers
The Main and Forward Bed Beam Spacers may be cut from unused 4040 and 2040 extrusion respectively. Accurate formation of these parts is important for frame squaring and alignment. Since these are very short pieces to work with, and perhaps somewhat difficult to make, STLs for [Printed Spacers](STL/Frame) are an option.

### Required Drilling & Tapping
Aside from cutting new and repurposed extrusions to length, drilling and tapping is required. Specifically, the following is required. Consider laying out and double checking all dimensions for all members prior to performing any cutting or drilling. The instructions below should be accurate, but things happen. Case in point, the Initial Release of the CAD files (Fusion 360) has an error in the location of the tapped holes for the Forward Bed Beam Spacer.
- New 4040 Main Cross Member
  - Tap two holes on each end with an M5×0.8 tap to connect the Left & Right Base Members with 2-M5 SHCS each side
  - Drill four 5.5mm holes midway along the extrusion for 4-M5 SHCS to attach Bed Beam
  - These holes will be 130mm from each end of the extrusion and separated by 20mm at the midpoint
  - Provide clearance for the M5 SHCS heads in the same way as the stock extrusions (a 9mm drill bit should work)
- New 2020 Top Cross Member
  - Drill two 5.5mm holes at each end to align with tapped holes in Left & Right Column Members (10mm and 30mm from ends)
  - The stock Ender 3 Top Cross Member may be used as a template for drilling
  - Provide clearance for the M5 SHCS heads
  - The new Top Cross Member should look just like the stock one, except longer
- New 2020 Forward Cross Member (repurposed 2020 gantry extrusion)
  - Drill one 5.5mm hole 10mm from each end to align with the lower inside holes of the Left & Right Base Members
  - These holes will be 300mm apart along the 320mm long extrusion
  - Drill two 5.5mm holes midway along the extrusion for 2-M5 SHCS to attach the Bed Beam
  - These holes will be 150mm from each of the extrusion and separated by 20mm at the midpoint
  - Provide clearance for the M5 SHCS heads
- Existing Bed Beam Member
  - Confirm that the extrusion is 350mm in length
  - Locate the four existing tapped holes for mounting the Bed Beam to the existing Main Cross Member
  - Drill two 4.2mm holes spaced 20mm backward of the existing holes (105mm from the back end of the extrusion)
  - Drill two 4.2mm holes spaced 80mm from the front end of the extrusion
  - Tap the four new holes with an M5×0.8 tap
  - Ensure that the lower two holes at the front end of the extrusion are tapped for an M5 bolt to attach the Y-Idler
  - Ensure that the four holes at the back end of the extrusion are tapped for an M5 bolt to attach the Y-Motor
- Main and Forward Bed Beam Spacers
  - If using 4040 and 2040 extrusion for bed beam spacers, drill each hole with a 5.5mm drill to provide clearance for M5 bolts
- Existing Left & Right Base Members
  - Ensure that the ends are tapped for M5 bolts to attach the Forward Cross Member and skirt components
- Gantry
  - Aside from cutting the new 2020 Gantry to length, no drilling or tapping is necessary

### Frame Assembly
Assemble the frame using M5×25 and M5×45 SHCS bolts with washers. With the exception of perhaps two M5×25 bolts for the Forward Cross Member, these bolts come from the Ender 3 Pro frame. Refer to the CAD models for specifics. Square and align the frame in the same manner as other builds described elsewhere.

## Gantry, Idler, and Belt Details
### Gantry
The new longer gantry extrusion provides full use of the MGN12 × 300mm linear rail and thus full use of the 235mm bed width and then some. Two options are provided for the gantry belt idlers: toothed or smooth. The smooth idler option is generally more economical as the Gates GT2 toothed idlers can be pricey. Whichever option is chosen for the gantry, the corresponding option should be used for the upper idlers to maintain belt alignment.

<img src="/Images/Frame-Gantry-Details/New-Gantry.png" width="600">

### Toothed Option
The toothed option requires a total of six toothed idlers, two for the gantry and four for the upper idlers, plus two smooth F695 idler assemblies.

<img src="/Images/Frame-Gantry-Details/Toothed-Gantry-Idler-Blocks.png" width="300">
<img src="/Images/Frame-Gantry-Details/Toothed-Upper-Idler-Blocks.png" width="300">

### Smooth Option
The smooth option requires a total of eight F695 idler assemblies.

<img src="/Images/Frame-Gantry-Details/Smooth-Gantry-Idler-Blocks.png" width="300">
<img src="/Images/Frame-Gantry-Details/Smooth-Upper-Idler-Blocks.png" width="300">

### Belt Details
The Gantry uses Gates 6mm GT2 belting. The spacing and offsets for the XZ belts are identical to Voron Switchwire and the implementation by [DaRk_dOg](https://github.com/boubounokefalos/Ender_SW/tree/main).  
- Belt spacing is 10mm centerline to centerline.
- Centerline of Belt B is 24mm from face of frame.
- Centerline of Belt A is 14mm from face of frame.
- Motor B and Motor A pulley offsets measured from the outside edge of the frame is 10.62mm.

<img src="/Images/Frame-Gantry-Details/XZ-Belt-Spacing-Offsets.png" width="300">
<img src="/Images/Frame-Gantry-Details/XZ-Pulley-Offset.png" width="300">

