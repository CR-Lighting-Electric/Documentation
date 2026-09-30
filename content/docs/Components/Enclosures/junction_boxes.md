---
title: Junction Boxes
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-09-23
---
## Overview

A junction box is an enclosure used purely to house conductor splices, taps, or pull points — not to mount a switch, receptacle, or other device. This distinguishes it from the Square Boxes covered elsewhere in this subcategory, which (via a plaster ring) are usually the base for a device; a junction box's cover is typically blank, screwed or hinged shut, and meant to stay closed except for maintenance access. Junction boxes range from small single-gang-sized enclosures up through large pull boxes, and are selected largely by environment, material, and size rather than by device compatibility.

![](/images/junction-box-example.png)

Junction boxes are selected based on:

1. **Material:**
    - **Steel (carbon steel, powder-coated)** — the standard indoor choice; provides mechanical protection and, when part of a metal raceway system, a bonding path.
    - **Stainless steel (304/316)** — for corrosive, washdown, or sanitary environments where standard steel would rust; 316 for the most aggressive (coastal, chemical) exposure.
    - **Aluminum** — lighter weight than steel with good corrosion resistance for many outdoor applications, without the cost of stainless.
    - **PVC/nonmetallic** — fully nonmetallic construction for the most corrosion-prone environments (wastewater treatment, marine, car washes, agricultural, chemical washdown areas); no bonding path, and not a substitute for steel where mechanical protection is the priority.
2. **NEMA/Type rating** — matched to the installation environment:
    - **Type 1** — general-purpose indoor use, no specific ingress protection beyond basic enclosure.
    - **Type 3R** — outdoor use, protects against rain and ice formation but not a watertight seal.
    - **Type 4/4X** — watertight and dust-tight; Type 4X adds corrosion resistance, used for washdown or corrosive outdoor/indoor environments.
    - **Type 12** — indoor use, protects against dust, dripping water, and non-corrosive liquids; common in industrial indoor settings.
3. **Cover type** — a **screw cover** (flat cover held by perimeter screws) is standard for Type 1 indoor use; a **continuous-hinge/clamp gasketed cover** provides the sealed closure needed for Type 3R/4/4X/12 ratings, using a gasket (e.g., a Poron or molded gasket) compressed around the full perimeter.
4. **Size** — junction boxes range from small (roughly 4"x4"x2") up to large pull boxes (16"x16"x10" or larger); size must accommodate box-fill volume for the conductors, splices, and any devices such as wire nuts or terminal blocks inside (see NEC 314.16 and 314.28 for pull/junction box sizing rules, which differ from standard device box-fill rules for larger conductors).
5. **Knockouts vs. no knockouts** — steel junction boxes typically have pre-formed knockouts sized for common conduit sizes; nonmetallic boxes may ship as plain-wall enclosures requiring field-drilled/hole-sawed conduit entries, or with knockouts depending on the product line.

## Further Resources

- [NEMA Enclosures – Junction Box Enclosure Manufacturer](https://www.nemaenclosures.com/types/junction-box/) — reference on steel, stainless steel, and aluminum junction box materials, cover styles, and NEMA/IP rating overview.
- [IPEX – Scepter JBox PVC Junction Box](https://ipexna.com/solutions/electrical-solutions/rigid-pvc-conduit-fittings/scepter-jbox-pvc-junction-box/) — manufacturer reference for nonmetallic PVC junction boxes, size range, NEMA ratings, and gasketed cover design.
- [Polycase – Exploring Different Types of NEMA 4X Junction Boxes](https://www.polycase.com/techtalk/nema-rated-enclosures/exploring-different-types-of-nema-4x-junction-boxes.html) — overview of NEMA 4X-rated junction box construction and use cases.
- [Eaton – Type 3 and 3R Junction Boxes](https://www.eaton.com/us/en-us/catalog/enclosures/type-3-3r-junction-boxes.html) — manufacturer reference on Type 3R outdoor-rated junction box construction.
- National Electrical Code (NEC), NFPA 70 — Article 314.16 (Number of Conductors in Outlet, Device, and Junction Boxes) and Article 314.28 (Pull and Junction Boxes, sizing for conductors 4 AWG and larger), governing box-fill and pull/junction box minimum dimension requirements.

## Naming Convention

When identifying junction boxes for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE RATING (MATERIAL) (COVER) Junction-Box
```

### Example Names

- `6"-6"-4" NEMA-1 Steel Screw-Cover 6"-6"-4" Junction-Box`
- `8"-8"-4" NEMA-3R Steel Hinged-Gasketed Junction-Box`
- `6"-6"-4" NEMA-4X Stainless-Steel Hinged-Gasketed Junction-Box`
- `4"-4"-2" NEMA-4X PVC Screw-Cover Junction-Box`
- `8"-8"-6" NEMA-4 Junction-Box`
- `48"-48"-12" NEMA-1 Junction-Box`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                                                                      |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | The box's interior dimensions (width x height x depth, e.g., 6x6x4in), sized for box-fill volume per NEC 314.16/314.28 based on conductor count, splices, and any internal devices.                                                                                              |
| `RATING`     | The NEMA/Type enclosure rating (e.g., NEMA-1 general indoor, NEMA-3R outdoor/rain, NEMA-4 watertight, NEMA-4X watertight plus corrosion-resistant, NEMA-12 indoor dust/drip-tight), matched to the installation environment.                                                     |
| `(MATERIAL)` | Steel (standard indoor, mechanical protection/bonding), Stainless-Steel (corrosive/washdown environments, specify 304 or 316 grade separately if needed), Aluminum (lighter-weight outdoor corrosion resistance), or PVC (fully nonmetallic, most corrosion-prone environments). |
| `(COVER)`    | Screw-Cover (flat perimeter-screw cover, standard for Type 1) or Hinged-Gasketed (continuous-hinge or clamp cover with a compressed gasket, required for sealed Type 3R/4/4X/12 ratings). Default to Screw-Cover.                                                                |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for individual junction boxes across all sizes.|
|**Case**|Distributor bulk quantity for large commercial or industrial projects, typically for smaller standard sizes.|

### Ordering Help

- Always match **NEMA/Type rating to the actual installation environment**, not just indoor-vs-outdoor as a general idea — a Type 3R box protects against rain but is not watertight, while a true washdown or submersible-adjacent environment needs Type 4X specifically.
- Size the box using **box-fill/pull-box sizing rules appropriate to the conductors involved** — NEC 314.28 governs minimum dimensions for pull and junction boxes containing conductors 4 AWG and larger differently than the standard 314.16 volume-based method used for smaller conductors and device boxes.
- For **corrosive or washdown environments**, weigh stainless steel against PVC — stainless offers mechanical strength and bonding capability that PVC doesn't, while PVC avoids corrosion entirely but has no bonding path and generally lower mechanical/impact resistance.
- Confirm **cover type matches the rating** — a screw cover alone does not achieve a Type 4/4X/12 sealed rating; that requires the gasketed hinged or clamp-style cover construction.
- For **larger pull boxes**, confirm knockout pattern (or lack thereof, for field-drilled nonmetallic boxes) against the actual conduit sizes and entry points needed, since junction/pull boxes are frequently used as a consolidation point for multiple conduit runs.