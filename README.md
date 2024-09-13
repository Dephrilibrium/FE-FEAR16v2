# Description
This repository groups all individual repositories necessary to build the F(ield) E(mission) A(rray) R(egulation) current control ciruit managed as submodules.

| SubModule                 | Description |
|:--------------------------|:------------|
| FE-FEAR16v2-PCB-Mainboard | KiCAD-Designfiles of the mainboard which can take up to 16 shield-PCBs. |
| FE-FEAR16v2-PCB-CathReg   | KiCAD-Designfiles for a single shield. Regulates the voltage of a device connected to its input, depending on the current flowing through the device under test (DUT). |
| FE-FEAR16v2-PCB-GridReg   | KiCAD-Designfiles for a single shield. Regulates the voltage of a device connected to its "Grid-input", depending on the current flowing through the secondary "Cath-input". |
| FE-FEAR16v2-Firmware      | Firmware for the mainboard. |