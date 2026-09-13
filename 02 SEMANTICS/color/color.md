# Color

**Semantic ID:** `SEM-COLOR-DOMAIN-001`  
**Preferred Name:** Color Semantic Domain  
**Artifact Type:** Semantic Domain / Cross-Layer Routing Authority  
**Primary Responsibility:** Resolve colour senses, semantic ownership, qualifiers, and cross-layer routing without creating a standalone Color ontology layer.  
**Status:** IMPLEMENTATION-COMPLETE — COORDINATION  
**Version:** 0.1.0  
**Authority:** GIOP V3.1 domain coordination governance; existing semantic-layer authorities remain authoritative.  
**Provenance:** Multi-dimensional, multi-domain semantic synthesis; external standards, ontologies, scientific literature, and domain sources are evidence, not GIOP authority.  
**Validation:** Research cross-check and internal boundary analysis completed; no existing canonical layer redefined and no new relation predicate admitted.  
**Related IDs:** `SEM-PERCEPTION-GENERIC-001`; `SEM-OBSERVER-MODEL-001`; `SEM-CLASS-MATERIAL-001`; `SEM-RELATION-GENERIC-001`; `SEM-RESULT-GENERIC-001`; relevant Quantity, Property, Representation, Condition, Activity, Process, Textile, Garment, Model, and Implementation authorities.

## 5W1H Orientation

### What

Color is a cross-layer semantic domain covering multiple legitimate senses of colour: perceptual appearance, bearer-related characteristic, colourimetric specification, quantitative value, representation, functional signal, conventional meaning, physical generation mechanism, and time-varying colour behaviour. The domain coordinates these senses; it is not itself a new semantic layer and does not assert one universal canonical Color concept.

### Why

The term colour is polysemous across colorimetry, perception, materials, biology, imaging, computer vision, digital colour management, safety communication, linguistics, food and textile practice. Treating every occurrence as one semantic type would collapse perception, property, quantity, representation, signal, meaning, mechanism, and evidence. A bounded routing authority prevents those collapses.

### Who

The domain serves semantic modelers, color scientists, metrologists, imaging and computer-vision practitioners, material and textile specialists, biomedical and scientific-imaging users, accessibility and interface designers, cultural-heritage systems, and machine consumers that must identify the responsible semantic owner of a colour-related claim.

### Where

It applies wherever colour terminology crosses semantic boundaries: observed scenes and surfaces, self-luminous stimuli, physical/material coloration, measurement and colorimetry, displays and images, colour spaces and encodings, remote-sensing false colour, biological signalling, safety conventions, linguistic categorization, food/material quality judgments, and responsive colour systems.

### When

Colour semantics are relevant whenever a colour is perceived, characterized, measured, represented, displayed, generated, signalled, conventionally interpreted, or observed to change. Temporal change, measurement events, and evidence remain separately represented rather than becoming intrinsic parts of the Color domain identity.

### How

A colour-related record is routed by semantic responsibility: identify whether the target is appearance/perception, a bearer-related property, a quantity or value, a measurement activity/result, a representation/encoding, a signal or convention, a physical generation mechanism, a condition/context, or evidence/provenance. Preserve material, observer, illumination, viewing, measurement, representation, functional, and temporal qualifiers when they affect interpretation.

## Semantic Definition

**Color Semantic Domain** is a cross-layer coordination authority for the controlled interpretation and routing of colour-related meanings. It resolves colour senses and preserves distinctions among perceptual appearance, bearer-related characteristics, colourimetric quantities and values, measurements and results, representations and encodings, physical coloration mechanisms, functional signals, conventional meanings, and contextual or temporal qualifications.

The domain deliberately does **not** establish Color as an independent GIOP semantic layer. A colour claim acquires its authoritative semantic identity from the existing layer or domain that owns the claim.

## Scope and Boundary

### In scope

- Perceptual colour and colour appearance as an observer-dependent interpretation.
- Bearer-related colour characteristics when the semantic target is a property.
- Chromaticity and colourimetric quantities/values through existing Quantity and Property authorities.
- Colour measurement through Measurement Activity, Measurement Result, Quantity Value, uncertainty, context, and provenance as applicable.
- Colour spaces, encodings, profiles, palettes, colour maps, displayed colour, and false-colour imagery through Representation authorities.
- Physical/material coloration mechanisms, including pigmentary, structural, emission, interference, scattering, and other documented mechanisms, through responsible physical/material domains.
- Functional colour signals and conventional/normative colour meanings when qualified by context, function, or standard.
- Dynamic or responsive colour as a phenomenon whose state, process, activity, or material mechanism is separately owned.
- Linguistic colour categories and terminology as contextual/linguistic phenomena, not intrinsic physical meanings.

### Out of scope

- A new canonical Color semantic layer.
- A universal canonical Color class, property, perception, quantity, representation, or relation.
- A universal closed taxonomy of colour-generation mechanisms.
- Treating colour names or safety meanings as intrinsic physical semantics.
- Treating a displayed/pixel colour as automatically equivalent to intrinsic object or surface colour.
- Treating colour space as colour itself, or encoding/profile as the underlying colour stimulus.
- Treating a colour difference metric, validation metric, or formula as a semantic Color concept.
- Importing external ontology classes, relation predicates, axioms, or standard terms as GIOP canon without governance.

## Core Distinctions

### Color vs Perception

Perceived colour is an observer-dependent perceptual phenomenon. The same physical stimulus can be characterized through colorimetry while its experienced appearance depends on observer and viewing conditions. Route perception to `perception/`; do not equate colour terminology with the Perception layer.

### Color vs Property

A bearer-related colour characteristic may be modeled as a Property when the semantic target is a quality/characteristic of a bearer. This does not make every use of “color” a GIOP Property.

### Color vs Quantity and Quantity Value

Chromaticity coordinates, tristimulus values, lightness, chroma, and colour-difference values are quantitative specifications or values in defined systems. They are not interchangeable with the general semantic domain of colour.

### Color vs Measurement

Measurement is an Activity with a Result. A measured colour description is not the measurement event itself and must retain method, uncertainty, context, observer/measurement-system, and provenance where material.

### Color vs Representation

An image pixel, colour swatch, palette, colour map, colour-space encoding, ICC profile, display rendering, or false-colour visualization is a representation or encoding. It must not be inferred to be the underlying physical or perceptual colour without the required interpretation chain.

### Color vs Signal or Meaning

Colour can function as a signal or acquire conventional meaning, but danger, permission, category, taste expectation, or other meanings are assigned by context, convention, design, culture, or normative systems. Such meanings are not intrinsic Color identity.

### Color vs Mechanism

Pigments, structural nanostructures, emission, interference, scattering, and related mechanisms can generate or modify colour. A mechanism is not the colour itself.

### Color vs Condition and Context

Illumination, viewing condition, adaptation, background, display condition, and scene context can affect colour interpretation. They remain conditions/context rather than becoming Color identity.

### Color vs Evidence and Provenance

Spectral measurements, images, documents, calibration records, and other evidence can support a colour claim. Evidence and provenance are not the claimed colour semantics.

### Color vs Integrity

Colour consistency, colour-profile validity, colour fastness, or validation metrics may concern integrity or quality assurance. They do not redefine Color semantics.

## Cross-Layer Routing

- Perceived colour / colour appearance → Perception + Observer/Viewing Condition where applicable.
- Bearer-related colour characteristic → Property authority where applicable.
- Chromaticity / tristimulus / colour-space coordinates / colour difference → Quantity and/or Property according to the established semantic owner.
- Colour measurement → Measurement Activity → Measurement Result → Quantity Value(s) + uncertainty/context/provenance.
- Colour space / encoding / profile / palette / colour map / false-colour image → Representation authority.
- Physical coloration mechanism → responsible Class/Material/Textile/Garment or other physical domain + Process/Activity where applicable.
- Current colour configuration or dynamic colour state → State where state is the target; change event → Activity/Process.
- Colour signal/code/indicator → Representation and relevant Context/Function; normative meaning remains context-bound.
- Colour naming/category → linguistic/terminological responsibility and relevant context.
- Evidence and traceability → Provenance/Evidence/Validation responsibility.
- Colour-related integrity evaluation → BIL or other integrity authority where applicable; BIL does not own Color semantics.

**No new relation predicate is admitted by this domain.**

## Cross-Domain Significance

Colour is a coordination hotspot because one lexical term can connect physical optics, material structure, perception, measurement, digital imaging, display technology, biological signalling, safety communication, language, food, textiles, and scientific visualization. The routing domain allows those connections without flattening them into one ontology category.

A critical machine-consumption rule is: **pixel/display colour is not automatically intrinsic object colour**. Interpretation requires the relevant representation, colour-space, illumination, sensor/display, measurement, and observer context.

## Trust and Evidence

The domain is supported by multi-dimensional evidence from CIE colorimetry and terminology, ISO/CIE colour standards, ICC colour-management specifications, W3C CSS Color, DICOM, external ontologies such as PATO and CIDOC CRM, metrology guidance, computer-vision literature, structural-colour research, biological signalling research, safety standards, linguistic colour research, and domain-specific textile/food/imaging practice. These sources demonstrate competing and complementary semantic usages; they do not constitute GIOP canonical authority.

Where quantitative colour claims are made, uncertainty and traceability are material considerations. Standard observers and standardized colour systems are operational constructs and do not eliminate individual observer variation.

## Visitor Universe

All visitor categories consume the same Color Semantic Domain through different entry depths. A general visitor may need the appearance/meaning distinction; a metrologist needs colorimetric and uncertainty routing; an imaging practitioner needs representation/profile/false-colour boundaries; a material or textile practitioner needs bearer/mechanism routing; a machine consumer needs deterministic ownership and non-collapse rules. No visitor receives a separate colour identity.

## Lifecycle

Current state: implementation-complete coordination authority. The routing boundaries and non-collapse decisions are stable for this V3.1 phase. Specialized colour concepts may be independently evaluated under their responsible semantic layer or domain. Any future canonical promotion requires normal GIOP governance and conflict analysis; external standards do not automatically promote concepts.

## Retrieval Anchors

`COLOR`, `COLOUR`, `COLOR SEMANTIC DOMAIN`, `COLOUR APPEARANCE`, `PERCEIVED COLOR`, `CHROMATICITY`, `COLORIMETRY`, `COLOR SPACE`, `COLOR ENCODING`, `COLOR PROFILE`, `FALSE COLOR`, `STRUCTURAL COLOR`, `COLOR SIGNAL`, `COLOR MEANING`, `COLOR CHANGE`, `COLOR DIFFERENCE`, `COLOR RENDERING`, `METAMERISM`
