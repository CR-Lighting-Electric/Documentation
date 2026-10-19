---
title: Circuit Breakers
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

A circuit breaker is an overcurrent protective device that opens and closes a circuit by hand and trips automatically on a set overcurrent without damage when applied within its rating. It does the job of a fuse, with a handle that can be reset instead of an element that is replaced. On commercial orders it covers the small plug-on branch breakers that fill a panelboard or load center, and the larger molded case breakers that protect feeders, motors, and equipment.

![](/images/circuit-breaker-example.png)

Scope against neighboring pages: fuses are on the Fuses page (Wiring > Accessories). This page covers the breaker itself. It does not cover the panelboard, the enclosure that houses a breaker, or the ground and neutral bars inside the panel (see the Ground Bars and Busbars pages). A breaker sold already mounted in its own enclosure is an enclosed breaker, a separate product. DIN-rail breakers appear in catalogs for control panels; confirm their listing, since a supplementary protector is not branch-circuit protection (from memory, not checked against UL 1077).

Breaker families:

- **Branch (plug-on) breakers** — small 1-pole and 2-pole breakers that snap onto the bus of a specific panelboard or load center family. Square D, for example, lists QO standard 1-pole breakers from 15 to 70A and 2-pole from 15 to 200A.
- **Molded case circuit breakers (MCCB)** — a breaker built as an integral unit in a supportive, enclosed housing of insulating material (UL 489). They are sold by frame size, the ampere label of the group, which matches the largest rating in that group, and by 2-, 3-, and 4-pole counts. They mount as bolt-on, I-Line, DIN-rail, busbar, or unit-mount.
- **Main breakers and main breaker kits** — the breaker that serves as the main disconnect, sold as its own item or as a kit.

Breaker functions:

- **Standard (thermal-magnetic)** — a fixed or adjustable thermal element for overload and a magnetic element for short circuits. It is the common trip type.
- **Electronic trip** — a trip unit with adjustable long-time, short-time, instantaneous, and ground-fault functions (LI, LSI, LSIG), usually with an interchangeable trip unit or rating plug on larger frames.
- **AFCI** — a combination arc-fault breaker for series and parallel arcing (UL 1699, NEC 210.12).
- **GFCI** — a ground-fault breaker for personnel protection (NEC 210.8). Some makers list high-frequency-rated GFCI breakers for heat pumps, EV chargers, and pool pumps.
- **Dual-function (AFCI/GFCI)** — one breaker that does both. Check that an AFCI is dual-function before assuming it provides ground-fault protection, since several combination AFCIs do not.

Ratings that the order has to name:

- **Ampere rating** — the marked rating, which must be a standard rating from NEC 240.6(A) for fixed breakers; adjustable-trip breakers take the long-time pickup setting.
- **Voltage rating** — a straight rating (such as 240V) is acceptable if the system voltage between any two conductors does not exceed it. A slash rating (such as 480Y/277V) applies the lower value conductor-to-ground and the higher value conductor-to-conductor.
- **Interrupting rating (AIC)** — the highest current at rated voltage the breaker is designed to interrupt, written in kA (for example 10kA, 25kA, 35kA, 65kA). It must be at least the available fault current at the point of installation.
- **Poles** — 1, 2, 3, or 4.

Circuit breakers are selected based on:

1. **Panel or frame** — the breaker series has to match the panelboard or load center it plugs into.
2. **Ampere rating** — matched to the conductor ampacity (NEC 240.4), such as 15A for 14 AWG copper under 240.4(D).
3. **Voltage and poles** — matched to the system and the circuit.
4. **Interrupting rating** — at least the available fault current. A breaker used where fault current exceeds its rating must be a listed series combination (NEC 240.86).
5. **Function** — Standard, AFCI, GFCI, Dual-Function, or Electronic-Trip for the circuit and the code requirement.
6. **Marking** — breakers switching fluorescent lighting are marked SWD, and those switching HID lighting are marked HID (NEC 240.83(D)).

## Further Resources

- [Electrical Engineering Portal – Definitions from the Standard UL 489 (MCCB)](https://electrical-engineering-portal.com/definitions-from-the-standard-ul-489-mccb) — reference on frame, trip unit, rated current, instantaneous and adjustable trip, interrupting rating, and current-limiting terms.
- [EC&M – NEC Requirements for Overcurrent Protection](https://www.ecmweb.com/national-electrical-code/code-basics/article/55352339/nec-requirements-for-overcurrent-protection) — reference on NEC 240.6, 240.4, 240.86, 240.83(D), 240.85, and breaker mounting rules.
- [Schneider Electric – Square D QO Circuit Breakers](https://se.com/us/qocircuitbreakers) — manufacturer reference for plug-on and plug-on neutral QO breakers, pole and ampere ranges, and AFCI, GFCI, and dual-function options.
- [Schneider Electric – QO and Homeline Breaker Compatibility FAQ](https://www.se.com/us/en/faqs/FAQ000282565/) — manufacturer FAQ on matching breakers to panel type and plug-on neutral requirements.
- [RSP Supply – Molded Case Circuit Breakers](https://rspsupply.com/c-4729-molded-case-circuit-breakers.aspx) — distributor catalog showing breaker categories, frame sizes, pole counts, interrupting ratings, and mounting types.
- National Electrical Code (NEC), NFPA 70 — Article 240 (Overcurrent Protection), including 240.4, 240.6, 240.83, 240.85, and 240.86; Article 110.9 (Interrupting Rating); 210.8 (GFCI Protection); 210.12 (AFCI Protection); and Article 408 (Panelboards).
- UL 489 — the standard for molded-case circuit breakers.
- UL 1699 — the standard for arc-fault circuit interrupters.

## Naming Convention

When identifying circuit breakers for vendor ordering, use the following naming structure, listing attributes in this order:

```
(BRAND) SERIES POLES AMPS VOLTS AIC (FUNCTION) (MOUNT) Circuit-Breaker
```

### Example Names

These examples show the pattern; confirm the series, ratings, and availability in the maker's catalog.

- `QO 1-Pole 20A 120V 10kA Standard Circuit-Breaker`
- `QO 2-Pole 50A 120/240V 10kA Standard Circuit-Breaker`
- `QO 1-Pole 20A 120V 10kA AFCI Circuit-Breaker`
- `QO 2-Pole 40A 120/240V 10kA GFCI Circuit-Breaker`
- `QO 1-Pole 20A 120V 10kA Dual-Function Circuit-Breaker`
- `150F 3-Pole 125A 480V 25kA Thermal-Magnetic Circuit-Breaker`
- `150F 3-Pole 100A 480Y/277V 35kA Thermal-Magnetic Circuit-Breaker`
- `Eaton 3-Pole 600A 600V 65kA Electronic-Trip Snap-In Circuit-Breaker`

### Convention Notes

| Descriptor   | Explanation                                                                                                                                                                                                                           |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `(BRAND)`    | Optional branding specifier for the breaker.                                                                                                                                                                                          |
| `SERIES`     | The maker's breaker series for branch breakers (for example QO, Homeline, BR, CH), or the frame designation for a molded case breaker (for example 150F); omit where only the ratings identify it. The series sets the panel it fits. |
| `POLES`      | 1-Pole, 2-Pole, 3-Pole, or 4-Pole.                                                                                                                                                                                                    |
| `AMPS`       | The ampere rating (for example 15A, 20A, 100A, 600A); a standard rating from NEC 240.6(A) for fixed breakers.                                                                                                                         |
| `VOLTS`      | The voltage rating, either straight (for example 240V, 600V) or slash (for example 120/240V, 480Y/277V).                                                                                                                              |
| `AIC`        | The interrupting rating in kA (for example 10kA, 25kA, 65kA), at the rated voltage.                                                                                                                                                   |
| `(FUNCTION)` | Standard, AFCI, GFCI, Dual-Function, Thermal-Magnetic, Electronic-Trip, or Adjustable-Magnetic. Standard is a plain thermal-magnetic branch breaker; use Thermal-Magnetic for a molded case breaker. Default to Standard.             |
| `(MOUNT)`    | Optional specific mounting mechanism for attaching the breaker into a panel; options typically include "Bolt-On", "Snap-In", "Plug-On", etc. If omitted, default to whatever the brand/series/function the breaker comes with.        |

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for a single breaker.|
|**Pack**|Multi-packs of common branch breakers; the count depends on the maker.|
|**Case**|Distributor bulk quantity for larger projects.|

### Ordering Help

- Match the **breaker to the panel first**. Square D states that QO and Homeline breakers are not interchangeable (the QOM main breakers are the exception), and the other makers' families follow the same rule. Check the panel's listing for approved breakers.
- For **plug-on neutral (PoN) breakers**, confirm the load center is plug-on neutral; Square D lists its QO load centers made after 2012 at 12 spaces and 100A and above as PoN, and older and smaller units use pigtail neutrals.
- Size the **ampere rating to the conductor** (NEC 240.4), not just to the load. Small conductors have maximums, such as 15A for 14 AWG copper.
- Check the **interrupting rating against the available fault current**. A breaker with a lower rating needs a listed series combination (NEC 240.86), and the combination is tested and marked on the end-use equipment.
- Order **AFCI, GFCI, or Dual-Function** to match the code requirements for the circuit (NEC 210.12 and 210.8), and confirm the function on the datasheet rather than the name. Some combination AFCIs have no ground-fault protection.
- Use a **slash-rated breaker only where the system fits both values**: the lower value applies conductor-to-ground and the higher value conductor-to-conductor (NEC 240.85). A straight-rated breaker is acceptable when the system voltage between any two conductors does not exceed its rating.
- Order **SWD- or HID-marked breakers** for lighting circuits that are switched at the breaker.
- Check the **lug range and terminal torque** of molded case breakers; larger frames are sold with or without lugs, and some are frame-only with a separate trip unit.
- Confirm the **edition of the NEC your jurisdiction enforces**, since section numbers and wording change between editions.

_Generated Schematic_
![](/images/circuit-breaker-schematic.png)