---
title: Labels
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
imported: true
date: 2026-10-23
---
## Overview

CNC label materials are the sheet plastics that panel identification labels are engraved and cut from on a CNC router. A label blank is a layered sheet: a top layer in one color over a core in a contrasting color, so the router cuts through the top layer and the lettering shows in the core color. The sheet is then profile-cut into individual labels, and in the field each label is attached to a panel, enclosure, or disconnect. This page covers the common sheet stocks bought for that work. It does not cover the finished, engraved label, the CNC router and its cutters, or pre-printed labels and markers.

![](/images/labels-example.png)

The supplier named for this work is Johnson Plastics Plus (JP Plus). The product lines below are the ones it lists, and the specifications come from its product pages.

Material families:

- **Two-ply and three-ply acrylic (Rowmark Mattes)** — a matte, non-glare acrylic with a top layer designed for fine, detailed rotary engraving, sold in 1/32", 1/16", and 1/8" thicknesses. JP Plus describes it for interior signage, plaques, industrial labels, and name badges. Sold with or without pre-applied adhesive, with a clear protective masking on the sheet.
- **Ultra-Mattes (front engraving)** — a matte, non-glare, fingerprint-resistant acrylic in 1/16" and 1/8" thicknesses. JP Plus describes it as suited for interior and exterior signage and challenging environments. A separate UltraMatte Reverse product is made for reverse engraving.
- **Value Series (ADA alternative)** — a single-ply matte acrylic, laser engravable and routable, in 1/32", 1/16", and 1/8" thicknesses and in 12" x 24", 24" x 24", and 24" x 48" sheets. Single-ply means the color is the same all the way through, so it suits cut-out and routed shapes better than contrast-color engraving.
- **Phenolic (Norplex)** — a three-ply phenolic made from layers of pigmented paper bonded with melamine resin, in 1/16" and 1/8" thicknesses, matte/polished or polished/polished, with or without adhesive. JP Plus describes it for nameplates and industrial and electrical signs, and for rotary engraving. It is brittle, contains hazardous materials per the product page, and is made to order.
- **ABS** — a tough, impact-resistant plastic that is typically extruded and rotary engravable only, and engraves faster than acrylic because it is softer.

Also seen at JP Plus but not for a CNC router:

- **Rowmark LaserMax** — sold as a laser engravable plastic, with dozens of two-tone combinations in 1/32", 1/16", and 1/8". It is for laser engravers; confirm with the manufacturer before routing it.

Materials to avoid on the router:

- **PVC and other chlorine-containing plastics**, which can release toxic fumes and damage equipment.
- **Polycarbonate**, which can produce hazardous fumes.
- **Painted plastics** and those with additives that can discolor or crack.

Label materials are selected based on:

1. **Environment** — interior or exterior, and the temperature and moisture of the space. Check the manufacturer's UV and weather recommendations before outdoor use.
2. **Durability** — NEC 110.21(B) requires field-applied hazard labels to withstand the environment and be permanently affixed. Phenolic and acrylic are the common choices.
3. **Thickness** — 1/16" for most panel labels and 1/8" for stiffer or larger plates.
4. **Color** — a top/core pair chosen for contrast and for color-coding (for example red/white for emergency or fire alarm).
5. **Mounting** — with adhesive backing, or without it for labels that are fastened with screws or rivets.
6. **Sheet size** — full, half, or quarter sheet, picked to nest the labels with little waste.

## Further Resources

- [JP Plus – Rowmark Plastic Sheet Stock for Engraving](https://www.jpplus.com/rowmark) — supplier overview of the Rowmark acrylic and ABS lines, thicknesses of 1/32", 1/16", and 1/8", and standard sheet sizes.
- [JP Plus – Rowmark Mattes Engraving Plastic](https://www.jpplus.com/mattes) — supplier page for the matte two-ply and three-ply acrylic for rotary engraving.
- [JP Plus – Rowmark Ultra-Mattes Front Engraving Plastic](https://www.jpplus.com/rowmark-ultra-mattes-ivory-dark-brown-engraving-plastic) — supplier page for the matte, fingerprint-resistant front-engraving acrylic.
- [JP Plus – Rowmark Value Series ADA Alternative Engraving Plastic](https://www.jpplus.com/rowmark-value-series-ada-alternative-engraving-plastic) — supplier page for the single-ply acrylic, with its sheet sizes and thicknesses.
- [JP Plus – Norplex Phenolic Sheet](https://www.jpplus.com/norplex-phenolic-sheet) — supplier page for the three-ply phenolic, with thicknesses, sheet sizes, ordering notes, and handling notes.
- [JP Plus – Engraving Plastics: Part One](https://jpplus.com/engraving-plastics-part-one) — article on acrylic and ABS, rotary and laser engraving, and the plastics to avoid.
- [JP Plus – Rowmark LaserMax Engravable Plastic](https://jpplus.com/rowmark-lasermax-engravable-plastic-from-johnson-plastics-plus) — supplier page for the laser engravable line.
- [EC&M – Make Your Mark: Electrical Circuits and Equipment Markings](https://www.ecmag.com/magazine/articles/article-detail/codes-standards-make-your-mark-electrical-circuits-and-equipment-markings-nec) — reference on the durability and permanence rules for field markings in NEC 110.21(B), 110.22(A), and 110.24.
- National Electrical Code (NEC), NFPA 70 — Article 110.16(B) (service equipment labels), 110.21(B) (field-applied hazard markings), 110.22 (identification of disconnecting means), 110.24 (available fault current marking), and 408.4 (panelboard directory).

## Naming Convention

When identifying CNC label materials for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE LINE COLOR (MATERIAL) (PLY) (ADHESIVE) Label-Stock
```

### Example Names

These examples show the pattern; confirm the colors, sizes, and availability on the JP Plus product page.

- `12"-24"-1/16" Mattes Red/White Adhesive ABS Label-Stock`
- `12"-24"-1/8" Mattes Yellow/Black No-Adhesive Acrylic Label-Stock`
- `12"-12"-1/16" Ultra-Mattes Ivory/Dark-Brown Adhesive Acrylic Label-Stock`
- `24"-24"-1/16" Rowmark Red/White ABS 3-Ply 3M-Standard-Adhesive Label-Stock`
- `18"-39"-1/8" Red/White Phenolic-Norplex Label-Stock`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | The sheet size in inches: Quarter, Half, or Full. For Rowmark, full is 24"-48" and half is 12"-24"; for Norplex phenolic, quarter is 18"-19.5", half is 18"-39", and full is 36" x 39". Use the `WIDTH-LENGTH-THICKNESS` naming here.    |
| `LINE`       | The product line, such as Mattes, Ultra-Mattes, or Rowmark (Matte acrylic), or Norplex (phenolic). The line commonly sets the ply count, finish, and engraving method.                                                                   |
| `COLOR`      | The face and core colors written as Face/Core (for example White/Black). A single-ply sheet takes one color (for example Black). Multi-word color names are hyphenated.                                                                  |
| `(MATERIAL)` | Acrylic, Phenolic, or ABS. Acrylic can be extruded or cast; cast acrylic starts at 1/4" thick, so label work uses extruded sheet. If the `LINE` dictates the material, then this field can be omitted and defaulted to whatever is used. |
| `(PLY)`      | Optional ply (layers) specifier for a more custom label stock order.                                                                                                                                                                     |
| `(ADHESIVE)` | Adhesive options attached to the underside of the stock. Rowmark acrylic and Norplex phenolic are both sold either way. Separate the description with hyphens.                                                                           |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Sheet**|Standard unit for label stock; full, half, and quarter sizes are made.|
|**Pack**|Occasional pack quantities for small sheets.|
|**Pallet**|Phenolic ships on a pallet per JP Plus.|

### Ordering Help

- Pick the **material by the use first**: Rowmark acrylic for interior and exterior panel labels, and phenolic for heavy-duty nameplates in industrial and electrical work.
- Order **rotary-engravable stock** for the CNC router. LaserMax is a laser product, and ABS engraves rotary only.
- Order **half or quarter sheets of phenolic**; JP Plus calls the material extremely brittle and recommends smaller sheets to reduce shipping damage. It is made to order, typically ships in 7 to 9 business days from the supplier, and is non-returnable, so confirm color and thickness before ordering.
- Treat **phenolic as a hazardous material** for shipping and handling, and read the supplier's data sheet before cutting. Plan for dust collection at the router (from memory, not on the supplier page).
- Never cut **PVC, polycarbonate, or painted plastics** on the router.
- Choose **colors for contrast and for the labeling system**, such as red/white for emergency equipment, and confirm the safety color on the project specification.
- Order **adhesive-backed stock** for labels stuck to flat panels, and non-adhesive stock for plates that are fastened. Keep the protective masking on until the label is cut.
- Use the **manufacturer's rotary engraving recommendations** for cutters and speeds; Rowmark publishes them for each product line, and acrylic needs slower speeds than ABS to avoid melting.
- Check that the **label is durable and permanently affixed** for the environment (NEC 110.21(B)), and that disconnect labels name the purpose and the source (110.22(A)). Confirm the edition of the NEC your jurisdiction enforces.

_Generated Schematic_:
![](/images/labels-schematic.png)