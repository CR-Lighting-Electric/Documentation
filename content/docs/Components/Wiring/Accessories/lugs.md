---
title: Wire Lugs
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

A wire lug (also called a compression lug or terminal lug) terminates a conductor to a bolt, stud, or bus bar — used for connections to panel-boards, switchgear, transformers, grounding systems, and equipment terminals where a screw-type terminal block isn't the connection point. Lugs are distinct from the ring/spade/quick-disconnect terminals documented on the Terminals page: lugs are sized for larger power conductors (typically 8 AWG and up through large KCMIL sizes) and are almost always installed with a dedicated compression or mechanical tool rather than a simple hand crimper.

![](/images/wire-lug-example.png)

Wire lugs are selected based on:

1. **Installation method:**
    - **Compression lug** — a seamless copper (or aluminum) barrel permanently crimped onto the conductor using a hydraulic or mechanical compression tool and a matched die, creating a gas-tight connection that resists oxidation over the life of the installation.
    - **Mechanical (set-screw) lug** — secures the conductor with one or more set screws rather than a crimp, requiring no special tooling; reusable and adjustable, but generally not preferred for permanent, high-vibration, or code-critical terminations where a compression lug would be specified.
2. **Barrel length:**
    - **Short (standard) barrel** — used for standard applications and confined spaces.
    - **Long barrel** — provides greater contact surface area for heavy-duty industrial applications, improving pull-out strength and reducing resistance.
3. **Hole count:**
    - **One-hole lug** — standard for most general-purpose terminations, including residential panel connections and grounding.
    - **Two-hole lug** — used at larger conductor sizes (typically 1/0 AWG and above), in high-vibration environments (switchgear, transformers, marine, motor control centers), or where local code requires an anti-rotation termination, since a single-bolt connection can rotate under load or vibration.
4. **Material:**
    - **Copper** — electro-tin-plated wrought or seamless copper is the standard construction, providing corrosion resistance and stable, low contact resistance.
    - **Aluminum / dual-rated (AL9CU)** — tin-plated aluminum-body lugs rated for connection to either aluminum or copper conductors; an oxide-inhibitor (antioxidant) paste must be applied to the conductor before insertion when terminating aluminum.
5. **Stud/bolt hole size** — common sizes are 1/4", 5/16", 3/8", 1/2", and 5/8"; this must match the actual bolt or stud at the termination point, since an oversized hole on an undersized bolt significantly reduces usable contact surface area.

**Two identification systems matter for ordering and installation, and they are not the same thing:**

- **Color code** — most manufacturers follow an industry-standard color-keyed system linking barrel color to AWG/kcmil size (e.g., red for 8 AWG, blue for 6 AWG, gray for 4 AWG), intended to let an installer visually match a lug to its corresponding crimp die. This convention is widely shared across major manufacturers but is not a mandatory standard — the printed wire range on the lug always governs, not color alone.
- **Die index** — a number laser-etched or embossed directly on the lug barrel identifying the specific crimping die required to properly compress it. The die index must match the compression tool's die set exactly; using the wrong die — even one rated for the same nominal wire gauge — can result in an under- or over-compressed, non-code-compliant crimp.

**Installation notes worth flagging:**

- UL 486A/B sets minimum pull-out force requirements for a properly crimped compression lug, ranging from roughly 90 lbs for 8 AWG up to nearly 2,000 lbs for 750 kcmil — a correctly matched die and full crimp cycle are what achieve this rating, not the lug alone.
- Most lugs include a sight window (peephole) to visually confirm the conductor is fully seated in the barrel before crimping; where no window is present, mark the conductor at the barrel entrance before insertion.
- Fine-strand (Class K) conductors, such as welding cable or DLO, generally require a specialized flexible-conductor-rated lug rather than a standard-strand lug, even at the same nominal AWG.

## Further Resources

- [UL 486A-486B – Wire Connectors](https://www.shopulstandards.com/ProductDetail.aspx?productId=UL486A-486B_4_S_20250314) — the primary UL safety standard covering lug construction, current rating, and minimum pull-out force testing.
- [ABB – Color-Keyed Compression Lugs](https://electrification.us.abb.com/products/connectivity-grounding/color-keyed-compression-lugs) — manufacturer reference on the industry-standard color-coded lug and die system.
- [Penn Union – Compression Lugs](https://www.penn-union.com/products/compression/compression-lugs/) — manufacturer catalog with sizing, color code, and die code cross-reference tables by AWG/kcmil.
- [Conversions Tech – Compression Lug Sizing Guide: AWG to Stud Size Chart](https://conversionstech.com/blogs/do-you-need-8k-hdmi-cable/compression-lug-sizing-guide-awg-to-stud-size-chart-2026) — practical sizing reference covering barrel size, stud size, die index, and one-hole vs. two-hole selection.
- National Electrical Code (NEC), NFPA 70 — Article 110.14 (Electrical Connections) and Article 250 (Grounding and Bonding) — governing connector listing, conductor material identification, and grounding-conductor termination requirements.

## Naming Convention

When identifying wire lugs for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE HOLE-SIZE CONDUCTORS (BARREL) (MATERIAL) HOLES Lug
```

| Descriptor   | Explanation                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------- |
| `SIZE`       | Wiring size for the lug connection in AWG or KCMIL (3-AWG, 250-KCMIL, etc.)                                      |
| `CONDUCTORS` | The conductor material(s) the lug is rated for; Copper, Aluminum, etc.                                           |
| `(BARREL)`   | Optional barrel length for lug, can be specified as Short-Barrel or Long-Barrel. Assume Short-Barrel as default. |
| `TYPE`       | Type of the lug, common configurations include Compression or Mechanical.                                        |
| `STUD-SIZE`  | The size of the hold for the bolt/hardware to secure the lug with, 1/2"-Stud i.e.                                |
| `(MATERIAL)` | Optional material specifier for the lug itself, assume Aluminum as default.                                      |

### Example Names

- `250-KCMIL Copper Long-Barrel Compression 1/2"-Stud Aluminum 2-Hole Lug`
- `4-AWG Aluminum Compression 1/8"-Stud 1-Hole Lug`
- `350-KCMIL Copper-Aluminum Short-Barrel Mechanical 3/4"-Stud Aluminum 1-Hole Lug`

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for larger lugs (1/0 AWG and up) and two-hole/long-barrel styles, which are typically ordered in the exact quantity needed.|
|**Box**|Common bulk packaging for smaller, high-volume lug sizes (8 AWG through 2/0 AWG), typically packed **25 or 50 per box**.|
|**Bag**|Occasional packaging for small one-hole compression lugs at high volume.|
|**Case**|Distributor bulk quantity, made up of multiple boxes; used for large project takeoffs.|

### Ordering Help

- Always specify **style, hole count, barrel length, metal, conductor size, and stud size** together — a lug order missing any one of these fields risks arriving with the wrong die rating, wrong bolt fit, or incompatible conductor material.
- Confirm the **die index number** required for compression lugs against the crimping tool actually available on site — the correct AWG match alone does not guarantee die compatibility across manufacturers.
- For **aluminum conductor terminations**, order oxide-inhibitor (antioxidant) paste as a separate line item if not already on hand — this is required for a proper aluminum crimp and is not included with the lug.
- Confirm **two-hole spacing** (standard 1-3/4" vs. narrow 1" centers) against the equipment's mounting pattern before ordering, particularly for switchgear, transformer, or marine applications.
- Verify the lug's **voltage and temperature rating** (commonly 600V or 35kV, 90°C) is adequate for the application, and confirm UL Listing where required by spec.

_Generated Schematic_
![](/images/wire-lug-schematic.png)