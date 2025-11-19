# Fuel Cell Controller — Hardware

This repository contains the KiCad schematic and PCB hardware design for the Fuel Cell Controller developed by **Lab-FuelCell-ITS**. The project includes complete KiCad source files, symbol/footprint libraries, and backups used for designing, modifying, and fabricating the controller board.

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

## Requirements

- **KiCad (v9 or newer)**  
  Older versions may open the project but can cause compatibility issues.

Optional but useful:
- Gerber viewer (KiCad viewer, gerbv, or online tools)
- Spreadsheet editor for BOM handling
- PCB manufacturer preview tools

---

## How to Open the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Lab-FuelCell-ITS/fuelcell_controller_hw.git
   cd fuelcell_controller_hw
