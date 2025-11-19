# Fuel Cell Controller — Hardware

This repository contains the KiCad schematic and PCB hardware design for the Fuel Cell Controller developed by **Lab-FuelCell-ITS**. The project includes complete KiCad source files, symbol/footprint libraries, and backups used for designing, modifying, and fabricating the controller board.

<!-- <img width="1049" height="713" alt="{BA82DBBF-16C6-43F1-AAF5-F1074114E6D2}" src="https://github.com/user-attachments/assets/8fef73a0-f4a1-47a8-a998-3048bcc98810" />
<img width="1056" height="700" alt="{CD6223DB-963B-4A11-8DCC-30DFFEBB6A86}" src="https://github.com/user-attachments/assets/9b73dac4-e640-4459-982e-8afceb8b78d7" /> -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/8fef73a0-f4a1-47a8-a998-3048bcc98810" height="400">
  <img src="https://github.com/user-attachments/assets/9b73dac4-e640-4459-982e-8afceb8b78d7" height="400">
</p>
---

## Features

- Full KiCad project (schematics + PCB layout)
- Custom symbol and footprint libraries
- Backup snapshots for restoration
- Ready for Gerber and BOM generation
- Structured for collaboration and long-term maintenance

---

## Repository Contents

- `fuelcell.kicad_pro` — main KiCad project file  
- `fuelcell.kicad_sch` — schematic  
- `fuelcell.kicad_pcb` — PCB layout  
- `fuel_cell_lib.kicad_sym` — symbol library  
- `fuel_cell_foot.pretty/` — footprint library  
- `fuelcell-backups/` — automatic KiCad backups  
- KiCad metadata: `fp-lib-table`, `sym-lib-table`, `fp-info-cache`, etc.

---

## Notes for next update
- CAN label flipped
- added more space between DC-DC connector
- Nextion should supplied from 5v

--- 

## Requirements

- **KiCad (v9 or newer)**  
  Older versions may open the project but can cause compatibility issues.
  
---

## BOM
[BOM](https://docs.google.com/spreadsheets/d/1h5o9iBbPZtMF7gXZkPm5TLBS_tpg8lyO8AkKIXZHr1Q/edit?gid=0#gid=0)

list belanja
---

## How to Open the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Lab-FuelCell-ITS/fuelcell_controller_hw.git
   cd fuelcell_controller_hw
