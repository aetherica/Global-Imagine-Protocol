# GIOP V3.1 — Semantic Integration Map

**Status:** CLOSED FOR CURRENT V3.1 SEMANTIC NUCLEI  
**Branch:** `v3.1-tree-architecture`

## Governing model

`Visitor Universe → different entry depth → same canonical knowledge`

Visitor Universe changes orientation, entry depth and navigation. It does not create alternate semantic identities. Repository placement is organizational; semantic responsibility is authoritative.

## Current integrated nuclei

| Concept / Layer | Primary responsibility | Placement | Current state |
|---|---|---|---|
| Quantity | Measurable semantic concept | `quantities/` | Current nucleus closed |
| Temperature Condition | Contextual circumstance | `conditions/temperature-condition.md` | Active |
| Process | Processual transformation/organization | `processes/process.md` | Generic nucleus closed; specialized candidates deferred |
| State | Temporal/configurational mode | `states/state.md` | Generic nucleus active; specialized states deferred |
| Activity | Temporal occurrence of doing/observing/measuring/acquiring/processing | `activities/` | Seven-concept scoped batch active canonical |
| Relation | Typed semantic connection | `relations/` | Six-concept scoped seed active canonical; `viewing-distance` routed candidate |
| Representation | Information-bearing form | `representations/` | Generic batch closed |
| Time | Temporal semantics | `temporal/time.md` | Current nucleus closed |
| Result | Activity/execution-generated outcome entity | `results/result.md` | Current nucleus closed |
| Measurement Procedure | Reusable procedure/workflow specification | `workflows/measurement-procedure.md` | Current nucleus closed |
| Algorithm | Computational method | `computational-methods/algorithm.md` | Current nucleus closed |
| Software | Computational implementation | `implementations/software.md` | Current nucleus closed |

## Canonical chains

### Measurement

`Scene / Object / System → Condition(s) → Measurement Procedure → Activity / Execution → Result → Representation`

### Observation and presentation

`Result / Information → Representation → Display → Viewing Conditions → Observer → Perception`

### Computational realization

`Algorithm → Software Implementation → Execution / Processing → Result`

### Temporal qualification

`Phenomenon → Time context → Acquisition / Execution / Processing → Result time → Presentation`

### Viewing geometry

`Reference A → Viewing Distance → Reference B`, with a Distance quantity/value used as qualification where applicable.

## Boundary decisions

1. No important noun is promoted to Class merely because it is important.
2. Quantity is distinct from Quantity Value, Unit, Measurement and Measurement Result.
3. Activity is distinct from Process; Procedure is distinct from Activity/Execution.
4. Result is distinct from Representation and from Measurement Result.
5. Algorithm is distinct from Software and actual Processing.
6. Relation concept is distinct from relation assertion and validation constraint.
7. `part-of` is distinct from `participates-in`.
8. `derived-from` is lineage/provenance, not generic causality.
9. `has-result` is a reusable output relation and does not globally impose measurement semantics or fixed cardinality.
10. Time is temporal semantics, not merely a timestamp field.
11. Viewing Distance remains a specialized relation candidate and is not silently promoted into the canonical relation seed.

## Closure rule

A layer is considered closed only for its stated nucleus when identity, semantic responsibility, boundaries, relation authority, Visitor Universe routing, retrieval, lifecycle and cross-layer integration have been checked. Controlled candidates and deferred concepts remain retained and require independent promotion.

The detailed closure state is recorded in `02 SEMANTICS/SEMANTIC-CLOSURE-MAP.md`.
