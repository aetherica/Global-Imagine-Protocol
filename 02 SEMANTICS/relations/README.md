# GIOP Canonical Relations

## Status
**CANONICAL — SCOPED V3.1 RELATION BATCH**

The `relations/` directory is the authoritative published GIOP semantic layer for reusable relation concepts admitted to the current V3.1 relation vocabulary.

## Purpose
The governing question is: **What typed semantic connection may hold between eligible participants?**

A Relation is a reusable canonical semantic concept specifying a typed connection between eligible entities, concepts, activities, processes, representations, or other semantic elements. A Relation is not itself a class, property, quantity, value, state, condition, activity, process, result, representation, or implementation claim.

## Canonical Relation Definition
**Relation is a reusable canonical semantic concept specifying a typed connection between eligible semantic participants.**

The canonical model is:
`RELATION CONCEPT → RELATION ASSERTION → OPTIONAL QUALIFICATION / CONTEXT`

An asserted relation may support inference only according to the canonical relation's declared characteristics and boundaries.

## Authoring Standard
`RELATION-AUTHORING-SPECIFICATION.md` defines the relation-specific canonical authoring pattern: identity, orientation, semantic contract, family, domain/range, direction, inverse, logical characteristics, qualification, distinctions, inference boundary, cross-layer significance, trust/evidence, machine interpretation, lifecycle, retrieval, and semantic boundary.

## Current Canonical Vocabulary
The current conservative V3.1 seed is exactly:
1. `part-of`
2. `participates-in`
3. `observes`
4. `represents`
5. `derived-from`
6. `has-result`

`has-result` provides the reusable output link from an Activity/Execution to a Result. It does not imply that every activity has one result or that every result is a measurement result.

## Routed / Specialized Concepts
`viewing-distance` (`SEM-RELATION-VIEWING-DISTANCE-001`) remains retained as a **ROUTED — SPECIALIZED RELATION CANDIDATE**. It is intentionally not part of the six-concept canonical seed because its primary responsibility is specialized spatial/viewing semantics and it requires reconciliation with the Spatial/Distance architecture.

This distinction is explicit:
`CANONICAL SEED ≠ EXHAUSTIVE RELATION KNOWLEDGE`.

Routed, deferred, conflicted, or specialized knowledge is retained and remains discoverable; it is not deleted merely because it is outside the current seed.

## Relation Concept vs Assertion
A canonical page defines a reusable relation concept. An instance assertion identifies subject, relation, and object and may carry assertion status, qualification, evidence, provenance, and inference status. Assertions do not belong in canonical relation concept pages.

## Directionality and Inverse
Direction is semantically significant where applicable. An inverse is the reversed semantic direction and does not automatically require a separate canonical concept page.

Current inverse expressions include `has-part`, `has-participant`, `is-observed-by`, `is-represented-by`, reverse provenance traversal, and `is-result-of`.

## Domain and Range
Each canonical relation declares eligible subject/domain and object/range positions. Examples do not establish domain/range, and domain/range do not imply that every eligible entity participates.

## Logical Characteristics and Inference
Logical characteristics such as symmetry, transitivity, reflexivity/irreflexivity, functionality, and inverse behaviour are semantic commitments, not decorative metadata. An unspecified characteristic is not silently treated as false. Validation constraints remain separate from ontology-level semantics.

## Qualification / Context
Assertions may require time, space, configuration, process stage, observation conditions, measurement context, provenance, or other qualification. Qualification does not create a new relation unless the underlying semantic responsibility changes.

## Cross-Layer Boundary
Relations connect semantic layers without absorbing their responsibilities. Examples:
`Camera → CLASS`
`Sensitivity → PROPERTY`
`Distance → QUANTITY`
`Temperature Condition → CONDITION`
`Calibration → ACTIVITY`
`Result → RESULT`
`Camera observes Scene → RELATION`
`Representation represents Scene → RELATION`
`Execution has-result Result → RELATION`
`Artifact derived-from Source Artifact → RELATION`

## Evidence / Trust
External standards, formal ontologies, provenance models, scientific literature, and domain practice provide evidence and design reference. They do not automatically become GIOP authority. Provenance, evidence, authority, validation status, confidence, and historical status remain differentiated.

## Machine / AI Interpretation
Machines must distinguish relation concept, assertion, subject/domain, object/range, direction, inverse, logical characteristics, qualification, asserted/inferred status, and provenance/evidence. Mention or co-occurrence alone does not create a relation assertion.

## Visitor Universe
There are no visitor-specific duplicate relation definitions. Novice, expert, and machine-facing visitors receive different entry depths into the same canonical relation: orientation → semantic contract/boundaries → formal logic, inference, assertion, provenance, and machine interpretation.

## Lifecycle
Canonical concepts follow Candidate → Authored → Integrated → Validated → Approved → Active Canonical under the applicable promotion gate. Scoped promotion is not universal approval for future relation concepts. Routed candidates remain retained and may later be promoted, specialized, or redirected through explicit decision.

## Completion Rule
A Relation semantic pass is complete when the authoring specification is established, the canonical index is synchronized, every admitted seed relation has a complete page, routed/deferred relation knowledge remains discoverable, and no relation knowledge has been silently discarded. The current six-concept seed satisfies the canonical vocabulary scope; specialized/routed relation work remains explicitly separated.
