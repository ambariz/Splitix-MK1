# Production - Splitix MK1

## Production Files

### PCB (Gerbers)

* `gerber_left.zip` – Left half PCB
* `gerber_right.zip` – Right half PCB
* `gerber_full.zip` – Panelized full PCB

### Case (3D Models)

* `left_open_case.3mf` / `left_open_case.stl`
* `right_open_case.3mf` / `right_open_case.stl`
* `full_open_case.3mf` / `full_open_case.stl`

---

## Which Files Should You Use?

### PCB

> *NOTE:*
> full gerber or left and right gerber costs will be same. full gerber got mousebites, you can easily break in to left and right pcb.

* Printing seperately or any one side → `gerber_left.zip` + `gerber_right.zip`
* Printing both → `gerber_full.zip`

### Case

* Split case → left + right files
* Single-piece case → full files

### Other Formats

* Other fomates are in ```cad/3d_printing```

> *NOTE:*
> All formats contain the same models. You only need one.

---

## PCB Manufacturing

1. Go to any PCB manufacturer (JLCPCB, PCBWay, etc.)

2. Upload:
   ```
   gerber_left.zip
   gerber_right.zip
   ```
   or:
   ```
   gerber_full.zip
   ```
---

## Source Files
For modifications:
* PCB design → `/pcb/`
* Case models → `/cad/`
---
## Summary
* Use Gerber files to manufacture PCBs
* Use STL or 3MF files to print cases
* Choose split or full configuration based on your build
---
