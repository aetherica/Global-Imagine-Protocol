# Sensitivity

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-SENSITIVITY-001
- **Canonical Label:** Sensitivity
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Sensitivity is a characteristic describing how a defined system's response depends on changes in a defined input or measurand under a specified context.

### Who / What Can Bear It
Measuring systems, sensors, imaging systems, and other eligible systems for which an input-output or response relationship is meaningfully defined.

### Where
It concerns the response behaviour of the relevant system with respect to a defined input.

### When
Its realization depends on the input/output definitions, operating range, system state, measurement model, and relevant conditions.

### Why
The Property separates the reusable characteristic concept from particular sensitivity coefficients, thresholds, or measured response values.

### How
It may be characterized by a defined response model or measurement procedure relating a change in input to a corresponding change in output or response.

## Semantic Definition

**Sensitivity is a reusable canonical semantic concept denoting a characteristic of an eligible system concerning the dependence of its defined response on changes in a defined input or measurand under specified conditions.**

## What This Property Characterizes

This Property characterizes input-response behaviour. Its exact quantitative realization depends on the defined system, input, output, measurand, model, and context.

## Bearer / Applicability

Applicable to measuring systems, sensors, imaging systems, and other systems for which sensitivity is a meaningful characteristic. Applicability does not imply a particular numerical sensitivity or that measurement has occurred.

## Distinctions

- **Sensitivity vs Responsivity:** responsivity is a specific quantitative response measure; sensitivity is the broader characteristic concept.
- **Sensitivity vs Quantum Efficiency:** quantum efficiency expresses a defined efficiency relationship and is quantitative.
- **Sensitivity vs Noise:** noise concerns disturbance or variability, not response dependence itself.
- **Sensitivity vs Exposure:** exposure describes an exposure condition or quantity depending on domain; it is not synonymous with response sensitivity.
- **Sensitivity vs Accuracy:** accuracy concerns agreement with a reference or true value under a measurement definition; sensitivity concerns response dependence.

## Quantification

Quantitative realizations may include sensitivity coefficients, slopes, threshold-based measures, or other domain-defined measures. Their meaning requires explicit input, output, model, range, and measurement context.

## Value Semantics

The Property itself has no numerical value. A sensitivity coefficient or threshold MUST be represented with its quantity/value semantics and relevant conditions and provenance.

## Conditions and Context

Relevant context may include measurand/input definition, output definition, operating range, wavelength, illumination, temperature, gain, exposure/integration conditions, system state, and measurement procedure. Context is necessary to interpret a particular realization.

## Measurement Context

Measurement of sensitivity presupposes a defined input-output relationship and an appropriate measurement framework. A Property assertion does not establish calibration, linearity, accuracy, or a particular test procedure.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, and `characterized-by`. Specific responsivity, threshold, or coefficient concepts remain separate quantitative entities.

## Subproperties

No domain-specific sensitivity subtype is canonicalized in the seed vocabulary. Specialized forms may be introduced after independent semantic verification.

## Synonyms / Related Terms

Sensitivity is related to response coefficient, response dependence, and system sensitivity. Terminological equivalence MUST be established from the relevant domain definition before aliasing.

## Evidence and Provenance

The Property classification is supported by measurement-science terminology, including VIM treatment of sensitivity as a property of a measuring system, together with imaging characterization practice. GIOP's definition is an independent semantic synthesis.

## Trust and Validation

The presence of this Property MUST NOT be interpreted as evidence for a numerical sensitivity, calibrated status, accuracy, detection threshold, or manufacturer performance claim.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Specialized sensitivity concepts may be added through the normal verification workflow.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible bearer when the input-response characteristic is semantically applicable. It MUST NOT infer a specific sensitivity value, threshold, or calibration state without explicit evidence.

## Retrieval Anchors

`sensitivity`, `system sensitivity`, `response sensitivity`, `input-response characteristic`, `sensitivity coefficient`

## What This Property Does NOT Mean

It does not mean high performance, high signal, high gain, calibrated operation, accuracy, or a particular detection threshold.

## Semantic Boundary

`SENSITIVITY → PROPERTY`

`SENSITIVITY COEFFICIENT / THRESHOLD → QUANTITY / VALUE`

`SENSITIVITY MEASUREMENT → ACTIVITY / MEASUREMENT`

`MEASUREMENT RESULT → RESULT`

`CALIBRATION → ACTIVITY / PROCESS`

`CALIBRATION STATUS → STATE / STATUS`

This document defines the reusable characteristic concept only.