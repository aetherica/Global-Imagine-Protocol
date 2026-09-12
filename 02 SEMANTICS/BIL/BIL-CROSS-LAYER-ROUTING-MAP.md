# BIL Cross-Layer Routing Map — V3.1

**Status:** RESEARCH / ROUTING RECORD  
**Purpose:** Map discovered BIL topics to existing GIOP semantic ownership and preserve BIL-specific integrity responsibility without duplication.

## Routing Principle

`DISCOVERED TOPIC → PRIMARY SEMANTIC RESPONSIBILITY → BIL INTEGRITY ROLE`

BIL does not absorb an existing semantic layer merely because that layer is relevant to an integrity claim.

## Routing Table

| Discovered topic | Primary semantic owner | BIL role | Notes |
|---|---|---|---|
| Human / Animal / Plant | `classes/` or applicable domain entity semantics | Subject scope | Entity identity is not BIL-native by default |
| Phone / Bag / Prop | `classes/object` or domain entity semantics | Interaction/configuration component | Object semantics remain external |
| Fabric / Water / Surface | `classes/`, `properties/`, `conditions/` or domain routing | Material/environment evidence | Context-specific relevance only |
| Skin characteristic | `properties/` or scientific model | Appearance evidence | BIL evaluates reference consistency |
| Wet / Dry | `states/`, `conditions/`, property context | State consistency | No duplicate state ontology |
| Pose / Expression | `states/`, `activities/`, domain model | Configuration/state target | Profile-sensitive |
| Gait / Dance / Sport action | `activities/` / `processes/` / domain workflow | Dynamic integrity target | Actual action remains Activity/Process-owned |
| Hand-phone contact | `relations/` + Activity/Process where applicable | Interaction configuration evidence | New relation authority requires independent promotion |
| Ground support | `relations/` + condition/state context | Physical configuration evidence | BIL consumes assertion |
| Distance | `quantities/` | Qualification/evidence | Quantity remains Quantity-owned |
| Time | `temporal/` | Temporal qualification | Time remains temporal layer |
| Image / Video / Mesh | `representations/` | Reference/evidence/output representation | Representation remains canonical owner |
| Measurement | `activities/` | Validation activity | Measurement semantics not redefined |
| Measurement Result | `results/` / relevant measurement semantics | Evidence/result input | Result semantics remain external |
| Algorithm | `computational-methods/` | Evaluation method | Algorithm is not BIL semantics |
| Software | `implementations/` | Operational implementation | Runtime tool is not semantic authority |
| Procedure | `workflows/` | Validation/evaluation workflow | Procedure remains reusable specification |
| Shadow / Reflection | Optical/condition/property/domain semantics | Optical evidence | BIL interprets consistency |
| Species classification | Domain/scientific semantics | Species integrity dimension | Species identity is not a BIL class |
| Morphing | Security/attack research | Integrity threat context | Attack semantics remain distinct |
| Provenance | Foundation / PROV / provenance controls | Trust evidence | Provenance authenticity != biological integrity |
| CIEDE2000 / IoU / RMS | Quantity/measurement/validation method context | Validation instrument | Metric is not an integrity concept |
| 3DMM / OpenPose / BSSRDF | Scientific/computational model | Evidence/reconstruction mechanism | Model is not BIL semantic identity |

## BIL-Native Candidate Routing

After current research, the strongest BIL-native candidate responsibilities are:

1. Integrity Reference
2. Integrity Claim
3. Invariant / Conditional Invariance
4. Permitted Variation / Declared Transformation
5. Integrity Evidence
6. Evidence Sufficiency
7. Integrity Evaluation
8. Integrity Decision
9. Evidence Conflict / Adjudication
10. Integrity Profile

These remain candidate-level items until individual boundary validation and Gate-J promotion.

## Core Distinctions

### Integrity vs Property

Property describes an attributable characteristic. BIL asks whether a characteristic/configuration remains consistent with a declared reference and context.

### Integrity vs State

State describes the current recognized mode/configuration at a temporal locus. BIL evaluates whether the observed/derived state is consistent with reference and declared transformation.

### Integrity vs Relation

Relation specifies a typed connection. BIL may use relation assertions as evidence for configuration integrity.

### Integrity vs Representation

Representation carries information. BIL evaluates whether the relevant information/configuration represented remains consistent.

### Integrity vs Provenance

Provenance records origin/history. BIL evaluates biological/configurational consistency. Neither substitutes for the other.

### Integrity vs Physical Plausibility

A fictional creature may be internally consistent with its declared reference without being natural-world anatomically plausible.

### Integrity vs Identity

Identity is one possible integrity dimension, not the complete definition of integrity.

## Current Routing Decision

No existing GIOP semantic layer is to be duplicated inside BIL for convenience. BIL retains a cross-layer control responsibility and uses stable canonical IDs from the existing semantic architecture.
