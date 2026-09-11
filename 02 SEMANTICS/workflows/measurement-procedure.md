# Measurement Procedure

**Semantic ID:** `SEM-WORKFLOW-MEASUREMENT-PROCEDURE-001`  
**Preferred Name:** Measurement Procedure  
**Artifact Type:** Workflow Specification  
**Primary Responsibility:** Procedure Specification  
**Domain:** Measurement / Metrology / Imaging  
**Status:** Provisional  
**Version:** 0.1.0

> A Measurement Procedure is a detailed specification of how a measurement is to be carried out, including the relevant measurement principle or method, measurement model, operations, calculations, and conditions required to obtain a measurement result.

## What

A Measurement Procedure specifies the operational organization of a measurement. It may define the measurand, principle, method, measuring system, conditions, inputs, operations, calculations, corrections, acceptance criteria, and expected outputs.

## Why

A measurement result is not meaningful merely because a number exists. The procedure establishes how the result was produced and provides the reproducibility and interpretability context needed for technical use.

## Structure

A procedure may contain:

- measurand definition;
- measurement principle;
- measurement method;
- measurement model;
- measuring system;
- required conditions;
- inputs and reference values;
- operational steps;
- calculations and corrections;
- acceptance criteria;
- uncertainty or quality requirements;
- expected result structure;
- repeatability/reproducibility requirements;
- version and provenance information.

## How

A procedure is applied through an execution or measurement activity. The procedure itself is reusable specification; its execution is a particular occurrence.

## Where

It applies to laboratory measurements, camera and sensor characterization, optical metrology, calibration, testing, industrial measurement, imaging science, and other controlled measurement contexts.

## Who

It is relevant to metrologists, scientists, engineers, laboratory operators, calibration personnel, sensor specialists, and software or machine-readable measurement systems.

## Core Distinctions

### Procedure vs Measurement

A procedure specifies how measurement is carried out. Measurement is the activity or process of obtaining quantity values.

### Procedure vs Measurement Result

A procedure produces the specification for obtaining a result; it is not itself a result.

### Procedure vs Algorithm

A procedure may contain or invoke calculations or computational methods, but a procedure is operational and contextual while an algorithm is an implementation-independent computational method.

### Procedure vs Execution

A procedure can be reused. An execution is a particular act of carrying it out with a defined system and context.

## Relations

Potential canonical relations include `specifies`, `used-for-execution`, `implemented-by`, `has-input`, `has-output`, `requires-condition`, and `produces-result` through execution.

## Provenance / Validation

A procedure should record its normative or scientific source, version, applicable standards, validation status, known limitations, and any conditions under which its claimed performance is established.

## Trust

A measurement procedure should not be presented as validated merely because it is detailed. Validation requires evidence that the procedure is fit for its intended purpose and that its assumptions, calculations, conditions, and performance have been appropriately assessed.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`MEASUREMENT PROCEDURE`, `MEASUREMENT METHOD`, `MEASUREMENT MODEL`, `MEASURAND`, `MEASUREMENT PRINCIPLE`, `MEASURING SYSTEM`, `UNCERTAINTY`, `REPEATABILITY`, `REPRODUCIBILITY`
