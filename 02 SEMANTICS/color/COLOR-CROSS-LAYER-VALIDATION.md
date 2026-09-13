# Color — Cross-Layer Validation

**Status:** IMPLEMENTATION-COMPLETE — COORDINATION  
**Semantic ID:** `SEM-COLOR-DOMAIN-001`  
**Version:** 0.1.0

## Validation Matrix

| Colour-related target | Responsible authority | Color-domain treatment | Validation rule |
|---|---|---|---|
| Perceived colour/appearance | Perception + Observer/conditions | Route | Do not equate with physical stimulus |
| Bearer colour characteristic | Property | Route conditionally | Bearer/property semantics must be explicit |
| Chromaticity | Quantity/Property | Route | Preserve defined colorimetric system |
| Tristimulus/colourimetric value | Quantity/Quantity Value | Route | Preserve observer/system and units where applicable |
| Colour measurement | Measurement Activity | Route | Separate event from result |
| Measurement outcome | Result + Quantity Value(s) | Route | Preserve uncertainty/context/provenance |
| Colour space | Representation | Route | Space is not the colour stimulus |
| Colour encoding | Representation/Encoding | Route | Encoding is not semantic identity |
| ICC profile | Representation/Profile | Route | Profile mediates transformations; it is not colour itself |
| Displayed/pixel colour | Representation/Display | Route | Do not infer intrinsic object colour automatically |
| False colour | Representation/visualization | Route | Identify mapping/derived data basis |
| Colour difference | Quantity/validation context | Route | Distance in a specified space is not generic colour identity |
| Metamerism | Colorimetry/Measurement context | Route | Qualify by specified colorimetric system |
| Colour rendering | Viewing/illumination + perceptual context | Route | Separate effect from underlying colour |
| Pigment/structural/emissive mechanism | Material/physical domain | Route | Mechanism is not Color |
| Dynamic colour state | State | Route | State is not universal Color identity |
| Colour change operation | Activity/Process | Route | Operation is distinct from state/result |
| Safety colour | Context/standard + Representation | Route | Meaning is conventional/normative |
| Biological colour signal | Signal/function + domain context | Route | Signal function is not intrinsic colour |
| Colour term/category | Terminology/linguistic context | Route | Do not universalize language categories |
| Colour fastness/integrity | Textile/BIL/validation | Route | Integrity is not Color semantics |

## Chain Validation

### Observation

`Stimulus / Surface / Object → Condition → Observation → Observer / Perception`

Colour interpretation must not bypass the relevant observer and condition semantics when the target is perceived appearance.

### Measurement

`Stimulus / Sample → Measurement Activity → Measurement Result → Quantity Value(s) + Uncertainty → Representation`

The colour domain coordinates the terms but does not collapse the chain.

### Representation

`Information / Measured values → Colour Space / Encoding / Profile → Image / Display / Visualization`

A representation remains distinct from the physical or perceptual colour it encodes or displays.

### Material and mechanism

`Material / Structure / Illumination → physical interaction or generation mechanism → observable stimulus → perception / measurement`

The mechanism is separately owned.

## Validation Verdict

Architecture: PASS.  
Semantic ownership: PASS.  
Perception boundary: PASS.  
Property boundary: PASS.  
Quantity/value boundary: PASS.  
Measurement/result boundary: PASS.  
Representation/encoding boundary: PASS.  
Mechanism/material boundary: PASS.  
Signal/meaning boundary: PASS.  
Safety-convention boundary: PASS.  
Linguistic boundary: PASS.  
Visitor Universe rule: PASS.  
Relation authority preservation: PASS.  
No new semantic layer: PASS.  
No new relation predicate: PASS.

## Residual Risk

Colour terminology remains highly polysemous. Specialized colour concepts should therefore be promoted only under their responsible semantic layer/domain after independent conflict analysis. The domain intentionally remains a coordination authority rather than a closed universal Color ontology.
