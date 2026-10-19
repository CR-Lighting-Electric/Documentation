---
title: Cable Supports
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

A cable support is a fitting that holds a cable in place and keeps it from hanging by its own weight or from its connections. On electrical orders it covers three jobs that share the name: fastening cable to framing, hanging low-voltage cable runs, and carrying the weight of conductors in vertical raceways. The type is set by the job, not by the cable alone.

![](/images/cable-support-example.png)

**Field names:** The stud-mounted cable support is called a **"Colorado Jim"** on the field. The name matches the nVent CADDY "Colorado Jim" cable support, a hammer-on bracket that mounts to wood or metal studs, and it is now used for the whole family of stud-mount supports from any maker. Vertical-riser supports are often called **"Kellems grips"** after the Hubbell Kellems brand, again used generically.

Scope against neighboring pages: this page covers supports that hold cable. Conduit straps and strut are raceway supports and are not covered here, and the clamps that fasten a cable at a box are box connectors, not cable supports.

Cable support types:

- **Stud support (Colorado Jim)** — a hammer-on bracket that mounts to a wood or metal stud and holds one or more cables. nVent describes the CADDY version as having a locking tab for installation, ribs that position cables and keep them separated, flared edges that protect the cables, and mounting to wood or metal studs. It is listed to ANSI/UL 2239 and is described by nVent as meeting the cable protection requirement of NEC 300.4(D). A standoff version (CJ6S) holds the cables off the face of the stud.
- **J-hook** — an open steel hook hung from a wall, ceiling, or threaded rod that carries low-voltage data and communications cable in loose bundles. The nVent CADDY Cat HP J-hook is pregalvanized steel and plenum-suitable (UL 2043), and its 2" size is rated for 60 lb static load and listed at 90 Cat 5e, 60 Cat 6, or 35 Cat 6A cables at 70% fill. Non-continuous supports may not exceed 5' spacing under TIA 569.
- **Vertical riser support** — a device that takes the weight of conductors in a long vertical raceway so that it does not hang on the terminations. NEC 300.19 requires support at the top and at intermediate points set by a table on conductor size and material, and 300.19(C) accepts insulating wedge clamping devices at the raceway end, pull boxes with insulating supports, junction boxes where the conductors turn 90 degrees, or other approved means. The wedge type is a one-piece or segmented plug of impregnated hardwood or thermoset plastic; a split-body retrofit type can be installed around cables already in place. A Kellems-style grip is a woven-wire sleeve that takes the load.

NM cable carries its own securing rule: NEC 334.30 requires cable to be secured at intervals of no more than 4-1/2' and within 12" of each box, cabinet, or conduit body, with no more than 18" of cable between the entry and the nearest support. Stud supports are one way of meeting that spacing where cable runs through or along framing.

Cable supports are selected based on:

1. **Job** — framing, low-voltage run, or vertical riser, which sets the type.
2. **Mount** — hammer-on for studs, wall or ceiling or threaded rod for J-hooks, conduit or box-mounted for risers.
3. **Size** — the cable count and cable gauge for stud supports, the hook diameter for J-hooks, and the conduit size and cable diameter for risers.
4. **Material** — steel for most, with a plenum rating where the space needs it; wedge types of hardwood or thermoset plastic.
5. **Listing** — look for the UL listing for the application, such as ANSI/UL 2239 for stud supports and UL 2043 for plenum use.

## Further Resources

- [nVent CADDY – "Colorado Jim" Cable Support](https://origin-nvent.nvent.com/en-ar/caddy/products/colorado-jim-cable-support) — manufacturer reference for the hammer-on stud support, its features, and its listings.
- [Crescent Electric – Colorado Jim Cable Support with Standoff](https://www.crescentelectric.com/product/99059/colorado-jim-cable-support-with-standoff) — distributor listing for the CJ6S, with the cable gauges it holds.
- [nVent CADDY – Cat HP J-Hook CAT32HP Data Sheet](https://www.nvent.com/sites/default/files/acquiadam/assets/H88587-USEN.pdf) — manufacturer reference on J-hook size, cable capacity, static load, and mounting.
- [EC&M – Hanging Tough with Vertical Cable Supports](https://www.ecmweb.com/construction/article/20904254/hanging-tough-with-vertical-cable-supports) — reference on NEC 300.19, wedge-type supports, and split-body retrofit supports.
- [Electrician U – Securing and Supporting NM Cable: A Guide to NEC Compliance](https://electricianu.com/securing-and-supporting-nm-cable-a-guide-to-nec-compliance/) — reference on NEC 334.30 securing intervals and 300.4 protection at framing.
- National Electrical Code (NEC), NFPA 70 — Article 300.4 (Protection Against Physical Damage), 300.19 (Supporting Conductors in Vertical Raceways), and 334.30 (Securing and Supporting NM Cable).
- ANSI/UL 2239 — the standard for hardware for the support of conduit, tubing, and cable.
- ANSI/TIA-569 — the telecommunications pathways and spaces standard, which sets the spacing for non-continuous cable supports.

## Naming Convention

When identifying cable supports for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPE (MOUNT) (MATERIAL) Cable-Support
```

### Example Names

- `10/4 Stud-Support Hammer-On Cable-Support`
- `10/4 Stud-Support Hammer-On-Standoff Cable-Support`
- `2" J-Hook Ceiling Steel Cable-Support`
- `2" J-Hook Threaded-Rod Steel Cable-Support`
- `1-1/4" Riser-Wedge Conduit-End Cable-Support`
- `2" Riser-Grip Conduit-End Cable-Support`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | For a stud support, the largest cable configuration it is made for (for example 10/4), per the catalog. For a J-hook, the hook diameter (for example 2"). For a riser support, the conduit trade size (for example 1-1/4"). For Stud-Support, default to 6/4 sizing. |
| `TYPE`       | Stud-Support (the Colorado Jim), J-Hook, Riser-Wedge (insulating wedge for vertical raceways), or Riser-Grip (Kellems-style woven grip).                                                                                                                             |
| `(MOUNT)`    | How it attaches: Hammer-On (stud support), Hammer-On-Standoff (stud support that holds the cable off the stud face), Wall, Ceiling, or Threaded-Rod (J-hook), or Conduit-End (riser support at the raceway end). Default to Hammer-On (stud support), .              |
| `(MATERIAL)` | Steel for J-hooks, or omit where the datasheet does not state it, as for stud supports and the riser types. Confirm any plenum rating in the catalog. Default aluminum for riser and grip wedges.                                                                    |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for riser supports and occasional single pieces.|
|**Bag or Box**|Common packaging for stud supports and J-hooks; the count depends on the model.|
|**Case**|Distributor bulk quantity for larger projects.|

### Ordering Help

- Pick the **type by the job first**: stud supports for cable on framing, J-hooks for low-voltage runs, and riser supports for conductors in long vertical raceways.
- For stud supports, **match the cable count and gauge to the model**. The CJ6S lists 14/4, 12/2, 10/2, 8/2, 14/3, 12/3, 10/3, 12/4, and 10/4, so confirm that the cable you run is on the model's list.
- Space supports to the **NM cable rule in NEC 334.30**: no more than 4-1/2' apart and within 12" of every box. Confirm the edition adopted locally.
- For **J-hooks, size by cable count and fill**, not by weight alone. The nVent 2" hook lists 35 Cat 6A at 70% fill. Keep non-continuous supports no more than 5' apart.
- Use **plenum-rated J-hooks** where the space is a plenum.
- For **vertical risers**, take the support spacing from NEC Table 300.19(A), based on conductor size and material, and support each cable rather than letting it hang on the others. Use the wedge types listed for the voltage and the insulation of the conductors.
- Confirm the **stud type** (wood or metal) before ordering stud supports, and confirm the mounting method in the catalog.

_Generated Schematic_
![](/images/cable-support-schematic.png)