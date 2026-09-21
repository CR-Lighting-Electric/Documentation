---
title: Wire Taps
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-07-10
---
## Overview

A wire tap, in this context, refers to an **insulated multi-tap connector** (also called a power distribution tap, multi-tap block, or by the genericized brand name "Polaris connector") — a factory-insulated, set-screw-based connector that splits one larger main/run conductor into multiple smaller tap/load conductors without cutting the main conductor or building the splice with wire nuts and tape. Multi-tap connectors are common in street and parking lot lighting, service entrance and meter-base taps, solar/renewable energy strings, motor lead connections, and any application needing a clean, reusable, code-recognized tap off a feeder or branch circuit.

Multi-tap connectors are selected based on:

1. **Port count** — the number of conductor entry points, commonly 2 through 6 ports (occasionally more on larger power-distribution styles), each independently secured with its own set screw.
2. **Entry configuration:**
    - **Single-sided entry** — all ports enter from the same side of the connector body.
    - **Dual/double-sided entry** — ports enter from opposite sides, which can simplify routing in tight panel or enclosure layouts.
3. **Wire range** — most connectors are rated for a single conductor range shared across all ports (e.g., 14 AWG–2 AWG). Larger "B-tap" or "run/tap" style connectors instead specify a **separate main (run) range and tap (load) range** — e.g., a main conductor from 500 kcmil–2/0 AWG feeding taps from 4/0–4 AWG — since the main and tap conductors are not expected to be the same size.
4. **Material and conductor compatibility** — most multi-tap connectors are constructed from high-strength forged aluminum alloy (commonly 6061-T6) and are **dual-rated (AL9CU)** for both aluminum and copper conductors; they typically ship pre-filled with oxide inhibitor at the factory, eliminating a separate field-applied paste step required on many other aluminum terminations.
5. **Insulation** — a factory-molded, high-dielectric plastisol (or similar PVC-type) shell fully encapsulates the connector body, standard at 600V. Insulation is commonly black (opaque) or clear — clear housings allow visual inspection of proper conductor insertion both during installation and at final inspection.
6. **Environment rating** — standard multi-tap connectors are designed for indoor use or protected outdoor use within a NEMA-rated enclosure or junction box; they are **not** rated for direct burial or continuous submersion unless specifically labeled as a direct-burial or submersible model.

**A note on scope and code use:** these connectors are functionally similar to a lug in that they use a set screw rather than a crimp, but they are their own distinct listing category (typically UL 486B) rather than a general-purpose lug, and they are not the same product as a bolted power distribution block (PDB) built into switchgear — a PDB is a bussed assembly with its own mounting and short-circuit current rating (SCCR) considerations, while an individual multi-tap connector is not physically fastened to anything but the conductors it joins. Multi-tap connectors are also frequently used to make conductor taps consistent with NEC tap rules (e.g., Article 240.21), but the tap conductor's ampacity and overcurrent protection must still be verified against the governing code section — the connector's rating alone does not satisfy the tap rule.

## Further Resources

- [UL 486B – Standard for Wire Connectors for Use with Aluminum Conductors](https://www.shopulstandards.com/) — the primary UL safety standard governing insulated multi-tap connector construction and listing.
- [Ilsco – Nimbus Insulated Multi-Tap Connectors](https://www.ilsco.com/) — manufacturer catalog reference for port count, entry configuration, and main/tap range combinations across the common Nimbus/PBTD product line.
- [Burndy – UNITAP Insulated Multi-Tap Connectors](https://www.burndy.com/) — manufacturer reference for the UNITAP line, covering AL/CU dual-rated construction and amperage ratings by port and wire range.
- [NSI Industries – Polaris Insulated Multi-Tap Connectors](https://www.nsiindustries.com/) — manufacturer reference for the widely genericized "Polaris" connector line, including the Vision (clear) series.
- National Electrical Code (NEC), NFPA 70 — Article 110.14 (Electrical Connections) and Article 240.21 (Location of Overcurrent Protection, Tap Conductors) — governing connector listing and the ampacity/protection rules that apply to any tap made using this connector type.

## Naming Convention

When identifying multi-tap connectors for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE PORTS (ENTRY) (CONDUCTOR-Conductor) (MATERIAL) (INSULATED) Tap
```

### Convention Notes

| Descriptor    | Explanation                                                                                                       |
| ------------- | ----------------------------------------------------------------------------------------------------------------- |
| `SIZE`        | Size of the wiring entering the ports (250-MCM, 1/0-AWG, 6-AWG, etc.)                                             |
| `PORTS`       | Number of ports present on the tap itself (1-Port, 2-Port, 3-Port, etc.)                                          |
| `(ENTRY)`     | Which sides have wire entry into the tap (1-Sided, 2-Sided), assume 1-Sided as the default for entries.           |
| `(CONDUCTOR)` | The conductor material of the wire coming in (Aluminum, Copper, etc.), assume Copper-Conductor as the default.    |
| `(MATERIAL)`  | The actual material of the tap itself; assume Aluminum as the default.                                            |
| `(INSULATED)` | Whether the tap is insulated or not; assume Insulated as the default. Options include Insulated or Non-Insulated. |

### Example Names

- `10-AWG 2-Port Tap`
- `2-AWG 3-Port 2-Sided Aluminum-Conductor Tap`
- `250-KCMIL 2-Port Copper-Conductor Aluminum Non-Insulated Tap`

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for larger, high-port-count, or high-amperage connectors, which are typically ordered in the exact quantity needed.|
|**Box/Carton**|Common bulk packaging for smaller, high-volume connector sizes (2–3 port, smaller AWG ranges), typically packed **6, 10, or 25 per box**.|
|**Bag**|Occasional packaging for small connectors at high volume, especially from lighting and utility distributors.|
|**Case**|Distributor bulk quantity, made up of multiple boxes; used for large project takeoffs.|

### Ordering Help

- Always specify **port count, entry configuration, metal/conductor rating, and full wire range (including separate main/tap ranges where applicable)** together — a multi-tap connector order missing the main-vs-tap range distinction risks arriving unable to accommodate the actual conductor sizes in the field.
- Confirm the **hex key/set-screw driver size** needed for installation, since it varies by connector size and is not always obvious from the part number alone.
- If the application is **outdoor, wet, or below grade**, confirm the connector is rated for that environment — standard multi-tap connectors are not rated for direct burial or continuous submersion despite often being installed in outdoor lighting and utility applications, and a submersible-rated model must be specified separately.
- When a multi-tap connector will be used to create a **conductor tap under NEC Article 240.21**, confirm the tap conductor length, ampacity, and overcurrent protection requirements independently — the connector's UL listing covers the connection itself, not the broader tap-rule compliance of the installation.
- For **high-amperage or main-distribution applications**, confirm the connector's amperage rating (not just its wire range) is adequate for the actual circuit load, since amperage rating can vary between connectors with an identical wire range depending on port count and construction.