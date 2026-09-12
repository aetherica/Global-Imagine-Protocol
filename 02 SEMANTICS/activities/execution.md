# Execution

**Semantic ID:** `SEM-ACTIVITY-EXECUTION-001`  
**Preferred Name:** Execution  
**Semantic Class:** Activity  
**Domain:** Cross-domain operational semantics  
**Status:** Active  
**Version:** 1.0.0  
**Primary Responsibility:** A concrete occurrence in which a defined Procedure is carried out.

## 5W1H Orientation
### What
Execution is the occurrence of carrying out a defined Procedure or operational specification.
### Why
It distinguishes actual enactment from the Procedure itself and enables reproducibility, provenance, timing, participation, inputs, and outputs to be represented at occurrence level.
### Who
A human Agent, instrument, System, software environment, or coordinated participants may perform an Execution.
### Where
Physical, laboratory, imaging, measurement, computational, simulated, and virtual environments.
### When
Execution is temporally situated; execution time may differ from phenomenon time and result time.
### How
An Execution carries out a Procedure and may use inputs, involve participants, operate under Conditions or States, and generate Results or other entities.

## Semantic Definition
**Execution** is an Activity occurrence in which a specified Procedure is actually carried out. It represents the performed instance of a method rather than the method specification itself.

## Semantic Responsibility
Execution is used when the important semantic fact is that a Procedure was actually enacted. It is a procedure-driven Activity pattern, not a universal parent for all Activity concepts.

## Core Distinctions
`Execution ≠ Activity`: Execution is narrower and procedure-driven.  
`Execution ≠ Procedure`: Procedure specifies; Execution enacts.  
`Execution ≠ Process`: Process denotes transformation, development, progression, or an organized course.  
`Execution ≠ Result`: Execution is the occurrence; Result is an output.

## Relation to Procedure
The semantic dependency is `Procedure → specifies → Execution`; the relation label remains conceptual unless separately admitted to canonical relation vocabulary.

## Relation to Specialized Activities
Observation and Measurement may be represented as procedure-driven Executions where their procedural character is relevant. Sampling is staged for later work. Acquisition, Processing, and Calibration remain independent Activity concepts.

## Temporal Semantics
Relevant information may include start time, end time, duration, phenomenon time, and result time. Distinct temporal events must remain distinct.

## Inputs and Outputs
An Execution may use entities required by its Procedure and generate one or more Results or other entities. Inputs and outputs are Procedure- and occurrence-specific.

## Actors and Systems
Performers or participants may include humans, organizations/services, instruments, systems, software, or coordinated participants.

## Cross-Domain Significance
Execution is useful wherever GIOP must distinguish a reusable method from an occurrence of that method, including measurement, observation, testing, laboratory work, computational workflows, and instrument operation.

## Trust / Provenance
Execution assertions should retain occurrence provenance, Procedure identity, participating Agent/System, temporal information, inputs, outputs, evidence, validation state, and authority context where available.

## Validation
Cross-layer validation confirms the boundary between Activity, Execution, Procedure, Process, Result, Observation, and Measurement. The entry is approved for active canonical use within the scoped Activity batch.

## Lifecycle
**Current state:** Active canonical semantic entry.  
**Version:** 1.0.0  
**Promotion path:** Authored → Integrated → Validated → Approved → Active Canonical.

## Relations
Use canonical `participates-in`, `has-result`, `part-of`, `derived-from`, and `observes` where their established semantics apply. Procedure specification and other dependencies remain conceptual until separately promoted.

## Retrieval Anchors
`EXECUTION`, `ACTUAL EXECUTION`, `PROCEDURE EXECUTION`, `PERFORMED PROCEDURE`, `ACTIVITY`, `OBSERVATION`, `MEASUREMENT`, `PROCEDURE`, `RESULT`

## Evidence / Source Basis
Semantic synthesis is informed principally by W3C SOSA/SSN execution and observation modelling, W3C PROV activity semantics, and GIOP's Procedure–Activity–Result separation.
