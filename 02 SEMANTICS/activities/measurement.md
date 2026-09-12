# Measurement

**Semantic ID:** `SEM-ACTIVITY-MEASUREMENT-001`  
**Preferred Name:** Measurement  
**Semantic Class:** Activity  
**Domain:** Measurement science  
**Status:** Provisional  
**Version:** 0.1.0  
**Primary Responsibility:** An Activity in which one or more quantity values attributable to a quantity are experimentally obtained.

## 5W1H Orientation

### What

Measurement is the activity of experimentally obtaining one or more quantity values attributable to a quantity.

### Why

Measurement separates the act of obtaining quantitative information from the quantity being measured and from the resulting value or result record.

### Who

Measurement may be performed by a human operator, Measuring System, instrument, automated system, or coordinated measurement setup.

### Where

Measurement may occur in laboratories, physical scenes, imaging systems, industrial environments, field systems, calibration environments, simulations, or other defined measurement contexts.

### When

Measurement occurs over a defined temporal context. The measurement activity time may differ from the phenomenon time and from the time at which the result is reported.

### How

Measurement follows or is governed by a Measurement Procedure or method, uses a Measuring System and relevant inputs, occurs under Conditions, concerns a Measurand, and produces a Measurement Result.

## Semantic Definition

**Measurement** is an Activity consisting of experimentally obtaining one or more quantity values attributable to a quantity.

Measurement is a quantitative obtaining activity. It does not denote the quantity itself, the quantity intended to be measured, the procedure used, the measuring system, or the resulting value/result record.

## Semantic Responsibility

Measurement owns the occurrence-level act of experimentally obtaining quantity value(s). It therefore belongs in the Activity layer rather than the Quantity or Result layer.

## Core Distinctions

### Measurement vs Quantity

Quantity is the measurable concept or kind. Measurement is the activity of obtaining value(s) attributable to that quantity.

`Measurement ≠ Quantity`.

### Measurement vs Measurand

A Measurand is the quantity intended to be measured in a particular measurement context. Measurement is the activity that obtains value(s) for it.

`Measurement ≠ Measurand`.

### Measurement vs Measurement Procedure

Measurement Procedure describes how a measurement is to be performed. Measurement is the actual occurrence of obtaining the values.

### Measurement vs Measurement Result

Measurement is the activity. Measurement Result is the output information containing the obtained quantity values and relevant information.

### Measurement vs Observation

Measurement and Observation are adjacent Activity concepts. Observation may obtain information without producing a quantity value. Measurement is specifically quantitative. `Observation ≠ Measurement` as a canonical identity rule.

## Measurement Context

A complete measurement interpretation may depend on:

- Measurand;
- Quantity;
- measurement procedure;
- measuring system;
- Conditions;
- relevant States;
- measurement standards or references;
- uncertainty and other result information where applicable;
- temporal context;
- traceability requirements.

These concepts remain semantically separate in GIOP.

## Measurement Chain

```text
Quantity
   ↓
Measurand specification
   ↓
Measurement Procedure
   ↓
Measurement Activity
   ↓
Measurement Result
```

The Measurement Activity may use a Measuring System and occur under specified Conditions.

## Imaging and Optical Context

In imaging, measurement may concern quantities derived from radiometric, geometric, photometric, sensor, material, or system observations. An image may be an input, intermediate representation, or result depending on the measurement procedure. The existence of an image does not by itself make an activity a Measurement.

## Temporal Semantics

Measurement records should distinguish, when applicable:

- activity start/end;
- phenomenon time;
- acquisition time;
- result time.

The values must not be conflated when they describe different temporal events.

## Inputs and Outputs

Typical inputs include the measurand context, Scene/Object/Material, Conditions, Measuring System, measurement standards, Procedure, acquired data, and relevant prior information.

The primary output is a Measurement Result. Intermediate representations or data may also be generated.

## Trust / Provenance

Measurement claims are evidence-sensitive. Where quantitative claims are recorded, provenance should preserve the measurement procedure, measuring system, conditions, relevant standards or references, result information, validation state, authority, confidence/review state, and version/date as applicable.

A canonical GIOP definition is a semantic synthesis; numerical values in individual measurement records require their own provenance and evidence.

## Validation Notes

This entry preserves the VIM distinction among Measurement, Measurand, Measurement Procedure, and Measurement Result. It also preserves GIOP's distinction between Quantity as measurable concept and Measurement as obtaining activity.

## Lifecycle

**Current state:** Provisional semantic entry.  
**Next intended state:** Review → Validated → Active, subject to scoped validation and promotion.

## Relations

```text
Measurement Procedure → specifies → Measurement
Measurement → concerns → Measurand / Quantity
Measurement → uses → Measuring System
Measurement → occurs-under → Condition / State
Measurement → produces → Measurement Result
Agent / System → performs / participates-in → Measurement
```

## Retrieval Anchors

`MEASUREMENT`, `MEASUREMENT ACTIVITY`, `MEASURE`, `QUANTITY VALUE`, `MEASURAND`, `MEASUREMENT PROCEDURE`, `MEASURING SYSTEM`, `MEASUREMENT RESULT`, `OBSERVATION`, `CALIBRATION`

## Evidence / Source Basis

Semantic synthesis informed principally by the International Vocabulary of Metrology (VIM), W3C SOSA/SSN execution and observation modelling, CIDOC CRM measurement modelling, and GIOP's existing Quantity, Procedure, Measuring System, Condition, Result, and Relation semantics.
