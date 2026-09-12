# GIOP V3.1 — Activity Canonical Promotion Decision

**Scope:** Current Activity semantic batch  
**Branch:** `v3.1-tree-architecture`  
**Decision:** PROMOTED TO ACTIVE CANONICAL  
**Current state:** ACTIVE / CANONICAL

## Promoted Records

- `SEM-ACTIVITY-001` — Activity
- `SEM-ACTIVITY-EXECUTION-001` — Execution
- `SEM-ACTIVITY-OBSERVATION-001` — Observation
- `SEM-ACTIVITY-MEASUREMENT-001` — Measurement
- `SEM-ACTIVITY-ACQUISITION-001` — Acquisition
- `SEM-ACTIVITY-PROCESSING-001` — Processing
- `SEM-ACTIVITY-CALIBRATION-001` — Calibration

All records are version `1.0.0` and are active canonical semantic entries within this scoped decision.

## Decision Basis

The dedicated Activity Semantic Validation Record and Activity Gate-J Approval confirm that the batch satisfies the applicable GIOP Foundation authoring, semantic, provenance/evidence, lifecycle, trust, cross-reference, and promotion controls.

## Canonical Boundaries Preserved

Activity is the occurrence layer. Procedure remains specification-level; Process remains a broader transformation/development/progression or organized temporal course; Result remains generated output; Representation remains information-bearing form.

Execution is a procedure-driven Activity pattern rather than a universal parent. Observation and Measurement are adjacent but distinct. Acquisition is the capture occurrence and is not Camera/Lens/Sensor. Processing is the actual operation and is not Algorithm/Software. Calibration is the metrological relationship-establishing operation and is not Adjustment/Verification/Maintenance.

## Visitor Universe

The promotion authorizes one canonical Activity knowledge layer. Visitor Universe may provide different entry depth, orientation, traversal, and technical presentation to different visitors, but it does not create alternate canonical definitions or duplicate audience-specific knowledge.

## Relation Control

Existing canonical relations remain authoritative. Activity records may use established relation semantics where applicable. Explanatory dependencies such as `specifies`, `uses`, `produces`, `concerns`, and similar labels are not silently promoted as new relation vocabulary.

## State Transition

`AUTHORED → INTEGRATED → VALIDATED → APPROVED → ACTIVE CANONICAL`

## Preservation

No prior semantic record or V3 source material is deleted or overwritten as a consequence of this promotion. Future Activity concepts remain independently gated.
