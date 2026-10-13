# Simple_PCB_Design
# KiCad LED Indicator PCB

## Project Overview

This is a beginner-level printed circuit board (PCB) project designed using KiCad. It implements a simple LED indicator circuit with through-hole components.

The project demonstrates the basic PCB design workflow, from schematic creation through PCB layout and manufacturing file generation.

## Objectives

- Create an electronic schematic.
- Assign through-hole component footprints.
- Arrange components and draw the PCB outline.
- Route copper tracks.
- Perform electrical and PCB design checks.
- Generate and inspect Gerber and drill files.

## Components

| Reference | Component | Value / Description |
|---|---|---|
| J1 | 2-pin connector | 2.54 mm pin header |
| R1 | Resistor | 330 Ω, axial through-hole |
| D1 | LED | 5 mm through-hole LED |

**Note:** Physical component dimensions and LED polarity must be verified before fabrication.

## Tools Used

- KiCad
- KiCad Schematic Editor
- KiCad PCB Editor
- KiCad Electrical Rules Checker (ERC)
- KiCad Design Rules Checker (DRC)
- KiCad Gerber Viewer

## Project Files

- `PCB_Learning.kicad_pro` — project settings
- `PCB_Learning.kicad_sch` — schematic
- `PCB_Learning.kicad_pcb` — PCB layout
- `manufacturing/` — Gerber and drill outputs
- `images/` — screenshots of the design

## Design Workflow

1. Created the project and schematic.
2. Connected the resistor, LED, and power connector.
3. Assigned THT footprints.
4. Updated the PCB from the schematic.
5. Arranged the component footprints.
6. Created the board outline on the Edge.Cuts layer.
7. Routed the copper tracks.
8. Ran ERC and DRC checks.
9. Generated Gerber and drill files.
10. Inspected the manufacturing outputs in Gerber Viewer.

## Manufacturing Notes

The Gerber and drill files are provided as fabrication outputs. Review the design, check the component pinout and footprint dimensions, and verify manufacturer requirements before ordering a physical board.

## Learning Outcomes

This project provided hands-on practice with schematic capture, through-hole footprint assignment, PCB layout, copper routing, design-rule checking, and manufacturing file generation.

## Status

Beginner learning project. Final electrical and manufacturing validation should be completed before production.

## 3D PCB View

![3D view of the LED indicator PCB](images/pcb-3d-view.png)
