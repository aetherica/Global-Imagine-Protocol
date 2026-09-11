# GIOP Facet Knowledge Registry

## Status

**CANONICAL RETENTION / AUDIT RECORD — V3.1**

## Purpose

This registry preserves recovered Facet knowledge, alternative terminology, structural candidates, unresolved classifications, and validated organizational-view decisions while separating evidence from canonical admission. It is a retention and decision layer, not a parallel Facet ontology.

## Governing Rule

No recovered Facet knowledge is discarded merely because it is not currently canonical in `02 SEMANTICS/facets/`.

`VERIFIED ≠ CANONICAL`

`DEFERRED ≠ DELETED`

`FILTERED ≠ DISCARDED`

Every retained candidate should have an explicit semantic type, epistemic status, canonical status, evidence/provenance, GIOP decision, destination, and reconsideration condition where applicable.

## Record Contract

Each record should expose, where applicable:

- stable registry ID;
- preferred term;
- recovered meaning;
- semantic/structural type;
- epistemic status;
- canonical status;
- scope/applicability;
- evidence/provenance;
- competing definitions or structures;
- GIOP semantic decision;
- primary destination;
- cross-layer references;
- reconsideration trigger.

## Canonical Seed Records

### FAC-001 — Facet

**Preferred term:** Facet  
**Semantic type:** FACET / KNOWLEDGE-ORGANIZATION CONSTRUCT  
**Epistemic status:** VERIFIED AS GIOP SYNTHESIS WITH STRONG EXTERNAL SUPPORT  
**Canonical status:** CANONICAL  
**Destination:** `02 SEMANTICS/facets/facet.md`

**Synthesized meaning:** A reusable canonical organizational construct that groups compatible canonical semantic concepts according to a coherent inherent category or declared organizing criterion without replacing or redefining their primary semantic identities.

**Boundary decision:** Facet is not Class, Property, Condition, State, Relation, Quantity, Activity, Process, Representation, Perception, Context, Visitor Universe, tag, or UI filter.

### FAC-002 — Characteristic of Division

**Preferred term:** Characteristic of Division  
**Semantic type:** STRUCTURAL FACET CONCEPT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** CANONICAL  
**Destination:** `02 SEMANTICS/facets/characteristic-of-division.md`

**Synthesized meaning:** The explicit criterion by which a defined conceptual scope is divided into distinguishable and comparable sibling concepts or arrays within a controlled facet organization.

**Boundary decision:** The criterion is organizational and is not automatically a Property, Relation, Context, or visitor classification.

## Structural / Methodological Records

### FAC-003 — Array

**Semantic type:** STRUCTURAL FACET CONSTRUCT  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** DEFERRED AS INDEPENDENT ENTRY  
**Destination:** `FACET-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** A structured set of sibling concepts resulting from application of a common characteristic of division.

**GIOP decision:** Retain as a first-class structural construct in the Facet organization model, but do not create a standalone canonical semantic page until independent semantic responsibility and retrieval need are demonstrated.

### FAC-004 — Facet Membership

**Semantic type:** ORGANIZATIONAL ASSERTION  
**Epistemic status:** VERIFIED / ARCHITECTURALLY SUPPORTED  
**Canonical status:** DEFERRED AS INDEPENDENT RELATION ENTRY  
**Destination:** `FACET-MEMBERSHIP-RULE.md`

**Recovered meaning:** An assertion that an existing canonical concept participates in a specified Facet or Array.

**GIOP decision:** Govern as an organizational assertion. Do not infer `is-a`, `part-of`, causal, observational, representational, measurement, or contextual semantics from membership.

### FAC-005 — Facet Analysis

**Semantic type:** METHODOLOGY / KNOWLEDGE-ORGANIZATION ANALYSIS  
**Epistemic status:** VERIFIED / STRONGLY SUPPORTED  
**Canonical status:** METHODOLOGICAL / NOT A FIRST-WAVE SEMANTIC ENTRY  
**Destination:** `FACET-ANALYSIS-SPECIFICATION.md`

**Recovered meaning:** Analytical method for identifying coherent organizing dimensions, division criteria, arrays, and memberships.

**GIOP decision:** Keep as specification methodology. Do not create `facet-analysis.md` unless later analysis establishes an independent semantic responsibility that cannot be represented as methodology.

## Validated Organizational Views

### FAC-VIEW-026 — Imaging-System Role View

**Semantic type:** VALIDATED ORGANIZATIONAL VIEW  
**Canonical status:** VALIDATED VIEW / NOT INDEPENDENT SEMANTIC ENTRY  
**Destination:** `02 SEMANTICS/facets/FACET-ORGANIZATION-CATALOG.md`

**Scope:** Existing canonical Class concepts.  
**Division criterion:** Functional role in an imaging system/environment.

**Decision:** Valid organizational use of existing Class identities. Does not replace the Class layer or create a part-whole model.

### FAC-VIEW-027 — Imaging-Characteristic Domain View

**Semantic type:** VALIDATED ORGANIZATIONAL VIEW  
**Canonical status:** VALIDATED VIEW / NOT INDEPENDENT SEMANTIC ENTRY  
**Destination:** `02 SEMANTICS/facets/FACET-ORGANIZATION-CATALOG.md`

**Scope:** Current canonical Property concepts.  
**Division criterion:** Principal imaging behavior or characteristic family.

**Decision:** Valid organizational use of existing Property identities. Does not redefine Properties or imply shared units, procedures, or applicability.

### FAC-VIEW-028 — Contextual-Frame Use View

**Semantic type:** VALIDATED ORGANIZATIONAL VIEW  
**Canonical status:** VALIDATED VIEW / NOT INDEPENDENT SEMANTIC ENTRY  
**Destination:** `02 SEMANTICS/facets/FACET-ORGANIZATION-CATALOG.md`

**Scope:** Canonical Context concepts with established status.  
**Division criterion:** Principal use or situational purpose of the contextual frame.

**Decision:** Valid for canonical Context members. Candidate Contexts remain excluded until their owning layer promotes them.

### FAC-VIEW-029 — Relation-Function View

**Semantic type:** VALIDATED ORGANIZATIONAL VIEW  
**Canonical status:** VALIDATED VIEW / NOT INDEPENDENT SEMANTIC ENTRY  
**Destination:** `02 SEMANTICS/facets/FACET-ORGANIZATION-CATALOG.md`

**Scope:** Current canonical Relation seed vocabulary.  
**Division criterion:** Primary semantic function of the relation concept.

**Decision:** Valid organizational use of existing Relation identities. Does not alter directionality, logical characteristics, domain/range, qualification, or inference semantics.

## Deferred Organizational Terms

### FAC-006 — Hierarchy

**Semantic type:** STRUCTURAL ORGANIZATION  
**Canonical status:** DEFERRED

A hierarchy may occur within a Facet organization but is not synonymous with Facet. Existing semantic broader/narrower structures must not be duplicated merely for navigation.

### FAC-007 — Guide Term

**Semantic type:** ORGANIZATIONAL / PRESENTATION STRUCTURE  
**Canonical status:** DEFERRED

Retained because mature thesauri and vocabularies use guide terms to organize or label conceptual sections. It is not automatically a GIOP semantic concept.

### FAC-008 — Node Label

**Semantic type:** ORGANIZATIONAL / PRESENTATION STRUCTURE  
**Canonical status:** DEFERRED

Retained as a structural labeling mechanism. It must not be treated as primary semantic authority without separate justification.

### FAC-009 — Facet Indicator

**Semantic type:** CLASSIFICATION NOTATION / STRUCTURAL DEVICE  
**Canonical status:** DEFERRED

Retained as classification terminology rather than a first-wave semantic entry.

### FAC-010 — Facet Scheme

**Semantic type:** ORGANIZATION-SYSTEM CONSTRUCT  
**Canonical status:** DEFERRED

Requires a separate decision about whether GIOP needs a canonical scheme object or whether organization schemes remain specification/runtime structures.

### FAC-011 — Concept Group

**Semantic type:** GENERAL GROUPING CONSTRUCT  
**Canonical status:** DEFERRED

A Concept Group does not automatically satisfy the stronger coherence and division-criterion requirements of a Facet.

### FAC-012 — Concept Scheme

**Semantic type:** KNOWLEDGE-ORGANIZATION / EXTERNAL MODEL CONSTRUCT  
**Canonical status:** DEFERRED

Retained for interoperability analysis; not automatically a GIOP Facet semantic concept.

## Domain-Specific Candidates

### FAC-CAND-013 — Spatial Facet

**Status:** DEFERRED

Requires comparison against the future spatial semantic layer and against spatial relations/quantities. Spatial organization must not become a duplicate spatial ontology.

### FAC-CAND-014 — Temporal Facet

**Status:** DEFERRED

Requires comparison against the future temporal semantic layer and temporal relations/quantities.

### FAC-CAND-015 — Modality Facet

**Status:** DEFERRED

Requires comparison against the existing `modalities/` semantic responsibility.

### FAC-CAND-016 — Measurement Facet

**Status:** DEFERRED

Requires separation from measurement activities, quantities, measuring systems, conditions, and contexts.

### FAC-CAND-017 — Domain Facet

**Status:** DEFERRED

Requires distinction from Domain Context and general Concept Group semantics.

### FAC-CAND-018 — Application Facet

**Status:** DEFERRED

Requires distinction from Application Context and application-specific workflow organization.

### FAC-CAND-019 — Capture Facet

**Status:** DEFERRED

Requires distinction from Capture Context and future capture/system semantics.

### FAC-CAND-020 — Processing Facet

**Status:** DEFERRED

Requires distinction from Processing Context and process/activity semantics.

### FAC-CAND-021 — Operational Facet

**Status:** DEFERRED

Requires distinction from Operational Context and operational workflow semantics.

### FAC-CAND-022 — Optical Facet

**Status:** DEFERRED

Requires audit against optics-related classes, properties, conditions, quantities, and future domain organization.

### FAC-CAND-023 — Environmental Facet

**Status:** DEFERRED

Requires audit against Conditions and Contexts to avoid semantic duplication.

### FAC-CAND-024 — Representation Facet

**Status:** DEFERRED

Requires comparison against the canonical Representation layer.

### FAC-CAND-025 — Perception Facet

**Status:** DEFERRED

Requires comparison against the canonical/future Perception layer.

## Decision Rules

A candidate must not become canonical merely because:

- an external vocabulary uses the term;
- a user interface benefits from it;
- visitors search for it;
- a vendor uses it;
- it creates a convenient folder;
- it resembles a known facet label.

Canonical admission requires semantic responsibility, evidence, coherent division logic, cross-layer boundary analysis, GIOP synthesis, and validation.

## Visitor Universe Relevance

Visitor relevance is retained as access guidance rather than semantic identity.

Facet organization can serve different entry depths:

- general visitors use facets for discovery;
- learners use them to understand conceptual organization;
- practitioners use them to navigate related knowledge;
- engineers and scientists inspect division criteria and membership boundaries;
- standards and metrology users inspect evidence and controlled organization;
- AI, data, API, and system consumers resolve stable IDs and membership structures.

No visitor category is itself a Facet semantic type.

## Reconsideration Triggers

Revisit a deferred candidate when:

1. a distinct reusable organizational responsibility is demonstrated;
2. cross-layer duplication has been ruled out;
3. a stable machine-retrievable identity is required;
4. multiple validated arrays depend on the same organizing construct;
5. current specification treatment becomes insufficient for canonical interoperability;
6. new evidence materially changes the GIOP synthesis.

## Retention Principle

The registry preserves alternative classifications and deferred structures so that later GIOP layers can reuse evidence without repeating the entire research process. Registry retention does not make a candidate canonical.
