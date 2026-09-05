---
title: Adapters
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-07-08
---
## Overview

Adapters are transitional fittings used to bridge incompatible raceway types, sizes, or connection methods within a single conduit run or system interface. They are essential in commercial projects where mixed raceway systems, field modifications, or equipment entry requirements prevent direct connections.

![](/images/adapter-example.png)

**Primary Functions:**

- **Type Transition:** Convert between different raceway materials or systems (e.g., EMT to rigid steel, PVC to aluminum, flexible conduit to rigid conduit)
- **Size Reduction/Increase:** Step down or step up trade sizes to match equipment entries, panelboards, or downstream raceway runs
- **Thread/Connection Conversion:** Bridge incompatible coupling methods (e.g., NPT to FPT, compression to set-screw, threaded to unthreaded)
- **System Integration:** Interface conduit with cable trays, wireways, boxes, cabinets, or equipment enclosures

**Common Configurations:**

- **Tapered/Stepped Reducers & Increasers:** Gradual or abrupt size changes
- **Type-Change Adapters:** EMT-to-RMC, PVC-to-Steel, FMC-to-RMC, etc.
- **Box/Panel Entry Adapters:** Conduit-to-box, conduit-to-cabinet, tray-to-enclosure
- **Expansion/Thermal Adapters:** Accommodate thermal growth in long straight PVC or aluminum runs

**Code & Installation Requirements (NEC/NFPA 70):**

- **Article 300.15 & 300.16:** Raceways must enter boxes, cabinets, or fittings in a manner that protects conductors from damage
- **Article 314.27:** Strict conductor fill limits apply when adapters are used as part of an enclosed space
- **Article 250.92:** Nonmetallic-to-metallic transitions require listed bonding jumpers or integrated grounding paths
- **Article 300.18 & 300.37:** Bending space and support requirements remain in effect; adapters do not exempt runs from NEC spacing rules
- **Article 344.20 / 352.46 / 358.40:** Type-specific installation rules apply at transition points

In commercial projects, adapters reduce field labor, eliminate costly custom fabrication, maintain grounding continuity, and ensure code-compliant transitions between mixed raceway systems or equipment entries.

---

## Naming Convention

To standardize procurement, specification, and inventory tracking across commercial projects, use the following modular naming convention. This format captures transition type, sizing, material, and connection details while remaining compatible with major manufacturer catalogs.

```
FROM_SIZE(xTO_SIZE) TYPE MATERIAL (SCHEDULE) (FINISH) CONNECTION (GENDER) Adapter
```

| Descriptor   | Explanation                                                                                                    |
| ------------ | -------------------------------------------------------------------------------------------------------------- |
| `FROM_SIZE`  | Source raceway size                                                                                            |
| `(TO_SIZE)`  | Optional destination raceway size, defaults to `FROM_SIZE` if omitted.                                         |
| `TYPE`       | Type of adapter fitting, such as PVC, EMT, RMC, etc.                                                           |
| `(MATERIAL)` | Optional material specifier; classics include Stainless-Steel, Aluminum, etc.                                  |
| `(SCHEDULE)` | If `TYPE`/`MATERIAL` is PVC, optionally identify the schedule, defaults to Schedule-40.                        |
| `(FINISH)`   | Optional finish specifier which could include Galvanized, Oxide, Enamel, etc.                                  |
| `CONNECTION` | Connection type of the adapter. Common connections are threaded, but there are Set-Screw, Push-In, and others. |
| `(GENDER)`   | Gender for the ends of the adapter. Female is common, but Male is an option.                                   |

### Example Names

- `1-1/2" PVC Threaded Female Adapter`
- `3/4"x1/2" PVC Schedule-80 Threaded Female Adapter`
- `1/2" EMT Set-Screw Female Adapter`
- `2"x1-1/2" EMT Reducer Female Adapter`
---

### **Further Resources**

- **NEC/NFPA 70 (2023/2026):** Articles 300.15, 300.16, 300.18, 300.37, 314.27, 250.92, and raceway-specific articles (344, 352, 358)
- **NECA/IBEW Installation Guides:** Best practices for raceway transitions, bonding, and field modifications
- **Manufacturer Technical Bulletins:** Hubbell, Thomas & Betts, Raco, and Eaton publish detailed adapter compatibility charts, pull-force limits, and listing certificates
- **UL/ETL Listing Directories:** Verify that adapters carry appropriate agency markings for the specified transition type and environment
- **NEMA 250:** Enclosure classification standards (useful when specifying adapters for wet, corrosive, or hazardous locations)
- **IWEC Wire & Cable Installation Manual:** Practical guidance on fill calculations, bending space, and transition fitting selection