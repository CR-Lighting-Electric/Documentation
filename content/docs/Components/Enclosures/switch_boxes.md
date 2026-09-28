---
title: Switch Boxes
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-09-22
---
## Overview

A switch box (also called a device box) is the enclosure mounted in a wall to house a switch, receptacle, or other wiring device, providing the mounting points for the device's yoke and containing the wire splices/connections behind it. Despite the name, the same box style is used for switches, receptacles, and most other single-device wall openings — "switch box" and "device box" are used interchangeably in the field.

Switch boxes are selected based on:

1. **Gang count** — a single-gang box holds one device; multi-gang boxes (2-gang, 3-gang, 4-gang, etc.) hold multiple devices side by side under a single multi-opening cover plate. Multi-gang metal boxes are typically ganged from individual single-gang boxes with removable side plates; multi-gang plastic boxes are usually molded as one piece.
2. **Material:**
    - **Metal (steel)** — required in some installations for mechanical protection or where the box must bond to a metal raceway system as part of the grounding path; used with metal (EMT, rigid) conduit runs.
    - **Nonmetallic (PVC/plastic)** — the common choice with NM cable (Romex) wiring; lower cost, no bonding required, and includes molded-in cable clamps on many models. Not used where the wiring method requires a metal box (e.g., certain conduit terminations).
    - **Fiberglass/polycarbonate** — heavier-duty nonmetallic option for higher-durability or specific listing requirements.
3. **Mounting type:**
    - **New-work (new construction)** — has an integrated nail-on bracket, flange, or fixed ears for direct fastening to an exposed wall stud before drywall goes up.
    - **Old-work (remodel/retrofit)** — has no stud-mounted bracket; instead uses swing-out mounting ears/wings that clamp against the back of the drywall when tightened, or a separate adjustable bar hanger between studs, allowing installation into a finished wall with no stud access.
4. **Depth and volume (cubic inches)** — box interior volume must be sufficient for the number of conductors, devices, and fittings it will contain per NEC 314.16 box-fill rules; deeper boxes and boxes with volume markings (required by code on nonmetallic boxes and metal boxes over a certain size) give more fill capacity for larger conductor counts or multiple devices sharing a box.
5. **Cable entry** — nonmetallic boxes commonly include molded-in cable clamps or knockouts sized for NM cable; metal boxes use separate NM connectors or conduit fittings through their knockouts (see the NM Connectors page for the fitting itself).

## Further Resources

- [ExpertCE – Choosing and Installing Old Work vs. New Work Electrical Boxes](https://expertce.com/learn-articles/old-work-vs-new-work-electrical-boxes/) — guide comparing new-work bracket-mounted boxes to old-work clamp/wing-mounted boxes and when each applies.
- [This Old House – How To Choose an Electrical Box](https://www.thisoldhouse.com/ask-this-old-house/21115317/how-to-choose-an-electrical-box) — overview of box material, gang count, and mounting style selection.
- [ECM Magazine – Box-Fill Calculations: Understanding NEC Article 314, Part III](https://www.ecmag.com/magazine/articles/article-detail/codes-standards-box-fill-calculations-part-iii) — reference on NEC 314.16 box-fill volume rules, what counts toward fill, and cubic-inch marking requirements.
- [Carlon – Nonmetallic Adjustable One-Gang, 2-, 3-, 4-Gang Old Work Ceiling Boxes](https://carlonsales.com/techinfo/brochures/electrical/Zip%20Boxes_2B1.pdf) — manufacturer reference for nonmetallic old-work box construction and gang options.
- National Electrical Code (NEC), NFPA 70 — Article 314.16 (Number of Conductors in Outlet, Device, and Junction Boxes) and Article 314.17 (Conductors Entering Boxes), governing box-fill volume and cable entry/securing requirements.

## Naming Convention

When identifying switch boxes for vendor ordering, use the following naming structure, listing attributes in this order:

```
GANG MATERIAL MOUNT DEPTH Switch-Box
```

### Example Names

- `1-Gang Nonmetallic New-Work 3.5in Switch-Box`
- `1-Gang Nonmetallic Old-Work 3.5in Switch-Box`
- `2-Gang Nonmetallic New-Work 3.5in Switch-Box`
- `1-Gang Metal New-Work 2.5in Switch-Box`
- `3-Gang Metal New-Work 3in Switch-Box`
- `1-Gang Metal Old-Work 2.5in Switch-Box`

### Convention Notes

| Descriptor     | Explanation                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| GANG           | Single, Double, Triple, Quad, etc. — the number of devices the box is sized to hold side by side under one cover plate.                                                                                                       |
| MATERIAL       | Nonmetallic (PVC/plastic, standard with NM cable), Metal (steel, used with metal conduit or where bonding/mechanical protection is required), or Fiberglass (heavier-duty nonmetallic option).                                |
| MOUNT          | New-Work (nail-on bracket for open stud framing) or Old-Work (swing-ear/wing clamp or bar-hanger mount for finished walls). Cut-In and Old-Work can be used interchangeably.                                                  |
| DEPTH          | The box's interior depth (e.g., 2.5in, 3in, 3.5in), which along with gang count determines cubic-inch volume and box-fill capacity per NEC 314.16.                                                                            |
| Catalog number | Vendor catalogs (e.g., Carlon, Raco, Steel City, Cooper Crouse-Hinds) also carry their own part numbers; provide both the plain-language name and the catalog number when known.                                              |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Occasionally used for large or specialty sizes, but uncommon as a standalone unit.|
|**Pack**|Common small-quantity packaging, typically **10-25 per pack**.|
|**Box**|Standard bulk packaging for common sizes, typically **50 or 100 per box**.|
|**Case**|Distributor bulk quantity for large commercial or residential projects; multiple boxes per case.|

### Ordering Help

- Always confirm **material matches the wiring method** — nonmetallic boxes are standard with NM cable, while metal conduit installations generally require a metal box for proper bonding and mechanical protection.
- Choose **mounting type based on the wall condition at install time** — new-work bracket boxes require open stud access; old-work boxes are required (and code-recognized) for finished-wall installs where studs aren't exposed.
- Always check **box-fill volume** against the actual number of conductors, devices, and fittings (including grounding conductors and clamps) that will share the box per NEC 314.16 — undersizing a box is one of the most common rough-in mistakes and a frequent inspection failure point.
- **Gang count** should be decided at rough-in based on the final device plan — combining switches, receptacles, or dimmers under one cover plate requires the correct multi-gang box up front, since retrofitting a single-gang box to multi-gang later means replacing the box.
- For **ceiling-mounted fixtures or fans**, confirm the box (and its listing) is rated for that specific use — a standard wall switch box is not necessarily rated for ceiling fan support weight; that's a separate box type from the ones this page covers.