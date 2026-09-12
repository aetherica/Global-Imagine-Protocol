# Calibration

**Semantic ID:** `SEM-ACTIVITY-CALIBRATION-001`  
**Preferred Name:** Calibration  
**Semantic Class:** Activity  
**Domain:** Metrology and instrument characterization  
**Status:** Provisional  
**Version:** 0.1.0  
**Primary Responsibility:** An Activity that establishes a relationship between quantity values provided by measurement standards and corresponding indications of a measuring system under specified conditions.

## 5W1H Orientation

### What

Calibration is an operation that establishes a relationship between quantity values provided by measurement standards and the corresponding indications of a measuring system.

### Why

Calibration provides a controlled basis for understanding or using the indications of a measuring system in relation to reference quantity values. It supports measurement reliability, comparability, and traceability where applicable.

### Who

Calibration may be performed by qualified personnel, calibration laboratories, instrument specialists, automated systems, or other authorized actors using suitable standards and procedures.

### Where

Calibration may occur in laboratories, manufacturing environments, field settings, optical and imaging systems, sensor systems, measurement facilities, or controlled calibration environments.

### When

Calibration occurs at a defined time and under stated conditions. Calibration status may change over time and therefore requires lifecycle and validity management.

### How

Calibration uses measurement standards, a measuring system, a defined procedure, and specified conditions to establish a relationship between reference values and indications. The resulting calibration information may be used in subsequent measurements.

## Semantic Definition

**Calibration** is an Activity that establishes a relationship between quantity values provided by measurement standards and corresponding indications of a measuring system under specified conditions.

Calibration is an operation. It is not synonymous with adjustment, verification, maintenance, or a calibration result/document.

## Semantic Responsibility

Calibration owns the occurrence-level operation of establishing or determining the relevant relationship between reference quantity values and measuring-system indications.

## Core Distinctions

### Calibration vs Adjustment

Calibration establishes or determines the relationship between reference values and indications. Adjustment changes or configures a measuring system so that its indications behave as intended. They are distinct operations.

### Calibration vs Verification

Verification provides evidence that specified requirements are fulfilled. Calibration establishes the relevant relationship to measurement standards. A verification may use calibration information, but verification is not calibration.

### Calibration vs Maintenance

Maintenance preserves or restores functional condition. Calibration concerns metrological relationship to reference quantity values. Maintenance and calibration may be performed together operationally but remain distinct semantic activities.

### Calibration vs Measurement

Calibration is a specialized activity concerned with establishing the relationship between standards and indications. A subsequent Measurement uses a measuring system to obtain quantity value(s). Calibration may support measurement but is not identical to every measurement.

### Calibration vs Calibration Result

Calibration is the operation. Calibration information, relation, certificate, curve, or other output is generated information and is not the Activity itself.

## Calibration Context

Relevant context may include:

- measurement standards;
- reference quantity values;
- measuring system;
- indications;
- calibration procedure;
- environmental and optical Conditions;
- instrument State;
- uncertainty and associated information where applicable;
- traceability information;
- calibration date and validity context.

These remain semantically distinct GIOP concepts.

## Imaging and Sensor Context

Calibration may apply to Cameras, Sensors, optical systems, displays, measuring systems, and other instrumentation. The calibrated system remains a Class/entity; calibration is the activity performed on or with that system.

## Temporal Semantics

Calibration is temporally situated. The calibration activity time, standard reference conditions, generated calibration information, and later measurement time may be different temporal events.

Calibration status and validity must therefore be managed through lifecycle information rather than inferred solely from the existence of a calibration record.

## Inputs and Outputs

Inputs may include measurement standards, reference values, measuring system, indications, calibration procedure, conditions, configurations, and prior calibration information.

Outputs may include calibration relation, calibration data, coefficients, curves, records, certificates, or other Results/Representations, subject to the specific calibration method.

## Trust / Provenance

Calibration evidence is highly provenance-sensitive. Records should preserve the standards used, procedure, measuring system identity/configuration, relevant conditions, dates, generated calibration information, authority, validation state, and traceability information where applicable.

A calibration statement must not imply validity beyond the conditions, scope, or evidence actually established.

## Validation Notes

The entry preserves the metrological distinction among Calibration, Measurement, Adjustment, Verification, and Maintenance. Calibration information is treated as generated information/result rather than the calibration occurrence itself.

## Lifecycle

**Current state:** Provisional semantic entry.  
**Next intended state:** Review → Validated → Active, subject to scoped validation and promotion.

## Relations

```text
Calibration Procedure → specifies → Calibration
Calibration → uses → Measurement Standard
Calibration → uses → Measuring System
Calibration → occurs-under → Condition / State
Agent / System → performs / participates-in → Calibration
Calibration → produces → Calibration Information / Result
Calibration → supports → Measurement
```

## Retrieval Anchors

`CALIBRATION`, `CALIBRATE`, `CALIBRATION ACTIVITY`, `CALIBRATION OPERATION`, `MEASUREMENT STANDARD`, `MEASURING SYSTEM`, `INDICATION`, `TRACEABILITY`, `ADJUSTMENT`, `VERIFICATION`, `MAINTENANCE`

## Evidence / Source Basis

Semantic synthesis informed principally by the International Vocabulary of Metrology (VIM), W3C provenance/activity semantics, and GIOP's existing Measuring System, Condition, Procedure, Quantity, Activity, and Result boundaries.
