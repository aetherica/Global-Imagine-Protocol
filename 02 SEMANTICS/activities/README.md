# GIOP Activity Semantics

## Status

**ACTIVE CANONICAL — SCOPED ACTIVITY BATCH**

This directory is the canonical semantic home for the occurrence-level Activity concepts admitted to the Activity batch. The batch has completed scoped semantic validation and promotion approval.

## Purpose

The Activity layer represents what actually happens: an occurrence of doing, observing, measuring, acquiring, transforming, calibrating, or otherwise performing an operation.

```text
Procedure       = prescribed/specification-level way of doing
Activity        = actual occurrence
Process         = transformation, development, progression, or organized temporal course
Result          = output of an occurrence
Representation  = information-bearing form
```

## Active Canonical Batch

1. `activity.md` — Activity
2. `execution.md` — Execution
3. `observation.md` — Observation
4. `measurement.md` — Measurement
5. `acquisition.md` — Acquisition
6. `processing.md` — Processing
7. `calibration.md` — Calibration

All seven entries are version `1.0.0` and have Active canonical status under the scoped Activity promotion decision.

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

## Activity ↔ Process Boundary

Activity is the occurrence layer: a concrete temporal happening or operation. Process is the broader transformation, development, progression, or organized temporal course. A Process may organize or contain multiple Activities; an Activity is not automatically a Process merely because it takes time.

## Procedure ↔ Activity ↔ Result

A Procedure describes how an operation is to be performed. An Activity records the occurrence. A Result is generated information/output. This separation is preserved throughout the batch. Activity-specific directional dependencies such as `specifies`, `uses`, and `produces` are explanatory unless separately admitted to canonical relation vocabulary.

## Observation ↔ Measurement

Observation is an information-obtaining activity with broader epistemic scope. Measurement is specifically concerned with experimentally obtaining quantity value(s). The Activity batch intentionally does not impose a universal subclass relation between them.

## Acquisition ↔ Camera / Lens / Sensor

Camera, Lens, and Sensor remain system/component entities. Acquisition is the actual information-capture occurrence. The established acquisition subsystem remains conceptually `Camera → Lens → Sensor`; Acquisition is the operational occurrence using or enabled by that subsystem, not another component in the hardware hierarchy.

## Processing ↔ Algorithm / Software / Process

Algorithm is a computational method; Software is an implementation artifact; Processing is the actual operation. A broader Process may include processing activities. Lexical similarity does not determine semantic placement.

## Calibration Boundary

Calibration is the metrological operation establishing a relationship between reference quantity values and measuring-system indications. Adjustment, Verification, and Maintenance remain distinct activity concepts and are not silently collapsed into Calibration.

## Visitor Universe

The Activity layer contains one canonical body of knowledge. Visitor Universe does not create audience-specific semantic entries or duplicate knowledge.

```text
Canonical Activity Knowledge
        ↓
Visitor Universe
        ↓
Entry / Traversal Depth
        ↓
Human or Machine Consumption
```

Novice, professional, and expert visitors may receive different entry depth, orientation, navigation, and technical detail, but the underlying semantic identity, boundary, provenance, lifecycle, and canonical truth remain one.

## Deferred Concepts

The following remain intentionally staged for separate semantic work:

- Sampling
- Assessment
- Evaluation
- Verification
- Adjustment
- Actuation
- Measurand
- Sample
- Measurement standards and specialized sampling semantics

Deferred concepts are not absent because they are unimportant; they require separate routing and boundary validation.

## Relation Policy

Canonical relations already admitted by GIOP may be used where their semantics apply, including `part-of`, `participates-in`, `observes`, `represents`, `derived-from`, and `has-result`. Activity entries do not silently create new relation authority. New relation concepts require independent semantic authoring, validation, and promotion.

## Provenance and Evidence

The Activity batch is informed by W3C PROV/PROV-O, W3C SOSA/SSN, International Vocabulary of Metrology (VIM), ISO process terminology, CIDOC CRM activity/measurement modelling, and the existing GIOP semantic architecture. External sources are evidence for semantic analysis; GIOP Foundation controls govern canonical identity and lifecycle.

## Validation and Promotion

The batch was checked for identity, semantic responsibility, authoring structure, provenance/evidence, cross-layer boundaries, duplicate authority, lifecycle/versioning, trust metadata, and scoped Gate-J approval. The resulting state transition is:

`AUTHORED → INTEGRATED → VALIDATED → APPROVED → ACTIVE CANONICAL`

Validation is scoped to this Activity batch and does not waive gates for future concepts.

## Retrieval Anchors

`ACTIVITY`, `EXECUTION`, `OBSERVATION`, `MEASUREMENT`, `ACQUISITION`, `PROCESSING`, `CALIBRATION`, `PROCEDURE`, `PROCESS`, `RESULT`, `REPRESENTATION`, `PROVENANCE`, `TEMPORAL OCCURRENCE`
