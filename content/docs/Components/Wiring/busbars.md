---
title: Busbars
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
imported:
date: 2026-10-12
---
## Overview

A busbar is a solid metal bar, usually copper or aluminum, that carries current or provides a common connection point for several conductors. It replaces a bundle of splices or a chain of lugs with one conductive bar that conductors land on. On electrical orders it shows up in several forms: ground and neutral bars in panelboards, telecommunications grounding busbars, loose flat bar stock cut and drilled for a custom assembly, and terminal or distribution bars in control and power enclosures. This page covers the busbars bought as separate line items, not the main and phase bus built into a panelboard or switchboard.

![](/images/busbar-example.png)

The role of the bar sets how it is sized:

- **Ground bar** — the equipment grounding and bonding connection point. It carries no current in normal operation, so it is sized for fault current and clearing time, not for load.
- **Neutral bar** — collects the return current from the loads and is normally sized to match the phase bars. It can need to be larger where non-linear loads produce triplen harmonics.
- **Telecommunications grounding busbars** — a solid copper bar with a standard hole pattern, mounted on insulators, used as the bonding point for telecommunications grounding. The main bar (TMGB) is the building's main telecommunications ground, and the secondary bar (TGB) serves each telecommunications room. They follow the ANSI/TIA-607 recommendations.
- **Flat bar stock** — a plain copper or aluminum bar sold by thickness, width, and length, cut and drilled in the shop or field for a custom bus or bonding job.
- **Terminal (distribution) bars** — a bar with a row of screw or stud terminals that lets several conductors share one connection point in a control or power enclosure; often insulated or enclosed for safety.

Busbars are selected based on:

1. **Type** — Panel-Ground or Panel-Neutral for a panelboard kit, Telecom-Ground for TMGB and TGB work, Flat-Stock for a custom bar, Terminal for a distribution bar.
2. **Material** — Copper for compact, high-reliability, or corrosion-sensitive installations; Tin-Plated-Copper where extra corrosion resistance is wanted; Aluminum where weight and cost matter on large runs. Aluminum has lower conductivity and needs roughly 1.6 times the cross-section of copper for the same duty, and it needs proper transition hardware to avoid galvanic corrosion.
3. **Size** — thickness by width by length for bar stock and telecom bars (for example, 1/4" x 4" x 12"); for panelboard kits, the terminal count and the length of the kit.
4. **Termination** — the hole pattern or terminal count: Unpunched for plain stock, TIA-607 for the telecom hole pattern, or a stated terminal count (for example 9, 12, or 18 terminals) for a panelboard kit.
5. **Compatibility and listing** — panelboard kits are made for a specific panel family; telecom bars are UL 467 listed; panelboard kits carry their own listing (for example, the Square D PK18GTA complies with UL 67).

## Further Resources

- [Payapress – What Is a Busbar in an Electrical Panel? Function, Types and Sizing](https://payapress.com/busbar-in-electrical-panels/) — reference on main, neutral, and ground bars, copper vs. aluminum, and first-pass sizing.
- [Payapress – Terminal Bus Bars: Types, Sizing, Wiring and Standards](https://payapress.com/terminal-bus-bar/) — reference on insulated and grounding terminal bars, plating, UL 508A and UL 1059 context, and torque practice.
- [Watteredge – Telecommunications Grounding and Main Grounding Busbars](https://www.watteredge.com/product/grounding-and-earthing-products/telecommunications-grounding-and-main-grounding-busbars/) — manufacturer reference for TGB and TMGB bars, copper construction, two-hole lug patterns, insulators and brackets, and UL 467 listing.
- [Harger – TMGB Hole Pattern](https://www.harger.com/product/tmgb-hole-pattern) — manufacturer reference for 1/4" x 4" TMGB bars from 10" to 48" long, with their hole sets.
- [Schneider Electric – PK18GTA Ground Bar Kit, 18 Terminals](https://www.se.com/us/en/product/PK18GTA/load-center-accessory-qo-homeline-ground-bar-kit-18-terminals/) — manufacturer reference for a panelboard ground bar kit and its UL 67 listing.
- National Electrical Code (NEC), NFPA 70 — Article 250 (Grounding and Bonding) and Article 408 (Switchboards, Switchgear, and Panelboards).
- ANSI/TIA-607 — the telecommunications bonding and grounding standard that the TMGB and TGB bars follow.

## Naming Convention

When identifying busbars for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPE MATERIAL TERMINATION Busbar
```

### Example Names

- `1/4"-4"-12" Telecom-Ground Copper TIA-607 Busbar`
- `1/4"-4"-24" Telecom-Ground Copper TIA-607 Busbar`
- `1/4"-4"-12" Flat-Stock Copper Unpunched Busbar`
- `1/4"-2"-12" Flat-Stock Aluminum Unpunched Busbar`
- `Panel-Ground Aluminum 18-Terminal Busbar`
- `Panel-Neutral Copper 12-Terminal Busbar`
- `Terminal Tin-Plated-Copper 12-Terminal Busbar`

### Convention Notes

| Descriptor    | Explanation                                                                                                                                                                                                                 |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`        | Thickness x width x length in inches (for example 1/4x4x12in) for stock and telecom bars; omit for kits and terminal bars sold by terminal count.                                                                           |
| `TYPE`        | Panel-Ground (panelboard equipment ground bar kit), Panel-Neutral (panelboard neutral bar kit), Telecom-Ground (TMGB or TGB), Flat-Stock (plain bar cut and drilled to suit), or Terminal (screw or stud distribution bar). |
| `MATERIAL`    | Copper, Tin-Plated-Copper, or Aluminum. NA for a panelboard kit whose datasheet does not state the material; confirm it in the datasheet.                                                                                   |
| `TERMINATION` | Unpunched (plain stock), TIA-607 (telecom hole pattern for two-hole lugs), or the terminal count (for example 9-Terminal, 12-Terminal, 18-Terminal).                                                                        |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for panelboard kits, telecom bars, and cut-to-length stock pieces.|
|**Kit**|Panelboard ground and neutral bars, sold with their mounting hardware.|
|**Foot (FT)**|Bar stock sold by the foot or in stock lengths and cut to order.|

### Ordering Help

- Match the bar to its **job**: a ground bar is sized for fault current and clearing time, not load, while a neutral bar is normally sized to match the phase bars and can need to be larger on circuits with non-linear loads.
- Order panelboard ground and neutral kits **by panel family**; a kit made for one manufacturer's load center is not a substitute in another's, so confirm the panel catalog number before ordering. Equipment grounding and neutral bars are kept as separate bars in a subpanel (see NEC 408.40).
- For **telecommunications grounding**, order the TIA-607 pattern bar, which typically ships assembled with insulators and stand-off brackets and is UL 467 listed. Use the TMGB as the main building bar and the TGB in each telecommunications room.
- Choose **copper unless weight and cost drive aluminum**. If aluminum is used, plan for the larger cross-section, the transition hardware, and the extra care joints need.
- Take the **ampacity from the vendor's tables** for the cross-section, and treat custom high-current assemblies as engineered work (temperature rise and short-circuit withstand), not a catalog pick.
- Follow the **torque specification for lugs and studs**; an under-torqued connection overheats and an over-torqued one can deform the bar.

_Generated Schematic_
![](/images/busbar-schematic.png)