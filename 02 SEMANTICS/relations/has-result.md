# Has Result

## Identity / Metadata

- Semantic ID: `SEM-RELATION-HAS-RESULT-001`
- Preferred Name: Has Result
- Artifact Type: Semantic Relation
- Primary Responsibility: Relation
- Relation Family: Result / Output
- Status: Active — Scoped Canonical
- Version: 1.0.0
- Domain: Activity / Execution
- Range: Result

## 5W1H Orientation

### What

`has-result` is a directed relation connecting an activity or execution to a result produced or yielded by that occurrence.

### Why

It makes the operational and provenance connection between an occurrence and its result explicit while keeping the activity and result semantically distinct.

### Who / Subject

An eligible Activity or Execution, including specialized activity types such as Observation, Measurement, Acquisition, Processing, or Calibration where a result is produced.

### What / Object

An eligible Result.

### Where

Where a concrete activity/execution has a result relationship supported by the applicable procedure, execution record, provenance, or other authoritative evidence.

### When

The assertion may be qualified by execution time, result time, phenomenon time, procedure, configuration, or provenance where those distinctions matter.

### How

By asserting that the subject activity/execution produced or yielded the object result under the applicable GIOP activity and result semantics.

## Semantic Definition

`has-result` denotes a result-producing relationship in which an Activity or Execution is connected to a Result that it produces or yields as part of its occurrence.

The relation does not define the internal structure, numerical content, validity, representation, display form, or interpretation of the Result.

## Relation Family

Result / Output.

## Subject / Domain

Primary domain: Activity or Execution.

## Object / Range

Primary range: Result.

## Directionality

`Activity / Execution → Result`.

The direction follows the operational provenance path from an occurring activity toward the output/result associated with that occurrence.

## Inverse

The inverse expression `is-result-of` may be used for retrieval or graph traversal. Its use does not automatically create a separately canonical GIOP relation artifact.

## Logical Characteristics

No additional global logical characteristics are asserted beyond the defined direction and domain/range semantics. Cardinality is intentionally not fixed at the relation-definition level because applicable GIOP record profiles may permit one or multiple results.

## Qualification / Context

A concrete assertion may require:

- activity/execution identity;
- result identity;
- execution time;
- result time;
- phenomenon time where applicable;
- procedure or method;
- instrument/system configuration;
- provenance and evidence;
- assertion or validation status.

These qualifiers describe an assertion and do not change the core meaning of `has-result`.

## Core Distinctions / Non-equivalence

`has-result` is distinct from:

- `derived-from`, which describes derivational lineage;
- `represents`, which describes representational correspondence;
- `part-of`, which describes structural constitution;
- `participates-in`, which describes participation in an occurrence;
- `has-value`, which would connect an information object to a value rather than identify its producing occurrence.

## What This Relation Does Not Mean

`has-result` does not by itself imply:

- that the result is correct, valid, or fit for purpose;
- that the result is a measurement result;
- that the producing activity is a measurement;
- that the result is numeric;
- that the result is a representation or display;
- that the result has only one source input;
- that the result is causally related to every entity used by the activity;
- that the result is unique.

## Inference Boundary

Permitted: the relation supports traversal from a producing activity/execution to its associated result.

Conditional: a result may be further classified according to the producing activity and result semantics, but that classification requires independent evidence.

Prohibited: `has-result` must not be used alone to infer measurement status, correctness, causality, representation type, uniqueness, or cardinality.

## Cross-Layer Significance

`has-result` connects the Activity layer to the Result layer. In the GIOP operational chain it supports:

`Scene / Object / Conditions → Procedure → Activity / Execution → Result → Representation`.

It therefore provides a controlled bridge between an occurrence and the information/output associated with that occurrence.

## Typical GIOP Usage

- Measurement → has-result → Measurement Result
- Observation → has-result → Observation Result
- Acquisition → has-result → Acquired Result or Representation where the applicable result semantics permit it
- Processing → has-result → Processed Result

These are semantic usage patterns, not instance assertions.

## Trust / Evidence / Validation

A concrete `has-result` assertion should be supported by the activity/execution record, procedure/execution evidence, or other authoritative provenance. Validation should verify that the subject and object conform to the applicable Activity/Execution and Result semantics.

Provenance, evidence, authority, confidence, and validation status remain distinct dimensions.

## Machine / AI Interpretation

Canonical predicate: `SEM-RELATION-HAS-RESULT-001`

Subject role: Activity / Execution

Object role: Result

Direction: producing occurrence → result

Assertion status: asserted or inferred, represented separately by the consuming graph system.

Inference restriction: do not infer result type, validity, uniqueness, measurement status, representation type, or causal responsibility from this predicate alone.

## Lifecycle

Current state: Active canonical semantic relation within the scoped Relation implementation batch. Future changes require the applicable GIOP validation and promotion process.

## Retrieval Anchors

`HAS RESULT`, `has-result`, `IS RESULT OF`, `is-result-of`, `EXECUTION RESULT`, `OBSERVATION RESULT`, `MEASUREMENT RESULT`, `COMPUTATIONAL RESULT`, `RESULT PROVENANCE`

## Semantic Boundary

Relation: Activity / Execution → Result.

Result content remains the responsibility of the Result semantic layer. Activity/execution semantics remain the responsibility of the Activity layer. The relation establishes only the canonical semantic connection between them.
