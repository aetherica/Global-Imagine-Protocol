# GIOP Process Semantics

## Status

**ACTIVE CANONICAL — SCOPED PROCESS BATCH**

This directory is the canonical semantic home for process-level concepts admitted to the Process batch. The batch establishes the boundary between Process, Activity, Procedure, Result, State, and Representation without creating audience-specific semantic duplicates.

## Purpose

The Process layer represents an organized temporal course, transformation, development, or progression in which interrelated or interacting activities use, transform, or organize inputs toward one or more results.

```text
Procedure      = prescribed/specification-level way of doing
Activity       = actual occurrence of doing/observing/measuring/etc.
Process        = organized temporal course / transformation / progression
Result         = output or generated information of an occurrence or process
State          = recognized mode/condition at a temporal locus
Representation = information-bearing form
```

## Active Canonical Batch

1. `process.md` — Process

The Process nucleus is intentionally small. A general Process concept is canonical; specialized process concepts remain candidates until their independent semantic responsibilities and cross-layer boundaries are validated.

## Controlled Candidates

The following are retained as candidates rather than silently promoted:

- Transformation Process
- Development Process
- Operational Process
- Workflow Process

These terms have substantial domain and methodological variation. They require individual promotion gates and must not become implicit subclasses merely because they occur in process descriptions.

## Core Boundary Rules

```text
Process ≠ Activity
Process ≠ Procedure
Process ≠ Result
Process ≠ State
Process ≠ Condition
Process ≠ Context
Process ≠ Representation
Process ≠ Algorithm
Process ≠ Software
Process ≠ Workflow document
Process ≠ Project
Process ≠ Method
```

A Process may organize multiple Activities. An Activity is an occurrence; a Process is the broader organized course in which occurrences may participate. A Procedure specifies how something is to be done; it is not the occurrence or the process itself.

## Process ↔ Activity

The relationship is compositional and contextual, not an automatic identity or universal inheritance rule. A process can consist of or organize multiple activities, while an activity can occur within a process. Duration alone does not convert an Activity into a Process.

## Process ↔ Procedure

A Procedure is a specification or prescribed method for performing an operation. A Process is the organized course that occurs or is realized through activities. The same Procedure may be applied in multiple Processes, and a Process may involve multiple Procedures.

## Process ↔ Result

A Process can deliver or contribute to one or more Results. Result semantics remain separate so that a result can be represented, evaluated, measured, preserved, or reused independently of the process that produced or contributed to it.

## Process ↔ State / Condition

A Process can cause, maintain, or be evaluated under states and conditions, but it is neither a State nor a Condition. A State describes a recognized mode of a bearer at a temporal locus; a Condition describes relevant environmental/operational circumstances. Process is the temporal course of organized change or operation.

## Process ↔ Representation

A Process can transform, generate, or work with information that is expressed through Representations. Representation remains the information-bearing form; Process remains the organized course of operation. A file, serialization, encoding, or display must not be reclassified as a Process merely because a process operates on it.

## Process ↔ Algorithm / Software

An Algorithm is a computational method. Software is an implementation artifact. A Process is the organized occurrence/course in which methods and software may be used. The presence of computation does not make a Process an Algorithm or Software.

## Visitor Universe

The Process layer contains one canonical body of knowledge. Visitor Universe changes entry depth, navigation, explanatory density, and retrieval strategy; it does not create visitor-specific process concepts.

```text
Canonical Process Knowledge
        ↓
Visitor Universe
        ↓
Entry / Traversal Depth
        ↓
Human or Machine Consumption
```

## Relation Policy

Only relations already admitted to GIOP may be used where their semantics apply, including `part-of`, `participates-in`, `observes`, `represents`, `derived-from`, and `has-result`. Process-specific terms such as `contains-activity`, `transforms`, `has-input`, `has-output`, `implements`, or `follows` are not silently promoted to canonical relation authority by this batch.

## Provenance and Evidence

The batch is informed by ISO 9000 process terminology, W3C PROV-O, CIDOC CRM, the existing GIOP Activity semantics, and the GIOP Foundation authoring/canonicalization rules. External standards are evidence for semantic analysis; GIOP Foundation controls canonical identity and lifecycle.

## Validation and Promotion

The Process batch is evaluated through identity, responsibility, existing-entry, boundary, relation-authority, provenance/evidence, Visitor Universe, retrieval, lifecycle, and cross-layer validation gates.

The canonical Process entry is promoted only for the generic process responsibility. Specialized candidates remain explicitly controlled candidates.

## Retrieval Anchors

`PROCESS`, `ACTIVITY`, `PROCEDURE`, `TRANSFORMATION`, `DEVELOPMENT`, `OPERATIONAL COURSE`, `WORKFLOW`, `RESULT`, `TEMPORAL COURSE`, `INPUT`, `OUTPUT`, `PROVENANCE`
