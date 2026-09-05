---
title: Seismic Wire
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

Seismic wire is galvanized, soft-annealed mild steel wire used to suspend and laterally brace overhead building elements — most commonly suspended acoustical ceiling grids, light fixtures, and other ceiling-supported components — so that they remain attached to the structure and resist horizontal displacement during an earthquake. It is governed primarily by **ASTM C635** (classification of suspension system duty ratings), **ASTM C636** (standard installation practice), and **ASTM E580** (additional installation requirements specifically for areas subject to earthquake ground motion), which the IBC and ASCE 7 incorporate by reference for buildings in Seismic Design Categories C, D, E, and F.

![](/images/seismic-wire-example.png)

Seismic wire serves two distinct functions, and both are commonly built from the same base wire stock but installed differently:

1. **Vertical hanger wire** — supports the dead load of the ceiling grid itself, running straight down from the structure above to the main runner. <cite index="70-1">Hanger wires shall be a minimum of No. 12-gauge galvanized, soft-annealed, mild steel wire</cite>, typically spaced at 4 ft on center along the main runner, or at wider spacing if a heavier gauge is substituted.
2. **Splay (brace) wire** — provides horizontal seismic restraint, resisting lateral movement of the grid during ground motion. <cite index="61-1">Splay wire bracing shall be clusters of four 12 gauge wires attached to the main beam within 2" of the cross tee intersection, arrayed 90° from each other at an angle not exceeding 45° from the plane of the ceiling</cite>, typically at a 12 ft × 12 ft spacing pattern across the ceiling area.

**Material and code requirements:**

- <cite index="79-1">Ceiling wire is required to be Class 1 zinc-coated (galvanized) carbon steel conforming to ASTM A641, in soft temper, with a minimum ultimate tensile stress of 70 ksi</cite>.
- <cite index="66-1">18-gauge stainless steel wire and 1/8" multi-stranded aircraft cable are explicitly disallowed as substitutes</cite> for standard specialty/decorative ceiling suspension wire under the referenced seismic technical guidance — a lighter-gauge or different-construction wire is not an acceptable equivalent even if its rated strength looks comparable on paper, unless independently engineered and approved for the specific application.
- <cite index="67-1">12-gauge wire has a typical listed break strength around 375 lbs with a safe working load around 94 lbs (break strength divided by a safety factor of roughly 4)</cite>, though <cite index="79-1">DSA guidance for custom/engineered ceiling designs specifies a minimum safety factor of 2.0 against the wire's ultimate tensile stress</cite> — the applicable safety factor depends on which design methodology and jurisdiction governs the project, so gauge selection for non-prescriptive designs should be confirmed against the engineer of record's calculations rather than assumed from a generic table.
- <cite index="78-1">Wires must be attached by wrapping the wire around itself a minimum of three full 360° turns within a 3-inch length</cite> — this is an installation detail, but it directly affects whether a given wire spool's usable working length matches the field layout, since each termination consumes wire length beyond the nominal span.

**Application-specific gauge and wire requirements:**

- <cite index="78-1">Light fixtures weighing less than 10 lbs require one 12-gauge hanger wire connected from the fixture to the structure above (which may be slack); fixtures weighing 10–56 lbs require two 12-gauge wires attached at opposing corners (which may also be slack); fixtures over 56 lbs must be supported directly from the structure above by approved hangers rather than through the ceiling grid</cite>.
- <cite index="78-1">Pendant-mounted fixtures must be directly supported from the structure above using 9-gauge wire</cite> (heavier than the standard 12-gauge grid wire) <cite index="78-1">or an approved alternate support, without relying on the ceiling suspension system for direct support</cite>.
- <cite index="63-1">10-gauge wire may be substituted for 12-gauge at wider spacing along the main runner where permitted by the governing standard</cite>.

**Important scope note:** <cite index="62-1">cable trays and electrical conduits must be supported and braced independently of the ceiling grid</cite> — seismic wire documented on this page covers ceiling grid, light fixture, and specialty ceiling suspension only. Seismic bracing for cable tray, conduit, and other raceway systems is typically accomplished with rigid strut bracing assemblies (see the Brackets page) rather than wire, and is designed to its own separate engineering criteria.

## Further Resources

- [ASTM C636 / C636M – Standard Practice for Installation of Metal Ceiling Suspension Systems for Acoustical Tile and Lay-In Panels](https://www.astm.org/) — the base standard installation practice for hanger and splay wire spacing, gauge, and attachment.
- [ASTM E580 / E580M – Standard Practice for Installation of Ceiling Suspension Systems for Acoustical Tile and Lay-in Panels in Areas Subject to Earthquake Ground Motions](https://www.astm.org/) — the seismic-specific installation practice referenced by the IBC for Seismic Design Categories C–F.
- [DSA IR 25-1 – Maximum Allowable Load for Ceiling Wires (PDF)](https://www.dgs.ca.gov/-/media/Divisions/DSA/Publications/interpretations_of_regs/IR_25-1.pdf) — California Division of the State Architect interpretation clarifying allowable load capacity and material requirements (ASTM A641) for ceiling hanger and brace wire.
- [Armstrong Ceilings – Seismic Design: What You Need to Know (PDF)](https://www.armstrongceilings.com/content/dam/armstrongceilings/commercial/north-america/brochures/seismic-design-what-you-need-to-know-brochure.pdf) — practical manufacturer guidance summarizing ASTM C635/C636/E580 requirements by Seismic Design Category.
- [USG – Seismic Technical Guide: Hanger Wire Attachment (PDF)](https://www.usg.com/content/dam/USG/pdpmovedocuments/seismic-technical-guide-hanger-wire-attachment-en-SC2522.pdf) — manufacturer reference on hanger wire spacing, attachment methods, and load-carrying classification (Light/Intermediate/Heavy Duty).
- National Electrical Code (NEC), NFPA 70, and International Building Code (IBC) Section 1621/ASCE 7 §13.5.6 — governing the overall seismic bracing requirements this wire supports; always confirm with the project's structural engineer of record for anything outside prescriptive, code-minimum ceiling installations.

## Naming Convention

When identifying seismic wire for vendor ordering, use the following naming structure, listing attributes in this order:

```
(BRAND) (SIZE) (TYPE) (ENDS) Seismic-Wire
```

| Descriptor | Explanation                                                                                                                                                                                                                                                                                         |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `(BRAND)`  | Many manufactures have their own suspension systems; designate a specific brand like Hilti for their specific systems.                                                                                                                                                                              |
| `(SIZE)`   | Optional size specifier if the order dictates a specific system's gauge of seismic cable (16-Gauge, 18-Gauge, etc.); assume the typical 12-Gauge size as default.                                                                                                                                   |
| `(TYPE)`   | Optional type specifier if the request is for something specific for the brand, for example a specific Hilti system such as the [X-MW ALH L](https://www.hilti.com/c/CLS_MODULAR_SUPPORT_SYSTEM/CLS_WIRE_SUSPENSION_SYS/r13332525) might be requested. Replace spaces with dashes if there are any. |
| `(ENDS)`   | Optional ends to include with the seismic wire. Typical fastenings include Eyebolts-Ends, Loop-Ends, etc.                                                                                                                                                                                           |

### Example Names

- `Hilti X-MW-ALH-L Seismic-Wire`
- `Seismic Wire`
- `Hilti BX3 Seismic-Wire`


## Typical Units of Measure

| Unit                 | Typical Use                                                                                                                                     |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Coil/Bundle (EA)** | Base packaging unit — seismic wire is sold as a wound coil, commonly in **1 lb, 5 lb, or 10 lb** sizes depending on gauge or in **linear feet** |
| **Box/Carton**       | Standard bulk packaging, commonly multiple coils per box; quantity varies by gauge and manufacturer.                                            |
| **Pallet**           | Distributor bulk quantity for large commercial ceiling and lighting projects.                                                                   |

### Ordering Help

- Always specify **type (vertical, splay, or pendant), gauge, and material** together — a generic "seismic wire" order without these fields risks the wrong wire being substituted for a code-required application.
- Never accept a **stainless steel or aircraft cable substitution** for standard galvanized annealed hanger/splay wire without confirming it against an approved engineered design — this substitution is explicitly disallowed under standard specialty ceiling guidance and is not a matter of vendor availability or preference.
- Confirm **project-specific requirements from the structural engineer of record or governing local seismic technical guide** before defaulting to prescriptive code-minimum gauge and spacing — Seismic Design Categories D, E, and F frequently require tighter spacing, heavier gauge, or engineered bracing beyond the basic ASTM C636/E580 prescriptive minimums.
- Order **quantity based on actual field span plus a wrap allowance** for each termination (a minimum of three full 360° wraps within 3 inches per end) — underestimating wire length by only accounting for the nominal span between attachment points is a common takeoff error.
- Remember that **cable tray and conduit seismic bracing is a separate system** (typically rigid strut, not wire) — do not attempt to use seismic wire products from this page as a substitute for raceway seismic bracing, which is designed and ordered independently.

_Generated Schematic_
![](/images/seismic-wire-schematic.png)