# Material — Boundary Rule

**Status:** IMPLEMENTATION-COMPLETE — CLASS-ROUTED DOMAIN COORDINATION
**Canonical owner:** `SEM-CLASS-MATERIAL-001`

## Core Rule

The word `Material` does not create a new semantic layer. The canonical Material identity remains in `02 SEMANTICS/classes/material.md`.

## Boundary Rules

1. Do not create a second canonical Material entry under this folder.
2. Material owns the identity of a physical substance or medium considered for composition, structure, manufacture, use, or domain-relevant behaviour.
3. Property owns characteristics of a material, including optical, mechanical, electrical, thermal, chemical, or qualitative characteristics.
4. Quantity owns measurable kinds; Quantity Value owns values and Units/Reference/Scale qualification where applicable.
5. Measurement Activity owns the measurement act; Result owns the measurement outcome.
6. Object/Class semantics own identifiable objects that may contain or be made of one or more materials.
7. Surface semantics own boundaries/interfaces; surface appearance does not establish material identity.
8. Textile owns textile-specific fibre/yarn/fabric/structure/finish semantics; generic textile material remains routed to Material unless the claim is specifically about the textile entity.
9. Garment owns wearable articles and garment-specific components; garment material is composition/context, not an alternate garment identity.
10. Activity/Process/Workflow own material transformation, manufacture, treatment, testing, finishing, recycling, and related operations.
11. State/Condition own temporary modes or conditions of a material, not the material identity.
12. Representation owns photographs, scans, meshes, drawings, files, encodings, and other information-bearing forms that depict or record material.
13. Provenance owns source/history/authenticity information; evidence supports a material claim but is not the material.
14. BIL may evaluate whether material or material-related configuration affects integrity, but BIL does not own Material.
15. No new relation predicate may be introduced for material composition or material interaction without an independent Relation-authority pass.

## Non-Collapse Tests

- Material ≠ Property
- Material ≠ Quantity
- Material ≠ Quantity Value
- Material ≠ Measurement Activity
- Material ≠ Measurement Result
- Material ≠ Object
- Material ≠ Surface
- Material ≠ Textile
- Material ≠ Garment
- Material ≠ Representation
- Material ≠ Process
- Material ≠ State
- Material ≠ Condition
- Material ≠ Provenance
- Material ≠ Evidence

## Lexical Polysemy Rule

`Material` may denote a substance, medium, sample, specimen, engineering form, educational resource, clothing material, or other context-specific concept in external systems. GIOP routing must follow semantic responsibility, not lexical coincidence. External vocabulary does not override the canonical Material Class boundary.

## Promotion Gate

A future material-specific concept may only be promoted when it demonstrates an independent responsibility that cannot be handled as the Material Class itself, a Property, Quantity/Measurement, Object, Textile/Garment concept, Activity/Process, State/Condition, Representation, or another established owner.
