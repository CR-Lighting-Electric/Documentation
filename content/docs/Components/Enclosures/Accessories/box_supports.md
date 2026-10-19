---
title: Box Supports
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-10-02
---
## Overview

A box support (bracket) is the stamped-steel hardware that secures an electrical box to framing — a stud, joist, or the floor — in new-work construction, used wherever the box itself doesn't have an integral nailing flange or needs to be positioned independent of exactly where the framing lands. The single-stud mounting bracket style is universally nicknamed a **"steam boat"** on the field, after the shape of its stamped profile — a flat base with the ends bent upward, resembling a small hull. They are also commonly known as **"F-clips."** Box supports are a routine companion item to the Switch Boxes, Square Boxes, and Masonry Boxes already covered in this documentation, since those boxes are frequently ordered without their own mounting means and rely on one of these bracket types to actually get fastened to framing.

![](/images/box-support-example.png)

Box support types:

- **Stud bracket ("steam boat")** — a single-piece bracket that mounts a box to the face or side of one stud, commonly with a snap-on or screw-on connection; available for standard single-gang/4" boxes and gangable for multi-box runs. This is the shape that earns the "steam boat" nickname in the field.
- **Bar hanger** — a horizontal bar spanning between two studs or joists, with the box mounted at a point along its length; **fixed** bar hangers are a set length for standard stud/joist spacing (16" or 24" on-center), while **adjustable (telescoping)** bar hangers extend to fit non-standard spacing and allow the box position to be fine-tuned along the bar before fastening.
- **Offset/wrap-around bracket** — wraps around the stud face to accommodate a range of stud depths (commonly 2.5" to 6"), used where stud dimensions vary or where the box needs to sit at a specific offset from the stud face.
- **Floor-mount stand** — a rigid upright bracket that positions a box at a fixed height above a floor slab or deck before pour, commonly used for floor-box rough-ins (see the Floor Boxes-adjacent coverage elsewhere in this documentation) or equipment requiring a box mounted above finished floor level.

Box supports are selected based on:

1. **Framing type and spacing** — a Stud-Bracket for single-stud mounting, a Bar-Hanger (fixed for standard on-center spacing, adjustable for non-standard spacing) for spanning between two studs/joists, an Offset-Bracket where stud depth varies, or a Floor-Stand for floor-mounted rough-in.
2. **Box compatibility** — matched to the box size/type being mounted (most support 4", 4-11/16", or single-gang boxes; some include an integral or adjustable mud ring, consolidating the bracket and ring into one part).
3. **Adjustability** — Fixed brackets install faster where spacing is already standard; Adjustable/telescoping brackets handle non-standard spacing or allow fine positioning before final fastening.
4. **Material** — Pre-Galvanized-Steel is the standard finish for corrosion resistance during and after construction; Stainless-Steel for corrosive-environment installations.
5. **Gang count** — single-box brackets for individual device/junction boxes, gangable brackets where multiple boxes need to be mounted together at a consistent spacing (e.g., a multi-gang device run).

## Further Resources

- [Eaton – Box Supports (Support Systems Catalog)](https://www.eaton.com/us/en-us/catalog/support-systems/box-supports.html) — manufacturer catalog reference covering stud brackets, fixed/adjustable bar hangers, wrap-around offset brackets, and floor-mount stands.
- [Hubbell RACO – Universal Stud-Mount Brackets](https://www.hubbell.com/raco/en/news/universal-stud-mount-brackets) — manufacturer reference on snap-to-stud bracket design, gangability, and integral/adjustable mud ring options.
- [Orbit Electric – Adjustable Bar Hangers for Stud Walls & Ceiling Joists](https://www.orbitelectric.com/adjustable-bar-hangers-for-stud-walls-ceiling-joists.html) — reference on adjustable/telescoping bar hanger design and use.

## Naming Convention

When identifying box supports for vendor ordering, use the following naming structure, listing attributes in this order:

```
TYPE MOUNT MATERIAL Box-Support
```

### Example Names

- `Stud-Bracket Fixed Pre-Galvanized-Steel Box-Support`
- `Steam-Boat Box-Support`
- `Bar-Hanger Adjustable Pre-Galvanized-Steel Box-Support`
- `Bar-Hanger Fixed Pre-Galvanized-Steel Box-Support`
- `Offset-Bracket Adjustable Pre-Galvanized-Steel Box-Support`
- `Floor-Stand Pre-Galvanized-Steel Box-Support`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                                     |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `TYPE`       | Stud-Bracket or Steam-Boat (single-stud mount, field-nicknamed "steam boat"), Bar-Hanger (spans between two studs/joists), Offset-Bracket (wraps around varying stud depths), or Floor-Stand (fixed-height floor rough-in mount).               |
| `(MOUNT)`    | Fixed (set length/position, for standard on-center spacing) or Adjustable (telescoping, for non-standard spacing or fine positioning); NA for Floor-Stand, which mounts at a fixed height rather than a span. Default to Fixed for Steam-Boats. |
| `(MATERIAL)` | Pre-Galvanized-Steel (standard corrosion resistance) or Stainless-Steel (corrosive-environment installations). Default to Pre-Galvanized-Steel for Steam-Boats.                                                                                 |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Occasionally used for large or specialty brackets.|
|**Pack**|Common small-quantity packaging, typically **10-25 per pack**.|
|**Box**|Standard bulk packaging for common sizes/types on larger construction projects.|

### Ordering Help

- Confirm **stud/joist spacing before ordering Fixed bar hangers** — a fixed-length bar hanger sized for 16" on-center framing won't fit 24" on-center spacing; an Adjustable/telescoping bar hanger avoids this mismatch on jobs with mixed or non-standard framing.
- Where a box needs a **mud ring as well as a mounting bracket**, check for an integral or adjustable-mud-ring bracket option before ordering the two as separate parts — several manufacturers combine them into a single product.
- Use an **Offset/wrap-around bracket** rather than a standard stud bracket wherever stud depth varies from the typical dimensional lumber or metal stud size, to keep the box at a consistent, code-compliant setback from the finished wall surface.
- **"Steam boat"** is the common field name for the single-stud bracket specifically — useful to know when a request comes in using that term rather than the catalog name, so the right product gets ordered.
- Box supports are a **routine companion item to new-work box orders** — confirm bracket quantity and type are included alongside the box order itself rather than assuming the box ships with adequate mounting means.

_Generated Schematic_
![](/images/box-support-schematic.png)