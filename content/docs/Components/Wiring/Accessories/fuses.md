---
title: Fuses
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-08-26
---
## Overview

A fuse is an overcurrent protective device with a metal element that melts and opens the circuit when current exceeds its rating for long enough. On commercial and industrial electrical orders, fuses are most often the UL-classed cartridge fuses that fit disconnect switches, fuse blocks, and equipment holders, with Type S plug fuses still found in older panels. This page covers those power-distribution fuses. It does not cover glass or blade fuses for electronics and vehicles, or semiconductor fuses for drives and rectifiers, which are not branch-circuit protection under the NEC.

![](/images/fuse-example.png)

A fuse is ordered by its UL class first, because the class sets the dimensions, voltage rating, interrupting rating, and rejection features. Shape alone does not identify the class.

Fuse classes and types:

- **Class RK1 and RK5 (Class R)** — current-limiting cartridge fuses rated 250V or 600V, up to 600A, with a rejection feature. RK1 limits current more than RK5. Common for motor branch circuits and general industrial equipment. Class R fuse dimensions depend on both ampere rating and voltage, so 250V and 600V Class R fuses are not interchangeable.
- **Class J** — 600V, up to 600A, with a rejection feature. It takes roughly half the mounting space of a 600V Class R fuse, so it is common in newer equipment designed around it.
- **Class T** — 300V or 600V, up to 1200A, with a rejection feature. It is the most compact of the group, used in meter stacks, compact switchboards, and control assemblies.
- **Class CC** — 600V, up to 30A, with a rejection feature. The smallest body of the group, used for control circuits, transformer primaries, and short-circuit protection on IEC-style motor starters.
- **Class L** — 600V, from 601A to 6000A, bolt-in mounting with no rejection feature. Used in service entrance equipment and large feeders.
- **Type S plug fuse** — a screw-in fuse for older panels, limited to 125V and 30A, in three ampere classes (0 to 15A, 16 to 20A, and 21 to 30A) that are physically non-interchangeable. Type S fuses go in a Type S adapter, which once installed cannot be removed. Edison-base plug fuses are permitted only as replacements in existing installations.

The cartridge classes above are rated 200kA interrupting. A fuse with no interrupting rating marked is treated as a 10,000A device.

Fuses also differ by speed:

- **Fast-acting** — a single-element fuse that opens quickly on overload. It suits resistive loads and sensitive electronics, but on a motor it can open on every start.
- **Time-delay** — often a dual-element fuse that tolerates a brief overload or inrush before opening. It suits motors, transformers, and other inductive loads. The class does not determine the speed, so confirm the characteristic on the manufacturer's datasheet for the specific part.

Fuses are selected based on:

1. **Class** — matched to the fuse holder, fuse block, or disconnect, and to the space available.
2. **Ampere rating** — sized to the circuit or equipment, never above the conductor's protection requirement.
3. **Voltage rating** — at least the system voltage.
4. **Speed** — Time-Delay for motors and inductive loads, Fast-Acting for resistive loads and where fast clearing is needed.
5. **Interrupting rating** — at least the available fault current at the point of installation.

## Further Resources

- [ATEK – Industrial Fuse Classes Explained: RK1, RK5, J, T, CC & L](https://atekdistribution.com/industrial-fuse-selection-guide/) — reference comparing the fuse classes by voltage, ampere range, interrupting rating, rejection features, and applications, with time-delay vs. fast-acting guidance.
- [ATEK – Plug Fuses, Type S Fuses and Cartridge Fuse Rules (NEC Article 240)](https://atekdistribution.com/plug-fuses-type-s-nec-240/) — reference on plug fuse and Type S limits, Type S adapters, and cartridge fuse voltage and marking rules.
- [ATEK – Types of Fuses: Complete Guide to Types, Ratings & Sizes](https://atekdistribution.com/types-of-fuses/) — reference on ferrule and knife-blade cartridge fuses, fast-acting vs. time-delay, and the main fuse selection factors.
- [Eaton Bussmann – 14 Classes of Fuses](https://www.eaton.com/content/dam/eaton/products/electrical-circuit-protection/fuses/solution-center/bus-ele-tech-lib-fuse-classes.pdf) — manufacturer technical library reference on fuse classes.
- [Littelfuse – Fuse Class and Selection Chart](https://cdn.loebelectric.com/Resources/Littelfuse_01053_2_38_39_CAT.pdf) — manufacturer chart for fuse class selection.
- National Electrical Code (NEC), NFPA 70 — Article 240 (Overcurrent Protection), including 240.50 through 240.54 (plug fuses, fuseholders, and adapters) and 240.60 and 240.61 (cartridge fuses); Table 430.52 for motor branch-circuit fuse sizing.
- UL 248 — the safety standard for low-voltage fuses.

## Naming Convention

When identifying fuses for vendor ordering, use the following naming structure, listing attributes in this order:

```
CLASS AMPS VOLTS (SPEED) Fuse
```

### Example Names

- `Class-RK5 30A 250V Time-Delay Fuse`
- `Class-RK1 60A 600V Time-Delay Fuse`
- `Class-J 100A 600V Time-Delay Fuse`
- `Class-J 60A 600V Fast-Acting Fuse`
- `Class-CC 10A 600V Time-Delay Fuse`
- `Class-T 30A 600V Fast-Acting Fuse`
- `Class-L 800A 600V Time-Delay Fuse`
- `Type-S 20A 125V Fuse`

### Convention Notes

| Descriptor | Explanation                                                                                                                                                                                                                                |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `CLASS`    | Class-RK1, Class-RK5, Class-J, Class-T, Class-CC, Class-L, or Type-S (plug fuse). The class sets the dimensions, voltage rating, interrupting rating, and rejection features.                                                              |
| `AMPS`     | The ampere rating (for example 10A, 30A, 100A, 800A), matched to the circuit and the fuse holder's range.                                                                                                                                  |
| `VOLTS`    | The voltage rating (for example 125V, 250V, 600V). Class R fuses of 250V and 600V are not interchangeable.                                                                                                                                 |
| `SPEED`    | Time-Delay (tolerates motor inrush and brief overloads) or Fast-Acting (opens quickly); omit where the product does not state it, as with many plug fuses. Confirm the characteristic on the datasheet, since class alone does not set it. |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for single fuses or spares.|
|**Set of 3**|A common order quantity for three-phase equipment, one fuse per pole.|
|**Box**|Manufacturer packaging, with the quantity depending on the class and ampere rating.|
|**Case**|Distributor bulk quantity for stock and larger projects.|

### Ordering Help

- Match the **class to the fuse holder or fuse block**, not just to the amperage. Rejection features exist so a lower-rated fuse cannot be installed in the holder, and the holder is made for one class.
- Replace a fuse with the **same class, ampere rating, and voltage**. A different class may physically fit, and a different rating defeats the protection; the 250V and 600V Class R sizes also differ.
- Use **Time-Delay fuses on motors and other inductive loads**; a fast-acting fuse sized for running current will typically open on start-up inrush. Size motor branch-circuit fuses to NEC Table 430.52, which allows up to 175% of full-load current for dual-element time-delay fuses and up to 300% for non-time-delay fuses.
- Check the **interrupting rating against the available fault current**, and note that a fuse with no marked interrupting rating is treated as 10,000A.
- Order fuses **in sets for three-phase equipment** and keep spares of the common classes and ratings on hand, since a blown fuse in a disconnect stops the equipment until it is replaced.
- Plug fuses: **Type S fuses require a Type S adapter** sized to the conductor, and Edison-base fuses are permitted only as replacements in existing installations, so confirm the panel before ordering plug fuses.
- Confirm the **edition of the NEC your jurisdiction enforces**, since section numbers and wording change between editions. 

_Generated Schematic_
![](/images/fuse-schematic.png)