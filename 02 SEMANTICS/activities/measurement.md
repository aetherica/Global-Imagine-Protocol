# Measurement

**Semantic ID:** `SEM-ACTIVITY-MEASUREMENT-001`  
**Preferred Name:** Measurement  
**Semantic Class:** Activity  
**Domain:** Measurement science  
**Status:** Active  
**Version:** 1.0.0  
**Primary Responsibility:** An Activity in which one or more quantity values attributable to a quantity are experimentally obtained.

## 5W1H Orientation
### What
Measurement is the activity of experimentally obtaining one or more quantity values attributable to a quantity.
### Why
It separates quantitative obtaining from the quantity, measurand, procedure, measuring system, and resulting information.
### Who
A human operator, Measuring System, instrument, automated system, or coordinated setup may perform it.
### Where
Laboratories, physical scenes, imaging systems, industrial environments, field systems, calibration environments, simulations, or other defined contexts.
### When
Measurement occurs over a defined temporal context; activity time may differ from phenomenon and result time.
### How
Measurement follows or is governed by a Measurement Procedure or method, uses a Measuring System and relevant inputs, occurs under Conditions, concerns a Measurand, and produces a Measurement Result.

## Semantic Definition
**Measurement** is an Activity consisting of experimentally obtaining one or more quantity values attributable to a quantity. It does not denote the quantity, measurand, procedure, measuring system, or result.

## Semantic Responsibility
Measurement owns the occurrence-level act of experimentally obtaining quantity value(s), placing it in the Activity layer rather than Quantity or Result.

## Core Distinctions
`Measurement ≠ Quantity`: Quantity is the measurable concept/kind.  
`Measurement ≠ Measurand`: Measurand is the quantity intended to be measured in a context.  
`Measurement ≠ Measurement Procedure`: the latter specifies how.  
`Measurement ≠ Measurement Result`: the latter is generated output information.  
`Measurement ≠ Observation`: Observation is broader and need not produce quantity values.

## Measurement Context
Relevant context may include Measurand, Quantity, measurement procedure, Measuring System, Conditions, States, standards/references, uncertainty and result information, temporal context, and traceability requirements. These remain distinct GIOP concepts.

## Measurement Chain
```text
Quantity → Measurand specification → Measurement Procedure → Measurement Activity → Measurement Result
```

## Imaging and Optical Context
Measurement may concern radiometric, geometric, photometric, sensor, material, or system quantities derived from observations or images. An image may be input, intermediate representation, or result depending on the procedure; its existence does not make an activity a Measurement.

## Temporal Semantics
Distinguish activity start/end, phenomenon time, acquisition time, and result time when applicable.

## Inputs and Outputs
Inputs may include measurand context, Scene/Object/Material, Conditions, Measuring System, standards, Procedure, acquired data, and prior information. Primary output is Measurement Result; intermediate representations may also be generated.

## Trust / Provenance
Quantitative claims require provenance for procedure, measuring system, conditions, standards/references, result information, validation state, authority, confidence/review state, and version/date as applicable. Individual numerical records require their own evidence.

## Validation
Cross-layer validation preserves the VIM distinction among Measurement, Measurand, Measurement Procedure, and Measurement Result and the GIOP Quantity/Activity/Result boundaries. The entry is approved for active canonical use within the scoped Activity batch.

## Lifecycle
**Current state:** Active canonical semantic entry.  
**Version:** 1.0.0  
**Promotion path:** Authored → Integrated → Validated → Approved → Active Canonical.

## Relations
Canonical `participates-in`, `has-result`, `part-of`, and `derived-from` may be used where applicable. Procedure, Measurand, Quantity, and standards dependencies remain semantically explicit but are not silently introduced as new relation vocabulary.

## Retrieval Anchors
`MEASUREMENT`, `MEASUREMENT ACTIVITY`, `MEASURE`, `QUANTITY VALUE`, `MEASURAND`, `MEASUREMENT PROCEDURE`, `MEASURING SYSTEM`, `MEASUREMENT RESULT`, `OBSERVATION`, `CALIBRATION`

## Evidence / Source Basis
Semantic synthesis is informed principally by the International Vocabulary of Metrology (VIM), W3C SOSA/SSN execution and observation modelling, CIDOC CRM measurement modelling, and GIOP's Quantity, Procedure, Measuring System, Condition, Result, and Relation semantics.
