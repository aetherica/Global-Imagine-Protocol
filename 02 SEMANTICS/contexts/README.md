# GIOP Canonical Contexts

## Status

**CANONICAL — V3.1 SEMANTIC LAYER**

The `contexts/` directory defines the authoritative GIOP semantic layer for reusable contextual frames. It does not define a second knowledge base and does not replace the semantics of the entities, conditions, states, quantities, activities, processes, relations, or representations that may occur within a context.

## Governing Question

> **Within what setting, circumstance, purpose, perspective, or situational frame is a semantic element defined, interpreted, used, evaluated, observed, measured, represented, or otherwise understood?**

## Canonical Context Definition

**Context is a reusable canonical semantic construct that specifies the relevant setting, circumstance, purpose, perspective, or situational frame within which a semantic element is defined, interpreted, used, evaluated, observed, measured, represented, or otherwise understood.**

A Context is a frame, not merely a condition, metadata field, location, time value, or collection of surrounding facts. Context may reference or contain entities, conditions, states, quantities, relations, procedures, activities, processes, observations, results, representations, actors, purposes, and perspectives as contextual components.

## Architectural Position

GIOP treats Context as part of canonical knowledge while treating Visitor Universe as the framework through which the same canonical knowledge is entered, navigated, and consumed:

`CANONICAL KNOWLEDGE → VISITOR UNIVERSE → ENTRY DEPTH → HUMAN / MACHINE CONSUMPTION`

Visitor Universe is not an additional semantic payload and does not require visitor-specific definitions, sections, or copies of canonical knowledge. Entry depth is produced by the structure and progressive technical depth of the canonical content itself.

## Context Family

The current V3.1 seed vocabulary is:

1. `context`
2. `domain-context`
3. `application-context`
4. `capture-context`
5. `measurement-context`
6. `viewing-context`
7. `assessment-context`
8. `processing-context`
9. `operational-context`

`context`, `domain-context`, `application-context`, `measurement-context`, `viewing-context`, and `assessment-context` are currently admitted as canonical V3.1 concepts. `capture-context`, `processing-context`, and `operational-context` remain **CANONICAL CANDIDATE — V3.1 SEED** entries pending the cross-analysis required for promotion. The retained registry contains additional recovered and externally evidenced context terms that remain deferred, under verification, conflicted, or routed to another semantic responsibility.

## Boundary Model

`CONTEXT → contextual frame`

`CONDITION → contextual circumstance or condition`

`STATE / STATUS → mode or status of an entity/process`

`QUANTITY → measurable concept`

`VALUE / RESULT → realization or outcome`

`RELATION → typed connection`

`ACTIVITY → intentional or procedural action`

`PROCESS → transformation/development occurring through time`

`REPRESENTATION → information-bearing representational entity`

`VISITOR UNIVERSE → access/navigation framework, not semantic meaning`

A Context can include or qualify any of these without becoming equivalent to them.

## Context Composition

A context may be described through contextual dimensions such as:

- identity and participating entities;
- activity, task, or purpose;
- spatial setting;
- temporal setting;
- environmental and optical circumstances;
- observation or measurement setup;
- procedure and instrumentation;
- viewing and display conditions;
- processing and computational configuration;
- operational constraints;
- assessment method, material, assessor, and session;
- domain or knowledge universe;
- application or use scenario;
- perspective, interpretation frame, or intended use;
- relevant relations among contextual components.

These dimensions are not a mandatory universal schema. A Context page defines only the dimensions materially relevant to that context type.

## Context Is Not a Container Class by Default

GIOP uses **Context Family** as a semantic grouping until explicit `is-a` distinctions are sufficiently established. A context type must not be declared a subclass of generic Context merely because its name contains the word “context.” Its semantic responsibility must be established first.

## Condition and Context

A Condition describes a contextual circumstance or state of relevant influence. Context describes the broader frame in which something is understood or used. Conditions may be components or constraints of a Context.

For example, illumination condition may occur within a capture context; room illumination may be part of a viewing context; temperature may be an influence condition within a measurement context. None is thereby identical to Context.

## Measurement Context

Measurement Context is broader than a measurement condition or reference operating condition. It may include the measurand/quantity description, measuring system, procedure, operator or observer, measurement conditions, influence quantities, configuration, time, location, calibration/traceability information, and result interpretation frame.

The quantity/value/result semantics remain in their respective layers.

## Viewing Context

Viewing Context is broader than a single viewing condition. It can include stimulus, background, surround, adapting field, display, viewing geometry, viewing distance, observer characteristics, room environment, illumination, and intended evaluation task. It provides the frame in which a representation or visual stimulus is viewed or interpreted.

## Assessment Context

Assessment Context includes the circumstances and methodological frame of an evaluation, such as task, test material, assessor/observer, procedure, session, reference or anchor, service-use scenario, and relevant environment. It is not synonymous with viewing context, although a viewing context can be a component of an assessment context.

## Observation Context Boundary

`ObservationContext` is retained in the registry because external observation models use the term for contextual dependence between observations. It is not automatically equated with generic GIOP Context. Where it expresses a typed observation-to-observation association, its primary semantic responsibility may belong to Relations/Observation semantics, with Context as a cross-reference.

## Spatial and Temporal Context

Spatial and temporal semantics remain the responsibility of future `spatial/` and `temporal/` layers. Context may specify that spatial or temporal information is relevant to interpretation, but it does not redefine spatial or temporal relations or quantities.

## Evidence and Trust

Context concepts are admitted through semantic evidence, not visitor demand. External standards, scientific literature, technical models, and GIOP architectural synthesis provide evidence. A verified external term does not automatically become a canonical GIOP Context.

Epistemic status and canonical status are separate:

- **Epistemic:** `VERIFIED`, `UNDER VERIFICATION`, `UNVERIFIED`, `CONFLICTED`
- **Canonical:** `CANONICAL`, `CANONICAL CANDIDATE`, `DEFERRED`, `ROUTED ELSEWHERE`, `HISTORICAL/NON-CANONICAL`

## Visitor Universe and Entry Depth

Visitor Universe is implemented through the canonical content itself, not as a second semantic section inside each Context entry.

A well-formed Context page provides natural entry points through its identity, 5W1H orientation, definition, distinctions, contextual dimensions, cross-layer relations, technical explanation, trust, lifecycle, machine interpretation, and retrieval anchors. Different visitors can stop at the depth relevant to their task or continue into deeper technical material without receiving different canonical knowledge.

For example, a general visitor may begin with What and Why; a student may continue through Definition and Distinctions; an engineer may follow contextual components, constraints, and cross-layer relations; a scientist or metrologist may continue into evidence, measurement compatibility, and validation; a machine consumer may use stable identity, structured relations, boundaries, and retrieval anchors. These are reading behaviors, not additional semantic fields.

## Authoring Requirements

A canonical Context page should provide, as applicable:

1. Identity and stable canonical ID;
2. 5W1H orientation;
3. canonical semantic definition;
4. scope and target;
5. context family;
6. contextual components and dimensions;
7. composition/applicability;
8. distinctions from adjacent concepts;
9. cross-layer relations;
10. evidence and provenance;
11. trust and validation;
12. lifecycle;
13. machine/AI interpretation;
14. retrieval anchors;
15. what the Context does not mean;
16. semantic boundary and cross-references.

The exact section set may vary with semantic responsibility. Conditions, classes, properties, relations, and Contexts need not use identical headings; they must use the same content-first entry discipline and progressive depth established by the GIOP canonical implementation standard.

## Knowledge Retention Rule

No recovered knowledge is discarded because it is not currently canonical in `contexts/`.

`SOURCE → RECOVERED KNOWLEDGE → REGISTRY → CLASSIFICATION → EVIDENCE → CONFLICT ANALYSIS → PRIMARY RESPONSIBILITY → CANONICAL DECISION → CANONICAL ENTRY / ROUTED OR DEFERRED RECORD`

The registry is a retention and audit layer, not a replacement for future canonical semantic folders.

## Completion Rule

The V3.1 Context pass is complete for the current seed vocabulary when the canonical specification exists, every admitted seed Context has a complete canonical page, candidate entries remain explicitly identified until validated, and all other recovered context knowledge has a durable registry record with evidence/status/decision/routing rather than being silently omitted.
