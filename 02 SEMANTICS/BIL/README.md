# GIOP V3.1 — Biological Integrity Lock (BIL)

**Status:** RESEARCH / REGISTRY IMPLEMENTATION — NOT CANONICAL SEMANTIC PROMOTION  
**Branch:** `v3.1-tree-architecture`

## Purpose

The `BIL/` directory currently stores the controlled research and candidate dataset for Biological Integrity Lock.

BIL is being implemented as a **cross-layer integrity-control framework**, not as a replacement ontology for Classes, Properties, Conditions, States, Quantities, Activities, Processes, Relations, Representations, Temporal Semantics, Results, Workflows, Computational Methods, Implementations, or Provenance.

The current implementation preserves the governing Foundation rule:

`LEARN → RETAIN → CLASSIFY → VERIFY → RESOLVE → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE`

No research item becomes canonical merely because it is present in this folder.

## Current Working Scope

The initial BIL dataset covers a broad integrity universe including:

- biological subjects and species;
- human, animal, wildlife, botanical, synthetic, and multi-organism contexts;
- identity, anatomy, morphometry, state, behaviour, motion, group configuration;
- clothing, fabric, accessories, carried objects, phone/bag/prop interactions;
- water, fluids, wetness, dust, mud, snow, ice, smoke and other material/environmental interactions;
- surfaces, support, contact, affordance and environmental configuration;
- lighting, shadows, reflections, refraction, occlusion and optical evidence;
- still, video, 3D, 4D, VFX and generated-media representations;
- transformation, reconstruction, temporal continuity and cross-view consistency;
- evidence, uncertainty, reference sufficiency, validation, threats and provenance.

These are **topic-space entries and routing metadata**, not a declaration that each item is a BIL semantic concept.

## Claim-Centric Core

The current implementation model is:

```text
REFERENCE
   ↓
CLAIM
   ↓
EVIDENCE
   ↓
EVALUATION
   ↓
DECISION
```

Claims are evaluated within a declared profile/context and may distinguish:

- invariant;
- conditionally invariant;
- permitted variation;
- declared transformation;
- unconstrained;
- unknown / unobservable.

The implementation intentionally avoids collapsing the result into a universal scalar `integrity_score`.

## Existing GIOP Layer Routing

BIL consumes canonical GIOP semantics rather than redefining them.

| Responsibility | Primary owner | BIL treatment |
|---|---|---|
| Entity type | `classes/` | integrity target/context |
| Characteristic | `properties/` | evidence/claim target |
| Contextual circumstance | `conditions/` | qualification |
| State | `states/` | state-consistency target |
| Measurable concept | `quantities/` | evidence source |
| Action/occurrence | `activities/` | evaluation activity |
| Transformation | `processes/` | change source |
| Typed connection | `relations/` | interaction/configuration evidence |
| Information-bearing form | `representations/` | reference/evidence/output form |
| Time | `temporal/` | temporal qualification |
| Result | `results/` | evaluation output |
| Procedure | `workflows/` | reusable validation procedure |
| Computational method | `computational-methods/` | inference/evaluation method |
| Implementation | `implementations/` | operational realization |
| Provenance | Foundation controls | trust/traceability input |

## Visitor Universe

BIL uses one canonical knowledge body with variable entry depth:

`CANONICAL BIL KNOWLEDGE → VISITOR UNIVERSE → ENTRY DEPTH → CONSUMPTION`

Visitor routing may alter orientation, technical depth, profile visibility, examples, evidence detail, validation detail and retrieval granularity. It must never alter canonical identity, definition, provenance, lifecycle, evidence identity or canonical decision.

Candidate depth model:

- **Depth 0 — Orientation**: What BIL is and why it exists.
- **Depth 1 — Conceptual**: Reference, claim, invariant, variation, evidence, evaluation and decision.
- **Depth 2 — Applied**: Profile-specific scope, evidence requirements, observability and transformation rules.
- **Depth 3 — Technical**: Models, measures, uncertainty, thresholds, temporal/physical/cross-view validation.
- **Depth 4 — Formal/Machine**: Stable IDs, graph relations, profile parameters, evidence status, provenance and machine validation metadata.

No audience-specific semantic duplicates are permitted.

## Lifecycle

BIL research material follows Foundation lifecycle controls. Current directory status is deliberately non-canonical until candidate-level validation and Gate-J promotion are completed.

### Current State

**RESEARCH DATASET ACTIVE FOR STRUCTURED ENTRY**

**CANONICAL BIL SEMANTIC PROMOTION: NOT YET PERFORMED**

## Repository Rule

`.gitkeep` is retained as the original folder placeholder history; it is not a completeness criterion.

The authoritative decision path is determined by semantic identity, evidence, ownership, validation, lifecycle and promotion state—not by file count or folder occupancy.
