---
title: Ceiling Boxes
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

A ceiling box is a round or octagonal outlet box mounted to overhead framing to support a light fixture or ceiling fan and house its connections — distinct from the Square Boxes already covered in this subcategory, which are typically wall-mounted and device-oriented. The critical distinction within this page itself is **fixture-only support vs. fan support**: a box rated only for a static light fixture is not automatically safe for a ceiling fan, and per NEC 314.27(C), a box used as the sole support for a ceiling-suspended paddle fan must be specifically listed for fan support — the constant vibration and torque of a rotating fan will fatigue and eventually fail a standard fixture box not built or rated for that dynamic load.

![](/images/ceiling-box-example.png)

Ceiling box types:

- **Octagon box** — the standard shape for ceiling-mounted fixtures and fans, typically 4" across; available in both fixture-only and fan-rated versions.
- **Round box** — similar function to an octagon box, round profile; also available in fixture-only and fan-rated versions.
- **Pancake box** — a shallow box (roughly 1/2" deep) used where a ceiling joist sits directly above the fixture/fan location, mounted flush to the joist face; standard pancake boxes are fixture-only, and a fan-rated pancake box specifically must be heavy-gauge steel, UL-listed and labeled for fan support, and lag-screwed directly into the joist.
- **Fan-rated box** — not a separate shape but a construction/listing distinction applying to octagon, round, or pancake boxes: reinforced construction, internal markings stating maximum supported weight (up to 70 lb on listed models; boxes supporting over 35 lb require the weight rating marked inside), and a UL listing specifically covering dynamic fan loads, not just static weight.

Ceiling boxes are also distinguished by mounting method:

- **New-work** — a bracket-mounted box attached directly to an exposed joist before drywall/ceiling finish is installed; the most secure mounting method, used wherever framing is accessible during rough-in.
- **Old-work/retrofit (brace bar)** — an adjustable brace bar that expands between two joists and is accessed/installed through the ceiling cutout itself, used where the fixture or fan location doesn't land under a joist and the ceiling is already finished; brace-bar kits rated for fan support carry the same listing requirement as the box itself.
- **Direct-to-joist (pancake)** — mounted flush to the underside of a joist that happens to fall at the fixture/fan location, used in both new-work and retrofit settings.

Ceiling boxes are selected based on:

1. **Support rating** — Fixture-Only for lights and other static loads, or Fan-Rated (with the specific weight capacity marked, e.g., 35lb or 70lb) wherever a ceiling fan will be the box's sole means of support; never substitute a fixture-only box for fan support regardless of the fan's actual weight.
2. **Shape/depth** — Octagon or Round for standard ceiling locations with box-fill volume to spare; Pancake where joist clearance above the ceiling is limited and a shallow box is needed to clear the joist.
3. **Mounting method** — New-Work bracket where framing is accessible during rough-in; Brace-Bar for retrofit/remodel work through an existing finished ceiling; Direct-to-Joist where a joist falls directly at the box location.
4. **Box-fill volume** — sized per NEC 314.16 for the conductor count, splices, and any fixture/fan wiring devices (e.g., a fan's internal switch wiring) that will be housed inside; pancake boxes in particular have limited interior volume and should be checked for adequate fill capacity before selection.
5. **Material** — Steel (standard, required for most fan-rated listings) or PVC/nonmetallic (lighter-duty fixture-only applications).

## Further Resources

- [Relight Depot – Ceiling Fan Box: Fan-Rated Support Boxes](https://relightdepot.com/electrical/boxes-and-fittings/ceiling-fan-support-boxes/) — reference on UL listing/weight rating requirements per NEC 314.27(C), fixture vs. fan-rated box construction, pancake box retrofit use, and new-work/brace-bar/pancake mounting styles.
- [EngineerSkill.blog – Can You Use a Pancake Electrical Box for a Ceiling Fan?](https://engineerskill.blog/can-you-use-pancake-box-for-ceiling-fan) — reference distinguishing standard vs. fan-rated pancake box construction and direct-to-joist mounting requirements.
- National Electrical Code (NEC), NFPA 70 — Article 314.27(C) (Boxes at Ceiling-Suspended (Paddle) Fan Outlets, requiring a box listed for fan support), and Article 314.16 (Number of Conductors in Outlet, Device, and Junction Boxes) for box-fill sizing.
- UL 514A — the governing listing standard for metallic outlet boxes, including fan-support rated construction.

## Naming Convention

When identifying ceiling boxes for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE SHAPE ADJUSTABILITY SUPPORT MOUNT (DEPTH-Depth) (KNOCKOUTS-KO) (DROPDOWN) Ceiling-Box
```

### Example Names

- `4" Octagon Fixture-Only New-Work 1-1/2"-Depth Ceiling-Box`
- `4" Octagon Adjustable Fan-Rated-70lb New-Work 2-1/8"-Depth Ceiling-Box`
- `3-1/2" Round Fan-Rated-70lb Brace-Bar 2-1/8"-Depth Ceiling-Box`
- `3-3/8" Pancake Fixture-Only Direct-to-Joist Ceiling-Box`
- `4" Pancake Fan-Rated-35lb Direct-to-Joist 1/2"-Depth Ceiling-Box`
- `4" Octagon Fixture-Only Adjustable Brace-Bar 1-1/2"-Depth 8"-Dropdown Ceiling-Box`

### Convention Notes

| Descriptor      | Explanation                                                                                                                                                                                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `SIZE`          | Diameter or width of the ceiling box itself. Typically come in default sizes for the different shapes, but should be specified for .                                                                                                                         |
| `SHAPE`         | Octagon (standard 4" ceiling box), Round, or Pancake (shallow, ~1/2in, direct-to-joist).                                                                                                                                                                     |
| `SUPPORT`       | Fixture-Only (static light fixture loads only) or Fan-Rated-35lb / Fan-Rated-70lb (UL-listed per NEC 314.27(C) for ceiling fan support, with the specific weight capacity marked inside the box); never substitute Fixture-Only where fan support is needed. |
| `ADJUSTABILITY` | Wether the box and bracket system is adjustable to fit varying length. Options include Adjustable or Non-Adjustable.                                                                                                                                         |
| `MOUNT`         | New-Work (bracket mounted to exposed joist before ceiling finish), Brace-Bar (adjustable bar expanding between joists for retrofit/remodel work), or Direct-to-Joist (box mounted flush to a joist directly above the location, typical of pancake boxes).   |
| `(DEPTH)`       | The box's depth (e.g., 0.5in for pancake, 1.5in-2.125in for standard octagon/round), checked against box-fill volume needs per NEC 314.16 for the conductors and devices to be housed.                                                                       |
| `(KNOCKOUTS)`   | Sizes of any optional knockouts that are present on the box itself.                                                                                                                                                                                          |
| `(DROPDOWN)`    | Optional drop-down amount with a bar attached to the bracket.                                                                                                                                                                                                |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for individual ceiling boxes.|
|**Case**|Distributor bulk quantity for common sizes on larger residential/commercial lighting or fan installs.|

### Ordering Help

- Never install a **Fixture-Only box as sole support for a ceiling fan**, regardless of the fan's weight — NEC 314.27(C) requires a box specifically listed for fan support, and a standard fixture box will fatigue and fail under the dynamic rotating/torque load a fan applies that a static fixture never does.
- Confirm the **marked weight capacity inside a fan-rated box** (up to 70 lb on listed models) against the actual installed weight of the fan, including any light kit attached to it — not just the fan motor housing alone.
- Choose **Brace-Bar mounting for retrofit/remodel work** where the fixture or fan location doesn't land under an existing joist and the ceiling is already finished — this avoids opening up the ceiling further than the fixture cutout itself.
- Use a **fan-rated Pancake box only where it's specifically labeled for fan support and lag-screwed directly into a joist** — an unrated pancake box, even one that physically fits, is not an acceptable substitute at a fan location.
- Check **box-fill volume against actual conductor and device count** before finalizing size, especially for pancake boxes, whose shallow depth limits interior volume more than a standard octagon or round box of the same diameter.

![](/images/ceiling-box-schematic.png)