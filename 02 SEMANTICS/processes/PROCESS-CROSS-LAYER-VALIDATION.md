# Process Cross-Layer Validation

## Status

**VALIDATED — SCOPED PROCESS BATCH**

## Validation Matrix

| Concept | Process? | Decision |
|---|---:|---|
| Activity | No | occurrence-level concept remains separate |
| Procedure | No | prescribed/specification-level concept |
| Result | No | output/information concept |
| State | No | temporal mode/condition of a bearer |
| Condition | No | circumstance/environment concept |
| Context | No | interpretive/situational frame |
| Representation | No | information-bearing form |
| Algorithm | No | computational method |
| Software | No | implementation artifact |
| Workflow document | No | representation/artifact describing a workflow |
| Project | No | organizational endeavor with separate semantics |
| Transformation Process | Candidate | potentially narrower process responsibility |
| Development Process | Candidate | domain-dependent progression semantics |
| Operational Process | Candidate | controlled/operational course semantics |
| Workflow Process | Candidate | requires distinction between model, procedure, and realized process |

## Gate Tests

### Test A — Long-running acquisition

A capture operation lasting several hours remains an Acquisition Activity when the assertion concerns the actual capture occurrence. A broader organized capture campaign may be modeled as a Process if the assertion concerns the coordinated course.

**Decision:** preserve Activity/Process distinction.

### Test B — Image-processing pipeline

A sequence of processing operations may constitute a Process when the semantic assertion concerns the organized pipeline as a whole. Individual processing operations remain Processing Activities. A pipeline specification or diagram is a Representation of process information, not automatically the Process itself.

**Decision:** Process may coordinate Activities; Representation remains separate.

### Test C — Algorithm execution

An algorithm is a method. Its execution is an Activity. A broader computational workflow may be a Process. Software implementing the algorithm remains an implementation artifact.

**Decision:** do not collapse method, occurrence, implementation, and process.

### Test D — Laboratory measurement program

A measurement Activity obtains quantity values. A larger organized measurement program may be a Process. Measurement, Quantity, Result, and Process retain separate responsibilities.

**Decision:** no universal subclass relation is introduced.

### Test E — Manufacturing line

A manufacturing course can be a Process; individual machining, inspection, calibration, and transfer operations are Activities; products and measurements remain separate entities/results.

**Decision:** composite process semantics accepted.

### Test F — Workflow file

A workflow file can encode a process model or procedure. The file itself is a Representation/Artifact. Its content does not become a Process merely because it describes execution.

**Decision:** representation/process boundary preserved.

## Required Gates

- Identity gate: passed
- Primary responsibility gate: passed
- Existing-entry gate: passed against Activity and adjacent semantic folders
- Boundary gate: passed
- Relation-authority gate: passed; no new relation authority introduced
- Provenance/evidence gate: passed
- Visitor Universe gate: passed
- Retrieval gate: passed
- Lifecycle gate: passed

## Promotion Rule

Only `SEM-PROCESS-GENERIC-001` is promoted in this scoped batch. Specialized candidates require their own evidence and promotion decisions.
