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
date: 2026-07-10
---
## Overview

Wiring connectors are the small hardware used to terminate the end of a conductor for connection to a device, another conductor, or a data network — as distinct from wire nuts, which splice conductors together inside a box. This page covers two closely related but functionally distinct families: **RJ45 (Ethernet/data) connectors** and **general-purpose crimp terminal connectors** (ring, spade/fork, butt splice, and quick-disconnect/blade terminals).

![](/images/wiring-connector-example.png)

**RJ45 connectors** terminate twisted-pair Ethernet cable (see the Ethernet Cable page) for connection to a jack, patch panel, or network device. They are selected based on:

1. **Category match** — <cite index="11-1">the connector must be purchased to exactly match the cable's printed category (Cat5e, Cat6, or Cat6a), since the physical connector design changes to accommodate thicker wire as speeds increase</cite>.
2. **Shielding match** — <cite index="11-1">a UTP (unshielded) cable requires an unshielded connector, and an STP/FTP (shielded) cable requires a shielded connector with a metal shell</cite>; mismatching shield type between cable and connector degrades or defeats the shielding entirely.
3. **Wire gauge compatibility** — <cite index="11-1">standard Ethernet connectors accommodate 23–26 AWG conductors</cite>, but the connector's internal channel size must be checked against the specific cable's conductor and insulation diameter.

## Further Resources

- [ShowMeCables – RJ45 Connector Types Explained](https://www.showmecables.com/blog/post//rj45-connector-types-explained-cat5e-cat6-cat6a-shielded) — practical buying guide covering category, shielding, AWG matching, and pass-through vs. standard connectors.
- [trueCABLE – Cat6/6A RJ45 Connectors](https://www.truecable.com/products/cat6-6a-pass-through-rj45-connectors-shielded) — manufacturer reference on shielded vs. unshielded RJ45 connector construction and PoE compatibility.
- [ANSI/TIA-568.2-D](https://tiaonline.org/products-solutions/standards/) — the governing performance standard RJ45 connectors are tested and rated against.
- [ConnectorSupplier – What Are Crimp Terminals?](https://connectorsupplier.com/what-are-crimp-terminals/) — overview of ring, spade, butt splice, and blade terminal construction and history.
- [OurPCB – Wire Harness Terminal Types: Ring, Spade, Pin & Crimp Terminal Selection Guide](https://customwireassembly.com/resources/learning-center/wire-harness-terminal-types-selection-guide/) — detailed sizing, plating, and crimp specification reference across terminal families.
- [UL 486A-486B / UL 486C – Wire Connectors and Splicing Wire Connectors](https://www.shopulstandards.com/) — the UL safety standards governing crimp terminal and splice connector construction and pull-out force testing.

## Naming Convention

When identifying some sort of connector for vendor ordering, use the following naming structure, listing attributes in this order:

```
(SIZE) STYLE TYPE CATEGORY (MATERIAL) (SHIELDING) Connector
```

| Descriptor    | Explanation                                                                                                                                                |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `(SIZE)`      | Any optional size related information to the connector such as AWG.                                                                                        |
| `STYLE`       | Style of the connector; typical styles include Pass-Through, Multimode, Singlemode, Toolless, Standard, Blocker, CAT5E, CAT6, etc.                         |
| `TYPE`        | Type of the connector which refers to how the connector is fastened. Examples include compression, RJ45, etc.                                              |
| `CATEGORY`    | Broad category of the connector or wiring type that the connector connects to, for example Ethernet, Fiber, Coaxial, etc.                                  |
| `(MATERIAL)`  | Optional material specifier for plating, surrounding material, etc. for example Gold-Plating. If left off, assume, the default material for the connector. |
| `(SHIELDING)` | Optional shielding specifier, Shielded or Unshielded. If left off, assume                                                                                  |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Occasionally used for large or specialty connectors, but uncommon as a standalone ordering unit for small terminals.|
|**Bag/Pack**|Most common small-quantity packaging for both RJ45 connectors and crimp terminals, typically **10, 25, 50, or 100 per pack**.|
|**Box/Jar**|Common bulk packaging for jobsite or truck stock, typically **100 per box** for RJ45 connectors and **100 or 500 per jar** for crimp terminals.|
|**Assortment Kit**|Multi-size, multi-style kits (particularly common for crimp terminals) covering a spread of gauges and styles in one package — useful for stock but not for a single specified order.|
|**Case**|Distributor bulk quantity made up of multiple boxes or jars; used for large project takeoffs.|

### Ordering Help

- For **RJ45 connectors**, always confirm category, shield type, and AWG range against the specific cable being terminated before ordering — a mismatch on any one of these degrades performance or prevents proper termination altogether.
- Confirm which **crimping tool** (standard, pass-through, or ratcheting die-specific) is compatible with the connector or terminal style ordered — pass-through RJ45 connectors and many terminal styles require a matching tool, not a generic crimper.
- Avoid ordering **assortment kits** for a specified job — they're useful for general stock or field trucks, but a designed installation should specify exact style/size/gauge combinations as discrete line items to avoid running short on the specific size actually needed.
- For **wet, outdoor, or vibration-prone environments**, specify heat-shrink or fully-insulated crimp terminals, and confirm RJ45 connectors are rated for the installation environment, since most shielded RJ45 connectors are designed for indoor use only.

_Generated Schematic_
![](/images/wiring-connector-schematic.png)