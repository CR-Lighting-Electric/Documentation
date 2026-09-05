---
title: Stub Downs
description:
function:
type: docs
obstype: component
related:
next:
prev:
sidebar:
open: true
date: 2026-08-14
---
## Overview

A stub down (also called a stub up, depending on the direction of transition) is a length of raceway — either a factory elbow/riser assembly or a straight conduit run terminating in a 90° bend — used to transition a raceway from below a concrete slab, underground run, or duct bank up through the slab to an exposed connection point, or from an exposed run down into a slab or underground routing. The terms are directional descriptions of the same basic installation practice, not different products: a "stub up" rises out of the slab toward equipment above; a "stub down" drops from an exposed run into the slab or ground below.

![Stub Down Example](/images/stub-down-example.png)

Stub downs are selected based on:

1. **Material:**
    - **PVC (Schedule 40 or Schedule 80)** — <cite index="13-1">acceptable for coming up through a slab with no NEC requirement to use RMC or IMC, though where the PVC will be exposed to physical damage it must be identified for that use (Schedule 80)</cite>.
    - **Rigid Metal Conduit (RMC/RGS)** — commonly specified for the exposed portion of a stub-up specifically for physical protection, since <cite index="15-1">rigid stub ups protect the conduit from damage both after construction and during construction, when stub-ups are frequently broken off by other trades on a job site</cite>.
    - **PVC-coated rigid steel** — <cite index="16-1">specified for stub-ups in corrosive or wet environments (e.g., lift stations, industrial sites), often called out specifically as "PVC coated rigid steel elbows" in engineering specifications</cite>, combining the physical strength of steel with a corrosion-resistant coating.
    - Many project specifications require rigid or PVC-coated rigid conduit for stub-ups even where the NEC itself does not mandate it — always check the governing spec before defaulting to PVC.
2. **Configuration:**
    - **Factory 90° elbow + riser** — a pre-bent factory elbow transitions from horizontal (underground/under-slab) to vertical, with a straight riser section extending up (or down) to the termination point.
    - **Field-bent riser** — a field bender is used to create the 90° transition directly in a single continuous length of conduit, avoiding a separate elbow/coupling joint.
    - **Concrete-tight stub-down fitting** — a specialized fitting (often used with ENT) designed to be cast directly into the slab, providing a factory-sealed, code-compliant transition without solvent welding or taping at the penetration point.
3. **Length above/below finished grade or slab** — <cite index="11-1">the NEC limits the length of an exposed stub-up to approximately 24 inches (600 mm) above the concrete, to minimize the leverage exerted on the connection point and prevent stress that could crack the concrete or damage the fitting</cite>.

**Installation notes worth flagging:**

- <cite index="11-1">PVC conduit is lighter than concrete and will float during a pour if not adequately secured — the run must be firmly tied to rebar with tie wire at regular intervals, and conduit spacers or templates are commonly used to maintain separation and vertical alignment where multiple stub-ups occur in a group</cite>.
- <cite index="11-1">Installers commonly add a temporary nipple or coupling at the stub-up point during the pour, extending it high enough to remain visible and plumb, to allow for minor alignment adjustments before the final connection is made</cite>.
- <cite index="12-1">Support requirements for the exposed portion follow standard NEC conduit support spacing (e.g., within 3 ft of a box, up to 5 ft elsewhere if no structural member is available to tie into) — a stub-up more than a few feet from its termination point may need intermediate support, such as strut, before the final connection</cite>.
- Confirm whether the governing project specification requires rigid or PVC-coated rigid conduit specifically for the stub — this is frequently an engineering/spec requirement above and beyond the NEC minimum, particularly in industrial, wet, or vehicle-traffic-adjacent areas.

## Further Resources

- [Engineer Fix – How to Properly Install a Conduit Stub Up](https://engineerfix.com/how-to-properly-install-a-conduit-stub-up/) — practical installation guide covering material selection, securing to rebar, and NEC exposed-length limits.
- [Steel Tube Institute – Guidelines for Installing Steel Conduit / Tubing (PDF)](https://steeltubeinstitute.org/wp-content/uploads/2021/01/Steel-Conduit-Installation-Guide.pdf) — covers steel conduit installed in concrete and PVC-coated conduit installation practices.
- [Mike Holt Forum – NEC Stub-Up for Concrete Slab](https://forums.mikeholt.com/threads/nec-stub-up-for-concrete-slab.50021/) — field discussion on PVC vs. rigid requirements and the applicable NEC articles.
- [City of Galveston – Conduit, Fittings, and Bodies Specification (PDF)](https://www.galvestontx.gov/DocumentCenter/View/1657/16111---Conduit-Fittings-and-Bodies) — example municipal specification requiring PVC-coated rigid steel elbows for stub-ups in wet/corrosive locations.
- National Electrical Code (NEC), NFPA 70 — Article 300.5 (underground burial depth), Article 344 (RMC) and Article 352 (PVC) installation requirements, and the 24-inch exposed stub-up guidance referenced above.

## Naming Convention

When identifying stub downs for vendor ordering, use the following naming structure, listing attributes in this order:

```
SIZE TYPE CONFIG LENGTH Stub
```

### Example Names

- `2 RigidSteel Elbow90plusRiser 24in Stub`
- `3 PVCSch80 Elbow90plusRiser 18in Stub`
- `4 PVCCoatedRigid Elbow90plusRiser 24in Stub`
- `1 PVCSch40 FieldBent 12in Stub`
- `3/4 ENT ConcreteTight Fitting Stub`

### Convention Notes

- Lead with **SIZE** as the nominal trade size matching the conduit run (e.g., 3/4", 1", 2", 3", 4", and larger).
- State **TYPE** as the raceway material: RigidSteel, PVCSch40, PVCSch80, PVCCoatedRigid, or ENT.
- State **CONFIG** as Elbow90plusRiser (factory elbow with riser section), FieldBent (single continuous field-bent length), or ConcreteTightFitting (specialized cast-in fitting).
- State **LENGTH** as the exposed riser length above (or below) the slab, in inches (e.g., "24in") — always confirm this against the NEC's approximate 24" maximum exposed guidance and the governing project spec.
- Note that most stub-downs are **specified and built to job-specific dimensions** rather than ordered as a single fixed catalog SKU — confirm with the vendor or fabricator whether a factory pre-assembled elbow-plus-riser is available at the needed length, or whether it will be field-assembled from a standard elbow and a cut riser section.
- Many vendor catalogs (e.g., Kwikon, Robroy Industries for PVC-coated rigid, Cantex, Carlon) also carry a **manufacturer catalog number** for the elbow/fitting component; when ordering, provide both the plain-language description above and the catalog number if known.

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Standard unit for the elbow or concrete-tight fitting component, and for a complete pre-assembled stub-up/stub-down unit where sold that way.|
|**Foot/Linear Foot (FT/LF)**|Used for the riser/straight portion at takeoff, since exposed length is job-specific and calculated separately from the elbow fitting.|
|**Assembly/Kit**|Some manufacturers sell a factory pre-assembled elbow-plus-riser as a single kit at fixed common lengths (e.g., 12", 18", 24").|

### Ordering Help

- Always specify **trade size, material, configuration, and riser length** together — a stub down is a job-specific assembly, not a generic catalog part, and any one field left unspecified can result in the wrong fitting or an oversized/undersized exposed length.
- Confirm whether the **project specification requires rigid or PVC-coated rigid conduit** for the stub even in locations where the NEC alone would permit PVC — this is a common point of disagreement between code minimums and engineering specs.
- Order **conduit spacers/templates and tie wire** as separate line items when stub-ups are being cast into a slab, since these are necessary to prevent PVC from floating or shifting during the pour but are not bundled with the stub fitting itself.
- For **wet, corrosive, or heavy-traffic-adjacent locations**, confirm PVC-coated rigid steel construction and the correct coating thickness before ordering, since this materially affects both cost and lead time compared to standard galvanized rigid or PVC.

_Generated Schematic_
![](/images/stub-down-schematic.png)