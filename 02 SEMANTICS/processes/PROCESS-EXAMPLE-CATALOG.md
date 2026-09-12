# GIOP V3.1 — Process Example Catalog

**Artifact Type:** Semantic Example / Boundary Catalog  
**Semantic Layer:** Process  
**Version:** 1.0.0  
**Status:** Active  
**Authority:** GIOP

## Purpose

This catalog provides boundary-controlled examples for the canonical Process concept. Examples illustrate semantic routing; they do not create additional canonical Process identities.

## Example 1 — Image-processing pipeline

**Process interpretation:** An organized course coordinating multiple processing activities from source representation through one or more transformed results.

**Activity boundary:** Individual denoising, demosaicing, color conversion, resizing, or encoding occurrences remain Activities.

**Representation boundary:** A pipeline diagram or workflow file describing the course is a Representation/artifact, not automatically the Process.

**Retrieval path:** `Process → Activities → Results → Representations`.

## Example 2 — Coordinated capture campaign

**Process interpretation:** A planned or realized temporal course coordinating multiple acquisition/capture activities toward a collection of results.

**Activity boundary:** One camera exposure, recording session, observation, or measurement occurrence remains an Activity when the assertion concerns that occurrence.

**Context boundary:** Location, lighting, operational conditions, and project purpose qualify the course without becoming the Process identity.

## Example 3 — Laboratory measurement program

**Process interpretation:** An organized course coordinating repeated measurement activities, calibration activities, analysis, and result production toward a defined program objective.

**Quantity boundary:** Measured quantities and quantity values remain Quantity semantics.

**Result boundary:** Measurement results remain separate semantic outputs.

**Procedure boundary:** The prescribed measurement method remains Procedure-level semantics where applicable.

## Example 4 — Manufacturing course

**Process interpretation:** An organized production course linking machining, inspection, calibration, transfer, and other activities toward product results.

**Activity boundary:** Individual machining or inspection occurrences remain Activities.

**State boundary:** Machine readiness, running, stopped, or maintenance states remain States.

**Condition boundary:** Temperature, environmental, or operational circumstances remain Conditions.

## Example 5 — Software deployment course

**Process interpretation:** A coordinated temporal course involving build, test, packaging, deployment, verification, and release activities.

**Algorithm boundary:** Algorithms used during the course remain computational methods.

**Software boundary:** Executable software and implementation artifacts remain separate from the Process.

**Representation boundary:** Deployment manifests and workflow files may represent process information without being the Process itself.

## Example 6 — Preservation and migration course

**Process interpretation:** An organized temporal course coordinating assessment, migration, validation, packaging, and preservation activities.

**Representation boundary:** Files and archival packages remain information-bearing/storage artifacts or representations.

**Provenance boundary:** Source, derivation, activity, and agent information should be retained through established provenance semantics.

## Non-Process Examples

| Example | Correct route | Why |
|---|---|---|
| A single exposure | Activity | occurrence-level action |
| A measurement result | Result | generated result/information |
| A camera in standby | State | recognized mode at temporal locus |
| Illumination during capture | Condition | circumstance affecting operation/observation |
| A workflow YAML file | Representation | information-bearing artifact describing a workflow |
| A denoising algorithm | Algorithm | computational method |
| A deployment script | Software / Representation | implementation or representation artifact |
| A process diagram | Representation | represents process information |
| A project | Project / organizational semantics | endeavor, not automatically a Process |

## Visitor Entry Depth

- **General:** understand Process as an organized course rather than a single action.
- **Learner:** compare Process with Activity, Procedure, Result, State, and Representation.
- **Imaging practitioner:** use pipeline and capture examples.
- **Engineer/scientist:** inspect composition, transformation, inputs, results, provenance, and validation boundaries.
- **AI/data/API consumer:** use stable identity and machine retrieval anchors.
- **Standards/preservation:** inspect evidence, lifecycle, provenance, and artifact boundaries.

Entry depth does not create visitor-specific Process semantics.

## Canonicalization Reminder

Examples are explanatory evidence for boundary testing. They do not authorize promotion of `Transformation Process`, `Development Process`, `Operational Process`, or `Workflow Process` without independent canonicalization review.
