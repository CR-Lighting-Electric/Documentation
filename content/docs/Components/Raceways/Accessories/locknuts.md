---
title: Locknuts
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-08-31
---
## Overview

A locknut threads onto a length of threaded conduit or a threaded connector/nipple and is tightened against the inside (or outside) face of a box, cabinet, or enclosure wall, mechanically securing the raceway in place at the termination point. Locknuts are the primary means of securing threaded raceway to sheet-metal enclosures, and — depending on style — can also serve a bonding function distinct from simple mechanical securement.

Locknuts are selected based on:

1. **Function:**
    - **Standard (conduit) locknut** — a flat, notched steel or malleable iron ring that secures the raceway mechanically. It relies on direct metal-to-metal contact with the enclosure for any incidental bonding, which can be unreliable through painted, coated, or concentric/eccentric knockout surfaces.
    - **Bonding locknut** — has an integral sharp bonding tooth, screw, or serrated edge designed to bite through paint, coatings, or the layered rings of a concentric/eccentric knockout, establishing a reliable bonding path where a standard locknut's flat face cannot be depended on to do so. Commonly required per NEC 250.92(B) at concentric/eccentric knockouts.
    - **Sealing locknut** — incorporates an integral gasket (e.g., Santoprene) to provide a liquid-tight and dust-tight seal at the enclosure wall, in addition to its mechanical securing function; used in wet, washdown, or outdoor NEMA 3R/4/6/13-rated applications.
    - **Fixture locknut** — a smaller, thinner locknut sized for lighter-duty fixture stems and studs rather than conduit, typically used in luminaire and fixture mounting rather than raceway securement.
2. **Raceway/thread compatibility** — locknuts are sized to match standard NPT conduit threads and are generally shared across RMC, IMC, and threaded fittings/nipples of the same trade size; a locknut is not, by itself, raceway-type-specific the way a connector or coupling is.
3. **Material and finish:**
    - **Steel** — the standard, zinc-plated construction for general use, typically covering smaller trade sizes.
    - **Malleable iron** — used for larger trade sizes, offering greater strength than stamped steel.
    - **Aluminum** — used where a nonferrous, corrosion-resistant, and lighter-weight locknut is preferred, or to avoid dissimilar-metal contact with aluminum conduit or enclosures.
    - **Stainless steel** — used in corrosive, coastal, or washdown environments where standard zinc-plated finishes would degrade.

**Important notes worth flagging:**

- A standard locknut alone does not reliably establish bonding continuity at a concentric or eccentric knockout — where code requires positive bonding at such a knockout, a bonding locknut (or a separate bonding jumper/bushing) is required, not just an additional standard locknut.
- **Double-locknut construction** — installing one locknut on the inside and one on the outside of a thin enclosure wall — is common practice for nipples and other terminations lacking an integral hub, since a nipple has no shoulder to bear against and depends entirely on the locknuts for mechanical security (see the Nipples page).
- A sealing locknut's gasket performance depends on proper torque during installation — overtightening can distort or extrude the gasket material rather than improve the seal.

## Further Resources

- [Voltage Lab – Grounding vs. Bonding Bushings: NEC Differences Explained](https://www.voltagelab.com/grounding-vs-bonding-bushings/) — explains the related bonding-continuity concept that bonding locknuts and bonding bushings both address at knockouts.
- [ABB/Thomas & Betts – Rigid and Intermediate Metal Conduit Fittings: Locknuts Application (PDF)](https://tnb.ca.abb.com/en/pdf-catalogues/fittings-and-conduit-systems/industrial-fittings/rigid-and-intermediate-metal-conduit-fittings.pdf) — manufacturer reference covering standard, bonding, and sealing locknut construction, sizing, and material/finish suffix codes.
- [Calbrite – Stainless Steel Sealing Locknuts](https://www.atkore.com/products/conduit-and-cable-fittings/stainless-steel-sealing-locknuts) — reference on sealing locknut construction for watertight terminations in corrosive environments.
- National Electrical Code (NEC), NFPA 70 — Sections 250.92(B) (bonding at knockouts) and 300.4(G), and raceway-specific securing requirements (e.g., 344.42 and 344.46 for RMC).

## Naming Convention

When identifying locknuts for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE FUNCTION MATERIAL Locknut
```

### Example Names

- `3/4in Standard Steel Locknut`
- `1in Bonding Steel Locknut`
- `2in Sealing Steel Locknut`
- `3in Standard Malleable-Iron Locknut`
- `1/2in Standard Aluminum Locknut`
- `3/4in Sealing Stainless-Steel Locknut`

### Convention Notes

|Descriptor|Explanation|
|---|---|
|SIZE|The nominal trade size matching the conduit/thread it will secure (e.g., 1/2in, 3/4in, 1in, 2in, 3in). Leads the name, since fit is the first compatibility check.|
|FUNCTION|Standard, Bonding, Sealing, or Fixture. Standard secures mechanically only; Bonding adds a tooth/screw to bite through paint or coatings at concentric/eccentric knockouts; Sealing adds an integral gasket for wet/washdown locations; Fixture is a smaller size for luminaire stems rather than conduit.|
|MATERIAL|Steel, Malleable-Iron, Aluminum, or Stainless-Steel. Confirm compatibility with the enclosure and conduit material to avoid unwanted dissimilar-metal contact.|
|Catalog number|Vendor catalogs (e.g., Thomas & Betts, Bridgeport, Sigma, Calbrite, Cooper Crouse-Hinds) also carry their own part numbers and finish suffix codes; provide both the plain-language name and the catalog number when known.|
|UL Listing|If required by spec, append it to the name, e.g., "...UL Listed to UL 514B."|

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for pricing and small quantity orders, especially larger trade sizes and bonding/sealing locknuts.|
|**Box**|Common bulk packaging for smaller trade sizes (1/2" through 1-1/4") of standard locknuts, typically packed **50 or 100 per box**.|
|**Case**|Distributor bulk quantity, made up of multiple boxes; used for large project takeoffs.|

### Ordering Help

- Always specify **size, function, and material** together — a generic "locknut" order without these fields risks the wrong bonding performance, sealing capability, or dissimilar-metal contact for the application.
- Confirm whether a **bonding locknut is specifically required** at any concentric or eccentric knockout — a standard locknut's flat face is not a reliable substitute where code requires positive bonding continuity through such a knockout.
- For **outdoor, wet, or washdown-rated enclosures** (NEMA 3R/4/6/13), confirm a sealing locknut is specified rather than a standard locknut, and torque to the manufacturer's recommendation during installation to avoid gasket distortion.
- Order **two locknuts per termination** when securing a nipple or any raceway lacking an integral hub or shoulder (double-locknut construction), since a single locknut alone doesn't provide adequate mechanical security in that configuration.
- For **corrosive, coastal, or dissimilar-metal environments**, confirm stainless steel or aluminum construction rather than a standard zinc-plated finish before finalizing an order.