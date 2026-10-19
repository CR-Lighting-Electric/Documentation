---
title: Pull Boxes
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-10-01
---
## Overview

A pull box is a large enclosure installed along a conduit run specifically to provide a point for pulling conductors through — easing the tension and bend stress on long or multi-bend raceway runs — rather than to house splices, taps, or devices the way a standard Junction Box does (see the Junction Boxes page). The two pages overlap in general construction and are often the same physical product line, but this page focuses specifically on boxes sized under **NEC 314.28**, the dimension-based method that applies to boxes containing conductors 4 AWG and larger, as distinct from the cubic-inch volume method (NEC 314.16) used for standard device and junction boxes with smaller conductors.

![](/images/pull-box-example.png)

NEC 314.28 sizing depends on how the conductors pull through the box:

- **Straight pull** — conductors enter and exit through raceways on opposite walls without changing direction inside the box; the box's length (in the direction of the pull) must be at least **8 times the trade size of the largest raceway** entering that wall.
- **Angle pull or U-pull** — conductors change direction inside the box (entering and exiting on adjacent or the same wall); the distance from the entry wall to the opposite wall must be at least **6 times the trade size of the largest raceway in that row, plus the sum of the trade sizes of all other raceways in the same row on that wall**.
- **Raceway spacing** — where multiple raceways on the same wall are used for an angle pull, the distance between any two raceways must be at least **6 times the trade size of the larger of the two**.
- **Accessibility** — per NEC 314.29, a pull box must remain accessible without removing building structure or permanent fixtures; pull boxes are not meant to be buried behind finished walls or ceilings once installed.

Pull boxes are selected based on:

1. **Pull geometry** — straight, angle, or U-pull, which determines the minimum box dimensions per 314.28; this is a design calculation based on the actual raceway layout rather than a fixed product attribute, so box size is calculated per installation rather than picked from a standard size chart the way a small device box might be.
2. **Material** — Steel (standard indoor, mechanical protection/bonding path), Stainless-Steel (304/316, corrosive or washdown environments), Aluminum (lighter-weight outdoor corrosion resistance), or PVC/nonmetallic (fully nonmetallic, most corrosion-prone environments, no bonding path).
3. **NEMA/Type rating** — matched to the installation environment, same ratings as standard junction boxes (Type 1 indoor, Type 3R outdoor/rain, Type 4/4X watertight, Type 12 indoor dust/drip-tight).
4. **Cover type** — Screw-Cover (flat perimeter-screw cover) for Type 1 indoor use, or Hinged-Gasketed for sealed Type 3R/4/4X/12 ratings; larger pull boxes commonly use a bolted or hinged cover sized to the full box opening for ease of conductor access during the pull.
5. **Size** — the box's actual interior dimensions, calculated from the specific raceway sizes and pull geometry per NEC 314.28 rather than selected from a general-purpose size range.

## Further Resources

- [VoltageLab – Pull Box & Junction Box Sizing: NEC Rules with Chart](https://www.voltagelab.com/pull-box-junction-box-sizing/) — reference on NEC 314.28 straight pull (8x trade size), angle/U-pull (6x trade size plus other entries), and same-wall raceway spacing requirements.
- [NEMA Enclosures – Junction Box Enclosure Manufacturer](https://www.nemaenclosures.com/types/junction-box/) — reference on steel, stainless steel, and aluminum enclosure materials, cover styles, and NEMA/IP rating overview, applicable to pull boxes as well as standard junction boxes.
- [Eaton – Type 3 and 3R Junction Boxes](https://www.eaton.com/us/en-us/catalog/enclosures/type-3-3r-junction-boxes.html) — manufacturer reference on Type 3R outdoor-rated enclosure construction.
- National Electrical Code (NEC), NFPA 70 — Article 314.28 (Pull and Junction Boxes, sizing for conductors 4 AWG and larger) and Article 314.29 (Boxes to Be Accessible).

## Naming Convention

When identifying pull boxes for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE (SHAPE) (DEPTH-Depth) (RATING) COVER MATERIAL Pull-Box
```

### Example Names

- `24"-24"-8" NEMA-1 Hinged-Cover Steel Pull-Box`
- `12"-18"-6" NEMA-3R Screw-Cover Stainless-Steel Pull-Box`
- `9" Round 10"-Depth Bolted-Cap PVC Pull-Box`

### Convention Notes

| Descriptor | Explanation                                                                                                                                                                                                                                                                                                                |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`     | The box's calculated interior dimensions (length x width x depth, e.g., 24x8x8in), derived from NEC 314.28 straight-pull (8x largest raceway trade size) or angle/U-pull (6x largest raceway trade size plus the sum of other entries) formulas for the specific raceway layout — not a standard off-the-shelf size range. |
| `(SHAPE)`  | Some pull boxes can come in a Round variant without any sort of square sizing, instead it has a diameter and a depth. Use "Round" for the round version, and default to square if omitted.                                                                                                                                 |
| `(DEPTH)`  | Optional depth specifier if the depth is left off of `SIZE`, or if the `SHAPE` is Round, then it should have a depth specifier. If omitted, the size should include a depth measurement.                                                                                                                                   |
| `(RATING)` | The NEMA/Type enclosure rating (e.g., NEMA-1 general indoor, NEMA-3R outdoor/rain, NEMA-4 watertight, NEMA-4X watertight plus corrosion-resistant, NEMA-12 indoor dust/drip-tight), matched to the installation environment.                                                                                               |
| `COVER`    | Screw-Cover (flat perimeter-screw cover, standard for Type 1) or Hinged-Gasketed (continuous-hinge or bolted cover with a compressed gasket, required for sealed Type 3R/4/4X/12 ratings).                                                                                                                                 |
| `MATERIAL` | Steel (standard indoor, mechanical protection/bonding), Stainless-Steel (corrosive/washdown environments, specify 304 or 316 grade separately if needed), Aluminum (lighter-weight outdoor corrosion resistance), or PVC (fully nonmetallic, most corrosion-prone environments).                                           |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit; pull boxes are ordered and sized individually per installation.|

### Ordering Help

- Calculate the required size from the **actual raceway layout before ordering** — straight pulls, angle/U-pulls, and mixed-geometry pulls on the same box each have a different minimum-dimension formula under NEC 314.28, and the box must satisfy the formula for every entry/exit combination present, not just the largest raceway in isolation.
- Confirm **raceway spacing on the same wall** for any angle pull — the minimum 6x-trade-size spacing between adjacent raceways on one wall is a separate requirement from the overall box dimension and is easy to miss when laying out multiple conduit entries.
- Remember that **pull boxes must stay accessible** per NEC 314.29 — don't plan a pull box location that will end up behind a permanently finished wall, ceiling, or inaccessible equipment once construction is complete.
- Larger or non-standard calculated dimensions are often **custom/made-to-order** rather than a stock size — confirm lead time with the vendor before committing to an installation schedule, especially on larger conduit runs with multiple large raceways.
- Match **material and NEMA/Type rating to the environment**, the same as standard Junction Boxes — a pull box installed outdoors or in a washdown area needs the same Type 3R/4X consideration as any other enclosure on this list, not just mechanical sizing.

![](/images/pull-box-schematic.png)