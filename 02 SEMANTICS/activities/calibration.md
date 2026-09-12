# Calibration

**Semantic ID:** `SEM-ACTIVITY-CALIBRATION-001`  
**Preferred Name:** Calibration  
**Semantic Class:** Activity  
**Domain:** Metrology and instrument characterization  
**Status:** Active  
**Version:** 1.0.0  
**Primary Responsibility:** An Activity that establishes a relationship between quantity values provided by measurement standards and corresponding indications of a measuring system under specified conditions.

## 5W1H Orientation
### What
Calibration is an operation establishing a relationship between quantity values provided by measurement standards and corresponding measuring-system indications.
### Why
It provides a controlled basis for interpreting indications against reference quantity values and supports reliability, comparability, and traceability where applicable.
### Who
Qualified personnel, calibration laboratories, instrument specialists, automated systems, or authorized actors may perform it.
### Where
Laboratories, manufacturing, field settings, optical/imaging systems, sensor systems, measurement facilities, and controlled calibration environments.
### When
Calibration is temporally situated; calibration status and validity change over time and require lifecycle management.
### How
Calibration uses standards, a measuring system, a procedure, and specified conditions to establish the relevant relationship. Generated calibration information may support later measurements.

## Semantic Definition
**Calibration** is an Activity that establishes a relationship between quantity values provided by measurement standards and corresponding indications of a measuring system under specified conditions. It is distinct from adjustment, verification, maintenance, and calibration information/result.

## Semantic Responsibility
Calibration owns the occurrence-level operation of establishing or determining the relevant relationship between reference quantity values and measuring-system indications.

## Core Distinctions
`Calibration ≠ Adjustment`: adjustment changes/configures a system; calibration establishes/determines the relationship.  
`Calibration ≠ Verification`: verification provides evidence that requirements are fulfilled.  
`Calibration ≠ Maintenance`: maintenance preserves/restores functional condition.  
`Calibration ≠ Measurement`: calibration establishes a standards-to-indication relationship; measurement obtains quantity value(s).  
`Calibration ≠ Calibration Result`: information, curves, certificates, or records are outputs.

## Calibration Context
Relevant context may include measurement standards, reference values, measuring system, indications, calibration procedure, environmental/optical Conditions, instrument State, uncertainty information, traceability, date, and validity context.

## Imaging and Sensor Context
Calibration may apply to Cameras, Sensors, optical systems, displays, measuring systems, and other instrumentation. The calibrated system remains an entity; calibration is the activity performed on or with it.

## Temporal Semantics
Distinguish calibration activity time, reference conditions, generated calibration information, and later measurement time. Validity must be managed through lifecycle information.

## Inputs and Outputs
Inputs may include standards, reference values, measuring system, indications, procedure, conditions, configurations, and prior calibration information. Outputs may include calibration data, coefficients, curves, records, certificates, or other Results/Representations.

## Trust / Provenance
Preserve standards used, procedure, measuring-system identity/configuration, conditions, dates, generated calibration information, authority, validation state, and traceability where applicable. Do not imply validity beyond established scope/evidence.

## Validation
Cross-layer validation preserves the metrological distinctions among Calibration, Measurement, Adjustment, Verification, Maintenance, Measuring System, Condition, Procedure, and Result. The entry is approved for active canonical use within the scoped Activity batch.

## Lifecycle
**Current state:** Active canonical semantic entry.  
**Version:** 1.0.0  
**Promotion path:** Authored → Integrated → Validated → Approved → Active Canonical.

## Relations
Canonical `participates-in`, `has-result`, `part-of`, and `derived-from` may be used where applicable. Other calibration dependencies remain explicit but are not silently promoted as relation vocabulary.

## Retrieval Anchors
`CALIBRATION`, `CALIBRATE`, `CALIBRATION ACTIVITY`, `CALIBRATION OPERATION`, `MEASUREMENT STANDARD`, `MEASURING SYSTEM`, `INDICATION`, `TRACEABILITY`, `ADJUSTMENT`, `VERIFICATION`, `MAINTENANCE`

## Evidence / Source Basis
Semantic synthesis is informed principally by the International Vocabulary of Metrology (VIM), W3C provenance/activity semantics, and GIOP's Measuring System, Condition, Procedure, Quantity, Activity, and Result boundaries.
