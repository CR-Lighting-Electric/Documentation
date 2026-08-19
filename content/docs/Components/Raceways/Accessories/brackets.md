---
title:
description:
function:
type: docs
obstype: component
related:
  - "[[Documentation/Components/Raceways/strut|strut]]"
next:
prev:
sidebar:
open: true
date: 2026-08-13
---
## Overview

Brackets are the structural fittings used to build support framework for raceways — most commonly strut/channel-based systems (e.g., Unistrut, Power-Strut, B-Line) — rather than fastening a single conduit directly to a wall the way a strap does. Brackets connect strut channel to a building structure, join strut sections to one another, or build out trapeze and rack assemblies that carry multiple conduits, cable trays, or raceways together across a span.

![Bracket Example](/images/bracket-example.png)

Brackets are selected based on:

1. **Connection function:**
    - **Wall/surface bracket** — anchors a length of strut channel directly to a wall or vertical surface, creating a fixed cantilevered support point.
    - **Angle bracket** — joins two pieces of strut at a fixed angle (typically 90°), used to build corners, L-shaped frames, or perpendicular branch supports.
    - **Channel/flat bracket** — a general-purpose flat fitting that joins strut sections in a flat, parallel, or end-to-end configuration.
    - **Post base** — anchors a vertical strut post to a floor or concrete surface, forming the foundation of a freestanding rack or support frame.
    - **Trapeze bracket** — used in pairs with a horizontal strut span to create an overhead trapeze support, allowing multiple conduits or a cable tray to be carried across a span from two suspension points.
    - **Beam clamp** — attaches strut channel or conduit directly to a structural steel beam or flange without drilling or welding.
2. **Adjustability** — fixed 90° brackets provide a rigid, non-adjustable connection, while adjustable/swivel brackets accommodate non-standard angles or field conditions where framing isn't perfectly square.
3. **Load rating** — brackets are rated for a maximum supported load (commonly expressed in lbs.), which varies by bracket size, gauge, and material — critical for trapeze and multi-raceway support applications where cumulative weight matters.
4. **Strut channel size compatibility** — brackets are manufactured to match a specific strut channel width, most commonly the industry-standard **1-5/8"** channel, with standard **9/16" holes on 1-7/8" centers**. Brackets sized for one channel width or hole spacing are not compatible with a different series.
5. **Material and finish:**
    - **Electro-galvanized (EG) or pre-galvanized (PG) steel** — standard finish for general indoor use.
    - **Hot-dip galvanized (HDG) steel** — heavier zinc coating for outdoor, rooftop, or corrosion-prone environments.
    - **Stainless steel (304/316)** — used in cleanrooms, food/beverage facilities, coastal environments, or other highly corrosive settings.

**Installation notes worth flagging:**

- Matching finishes between the bracket and the strut channel it connects to is recommended, particularly outdoors — mixing a zinc-plated bracket with hot-dip galvanized channel can accelerate galvanic corrosion at the joint.
- Nuts and bolts (typically strut-specific spring nuts and hex bolts) are usually sold separately from the bracket itself and must be ordered as their own line item.
- Bracket hole spacing must match the strut channel's slot spacing — this is standardized industry-wide at 1-7/8" centers for 1-5/8" channel, but should still be confirmed against the specific manufacturer's series before ordering.

## Further Resources

- [Unistrut Store – Unistrut Fittings: Brackets & Accessories](https://unistrutstore.com/1-58-metal-framing/unistrut-fittings.html) — manufacturer reference covering flat, 90°, angle, Z, and U-shape bracket types for 1-5/8" strut channel.
- [Unistrut Buffalo – Unistrut Brackets & Braces](https://unistrutstore.com/1-58-metal-framing/unistrut-brackets.html) — detailed reference on wall brackets, adjustable braces, and material/finish specifications (ASTM A575, A576, A635, A36).
- [Shielden Strut – Top 10 Strut Channel Fittings](https://shieldenstrut.com/blogs/news/top-10-strut-channel-fittings-you-need-for-reliable-and-efficient-installation/) — practical guide covering channel brackets, trapeze/adjustable brackets, beam clamps, and finish selection by environment.
- [Power-Strut – Engineering Catalog (PDF)](https://powerstrut.com/Power-Strut-Catalog_2017.pdf) — comprehensive manufacturer catalog including trapeze system design, brackets and supports, and beam/C-clamp sections.
- National Electrical Code (NEC), NFPA 70 — Articles 342.30, 344.30, 348.30, 352.30, and 358.30 (Securing and Supporting) — governing support spacing requirements that bracket/trapeze layouts must satisfy.

## Naming Convention

When identifying brackets for vendor ordering, use the following naming structure, listing attributes in this order:

```
(SIZE) STYLE (DEGREE) TYPE (MATERIAL) (FINISH) Bracket
```

| Descriptor | Explanation                                                                                                                                              |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `(SIZE)`   | Optional size parameter for a specific sizing of the bracket if necessary. Default is 9/16" for angle.                                                   |
| `STYLE`    | The style of the raceway bracket, for example Five-Hole, Four-Hole, Two-Hole, Four-Hole-Tee-Splice, etc. in the case of strut brackets.                  |
| `(DEGREE)` | Optional degree specification of angle brackets, list as "45-Degree", "30-Degree", "60-Degree" for degree measurements and list "90-Degree" as "Corner." |
| `TYPE`     | Type of raceway bracket, i.e. Open-Angle, Closed-Angle, Tee-Splice, Splice, etc.                                                                         |

### Example Names

- `Four-Hole 45-Degree Open-Angle Bracket`
- `Two-Hole 60-Degree Closed-Angle Bracket`
- `5-1/2"x3-1/2" Four-Hole Tee-Splice Bracket`
- `7-1/4" Four-Hole-Flat Steel Bracket`
- `3-1/2"x3-1/2" Three-Hole-Flat Stainless-Steel Bracket`
- `9/16" 30-Degree Closed-Angle Pre-Galvanized Bracket`

### Convention Notes

- Lead with **SIZE** if necessary as the strut channel width the bracket is sized for (e.g., "158in" for 1-5/8" channel) — this is the single most important compatibility field, since brackets are not interchangeable across channel series.
- State **STYLE** as Wall, Angle90, Flat, PostBase, Trapeze, BeamClamp, or Adjustable to identify the bracket's connection role.
- State **STYLE** as the style of fastening for the bracket, separated by hyphen. Any amount of holes, specific fastener shapes, etc. should be specified here.
- State **TYPE** as the actual type of the bracket, which could be angle, tee splices, regular splices, etc. separated by hyphen.s
- State **FINISH** as Pre-Galvanized, Electro-Galvanized), Hot-Dip-Galvanized, Stainless-Steel.
- Note that **nuts, bolts, and channel nuts are ordered separately** from the bracket itself and are not implied by the bracket name — include them as their own line items on any order.

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and ordering — brackets are ordered individually or in small quantities based on the number of support points designed into the run.|
|**Box**|Common bulk packaging for smaller, high-volume bracket types, typically packed **10 or 25 per box**.|
|**Case**|Distributor bulk quantity for large commercial or industrial projects; multiple boxes per case.|
|**Pair**|Some bracket types (e.g., trapeze brackets) are sold or specified in matched pairs, since a single trapeze support point requires two.|

### Ordering Help

- Always specify **channel width, function, load rating, and finish** together — channel width alone does not guarantee fit or adequate load capacity for the application.
- Order **nuts, bolts, and channel nuts as separate line items** — these are almost never included with the bracket and are required for installation.
- For **trapeze supports**, confirm the load rating against the combined weight of all raceways/conduits to be carried across the span, not the weight of a single conduit, and order brackets in matched pairs.
- Match **finish between brackets and the strut channel** they'll be installed with, especially outdoors — mismatched finishes (e.g., zinc-plated bracket with HDG channel) can accelerate galvanic corrosion at the connection point.
- For **cleanroom, food-service, or coastal environments**, confirm stainless steel (304 or 316) construction rather than a standard galvanized finish before finalizing an order.

_Generated Schematic_
![](/images/bracket-schematic.png)