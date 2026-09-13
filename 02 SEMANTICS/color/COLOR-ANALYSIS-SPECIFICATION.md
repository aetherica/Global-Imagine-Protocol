# Color — Analysis Specification

**Status:** IMPLEMENTATION-COMPLETE — COORDINATION  
**Folder:** `02 SEMANTICS/color/`  
**Semantic role:** Cross-layer routing authority for colour-related senses.  
**Version:** 0.1.0

## Analysis Objective

Determine the semantic responsibility of colour terminology across GIOP V3.1 without creating a duplicate of Perception, Property, Quantity, Activity, Result, Representation, Condition, Class/Material, or any other established layer.

## Research Dimensions

1. CIE colorimetry and terminology: colour, chromaticity, colour spaces, tristimulus values, colour difference, metamerism, colour rendering, viewing conditions.
2. ISO/CIE standards: standard observers, illuminants, CIELAB/CIE 1976, CIELUV and related colourimetric systems.
3. ICC colour management: device-dependent spaces, profiles, profile connection space, encoding and transformation boundaries.
4. W3C digital colour: colour values, interpolation, gamut mapping, serialization and custom colour spaces.
5. DICOM and scientific/medical imaging: colour-space metadata, ICC profiles, rendering, colour maps and image representation.
6. External ontologies and cultural-heritage terminology: PATO, CIDOC CRM, Getty AAT and alternative quality/feature modelling choices.
7. Metrology: reflectance, traceability, uncertainty and measurement-system limitations.
8. Physical/material mechanisms: pigmentary, structural, emissive, interference, scattering and responsive coloration; mechanism taxonomy treated as documented, not exhaustive.
9. Biology and signalling: coloration as camouflage, display, communication, or indicator output.
10. Computer vision and remote sensing: illumination/reflectance/sensor decomposition and false-colour visualization.
11. Safety and normative communication: ISO 3864/7010 and context-dependent colour meanings.
12. Linguistics and cognition: colour categories, naming, perceptual constraints, communication and socio-cultural variation.
13. Food, textile, accessibility and applied domains: colour as perceptual cue, quality expectation, fastness, visualization and redundant communication.
14. GIOP internal architecture: existing Perception, Observer, Property, Quantity, Activity, Process, Result, Representation, Condition, State, Material, Textile, Garment, Model and BIL boundaries.

## Competing Interpretations

### Interpretation A — Color as a universal Class

Rejected. Colour can denote an appearance, quality, quantitative specification, representation, signal, meaning, mechanism, or domain-specific category. No universal bearer identity is justified.

### Interpretation B — Color as a canonical Property

Rejected as universal. Some bearer-related colour characteristics can route to Property, but not all colour uses are properties.

### Interpretation C — Color as Perception

Rejected as universal. Perceived colour belongs with Perception and Observer/Viewing Condition semantics, while colourimetry and representations have distinct responsibilities.

### Interpretation D — Color as Quantity

Rejected as universal. Colourimetric coordinates and values are quantitative specifications in defined systems; the general domain of colour is broader.

### Interpretation E — Color as Representation

Rejected as universal. Encoded colours, palettes, profiles, colour maps and false-colour imagery are representations/encodings of information and are not automatically intrinsic colour.

### Interpretation F — Color as signal or meaning

Rejected as intrinsic identity. Functional and normative meanings are context- or convention-dependent.

### Interpretation G — Color as physical/material mechanism

Rejected as universal. Pigments, nanostructure, emission, interference and scattering are mechanisms that can generate colour, not the colour semantic itself.

### Interpretation H — Color as an independent GIOP semantic layer

Rejected. The research shows a cross-layer semantic domain is more faithful to the polysemy and preserves existing architecture.

### Interpretation I — Color as a cross-layer coordination domain

Retained. This provides a bounded intake and routing surface while leaving canonical semantic ownership with established layers and domain authorities.

## Semantic Ownership Decision

Primary ownership is **cross-layer domain coordination**. The folder resolves colour senses, preserves qualifiers, and routes claims to the responsible existing layer/domain. It does not promote a new ontology layer, relation predicate, or universal Color concept.

## Key Boundary Findings

- Perceptual colour depends on observer and viewing conditions; standard colorimetry operationalizes stimuli but does not erase observer variation.
- Chromaticity and colourimetric values require a specified system; metamerism is system-relative.
- Colour space, colour-space encoding, profile, display and image are distinct representation/encoding constructs.
- False colour is a visualization convention and must not be treated as literal object colour.
- Safety colour meanings are standardized conventions, not intrinsic meanings of wavelengths or colours.
- Linguistic colour categories reflect interacting perceptual, linguistic, communicative and socio-cultural factors; deterministic cultural causation is not assumed.
- Colour-generation mechanisms form a documented family of mechanisms, not a claimed exhaustive universal taxonomy.
- Dynamic colour can be a state, activity/process, material response, signal, or representation depending on the semantic target.

## GIOP Decision

`SEM-COLOR-DOMAIN-001` is **IMPLEMENTATION-COMPLETE — COORDINATION**. Preferred name is **Color Semantic Domain**. It is not a canonical semantic layer or universal Color concept. No new relation predicate is created, and external ontologies/standards remain evidence only.
