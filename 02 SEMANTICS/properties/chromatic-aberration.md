# Chromatic Aberration

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-CHROMATIC-ABERRATION-001
- **Canonical Label:** Chromatic Aberration
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Chromatic aberration is a characteristic of optical imaging in which image formation varies with wavelength, producing wavelength-dependent differences in image position, focus, magnification, or related optical mapping behaviour.

### Who / What Can Bear It
Eligible optical imaging systems, lenses, cameras, or defined optical configurations in which wavelength-dependent image-formation behaviour is attributable.

### Where
It occurs in the optical image-forming behaviour of the relevant optical path and may manifest differently across field position, wavelength, focus, or magnification conditions.

### When
Its realization depends on optical configuration, wavelength range, focus condition, field position, and the declared characterization method.

### Why
The concept provides a reusable description of wavelength-dependent optical limitations without embedding any particular aberration measurement or lens specification.

### How
It may be characterized through defined optical models, standardized tests, image measurements, or other methods that explicitly define the relevant wavelength-dependent effect.

## Semantic Definition

**Chromatic Aberration is a reusable canonical semantic concept denoting a characteristic of an eligible optical imaging system concerning wavelength-dependent departure in image formation, including image position, focus, magnification, or related optical mapping behaviour.**

## What This Property Characterizes

It characterizes wavelength-dependent optical behaviour. It does not itself denote a wavelength, displacement, blur width, colour-fringing magnitude, coefficient, or measured severity.

## Bearer / Applicability

Applicable to optical imaging systems, lenses, cameras, and defined optical configurations where wavelength-dependent image formation is meaningfully characterized. Presence of the Property does not establish that a quantitative aberration measurement exists.

## Distinctions

- **Chromatic Aberration vs Optical Distortion:** distortion concerns geometric mapping relative to a reference; chromatic aberration is intrinsically wavelength-dependent.
- **Chromatic Aberration vs Spectral Response:** spectral response concerns response as a function of wavelength; chromatic aberration concerns wavelength-dependent optical image formation.
- **Chromatic Aberration vs Colour Appearance:** colour appearance is a perceptual concept dependent on observer and viewing context.
- **Chromatic Aberration vs Measurement Result:** a measured lateral or longitudinal deviation is a quantitative realization or result, not the Property itself.

## Quantification

Quantitative realizations may include wavelength-dependent positional displacement, focal shift, magnification difference, image-fringe metrics, or defined aberration coefficients. Each realization requires an explicit measurement definition and context.

## Value Semantics

The Property carries no numerical value. Numerical aberration values MUST retain their quantity definition, reference wavelength or spectral conditions where relevant, measurement context, and provenance.

## Conditions and Context

Relevant context may include wavelength, spectral bandwidth, field position, object distance, focus setting, aperture configuration, sensor/image plane, optical configuration, and measurement method. These are contextual qualifiers, not implicit Property values.

## Measurement Context

Chromatic aberration measurements require a defined form of aberration and a method for relating image behaviour across wavelength. A Property assertion does not imply use of ISO 15795, ISO 19084, a particular test chart, or a particular optical model.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, and `characterized-by`. Longitudinal and lateral forms may be related as domain-specific concepts only after independent semantic verification.

## Subproperties

No subtype hierarchy is asserted as canonical by this seed entry. Longitudinal, lateral, and other specialized forms remain linkable concepts subject to their own verification and canonicalization.

## Synonyms / Related Terms

Related terms include chromatic aberration, wavelength-dependent aberration, longitudinal chromatic aberration, and lateral chromatic aberration. Related terminology is not automatically interchangeable across measurement contexts.

## Evidence and Provenance

Supported by standardized optical terminology and measurement practice, including ISO 15795 and ISO 19084. These standards provide external evidence; this document is an independent GIOP semantic synthesis rather than a reproduction of source text.

## Trust and Validation

A Property assertion MUST NOT be interpreted as proof of a numerical aberration magnitude, visible colour fringing, optical defect severity, calibration validity, or manufacturer performance.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Specialized aberration forms may be added through the normal verification workflow.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible optical bearer. It MUST NOT infer a specific aberration value, wavelength range, measurement method, or perceptual artefact from the Property alone.

## Retrieval Anchors

`chromatic aberration`, `wavelength-dependent aberration`, `longitudinal chromatic aberration`, `lateral chromatic aberration`, `optical aberration`

## What This Property Does NOT Mean

It does not mean that colour fringing is visible, that an optical system is defective, or that a particular chromatic-aberration measurement has been performed.

## Semantic Boundary

`CHROMATIC ABERRATION → PROPERTY`

`ABERRATION MAGNITUDE / COEFFICIENT / DISPLACEMENT → QUANTITY / VALUE`

`ABERRATION MEASUREMENT → ACTIVITY / MEASUREMENT`

`ABERRATION MEASUREMENT RESULT → RESULT`

`COLOUR APPEARANCE / FRINGING EXPERIENCE → PERCEPTION`

This document defines the reusable characteristic concept only.