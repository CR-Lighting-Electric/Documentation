---
title: Receptacles
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-09-08
---
## Overview

A receptacle is the wall- or panel-mounted device a plug connects to, delivering power from a branch circuit to a cord-connected load. Receptacles are standardized by **NEMA configuration** (the pattern of blade slots, which determines voltage, amperage, and plug compatibility) and are further differentiated by protection type, duty grade, and physical style.

![](/images/receptacle-example.png)

Receptacles are selected based on:

1. **NEMA configuration** — a code identifying voltage, amperage, and blade pattern, always paired with an R (receptacle) or P (plug) suffix. Common straight-blade configurations include:
    - **5-15R** — the standard 125V, 15A residential/general-purpose outlet (the ubiquitous three-prong household outlet).
    - **5-20R** — 125V, 20A, identified by an additional T-shaped neutral slot; accepts both 5-15P and 5-20P plugs, making it backward-compatible with standard 15A cords.
    - **6-15R / 6-20R** — 250V configurations at 15A/20A, used for larger single-phase 240V equipment.
    - **L5-20R, L6-20R, etc. (L-series)** — twist-lock configurations, where the plug is inserted and rotated to lock in place, resisting accidental disconnection; common in industrial, stage/production, and outdoor equipment applications.
2. **Protection type:**
    - **Standard** — no integral protection beyond standard grounding.
    - **GFCI (Ground-Fault Circuit Interrupter)** — monitors for current leakage to ground and trips within milliseconds to prevent shock; required by the NEC in bathrooms, kitchens, garages, outdoors, and other damp/wet-adjacent locations.
    - **AFCI (Arc-Fault Circuit Interrupter)** — monitors for the electrical signature of a dangerous arc fault (a common fire cause) and trips before it ignites surrounding material; required by the NEC in most dwelling-unit living spaces.
    - **TR (Tamper-Resistant)** — has internal spring-loaded shutters that only open when both blades of a plug are inserted simultaneously, preventing insertion of foreign objects into a single slot. (cite index="20-1">NEC 210.52 has required tamper-resistant receptacles in dwelling units since 2011</cite>, applying to all 15A and 20A, 125V receptacles installed in residences.
    - **WR (Weather-Resistant)** — constructed and listed for outdoor use, resisting moisture and UV degradation; required wherever a receptacle is installed outdoors, typically paired with an in-use ("bubble") cover.
3. **Duty grade** — grade is a meaningful durability and reliability tier, not just a price point:
    - **Residential grade** — (cite index="20-1">uses minimal contact springs that fatigue rapidly; daily plug insertion/removal cycles cause spring force to degrade significantly within 1–2 years, resulting in loose plugs and poor connections</cite>.
    - **Commercial / specification ("spec") grade** — (cite index="20-1">offers better durability than residential devices with larger contact groups, superior pullout resistance for daily-use applications, and acceptable performance for office buildings, laboratories, and commercial spaces</cite>; typically the recommended default for any non-residential installation.
    - **Hospital grade** — the highest standard duty tier, identified by a green dot on the device face, built for maximum contact retention and durability; (cite index="20-1">intentionally requires higher insertion/removal force, which can cause frustration in office environments where cords are often removed by pulling on the cable rather than the plug</cite> — meaning hospital grade is not simply an upgrade for every application, but a specific fit for patient-care areas and similar high-reliability settings.
    - **Industrial grade** — extends beyond standard NEMA configurations into twist-lock (L-series) and pin-and-sleeve (IEC 60309) devices built for vibration resistance and environmental exposure.
4. **Physical style** — duplex (two outlets on one strap, the standard configuration), single/simplex, or decorator (Decora-style rectangular face) versus standard round-face style.

**A practical note on 15A vs. 20A:** (cite index="20-1">one common specification strategy is requiring 20A receptacles instead of 15A regardless of the circuit's actual rating, since the heavier internal contacts yield significant durability improvements</cite> even where the branch circuit itself doesn't demand 20A capacity — worth considering explicitly during design rather than defaulting to 15A everywhere out of habit.

## Further Resources

- [Industrial Monitor Direct – Receptacle Grade Types: Hospital vs. Commercial vs. Industrial vs. Residential](https://industrialmonitordirect.com/blogs/knowledgebase/receptacle-grade-types-hospital-vs-commercial-vs-industrial-vs-residential) — practical comparison of grade tiers, contact durability, and where each grade is actually appropriate.
- [NEMA Configuration Chart](https://www.nema.org/standards/) — the reference chart for straight-blade and locking (L-series) NEMA configurations, matching plug and receptacle patterns to voltage/amperage.
- [ElectricalFlux – Electrical Receptacle Wiring Diagrams: Standard & GFCI Guide](https://electricalflux.com/wire-switches/electrical-receptacle-wiring-diagrams-15a-20a-gfci) — wiring reference covering terminal layout, torque specs, and GFCI/MWBC considerations.
- National Electrical Code (NEC), NFPA 70 — Sections 210.8 (GFCI protection), 210.12 (AFCI protection), and 210.52 (tamper-resistant receptacles in dwelling units) — governing where each protection type is required.

## Naming Convention

When identifying receptacles for vendor ordering, use the following naming structure, listing attributes in this order:

```
CONFIG PROTECTION GRADE STYLE (FEATURES) (BRAND) Receptacle COLOR
```

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                                                                |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `CONFIG`     | The NEMA configuration code (e.g., 5-15R, 5-20R, 6-20R, L5-20R, L6-20R). Leads the name, since it determines voltage, amperage, and plug compatibility — the single most important compatibility field.                                                                    |
| `PROTECTION` | Standard, GFCI, AFCI, IG, TR (tamper-resistant), or WR (weather-resistant). A device may combine more than one (e.g., a GFCI receptacle that is also TR) — list all that apply.                                                                                            |
| `(TYPE)`     | Optional type of the receptacle common type identifiers include Twist-Lock, Plug-Tail, etc.                                                                                                                                                                                |
| `GRADE`      | Residential, Commercial (or Specification), Hospital-Grade, or Industrial. Confirm the application actually calls for the grade specified — Hospital-Grade is not a universal upgrade and carries different insertion-force characteristics unsuited to some environments. |
| `STYLE`      | Duplex, Single, or Decorator. Duplex is the standard two-outlet configuration; specify Single or Decorator explicitly where needed.                                                                                                                                        |
| `(FEATURES)` | Any additional extra features that may be added to the device, for example "2-USB-A" would denote a receptacle with two additional USB-A ports.                                                                                                                            |
| `(BRAND)`    | Specific branding identifier; common brands include Leviton, Decora,                                                                                                                                                                                                       |
| `COLOR`      | White, Ivory, Gray, Black, or Red (Red commonly denotes an emergency/isolated-ground or life-safety circuit in commercial specifications — confirm local convention before assuming).                                                                                      |

### Example Names

- `5-15R GFCI Commercial Duplex Receptacle White`
- `L6-20R Standard Industrial Single Receptacle Black`
- `5-20R WR Commercial Duplex Legrand Receptacle White`
- `5-25R TR GFCI Residential Single 2-USB-A Decora Receptacle Black`

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and ordering — receptacles are counted and ordered individually to match the device count on the plan set.|
|**Box/Pack**|Common bulk packaging for standard-grade devices, typically packed **10 per box**.|
|**Case**|Distributor bulk quantity, made up of multiple boxes; used for large commercial or multi-unit residential projects.|

### Ordering Help

- Always specify **configuration, protection type, grade, style, and color** together — a generic "receptacle" order without these fields is incomplete and risks the wrong voltage/amperage compatibility, missing required protection, or a mismatched device grade for the space.
- Confirm which **locations require GFCI or AFCI protection** (or both, where combination devices are used) against the current NEC edition adopted by the local jurisdiction, since requirements have expanded significantly across recent code cycles.
- Confirm **tamper-resistant (TR) requirements** apply to essentially all 15A/20A, 125V receptacles in dwelling-unit living spaces — this is a near-universal residential requirement, not an optional upgrade.
- For **commercial and institutional projects**, default to Commercial/Specification grade rather than Residential grade unless a specific budget constraint dictates otherwise — the durability difference materially affects long-term maintenance and callback rates.
- Confirm whether a **wallplate and matching cover (e.g., an in-use "bubble" cover for outdoor WR receptacles)** is included with the device or needs to be ordered as a separate line item, since this varies by manufacturer and product line.

_Generated Schematic_
![](/images/receptacle-schematic.png)