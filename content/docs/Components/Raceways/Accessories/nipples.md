---
title: Nipples
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

A conduit nipple is a short piece of raceway, threaded on both ends, used to join two closely spaced threaded enclosures, boxes, or conduit sections where a standard coupling or a full stick of conduit would be too long. Nipples are most commonly associated with **Rigid Metal Conduit (RMC)** and **Intermediate Metal Conduit (IMC)**, since both raceway types are factory-threaded (NPT) and support this style of fitting.

![](/images/nipple-example.png)

The most common nipple length is the **"close" nipple** — the shortest possible length for a given trade size, consisting of little more than the threads on each end meeting in the middle with virtually no unthreaded shoulder. **Chase nipples** are another common configuration with a flat locknut affixed to one end. Nipples are also available in longer standard lengths (e.g., 2", 3", 4", 6", up to several feet) for situations needing more separation than a close nipple but less than a full conduit stick.

**Typical uses:**

- Joining two enclosures, panels, or boxes mounted very close together (e.g., back-to-back or stacked).
- Extending a short section of threaded rigid or IMC conduit between two fittings.
- Connecting a meter socket, disconnect, or panel directly to an adjacent enclosure with minimal offset.

**Important distinctions:**

- **Nipples are not classified as "fittings" under UL 514B or NEMA FB 1.** Both standards explicitly exclude threaded conduit nipples from their scope. Nipples are instead evaluated under the same listing standards as the conduit they extend — UL 6 for RMC and UL 1242 for IMC — since a nipple is functionally a very short length of that same conduit, not an independent fitting.
- **Locknuts are required at each end.** Because a nipple has no integral hub, gasket, or insulated throat, it depends entirely on a locknut threaded onto each end (against the inside face of the enclosure wall) to secure it and maintain grounding/bonding continuity. Double-locknut construction (a locknut on both the inside and outside of thin-wall enclosures) is common practice where extra mechanical security is needed.
- **No set-screw or compression variants.** Unlike EMT connectors and couplings, nipples rely entirely on NPT male threads — there is no set-screw or compression nipple, since the raceway itself (RMC/IMC) is already factory-threaded.
- Insulated bushings are typically added separately at each termination point where conductor protection is required by the NEC, since the nipple itself has no built-in insulation.

## Further Resources

- [Wheatland – Elbows, Couplings and Nipples Are Not Fittings](https://www.wheatland.com/archives/60) — explains why nipples fall outside UL 514B/NEMA FB 1 scope and are instead listed under UL 6 (RMC) and UL 1242 (IMC).
- [Killark (Hubbell) – Rigid Conduit Nipples](https://www.hubbell.com/killark/en/products/electrical-electronic/fittings/hazardous-location/nipples/c/2146099) — manufacturer reference for rigid/IMC nipple construction, sizing, and materials.
- [McMaster-Carr – Conduit Nipples](https://www.mcmaster.com/products/conduit-nipples/) — practical sizing and length reference across trade sizes.
- Mike Holt Electrical Forum – ["chase nipples, close nipples, bond bushing"](https://forums.mikeholt.com/threads/chase-nipples-close-nipples-bond-bushing.130568/page-2) — field discussion covering locknut requirements, grounding continuity, and thread-type (NPT/NPS) compatibility considerations.
- National Electrical Code (NEC), NFPA 70 — Articles 342 (IMC) and 344 (RMC), and NEC 300.4(G) for insulated bushing/conductor protection requirements at nipple terminations.

## Naming Convention

When identifying nipples for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPE LENGTH (MATERIAL) (FINISH) (INSULATION) Nipple
```

| Descriptor     | Explanation                                                                                                                                                                              |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `SIZE`         | Trade size diameter of the nipple in inches (1/2", 2-3/4", etc.)                                                                                                                         |
| `(TYPE)`       | Optional conduit type which specifies a default material and finish.                                                                                                                     |
| `LENGTH`       | Total length of the nipple; industry shorthands include "Close", which are the smallest length standard for the size, "Chase", which are nipples with a flat locknut affixed at one end. |
| `(MATERIAL)`   | Optional material identifier (Stainless-Steel, Steel, Aluminum, etc.)                                                                                                                    |
| `(FINISH)`     | Optional finish identifier (Galvanized, Powder-Coated, Oxides, etc.)                                                                                                                     |
| `(INSULATION)` | Optional identifier for whether insulation should be present (Insulated).                                                                                                                |

### Example Names

- `1/2" RMC 12" Nipple`
- `3/4" Steel Chase Nipple`
- `4" Malleable-Iron Chase Nipple`
- `2-3/4" Stainless-Steel Close Nipple`

### Convention Notes

- Always lead with **trade size** (nominal), matching the conduit it will thread into — 1/2", 3/4", 1", 1-1/4", 1-1/2", 2", 2-1/2", 3", 3-1/2", 4", and larger.
- State **length explicitly**. Use "Close" for the shortest standard length for that trade size (the most commonly stocked option), or specify the exact length (e.g., "3 in Length," "6 in Length") for longer nipples. Do not assume "close" is the default — always confirm with the vendor, since close-nipple lengths vary by trade size (e.g., a 1/2" close nipple is roughly 1-1/2" long, while a 3/4" close nipple is roughly 1-1/8"–2" depending on manufacturer).
- Locknuts are ordered as a **separate line item** (not included with the nipple) unless a kit/assembly is explicitly specified by the vendor — confirm whether locknuts are bundled before assuming so.

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and ordering — nipples, especially in larger trade sizes or nonstandard lengths, are commonly ordered individually.|
|**Box**|Common bulk packaging for smaller trade sizes (1/2" through 1-1/4") in close lengths, typically packed **10, 25, or 50 per box**.|
|**Master Case/Carton**|Distributor/contractor bulk quantity for high-volume projects; several boxes per master case.|

## Ordering Help

- Always specify **trade size, length, and material/finish** together — these three fields fully define a nipple SKU, and omitting any one is a common source of ordering errors.
- Confirm whether **locknuts are included** with the nipple order or need to be ordered as a separate line item (typically two locknuts per nipple, one for each end).
- Close nipples are the most commonly stocked length; nonstandard lengths (cut-to-length or specialty long nipples) may carry longer lead times and should be confirmed with the vendor before finalizing a large order.

_Generated Schematic_
![Nipple Schematic](/images/nipple-schematic.png)