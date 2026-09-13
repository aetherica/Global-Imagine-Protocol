# GIOP V3.1 — Semantic Integration Map

**Status:** CLOSED FOR CURRENT V3.1 SEMANTIC NUCLEI + PROVISIONAL MODEL CANDIDATE + RELATION-ROUTED ATTACHMENT CANDIDATE + CLASS-ROUTED MATERIAL DOMAIN COORDINATION + COLOR CROSS-LAYER DOMAIN COORDINATION  
**Branch:** `v3.1-tree-architecture`

## Governing model

`Visitor Universe → different entry depth → same canonical knowledge`

Visitor routing changes orientation, entry depth and navigation. It does not create alternate semantic identities. Repository placement is organizational; semantic responsibility is authoritative.

## Current integrated nuclei

| Concept / Layer | Primary responsibility | Placement | Current state |
|---|---|---|---|
| Quantity | Measurable semantic concept | `quantities/` | Current nucleus closed |
| Temperature Condition | Contextual circumstance | `conditions/temperature-condition.md` | Active |
| Process | Processual transformation/organization | `processes/process.md` | Generic nucleus closed; specialized candidates deferred |
| State | Temporal/configurational mode | `states/state.md` | Generic nucleus active; specialized states deferred |
| Activity | Temporal occurrence of doing/observing/measuring/acquiring/processing | `activities/` | Seven-concept scoped batch active canonical |
| Relation | Typed semantic connection | `relations/` | Six-concept scoped seed active canonical; `viewing-distance` and attachment remain controlled candidates |
| Representation | Information-bearing form | `representations/` | Generic nucleus + first advanced extension batch closed |
| Model | Purpose-specific target-oriented abstraction or construct | `models/model.md` | Provisional candidate layer; specialized model vocabulary deferred |
| Material | Physical substance or medium identity | `classes/material.md` | Active canonical Class; `material/` is class-routed domain coordination |
| Time | Temporal semantics | `temporal/time.md` | Current nucleus closed |
| Result | Activity/execution-generated outcome entity | `results/result.md` | Current nucleus closed |
| Measurement Procedure | Reusable procedure/workflow specification | `workflows/measurement-procedure.md` | Current nucleus closed |
| Algorithm | Computational method | `computational-methods/algorithm.md` | Current nucleus closed |
| Software | Computational implementation | `implementations/software.md` | Current nucleus closed |
| Attachment Candidate | Physical/configurational connection pattern | `attachment/` | Candidate, routed to Relation; not canonical |
| Color Semantic Domain | Cross-layer colour sense resolution and routing | `color/` | Implementation-complete coordination; not a canonical layer |

## Canonical / Candidate chains

### Measurement

`Scene / Object / System → Condition(s) → Measurement Procedure → Activity / Execution → Result → Representation`

### Observation and presentation

`Result / Information → Representation → Display → Viewing Conditions → Observer → Perception`

### Computational realization

`Algorithm → Software Implementation → Execution / Processing → Result`

### Model-oriented realization

`Target / Phenomenon → Model → Algorithm / Activity / Process → Result / Representation`

This is a coordination pattern rather than a new relation vocabulary. It does not imply that every model is computational or that every model has an algorithmic implementation.

### Temporal qualification

`Phenomenon → Time context → Acquisition / Execution / Processing → Result time → Presentation`

### Material coordination

`Material Class identity → Property / Quantity / Measurement → Result / Representation`

The material node remains the existing Class authority. The chain does not create a Material layer or a new relation predicate.

### Viewing geometry

`Reference A → Viewing Distance → Reference B`, with a Distance quantity/value used as qualification where applicable.

### Attachment candidate routing

`Bearer A → Attachment candidate pattern → Bearer B`

This pattern is evaluated within Relation responsibility. The operation that establishes the connection routes to Activity/Process/Workflow; a recording of the connection routes to Representation; a garment-specific securing mechanism routes to Garment.

### Color cross-layer routing

`Colour claim → sense/target identification → responsible authority → qualified value/result/representation/context`

Typical chains include `Stimulus / Surface / Object → Condition → Observation / Measurement → Perception or Result → Representation` and `Material / Structure / Illumination → coloration mechanism → stimulus`. Functional or normative colour meaning routes through Context/Function/Representation rather than intrinsic Color identity.

## Boundary decisions

1. No important noun is promoted to Class merely because it is important.
2. Quantity is distinct from Quantity Value, Unit, Measurement and Measurement Result.
3. Activity is distinct from Process; Procedure is distinct from Activity/Execution.
4. Result is distinct from Representation and from Measurement Result.
5. Algorithm is distinct from Software and actual Processing.
6. Model is distinct from Representation, Algorithm, Software, Activity, Process and Result.
7. Material is the existing canonical Class identity and is distinct from Material Property, Quantity, Measurement Result, Object, Surface, Textile, Garment, Representation, Process, State and Condition.
8. Material does not become a second semantic layer merely because a `material/` domain folder exists.
9. Relation concept is distinct from relation assertion and validation constraint.
10. `part-of` is distinct from `participates-in`.
11. `derived-from` is lineage/provenance, not generic causality.
12. `has-result` is a reusable output relation and does not globally impose measurement semantics or fixed cardinality.
13. Time is temporal semantics, not merely a timestamp field.
14. Viewing Distance remains a specialized relation candidate and is not silently promoted into the canonical relation seed.
15. Model types such as machine-learning, causal, predictive, world, system, architecture, and digital-twin models remain independent candidate vocabulary and are not automatically separate canonical concepts.
16. Attachment is a bounded candidate pattern within Relation responsibility, not a parallel relation layer.
17. Physical attachment is not collapsed with psychological attachment or digital/file attachment.
18. Color is a cross-layer coordination domain, not a parallel semantic layer.
19. Color is not collapsed with Perception, Property, Quantity, Measurement, Result, Representation, Signal, Meaning, Mechanism, Evidence, State, or Integrity.
20. False colour and encoded/displayed colour are not automatically intrinsic object/surface colour.

## Closure rule

A layer or domain coordination area is considered closed only for its stated nucleus or explicitly bounded candidate scope when identity, semantic responsibility, boundaries, relation authority, Visitor Universe routing, retrieval, lifecycle and cross-layer integration have been checked. Controlled candidates and deferred concepts remain retained and require independent promotion.

The detailed closure state is recorded in `02 SEMANTICS/SEMANTIC-CLOSURE-MAP.md`.
