# UTAH-TPC-Simulation-and-Models
### Table of Contents
- [Simple Geometry Model](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#simple-geometry-model)
  - [Contents](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#contents)
  - [System](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#system)
  - [Field Cage Regions](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#field-cage-regions)
  - [Simulation and Calculations](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#simulation-and-calculations)
- [Complex Model](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#complex-model)
- COMSOL Simulation (Electric Field)
  - Importing External Models
  - Setting Up Paramaters
  - Mesh Settings
  - Simulation
- COMSOL Simulation (Particles in Free Space)

### File Shortcuts
| Item | File Extension  | Program |
|------|----------------|---------------------|
| [Design Considerations for the UTA/H LArTPC](/y.Original%20Documentation/)     | .pdf  | Any PDF Opener |
| [UTA/H TPC Original CAD Drawings ](/y.Original%20Documentation/) | .zip | N/A |
| [Simple Geometry Model](/Simple%20Model/) | .STEP | Any 3D CAD Program |
| [Voltage Divider](/Misc%20Assets/UTAH%20TPC%20Resistor%20Network/)       | .kicad_pro | [KiCAD](https://www.kicad.org/) |
| Detailed Model        | .STEP | Any 3D CAD Program |

---
## Simple Geometry Model

### Contents
---
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

