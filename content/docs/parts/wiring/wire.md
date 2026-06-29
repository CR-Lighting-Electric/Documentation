---
title: Wire
type: docs
prev: docs/parts/cord
next: docs/
---


Conductive material that routes an electrical current to some application or device. Wire comes in a large variety of sizing in two more common and cost effective materials: copper and aluminum. Each can be insulated with different materials that have different protective properties. High voltage and low voltage wiring uses different color schemes.

## Naming Convention

The code specifically calls out wire sizes on AWG, and more importantly, KCMIL. Suppliers and foremen may use MCM for their sizing on wiring, but this could easily be misread and misunderstood as MC for metal clad wiring. Let's use KCMIL to keep the two distinct. A wire component can be named as such:

`SIZE` `STRANDING` `MATERIAL` `INSULATION` `COLOR`

- `SIZE` includes the number sizing and the unit of measure, KCMIL or AWG. An example of the size portion of the convention could look like "250 KCMIL" or "1/0 AWG" or "2 AWG."
- `STRANDING` refers to the strand status of wire, which includes either stranded or solid. The type portion of the convention should use its full word as a title (Stranded, Solid).
- `MATERIAL` includes the type of material used in the wiring. Common types are copper or aluminum. In rare cases, silver, gold, or other conductive materials can be used. The material portion of the convention should list out the full word in title form (Aluminum, Copper, Silver)
- `INSULATION` refers to the type of insulation that surrounds the wiring. [Wire Gauge](https://wiregaugecalculator.com/blog/wire-insulation-types-guide) has an excellent reference for the common types. Unless called out for, usually all wire comes in the second generation rating. If the -2 is left off, assume the second modernized generation. In a nutshell, each letter contains a characteristic:
	-  **T** = Thermoplastic insulation material (as opposed to thermoset rubber insulation)
	- **H** = Heat resistant (90°C or 194°F rating)
	- **HH** = High heat resistant (90°C in dry locations, some applications allow higher)
	- **W** = Wet location rated (suitable for use in damp or wet locations)
	- **X** = Cross-linked polymer (XLPE insulation for higher performance)
	- **N** = Nylon jacket over the insulation (provides mechanical and chemical protection)
	- **-2** = Second generation rating with enhanced moisture and heat resistance (90°C wet)
	The insulation portion of the convention could look something like "THHN" or "THWN-2" or "XHHW-2."
- `COLOR` refers to the insulation color that the wiring may contain. Black is by far the most common insulation color, but in runs where multiple lines are utilized in low or high voltage settings, coloring might need to specifically be called out.

### Example Wiring Names

- `750 KCMIL Stranded Aluminum XHHW-2 Black`
- `4 AWG Stranded Copper THWN-2 Red`
- `3/0 AWG Solid Copper THHN Blue`
- `1/0 AWG Solid Aluminum XHHW-2 Green`
- `250 KCMIL Stranded Copper THHN-2 Brown`
- `500 KCMIL Stranded Aluminum XHHW-2 Black w/White Stripe`

## Units of Measure - Linear Feet

When purchased in bulk, wire primarily comes in reels that depend on the wire sizing itself. Bulk wires should round up to the next largest reel size for convenience of the supplier as well. For example, 12 AWG wire can be purchased standard at 2500' reels. Suppliers can also cut wire to length and wind these up on custom reels for use at the job site. These custom wire orders can use multiple conductors, grounds, and other characteristics a job site might need for their wire requirements.

## Further Resources

- [Wire Insulation Types - Wire Gauge Calculator](https://wiregaugecalculator.com/blog/wire-insulation-types-guide)