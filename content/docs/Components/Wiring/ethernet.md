---
title: Ethernet
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-07-10
---
## Overview

Ethernet cable is twisted-pair copper cabling used to carry data signals between network equipment — switches, patch panels, wall jacks, and end devices. It is the standard medium for structured cabling in commercial and light industrial buildings, governed primarily by the ANSI/TIA-568 series of standards for performance and NFPA 70 (NEC) Article 800 for installation and fire-rating requirements.

![](/images/ethernet-cable.png)

Ethernet cable is selected based on:

1. **Category (performance rating)** — determines maximum supported bandwidth and cable distance:
    - **Cat5e** — up to 1 Gbps, largely legacy at this point but still specified for low-bandwidth applications.
    - **Cat6** — up to 1 Gbps reliably over 100 m, and 10 Gbps over shorter distances (typically under 55 m).
    - **Cat6A** — full 10 Gbps over 100 m; the current standard specification for new commercial installations.
    - **Cat7 / Cat8** — higher-bandwidth, shielded-only cabling used in data centers and high-density switch-to-switch runs rather than general horizontal cabling.
2. **Shielding construction** — protects against electromagnetic interference (EMI):
    - **UTP (Unshielded Twisted Pair)** — standard for typical office, school, and retail environments.
    - **STP / FTP / S/FTP (Shielded / Foiled Twisted Pair)** — adds a foil or braided shield around the pairs or the whole cable core; used near motors, power lines, elevator equipment, or other high-EMI environments, and required for most Cat7/Cat8 installations. <cite index="4-1">Shielded construction protects the signal from outside EMI and also keeps the signal from emitting its own EMI — for example, in a hospital where many electronic devices emit EMI.</cite>
3. **Conductor type** — <cite index="4-1">solid conductors are generally used for in-wall, permanent horizontal wiring where flexibility isn't needed, while stranded conductors are more flexible and typically used for shorter patch cables and cross-connects</cite>.
4. **Jacket fire rating** — governs where the cable may legally be installed, and is entirely independent of the category rating. <cite index="2-1">Cat5e, Cat6, Cat6A, and Cat8 are network performance categories, while CMP, CMR, CM, and CMX describe where the jacket is rated to be installed</cite>. The common ratings, from most to least restrictive:
    - **CMP (Plenum)** — <cite index="9-1">can be installed in any space, including plenum spaces, and is made with fire- and smoke-resistant materials like FR-PVC or FEP.</cite>
    - **CMR (Riser)** — <cite index="10-1">can be used in the risers of commercial buildings and installed anywhere except plenum spaces.</cite>
    - **CM / CMG (General Purpose)** — <cite index="9-1">suitable for ordinary indoor communications use but not for plenum or riser applications requiring a higher rating.</cite>
    - **CMX (Limited Use / Outdoor)** — <cite index="1-1">the lowest fire rating, restricted almost entirely to outdoor or residential applications.</cite>
    - **Outdoor / Direct Burial** — uses a UV- and moisture-resistant jacket (often with a water-blocking gel or tape) for underground or exterior exposed runs; not fire-rated for indoor use.

> [!NOTE]
> A complete cable specification is never chosen from a single label alone — it names the category, the jacket rating, the shielding construction, the conductor type, an outdoor/direct-burial rating if applicable, and the jacket color and packaging format together</cite>, since any of these can vary independently on an otherwise identical-looking reel.

## Further Resources

- [TIA – ANSI/TIA-568 Structured Cabling Standards](https://tiaonline.org/products-solutions/standards/) — the governing performance standard for Ethernet cable categories (Cat5e through Cat8).
- [trueCABLE – Facts About Ethernet Cable Jacket Ratings](https://www.truecable.com/blogs/cable-academy/facts-about-ethernet-cable-jacket-ratings) — detailed breakdown of CMP, CMR, CM, and CMX ratings and where each is legally permitted.
- [UL 444 – Standard for Communications Cables](https://www.shopulstandards.com/ProductDetail.aspx?UniqueKey=32530) — the UL safety standard that defines and tests CM/CMR/CMP fire-rating classifications.
- National Electrical Code (NEC), NFPA 70 — Article 800 (Communications Circuits) — governing installation, listing, and permitted uses for communications cable, including plenum and riser requirements.
- [BICSI](https://www.bicsi.org/) — the professional association publishing the _Telecommunications Distribution Methods Manual (TDMM)_, a common commercial cabling design and installation reference.

## Naming Convention

When identifying Ethernet cable for vendor ordering, use the following naming structure, listing attributes in this order:

```
TYPE (SHIELD) (STRANDING) (SIZE) (JACKET) Ethernet-Cable (COLOR)
```

| Descriptor    | Explanation                                                                                                                                          |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| `TYPE`        | Standard designation of the cable: Cat5e, Cat6, Cat6A, etc.                                                                                          |
| `SHIELD`      | Optionally specify Whether the cable is shielded or not; use "Shielded" if it is, otherwise use "Unshielded."                                        |
| `(STRANDING)` | Optionally specify whether the conductor is Stranded or Solid, default Solid.                                                                        |
| `(SIZE)`      | Optionally specify the size of the conductors within the ethernet cable.                                                                             |
| `(JACKET)`    | Optionally Identify the jacket rating for the ethernet, "Plenum-Rated" or "Riser-Rated." If omitted, assume the jacket is general and has no rating. |
| `(COLOR)`     | Optional identifier for the color of the ethernet jacket.                                                                                            |

### Example Names

- `Cat5e Shielded Ethernet-Cable`
- `Cat6A Unshielded Ethernet-Cable`
- `Cat6 Plenum-Rated Ethernet-Cable`
- `Cat5 Shielded Stranded 18-AWG Riser-Rated Ethernet-Cable`
- `Cat8 Unshielded Ethernet-Cable`

## Typical Units of Measure

| Unit                         | Typical Use                                                                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Foot/Linear Foot (FT/LF)** | Base unit for pricing and takeoff quantities — most cable estimating and material lists are built in linear feet regardless of packaging format.             |
| **Box/Pull Box (EA)**        | Standard bulk packaging, most commonly **1000 ft** per box, dispensed from an internal coil through a pull-out hole.                                         |
| **Reel/Spool (EA)**          | Larger bulk quantities (typically 1000 ft, 2500 ft, or 5000 ft) wound on a reel, common for large commercial projects ordering well above a single pull box. |

### Ordering Help

- Always confirm **type, shielding, and jacket rating together** — a quote for just "Cat6 cable" is incomplete and risks a rating or construction mismatch on delivery.
- Order in full **box or reel quantities** where possible; breaking a box for a partial length often carries a cut charge or per-foot premium from distributors.
- Confirm the **jacket rating matches the installation space** (plenum vs. riser vs. general purpose vs. outdoor) before ordering — this is a code compliance issue, not just a preference, and the wrong rating can fail inspection.

_Generated Schematic_
![Ethernet Schematic](/images/ethernet-schematic.png)