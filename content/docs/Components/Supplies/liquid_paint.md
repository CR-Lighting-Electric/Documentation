---
title: Liquid Paint
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-10-01
---
## Overview

Liquid paint here refers to brush-, roller-, or dauber-applied paint sold in bottles, pints, quarts, and gallons — distinct from the Paint Cans page (aerosol spray) and the Paint Markers page (pen-style precision marking). It's named separately (rather than folded into Paint Cans) because it's ordered, stocked, and selected differently: liquid paint is the better choice for larger-area coating, bulk stock that gets decanted or brushed on as needed, and small built-in-brush touch-up bottles used for precise spot repairs where overspray from an aerosol can would be a problem (inside an open panel, near energized equipment, or in a tight enclosure).

![](/images/liquid-paint-example.png)

Liquid paint types mirror the same functional categories as aerosol paint:

- **Enamel (general-purpose)** — durable gloss or semi-gloss finish for general metal coating, brushed or rolled on; used where a larger area needs coating than a spray can covers efficiently, or where overspray must be avoided.
- **Rust-inhibitive/primer** — bonds to bare or lightly rusted steel and inhibits further corrosion; applied as a base coat before a finish coat, commonly by brush on fabricated steel, strut, and support hardware in the shop or field.
- **Equipment touch-up (color-matched)** — color-matched to a manufacturer's enclosure finish, most commonly **ANSI 61 gray**; frequently sold as a small brush-in-cap touch-up bottle (similar to a nail-polish-style applicator) specifically for spot repairs on panelboards, switchgear, and enclosures without the overspray risk of an aerosol can near open or energized equipment.
- **Safety/identification color** — liquid paint in standardized colors for hazard/status marking per OSHA 29 CFR 1910.144 and ANSI Z535.1 color conventions, brushed or rolled on larger areas (machine guards, barriers, equipment bases) where an aerosol can would be inefficient to cover the surface.

Liquid paint is selected based on:

1. **Type** — Enamel for general-purpose coating, Rust-Inhibitive/primer for bare or corroding steel, Equipment-Touch-Up where a specific factory finish needs matching, or Safety-Color for hazard/status marking.
2. **Color** — matched to the equipment manufacturer's finish for touch-up (ANSI 61 gray is standard for electrical equipment) or to the OSHA/ANSI safety color code for hazard marking.
3. **Container/application style** — a small brush-cap touch-up bottle for precise spot repairs near sensitive or energized equipment; a pint or quart for shop-scale brushed/rolled coating; a gallon for larger-area coverage.
4. **Finish** — Gloss (standard for most enclosure/equipment finishes), Satin, or Flat, matched to the surface being coated so the repair or coating doesn't stand out.
5. **Application method** — Brush-On for controlled spot repairs and detail work, Roll-On for efficient coverage of larger flat areas.

## Further Resources

- [Rust-Oleum – Industrial Choice Enamel Spray Paint, ANSI 61 Light Gray](https://www.amazon.com/Rust-Oleum-214645-General-Purpose-Container/dp/B00M0NTH90) — reference manufacturer also offering brush-grade liquid paint in the same ANSI 61 gray color line for enclosure touch-up.
- [LH Dottie – Rust Proof Paint, Light Gray ANSI-61 (Solvent-Based)](https://lhdottie.com/rust-proof-paint-solvent-based/361) — reference for rust-inhibitive ANSI 61 gray paint commonly carried in both aerosol and brush-applied liquid form by electrical distributors.
- [Hoffman – ATPPY61 Touch-Up Paint, ANSI 61 Polyprim](https://www.amazon.com/Hoffman-ATPPY61-Touch-Up-Paint-Polyprim/dp/B008KMFOMO) — manufacturer-matched touch-up paint line, commonly available as both a spray can and a small brush-cap touch-up bottle.
- [OSHA 29 CFR 1910.144 – Safety Color Code for Marking Physical Hazards](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.144) — the governing federal regulation defining Red (fire protection/danger/stop) and Yellow (caution/physical hazards) safety color meanings.
- ANSI Z535.1 — the broader industry standard extending the safety color convention to Orange, Green, Blue, and Purple.

## Naming Convention

When identifying liquid paint for vendor ordering, use the following naming structure, listing attributes in this order:

```
TYPE FINISH COLOR Liquid-Paint
```

### Example Names

- `Equipment-Touch-Up Gloss ANSI-61-Gray Liquid-Paint`
- `Enamel Gloss Black Liquid-Paint`
- `Rust-Inhibitive Flat Red-Oxide-Primer Liquid-Paint`
- `Safety-Color Gloss OSHA-Safety-Red Liquid-Paint`
- `Safety-Color Gloss OSHA-Safety-Yellow Liquid-Paint`
- `Enamel Satin White Liquid-Paint`

### Convention Notes

|Descriptor|Explanation|
|---|---|
|TYPE|Enamel (general-purpose coating), Rust-Inhibitive (bare/corroding steel, primer), Equipment-Touch-Up (color-matched to a manufacturer's finish), or Safety-Color (hazard/status marking per OSHA/ANSI color code).|
|FINISH|Gloss (standard for most enclosure/equipment finishes), Satin, or Flat, matched to the surface being coated.|
|COLOR|ANSI-61-Gray (standard electrical enclosure/switchgear finish) or another manufacturer-matched color; Red-Oxide-Primer for rust-inhibitive base coat; OSHA-Safety-Red, OSHA-Safety-Yellow, or the broader ANSI Z535.1 Orange, Green, Blue, and Purple for safety-color marking; standard colors (Black, White) for general-purpose work.|
|SIZE|The container size/style: 2oz-Brush-Bottle (built-in brush applicator for precise spot touch-up), Pint, Quart, or Gallon, matched to the coverage area and application method.|
|Catalog number|Vendor catalogs (e.g., Rust-Oleum, Hoffman, LH Dottie) also carry their own part numbers; provide both the plain-language name and the catalog number when known, since exact color match is manufacturer- and product-line-specific for equipment touch-up paint.|

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for touch-up bottles, pints, quarts, and gallons alike.|
|**Case**|Distributor bulk packaging for shop stock of common touch-up colors (e.g., ANSI 61 gray) or safety colors.|

### Ordering Help

- Use a **small brush-cap touch-up bottle rather than an aerosol can** for spot repairs inside an open panel, near energized equipment, or in any tight enclosure where overspray or airborne aerosol could reach live parts, other equipment, or nearby surfaces.
- For **larger-area coating or priming** (fabricated steel, strut, support hardware, equipment bases), a brushed or rolled quart/gallon is generally more economical and controllable than multiple aerosol cans.
- Match **color and manufacturer the same way as aerosol touch-up** — ANSI 61 gray is near-universal for electrical equipment, but exact shade can vary slightly between manufacturers.
- Keep **safety-color liquid paint stocked separately** from general touch-up colors, consistent with the aerosol Paint Cans page — Red and Yellow in particular carry specific OSHA 1910.144 meanings (fire protection/danger/stop, and caution/physical hazards) that shouldn't be diluted by interchangeable general-purpose use.
- Confirm **cure/dry time before re-energizing or closing up equipment** touched up with liquid paint — brushed paint in an enclosure may need longer to fully dry than a comparable aerosol touch-up, depending on film thickness applied.

![](/images/liquid-paint-schematic.png)