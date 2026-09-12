# Execution

**Semantic ID:** `SEM-ACTIVITY-EXECUTION-001`  
**Preferred Name:** Execution  
**Semantic Class:** Activity  
**Domain:** Cross-domain operational semantics  
**Status:** Provisional  
**Version:** 0.1.0  
**Primary Responsibility:** A concrete occurrence in which a defined Procedure is carried out.

## 5W1H Orientation

### What

Execution is the occurrence of carrying out a defined Procedure or operational specification.

### Why

Execution distinguishes the actual carrying-out of a prescribed method from the Procedure itself. This makes reproducibility, provenance, timing, participation, inputs, and outputs representable at occurrence level.

### Who

Execution may be performed by a human Agent, instrument, System, software environment, or coordinated set of participants, depending on the Procedure.

### Where

Execution may occur in physical, laboratory, imaging, measurement, computational, simulated, or virtual environments.

### When

Execution is time-bounded or otherwise temporally situated. The execution interval may differ from phenomenon time and result time.

### How

An Execution carries out a Procedure and may use inputs, involve participants, operate under Conditions or States, and generate Results or other entities.

## Semantic Definition

**Execution** is an Activity occurrence in which a specified Procedure is actually carried out. It represents the performed instance of a method rather than the method specification itself.

## Semantic Responsibility

Execution is used when the important semantic fact is that a Procedure was actually enacted. It therefore provides an occurrence-level bridge between procedural specification and observed, measured, sampled, actuated, acquired, or otherwise produced outcomes.

## Core Distinctions

### Execution vs Activity

Execution is a specialized procedure-driven Activity pattern. Activity is the broader occurrence concept. Not every Activity must be represented as an Execution.

### Execution vs Procedure

Procedure describes how an operation should be performed. Execution records that the operation was actually carried out. `Execution ≠ Procedure`.

### Execution vs Process

A Process describes transformation, development, progression, or an organized course. Execution denotes a concrete carrying-out occurrence. `Execution ≠ Process`.

### Execution vs Result

Execution is the occurrence; Result is an output of that occurrence.

## Relation to Procedure

The primary relation is:

```text
Procedure → specifies → Execution
```

A Procedure may be executed repeatedly under different conditions and with different inputs.

## Relation to Specialized Activities

Observation and Measurement are important procedure-driven Activity patterns and may be represented as Executions where their procedural character is relevant.

```text
Activity
   └── Execution pattern
         ├── Observation
         └── Measurement
```

Sampling is a validated staged candidate for this pattern. Actuation is deferred from the current GIOP canonical batch.

Acquisition, Processing, and Calibration remain independent Activity concepts because their primary semantic responsibilities should not be reduced to the generic idea of execution.

## Temporal Semantics

Relevant execution information may include start time, end time, duration, phenomenon time, and result time. These values should remain distinct when they refer to different temporal events.

## Inputs and Outputs

An Execution may use entities required by its Procedure and may generate one or more Results or other entities. Inputs and outputs are Procedure- and execution-specific.

## Actors and Systems

The performing or participating entity may be:

- human Agent;
- organization or service;
- instrument or System;
- software or computational infrastructure;
- coordinated participants.

## Cross-Domain Significance

Execution is useful wherever GIOP must distinguish a reusable method from an occurrence of that method: measurement, observation, sampling, testing, laboratory work, computational workflows, and instrument operation.

## Trust / Provenance

Execution assertions should retain occurrence provenance, participating agent/system, relevant procedure identity, temporal information, inputs, outputs, evidence, validation state, and authority context where available.

External ontology or standards terminology supports this semantic synthesis but does not itself define GIOP authority.

## Validation Notes

The entry preserves the boundary that Execution is a procedure-driven Activity pattern rather than a universal parent of all Activity concepts.

## Lifecycle

**Current state:** Provisional semantic entry.  
**Next intended state:** Review → Validated → Active, subject to scoped validation and promotion.

## Relations

```text
Procedure → specifies → Execution
Agent / System → participates-in / performs → Execution
Execution → uses → Entity
Execution → produces → Result
Execution → may be informed by → Activity
```

## Retrieval Anchors

`EXECUTION`, `ACTUAL EXECUTION`, `PROCEDURE EXECUTION`, `PERFORMED PROCEDURE`, `ACTIVITY`, `OBSERVATION`, `MEASUREMENT`, `PROCEDURE`, `RESULT`

## Evidence / Source Basis

Semantic synthesis informed principally by W3C SOSA/SSN execution and observation modelling, W3C PROV activity semantics, and GIOP's established Procedure–Activity–Result separation.
