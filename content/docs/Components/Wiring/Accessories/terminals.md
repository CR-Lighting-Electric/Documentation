---
title: Wire Terminals
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-07-10
---
## Overview

Terminals are crimp-on connectors that terminate a single conductor end for connection to a screw, stud, or a mating blade tab — as distinct from wire lugs, which are sized for larger power conductors and bolt to a stud or bus bar, and multi-tap connectors, which split one conductor into several without cutting it. Terminals are the small-gauge, high-volume hardware used throughout control wiring, automotive and appliance wiring, and general low-voltage connections. 

![](/images/terminal-example.png)

The core styles are:

- **Ring terminal** — a closed circular end secured under a bolt or screw, offering a vibration-resistant, maximum-security connection since the fastener must be fully removed to disconnect it.
- **Spade/fork terminal** — a U-shaped, open-ended fork that slides under a loosened screw head without fully removing it, trading some security for much faster connection and disconnection.
- **Butt splice connector** — a cylindrical barrel that joins two wires end-to-end, available in a heat-shrinkable form for environmental sealing.
- **Quick-disconnect/blade terminal** — a flat blade-and-receptacle pair designed for rapid assembly and disassembly, commonly found in automotive applications and household appliances.

Nearly all small-gauge terminals follow a common **color-coding convention** by wire gauge range, though this convention — like wire nut colors — is an industry norm rather than a mandatory standard and should be confirmed against the specific product's printed range:

|Color|Typical AWG Range|
|---|---|
|Red|22–18 AWG|
|Blue|16–14 AWG|
|Yellow|12–10 AWG|

Larger terminals (8 AWG and up) generally drop the color-coding convention and are sized by gauge and stud/tab dimension directly on the packaging.

## Further Resources

- [ConnectorSupplier – What Are Crimp Terminals?](https://connectorsupplier.com/what-are-crimp-terminals/) — overview of ring, spade, butt splice, and blade terminal construction and history.
- [OurPCB – Wire Harness Terminal Types: Ring, Spade, Pin & Crimp Terminal Selection Guide](https://customwireassembly.com/resources/learning-center/wire-harness-terminal-types-selection-guide/) — detailed sizing, plating, and crimp specification reference across terminal families.
- [UL 486A-486B / UL 486C – Wire Connectors and Splicing Wire Connectors](https://www.shopulstandards.com/) — the UL safety standards governing crimp terminal and splice connector construction and pull-out force testing.
- National Electrical Code (NEC), NFPA 70 — Article 110.14 (Electrical Connections), governing the requirement that terminals be identified for the conductor material and properly installed.

## Naming Convention

When identifying terminals for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE STYLE WIRE (INSULATION) Terminal
```

### Example Names

- `1/2" Spade 16-AWG Heat-Shrink Terminal`
- `M6 Ring 14-AWG Insulated Terminal`
- `M4 Quick-Disconnect 22-AWG Insulated Terminal`

### Convention Notes

| Descriptor     | Explanation                                                                                                                                               |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`         | The SIZE field — stud/hole diameter for ring terminals, or blade/fork width for spade and quick-disconnect styles.                                        |
| `STYLE`        | The terminal style. Specify Male or Female for Quick-Disconnect, since these mate as a pair.                                                              |
| `WIRE`         | The AWG field — the supported wire gauge range, written low-to-high. Always confirm against the specific product's printed range rather than color alone. |
| `(INSULATION)` | The INSULATION field. Heat-Shrink implies insulated with an added sealed, waterproof barrel.                                                              |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Occasionally used for large or specialty terminals, but uncommon as a standalone ordering unit for small sizes.|
|**Bag/Pack**|Most common small-quantity packaging, typically **10, 25, 50, or 100 per pack**.|
|**Box/Jar**|Common bulk packaging for jobsite or truck stock, typically **100 or 500 per jar/box**.|
|**Assortment Kit**|Multi-size, multi-style kits covering a spread of gauges and styles in one package — useful for stock but not for a single specified order.|
|**Case**|Distributor bulk quantity made up of multiple boxes or jars; used for large project takeoffs.|

### Ordering Help

- Always specify **style, size, and AWG range** together — color alone is a helpful visual sort but is not a substitute for confirming the printed wire range, especially across different manufacturers.
- Confirm which **crimping tool** (standard hand crimper vs. a ratcheting die-specific tool) is compatible with the terminal style ordered.
- Avoid ordering **assortment kits** for a specified job — they're useful for general stock or field trucks, but a designed installation should specify exact style/size/gauge combinations as discrete line items to avoid running short on the specific size actually needed.
- For **wet, outdoor, or vibration-prone environments**, specify Heat-Shrink or fully-insulated terminals rather than standard non-insulated construction.

_Generated Schematic_
![](/images/terminal-schematic.png)