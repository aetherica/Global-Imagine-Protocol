# GIOP V3.1 — Facet Cross-Layer Validation

## Status

**CANONICAL — V3.1 CROSS-LAYER VALIDATION RECORD**

## Purpose

This record validates the current `facets/` semantic nucleus and its concrete organizational views against the established GIOP semantic layers that existed before Facet authoring:

- `classes/`
- `properties/`
- `relations/`
- `contexts/`
- Foundation canonicalization and entry-depth rules

The purpose is not to redesign those layers. It is to verify that the Facet layer organizes existing canonical knowledge without taking semantic ownership from another layer, duplicating an existing identity, or converting visitor/navigation concepts into semantic meaning.

## Validation Scope

Current Facet canonical nucleus:

- `SEM-FACET-GENERIC-001` — Facet
- `SEM-FACET-DIVISION-001` — Characteristic of Division

Current Facet structural/methodological vocabulary reviewed:

- Array
- Facet Membership
- Facet Analysis
- Hierarchy
- Guide Term
- Node Label
- Facet Indicator
- Facet Scheme
- Concept Scheme
- Concept Group

Current validated organizational views:

- `FACET-VIEW-IMAGING-SYSTEM-ROLE-001`
- `FACET-VIEW-IMAGING-CHARACTERISTIC-001`
- `FACET-VIEW-CONTEXTUAL-FRAME-USE-001`
- `FACET-VIEW-RELATION-FUNCTION-001`

The review also checks the domain-specific candidates listed in `FACET-INDEX.md` against current semantic ownership.

## Governing Cross-Layer Rule

```text
PRIMARY SEMANTIC IDENTITY
        ↓
PRIMARY SEMANTIC AUTHORITY
        ↓
OPTIONAL FACET ORGANIZATION
        ↓
FACET / ARRAY MEMBERSHIP
```

Facet organization is a secondary organizational view. It must not become a competing semantic authority.

## Validation Matrix

| Check | Result | Finding |
|---|---|---|
| Facet vs Class | PASS | `classes/` defines entity kinds; `facets/` organizes already identified concepts. |
| Facet vs Property | PASS | `properties/` remains authoritative for attributable characteristics; Facet may organize them but does not redefine them. |
| Facet vs Relation | PASS | Facet Membership is explicitly treated as an organizational assertion, not as a physical, causal, observational, representational, or other relation. |
| Facet vs Context | PASS | Context remains authoritative for situational frames. Candidate Contexts are explicitly qualified wherever referenced. |
| Facet vs Condition/State | PASS | Facet organization does not assert physical circumstance, state, or status. |
| Characteristic of Division vs Property | PASS | The division criterion organizes concepts; it does not become an attributable property merely because a property may sometimes supply the criterion. |
| Characteristic of Division vs Relation | PASS | A division criterion is organizational logic, not a typed connection assertion. |
| Membership vs `is-a` | PASS | Membership rule explicitly prevents inference of semantic classification from Facet membership. |
| Membership vs `part-of` | PASS | Membership rule explicitly prevents part-whole inference. |
| Membership vs Context containment | PASS | Membership does not place a concept inside a contextual frame. |
| Visitor Universe vs Facet | PASS | Visitor Universe remains a consumption/navigation framework and is not semantic payload for the Facet concept. |
| Concrete organization views | PASS | Four views apply explicit scopes and division criteria to existing canonical identities without creating replacement semantic authority. |
| Candidate preservation | PASS | `capture-context`, `processing-context`, and `operational-context` remain qualified as Context candidates. |
| Domain-specific Facets | DEFERRED | Spatial, temporal, modality, measurement, domain, application, capture, processing, operational, optical, environmental, representation, and perception Facets remain candidates pending ownership validation. |
| Duplicate ontology risk | PASS | The Facet rules explicitly require existing canonical identities to remain authoritative. |
| Registry boundary | PASS | Retained candidates and competing classifications remain in the registry rather than being promoted by convenience. |

## Detailed Findings

### 1. Classes Boundary

The Class layer answers:

> What kind of entity is this?

The Facet layer answers an organizational question about already established semantic identities. The validated Imaging-System Role View demonstrates this distinction by organizing existing Classes according to functional role without redefining those Classes.

**Decision:** No class concept is being displaced by the current Facet nucleus or its organization views.

### 2. Properties Boundary

The Property layer defines reusable attributable characteristics. A Property may supply a useful organizational dimension, but the organizational construct is still the Facet and the Property remains the semantic owner.

The validated Imaging-Characteristic Domain View preserves:

```text
PROPERTY → characteristic
FACET → organizational construct
CHARACTERISTIC OF DIVISION → organizing criterion
```

**Decision:** No Property identity is duplicated.

### 3. Relations Boundary

The Relation layer defines typed semantic connections and their assertions. Facet Membership instead records participation in an organizational structure.

The validated Relation-Function View organizes the existing five canonical Relation concepts by primary semantic function without modifying directionality, domain/range, logical characteristics, or inference behavior.

**Decision:** Keep Facet Membership organizational unless future independent relation analysis establishes a separate semantic responsibility.

### 4. Context Boundary

The Context layer defines reusable situational frames. Facet organization does not create contextual containment merely because a Context is indexed or grouped by a Facet.

Established canonical Context members used in the validated Contextual-Frame Use View remain separately authoritative. Candidate Context entries remain excluded from established membership where their owning layer has not yet promoted them.

In particular:

- `measurement-context` is canonical;
- `viewing-context` is canonical;
- `assessment-context` is canonical;
- `application-context` is canonical;
- `domain-context` is canonical;
- `capture-context` remains a **CANONICAL CANDIDATE — V3.1 SEED**;
- `processing-context` remains a **CANONICAL CANDIDATE — V3.1 SEED**;
- `operational-context` remains a **CANONICAL CANDIDATE — V3.1 SEED**.

**Decision:** Preserve Context-layer status exactly; candidate contexts cannot silently acquire canonical Facet authority.

### 5. Visitor Universe Boundary

Foundation architecture treats Visitor Universe as an access/navigation framework over canonical knowledge, not as additional semantic payload. The ordinary Facet semantic entries have been cleaned accordingly.

Entry depth remains a property of canonical content consumption rather than a separate semantic definition or visitor-specific ontology.

**Decision:** No separate Visitor Universe semantic field is required in ordinary Facet entries.

### 6. Concrete Organization Validation

Each concrete view in `FACET-ORGANIZATION-CATALOG.md` satisfies the required chain:

```text
SCOPE
→ CHARACTERISTIC OF DIVISION
→ COMPARABLE MEMBERS / ARRAYS
→ EXISTING CANONICAL IDENTITIES
→ BOUNDARY TEST
→ VALIDATION DECISION
```

#### Imaging-System Role View

Organizes Classes according to functional role in an imaging system/environment. It does not assert subclassing or part-whole relations.

#### Imaging-Characteristic Domain View

Organizes canonical Properties according to principal imaging characteristic domain. It does not assert shared units, procedures, bearers, or numerical behavior.

#### Contextual-Frame Use View

Organizes established canonical Contexts according to principal use or situational purpose. It does not create Context subclass semantics.

#### Relation-Function View

Organizes canonical Relations according to their primary semantic function. It does not alter assertion semantics, directionality, logical characteristics, or inference rules.

**Decision:** All four views are validated as organizational constructs and are not admitted as four additional canonical Facet semantic concepts.

### 7. Domain-Specific Facet Candidates

The following remain deferred:

- Spatial Facet
- Temporal Facet
- Modality Facet
- Measurement Facet
- Domain Facet
- Application Facet
- Capture Facet
- Processing Facet
- Operational Facet
- Optical Facet
- Environmental Facet
- Representation Facet
- Perception Facet

Their usefulness for browsing is not sufficient for canonical admission. Each requires a characteristic-of-division analysis and a check against current or future semantic authority.

## Validation Decision

The current V3.1 Facet layer is **SEMANTICALLY VALID FOR CONTINUED USE**.

The Facet semantic nucleus remains intentionally compact at two canonical concepts:

1. Facet;
2. Characteristic of Division.

Concrete organizational behavior is now demonstrated through four validated organizational views over existing canonical knowledge. This provides operational evidence of the Facet construct without inflating the semantic ontology.

No redesign of `classes/`, `properties/`, `relations/`, or `contexts/` is required by this validation.

## Next Controlled Boundary

The Facet layer is not yet authorized to promote any deferred domain-specific Facet merely because a concrete view exists. Promotion requires independent semantic responsibility, stronger evidence, cross-layer analysis, and a demonstrated need for a stable canonical identity beyond the organization itself.

This record therefore closes the current concrete-organization validation step without converting domain-specific candidates into canonical semantic entries.

## Change History

- V3.1 — Initial cross-layer validation completed after the Facet semantic nucleus was authored.
- V3.1 — Concrete organizational views validated and recorded without expanding the canonical semantic nucleus.
