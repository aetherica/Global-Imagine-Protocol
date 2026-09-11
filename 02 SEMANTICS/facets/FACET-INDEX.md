# GIOP V3.1 — Facet Index

## Status

**CANONICAL — V3.1 FACET ORGANIZATION INDEX**

## Purpose

This index identifies the current canonical Facet organization vocabulary and records the status of related structural, methodological, candidate, and validated organizational-view terms. It is an index, not a substitute for the authoritative semantic entries.

## Canonical V3.1 Seed

| ID | Preferred Name | Type | Status | Authority |
|---|---|---|---|---|
| `SEM-FACET-GENERIC-001` | Facet | FACET | CANONICAL | `facet.md` |
| `SEM-FACET-DIVISION-001` | Characteristic of Division | STRUCTURAL FACET CONCEPT | CANONICAL | `characteristic-of-division.md` |

## Structural Constructs

| Term | V3.1 treatment | Reason |
|---|---|---|
| Array | Structural construct | Resulting sibling grouping under a common division criterion; independent semantic entry deferred |
| Facet Membership | Organizational assertion | Connects existing canonical identities to a Facet/Array without transferring semantic authority |
| Hierarchy | Structural organization | May occur within a facet organization; not duplicated as a Facet semantic entry |
| Facet Scheme | Organization-system construct | Requires separate validation before independent canonicalization |
| Concept Scheme | External/organization model | Not automatically a GIOP Facet concept |
| Concept Group | General grouping construct | Does not automatically satisfy Facet criteria |

## Methodological Construct

| Term | V3.1 treatment | Reason |
|---|---|---|
| Facet Analysis | Specification/methodology | Analytical process for identifying dimensions, division criteria, arrays, and memberships; not a first-wave semantic entry |

## Presentation / Classification Vocabulary

| Term | V3.1 treatment | Reason |
|---|---|---|
| Guide Term | Deferred | Organizational/display device; not automatically an independent semantic concept |
| Node Label | Deferred | Structural labeling mechanism; not primary semantic authority |
| Facet Indicator | Deferred | Classification notation/device |

## Validated Organizational Views

Concrete reusable organizations are published in `FACET-ORGANIZATION-CATALOG.md`. They are validated organizational views over existing canonical identities, not four new canonical Facet semantic concepts.

| View ID | Organization | Principal Scope | Status |
|---|---|---|---|
| `FACET-VIEW-IMAGING-SYSTEM-ROLE-001` | Imaging-System Role View | Classes | VALIDATED ORGANIZATIONAL VIEW |
| `FACET-VIEW-IMAGING-CHARACTERISTIC-001` | Imaging-Characteristic Domain View | Properties | VALIDATED ORGANIZATIONAL VIEW |
| `FACET-VIEW-CONTEXTUAL-FRAME-USE-001` | Contextual-Frame Use View | Canonical Contexts | VALIDATED ORGANIZATIONAL VIEW |
| `FACET-VIEW-RELATION-FUNCTION-001` | Relation-Function View | Canonical Relations | VALIDATED ORGANIZATIONAL VIEW |

These views demonstrate concrete Facet operation while preserving the two-concept canonical semantic nucleus.

## Domain-Specific Candidates

The following remain candidates and are not admitted as independent V3.1 canonical Facet entries:

- Spatial Facet;
- Temporal Facet;
- Modality Facet;
- Measurement Facet;
- Domain Facet;
- Application Facet;
- Capture Facet;
- Processing Facet;
- Operational Facet;
- Optical Facet;
- Environmental Facet;
- Representation Facet;
- Perception Facet.

Each candidate must first be checked against the semantic authority of existing and future layers. A domain term is not a Facet merely because it is useful as a navigation label.

## Cross-Layer Authority Examples

| Canonical concept | Primary authority | Facet role |
|---|---|---|
| Camera | `classes/camera.md` | May participate in a technical or other validated organization |
| Spectral Response | `properties/spectral-response.md` | Participates in the validated Imaging-Characteristic Domain View |
| Measurement Context | `contexts/measurement-context.md` | Participates in the validated Contextual-Frame Use View |
| Viewing Context | `contexts/viewing-context.md` | Participates in the validated Contextual-Frame Use View |
| Capture Context (candidate) | `contexts/capture-context.md` | Candidate only; not treated as canonical membership until Context-layer promotion |

These examples illustrate membership and organization, not creation of a second semantic authority.

## Admission Rule

A candidate becomes canonical only after:

1. semantic identity is resolved;
2. existing canonical identities are checked;
3. semantic responsibility is assigned;
4. evidence is assessed;
5. conflicting classifications are retained and reconciled where possible;
6. GIOP synthesis establishes a distinct organizational construct;
7. cross-layer authority is preserved;
8. validation passes.

## Visitor Universe View

This index does not encode visitor-specific semantic identities. Visitor Universe uses the index as a navigation surface over the same canonical knowledge.

A novice may use the index to discover a concept; a professional may use it to inspect organizational structure; a specialist may trace division criteria and membership; a machine may resolve IDs and relationships. None receives a different semantic definition.

## Retrieval Anchors

`FACET`, `CHARACTERISTIC OF DIVISION`, `ARRAY`, `FACET MEMBERSHIP`, `FACET ANALYSIS`, `FACET ORGANIZATION`, `PRIMARY SEMANTIC AUTHORITY`, `ORGANIZING DIMENSION`, `DIVISION CRITERION`, `SIBLING ARRAY`, `MEMBERSHIP`, `VALIDATED ORGANIZATIONAL VIEW`, `VISITOR UNIVERSE`, `ENTRY DEPTH`.
