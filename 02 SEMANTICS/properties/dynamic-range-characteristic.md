# Dynamic-Range Characteristic

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-DYNAMIC-RANGE-CHARACTERISTIC-001
- **Canonical Label:** Dynamic-Range Characteristic
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What

Dynamic-Range Characteristic is the characteristic of an eligible imaging, sensing, or measurement-capable system concerning the span of relevant signal or response conditions that the system can distinguish or accommodate under a defined operating and measurement context.

### Why

The concept provides a reusable characteristic-level description without embedding a particular numerical dynamic-range result, ratio, logarithmic value, bit representation, or test outcome.

### Where

It may apply to imaging sensors, cameras, sensing subsystems, measurement systems, or other eligible systems for which a defined dynamic-range behavior is semantically relevant.

### When

Its realized behavior depends on operating state, signal domain, measurement method, saturation behavior, noise conditions, environmental conditions, and other declared context.

### Who / What Bears It

The bearer is an eligible system or component whose response behavior can meaningfully be characterized in terms of dynamic range.

### How

The characteristic is established through an appropriate quantitative or measurement framework. The resulting numerical dynamic range, limits, ratio, decibel expression, bit-equivalent expression, or test result belongs to quantitative and measurement semantics rather than to the Property definition itself.

## Semantic Definition

**Dynamic-Range Characteristic is a reusable canonical semantic concept denoting the characteristic of an eligible system concerning the extent of relevant signal or response conditions that can be accommodated or distinguished under defined conditions and an explicitly declared measurement or evaluation context.**

## What This Property Characterizes

This Property characterizes the existence and semantic nature of a system's dynamic-range behavior. It does not itself assert a particular range, ratio, sensitivity threshold, saturation level, noise level, or performance value.

## Bearer and Applicability

The Property may characterize:

- image sensors;
- cameras;
- sensing subsystems;
- measurement systems;
- other technically eligible systems whose response span is meaningfully evaluated.

Applicability MUST be interpreted with the relevant signal domain and context.

## Distinctions

### Dynamic-Range Characteristic vs Dynamic Range

Dynamic-Range Characteristic is the Property-level abstraction. `Dynamic range` denotes a quantitative realization or performance measure derived under a defined method and context.

### Dynamic-Range Characteristic vs Sensitivity

Sensitivity concerns response to changes in input or measurand conditions. Dynamic-Range Characteristic concerns the span over which relevant response conditions can be accommodated or distinguished.

### Dynamic-Range Characteristic vs Noise

Noise is a disturbance or variability concept. Dynamic range may depend on noise-related criteria, but the two concepts are not interchangeable.

### Dynamic-Range Characteristic vs Resolution

Resolution concerns distinguishability of details, values, or features according to a specified domain. Dynamic-range behavior concerns span of accommodated or distinguished signal/response conditions.

## Quantification Boundary

This Property does not contain an instance value.

Quantitative realizations may include, depending on the declared measurement framework:

- dynamic-range ratios;
- logarithmic expressions such as decibel values;
- bit-equivalent expressions;
- upper and lower response limits;
- measurement-derived performance parameters.

Such values belong to quantity/value/result semantics.

## Conditions and Context

A dynamic-range realization is context-dependent. Relevant context may include:

- signal or measurand domain;
- operating state;
- exposure or integration conditions;
- spectral conditions;
- illumination conditions;
- noise conditions;
- saturation or clipping behavior;
- measurement method and procedure;
- calibration and test configuration.

The Property itself does not assert any of these conditions.

## Evidence and Provenance

The concept is retained as a characteristic-level abstraction because technical imaging and sensor standards treat dynamic range as a measurable performance quantity while also distinguishing it from other characterization parameters. GIOP therefore preserves the characteristic abstraction separately from its quantitative realizations.

## Relations

Possible relations include:

- `has-property` → Dynamic-Range Characteristic;
- `quantified-by` → dynamic-range quantity or derived performance measure;
- `evaluated-under` → measurement context;
- `characterized-by` → measurement procedure or test method.

These are relations to other semantic layers, not embedded Property content.

## Machine Interpretation

A machine MUST interpret this Property as a characteristic concept, not as a numerical dynamic-range value.

The presence of this Property MUST NOT imply:

- a particular numerical range;
- a particular unit or logarithmic representation;
- a particular sensor technology;
- a particular noise criterion;
- calibration validity;
- compliance with a specific test standard;
- a guaranteed manufacturer specification.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Future Expansion:** Additional quantitative and measurement concepts may be linked without redefining this Property.

## Semantic Boundary

`DYNAMIC-RANGE CHARACTERISTIC → PROPERTY`

`DYNAMIC RANGE / RANGE RATIO → QUANTITATIVE CONCEPT`

`MEASUREMENT PROCEDURE → PROCEDURE / PROCESS`

`MEASUREMENT RESULT → RESULT`

`CALIBRATION STATUS → STATE / STATUS`

The canonical boundary prevents a measurable performance value from being mistaken for the reusable Property concept.
