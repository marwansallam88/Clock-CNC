# CNC Roman Clock Simulation using winNC
<p align="center">
  <img src="Clock.png" alt="Description" width="400"/>
  <img src="Clock_CNC.png" alt="Description" width="600"/>
</p>

## Project Specifications

### Workpiece Configuration
![Preview](workpiece.PNG)
| Parameter | Value |
|-----------|-------|
| Material | Aluminum 6061-T6 |
| Diameter | 600mm |
| Thickness | 30mm |
| Stock Allowance | 2mm (all surfaces) |
| Work Zero Offsets | X+20mm, Y+20mm, Z+20mm |

## Tooling & Machining Strategy
![Preview](tools.PNG)
### Tool Table
| Tool | Type | Diameter | Flutes | Application | Offset Register |
|------|------|----------|--------|-------------|-----------------|
| T1 | Facemill | 40mm | 6 | Surface milling | G54.1 P1 |
| T2 | Endmill | 5mm | 4 | Roughing numerals | G54.1 P2 |
| T3 | Endmill | 3mm | 2 | Finishing details | G54.1 P3 |



## How To Run
1.  Open CLOCK.MPF file using a cnc software like WinNC
2.  Adjust the offsets in the software according to offsets.PNG file
3.  Run the program and see the finished product which is Roman Clock
