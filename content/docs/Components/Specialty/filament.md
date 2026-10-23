---
title: Filament
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
imported:
date: 2026-10-23
---
## Overview

3D printing filament is the thermoplastic feedstock for fused filament fabrication (FDM) printers. It is sold as a spool of round filament that the printer's hotend melts and lays down layer by layer. For electrical work the usual uses are shop-made parts such as jigs, mounting aids, brackets, cable guides, label holders, and prototypes. This page covers filament for FDM printers. It does not cover resin for resin printers, or sheet plastics for CNC cutting (see the CNC Label Materials page).

![](/images/filament-example.png)

Scope note: a printed part is not listed electrical equipment. A flame-retardant filament does not make a printed enclosure, box, or support a listed product (from memory, not checked against the NEC), so use printed parts where listed equipment is not required, and use listed products where it is.

Filament materials:

- **PLA** — very easy to print, rigid, and can be brittle. Heat resistance is low (about 50 to 60°C), and it can degrade with prolonged UV exposure. Typical print temperature is 180 to 230°C. For prototypes, jigs, and decorative parts.
- **PETG** — easy to medium to print, with good strength, some flexibility, and high chemical and moisture resistance, though it absorbs moisture itself. Heat resistance is about 70 to 80°C, and print temperature is about 210 to 235°C. For functional parts and containers.
- **ABS** — medium to difficult to print, prone to warping, and needs a heated bed and often an enclosure. Heat resistance is about 80 to 100°C, and print temperature is about 210 to 250°C. Strong and impact resistant, for functional parts, clips, and enclosures. It has a strong odor.
- **ASA** — strength similar to ABS, with better UV and weather resistance, so it is the outdoor choice. Print temperature is about 240 to 260°C, with printing difficulty similar to ABS and a strong odor.
- **Nylon** — very strong and abrasion resistant, with heat resistance of about 80 to 120°C or higher. It absorbs moisture, so it needs careful storage, and it is medium to difficult to print at about 220 to 260°C. For gears, hinges, and bearings.
- **TPU (TPE)** — flexible and rubber-like, with heat resistance of about 60 to 80°C. Medium to difficult to print, with a direct-drive extruder recommended, at about 225 to 235°C. For gaskets, seals, and flexible joints.
- **Polycarbonate (PC)** — very high strength and impact resistance, and difficult to print. It needs above 270°C at the nozzle (270 to 310°C), a bed above 100°C, and an enclosed printer.
- **PC/ABS flame-retardant** — a blend sold with a UL 94 V-0 flame rating. Spectrum PC/ABS FR V0, for example, is listed as meeting UL 94 V-0 (tested at 1.5 mm and 3.0 mm) for electrical housings, protective casings, and brackets, with a nozzle temperature of 240 to 265°C, a bed temperature of 90 to 110°C, and a heat deflection temperature of 90°C. The datasheet gives a flammability test only, and no UL listing or yellow card number.

Specialty variants such as carbon-fiber-filled, wood-filled, and PVA support filaments also exist. Check nozzle compatibility before ordering, since filled filaments wear standard nozzles (from memory, not on the sources cited).

Filament is selected based on:

1. **Material** — chosen for heat, strength, flexibility, UV exposure, and flammability.
2. **Diameter** — 1.75 mm and 2.85 mm are the common sizes, and the diameter must match the printer.
3. **Spool weight** — 1 kg is the common spool; some are smaller (for example 850 g).
4. **Color** — chosen for the part, and many materials come in black, white, and natural.
5. **Grade** — Standard, Flame-Retardant, or another filled or specialty grade.
6. **Printer capability** — nozzle and bed temperature, a heated bed, an enclosure, and a direct-drive extruder, as the material requires.

## Further Resources

- [Snapmaker – 3D Printer Filament Types](https://www.snapmaker.com/blog/3d-printer-filament-types/) — guide comparing PLA, PETG, ABS, ASA, nylon, TPU, and PC on difficulty, strength, heat resistance, UV, and typical uses.
- [CAMEO (Museum of Fine Arts, Boston) – 3D Printing Filaments](https://cameo.mfa.org/wiki/3D_printing_filaments) — reference table of print temperatures, properties, drawbacks, and common uses by filament, and the common 1.75 mm and 2.85 mm diameters.
- [Spectrum Filaments – PC/ABS FR V0](https://us.spectrumfilaments.com/collections/pc-abs-fr-v0) — manufacturer page for a UL 94 V-0 flame-retardant PC/ABS filament, with its applications, diameter, and spool weight.
- [Spectrum Filaments – PC/ABS FR V0 Technical Data Sheet](https://spectrumfilaments.com/wp-content/uploads/2024/02/en_tds_spectrum_pc_abs_fr_v0.pdf) — manufacturer data sheet with the UL 94 test thicknesses, print and bed temperatures, and heat deflection temperature.
- [DigiKey – 3D Printing Filaments](https://www.digikey.com/en/products/filter/3d-printing-filaments/944) — distributor catalog for filament by material, diameter, and color.
- UL 94 — the flammability standard for plastic materials in devices and appliances; V-0 is the rating that flame-retardant filaments claim.

## Naming Convention

When identifying 3D printing filament for vendor ordering, use the following naming structure, listing attributes in this order:

```
MATERIAL COLOR (DIAMETER-Diameter) Filament
```

### Example Names

These examples show the pattern; confirm the colors, weights, and availability on the vendor's product page.

- `PLA Black Filament`
- `PETG Black Filament`
- `ABS White Filament`
- `ASA Black Filament`
- `Nylon Natural Filament`
- `TPU Black Filament`
- `PC Black Filament`
- `PC-ABS White 2.25mm-Diameter Filament`

### Convention Notes

| Descriptor   | Explanation                                                                                |
| ------------ | ------------------------------------------------------------------------------------------ |
| `MATERIAL`   | PLA, PETG, ABS, ASA, Nylon, TPU, PC, etc. Write the blend with a hyphen.                   |
| `COLOR`      | The color name (for example Black, White, Natural). Multi-word color names are hyphenated. |
| `(DIAMETER)` | Commonly 1.75mm or 2.85mm, matched to the printer. Defaults to 1.75mm.                     |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Spool**|Standard unit, usually 1 kg (some are 850 g or other weights).|
|**Pack**|Multi-spool packs for common colors.|
|**Case**|Distributor bulk quantity for larger orders.|

### Ordering Help

- Pick the **material by the part's job**: PLA for jigs and prototypes, PETG for tougher functional parts, ASA for outdoor parts, ABS or nylon for strength and heat, TPU for gaskets and flexible parts, and Flame-Retardant for parts near electrical equipment.
- Check **what the printer can do**. ABS and ASA want a heated bed and often an enclosure, PC needs a nozzle above 270°C, a bed above 100°C and an enclosed printer, and TPU prefers a direct-drive extruder.
- Match the **diameter to the printer**; 1.75 mm and 2.85 mm filaments are not interchangeable.
- **Keep moisture-sensitive filament dry.** Nylon, PETG, and TPU absorb moisture, so store spools sealed and away from sunlight and heat.
- For **heat-exposed parts**, compare the material's heat resistance to the service temperature; PLA softens at about 50 to 60°C, so it is a poor choice near warm equipment or in a hot vehicle or enclosure.
- For **outdoor parts**, choose ASA over PLA or ABS because of its UV and weather resistance.
- Order a **flame-retardant grade with a documented UL 94 rating**, and read the test thickness. The rating applies at the tested thicknesses, and a printed part is not a listed product.
- Provide **ventilation** when printing ABS and ASA, which have a strong odor, and check the safety data sheet for fumes, especially for PC blends.
- Keep a **spare spool of the common materials and colors** on hand so a long print is not stopped by an empty spool.

_Generated Schematic_
![](/images/filament-schematic.png)