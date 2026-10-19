---
title: Transformers
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
---
## Overview

A transformer changes voltage from one level to another, or isolates one circuit from another, using coupled windings on a core. On commercial electrical orders the transformer is almost always a dry-type, low-voltage unit (600V class and below) that steps 480V power down to 208Y/120V for lighting and receptacles, or a small control or buck-boost unit inside equipment. This page covers those dry-type low-voltage transformers. It does not cover pad-mount or liquid-filled utility transformers, medium-voltage (5kV class and above) dry-type units, reactors, or motor-starting autotransformers; those are separate products.

Scope against neighboring pages: the breaker or fuse that protects a transformer is on the Circuit Breakers and Fuses pages. This page covers the transformer itself.

Transformer types:

- **General-purpose distribution** — the standard dry-type unit for general lighting and other low-voltage loads on linear loads, such as in commercial buildings. UL listed. Ventilated enclosures are common from 15kVA up, with non-ventilated enclosures on small and harsh-location units.
- **K-factor** — a unit built to tolerate the extra heating from harmonics in non-linear loads, typically oversized with a larger neutral and electrostatic shielding. Harmonic-mitigating transformers are a related type for data centers and telecom sites.
- **Control transformer** — a small isolation transformer, rated in VA, that holds its secondary voltage steady during the brief overload of inrush. Used for control circuits and typically rated 600V or less.
- **Buck-boost** — a small single-phase transformer (Bruc Electric lists 0.05 to 7.5kVA) whose windings are wired as an autotransformer to raise or lower a line voltage by a modest amount, typically 5 to 27%. It is for stable voltages; a fluctuating line needs a voltage conditioner.
- **Isolation** — a transformer whose secondary is electrically separate from the primary, used to isolate sensitive loads and drives. Drive isolation transformers are sized for the drive's horsepower because of SCR drive harmonics.
- **Mini-power center** — a 3 to 30kVA unit with a 380 to 575V primary and a 120/240V single-phase or 120/208V three-phase secondary, usually with the panelboard built in.
- **Encapsulated (potted)** — a unit with the core and coil sealed in resin for moisture, contaminants, and corrosion, including types for harsh and hazardous locations.

Ratings that the order has to name:

- **Rating** — kVA for distribution transformers and VA for control units. Pick it from the connected load, with the inrush and duty cycle for motor loads.
- **Phase** — single-phase or three-phase.
- **Primary and secondary voltage** — for example 480V primary to 208Y/120V secondary, or a dual-voltage primary such as 240/480V to a 120/240V secondary.
- **Winding** — Copper or Aluminum. Copper is generally used for higher-rated systems, and aluminum is lighter and easier to handle in hard-to-reach locations.
- **Temperature rise and insulation** — units are made for temperature rises from 80°C to 150°C, so confirm the class on the nameplate or datasheet.
- **Enclosure** — NEMA 1 for indoor, NEMA 3R for outdoor, and NEMA 3R, 4X, or 12 for non-ventilated units.

Transformers are selected based on:

1. **Type** — General-Purpose, K-Factor, Control, Buck-Boost, Isolation, or Mini-Power-Center for the job.
2. **Load** — the connected kVA or VA, and whether the load is linear or non-linear (harmonics).
3. **Voltage and phase** — primary and secondary matched to the supply and the loads.
4. **Winding and temperature rise** — Copper or Aluminum, and the insulation class for the space.
5. **Efficiency and listing** — energy-efficient units meet the DOE standards in 10 CFR Part 431; look for UL listing.
6. **Location** — indoor or outdoor, ventilated or non-ventilated, and the clearances the nameplate requires.

## Further Resources

- [TEMCo Industrial – Transformer Types](https://temcoindustrial.com/product-guides/transformers/transformer-types) — reference on control, buck-boost, isolation, general-purpose, K-factor, harmonic-mitigating, encapsulated, and autotransformer types.
- [Bruc Electric – Dry-Type Transformers](https://brucelectric.com/dry-type-transformers-html) — distributor reference on enclosed non-ventilated, mini-power center, buck-boost, K-factor, and other dry-type units, with kVA ranges, winding, and enclosure notes.
- [ABB – Type QB Buck-Boost Transformers](https://electrification.us.abb.com/products/transformers-low-voltage-dry-type/type-qb-buck-boost) — manufacturer reference for single-phase buck-boost units, their voltage combinations, and field connection as an autotransformer.
- [EC&M – Article 450: Transformers and Transformer Vaults](https://www.ecmweb.com/national-electrical-code/code-basics/article/20887357/article-450-transformers-and-transformer-vaults) — 2008 reference on overcurrent protection, ventilation, accessibility, and nameplate rules; verify the section numbers against the current NEC.
- [Yale Facilities – 26 24 07 Dry-Type Transformers Design Standard](https://facilities.yale.edu/sites/default/files/files/Design%20Standards/Updated%20Design%20Standards/26%20Electrical/26%2024%2007%20Dry-Type%20Transformenrs_06_15_16.pdf) — an owner's specification showing typical requirements for windings, taps, enclosure, impedance, and sound level.
- National Electrical Code (NEC), NFPA 70 — Article 450 (Transformers and Transformer Vaults), including 450.3(B) (overcurrent protection), 450.9 (ventilation), 450.11 (marking), and 450.13 (accessibility); and 240.21(C) (transformer secondary conductors).
- 10 CFR Part 431 — the U.S. Department of Energy efficiency standards for distribution transformers.

## Naming Convention

When identifying transformers for vendor ordering, use the following naming structure, listing attributes in this order:

```
(TYPE) POWER PHASE PRIMARY-Primary SECONDARY-Secondary (WINDING) (RATING) Transformer
```

### Example Names

These examples show the pattern; confirm the voltage combinations and availability in the maker's catalog.

- `General-Purpose 75kVA 3-Phase 480V-Primary 208Y/120V-Secondary Copper Transformer`
- `General-Purpose 30kVA 3-Phase 480V-Primary 208Y/120V-Secondary Aluminum Transformer`
- `General-Purpose 50kVA 1-Phase 240/480V-Primary 120/240V-Secondary Copper Transformer`
- `K-Factor 45kVA 3-Phase 480V-Primary 208Y/120V-Secondary Transformer`
- `Mini-Power-Center 15kVA 3-Phase 480V-Primary 208Y/120V-Secondary Copper Transformer`
- `Isolation 9kVA 3-Phase 480V-Primary 208Y/120V-Secondary NA Transformer`
- `Control 500VA 1-Phase 480V-Primary 120V-Secondary Transformer`
- `Buck-Boost 500VA 1-Phase 120x240V-Primary 12/24V-Secondary NEMA-3R Transformer`

### Convention Notes

| Descriptor  | Explanation                                                                                                                          |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `(TYPE)`    | General-Purpose, K-Factor, Control, Buck-Boost, Isolation, Mini-Power-Center, or Encapsulated. Default to General-Purpose.           |
| `POWER`     | The capacity in kVA for distribution units (for example 15kVA, 75kVA) or VA for control units (for example 500VA).                   |
| `PHASE`     | 1-Phase or 3-Phase.                                                                                                                  |
| `PRIMARY`   | The input voltage (for example 480V, 240/480V for a dual-voltage primary, 120x240V for a buck-boost).                                |
| `SECONDARY` | The output voltage (for example 208Y/120V, 120/240V, 12/24V). Y/ denotes a wye connection, where the lower value is line-to-neutral. |
| `(WINDING)` | Copper or Aluminum; omit where the datasheet does not state it, as for many control and buck-boost units.                            |
| `(RATING)`  | Optional enclosure rating of the transformer (NEMA-1, NEMA-3R, etc.)                                                                 |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for a single transformer.|
|**Pallet**|Large dry-type distribution units are shipped on a pallet or skid.|
|**Case**|Small control and buck-boost units in distributor bulk quantity.|

### Ordering Help

- Pick the **type by the load first**: General-Purpose for linear loads, K-Factor for non-linear loads, Control for control circuits, Buck-Boost for small voltage corrections, and Isolation where the secondary must be separate.
- Size the **rating to the load**, using VA for control units with the inrush in mind. Large distribution units are sized in kVA with room for the load to grow.
- Match the **primary and secondary voltages** to the supply and the loads, and confirm the dual-voltage connections; a 480V to 208Y/120V unit is the common commercial combination.
- For **buck-boost**, use it only on a stable line. ABB states a unit field-connected as an autotransformer can handle loads many times its nameplate rating (up to 20 times), so size from the connected load and the voltage change needed, not the nameplate alone, and confirm the connection diagram.
- Protect the transformer to **NEC 450.3(B)**. Primary protection is sized from Table 450.3(B), and where 125% of the primary current does not match a standard rating, the next higher standard rating may be used for currents of 9A or more (from a 2008 article, so check the current NEC). The secondary conductors also need overcurrent protection at their terminal end (240.21(C)).
- Allow for **ventilation and clearance**. NEC 450.9 requires ventilation openings to be free of obstructions, and the nameplate lists the required clearances (450.11). Transformers must be readily accessible to qualified personnel, with exceptions for open wall mounting and for units of 50kVA or less above suspended ceilings (450.13).
- Allow for **heat and harmonics**. Non-linear loads can heat a standard transformer beyond its rating, so order a K-Factor unit for them.
- Plan the **secondary side**: a transformer that creates a new system with its own neutral needs grounding and bonding; confirm the grounding method with the project engineer (NEC 250.30, from memory).
- Check the **sound level and weight** for ceiling and rooftop installations. One owner's specification asks for 40 to 55 dBA depending on kVA.
- Confirm the **edition of the NEC your jurisdiction enforces**, since section numbers and wording change between editions.