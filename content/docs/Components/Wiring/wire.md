---
title: Wire
description: Conductive metal surrounded by insulation.
function: Used to deliver power throughout buildings in the commercial electric industry.
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-05-21
---
## Overview

Conductive material that routes an electrical current to some application or device. Wire comes in a large variety of sizing in two more common and cost effective materials: copper and aluminum. Each can be insulated with different materials that have different protective properties. High voltage and low voltage wiring uses different color schemes.

![](/images/wire-example.png)

[Wire Gauge](https://wiregaugecalculator.com/blog/wire-insulation-types-guide) has an excellent reference for the common types of insulations that electrical wire can be ordered in. Unless called out for, usually all wire comes in the second generation rating. Each letter contains a characteristic:

-  **T** = Thermoplastic insulation material (as opposed to thermoset rubber insulation)
- **H** = Heat resistant (90°C or 194°F rating)
- **HH** = High heat resistant (90°C in dry locations, some applications allow higher)
- **W** = Wet location rated (suitable for use in damp or wet locations)
- **X** = Cross-linked polymer (XLPE insulation for higher performance)
- **N** = Nylon jacket over the insulation (provides mechanical and chemical protection)
- **-2** = Second generation rating with enhanced moisture and heat resistance (90°C wet)

## Further Resources

- [NFPA 70 (National Electrical Code)](https://www.cengage.com/c/electrical-wiring-commercial-19e-simmons-ode/9798214133133/?utm_source=chatgpt.com)  
    The primary code governing electrical installations in the United States. Even if you don't quote the code directly, it provides the terminology and installation requirements everything else is based on.
- [UL Solutions Wire & Cable Application Guide](https://www.ul.com/thecodeauthority/knowledge/wire-cable-guide?utm_source=chatgpt.com)  
    One of the best references available for understanding wire and cable markings, insulation types, temperature ratings, voltage ratings, direct burial, sunlight resistance, and proper applications.
- [Southwire Conduit Fill Calculator](https://www.southwire.com/calculator-conduit?utm_source=chatgpt.com)
- [Southwire Voltage Drop Calculator](https://www.southwire.com/calculator-vdrop?utm_source=chatgpt.com)
- [Southwire Ampacity Calculator](https://www.southwire.com/calculator-ampacity?utm_source=chatgpt.com)

## Naming Convention

The code specifically calls out wire sizes on AWG, and more importantly, KCMIL. Suppliers and foremen may use MCM for their sizing on wiring, but this could easily be misread and misunderstood as MC for metal clad wiring. Let's use KCMIL to keep the two distinct. A wire component can be named as such:

```
SIZE STRANDING MATERIAL INSULATION Wire (COLOR)
```

| Descriptor   | Explanation                                                                                                                                                                                                                                                                  |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | Includes the number sizing and the unit of measure, KCMIL or AWG. An example of the size portion of the convention could look like "250-KCMIL" or "1/0-AWG" or "2-AWG."                                                                                                      |
| `STRANDING`  | Refers to the strand status of wire, which includes either stranded or solid. The type portion of the convention should use its full word as a title (Stranded, Solid).                                                                                                      |
| `MATERIAL`   | Includes the type of material used in the wiring. Common types are copper or aluminum. In rare cases, silver, gold, or other conductive materials can be used. The material portion of the convention should list out the full word in title form (Aluminum, Copper, Silver) |
| `INSULATION` | Refers to the type of insulation that surrounds the wiring. Refer to the lettering of insulation in the information provided above. If the -2 is left off, assume the second modernized generation. Exaples include "THHN" or "THWN-2" or "XHHW-2."                          |
| `(COLOR)`    | Refers to the insulation color that the wiring may contain. Black is by far the most common insulation color, but in runs where multiple lines are utilized in low or high voltage settings, coloring might need to specifically be called out. Assume black if left off.    |

### Example Wiring Names

- `750-KCMIL Stranded Aluminum XHHW-2 Wire Black`
- `4-AWG Stranded Copper THWN-2 Wire Red`
- `3/0-AWG Solid Copper THHN Wire Blue`
- `1/0-AWG Solid Aluminum XHHW-2 Wire Green`
- `250-KCMIL Stranded Copper THHN-2 Wire Brown`
- `500-KCMIL Stranded Aluminum XHHW-2 Wire Black-With-White-Stripe`

## Typical Units of Measure - LF

Commercial electrical supply vendors use standardized parameters to quote and ship wire. Use this table to decode and specify orders accurately. The standard unit of measure for wire is **Linear Feet (LF)**, and can be cut/packaged according to standard lengths.

| Parameter     | Common Values                           | Description                                                           | Vendor/Ordering Context                                                              |
| ------------- | --------------------------------------- | --------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Length**    | 100', 500', 1000', 2500', 4000', Custom | Standard spool/reel lengths. Cut-to-length available on request.      | Vendors quote by full spool. Partial spools may carry minimums or restocking fees.   |
| **Packaging** | Spool, Drum, Reel, Cut-to-length        | Spools: ≤1000'. Drums/Reels: 2500'–4000'. Cut-to-length: custom runs. | Specify packaging preference. Drums require hoists/cranes; spools are hand-portable. |

> [!NOTE]
> Suppliers can also cut wire to length and wind these up on custom reels for use at the job site. These custom wire orders can use multiple conductors, grounds, and other characteristics a job site might need for their wire requirements.

## Ordering Help

When purchased in bulk, wire primarily comes in reels that depend on the wire sizing itself. Bulk wires should round up to the next largest reel size for convenience of the supplier as well.

**Generated Schematic**
![Wire Schematic](/images/wire-schematic.png)