# GIOP Relation Research — Retained Candidate Registry

## Purpose

This registry preserves recovered Relation knowledge while separating semantic classification, evidential status, and canonical admission to `02 SEMANTICS/relations/` or another semantic destination.

This file is a retention and decision record. It is **not** the canonical Relation vocabulary.

GIOP governing rule:

> **Knowledge must not be discarded merely because it is not currently canonical in the Relation layer. It must be retained, classified, verified or marked uncertain, and routed to the appropriate semantic destination.**

## Recovery and Routing Pipeline

`SOURCE → RECOVERED KNOWLEDGE → REGISTRY → CLASSIFY → EVIDENCE ASSESSMENT → VERIFY → CONFLICT / RECONCILIATION → SEMANTIC SYNTHESIS → CATEGORY ASSIGNMENT → CANONICAL DECISION → PRIMARY SEMANTIC ENTRY + CROSS-LAYER REFERENCE`

## Retained Candidate Index

| Preferred Term | Epistemic Status | Semantic Type | Canonical Status | Family | Destination / Decision |
|---|---|---|---|---|---|
| `part-of` | VERIFIED | RELATION | CANONICAL | Structural / Partitive | `relations/part-of.md` |
| `participates-in` | VERIFIED | RELATION | CANONICAL | Participation | `relations/participates-in.md` |
| `observes` | VERIFIED | RELATION | CANONICAL | Observation | `relations/observes.md` |
| `represents` | VERIFIED | RELATION | CANONICAL | Representation | `relations/represents.md` |
| `derived-from` | VERIFIED | PROVENANCE RELATION | CANONICAL | Provenance / Lineage | `relations/derived-from.md` |
| `component-of` | UNDER VERIFICATION | SPECIALIZED RELATION | DEFERRED | Component / System | Future relation specialization; distinguish from `part-of` |
| `has-component` | UNDER VERIFICATION | SPECIALIZED RELATION | DEFERRED | Component / System | Inverse/specialization analysis pending |
| `uses` | VERIFIED | RELATION | DEFERRED | Operational / Usage | Future relations semantics; broad cross-layer boundary |
| `used-by` | UNDER VERIFICATION | RELATION | DEFERRED | Operational / Usage | Inverse semantics pending |
| `depends-on` | VERIFIED | RELATION | DEFERRED | Dependency | Future relation semantics; dependency types require distinction |
| `has-dependency` | UNDER VERIFICATION | RELATION | DEFERRED | Dependency | Inverse semantics pending |
| `measures` | VERIFIED | RELATION / MEASUREMENT RELATION | DEFERRED | Measurement | Future measurement semantics; distinguish from `observes` and measurement activity |
| `measured-by` | UNDER VERIFICATION | RELATION / MEASUREMENT RELATION | DEFERRED | Measurement | Inverse semantics pending |
| `located-in` | VERIFIED | SPATIAL RELATION | ROUTED ELSEWHERE | Spatial | Future `spatial/` semantic destination |
| `contains` | VERIFIED | SPATIAL RELATION | ROUTED ELSEWHERE | Spatial | Future `spatial/`; structural containment must remain distinct |
| `overlaps` | VERIFIED | SPATIAL RELATION | ROUTED ELSEWHERE | Spatial | Future `spatial/` |
| `touches` | VERIFIED | SPATIAL RELATION | ROUTED ELSEWHERE | Spatial | Future `spatial/` |
| `within` | VERIFIED | SPATIAL RELATION | ROUTED ELSEWHERE | Spatial | Future `spatial/` |
| `before` | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/` |
| `after` | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/` |
| `during` | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/` |
| `meets` | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/` |
| `overlaps` (temporal) | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/`; disambiguate from spatial `overlaps` |
| `starts` | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/` |
| `finishes` | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/` |
| `equals` (temporal) | VERIFIED | TEMPORAL RELATION | ROUTED ELSEWHERE | Temporal | Future `temporal/`; identity/equality boundary required |
| `causes` | VERIFIED | CAUSAL RELATION | DEFERRED | Causal / Influence | Future causal semantics; avoid collapsing provenance into causation |
| `affects` | VERIFIED | CAUSAL / INFLUENCE RELATION | DEFERRED | Causal / Influence | Future causal/influence semantics |
| `influences` | UNDER VERIFICATION | CAUSAL / INFLUENCE RELATION | DEFERRED | Causal / Influence | Boundary with `affects` pending |
| `same-as` | VERIFIED | IDENTITY RELATION | ROUTED ELSEWHERE | Identity / Equivalence | Future `identity/` semantics |
| `equivalent-to` | VERIFIED | IDENTITY / EQUIVALENCE RELATION | ROUTED ELSEWHERE | Identity / Equivalence | Future `identity/`; equivalence vs identity boundary |
| `corresponds-to` | VERIFIED | ASSOCIATIVE / CORRESPONDENCE RELATION | DEFERRED | Correspondence | Future correspondence semantics |
| `related-to` | VERIFIED | ASSOCIATIVE RELATION | DEFERRED | Associative | Broad fallback relation; must not replace specific relations |
| `associated-with` | VERIFIED | ASSOCIATIVE RELATION | DEFERRED | Associative | Broad associative relation; scope pending |
| `was-generated-by` | VERIFIED | PROVENANCE RELATION | ROUTED ELSEWHERE | Provenance / Generation | Future provenance semantics; related to `derived-from` |
| `was-attributed-to` | VERIFIED | PROVENANCE RELATION | ROUTED ELSEWHERE | Provenance / Attribution | Future provenance semantics |
| `was-associated-with` | VERIFIED | PROVENANCE RELATION | ROUTED ELSEWHERE | Provenance / Association | Future provenance semantics |
| `has-source` | UNDER VERIFICATION | PROVENANCE RELATION | DEFERRED | Provenance / Source | Direction and redundancy with `derived-from` pending |
| `has-input` | VERIFIED | RELATION | DEFERRED | Process / Input | Future process/activity relation; distinguish from `uses` |
| `has-output` | VERIFIED | RELATION | DEFERRED | Process / Output | Future process/activity relation |
| `has-observer` | VERIFIED | RELATION | DEFERRED | Observation | Inverse/qualified observation structure pending |
| `observed-by` | VERIFIED | RELATION | DEFERRED | Observation | Inverse terminology; current canonical concept is `observes` |
| `represents` | VERIFIED | RELATION | CANONICAL | Representation | `relations/represents.md`; retained here for audit completeness |
| `is-represented-by` | VERIFIED | RELATION | DEFERRED | Representation | Inverse terminology; no separate canonical page required |

## Semantic Classification Rules

### Structural relations

Structural relations describe constitution or composition. `part-of` is the current canonical seed. More specialized component/system relations remain retained until their semantic distinction is stable.

### Participation relations

Participation connects entities to activities, processes, events, or occurrences. `participates-in` is canonical. Role-specific participation can later be specialized without redefining generic participation.

### Observation relations

Observation connects an observer to an observed target. `observes` is canonical. Measurement-specific relations remain distinct and deferred.

### Representation relations

Representation connects a representation to its referent. `represents` is canonical. Inverse and specialized representational relations remain retained.

### Provenance relations

`derived-from` is canonical for derivational lineage. More qualified provenance relations such as generation and attribution are retained for a future provenance treatment.

### Operational and dependency relations

`uses` and `depends-on` are technically important but broad. They remain retained until GIOP can define precise domain/range, qualification, inference, and cross-layer boundaries without semantic inflation.

### Measurement relations

`measures` is retained as measurement-oriented relation knowledge. It must remain distinct from the measurement activity itself, measurement result, quantity, and general observation.

### Spatial relations

Spatial relations such as `located-in`, `contains`, `overlaps`, `touches`, and `within` are retained and routed toward a dedicated spatial semantic layer. The same English label can have different semantics in spatial and non-spatial contexts; canonical IDs must disambiguate them.

### Temporal relations

Temporal relations such as `before`, `after`, `during`, `meets`, `overlaps`, `starts`, and `finishes` are retained and routed toward a dedicated temporal semantic layer. Temporal `overlaps` must not be confused with spatial `overlaps`.

### Causal and influence relations

`causes`, `affects`, and `influences` are retained. Provenance or derivation must not be silently interpreted as generic causation.

### Identity and equivalence relations

`same-as`, `equivalent-to`, and `corresponds-to` are retained for a future identity/equivalence treatment. Identity, logical equivalence, and correspondence are not assumed to be interchangeable.

### Associative relations

`related-to` and `associated-with` are retained as broad associative concepts. They must not be used as substitutes for a more specific canonical relation when the specific relation is known.

## Evidence and Provenance

The relation corpus is informed by formal and technical sources including RDF/OWL relation modeling, OBO Relation Ontology, SKOS relation patterns, W3C PROV-O provenance relations, ISO terminology relation traditions, OGC GeoSPARQL spatial relations, and Allen interval temporal relations.

These sources provide evidence and modeling patterns. They do not automatically become GIOP canonical semantics.

## Conflict and Open-Question Policy

A candidate may remain `UNDER VERIFICATION` or `CONFLICTED` when credible evidence supports materially different semantic interpretations.

Examples requiring explicit reconciliation include:

- `part-of` vs `component-of`;
- structural `contains` vs spatial `contains`;
- spatial vs temporal `overlaps`;
- `derived-from` vs causal `causes`;
- `observes` vs measurement-specific `measures`;
- `same-as` vs `equivalent-to` vs `corresponds-to`;
- broad `uses` vs process-specific input/output relations.

Unresolved questions remain visible. They are not silently converted into canonical assertions.

## Machine Interpretation

Every retained candidate must be machine-distinguishable by at least:

- preferred term;
- stable GIOP identifier when assigned;
- epistemic status;
- semantic type;
- family;
- canonical status;
- evidence/provenance;
- conflicts/open questions;
- GIOP decision;
- destination.

`NON-CANONICAL`, `DEFERRED`, `ROUTED ELSEWHERE`, and `UNDER VERIFICATION` do not mean `FALSE`.

## Completion / Retention State

The current V3.1 Relation layer has a complete canonical seed of five relation concepts. The broader recovered Relation corpus is retained in this registry and remains eligible for future semantic routing and promotion.

No candidate is considered lost merely because it is absent from the current `relations/` canonical index.
