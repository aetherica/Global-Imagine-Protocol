# Color — Boundary Rule

**Status:** IMPLEMENTATION-COMPLETE — COORDINATION  
**Semantic ID:** `SEM-COLOR-DOMAIN-001`  
**Version:** 0.1.0

## Governing Rule

`Color domain ≠ one semantic type`.

Every colour-related assertion must be routed according to its actual semantic target rather than the lexical presence of “color/colour”.

## Mandatory Non-Collapse Rules

- Color ≠ Perception.
- Color ≠ Property.
- Color ≠ Quantity.
- Color ≠ Quantity Value.
- Color ≠ Measurement.
- Color ≠ Measurement Result.
- Color ≠ Representation.
- Color ≠ Encoding.
- Color ≠ Display.
- Color ≠ Signal.
- Color ≠ Meaning.
- Color ≠ Mechanism.
- Color ≠ Condition.
- Color ≠ Context.
- Color ≠ State.
- Color ≠ Evidence.
- Color ≠ Provenance.
- Color ≠ Integrity.
- Color ≠ Material.
- Color ≠ Textile.
- Color ≠ Garment.

## Routing Safeguards

### Perception safeguard

If the semantic target is experienced or observer-dependent appearance, route to Perception and preserve Observer/Viewing Condition context where applicable.

### Property safeguard

If colour is asserted as a characteristic of a bearer, Property may own the assertion. Do not infer that all colour terminology is Property.

### Quantitative safeguard

If the claim is a tristimulus value, chromaticity coordinate, lightness, chroma, or defined colour-difference quantity, route to existing Quantity/Property authorities according to established ownership. Always preserve the specified colour system/space.

### Measurement safeguard

A measured colour is not the measurement event. Measurement remains Activity and its generated outcome remains Result, with uncertainty/context/provenance where applicable.

### Representation safeguard

A colour-space encoding, ICC profile, palette, display value, pixel, colour map, swatch, or false-colour rendering is not automatically the underlying colour stimulus or object property.

### Meaning safeguard

A conventional colour code, safety colour, category marker, or interface signal acquires meaning through a relevant context, standard, function, or convention. Meaning is not intrinsic Color identity.

### Mechanism safeguard

Pigment, structural nanostructure, emission, interference, scattering, fluorescence, or other coloration mechanism is not itself Color. Mechanism ownership follows the responsible physical/material domain.

### Dynamic-colour safeguard

A colour change may involve State, Activity, Process, material response, signal, or representation. The change event is not collapsed into a universal Color concept.

### False-colour safeguard

A rendered colour assigned from non-visible bands, derived variables, or visualization mappings must be identified as a representation/visualization result and must not be interpreted as literal surface colour without evidence.

### Safety safeguard

Standardized safety colours are normative communication conventions. Do not encode a universal intrinsic meaning such as “red = danger” in the Color domain.

### Linguistic safeguard

Colour names and categories are terminology/cognitive phenomena. Language-specific categories must not be treated as universal physical partitions of colour.

## External Ontology and Standard Rule

External definitions, classes, properties, relation predicates, equations, colour spaces, standards, and implementation conventions are evidence for analysis only. They do not automatically acquire GIOP canonical status.

## Relation Rule

No new relation predicate is admitted. Existing canonical relations remain unchanged.

## Visitor Rule

Visitor Universe may alter entry depth and presentation only. It may not create visitor-specific Color identities or semantic variants.
