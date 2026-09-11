# Optical Distortion

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-OPTICAL-DISTORTION-001
- **Canonical Label:** Optical Distortion
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Optical distortion is a characteristic of optical imaging concerning systematic geometric departure in spatial image mapping relative to a defined ideal, reference, or calibration mapping.

### Who / What Can Bear It
Eligible optical imaging systems or components, including lenses, cameras, and defined optical configurations, where geometric mapping behaviour is attributable to the bearer.

### Where
It concerns the geometric mapping behaviour of the relevant optical path or imaging configuration.

### When
Its realization is configuration- and context-dependent, including optical setup, field position, focus condition, and the declared reference or measurement method.

### Why
The concept allows geometric mapping behaviour to be described independently from any particular distortion coefficient, percentage, displacement, or test result.

### How
It may be characterized through a defined geometric model, calibration mapping, test procedure, or measurement method that compares observed mapping with an explicit reference.

## Semantic Definition

**Optical Distortion is a reusable canonical semantic concept denoting a characteristic of an eligible optical imaging system concerning systematic geometric deviation of its spatial image mapping from a defined ideal, reference, or calibration mapping.**

## What This Property Characterizes

This Property characterizes geometric imaging behaviour. It concerns spatial mapping rather than sharpness, resolution, chromatic aberration, exposure, or perceptual appearance.

## Bearer / Applicability

Applicable to optical imaging systems, lenses, cameras, or defined optical configurations when a geometric mapping and reference are meaningfully specified. Applicability does not imply that distortion has been measured, calibrated, or quantified.

## Distinctions

- **Optical Distortion vs Chromatic Aberration:** distortion concerns geometric mapping; chromatic aberration concerns wavelength-dependent optical image formation.
- **Optical Distortion vs Resolution:** resolution concerns distinguishability of spatial detail under a defined measurement framework; distortion concerns geometric mapping.
- **Optical Distortion vs Sharpness:** sharpness concerns perceived or measured acutance/detail character; it is not equivalent to geometric mapping error.
- **Optical Distortion vs Measurement Result:** a distortion coefficient or measured displacement is evidence about an instance, not the Property concept itself.

## Quantification

Quantitative realizations may include distortion coefficients, percentages, positional displacement, mapping residuals, or other defined parameters. Their meaning depends on the measurement model, reference mapping, coordinate system, and procedure. Numerical values belong to the appropriate quantity/value/result layer.

## Value Semantics

The Property itself carries no numerical value. A value such as a percentage or coefficient MUST be represented with its quantity definition, unit or dimensionless status where applicable, measurement context, and provenance.

## Conditions and Context

Relevant context may include optical configuration, focal setting, field position, wavelength or spectral condition, object/image geometry, reference mapping, calibration state, and measurement procedure. These contexts qualify a realization and are not asserted by the Property alone.

## Measurement Context

Measurement of distortion requires a defined method and reference. A claimed presence of Optical Distortion does not establish that a measurement has occurred or that a particular standard, chart, algorithm, or calibration procedure was used.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, and `characterized-by`. These connect the Property to bearers, quantities, contexts, measurement results, and procedures without collapsing those concepts into the Property.

## Subproperties

No additional subproperty hierarchy is canonicalized in the seed vocabulary. Domain-specific forms may be introduced only after semantic and measurement boundaries are independently verified.

## Synonyms / Related Terms

Related technical terminology may include geometric distortion and optical geometric distortion. Terminology MUST NOT be treated as synonymous merely because different standards or domains use overlapping labels.

## Evidence and Provenance

The semantic decision is supported by standardized digital-camera and optical-imaging measurement practice, including ISO 17850 and related terminology. The external standards provide evidence for the technical concept and its measurement treatment; this page is GIOP's independent semantic synthesis.

## Trust and Validation

A Property assertion alone MUST NOT be interpreted as proof of magnitude, severity, compliance, calibration, or manufacturer performance. Quantitative or normative claims require their own evidence and provenance.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Additional distortion subtypes or measurement parameters may be added only through the normal verification and canonicalization workflow.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible bearer when the semantic applicability is established. It MUST NOT infer a numerical distortion value, test method, calibration validity, or standards compliance from the Property alone.

## Retrieval Anchors

`optical distortion`, `geometric distortion`, `imaging geometry`, `spatial mapping deviation`, `distortion characteristic`

## What This Property Does NOT Mean

It does not by itself mean a lens is defective, that a camera has a specified distortion percentage, that a measurement has been performed, or that an image visibly exhibits distortion.

## Semantic Boundary

`OPTICAL DISTORTION → PROPERTY`

`DISTORTION COEFFICIENT / DISTORTION MAGNITUDE → QUANTITY / VALUE`

`DISTORTION MEASUREMENT → ACTIVITY / MEASUREMENT`

`DISTORTION MEASUREMENT RESULT → RESULT`

`CALIBRATION STATE → STATE / STATUS`

This document defines the reusable characteristic concept only.