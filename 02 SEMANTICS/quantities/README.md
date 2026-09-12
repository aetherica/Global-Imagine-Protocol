# Quantities

The Quantity semantic layer defines reusable canonical concepts for measurable aspects of entities, phenomena, systems, materials, spaces, and other eligible bearers.

**Semantic Layer:** Quantity  
**Version:** 3.1  
**Status:** Active development / canonical corpus implementation  
**Primary Responsibility:** Measurable semantic concept  
**Repository:** Global Imagine Protocol  
**Branch:** `v3.1-tree-architecture`

## What

A Quantity is a reusable canonical semantic concept denoting a measurable aspect whose magnitude can be expressed through an appropriate value and reference structure.

Quantity answers the semantic question: **what measurable aspect is being quantified?**

A Quantity is not the numerical value assigned to that aspect, the unit used to express the value, the measurement activity that establishes it, or the measurement result that records the outcome.

## Why

Imaging and related technical domains continuously use numerical descriptions: distance, focal length, wavelength, exposure time, illuminance, luminance, radiance, irradiance, reflectance, transmittance, spatial frequency, and many others.

Without a dedicated Quantity boundary, numerical concepts can be incorrectly classified as Properties, Values, Units, Measurements, Metrics, Parameters, Variables, States, or Conditions.

The Quantity layer provides a stable semantic owner for measurable concepts while allowing their values, units, measurement procedures, contexts, uncertainty, and representations to remain separately identifiable.

## Structure

The V3.1 Quantity model distinguishes at minimum:

`Quantity Concept → Quantity Value → Unit / Reference → Measurement or other establishment activity → Measurement Result / Representation`

Where relevant, a Quantity is further characterized through a quantity kind, quantity dimension, scale/reference system, mathematical structure, temporal scope, spatial scope, and domain constraints.

These supporting constructs are not automatically separate canonical concepts in V3.1. They are introduced as distinct concepts only where independent semantic responsibility is demonstrated.

## How

A candidate term enters the Quantity layer only after semantic classification, evidence review, conflict analysis, and cross-layer validation.

The governing decision path is:

`NEW KNOWLEDGE → RETAIN → CLASSIFY → VERIFY → RESOLVE → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE`

A numerical expression alone is insufficient for Quantity eligibility.

## Where

Quantity concepts may apply across optical imaging, photography, cinematography, sensors, displays, materials, scenes, measurement systems, computational imaging, color science, metrology, video, spatial media, and other domains.

Domain-specific use does not automatically create a new Quantity concept. A distinct concept is created only when the semantic responsibility is reusable and cannot be adequately represented by an existing canonical Quantity or another semantic layer.

## Who

The same canonical Quantity knowledge is intended for different entry depths across the GIOP Visitor Universe, including curious visitors, students, educators, imaging practitioners, engineers, scientists, metrologists, AI/ML engineers, data-curation specialists, system integrators, technology decision makers, archivists, journalists, and machine/API consumers.

Visitor categories do not alter Quantity identity and are not represented as semantic subtypes of Quantity.

## Semantic Definition

**Quantity** is a reusable canonical semantic concept denoting a measurable aspect of an eligible entity, phenomenon, system, material, spatial region, temporal occurrence, or other bearer whose magnitude can be expressed through an appropriate value-and-reference structure.

## Core Boundaries

`Quantity ≠ Quantity Value`  
`Quantity ≠ Unit`  
`Quantity ≠ Measurement`  
`Quantity ≠ Measurement Result`  
`Quantity ≠ Property`  
`Quantity ≠ Value`  
`Quantity ≠ Metric`  
`Quantity ≠ Parameter`  
`Quantity ≠ Variable`  
`Quantity ≠ State`  
`Quantity ≠ Condition`  
`Quantity ≠ Status`

A quantity may be used to quantify a property, state, condition, or other semantic element without becoming identical to that element.

## V3.1 Canonical Nucleus

The initial nucleus is intentionally small. It includes the generic Quantity concept and high-confidence domain quantities whose semantic responsibility can be independently defended.

Existing active entries include:

- `SEM-QUANTITY-DISTANCE-001` — Distance
- `SEM-QUANTITY-TEMPERATURE-001` — Temperature

The implementation wave will extend this nucleus only after candidate-level validation.

## Candidate and Deferred Knowledge

Terms such as resolution, SFR, MTF, OTF, noise, dynamic range, SNR, sharpness, sensitivity, metric, parameter, and variable may be numerically expressed but are not promoted merely because they are measurable or commonly reported as numbers.

Such knowledge remains retained in the Quantity decision registry when its final semantic owner is unresolved or domain-dependent.

## Evidence / Trust / Validation

Quantity definitions are source-independent but evidence-dependent. External standards, metrology references, ontologies, imaging standards, and scientific literature provide evidence; they do not automatically become GIOP semantic authority.

Particular attention is given to BIPM/VIM, SI, ISO 80000, ISO/IEC 11179, QUDT, SSN/SOSA, measurement science, CIE, and relevant optical/imaging standards.

Canonical status must not be inferred solely from source frequency, vendor usage, numerical representation, or evidence strength.

## Machine / AI Interpretation

Machines should be able to distinguish a Quantity concept from its value, unit, measurement activity, result, property, condition, state, relation, context, and representation.

Stable semantic IDs are the identity mechanism. File path, filename, display label, or lexical coincidence is not semantic identity.

## Lifecycle

Quantity artifacts follow the GIOP lifecycle and validation policy. Existing active entries remain preserved while the folder is expanded. Deferred concepts remain retained rather than silently deleted.

## Retrieval Anchors

`QUANTITY`, `MEASURABLE QUANTITY`, `PHYSICAL QUANTITY`, `MEASURABLE ASPECT`, `QUANTITY CONCEPT`, `QUANTITY VALUE`, `QUANTITY KIND`, `QUANTITY DIMENSION`, `UNIT`, `MEASUREMENT`, `MEASUREMENT RESULT`
