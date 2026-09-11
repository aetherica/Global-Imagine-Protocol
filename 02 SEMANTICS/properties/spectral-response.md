# Spectral Response

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-SPECTRAL-RESPONSE-001
- **Canonical Label:** Spectral Response
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Spectral response is a characteristic describing how an eligible imaging or sensing system responds as a function of wavelength or spectral content under a defined response definition.

### Who / What Can Bear It
Sensors, cameras, spectral channels, sensing subsystems, or defined imaging configurations whose response behaviour is meaningfully characterized spectrally.

### Where
It concerns the wavelength-dependent response behaviour of the relevant sensing or imaging path.

### When
Its realization depends on the spectral conditions, configuration, response definition, operating state, and measurement context.

### Why
The concept provides a reusable description of wavelength-dependent response without conflating the characteristic with a response value, coefficient, or sensor specification.

### How
It may be characterized using spectral measurements, response curves, defined models, or standardized sensor-characterization procedures.

## Semantic Definition

**Spectral Response is a reusable canonical semantic concept denoting a characteristic of an eligible imaging or sensing system concerning how its defined response varies with wavelength or spectral content under a specified configuration and response definition.**

## What This Property Characterizes

It characterizes spectral dependence of system response. It does not itself assert a particular response value, sensitivity coefficient, responsivity, quantum efficiency, colour specification, or calibration state.

## Bearer / Applicability

Applicable to sensors, cameras, spectral channels, and other eligible sensing or imaging systems where wavelength-dependent response is defined. Applicability does not imply that a spectral response curve has been measured.

## Distinctions

- **Spectral Response vs Sensitivity:** sensitivity describes response dependence on a defined input; spectral response specifically describes dependence across wavelength or spectral content.
- **Spectral Response vs Responsivity:** responsivity is a quantitative response measure under a defined input/output formulation.
- **Spectral Response vs Quantum Efficiency:** quantum efficiency is a quantitative efficiency concept; it is not synonymous with the broader characteristic.
- **Spectral Response vs Spectral Range:** spectral range concerns a defined wavelength domain or operating range, not the response characteristic itself.

## Quantification

Quantitative realizations may include wavelength-specific response values, normalized response curves, spectral sensitivity values, or related measurements. Their definitions and units depend on the declared measurement model and response quantity.

## Value Semantics

The Property itself has no response value. A curve or numerical value MUST retain wavelength definition, response definition, normalization, measurement conditions, and provenance as applicable.

## Conditions and Context

Relevant context may include wavelength, spectral bandwidth, illumination, optical path, exposure/integration conditions, detector state, filter configuration, temperature, and measurement method. These conditions qualify a realization and are not implied by the Property.

## Measurement Context

Spectral characterization requires an explicit spectral input or reference and a defined response quantity. A Property assertion does not imply calibration, a specific standard, or a particular measurement instrument.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, `characterized-by`, and `has-spectral-domain`. Relations to wavelength-specific quantities remain separate semantic objects.

## Subproperties

No specialized spectral-response subtype is canonicalized in the seed vocabulary. Channel-specific or modality-specific variants may be added later through verification.

## Synonyms / Related Terms

Related terminology includes spectral sensitivity and wavelength-dependent response. These terms MUST be reconciled against their quantitative definitions before being treated as synonyms.

## Evidence and Provenance

Supported by imaging and sensor characterization practice, including EMVA 1288 treatment of wavelength-dependent sensor response. External standards serve as evidence; the GIOP page is an independent semantic synthesis.

## Trust and Validation

The Property does not establish a response curve, calibration validity, spectral accuracy, sensor quality, or manufacturer specification. Those claims require explicit evidence.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Additional spectral-response forms may be added through the normal verification and canonicalization workflow.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible sensing or imaging bearer. It MUST NOT infer a response curve, numerical coefficient, wavelength range, or calibration state from the Property alone.

## Retrieval Anchors

`spectral response`, `wavelength response`, `spectral sensitivity`, `wavelength-dependent response`, `sensor spectral response`

## What This Property Does NOT Mean

It does not mean that the system has a particular spectral range, has been calibrated, or has a specific numerical response at any wavelength.

## Semantic Boundary

`SPECTRAL RESPONSE → PROPERTY`

`RESPONSIVITY / QUANTUM EFFICIENCY / RESPONSE VALUE → QUANTITY`

`SPECTRAL RESPONSE MEASUREMENT → ACTIVITY / MEASUREMENT`

`SPECTRAL RESPONSE RESULT / CURVE → RESULT / REPRESENTATION as applicable`

`CALIBRATION STATE → STATE / STATUS`

This document defines the characteristic concept only.