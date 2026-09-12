# Observation

**Semantic ID:** `SEM-ACTIVITY-OBSERVATION-001`  
**Preferred Name:** Observation  
**Semantic Class:** Activity  
**Domain:** Observation and imaging  
**Status:** Active  
**Version:** 1.0.0  
**Primary Responsibility:** An observation-oriented Activity in which information about a phenomenon, feature, property, or state is obtained.

## 5W1H Orientation
### What
Observation is an Activity in which an observer, sensor, instrument, system, or other observing entity obtains information about a phenomenon or feature of interest.
### Why
It represents information acquisition without requiring a numerical quantity value, supporting imaging, sensing, inspection, scientific observation, and categorical or structured outcomes.
### Who
A human observer, Sensor, Camera, Measuring System, software system, or other observing System may participate.
### Where
Physical scenes, laboratories, imaging systems, remote sensing, simulation, virtual environments, displays, or other observation contexts.
### When
Observation has temporal extent and may concern a phenomenon occurring at a different time; result availability may also occur later.
### How
An Observation may follow a method or Procedure, involve an observing System or Agent, concern a feature/property/phenomenon, and produce information.

## Semantic Definition
**Observation** is an Activity in which information about a phenomenon, feature, property, or state is obtained through an observing act. It may produce numerical, categorical, spatial, temporal, image-based, structured, or other information and is not restricted to quantitative measurement.

## Semantic Responsibility
Observation represents the act of obtaining or establishing information about something being observed.

## Core Distinctions
`Observation ≠ Measurement`: Observation is broader; Measurement specifically obtains quantity value(s).  
`Observer ≠ Observation`: Observer is the observing entity/model; Observation is the occurrence.  
`Sensor ≠ Observation`: Sensor is a sensing entity/system; Observation is the act.  
`Observation ≠ Result`: the result is what is obtained.  
`Observation ≠ Representation`: an image, table, geometry, signal, or category may represent the result.

## Feature, Property, and Phenomenon Context
Where relevant, an Observation should identify its feature/object of interest, observed property or characteristic, phenomenon, relevant Conditions and States, observing System/Agent, method/Procedure, and temporal context. These remain in their respective GIOP layers.

## Imaging Context
```text
Scene / Object → Conditions → Camera / Lens / Sensor → Observation / Acquisition Activity → Result → Representation / Display
```
Observation and Acquisition may co-occur but retain distinct responsibilities.

## Temporal Semantics
Relevant times include observation start/end, phenomenon time, and result time. Phenomenon time must not be assumed equal to execution or result time.

## Inputs and Outputs
Inputs may include Scene, Object, Surface, Light Source, Camera, Sensor, Measuring System, Procedure, Conditions, and States. Outputs may include an Observation Result, image, signal, categorical statement, geometry, measurement value, or other information-bearing entity.

## Cross-Domain Significance
Observation bridges phenomena and information across optical imaging, scientific observation, machine vision, inspection, remote sensing, experimental work, and computational observation systems.

## Trust / Provenance
Preserve observing system/agent, method, temporal and phenomenon context, generated result, conditions, source/evidence status, validation state, and relevant authority.

## Validation
Cross-layer validation confirms the boundary among Observation, Measurement, Observer, Sensor, Acquisition, Result, and Representation. No universal Observation↔Measurement subclass assertion is introduced. The entry is approved for active canonical use within the scoped Activity batch.

## Lifecycle
**Current state:** Active canonical semantic entry.  
**Version:** 1.0.0  
**Promotion path:** Authored → Integrated → Validated → Approved → Active Canonical.

## Relations
Canonical `observes`, `participates-in`, `has-result`, `part-of`, and `derived-from` may be used where applicable. Other dependencies remain conceptual until separately promoted.

## Retrieval Anchors
`OBSERVATION`, `OBSERVE`, `OBSERVING ACTIVITY`, `OBSERVATION RESULT`, `FEATURE OF INTEREST`, `OBSERVED PROPERTY`, `SENSOR`, `CAMERA`, `MEASUREMENT`, `ACQUISITION`

## Evidence / Source Basis
Semantic synthesis is informed principally by W3C SOSA/SSN Observation and Execution modelling, W3C PROV activity semantics, and GIOP's Observer, Camera, Sensor, Condition, Procedure, Result, and Representation boundaries.
