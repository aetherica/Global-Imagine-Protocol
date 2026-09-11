# Dynamic-Range Characteristic

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-DYNAMIC-RANGE-CHARACTERISTIC-001
- **Canonical Label:** Dynamic-Range Characteristic
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Dynamic-Range Characteristic is a characteristic of an eligible imaging, sensing, or measurement-capable system concerning the span of relevant signal or response conditions that the system can accommodate or distinguish under a defined operating and evaluation context.

### Who / What Can Bear It
Image sensors, cameras, sensing subsystems, measuring systems, and other eligible systems for which dynamic-range behaviour is meaningfully defined.

### Where
It concerns the usable or distinguishable span of relevant signal or response conditions of the system.

### When
Its realization depends on operating state, signal domain, measurement criteria, saturation behaviour, noise conditions, exposure or integration conditions, and other declared context.

### Why
The Property provides a characteristic-level abstraction without embedding a particular numerical dynamic-range ratio, logarithmic value, bit representation, or test result.

### How
The characteristic is established through an appropriate quantitative or measurement framework that defines the relevant lower and upper response limits and the criterion connecting them.

## Semantic Definition

**Dynamic-Range Characteristic is a reusable canonical semantic concept denoting a characteristic of an eligible system concerning the extent of relevant signal or response conditions that can be accommodated or distinguished under defined conditions and an explicitly declared evaluation or measurement context.**

## What This Property Characterizes

This Property characterizes dynamic-range behaviour at the characteristic level. It does not assert a particular range, ratio, sensitivity threshold, saturation level, noise level, or performance value.

## Bearer / Applicability

Applicable to image sensors, cameras, sensing subsystems, measuring systems, and other technically eligible systems whose response span is meaningfully evaluated. Applicability does not imply that dynamic range has been measured.

## Distinctions

- **Dynamic-Range Characteristic vs Dynamic Range:** the former is the reusable Property abstraction; a dynamic-range ratio or reported range is a quantitative realization under a defined method.
- **Dynamic-Range Characteristic vs Sensitivity:** sensitivity concerns response dependence on changes in input; dynamic range concerns the span of relevant response conditions.
- **Dynamic-Range Characteristic vs Noise:** noise concerns disturbance or variability. A dynamic-range criterion may depend on noise, but the concepts are not interchangeable.
- **Dynamic-Range Characteristic vs Resolution:** resolution concerns distinguishability of detail or values in a specified domain; dynamic range concerns signal/response span.

## Quantification

Quantitative realizations may include dynamic-range ratios, logarithmic expressions such as decibel values, bit-equivalent expressions, lower and upper response limits, or measurement-derived performance parameters. Their interpretation requires the declared measurement or evaluation framework.

## Value Semantics

The Property itself contains no numerical value. A reported dynamic range MUST retain its quantity definition, calculation basis, limits or criteria, representation, context, and provenance.

## Conditions and Context

Relevant context may include signal or measurand domain, operating state, exposure or integration conditions, spectral conditions, illumination, noise conditions, saturation or clipping behaviour, gain, calibration state, and measurement method. These qualify a realization and are not asserted by the Property.

## Measurement Context

A dynamic-range value requires explicit lower and upper criteria and a defined method or evaluation framework. A Property assertion does not establish that measurement occurred, that a particular standard was used, or that a manufacturer specification is valid.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, and `characterized-by`. Quantities, measurement results, procedures, and calibration states remain separate semantic entities.

## Subproperties

No specialized dynamic-range subtype is canonicalized in the seed vocabulary. Domain-specific forms may be introduced after independent verification.

## Synonyms / Related Terms

Related terms include dynamic range, dynamic-range capability, and signal-range characteristic. They MUST NOT be treated as equivalent without reconciling their quantitative and contextual definitions.

## Evidence and Provenance

The characteristic-level abstraction is supported by imaging and sensor characterization standards that treat dynamic range as a measurable performance concept alongside other distinct characterization parameters. GIOP separates that quantitative realization from the reusable characteristic concept.

## Trust and Validation

Presence of this Property MUST NOT be interpreted as proof of a numerical range, a particular noise criterion, saturation limit, calibration validity, standards compliance, or guaranteed manufacturer performance.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Quantitative and measurement concepts may be linked or added independently without redefining this Property.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible bearer. It MUST NOT infer a numerical dynamic range, unit, logarithmic representation, measurement criterion, calibration state, or performance claim from the Property alone.

## Retrieval Anchors

`dynamic-range characteristic`, `dynamic range`, `signal range`, `response span`, `dynamic-range behaviour`

## What This Property Does NOT Mean

It does not mean high sensitivity, low noise, high image quality, a particular bit depth, or a measured performance value.

## Semantic Boundary

`DYNAMIC-RANGE CHARACTERISTIC → PROPERTY`

`DYNAMIC RANGE / RANGE RATIO → QUANTITATIVE CONCEPT`

`DYNAMIC-RANGE MEASUREMENT / EVALUATION → ACTIVITY / MEASUREMENT`

`DYNAMIC-RANGE MEASUREMENT RESULT → RESULT`

`CALIBRATION STATUS → STATE / STATUS`

This document defines the reusable characteristic concept only.