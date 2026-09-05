---
title: Bushings
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-08-31
---
## Overview

A bushing threads or snaps onto the end of a conduit or fitting where it enters a box, cabinet, or enclosure, providing a smooth, rounded surface that protects conductor insulation from abrasion against sharp conduit threads or a knockout's rim as the conductors are pulled in and remain in service. Bushings are governed primarily by **NEC 300.4(G)**, which requires this protection wherever 4 AWG or larger insulated conductors enter an enclosure, and by raceway-specific sections (e.g., 344.46 for RMC) that require a bushing at any conduit-to-enclosure termination regardless of conductor size, unless the enclosure or fitting already provides equivalent rounded protection.

![](/images/bushing-example.png)

Bushings are selected based on:

1. **Function:**
    - **Insulating (standard) bushing** — provides abrasion protection only, with no grounding or bonding function. Constructed wholly of insulating material, it satisfies the NEC 300.4(G) insulation-protection requirement but **cannot** be used as the means of securing the raceway to the enclosure — the raceway must still be mechanically secured by a locknut, hub, or connector independent of the bushing.
    - **Grounding bushing** — an insulated bushing with an integral lay-in lug or set screw, allowing an equipment grounding conductor to be connected directly to the bushing and, through it, to the metallic raceway — commonly specified at service equipment and large feeder terminations where the raceway itself is not relied upon as the sole grounding path.
    - **Bonding bushing** — serves a related but distinct purpose from a grounding bushing: it ensures reliable bonding continuity of a metal raceway to a metal enclosure specifically at **concentric or eccentric knockouts**, where the layered knockout rings cannot be depended on to maintain a continuous bonding path through normal mechanical connection alone.
    - **Reducing bushing** - Provides a conversion characteristic from one size to another. Useful for RMC/IMC when connecting two different sizes together.
2. **Attachment style:**
    - **Threaded bushing** — screws directly onto the exposed male threads of Rigid Metal Conduit (RMC) or IMC, providing a secure, continuous, rounded surface at the termination.
    - **Snap-in / push-in bushing** — used on unthreaded raceway entries or on metal fittings/connectors that lack an integral insulated throat, offering quick, tool-free installation.
3. **Material and temperature rating** — bushings are typically constructed of high-dielectric nylon or a similar insulating composite, and per NEC 300.4(G), the bushing's temperature rating must be **at least equal to the insulation temperature rating of the conductors installed through it** (commonly 75°C or 90°C) — this must be checked against the manufacturer's marking and listing, not assumed from the bushing's appearance or price point.

**Important distinctions worth flagging:**

- A bushing is not automatically required at every termination — many connectors and fittings already have an integral insulated throat or a smoothly rounded/flared entry (e.g., most EMT connectors), which satisfies the same code intent without a separate bushing. Confirm whether the specific fitting being used already provides this protection before assuming a separate bushing is needed.
- A grounding bushing and a bonding bushing solve two related but different problems — grounding bushings establish a path for an equipment grounding conductor, while bonding bushings specifically address bonding continuity lost at concentric/eccentric knockouts. Specifying one where the other is actually needed is a common point of confusion in the field.
- As of the 2023 NEC, Section 300.4(G) was revised to clarify that this protection must be provided **before** conductors are pulled or installed, not added afterward — a longstanding common (but noncompliant) field practice was to pull conductors first and add the bushing last.

## Further Resources

- [Engineer Fix – What Are the NEC Plastic Bushing Requirements?](https://engineerfix.com/what-are-the-nec-plastic-bushing-requirements/) — overview of threaded vs. snap-in bushings, required materials, and temperature rating requirements under NEC 300.4(G).
- [Voltage Lab – Grounding vs. Bonding Bushings: NEC Differences Explained](https://www.voltagelab.com/grounding-vs-bonding-bushings/) — clear explanation of the distinct purposes served by grounding bushings and bonding bushings.
- [ExpertCE – Bushing and Fitting Requirements for Conduit per NEC 300.15](https://expertce.com/learn-articles/conduit-bushing-requirements-nec-300-15/) — practical walkthrough for selecting the correct protective fitting at a given termination point.
- [Electrical License Renewal – 300.4(G) Fittings](https://www.electricallicenserenewal.com/Electrical-Continuing-Education-Courses/NEC-Content.php?sectionID=1462) — summary of the 2023 NEC revision requiring insulated protection before conductors are pulled.
- National Electrical Code (NEC), NFPA 70 — Sections 300.4(G) and 300.15, and raceway-specific bushing requirements (e.g., 344.46 for RMC).

## Naming Convention

When identifying bushings for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPE ATTACHMENT (MATERIAL) Bushing
```

### Example Names

- `3/4" Insulating Threaded Nylon Bushing`
- `1" Insulating Snap-In Nylon Bushing`
- `3/4" Grounding Threaded Zinc-Aluminum Bushing`
- `2" Bonding Threaded Steel Bushing`
- `1-1/4" Insulating Threaded High-Dielectric-Nylon Bushing`
- `1/2"x3/4" Reducing Threaded Steel Bushing`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | The nominal trade size matching the conduit or fitting it will thread/snap onto (e.g., 3/4in, 1in, 2in). Leads the name, since fit is the first compatibility check.                                                                                                                                                                                                                                                        |
| `TYPE`       | Insulating provides abrasion protection only; Grounding adds a lay-in lug or set screw for an equipment grounding conductor; Bonding specifically addresses continuity loss at concentric/eccentric knockouts. Reducing bushings provide a conversion between two sizes, so there should be two measurements under `SIZE.` Never assume these are interchangeable.                                                          |
| `ATTACHMENT` | The ATTACHMENT field. Threaded bushings require male-threaded conduit (RMC/IMC); Pound-On bushings are used on unthreaded entries or fittings lacking an integral insulated throat.                                                                                                                                                                                                                                         |
| `(MATERIAL)` | The optional MATERIAL field. Insulating and grounding bushings are typically nylon or a similar composite for the insulated portion; grounding/bonding bushing bodies are commonly zinc, aluminum, or steel. Confirm the temperature rating printed on the specific product against the installed conductors' insulation rating — do not assume from material alone. If left off assume the standard nylon/plastic bushing. |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and small quantity orders, especially larger trade sizes and grounding/bonding bushings.|
|**Box**|Common bulk packaging for smaller trade sizes (1/2" through 1-1/4") of standard insulating bushings, typically packed **25 or 100 per box**.|
|**Case**|Distributor bulk quantity, made up of multiple boxes; used for large project takeoffs.|

### Ordering Help

- Always specify **size, function, attachment style, and material** together — a generic "bushing" order without these fields risks the wrong protective function or a fitting that won't attach to the raceway on site.
- Confirm whether the **specific connector or fitting already in use provides an integral insulated throat** before ordering a separate bushing — many EMT connectors and similar fittings already satisfy the NEC 300.4(G) requirement without one.
- Confirm whether **a grounding bushing or a bonding bushing** is actually what the application calls for — these solve different code requirements (equipment grounding conductor termination vs. knockout bonding continuity) and are not interchangeable substitutes for one another.
- Verify the **temperature rating printed on the specific bushing** meets or exceeds the insulation rating of the conductors being installed (commonly 75°C or 90°C) before finalizing an order — this is a code compliance detail, not a performance upgrade.
- Remember that an **insulating bushing cannot serve as the raceway's securing means** — order the appropriate locknut, hub, or connector as a separate line item to mechanically secure the raceway independent of the bushing.

_Generated Schematic_
![](/images/bushing-schematic.png)