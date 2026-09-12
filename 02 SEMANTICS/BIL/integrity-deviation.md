# BIL Integrity Deviation

**Semantic ID:** `SEM-BIL-INTEGRITY-DEVIATION-001`  
**Preferred Name:** Integrity Deviation  
**Semantic Class:** BIL Control Concept  
**Domain:** Biological / Configurational Integrity  
**Status:** Candidate  
**Version:** 0.2.0

> **Integrity Deviation** is an observed or inferred difference between a reference-defined expectation and an evaluated target within a declared integrity scope.

## 5W1H Orientation

### What
A difference detected between expected/reference configuration and observed/evaluated target.

### Why
A difference is not automatically an integrity failure. It must be interpreted against constraints, permitted variation, uncertainty and transformation intent.

### Who
Relevant to imaging scientists, validation engineers, VFX teams, researchers and machine evaluation systems.

### Where
Identity, geometry, morphology, state, interaction, appearance, temporal, spatial and contextual comparisons.

### When
At a declared comparison point, interval or transformation stage.

### How
`Reference Expectation → Target Observation → Difference Description/Measurement → BIL Interpretation`.

## Semantic Definition

**Integrity Deviation** is the BIL control concept denoting a reference-relative difference identified for a specified integrity claim.

## Core Distinctions

Deviation ≠ failure; ≠ error; ≠ drift; ≠ violation; ≠ permitted variation. Deviation becomes a failure only when the applicable policy interprets it as such.

## Scope and Boundary

Magnitude may be qualitative or quantitative. Numerical magnitude, units and measurement procedure belong to the relevant Quantity/Measurement/Result semantics.

## Cross-Domain Significance

`Reference → Target → Deviation → Constraint / Permitted Variation → Validation → Decision`.

BIL owns interpretation; existing semantic layers own the measured quantities, observations, states and relations.

## Trust and Evidence

Deviation evidence must retain measurement method, uncertainty, observability, reference identity and provenance.

## Visitor Universe

D0 explains difference; D1 distinguishes deviation from failure; D2 gives domain examples; D3 exposes measurement/uncertainty; D4 exposes machine deviation records.

## Lifecycle

`Candidate → Review → Validated → Approved → Active` or `Deferred / Superseded / Archived`.

## Retrieval Anchors

`INTEGRITY DEVIATION`, `REFERENCE DEVIATION`, `DEVIATION MAGNITUDE`, `PERMITTED VARIATION`, `BIL`
