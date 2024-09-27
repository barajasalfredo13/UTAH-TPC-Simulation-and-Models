# UTAH-TPC-Simulation-and-Models

### Motive
The motive for this computation was to determine ideal parameters for experimental development in particle detection using the UTAH-TPC Model as a basis. 

### Table of Contents
  - [Simple Geometry Model](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#simple-geometry-model)
  - [Contents](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#contents)
  - [System](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#system)
  - [Field Cage Regions](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#field-cage-regions)
  - [Simulation and Calculations](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#simulation-and-calculations)
  - [UTAH-TPC Model](https://github.com/barajasalfredo13/UTAH-TPC-Simulation-and-Models/tree/main?tab=readme-ov-file#complex-model)

### File Shortcuts
| Item                                                                           | File Extension |         Program         |
|--------------------------------------------------------------------------------|----------------|-------------------------|
| [Design Considerations for the UTA/H LArTPC](/y.Original%20Documentation/)     | .pdf           | Any PDF Opener          |
| [UTA/H TPC Original CAD Drawings ](/y.Original%20Documentation/)               | .zip           | N/A                     |
| [Simple Geometry Model](/Models/)                                              | .STEP          | Any 3D CAD Program      |
| [Voltage Divider](/Misc%20Assets/UTAH%20TPC%20Resistor%20Network/)             | .kicad_pro     | [KiCAD](https://www.kicad.org/) |
| [Voltage Calculator](/Misc%20Assets/Field%20Cage%20Calculator/)                | .xlsx          | Microsoft Excel         |
| [ElectricField.UTAHTPC](/Models/)                                              | .zip .mph      | COMSOL Multiphysics     |
| [Exposed UTAH TPC Model](/Models/)                                             | .STEP          | Any 3D CAD Program      |
| [Enclosed UTAH TPO Model](/Models/)                                            | .STEP          | Any 3D CAD Program      |

---
## Simple Geometry Model
Motivation: Simple set-up of a basic model to set-up parameters for the UTAH-TPC Model
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

<img src="./z.ReadMeAssets/UTAH%20Github/Slide7.PNG" width="100%">

---
### UTAH-TPC Model
---

<img src="./z.ReadMeAssets/UTAH%20Github/Slide8.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide9.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide10.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide11.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide12.PNG" width="100%">

<img src="./z.ReadMeAssets/UTAH%20Github/Slide13.PNG" width="100%">
