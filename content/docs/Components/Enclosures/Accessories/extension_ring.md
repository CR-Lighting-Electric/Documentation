---
title: Extension Rings
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-09-23
---
## Overview

An extension ring is a box-shaped collar mounted to the front of an existing square box (or other box) to add depth — used where a box has been set too shallow relative to the finished wall surface, where more physical room is needed for larger conductor counts or additional devices/fittings, or where a box needs to be brought forward after a wall finish (tile, extra layers of drywall, etc.) has been added. Unlike a mud ring, an extension ring keeps the box's full square opening intact rather than reducing it down to a device-sized opening — it's a volume/depth accessory, not a device-mounting accessory. Where both functions are needed on the same box (more depth _and_ a device-sized opening), an extension ring and a mud ring are stacked together.

![](/images/extension-ring-example.png)

The distinction that matters most when ordering an extension ring is whether it adds **legal box-fill volume** under NEC 314.16, and this is not simply a function of its physical depth:

- **Volume-marked (listed) extension rings** are stamped or marked with their own cubic-inch volume, and that volume can be legally added to the base box's volume when calculating box fill for the assembly.
- **Unmarked extension rings** solve a physical/depth or wall-finish problem (bringing the box face forward, giving more working room) but add zero legal box-fill volume to the calculation — regardless of how deep the ring physically is. Using an unmarked ring and assuming it buys additional fill capacity is a code compliance mistake.

This is the opposite failure mode from a mud ring, which is explicitly a finishing/device accessory and isn't expected to add volume at all — see the Mud Rings page. An extension ring can go either way depending on its specific listing, which is why the marking must be checked rather than assumed from appearance or depth alone.

Extension rings are selected based on:

1. **Box size fit** — sized to match the specific box it's extending (commonly 4" or 4-11/16" square, matching the Square Boxes page's sizing), and not interchangeable between box sizes.
2. **Depth** — how far the ring extends the box forward, commonly available from 1/4" up through 2-5/8" or more, including some adjustable-depth ranges; selected based on the physical clearance or wall-finish problem being solved.
3. **Volume listing** — Volume-Marked (carries a cubic-inch rating usable in box-fill calculations) or Unmarked (depth/finish accessory only, no legal fill contribution); this must be confirmed against the specific product, not assumed.
4. **Material** — steel is standard and most common; aluminum, nonmetallic (plastic), and other materials exist for specific environments or wiring systems, matched to the base box's material.
5. **Knockout configuration** — extension rings often include their own knockouts (commonly 1/2" through 2" trade sizes) for additional conduit entries at the extended depth.

## Further Resources

- [BoxFillCalculator.com – Extension Rings, Mud Rings, and Box Fill: What Adds Legal Volume?](https://boxfillcalculator.com/blog/extension-rings-mud-rings-box-fill) — reference explaining the critical distinction between volume-marked and unmarked extension rings under NEC 314.16, and how this differs from a mud ring's role.
- [McMaster-Carr – Electrical Box Extension Rings](https://www.mcmaster.com/products/electrical-box-extension-rings) — catalog reference for extension ring materials, depth ranges, knockout configurations, and gang options.
- [Mike Holt's Forum – Extension Rings](https://forums.mikeholt.com/threads/extension-rings.47431/) — field discussion on extension ring use cases and box-fill considerations.
- National Electrical Code (NEC), NFPA 70 — Article 314.16 (Number of Conductors in Outlet, Device, and Junction Boxes, governing which box-fill volume can be legally counted) and Article 314.20 (In Wall, Ceiling, or Floor; Flush Mounting).

## Naming Convention

When identifying extension rings for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE (CONSTRUCTION) DEPTH-Depth (KNOCKOUTS-KO) (MATERIAL) Extension-Ring
```

### Example Names

- `4" 1-1/2"-Depth Steel Extension-Ring`
- `4" 1/2"-Depth Extension-Ring`
- `4-11/16" 2"-Depth Aluminum Extension-Ring`
- `4" 1/4"-Depth Galvanized-Steel 3/4"-KO Extension-Ring`
- `4-11/16" 2-3/8"-Depth Extension-Ring`

### Convention Notes

| Descriptor       | Explanation                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`           | 4in or 4-11/16in — the specific square box size the ring is made to fit; extension rings are not interchangeable between box sizes.                             |
| `(CONSTRUCTION)` | Welded (individually welded seams) or Drawn (single-piece stamped construction, no welded seams); both are standard, code-recognized methods. Default to Drawn. |
| `DEPTH`          | The ring's extension depth (e.g., 1/4", 1/2", 1-1/2", 2-1/2"), selected based on the physical clearance or wall-finish problem being solved.                    |
| `(KNOCKOUTS)`    | Optional specifier for knockout sizing on the extension itself.                                                                                                 |
| `(MATERIAL)`     | Steel (standard, matched to metal boxes) or Nonmetallic (for nonmetallic box/wiring systems); confirm material matches the base box.                            |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Common for individual rings, especially larger or specialty depths.|
|**Pack**|Common small-quantity packaging, typically **10-25 per pack**.|
|**Case**|Distributor bulk quantity for large commercial or residential projects.|

### Ordering Help

- Always confirm whether the ring is **Volume-Marked or Unmarked** before relying on it to solve a box-fill problem — an unmarked ring adds physical depth but zero legal cubic-inch volume to the calculation under NEC 314.16, regardless of how deep it is.
- Confirm **box size fit (4in vs. 4-11/16in)** before ordering — like mud rings, extension rings are sized to one specific box and are not interchangeable.
- Where both **more depth and a device-sized opening** are needed on the same box, order an extension ring and a mud ring together as a stacked assembly rather than expecting one product to do both jobs.
- Extension rings are commonly used to **bring a box forward** after an unexpected wall-finish buildup (extra drywall layer, tile, etc.) — useful for correcting an as-built condition without resetting the box itself.
- When box-fill volume is the actual goal (not just physical clearance), it's often simpler and more reliably code-compliant to specify a **deeper base box** (see the Square Boxes page) from the start rather than relying on stacking a volume-marked extension ring after the fact — reserve extension rings for retrofits and corrections where resetting the box isn't practical.

![](/images/extension-ring-schematic.png)