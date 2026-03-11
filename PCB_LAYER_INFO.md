# PCB Layer Information

## Board: Zio LiPo Battery Manager (Single Battery)

**Layer Count: 2-layer PCB**

### Copper Layers

| Layer | Name   | Status |
|-------|--------|--------|
| 1     | Top    | Active |
| 2     | Route2 | Inactive |
| 15    | Route15| Inactive |
| 16    | Bottom | Active |

Only Layer 1 (Top / F.Cu) and Layer 16 (Bottom / B.Cu) are active copper layers.
Internal routing layers (Route2, Route15) are defined in the Eagle layer stack but are **not active**.

### Gerber Files

The Gerber output confirms 2-layer manufacturing:

- `.GTL` — Top copper
- `.GBL` — Bottom copper
- `.GTS` — Top solder mask
- `.GBS` — Bottom solder mask
- `.GTO` — Top silkscreen
- `.GBO` — Bottom silkscreen
- `.GTP` — Top paste
- `.GBP` — Bottom paste
- `.GML` — Board outline (mill layer)

No internal copper layer Gerbers (e.g., `.G2`, `.G3`, `.GIN1`, `.GIN2`) are present.

### Source

- Eagle board file: `EAGLE/Zio LiPo Battery Manager.brd`
- Gerber output: `GERBER/`
