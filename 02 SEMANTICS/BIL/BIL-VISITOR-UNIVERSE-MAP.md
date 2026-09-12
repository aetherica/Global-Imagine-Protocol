# BIL Visitor Universe Map — V3.1

**Status:** RESEARCH / PILOT ROUTING MAP  
**Canonical audience taxonomy:** NOT ESTABLISHED  
**Governing principle:** one canonical BIL knowledge body, different entry depth.

## 1. Core Rule

```text
CANONICAL BIL KNOWLEDGE
        ↓
VISITOR UNIVERSE
        ↓
TASK + PROFILE + EXPERTISE + RETRIEVAL INTENT
        ↓
ENTRY DEPTH
        ↓
HUMAN / MACHINE CONSUMPTION
```

Visitor routing changes orientation and traversal. It never creates audience-specific semantic identities.

## 2. Depth Model

| Depth | Entry purpose | Typical content |
|---|---|---|
| D0 | Orientation | What BIL is, why it exists, basic examples and boundaries |
| D1 | Conceptual | Reference, Claim, Invariant, Permitted Variation, Evidence, Evaluation, Decision |
| D2 | Applied | Profile, evidence requirements, observability, transformations, failure examples |
| D3 | Technical | Metrics, models, uncertainty, cross-view/temporal/physical validation, workflows |
| D4 | Formal/Machine | Stable IDs, profile parameters, evidence records, relations, provenance, machine validation |

## 3. Routing Dimensions

`TASK`
`EXPERTISE`
`PROFILE`
`INTEGRITY DIMENSION`
`EVIDENCE DEPTH`
`TECHNICAL DEPTH`
`RETRIEVAL INTENT`
`MACHINE/HUMAN MODE`

## 4. Canonical invariants across all visitors

These must remain identical across every projection:

- canonical identifier;
- semantic responsibility;
- approved definition, when canonical;
- candidate/canonical status;
- provenance identity;
- evidence identity and status;
- lifecycle state;
- relation semantics;
- validation decision;
- recorded uncertainty and unresolved questions.

## 5. Profile-aware routing examples

### Human Portrait

Focus: face identity, morphology, asymmetry, skin/ocular evidence, pose and permitted editing.

Typical depth: D1–D3.

### Wildlife

Focus: species, individual markings, pose-aware morphology, fur/feather/scale state, habitat and environmental interaction.

Typical depth: D1–D3.

### Sports

Focus: athlete identity, action configuration, equipment interaction, ground contact, group formation and temporal continuity.

Typical depth: D1–D3.

### Dance / Performance

Focus: member identity, choreography, formation, spacing, synchrony, costume motion and temporal transitions.

Typical depth: D1–D3.

### Group / Crowd

Focus: membership, identity attribution, relative geometry, occlusion, collective motion and member persistence.

Typical depth: D2–D4.

### VFX / Synthetic Creature

Focus: declared design reference, transformation intent, morphology consistency, interaction, physical plausibility and temporal continuity.

Typical depth: D2–D4.

### Scientific / Medical / Macro

Focus: reference conditions, evidence sufficiency, measurement context, observability, modality and validation constraints.

Typical depth: D2–D4.

## 6. Retrieval Intents

A BIL retrieval layer should support at least:

- concept discovery;
- subject discovery;
- profile discovery;
- integrity-dimension retrieval;
- evidence retrieval;
- validation retrieval;
- failure-mode retrieval;
- transformation retrieval;
- reference retrieval;
- provenance retrieval;
- machine/API retrieval.

## 7. Projection Integrity

A projection may omit information for relevance, but it must not rewrite meaning.

```text
CANONICAL RECORD
   ├── orientation projection
   ├── learner projection
   ├── practitioner projection
   ├── specialist projection
   ├── engineering projection
   └── machine projection
```

If two projections appear to disagree, the canonical record and underlying evidence are re-evaluated. A visitor-specific exception is not created merely to preserve a projection.

## 8. Retrieval Self-Containment

Any isolated BIL retrieval unit should expose enough identity to remain interpretable without conversational context. At minimum:

`ID`, `TITLE`, `TYPE`, `STATUS`, `PRIMARY RESPONSIBILITY`, `DEFINITION/WORKING DEFINITION`, `PROFILE SCOPE`, `EVIDENCE`, `VALIDATION`, `PROVENANCE`, `RELATED IDS`.

## 9. Machine Mode

Machine-oriented retrieval must expose deterministic fields without requiring human narrative order. It should be possible to traverse:

`BIL ID → Profile → Claim → Reference → Evidence → Evaluation → Decision → Provenance → Related GIOP IDs`

## 10. Visitor Universe Validation Cases

The pilot must test:

1. one candidate across D0–D4;
2. human profile;
3. wildlife profile;
4. sports profile;
5. dance/group profile;
6. VFX/synthetic profile;
7. still image;
8. video;
9. uncertain evidence;
10. permitted transformation;
11. conflicting provenance/evidence;
12. isolated chunk retrieval;
13. machine/API retrieval.

## 11. Current Status

**Visitor routing dataset entered for pilot use.**

This map is not a separate semantic ontology and does not authorize audience-specific BIL pages.
