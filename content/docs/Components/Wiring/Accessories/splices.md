---
title: Splices
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-09-21
---
## Overview

A splice joins two (or more) conductor ends together in-line, permanently, to extend a run or repair a break — distinct from a termination (ending a conductor at a lug or stud, covered on the Wire Lugs page), a twist-on connection (covered on the Wire Nuts page), and a multi-port distribution tap (covered on the Wire Taps page). This page covers the two families of hardware used to make that in-line joint: small-gauge crimp butt splices, and larger-conductor split-bolt and compression splice connectors.



**Butt splices** are the small-gauge, low-voltage workhorse: a metal barrel (with or without an insulating sleeve) that two stripped conductor ends are inserted into from opposite sides and crimped, joining them end-to-end in a straight line. They're sized to a specific AWG range like any crimp terminal, and come in several sleeve styles:

- **Non-insulated** — bare metal barrel only; used where the splice will be covered separately (heat-shrink tubing, tape, or an enclosure) or where the installer wants visual confirmation of a full, properly seated crimp.
- **Vinyl-insulated** — a colored plastic sleeve (color-coded to AWG range the same as insulated crimp terminals) snapped over the barrel; fastest to install, but the sleeve isn't sealed against moisture.
- **Heat-shrink (adhesive-lined)** — a heat-shrink sleeve, often with an internal adhesive lining that melts and flows under heat, forming a sealed, strain-relieved joint; the standard choice anywhere the splice may see moisture, vibration, or outdoor/direct-bury exposure.

**Split-bolt connectors** and **compression splice sleeves** step up to larger conductors — service entrance, feeder, or heavy branch-circuit splicing — where a crimped butt splice isn't practical:

- **Split-bolt connectors** — a bronze or copper-alloy body with a grooved channel that the conductors lay into side by side (not end-to-end), closed down by tightening a bolt that draws a wedge-shaped nut into the split body, biting into both conductors to make the connection. Reusable and field-adjustable without a crimping tool, but must be taped or covered afterward (a split bolt has no integral insulation) and is not rated for direct burial or submersion unless specifically listed for it.
- **Compression splice sleeves** — a plain metal barrel, larger and heavier-duty than a small-gauge butt splice, that the conductors are inserted into (either end-to-end or side-by-side, depending on sleeve style) and permanently crimped with a hydraulic or mechanical compression tool. Not reusable once crimped, but generally offers a lower-resistance, more vibration-resistant joint than a split bolt, and some styles are rated for direct burial or underground use when properly sealed.

Splices are selected based on:

1. **Conductor size (AWG/kcmil) and count** — the splice must be rated for the specific gauge(s) and number of conductors being joined; many models accept a small range (e.g., 16-14 AWG) or specific main/tap combinations for split bolts joining dissimilar conductor sizes.
2. **Conductor material** — copper, aluminum, or copper-to-aluminum (dissimilar-metal) splicing requires a connector specifically rated and listed for that combination (see Convention Notes); using a copper-only connector on aluminum conductors is a recognized fire hazard.
3. **Environment** — dry interior locations tolerate vinyl-insulated or taped non-insulated/split-bolt splices; wet, direct-bury, or high-vibration locations call for heat-shrink or a listed direct-bury/submersible splice kit.
4. **Method available** — crimp splices require a crimping tool matched to the connector's die specification; split bolts require only a wrench but must be torqued to the manufacturer's spec.
5. **Application/code context** — some splice types and installation methods (e.g., accessibility of the splice point, use of a junction box, direct-bury listing) are governed by NEC requirements rather than free choice.

## Further Resources

- Waytek – Butt Connectors, Crimp Connectors and Splice Connectors — reference on non-insulated, vinyl-insulated, and heat-shrink butt splice styles and AWG color coding.
- Delta Electronics – Using and Crimping Butt Splices: A Comprehensive Guide — practical crimping and heat-shrink sealing guidance.
- ConversionsTech – Split Bolt Connectors: Sizing, Torque, Taping, and Where the NEC Won't — guide on split-bolt sizing, torque specs, and code-compliant taping/insulating.
- UL 486A-486B — Wire Connectors (Splicing Wire Connectors) — governing listing standard for both butt splices and split-bolt/compression splice connectors, including dissimilar-metal (Al/Cu) ratings.
- National Electrical Code (NEC), NFPA 70 — Article 110.14(B) (Splices), governing that splices be made with devices identified for the purpose and that a splice be accessible unless specifically permitted otherwise (e.g., listed direct-bury or encapsulated splices).

## Naming Convention

When identifying splices for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE (CONDUCTORS-Conductor) SEALING STYLE Splice
```

### Example Names

- `18-AWG Aluminum-Conductor Heat-Shrink Butt Splice`
- `250-KCMIL Copper-Conductor Vinyl-Insulated Split-Bolt Splice`
- `16-AWG`

### Convention Notes

| Descriptor     | Explanation                                                                                                                                                                                                                                                       |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`         | The conductor gauge the splice is rated for (e.g., 18-AWG, 250-KCMIL), or a main/tap size pair for split bolts joining dissimilar conductor sizes (4-AWG-6-AWG).                                                                                                  |
| `(CONDUCTORS)` | Copper (copper-only conductors), Aluminum (aluminum-only), or Aluminum-Copper (specifically listed for joining dissimilar copper and aluminum conductors — never substitute a copper-only connector here). Assume Copper-Conductor as the default.                |
| `SEALING`      | Non-Insulated (bare, to be covered separately), Vinyl-Insulated (colored sleeve, dry locations), Heat-Shrink (sealed, adhesive-lined), Uninsulated (split bolts, taped after installation), or Direct-Bury (specifically listed for underground/submersible use). |
| `STYLE`        | Butt (small-gauge crimp barrel), Split-Bolt (bolted wedge connector for larger conductors), or Compression (heavy-duty crimped sleeve for larger conductors).                                                                                                     |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard for split-bolt and compression splices, especially in larger sizes.|
|**Pack**|Common small-gauge butt splice packaging, typically **10-25 per pack**.|
|**Box**|Standard bulk packaging for common butt splice sizes, typically **50-100 per box**.|
|**Case**|Distributor bulk quantity for large commercial or industrial projects.|

### Ordering Help

- Always confirm **conductor material** before ordering — a splice rated for copper-only must never be used to join aluminum conductors or a mixed copper-aluminum splice; use a connector specifically listed for the metal combination involved.
- For **wet, direct-bury, or vibration-prone locations**, specify a heat-shrink or listed direct-bury splice rather than a vinyl-insulated butt splice or a taped split bolt, which are not sealed against moisture intrusion.
- **Split bolts have no integral insulation** — always order (or stock separately) rubber/vinyl splicing tape or a cold-shrink cover to insulate the completed joint, and torque to the connector manufacturer's spec rather than "as tight as it'll go."
- Crimp splices (butt and compression) require a **crimping tool matched to the connector's die index/color code** — see the Wire Lugs page for the same die-index-vs-color-code distinction, which applies equally here.
- Per NEC 110.14(B), a splice generally must remain **accessible** after installation (inside a box or enclosure) unless the specific splice product is listed for direct burial or another permitted exception — confirm the installation location is code-compliant for the splice type ordered.