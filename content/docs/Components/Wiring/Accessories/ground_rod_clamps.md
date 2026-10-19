---
title: Ground Rod Clamps
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

A ground rod clamp is the fitting that connects the grounding electrode conductor to a ground rod. It is the bolted joint at the top of the rod, and it is usually buried, so it has to hold up in soil or concrete as well as carry fault current. It pairs with the rod on the Ground Rods page and the conductor that runs back to the Ground Bars and Busbars covered elsewhere in this documentation.

![](/images/ground-rod-clamp-example.png)

**Field names:** Ground rod clamps are called **"Acorns"** on the field. The name comes from the acorn-style clamp, a cast bronze clamp that fits a range of rod sizes, and is used for rod clamps in general, including the dual-nut and U-bolt styles. A vendor will not recognize it, so write the order with the plain-language name from the convention below.

NEC 250.70 sets what a rod clamp has to be:

- **Listed for the electrode material** — ground clamps must be listed for the material of the grounding electrode, so a clamp is chosen for the rod it goes on.
- **Listed for direct burial** — clamps used on a rod or other buried electrode must also be listed for direct soil burial or concrete encasement. UL 467 listed parts are suitable for direct burial in earth or concrete.
- **One conductor per clamp** — only one conductor goes on a clamp unless the clamp is listed for more than one.
- **Listed connection** — acceptable methods include exothermic welding, listed lugs, listed pressure connectors, and listed bolted cast bronze, brass, or iron clamps; connections that rely on solder are not allowed.

Clamp styles:

- **Acorn (universal, single-nut)** — a cast clamp that fits a range of rod diameters (for example 1/2" to 3/4") and takes a conductor range of about #10 solid to 1/0 stranded. The nVent ERICO CP34 is a silicon bronze example. One nut tightens the conductor and the rod together.
- **Dual-nut** — a clamp with a separate bolt for the rod and for the conductor, so the conductor can be moved or changed without loosening the rod. Bronze versions are listed for larger conductors (for example 6 AWG through 350 MCM on 1/2" and 5/8" rod, and 2 AWG through 250 MCM on 3/4" rod).
- **U-bolt** — a clamp with a U-bolt that wraps the rod, listed for a wide rod range (for example 3/8" to 1") and larger conductors (for example 6 AWG through 500 MCM in bronze).

Rod clamps are selected based on:

1. **Rod** — the rod diameter and material, because the clamp must be listed for the rod (for example 1/2", 5/8", and 3/4" copper-bonded or galvanized steel).
2. **Conductor** — the grounding electrode conductor size, which must fit the clamp's range.
3. **Style** — Acorn for a standard connection, Dual-Nut where the conductor may change, and U-Bolt for larger conductors.
4. **Material** — Bronze is the usual body material, with bronze or stainless steel bolts; copper is also made.
5. **Listing** — look for UL 467 and direct burial.

## Further Resources

- [Iowa Association of Electrical Inspectors – Clamps Solve the NEC 250.70 Compliance Problem](https://iaeimagazine.org/2018/2018november/clamps-solve-the-nec-250-70-compliance-problem/) — reference on NEC 250.70, listed clamps, direct burial, and the one conductor per clamp rule.
- [nVent ERICO – Universal Ground Rod Clamp, Rod to Conductor, Bronze](https://origin-nvent.nvent.com/erico/products/universal-ground-rod-clamp-rod-conductor-bronze) — manufacturer reference for a bronze universal rod clamp listed to ANSI/UL 467 for direct burial.
- [McMaster-Carr – Grounding Rod Clamps](https://www.mcmaster.com/acorn-clamps) — catalog reference for single-nut, dual-nut, and U-bolt clamps with their rod sizes and wire ranges.
- [Houston Wire & Cable – Ground Rod Clamps](https://www.houwire.com/ground-rods-clamps/) — distributor reference for universal clamps in 1/2", 5/8", and 3/4" rod sizes, in cast copper alloy with bronze or stainless bolts.
- National Electrical Code (NEC), NFPA 70 — Article 250.70 (Methods of Grounding and Bonding Conductor Connection to Electrodes), 250.68 (Grounding and Bonding Conductor Connections to Grounding Electrodes), and 250.52 (Grounding Electrodes).
- UL 467 — the listing standard for grounding and bonding equipment, including rod clamps.

## Naming Convention

When identifying ground rod clamps for vendor ordering, use the following naming structure, listing attributes in this order:

```
ROD TYPE CONDUCTOR MATERIAL Ground-Rod-Clamp
```

### Example Names

- `1/2" Acorn 10-AWG-1/0-AWG Silicon-Bronze Ground-Rod-Clamp`
- `5/8" Acorn 6-AWG-2-AWG Bronze Ground-Rod-Clamp`
- `5/8" Dual-Nut 6-AWG-350-KCMIL Bronze Ground-Rod-Clamp`
- `3/4" Dual-Nut 2-AWG-250-KCMIL Ground-Rod-Clamp`
- `3/8" U-Bolt 6-AWG-500-KCMIL Ground-Rod-Clamp`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `TYPE`       | Acorn (universal single-nut clamp), Dual-Nut (separate rod and conductor bolts), or U-Bolt.                                                                                                                                |
| `ROD`        | The rod diameter or range the clamp is listed for (for example 5/8" or 1/2"-3/4"). Match it to the rod on the Ground Rods page.                                                                                            |
| `CONDUCTOR`  | The conductor range the clamp accepts, written as the span from the smaller number (for example 10-1/0AWG or 6AWG-350MCM); the conductor goes with the clamp, one conductor per clamp unless the clamp is listed for more. |
| `(MATERIAL)` | Bronze (default), Silicon-Bronze, or Copper. Confirm the bolt material (bronze or stainless steel) in the catalog.                                                                                                         |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for a single clamp.|
|**Bag or Box**|Common packaging, with the count depending on the model and size.|
|**Case**|Distributor bulk quantity for larger projects.|

### Ordering Help

- Order the **clamp with the rod**: confirm the rod diameter and material (copper-bonded, galvanized, or stainless) against the clamp's listing, since NEC 250.70 requires a clamp listed for the electrode material.
- Order **only direct burial clamps** (UL 467) for any connection that will be buried or encased in concrete. Keep the listing mark on the clamp visible until the inspector has seen it.
- Check the **conductor range** against the grounding electrode conductor, which is sized from the service or feeder; an Acorn covers about #10 to 1/0, so larger conductors need a dual-nut or U-bolt clamp.
- Use **one conductor per clamp** unless the clamp is listed for more, and order extra clamps where several conductors land on one rod.
- Choose **Dual-Nut** where the conductor may be changed later without disturbing the rod, and **U-Bolt** where the rod diameter varies or the conductor is large.
- **Match the clamp, rod, and conductor metals** to avoid galvanic corrosion, and do not paint or coat the rod where the clamp makes contact.
- Tighten to the **manufacturer's torque**. One manufacturer cites a UL 467 requirement of 150 inch-pounds and states its clamp exceeds it; confirm the torque for the model installed.
- Confirm the **edition of the NEC your jurisdiction enforces**, since section numbers and wording change between editions.

_Generated Schematic_
![](/images/ground-rod-clamp-schematic.png)