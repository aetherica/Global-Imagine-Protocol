# GIOP V3.1 — Biological Integrity Lock (BIL)

**Status:** INTEGRATED CANDIDATE LAYER — NOT CANONICAL PROMOTION
**Branch:** `v3.1-tree-architecture`

## Purpose
BIL is implemented as a cross-layer integrity-control framework. It does not replace GIOP Classes, Properties, Conditions, States, Quantities, Activities, Processes, Relations, Representations, Temporal Semantics, Results, Workflows, Computational Methods, Implementations or Provenance.

The governing Foundation sequence remains:

`LEARN → RETAIN → CLASSIFY → VERIFY → RESOLVE → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE`

## Dataset implementation
The BIL topic universe is retained in `BIL-TOPIC-REGISTRY.md`. Candidate semantics are indexed in `BIL-CANDIDATE-REGISTRY.md` and must be interpreted through `BIL-IMPLEMENTATION-DATA-SCHEMA.md`.

The current integrated candidate set contains thirteen BIL-native candidates: Integrity Reference, Integrity Claim, Integrity Constraint, Permitted Variation, Integrity Evidence, Evidence Sufficiency, Integrity Validation, Integrity Decision, Integrity Adjudication, Integrity Profile, Integrity Drift, Integrity Deviation, and Integrity Preservation.

Presence in the registry does not confer canonical authority.

## Claim-centric model

```text
REFERENCE
   ↓
CLAIM
   ↓
EVIDENCE
   ↓
VALIDATION / EVALUATION
   ↓
DECISION
   ↘
   ADJUDICATION when conflict remains material
```

A claim is interpreted inside a profile/context and against declared constraints and permitted variation. `Deviation`, `Drift`, and `Preservation` are candidate interpretations, not automatic failure states.

## Existing GIOP ownership
BIL consumes existing canonical semantics. Entity type remains Classes; characteristics remain Properties; circumstance remains Conditions; mode remains State; measurable concepts remain Quantities; occurrences remain Activities; transformations remain Processes; typed connections remain Relations; information forms remain Representations; time remains Temporal; outputs remain Results; reusable procedures remain Workflows; algorithms and software remain their respective layers.

BIL supplies the integrity-specific comparison, claim, evidence, evaluation and decision control around those semantics.

## Visitor Universe
One canonical BIL knowledge body serves multiple visitors:

`CANONICAL KNOWLEDGE → PROFILE/TASK ROUTING → ENTRY DEPTH → CONSUMPTION`

Depth 0 provides orientation; Depth 1 conceptual structure; Depth 2 applied profile behavior; Depth 3 technical validation; Depth 4 formal/machine representation. Profile selection may change relevance and examples but never duplicates or changes canonical meaning, identity, provenance, lifecycle or evidence identity.

## Completion state
This pass completes the **structured BIL candidate dataset implementation** and its routing/index architecture. It does not perform universal canonical promotion. Candidate-level semantic validation and Foundation Gate-J remain the authority for promotion.

See `BIL-CLOSURE-AUDIT.md` for the current implementation audit.

`.gitkeep` remains only as placeholder history and is not a completion criterion.
