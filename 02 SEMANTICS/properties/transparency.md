# Transparency

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-TRANSPARENCY-001
- **Canonical Label:** Transparency
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Transparency is a physical characteristic of a material or medium concerning its capacity to permit relevant radiation to pass through it under a defined context.

### Who / What Can Bear It
Materials or media whose transmission of relevant radiation is being characterized.

### Where
It concerns transmission through the relevant material or medium and may depend on the radiation domain and path conditions.

### When
Its realization depends on wavelength or spectral content, direction, geometry, material state, thickness, surface condition, and other declared context.

### Why
The concept describes the physical characteristic independently from a particular transmittance value or perceptual judgment.

### How
It may be characterized through appropriate physical or optical characterization and quantified using defined transmission quantities.

## Semantic Definition

**Transparency is a reusable canonical semantic concept denoting a physical characteristic of an eligible material or medium concerning its capacity to permit relevant radiation to pass through it under a defined context.**

## What This Property Characterizes

Transparency characterizes physical transmission behaviour at the characteristic level. It does not itself specify a transmittance ratio, wavelength, angular response, thickness, or visual appearance.

## Bearer / Applicability

Primarily applicable to materials or media whose transmission of relevant radiation is meaningfully characterized. The Property does not imply uniform transmission across wavelengths, directions, or conditions.

## Distinctions

- **Transparency vs Transmittance:** transparency is the physical characteristic; transmittance is a quantitative ratio describing transmitted relative to incident radiation under a defined framework.
- **Transparency vs Clarity:** clarity concerns the perceptibility or preservation of distinguishable imagery through a medium.
- **Transparency vs Perceived Transparency:** perceived transparency belongs to perception and depends on observer and viewing conditions.
- **Transparency vs Spectral Response:** spectral response concerns wavelength-dependent system response and is not equivalent to material transparency.

## Quantification

Quantitative realizations may include transmittance and related transmission quantities under defined spectral, geometric, angular, and measurement conditions. Such quantities belong to the quantitative layer and MUST retain their definitions and contexts.

## Value Semantics

The Property itself carries no numerical transmission value. A transmittance value MUST specify the relevant radiation domain and measurement framework.

## Conditions and Context

Relevant context may include wavelength, spectral bandwidth, direction, incidence geometry, thickness, material state, surface condition, polarization, temperature, and surrounding medium. These factors may materially affect quantitative realizations.

## Measurement Context

A statement that a material is transparent does not establish that a measurement has occurred. Quantitative transmission claims require a defined procedure, measurement system, and provenance as appropriate.

## Relations

Potential relations include `has-property`, `quantified-by`, `evaluated-under`, `measured-by`, and `represented-by`. Relations to material, medium, illumination, observer, and perception concepts remain separate.

## Subproperties

No specialized transparency subtype is canonicalized in the seed vocabulary. Spectral, angular, or directional forms may be introduced only after independent semantic verification.

## Synonyms / Related Terms

Related terms include transparent, semitransparent, transmission characteristic, and optical transparency. These terms are not automatically interchangeable across physical and perceptual contexts.

## Evidence and Provenance

CIE terminology explicitly treats transparency as a physical property of a material or substance and distinguishes it from related concepts such as clarity. GIOP uses that evidence for an independent semantic synthesis.

## Trust and Validation

Presence of this Property MUST NOT be interpreted as evidence of a particular transmittance, optical quality, visual clarity, or standards compliance.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Additional physical transparency concepts may be introduced through the normal verification workflow.

## Machine / AI Interpretation

A machine MAY attach this Property to an eligible material or medium. It MUST NOT infer a particular transmittance value, wavelength response, perceptual transparency, or measurement result from the Property alone.

## Retrieval Anchors

`transparency`, `optical transparency`, `transparent material`, `semitransparency`, `physical transparency`

## What This Property Does NOT Mean

It does not mean complete transmission, high visual clarity, absence of scattering, or that an observer can see an object through the material under every condition.

## Semantic Boundary

`TRANSPARENCY → PROPERTY`

`TRANSMITTANCE → QUANTITY`

`TRANSMISSION MEASUREMENT → ACTIVITY / MEASUREMENT`

`TRANSMISSION MEASUREMENT RESULT → RESULT`

`PERCEIVED TRANSPARENCY → PERCEPTION`

This document defines the physical characteristic concept only.