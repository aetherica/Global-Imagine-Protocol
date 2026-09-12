# Viewing Distance

## Identity / Metadata
- **GIOP ID:** `SEM-RELATION-VIEWING-DISTANCE-001`
- **Preferred Term:** `viewing-distance`
- **Artifact Type:** Specialized Semantic Relation Candidate
- **Primary Responsibility:** Spatial relation specifying separation between a defined viewing reference and a viewed target.
- **Semantic Family:** Spatial / Viewing Relation
- **Status:** ROUTED — SPECIALIZED RELATION CANDIDATE
- **Version:** 1.0.0
- **Canonical Seed Status:** Not part of the six-relation V3.1 seed vocabulary.
- **Destination:** Future spatial/measurement-oriented relation treatment.

## 5W1H Orientation
**What:** A typed spatial relation between a viewing reference and a viewed target.
**Why:** To preserve visual setup geometry without conflating it with focal length, object distance, field of view, or angular size.
**Who/What:** Subject is the defined observer/viewing point; object is the viewed object, surface, display, scene, or other target.
**Where:** Display viewing, photography, cinematography, visual inspection, human factors, laboratory observation, metrology, and related visual contexts.
**When:** Context-dependent; may vary with observer, target, or configuration.
**How:** Identify both endpoints, the spatial frame, and the associated Distance quantity/value and unit where available.

## Semantic Definition
**Viewing Distance specifies a spatial separation between a defined viewing reference and a defined viewed target.**

The relation may be associated with a Distance quantity, but a bare distance value without defined endpoints does not establish this relation.

## Relation Contract
- **Domain:** Defined observer/viewing reference.
- **Range:** Defined viewed target.
- **Direction:** `VIEWING REFERENCE → VIEWED TARGET`.
- **Inverse:** Reverse traversal is possible; no separate canonical inverse is established.
- **Characteristics:** Spatial and context-dependent. No global transitivity, symmetry, or cardinality rule is established here.

## Qualification / Context
Spatial reference frame, observer/viewing point, target endpoint, time, configuration, measurement method, and Distance quantity/value may qualify an assertion.

## Core Distinctions
`viewing-distance` ≠ `focal-length`, `object-distance`, `field-of-view`, `angular-size`, or generic `distance`. Optical object distance belongs to a defined optical geometry; viewing distance belongs to a viewing relation.

## Inference Boundary
Do not infer focal length, field of view, angular size, object distance, or visual perception from this relation alone. The relation does not determine a Distance value unless one is separately established.

## Cross-Layer Significance
This relation connects spatial setup with Observer, Scene/Object, Display, and Distance semantics. Its specialized nature is why it is routed rather than admitted to the current conservative six-relation seed.

## Trust / Validation
Require identified endpoints and a defined spatial reference. Evidence may include experimental setup, display specifications, observation records, measurement records, or equivalent documentation.

## Machine / AI Interpretation
Treat as a specialized directed spatial predicate. Preserve endpoint identity, reference frame, qualification, and any associated Distance quantity/value. Do not promote the term to a general distance relation.

## Lifecycle
ROUTED — retained for future specialized semantic treatment; not deleted and not silently promoted to the current canonical seed.

## Retrieval Anchors
`viewing distance`, `viewing-distance`, `observation distance`, `viewing point`, `display viewing distance`, `distance`, `visual setup`

## Semantic Boundary
**Viewing Distance is a specialized spatial relation for separation between a viewing reference and viewed target. Its current routed status preserves the concept without expanding the conservative V3.1 canonical relation seed.**
