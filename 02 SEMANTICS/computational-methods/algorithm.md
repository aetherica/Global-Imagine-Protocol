# Algorithm

**Semantic ID:** `SEM-COMPUTATIONAL-METHOD-ALGORITHM-001`  
**Preferred Name:** Algorithm  
**Artifact Type:** Computational Method  
**Primary Responsibility:** Computational Method  
**Domain:** Computation / Imaging / Measurement  
**Status:** Provisional  
**Version:** 0.1.0

> An Algorithm is an implementation-independent, sufficiently specified computational method that defines how inputs are transformed into prescribed outputs under stated assumptions and constraints.

## What

An algorithm is an ordered computational method with defined inputs, operations or transformations, outputs, termination behavior, and applicable assumptions or constraints.

## Why

Algorithm must remain independent from any one software implementation, runtime, user interface, or generated result. The same algorithm may have multiple implementations and may be applied to multiple datasets or executions.

## Structure

Where relevant, an algorithm record should define:

- inputs;
- outputs;
- transformations;
- parameters;
- assumptions;
- constraints;
- termination conditions;
- numerical behavior;
- complexity or resource requirements;
- validation criteria;
- provenance and version.

## How

An algorithm is realized through one or more implementations. An implementation may execute the algorithm with a defined runtime and input state, producing a result.

## Where

Algorithms occur in image processing, demosaicing, rendering, measurement, signal processing, computer vision, numerical analysis, machine learning, and other computational domains.

## Who

It is relevant to computational scientists, software engineers, imaging engineers, researchers, data scientists, metrologists, and AI systems.

## Core Distinctions

### Algorithm vs Software

An algorithm is an abstract computational method. Software is an implementation artifact containing executable programs, associated data, and related implementation material.

### Algorithm vs Procedure

A procedure describes an operational workflow or method of carrying out an activity. An algorithm specifies a computational transformation independent of the surrounding operational workflow.

### Algorithm vs Execution

An execution is a particular occurrence of carrying out a method or procedure. The algorithm is the reusable computational specification.

### Algorithm vs Result

A result is produced by an execution. The algorithm is the method that contributes to producing the result.

## Relations

Potential canonical relations include `implemented-by`, `used-by`, `takes-input`, `produces-output`, `has-parameter`, `validated-by`, and `version-of`.

## Validation

Algorithm validation should establish correctness or intended behavior against appropriate reference cases, test vectors, datasets, numerical tolerances, assumptions, and domain constraints.

## Trust

An algorithm should not be treated as validated merely because it is implemented or widely used. Claims about correctness, bias, numerical stability, performance, or applicability require explicit evidence appropriate to the claim.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`ALGORITHM`, `COMPUTATIONAL METHOD`, `INPUT`, `OUTPUT`, `TRANSFORMATION`, `PARAMETER`, `ASSUMPTION`, `CONSTRAINT`, `IMPLEMENTATION`, `VALIDATION`
