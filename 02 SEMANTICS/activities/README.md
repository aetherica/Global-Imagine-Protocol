# GIOP Activity Semantics

## Status

**SCOPED CANONICAL PILOT — PROVISIONAL ENTRIES**

This directory is the canonical semantic home for occurrence-level Activity concepts admitted to the current Activity authoring batch. The entries are provisional until the applicable validation and promotion gates are completed.

## Purpose

The Activity layer represents what actually happens: an occurrence of doing, observing, measuring, acquiring, transforming, calibrating, or otherwise performing an operation.

It is intentionally distinct from:

```text
Procedure       = prescribed/specification-level way of doing
Activity        = actual occurrence
Process         = transformation, development, progression, or organized temporal course
Result          = output of an occurrence
Representation  = information-bearing form
```

## Current Scoped Batch

1. `activity.md` — Activity
2. `execution.md` — Execution
3. `observation.md` — Observation
4. `measurement.md` — Measurement
5. `acquisition.md` — Acquisition
6. `processing.md` — Processing
7. `calibration.md` — Calibration

## Semantic Model

```text
Activity
├── Execution-oriented pattern
│   ├── Observation
│   └── Measurement
├── Acquisition
├── Processing
└── Calibration
```

This diagram is semantic, not a mandatory filesystem hierarchy. Execution is not a universal parent of every Activity concept.

## Core Boundary Rules

```text
Activity ≠ Process
Activity ≠ Procedure
Activity ≠ Result
Activity ≠ Representation

Execution ≠ Procedure
Execution ≠ Process

Observation ≠ Measurement
Measurement ≠ Quantity
Measurement ≠ Measurand
Measurement ≠ Measurement Result

Acquisition ≠ Camera
Acquisition ≠ Lens
Acquisition ≠ Sensor
Acquisition ≠ Image / Data

Processing ≠ Algorithm
Processing ≠ Software
Processing Activity ≠ Processing Process

Calibration ≠ Adjustment
Calibration ≠ Verification
Calibration ≠ Maintenance
```

## Relationship to Visitor Universe

The Activity layer contains one canonical body of knowledge. Visitor Universe does not create audience-specific semantic entries or duplicate knowledge.

Different visitors may enter the same entry at different depths:

```text
Canonical Activity Knowledge
        ↓
Visitor Universe
        ↓
Entry / Traversal Depth
        ↓
Human or Machine Consumption
```

Orientation supports novice access; semantic boundaries, technical depth, provenance, relations, validation, and retrieval anchors support professional and expert access. The underlying definition remains one canonical truth.

## Research Scope and Deferred Concepts

The current batch is deliberately limited to mature concepts supported by the completed Activity research pass.

Validated but staged for later semantic work include:

- Sampling
- Assessment
- Evaluation
- Verification
- Adjustment
- Actuation

Future concepts such as Measurand, Sample, measurement standards, and specialized sampling semantics require their own semantic routing and must not be forced into this batch merely to increase folder completeness.

## Relation Policy

The Activity entries may refer to canonical relations such as `part-of`, `participates-in`, `observes`, `represents`, `derived-from`, and `has-result` where those relation semantics apply.

Activity-specific relations not yet admitted to the canonical relation vocabulary must remain conceptual candidates until independently resolved and promoted. No provisional Activity entry is an authority for silently creating a new relation concept.

## Provenance and Evidence

The semantic synthesis for this batch is informed by W3C PROV/PROV-O, W3C SOSA/SSN, the International Vocabulary of Metrology (VIM), ISO process terminology, CIDOC CRM activity/measurement modelling, and the existing GIOP semantic architecture.

External sources provide evidence for analysis; GIOP canonical identity and status remain governed by the Foundation controls.

## Lifecycle

All entries in the current batch begin as `Provisional`. They require independent review, cross-layer validation, provenance/evidence verification, and scoped Gate-J promotion before becoming `Active` canonical content.

## Retrieval Anchors

`ACTIVITY`, `EXECUTION`, `OBSERVATION`, `MEASUREMENT`, `ACQUISITION`, `PROCESSING`, `CALIBRATION`, `PROCEDURE`, `PROCESS`, `RESULT`, `REPRESENTATION`, `PROVENANCE`, `TEMPORAL OCCURRENCE`
