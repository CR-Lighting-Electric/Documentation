---
title: Tie Wire
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-08-24
---
## Overview

Tie wire is soft, fully annealed steel wire used to secure and bundle conductors, cable, and raceway during installation — most commonly to tie conduit or cable runs to rebar prior to a concrete pour (see the Stub Downs page), to bundle conductors together in cable tray or on a rack, or to secure cable to a messenger strand or support structure. The annealing process removes work-hardening from the wire, leaving it soft and pliable enough to twist tightly by hand or with a rebar tie tool while still holding its shape once twisted — this pliability, not raw tensile strength, is what distinguishes tie wire from general-purpose steel wire.

![](/images/tie-wire-example.png)

Tie wire is selected based on:

1. **Gauge** — common tie wire gauges are 14, 15, 16, 16.5, 17, and 18, with **16 gauge** (approximately 0.0625" / 1.6 mm diameter) the most widely used size for general tying and rebar work. Lower gauge numbers indicate thicker, stronger wire; higher gauge numbers indicate thinner, more flexible wire suited to lighter bundling tasks.
2. **Material/finish:**
    - **Black annealed steel** — the standard, most commonly used and most economical tie wire, suitable for general indoor use and typical construction tying.
    - **Galvanized annealed steel** — adds a zinc coating over the annealed wire for improved corrosion resistance compared to plain black annealed wire, at a modest cost premium.
    - **Stainless steel (304 or 316)** — used in corrosive, coastal, or long-service-life applications; non-magnetic and highly resistant to rust and staining, at a significant cost premium over galvanized or black annealed wire. Type 316 offers additional corrosion resistance over 304 for the most demanding marine/coastal environments.
    - **PVC-coated (color) wire** — used specifically with epoxy-coated rebar, where an uncoated wire could scratch through and compromise the rebar's epoxy coating; PVC-coated tie wire is typically produced to a minimum coating thickness (commonly 7 mil) for this purpose and is often color-coded (e.g., yellow) to visually distinguish it on site.
3. **Packaging weight/length** — tie wire is sold by coil weight rather than a fixed piece count, with the actual usable length varying by both weight and gauge (e.g., a 3.5 lb coil of 16-gauge wire yields roughly 320–340 ft).

**Important note:** tie wire is rated for tying and securing only — it is explicitly **not rated for lifting or load-bearing suspension** of any material, including conduit, rebar, or cable tray, regardless of gauge or material. It should not be confused with plastic cable ties (zip ties), which are a separate nylon fastener product with their own tensile rating and are not interchangeable with steel tie wire for rebar or high-heat applications.

## Further Resources

- [American Wire Tie – Rebar Tie Wire](https://americanwiretie.com/product-category/rebar-tie-wire/) — manufacturer reference covering black annealed, galvanized annealed, PVC-coated, and stainless steel tie wire across standard gauges and packaging.
- [Rebar Tie Wire Direct – Stainless Steel Tie Wire](https://rebartiewiredirect.com/material/stainless-steel/) — reference on 304 vs. 316 stainless tie wire selection for corrosive and coastal environments.
- [Gerard Daniel – Tie Wire](https://www.gerarddaniel.com/product/tie-wire/) — technical reference on annealing process and available alloy data sheets (stainless, galvanized, black annealed, copper-coated).
- National Electrical Code (NEC), NFPA 70 — Article 300.5 (underground burial and slab-penetration securing practices) and Article 250 (Grounding and Bonding), relevant where tie wire is used to secure grounding conductors or raceway during rough-in.

## Naming Convention

When identifying tie wire for vendor ordering, use the following naming structure, listing attributes in this order:

```
(SIZE) (MATERIAL) Tie-Wire
```

| Descriptor   | Explanation                                                                                                                           |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| `(SIZE)`     | Gauge size of the wiring itself (e.g., 16-Gauge, 18-Gauge, Gauge). Assume 16-Gauge as the default wiring size.                        |
| `(MATERIAL)` | Specify an exact material requested. Assume the default is Steel-Black-Annealed. Others might include Aluminum, Stainless-Steel, etc. |

### Example Names

- `16GA BlackAnnealed 3.5lb Tie Wire`
- `16GA Galvanized 3.5lb Tie Wire`
- `16GA StainlessSteel304 3.5lb Tie Wire`
- `16GA StainlessSteel316 5lb Tie Wire`
- `16GA PVCCoated 3lb Tie Wire`
- `14GA BlackAnnealed 5lb Tie Wire`

- `Tie-Wire`
- `18-Gauge Stainless-Steel Tie-Wire`
- `14-Gauge PVC-Coated Tie-Wire`

### Convention Notes

- Lead with **SIZE** as the wire gauge number (e.g., 16-Gauge, 18-Gauge, Gauge) — 16-Gauge is the standard default for general tying and rebar work unless a specific application calls for a heavier or lighter gauge.
- State **MATERIAL** as BlackAnnealed, Galvanized, StainlessSteel304, StainlessSteel316, or PVCCoated.
- State **WEIGHT** as the coil weight in pounds (e.g., "3.5lb," "5lb," "1lb") — this is the standard unit tie wire is packaged and sold by; confirm the corresponding approximate length against the specific gauge, since length-per-pound varies with wire diameter.
- Note explicitly if **PVC-coated wire is required for epoxy-coated rebar** — this is a project specification detail, not a cosmetic preference, since an uncoated wire can damage the rebar's epoxy coating.
- Many vendor catalogs (e.g., American Wire Tie, Western Steel & Wire, CCTI, Simba Steel) also carry a **manufacturer catalog number**; when ordering, provide both the plain-language description above and the catalog number if known.

## Typical Units of Measure

| Unit                 | Typical Use                                                                                                                                         |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Linear Feet (LF)** | When possible, use linear feet as an exact measure for ordering. This will allow metrics to compute price per foot.                                 |
| **Coil (EA)**        | Base packaging unit — tie wire can be sold as a wound coil, typically in **1 lb, 3 lb, 3.5 lb, or 5 lb** sizes depending on gauge and manufacturer. |
| **Box/Carton**       | Standard bulk packaging, commonly **20 coils per box/carton** (e.g., 20 × 3.5 lb coils = a 70 lb carton).                                           |
| **Pallet**           | Distributor bulk quantity made up of multiple cartons; used for large concrete/rebar-intensive projects.                                            |
| **Pound (LB)**       | Underlying pricing basis for most tie wire, since coil size is itself expressed in weight rather than a fixed length.                               |

### Ordering Help

- Always specify **gauge, material/finish, and coil weight** together — a listing for "tie wire" alone is incomplete, since gauge and material both significantly affect strength, corrosion resistance, and cost.
- Confirm the **approximate length per coil** for the specific gauge and weight being ordered, since it is not standardized across manufacturers and directly affects how many coils are needed for a given quantity of ties.
- For projects using **epoxy-coated rebar**, confirm PVC-coated tie wire is specified — this is frequently a project-specification requirement, not just a corrosion-resistance upgrade, since uncoated wire can compromise the rebar coating and void its corrosion warranty.
- For **coastal, marine, or long-service-life installations**, confirm whether 304 or 316 stainless steel is specified — 316 carries a further cost premium over 304 but offers meaningfully better resistance in the most demanding corrosive environments.
- Never substitute tie wire for a rated lifting or support product — it is intended for tying and securing only, and its packaging typically states this limitation explicitly.

_Generated Schematic_
![](/images/tie-wire-schematic.png)