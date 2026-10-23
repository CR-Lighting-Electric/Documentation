---
title: Threaded Inserts
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

A threaded insert is a fitting that is installed into a hole to provide a strong internal thread where the base material is too thin to tap, too soft to hold a thread, or has a thread that has been stripped. A screw or bolt then threads into the insert instead of the base material. On electrical orders they appear in enclosure and panel work, mounting plates, equipment frames, wood backboards, and thread repair.

Scope against neighboring pages: loose nuts and coupling nuts are on the Nuts page, screws and concrete screws are on the Screws page, bolts are on the Bolts page, and concrete and masonry anchors, including the internally threaded drop-in anchor, are on the Anchors page. This page covers inserts that create a thread in sheet metal, castings, wood, and plastic. Non-threaded blind rivets and strut nuts are not covered.

Threaded insert types:

- **Rivet nut (blind rivet nut)** — a one-piece, internally threaded, counterbored tubular rivet that anchors entirely from one side of the work, so a thread can be made in thin sheet metal where there is no access to the back. It is set with a hand or pneumatic tool. Body styles are Round (a cylindrical shank that can spin in softer materials), Hex (a hexagonal shank that cuts into the hole wall to resist turning, suited to aluminum, fiberglass, and plastic), and Knurled (ribs that bite the hole wall, in a round hole). Ends are Open (the bolt passes through, standard) or Closed (sealed on the blind side for water and dust). Low-profile and floating types also exist.
- **Helical-coil insert** — a diamond-section wire coil (Heli-Coil, Recoil, KATO) that screws into a tapped hole, in stainless steel or phosphor bronze. It is installed with a matched tap and insert tool, usually sold as a kit. It is used to repair stripped threads and to give stronger threads in soft materials such as aluminum, zinc die castings, wood, and plastic.
- **Self-tapping or externally threaded insert** — an insert with an outer thread that taps its own way into a hole in metal and is locked in by a nylon element, a thread-locking compound, a key, or friction. Key-locking inserts (Keenserts) are locked by keys hammered into the thread grooves.
- **Press-in (press-fit and swage) nut** — a nut that is pressed into a hole with an arbor press. The swage type has a knurled section that deforms the soft metal hole to grip it. For panels too thin to thread.
- **Wood insert** — an insert for wood and particleboard, either Screw-In (external thread with a hex head, driven with a screwdriver or Allen wrench) or Hammer-In (a barbed insert driven with a hammer, made in steel, brass, or nylon).
- **Plastic insert** — a brass or stainless steel insert that is molded in, or pressed into a hollow in a plastic part by heat (thermal) or vibration (ultrasonic), for plastic housings and casings.
- **Cage or clip-on nut** — a nut held in a sheet-metal carrier that clips onto the part, reusable with hand tools, for panels too thin to thread.

Threaded inserts are selected based on:

1. **Base material and access** — thin sheet metal with one-side access suits a rivet nut; a stripped or soft casting suits a helical coil; wood suits a wood insert.
2. **Thread** — the bolt or screw thread to be held, in inch (UNC or UNF, such as 1/4"-20, 10-32, 3/8"-16) or metric (such as M6).
3. **Type and style** — the insert type, and for a rivet nut the end (Open or Closed) and the body (Round, Hex, or Knurled).
4. **Material** — Steel or zinc-plated steel for general indoor use; Stainless-Steel (304 or 316) for outdoor and corrosive locations; Aluminum for aluminum panels, to avoid galvanic coupling; Brass for electrical enclosures, electronics, and plastics.
5. **Grip range** — for a rivet nut, the panel thickness range the insert is made for.
6. **Loads** — pull-out resistance and torque-out resistance, per the manufacturer's data.

## Further Resources

- [Wikipedia – Threaded Insert](https://en.wikipedia.org/wiki/Threaded_insert) — overview of captive nuts, plastic inserts, self-tapping and key-locking inserts, helical inserts, rivet nuts, and wood inserts.
- [AIMS Industrial – Rivet Nut Guide](https://aimsindustrial.com.au/blogs/product-guides/rivet-nut-guide) — reference on rivet nut end and body styles, materials, grip range, hole size, installation, and tools. Its tables are in metric and contain conflicting figures in places, so use the manufacturer's data sheet.
- [Albany County Fasteners – Threaded Insert Information](https://www.albanycountyfasteners.com/fasteners-101-threaded-insert-information) — distributor guide to helical, key-locking, self-tapping, heat-set, ultrasonic, and press-fit inserts (the page's body text did not load, so it is cited from its listing only).
- [McMaster-Carr – Threaded Inserts](https://www.mcmaster.com/products/threaded-inserts/thread-size~m8) — catalog reference for insert types, thread sizes, and materials.
- National Electrical Code (NEC), NFPA 70 — Article 250.8 (Connection of Grounding and Bonding Equipment), which does not permit sheet metal screws and calls for listed connectors or machine screws with proper thread engagement.

## Naming Convention

When identifying threaded inserts for vendor ordering, use the following naming structure, listing attributes in this order:

```
THREAD TYPE STYLE MATERIAL Threaded-Insert
```

### Example Names

These examples show the pattern; confirm the sizes, materials, and availability in the maker's catalog.

- `1/4"-20 Rivet-Nut Open-Hex Steel Threaded-Insert`
- `3/8"-16 Rivet-Nut Open-Round Stainless-Steel Threaded-Insert`
- `10-32 Rivet-Nut Closed-Round Aluminum Threaded-Insert`
- `M6-1.0 Rivet-Nut Open-Knurled Zinc-Plated-Steel Threaded-Insert`
- `1/4"-20 Helical-Coil NA Stainless-Steel Threaded-Insert`
- `1/4"-20 Key-Locking NA Stainless-Steel Threaded-Insert`
- `1/4"-20 Wood-Insert Hammer-In Steel Threaded-Insert`
- `M4-0.7 Plastic-Insert Heat-Set Brass Threaded-Insert`

### Convention Notes

|Descriptor|Explanation|
|---|---|
|THREAD|The internal thread the insert provides: inch as diameter-threads per inch (for example 10-32, 1/4"-20, 3/8"-16) or metric as M diameter-pitch (for example M6-1.0).|
|TYPE|Rivet-Nut, Helical-Coil, Key-Locking, Self-Tapping, Press-In, Wood-Insert, Plastic-Insert, or Cage-Nut.|
|STYLE|For a Rivet-Nut, the end and the body: Open-Round, Open-Hex, Open-Knurled, Closed-Round, Closed-Hex, or Closed-Knurled. For a Wood-Insert, Screw-In or Hammer-In. For a Plastic-Insert, the installation method (Heat-Set or Ultrasonic). NA where the type has no style, as for helical coils.|
|MATERIAL|Steel, Zinc-Plated-Steel, Stainless-Steel (304 or 316), Aluminum, Brass, or Phosphor-Bronze. Confirm the material for the base metal and the environment.|
|Grip range|Not part of the naming string, but for a Rivet-Nut confirm that the panel thickness is within the grip range on the datasheet, aiming for the middle of the range.|
|Hole size|Not part of the naming string, but drill the hole to the manufacturer's size. An oversized hole loses grip and an undersized hole risks stripping the thread.|
|Catalog number|Vendor catalogs (e.g., McMaster-Carr, Heli-Coil, Recoil, Keensert, PEM) also carry their own part numbers; provide both the plain-language name and the catalog number when known, since the grip range, hole size, and installation tool are brand- and model-specific.|

## Typical Units of Measure

|Unit|Typical Use|
|---|---|
|**Each (EA)**|Occasional use for a single specialty insert.|
|**Pack or Box**|Common packaging for rivet nuts and press-in nuts; the count depends on the size.|
|**Kit**|Helical-coil inserts are usually sold as kits with the matched tap and installation tool.|
|**Case**|Distributor bulk quantity for larger projects.|

### Ordering Help

- Pick the **type by the base material and access first**: a rivet nut for thin sheet metal with access to one side only, a helical coil to repair a stripped thread or strengthen a soft casting, and a wood insert for wood.
- For rivet nuts, **match the grip range to the panel thickness**. If the nut is too short for the panel it spins, and if it is too long it will not set fully.
- Drill to the **manufacturer's hole size**, deburr both faces, and set the tool's depth stop on scrap of the same thickness. Burrs are a common cause of spinning. An oversized hole even by 0.3 to 0.5 mm can cause spinning.
- Choose **Hex or Knurled bodies where the nut must not turn**, such as in aluminum, fiberglass, and plastic, and **Closed-End** where water or dust must not pass through.
- Match the **material to the panel and the environment**: Aluminum on aluminum to avoid galvanic coupling, Stainless-Steel for outdoor or corrosive use, Brass for enclosures and plastics. Zinc-plated steel is for indoor or sheltered use.
- Order the **installation tool with the inserts**: a hand tool with mandrels for small sizes, and a pneumatic tool for large sizes in stainless steel and for volume. For helical coils, order the kit with the matching tap and insert tool.
- For **ground and bonding connections** to an insert, use a machine screw with proper thread engagement and clear the paint at the contact face (NEC 250.8); treat it as an engineered connection and confirm it against the equipment listing.
- Check the **thread size to the screw or bolt on the Screws, Bolts, or Nuts pages**, and use the maker's thread standard (UNC or UNF for inch, ISO metric).
- Do not pick inserts for **overhead or structural loads** from the catalog name alone; confirm the pull-out and torque-out values with the manufacturer.