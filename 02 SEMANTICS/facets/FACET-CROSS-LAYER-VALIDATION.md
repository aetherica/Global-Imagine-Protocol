# GIOP V3.1 — Facet Cross-Layer Validation

## Status

**CANONICAL — V3.1 CROSS-LAYER VALIDATION RECORD**

## Purpose

This record validates the current `facets/` semantic nucleus against the established GIOP semantic layers that existed before Facet authoring:

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
| Facet vs Context | PASS with status correction | Context remains authoritative for situational frames. `Capture Context` must be labelled as a candidate wherever referenced because `contexts/README.md` has not yet promoted it to canonical status. |
| Facet vs Condition/State | PASS | Facet organization does not assert physical circumstance, state, or status. |
| Characteristic of Division vs Property | PASS | The division criterion organizes concepts; it does not become an attributable property merely because a property may sometimes supply the criterion. |
| Characteristic of Division vs Relation | PASS | A division criterion is organizational logic, not a typed connection assertion. |
| Membership vs `is-a` | PASS | Membership rule explicitly prevents inference of semantic classification from Facet membership. |
| Membership vs `part-of` | PASS | Membership rule explicitly prevents part-whole inference. |
| Membership vs Context containment | PASS | Membership does not place a concept inside a contextual frame. |
| Visitor Universe vs Facet | PASS after entry cleanup | Visitor Universe remains a consumption/navigation framework and is not semantic payload for the Facet concept. |
| Domain-specific Facets | DEFERRED | Spatial, temporal, modality, measurement, domain, application, capture, processing, operational, optical, environmental, representation, and perception Facets remain candidates pending ownership validation. |
| Duplicate ontology risk | PASS | The Facet rules explicitly require existing canonical identities to remain authoritative. |
| Registry boundary | PASS | Retained candidates and competing classifications remain in the registry rather than being promoted by convenience. |

## Detailed Findings

### 1. Classes Boundary

The Class layer answers:

> What kind of entity is this?

The Facet layer answers an organizational question about already established semantic identities. For example, `Camera` remains owned by `classes/camera.md`; a future Facet may organize Camera with other canonical concepts but must not redefine Camera as a Facet member type.

**Decision:** No class concept is being displaced by the current Facet nucleus.

### 2. Properties Boundary

The Property layer defines reusable attributable characteristics. A Property may sometimes supply a useful organizational dimension, but the organizational construct is still the Facet and the property remains the semantic owner.

The current Facet model therefore preserves the distinction:

```text
PROPERTY → characteristic
FACET → organizational construct
CHARACTERISTIC OF DIVISION → organizing criterion
```

**Decision:** No Property identity is duplicated by the current Facet nucleus.

### 3. Relations Boundary

The Relation layer defines typed semantic connections and their assertions. Facet Membership instead records that an existing concept participates in an organizational structure.

The current V3.1 rule intentionally does not promote `Facet Membership` to a standalone canonical Relation. This prevents the organization layer from quietly acquiring relation semantics.

**Decision:** Keep Facet Membership organizational unless future independent relation analysis establishes a separate semantic responsibility.

### 4. Context Boundary

The Context layer defines reusable situational frames. Facet organization does not create contextual containment merely because a Context is indexed or grouped by a Facet.

The current Context layer distinguishes canonical entries from candidate entries. In particular:

- `measurement-context` is canonical;
- `viewing-context` is canonical;
- `capture-context` remains a **CANONICAL CANDIDATE — V3.1 SEED**;
- `processing-context` remains a **CANONICAL CANDIDATE — V3.1 SEED**;
- `operational-context` remains a **CANONICAL CANDIDATE — V3.1 SEED**.

Therefore Facet documentation must never present candidate Context entries as if they were already canonical authorities.

**Decision:** Preserve Context-layer status exactly; Facet references to candidate contexts must carry candidate qualification.

### 5. Visitor Universe Boundary

Foundation architecture treats Visitor Universe as an access/navigation framework over canonical knowledge, not as additional semantic payload. Ordinary canonical entries should therefore not invent a separate semantic `Visitor Universe` section when entry depth can be expressed through the canonical content structure itself.

The existing Facet entries contained explicit `Visitor Universe and Entry Depth` sections. This validation identifies that presentation as unnecessary duplication of the established entry-depth rule.

**Decision:** Remove the separate Visitor Universe sections from `facet.md` and `characteristic-of-division.md`. Keep entry-depth implications implicit in the canonical content structure and retain Visitor Universe language only where needed to clarify the architecture or machine-consumption boundary.

### 6. Domain-Specific Facet Candidates

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

The current V3.1 Facet nucleus is **SEMANTICALLY VALID FOR CONTINUED USE**, subject to the two documentation corrections recorded above:

1. remove standalone Visitor Universe sections from ordinary Facet semantic entries;
2. preserve candidate status when referencing non-canonical Context entries, especially `capture-context`.

No redesign of `classes/`, `properties/`, `relations/`, or `contexts/` is required by this validation.

## Next Controlled Step

After these corrections, the next Facet-specific work should be validation of concrete organizational examples and candidate facet membership against real canonical concepts. Domain-specific Facet admission should occur only after those membership examples demonstrate:

```text
SCOPE
→ CHARACTERISTIC OF DIVISION
→ COMPARABLE SIBLINGS
→ EXISTING CANONICAL IDENTITIES
→ EVIDENCE
→ MEMBERSHIP DECISION
→ VALIDATION
```

This record does not itself admit any deferred domain-specific Facet as canonical.

## Change History

- V3.1 — Initial cross-layer validation completed after the Facet semantic nucleus was authored.
