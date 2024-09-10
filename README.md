# UTAH-TPC-Simulation-and-Models
### Table of Contents
- Simple Geometry Model
  - Contents
  - System
  - Field Cage Regions
  - Simulation and Calculations
- Complex Model
- COMSOL Simulation (Electric Field)
  - Importing External Models
  - Setting Up Paramaters
  - Mesh Settings
  - Simulation
- COMSOL Simulation (Particles in Free Space)

### File Shortcuts
| Item | File Extension  | Program |
|------|----------------|---------------------|
| [Design Consideratioons for the UTA/H LArTPC](/y.Original%20Documentation/UTAH_TPCs.pdf)     | .pdf  | Any PDF Opener |
| [UTA/H TPC Original CAD Drawings ](/y.Original%20Documentation/UTAH.zip) | .zip | N/A |
| Simple Geometry Model | .STEP | Any 3D CAD Program |
| Voltage Divider       | .kicad_pro | [KiCAD](https://www.kicad.org/) |
| Detailed Model        | .STEP | Any 3D CAD Program |

---
## Simple Geometry Model
### Contents
The objects contained in the STEP Files are as detailed
|      Name     |  Quantity  |                  Description                      |
|---------------|:----------:|---------------------------------------------------|
| Pixel         |     64     | Charge readout input                              |
| PCB Board     |      1     | PCB Board of Pixels                               |
| Mesh          |      1     | Electric Field Mesh for field line manipulation   |
| Field Ring    |     14     | Electric Field Ring for Static Cage Environment   |
| Mesh Ring     |      2     | Electric Field Ring for Mesh Support              |
| HDPE Cylinder |      2     | Electric Field Ring for Mesh Support              |


---
### System
---

<img src="./z.ReadMeAssets/UTAH%20Github/Slide1.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide2.PNG" width="100%">

Pixels are placed under a mesh grid such that any drifting charges are focused onto pads, a later simulation showcases such in an ideal system.

---
### Field Cage Regions
---

<img src="./z.ReadMeAssets/UTAH%20Github/Slide3.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide4.PNG" width="100%">

---
### Simulation and Calculations
---

<img src="./z.ReadMeAssets/UTAH%20Github/Slide5.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide6.PNG" width="100%">

---
## Complex Model
### Model Contents

