---
title: Ground Rods
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-10-12
imported: true
---
## Overview

A ground rod is a metal rod driven into the earth to serve as a grounding electrode, giving a building's electrical system and its equipment a low-resistance connection to ground. It is the electrode at the far end of the grounding path that starts at the Ground Bars and Busbars covered elsewhere in this documentation, with a grounding electrode conductor and a clamp joining the two.

![](/images/ground-rod-example.png)

The NEC sets several requirements for rod electrodes that drive what gets ordered:

- **Length** — rod and pipe electrodes must be at least 8ft long, with at least 8ft of direct soil contact.
- **Diameter** — stainless steel and copper-coated or zinc-coated steel rods must be at least 5/8" in diameter unless listed, in which case a smaller rod (commonly 1/2") is accepted.
- **Surface** — a steel electrode needs a galvanized or other metal-coated outer surface, and the rod must be free of nonconductive coatings such as paint or enamel.
- **Installation** — drive the rod to full depth and do not cut off the exposed end to make it fit. Where bedrock stops the rod, drive it at an angle of no more than 45 degrees from vertical; if that fails, lay it in a trench at least 30" deep (NEC 250.53(G)), which is a last resort.
- **Resistance** — a single rod, pipe, or plate electrode is acceptable if its resistance to earth is 25 ohms or less as shown by testing. If it exceeds 25 ohms, or is not tested, add a supplemental electrode of a type listed in the code. Rod electrodes must be at least 6ft from any other electrode. Check the NEC edition adopted locally, because the wording has changed between editions.

Ground rods are made in a few constructions:

- **Copper-bonded steel** — copper metallurgically bonded to a steel core, the most common type. Listed rods carry a minimum of 10 mils (0.010") of copper; some UL/RUS rods carry 13 mils. Rods shorter than 8ft or with less than 10 mils of copper do not meet UL or NEC requirements.
- **Galvanized steel** — a zinc-coated steel rod; the NEC requires the outer surface of a steel electrode to be galvanized or otherwise metal-coated.
- **Stainless steel** — a corrosion-resistant rod, also an NEC-recognized rod material.

The way rods join and connect gives three styles:

- **Standard** — a threadless rod that couples with a separate coupling (such as the TC type) when two lengths are needed.
- **Knurled** — a rod with a pre-knurled surface made for compression connectors.
- **Sectional** — a rod threaded on both ends that joins with a coupling and uses a drive stud, so it can be driven in sections where overhead clearance is limited or deep driving is needed.

Ground rods are selected based on:

1. **Length** — 8ft is the minimum for a code-compliant rod; 10ft and 12ft rods are made for jobs that call for more depth.
2. **Diameter** — 1/2", 5/8", 3/4", and 1" are made. Use 5/8" unless the rod is listed for a smaller diameter.
3. **Material** — Copper-Bonded-Steel as the default, Galvanized-Steel, or Stainless-Steel for corrosive locations.
4. **Style** — Standard, Knurled, or Sectional, matched to how the rod will be coupled and connected.
5. **Listing** — look for UL 467 and the minimum copper thickness.

## Further Resources

- [Electrical Contractor – Driven Grounding Electrodes: Understanding What They Are and Requirements](https://www.ecmag.com/magazine/articles/article-detail/codes-standards-driven-grounding-electrodes-understanding-what-they-are-and-requirements) — reference on NEC rod length, diameter, materials, installation, the bedrock alternatives, the 25 ohm rule, and electrode spacing.
- [Galvan – Copper-Bonded Ground Rods](https://galvanelectrical.com/catalog/copper-bonded-ground-rods/) — manufacturer catalog for standard, knurled, and sectional copper-bonded rods, plating thickness, and the 1/2" to 1" size range.
- [Harger – Copper-Bonded Steel Ground Rods](https://www.harger.com/product/copper-bonded-steel) — manufacturer catalog for copper-bonded rods from 1/2" to 1" in diameter and 8ft to 12ft in length, listed to UL 467.
- [nVent ERICO – Copper-Bonded Ground Rod, Threaded](https://www.nvent.com/en-us/erico/products/copper-bonded-ground-rod-threaded-0) — manufacturer reference for a threaded copper-bonded rod.
- National Electrical Code (NEC), NFPA 70 — Article 250.52(A)(5) (Rod and Pipe Electrodes) and 250.53 (Grounding Electrode System Installation).
- UL 467 — the listing standard for grounding and bonding equipment, including rods.
- NEMA GR-1 — the standard for grounding rod electrodes and grounding rod electrode couplings.

## Naming Convention

When identifying ground rods for vendor ordering, use the following naming structure, listing attributes in this order:

```
DIAMETER (STYLE) LENGTH-Length (MATERIAL) Ground-Rod
```

### Example Names

- `5/8" 8'-Length Ground-Rod`
- `5/8" Standard 10'-Length Ground-Rod`
- `1/2" Sectional 8ft Copper-Bonded-Steel Ground-Rod`
- `3/4" Knurled 10'-Length Ground-Rod`
- `5/8" Knurled 8'-Length Copper-Bonded-Steel Ground-Rod`
- `5/8" 8'-Length Galvanized-Steel Ground-Rod`
- `5/8" 8-Length Stainless-Steel Ground-Rod`

### Convention Notes

| Descriptor     | Explanation                                                                                                                                                                                                                                      |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `DIAMETER`     | The rod diameter: 1/2", 5/8", 3/4", or 1". Use 5/8" unless the rod is listed for a smaller diameter.                                                                                                                                             |
| `(STYLE)`      | Standard (threadless, joined with a separate coupling), Knurled (pre-knurled for compression connectors), or Sectional (threaded both ends, joined with a coupling and drive stud). Defaults to Standard.                                        |
| `LENGTH`       | The rod length (for example 8ft, 10ft, 12ft); 8ft is the code minimum.                                                                                                                                                                           |
| `(MATERIAL)`   | Copper-Bonded-Steel (default), Galvanized-Steel (zinc-coated steel), or Stainless-Steel (corrosion-resistant). Default to Copper-Bonded Steel.                                                                                                   |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for a single rod.|
|**Bundle**|Common packaging, typically **5 rods per bundle** for most sizes, with fewer in the large 1" rod bundles.|
|**Pallet**|Distributor bulk quantity for large projects.|

### Ordering Help

- Order **no less than 8ft and 5/8"** for a standard installation, and confirm the rod is listed; a rod shorter than 8ft or with less than 10 mils of copper does not meet UL or NEC requirements.
- Plan on **testing the rod's resistance to earth**. If a single rod reads above 25 ohms, or is not tested, a supplemental electrode is needed, so order the second rod and the conductor with the first; keep rod electrodes at least 6ft apart.
- Choose **Sectional rods where overhead clearance is limited** or the soil needs a deeper drive, and order the matching couplings and drive studs.
- Choose **Knurled rods when the connections will be compression connectors**, and match the rod diameter to the connector.
- Choose the **rod material for the soil and site**, and keep the clamp and conductor materials compatible with the rod to avoid galvanic corrosion; confirm the choice with the project specification.
- Order the **ground rod clamp (listed for the rod and for direct burial) and the grounding electrode conductor** with the rod, since the rod does nothing without them. Do not paint or coat the rod where it contacts the clamp or soil.
- Do not cut a rod to fit; if the rod hits rock, use the angled or trench installation instead.

_Generated Schematic_
![](/images/ground-rod-schematic.png)