---
title: Connectors
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-07-08
---
## Overview

Connectors are the fittings used to terminate a length of raceway (conduit or tubing) into a box, enclosure, cabinet, or piece of equipment. They form the mechanical and, in most metallic systems, the electrical (grounding/bonding) path between the raceway and the enclosure it enters. Connectors are distinct from **couplings**, which join two lengths of raceway together in a straight run rather than terminating into an enclosure.

![](/images/connector-example.png)

Connectors are selected based on three main factors:

1. **Raceway type** — the connector must match the raceway it is designed to receive (EMT, Rigid Metal Conduit/IMC, PVC, Flexible Metal Conduit, Liquidtight Flexible Metal or Nonmetallic Conduit, etc.). Connectors are generally not interchangeable across raceway types.
2. **Termination method** — how the connector grips the raceway. Common methods include:
    - **Set-screw** — one or more hardened screws bear directly on the raceway wall. Economical and common for dry, indoor locations; considered concrete-tight only when taped per the NEC.
    - **Compression** — a compression ring or gland nut draws up around the full circumference of the raceway, giving a firmer, 360° grip. Used where concrete-tight or rain-tight (wet location) performance is required.
    - **Threaded (hub)** — used with Rigid Metal Conduit (RMC) and Intermediate Metal Conduit (IMC), which have factory-cut NPSM threads; the connector threads directly onto the conduit end.
    - **Glued/solvent-weld** — used with PVC conduit; the connector is solvent-cemented to the conduit belled or plain end.
    - **Squeeze/strap or screw-in** — common on Flexible Metal Conduit (FMC) and Liquidtight Flexible Metal Conduit (LFMC), where a strap, screw, or gland compresses onto the flexible convolutions.
3. **Environment** — dry location, wet/rain-tight, concrete-tight, corrosive, or hazardous (classified) location duty all call for different connector construction, sealing, and listing.

Connectors also vary by:

- **Insulation** — an insulated throat (typically a nylon bushing rated to 105°C) protects conductor insulation from abrasion where required by the NEC (e.g., NEC 300.4(G)).
- **Material** — steel, zinc die-cast, malleable iron, or PVC/nonmetallic, chosen for strength, corrosion resistance, and compatibility with the raceway material.
- **Angle/style** — straight, 45°, or 90° (angle) connectors are used where a straight connector will not fit the available space behind a box.

Connectors are a code-required part of a raceway installation (NEC Article 342, 348, 350, 356, 358, etc., depending on raceway type) and are UL Listed for the specific raceway and location they are rated for. Using an unlisted or mismatched connector is both a code violation and a common point of installation failure.

## Naming Convention

When identifying connectors for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPE (MATERIAL) (SCHEDULE) (FINISH) (ANGLE) (INSULATION) CONNECTION Connector
```

| Descriptor     | Explanation                                                                                                                                                                                                          |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`         | Trade size of the connector, such as 1", 2-1/2", 3-1/4", etc.                                                                                                                                                        |
| `TYPE`         | Type of the connector, which commonly come in conduit types.                                                                                                                                                         |
| `(MATERIAL)`   | Optional material specifier (Stainless-Steel, Aluminum, etc.). Assume the type default material if omitted.                                                                                                          |
| `(SCHEDULE)`   | Schedule number of the PVC if the material is PVC. Schedule-40 if omitted.                                                                                                                                           |
| `(FINISH)`     | Optional finish specifier which could include Galvanized, Oxides, etc.                                                                                                                                               |
| `(ANGLE)`      | Optional angle identifier for any bends in the connector; should be in -Degree format, for example a 45 degree angle should appear as 45-Degree. If omitted, assume the angle is 0 degrees, or a straight connector. |
| `CONNECTION`   | Connection type of the connector; examples include Threaded, Compression, Set-Screw, Screw-Clamp, etc.                                                                                                               |
| `(INSULATION)` | Optionally identify if the connector is insulated or not with "Insulated".                                                                                                                                           |

### Example Names

- `1" EMT Set-Screw Connector`
- `2-1/2" LFMC Screw-Clamp Connector`
- `3" PVC Schedule-80 Threaded Connector`
- `4" EMT Stainless-Steel 90-Degree Compression Connector`
- `1-1/4" EMT Screw-Clamp Insulated Connector`

**Notes on convention:**

- Always lead with **trade size** (nominal), not actual outside diameter — this is how conduit and fittings are ordered industry-wide (e.g., 1/2", 3/4", 1", 1-1/4", 1-1/2", 2", 2-1/2", 3", 3-1/2", 4").
- Slang is commonly used for a lot of terms in the electrical industry. **Smurf** refers to ENT due to its old common blue color.
- State the **raceway type using its standard abbreviation** where one exists: EMT (Electrical Metallic Tubing), RMC/GRC (Rigid Metal/Galvanized Rigid Conduit), IMC (Intermediate Metal Conduit), FMC (Flexible Metal Conduit, "Greenfield"), LFMC (Liquidtight Flexible Metal Conduit, "Sealtite"), LFNC (Liquidtight Flexible Nonmetallic Conduit), PVC (Rigid PVC Conduit, with Schedule-40 or Schedule-80 noted), ENT (Electrical Nonmetallic Tubing).

## Further Resources

- [NEMA FB 1 – Fittings, Cast Metal Boxes, and Conduit Bodies for Conduit, Electrical Metallic Tubing, and Cable](https://www.nema.org/standards/view/fittings-cast-metal-boxes-and-conduit-bodies-for-conduit-electrical-metallic-tubing-and-cable) — the primary NEMA standard governing dimensions and performance of conduit/EMT fittings, including connectors.
- [UL 514B – Standard for Conduit, Tubing, and Cable Fittings](https://www.shopulstandards.com/ProductDetail.aspx?UniqueKey=32562) — the UL safety standard most conduit and EMT connectors are listed to.
- [Eaton Crouse-Hinds – EMT Connectors and Couplings Catalog](https://www.eaton.com/us/en-us/catalog/fittings/connectors-and-couplings---emt.html) — manufacturer reference showing set-screw vs. compression construction, materials, and options.
- [Southwire EMT Fittings Catalog (PDF)](https://www.southwire.com/medias/1-EMT-Section-Catalog-WEB.pdf) — catalog reference with part numbering and specification sheets.
- [American Fittings (AMFICO) – EMT & Flex Adapter Fittings](https://amftgs.com/emt-steel-compression-connectors-couplings-fittings-made-in-the-usa/) — detailed breakdown of concrete-tight, rain-tight, and standard duty connector construction and applicable standards (UL 514B, UL 467, Federal Spec A-A-50553, CSA C22.2).
- National Electrical Code (NEC), NFPA 70 — Articles 342 (IMC), 344 (RMC), 348 (FMC), 350 (LFMC), 352 (PVC), 358 (EMT) — governing installation, listing, and use requirements for each raceway type's fittings.

## Typical Units of Measure

Connectors are small hardware items and are typically ordered and priced by one of the following units, depending on trade size and vendor:

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and small quantity orders, especially larger trade sizes (2" and up).|
|**Box**|Common bulk packaging for smaller trade sizes (1/2" through 1-1/4"), typically packed **25, 50, or 100 per box**.|
|**Master Case/Carton**|Distributor/contractor bulk quantity, often several boxes per master case; used for large project takeoffs.|

## Ordering Help

- Always specify **trade size** and **quantity of pieces**, not boxes, when placing a formal order — box/carton pack quantities vary by manufacturer and are a packaging convenience, not a standardized unit.
- Insulated and non-insulated versions, and different environment ratings (standard vs. rain-tight/concrete-tight), are usually stocked and priced as separate SKUs even within the same trade size.
- Confirm **material and finish** (steel/zinc-plated, die-cast zinc, malleable iron) when requesting pricing, as this affects both cost and lead time.

_Generated Schematic_
![Raceway Connector Schematic](/images/raceway-connector-schematic.png)

