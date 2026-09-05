---
title: Couplings
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

Couplings are the fittings used to join two lengths of raceway (conduit or tubing) together in a straight, continuous run. They are distinct from **connectors**, which terminate a raceway into a box, enclosure, or piece of equipment rather than joining two raceway sections to each other. Couplings are required any time a single stick of conduit is too short to complete a run, or when transitioning between raceway types or sizes mid-run.

![](/images/coupling-example.png)

Couplings are selected based on the same core factors as connectors:

1. **Raceway type** — the coupling must match the raceway it is designed to join (EMT, Rigid Metal Conduit/RMC, IMC, PVC, Flexible Metal Conduit, Liquidtight Flexible Metal or Nonmetallic Conduit, etc.). As with connectors, couplings are generally not interchangeable across raceway types.
2. **Joining method** — how the coupling secures the two raceway ends. Common methods include:
    - **Set-screw** — one or more hardened screws bear directly on each side of the coupling body, clamping onto each conduit end. <cite index="18-1">Set screw couplings are used to connect two lengths of steel EMT conduit and are suitable for indoor applications, and approved for concrete-tight applications when taped.</cite>
    - **Compression** — a compression ring or gland nut on each end of the coupling draws up around the full circumference of the conduit, giving a firmer, 360° grip suitable for wet or concrete-tight locations.
    - **Threaded** — <cite index="20-1">used for connecting segments of threaded rigid conduit or IMC</cite>, where the coupling threads onto factory-cut NPSM threads on each conduit end.
    - **Solvent-weld (cement)** — used with PVC conduit; the coupling is solvent-cemented to each plain conduit end, chemically fusing the joint into a single, permanent piece.
    - **Expansion** — <cite index="13-1">used at any point where the expansion or contraction of the conduit run is a concern, allowing the conduit to move with temperature change rather than putting stress on the joint</cite>. Common on long outdoor PVC runs and steel runs crossing building expansion joints.
3. **Environment** — dry location, wet/concrete-tight, or direct-burial duty call for different coupling construction and sealing, in the same way they do for connectors.

Couplings also vary by:

- **Type/function** — in addition to the standard straight coupling joining two same-size, same-type conduit ends, the category includes:
    - **Reducing couplings** — join two different trade sizes of the same raceway type (e.g., 1" EMT to 3/4" EMT).
    - **Combination couplings** — join two different raceway types (e.g., EMT to Rigid/IMC, or EMT to Flexible Metal Conduit).
    - **Slip/telescoping couplings** — used in prefabrication or where conduit movement is constrained during installation, allowing one conduit end to slide into the coupling without rotation.
    - **Expansion/deflection couplings** — accommodate linear movement and, in some designs, slight angular deflection between building sections.
- **Material** — steel, zinc die-cast, malleable iron, or PVC/nonmetallic, matched to the raceway material and environment.

## Further Resources

- [NEMA FB 1 – Fittings, Cast Metal Boxes, and Conduit Bodies for Conduit, Electrical Metallic Tubing, and Cable](https://www.nema.org/standards/view/fittings-cast-metal-boxes-and-conduit-bodies-for-conduit-electrical-metallic-tubing-and-cable) — the primary NEMA standard governing dimensions and performance of conduit/EMT fittings, including couplings.
- [UL 514B – Standard for Conduit, Tubing, and Cable Fittings](https://www.shopulstandards.com/ProductDetail.aspx?UniqueKey=32562) — the UL safety standard most conduit and EMT couplings are listed to.
- [Steel Tube Institute – Fittings for Use with RMC, IMC and EMT](https://steeltubeinstitute.org/resources/fittings-for-use-with-rmc-imc-and-emt/) — detailed technical reference on set-screw and compression fitting torque, taping requirements, and when expansion fittings are required based on temperature differentials.
- [Eaton Crouse-Hinds – EMT Connectors and Couplings Catalog](https://www.eaton.com/us/en-us/catalog/fittings/connectors-and-couplings---emt.html) — manufacturer reference showing set-screw vs. compression coupling construction, materials, and options.
- [Conduit Bending – EMT vs Rigid vs IMC Conduit: Types & Differences](https://conduitbending.com/insights/conduit-types/) — comparison reference explaining threaded vs. threadless joining methods across common raceway types.
- National Electrical Code (NEC), NFPA 70 — Articles 342 (IMC), 344 (RMC), 348 (FMC), 350 (LFMC), 352 (PVC), 358 (EMT) — governing installation, listing, and use requirements for each raceway type's fittings, including expansion fitting requirements.

## Naming Convention

When identifying couplings for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPES (MATERIAL) (FINISH) CONNECTION (SPECIALTY) (END) Coupling
```

| Descriptor    | Explanation                                                                                                                                                                                                                                                     |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`        | Trade size of the coupling in inches, .i.e 1/2" or 3-1/2".                                                                                                                                                                                                      |
| `TYPES`       | Type of the coupling, most commonly a conduit type. If the coupling is a specialty combination type, there might be two types for example: "EMT-to-RMC."                                                                                                        |
| `(MATERIAL)`  | Optional material identifier. If omitted, assume standard type material.                                                                                                                                                                                        |
| `(SCHEDULE)`  | If PVC material, optionally identify the schedule. If omitted, Schedule-40.                                                                                                                                                                                     |
| `(FINISH)`    | Optional finishing identifier. If omitted, assume standard finish on material.                                                                                                                                                                                  |
| `CONNECTION`  | Connection types of the coupling. Threaded is very common, with Set-Screw, Solvent-Weld for PVC, Compression, etc.                                                                                                                                              |
| `(SPECIALTY)` | Specialty identifier: define if the coupling is a reducer or an expansion. If a reducer, then the specialty should look something like Reducer-1-1/2" meaning the coupling reduces to 1-1/2." If Expansion type, then include the linear movement: Expansion-6" |
| `(END)`       | If the type if PVC, then optional Bell-End can be ordered.                                                                                                                                                                                                      |

### Example Names

- `1/2" EMT Set-Screw Coupling`
- `3/4" PVC Solvent-Weld Coupling`
- `2-1/2" EMT Set-Screw Reducer-2" Coupling`
- `3" PVC Schedule-80 Threaded Expansion-6" Coupling`

### Convention Notes

- Always lead with **trade size** (nominal), not actual outside diameter — this is how conduit and fittings are ordered industry-wide (e.g., 1/2", 3/4", 1", 1-1/4", 1-1/2", 2", 2-1/2", 3", 3-1/2", 4").
- For **expansion couplings**, specify the rated linear movement (e.g., "4 in" or "6 in Movement") since this varies by manufacturer and directly affects suitability for the application.

## Typical Units of Measure

Couplings are small hardware items and are typically ordered and priced by one of the following units, depending on trade size and vendor:

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and small quantity orders, especially larger trade sizes (2" and up) and specialty items like expansion or combination couplings.|
|**Box**|Common bulk packaging for smaller trade sizes (1/2" through 1-1/4"), typically packed **5, 25, 50, or 100 per box** depending on size and manufacturer.|
|**Master Case/Carton**|Distributor/contractor bulk quantity, often several boxes per master case; used for large project takeoffs.|

## Ordering Help

- Always specify **trade size** and **quantity of pieces**, not boxes, when placing a formal order — box/carton pack quantities vary by manufacturer and are a packaging convenience, not a standardized unit.
- Confirm **material and finish** (steel/zinc-plated, die-cast zinc, malleable iron, PVC) and **rated expansion movement** (for expansion couplings) when requesting pricing, as these affect both cost and lead time.

_Generated Schematic_
![Coupling Schematic](/images/coupling-schematic.png)