---
title: Gutter Boxes
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-09-28
---
## Overview

A gutter box (auxiliary gutter or wiring trough) is a long, sheet-metal (or nonmetallic) enclosure with a hinged or removable cover, used to supplement the wiring space at meter centers, panelboards, switchboards, switchgear, and similar equipment. It's not a junction box in the everyday sense — it's a code-recognized extension of wiring space, used where the equipment itself doesn't provide enough room for the conductors, splices, and taps entering or leaving it, and it's governed by its own NEC article (366) rather than the box-fill rules that apply to standard device and junction boxes.

![](/images/gutter-box-example.png)

Key characteristics that distinguish a gutter box from other enclosures on this list:

- **Extension length limit** — an auxiliary gutter cannot extend more than 30 ft beyond the equipment it supplements (with a narrow elevator-related exception), since it's meant to supplement wiring space near equipment, not function as a long-distance raceway substitute.
- **Fill is percentage-based, not cubic-inch-based** — unlike standard box fill (NEC 314.16), a gutter's conductor fill is limited to 20% of its interior cross-sectional area at any point, and where splices or taps are made, the gutter can be filled to no more than 75% of its area at that point.
- **Construction requirements** — must provide a complete enclosure for the conductors, maintain electrical and mechanical continuity, be corrosion-protected, and use covers/fasteners spaced no more than 12" apart; conductor entry points must be smooth and rounded to avoid insulation damage, and a minimum 2" clearance is required between bare live parts of different voltage systems within the gutter.

Gutter boxes are selected based on:

1. **Material** — Steel (standard, requires bonding/grounding as part of the equipment grounding path) or Nonmetallic (for corrosive environments, no bonding path).
2. **NEMA/Type rating** — matched to the installation environment, most commonly Type 1 for indoor use or Type 3R for outdoor use where rain/ice protection is needed; higher ratings (Type 4/4X/12) apply in the same manner as other enclosures on this list where washdown or corrosive exposure is present.
3. **Cross-sectional size (width x height)** — sized so the conductor fill stays within the 20% limit (or 75% at splice/tap points) for the actual conductors being run, which for larger conductor counts or larger AWG/kcmil sizes means a larger gutter cross-section, not just a longer one.
4. **Length** — sized to the actual run needed to supplement the equipment's wiring space, always within the 30 ft extension limit from the equipment being supplemented.
5. **Cover type** — hinged (continuous-hinge, faster access for frequently-serviced runs) or removable/screw-on (standard bolted or screwed cover, common where access is infrequent).

## Further Resources

- [The NEC Wiki – Article 366: Auxiliary Gutters](https://thenecwiki.com/2021/02/article-366/) — summary of NEC Article 366 purpose, the 30 ft extension limit, 20%/75% fill limits, and construction requirements.
- [Mike Holt's Forum – Article 366 Auxiliary Gutters](https://forums.mikeholt.com/threads/article-366-auxiliary-gutters.113606/) — field discussion of auxiliary gutter application and code interpretation.
- [Jake Leahy's Electrical Code Connection – How to Calculate Auxiliary Gutter Fill 366.22(A),(B)](http://electricalcodeconnection.com/how-to-calculate-auxiliary-gutter-fill-366-22ab/) — worked reference on calculating gutter fill percentage.
- National Electrical Code (NEC), NFPA 70 — Article 366 (Auxiliary Gutters), the governing article for this product, including 366.22 (Fill Capacity of Conductors) and 366.12 (Extension Beyond Equipment).

## Naming Convention

When identifying gutter boxes for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE RATING (MATERIAL) (COVER) Gutter-Box
```

### Example Names

- `6"-6"-48" NEMA-1 Gutter-Box`
- `8"-8"-72" NEMA-3R Stainless-Steel Gutter-Box`
- `4"-4"-36" NEMA-4x Gutter-Box`
- `8"-8"-60" NEMA-3R Aluminum Gutter-Box`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                       |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | The gutter's interior cross-sectional dimensions (width-height-length), sized so conductor fill stays within the NEC 366.22 20%/75% limits for the conductors being run.                                          |
| `RATING`     | The NEMA/Type enclosure rating (e.g., Type-1 general indoor, Type-3R outdoor/rain, Type-4X watertight plus corrosion-resistant), matched to the installation environment.                                         |
| `(MATERIAL)` | Steel (standard, requires bonding as part of the equipment grounding path), Stainless-Steel (corrosive/washdown environments), or Nonmetallic (fully nonmetallic, no bonding path).                               |
| `(COVER)`    | Screw-Cover (flat perimeter-screw cover, standard for Type 1) or Hinged-Gasketed (continuous-hinge or clamp cover with a compressed gasket, required for sealed Type 3R/4/4X/12 ratings). Default to Screw-Cover. |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for individual gutter sections.|
|**Case**|Distributor bulk quantity for large commercial or industrial switchgear/panelboard projects.|

### Ordering Help

- Always check the **20% conductor fill limit** (and 75% at any point with splices or taps) against the actual conductor count and size before finalizing cross-sectional size — this is a percentage-of-area calculation under NEC 366.22, distinct from the cubic-inch box-fill method used for standard device and junction boxes.
- Confirm the **30 ft extension limit** from the equipment being supplemented — a run planned longer than that needs a different wiring method (e.g., conduit and a separate junction/pull box) rather than a longer auxiliary gutter.
- Match **NEMA/Type rating to the installation environment**, the same as other enclosures — Type 1 for indoor equipment rooms, Type 3R minimum for any outdoor gutter run.
- Where **different voltage systems** share the same gutter run, confirm the minimum 2" clearance requirement between bare live parts is maintainable at the planned conductor layout before committing to a cross-sectional size.
- Gutter boxes are typically ordered as part of a **larger equipment lineup** (alongside the panelboard, switchgear, or meter center they supplement) — confirm sizing and layout against the equipment manufacturer's or engineer's drawings rather than sizing in isolation.

_Generated Schematic_
![](/images/gutter-box-schematic.png)