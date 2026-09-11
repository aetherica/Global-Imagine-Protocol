# Chromaticity

## Identity

- **Semantic Type:** PROPERTY
- **Canonical ID:** SEM-PROPERTY-CHROMATICITY-001
- **Canonical Label:** Chromaticity
- **Lifecycle Status:** CANONICAL
- **Canonical Layer:** `02 SEMANTICS/properties/`

## 5W1H Orientation

### What
Chromaticity is a characteristic of a defined colour stimulus describing its chromatic aspect independently of its absolute luminous or radiant magnitude, within a specified colourimetric framework.

### Who / What Can Bear It
Defined colour stimuli and, where the semantic representation is explicitly tied to such a stimulus, colour-related representations. Applicability requires the relevant colourimetric framework and observer definition.

### Where
It concerns the chromatic aspect of the defined colour stimulus rather than its total radiant or luminous magnitude.

### When
Its realization depends on the selected colourimetric system, observer functions, stimulus conditions, and other declared colourimetric context.

### Why
The concept separates chromatic specification from absolute magnitude and from perceptual colour appearance.

### How
It is specified through defined chromaticity descriptors such as chromaticity coordinates or other standardized descriptors within a stated colourimetric framework.

## Semantic Definition

**Chromaticity is a reusable canonical semantic concept denoting a property of a defined colour stimulus concerning its chromatic aspect independently of its absolute luminous or radiant magnitude within a specified colourimetric framework.**

## What This Property Characterizes

It characterizes the chromatic aspect of a colour stimulus. It does not itself denote a coordinate pair, colour space, spectral power distribution, illuminant, or appearance judgment.

## Bearer / Applicability

Applicable where a defined colour stimulus and colourimetric framework are identified. A representation may carry a chromaticity description only when its relation to a defined colour stimulus and framework is explicit.

## Distinctions

- **Chromaticity vs Colour Appearance:** appearance depends on viewing, observer, adaptation, surround, and perceptual conditions; chromaticity is a colourimetric property.
- **Chromaticity vs Spectral Distribution:** a spectral distribution can produce a colour stimulus but is not identical to its chromaticity.
- **Chromaticity vs Colour Coordinate:** coordinates are quantitative descriptors used to specify chromaticity; they are not the Property concept itself.
- **Chromaticity vs Luminance/Radiant Magnitude:** chromaticity abstracts the chromatic aspect independently of absolute magnitude within the relevant framework.

## Quantification

Quantitative realizations may include chromaticity coordinates and other defined chromaticity descriptors. Their interpretation requires the associated colourimetric system, observer definition, and coordinate conventions.

## Value Semantics

The Property itself has no coordinate value. A coordinate pair or other descriptor MUST retain its coordinate system and colourimetric definitions.

## Conditions and Context

Relevant context may include colourimetric observer, illuminant or stimulus specification, adaptation/viewing conditions where applicable to interpretation, coordinate system, and measurement or computation method. Perceptual viewing context MUST NOT be silently substituted for the colourimetric definition.

## Measurement Context

Chromaticity may be determined from measurement or from a defined representation/model. A chromaticity assertion alone does not prove that a physical measurement occurred or that a particular instrument was used.

## Relations

Potential relations include `has-property`, `specified-by`, `quantified-by`, `derived-from`, `represented-by`, and `evaluated-under`. Colour spaces, observer functions, illuminants, and coordinate values remain separate semantic entities.

## Subproperties

No additional chromaticity subtype is canonicalized in the seed vocabulary. Domain-specific chromaticity descriptors may be introduced through the normal verification workflow.

## Synonyms / Related Terms

Related terms include chromaticity coordinates and chromatic aspect. Coordinate terminology MUST retain its colourimetric framework and MUST NOT be treated as a synonym for the Property concept.

## Evidence and Provenance

Supported by CIE terminology, which explicitly treats chromaticity as a property of a colour stimulus and expresses it through defined chromaticity descriptors. GIOP's definition is an independent semantic synthesis.

## Trust and Validation

Presence of this Property MUST NOT be interpreted as proof of a particular coordinate value, colour-space membership, perceptual appearance, measurement accuracy, or observer-independent visual experience.

## Lifecycle

- **Status:** CANONICAL
- **Seed Vocabulary:** Yes
- **Expansion:** Additional colourimetric characteristic concepts may be added through independent verification.

## Machine / AI Interpretation

A machine MAY attach this Property when the relevant colour stimulus and colourimetric framework are identified. It MUST NOT infer a coordinate pair, colour space, illuminant, or appearance judgment from the Property alone.

## Retrieval Anchors

`chromaticity`, `chromaticity property`, `chromatic aspect`, `chromaticity coordinates`, `colour stimulus`

## What This Property Does NOT Mean

It does not mean a particular colour appearance, hue label, colour-space coordinate, spectral distribution, or measured physical value without explicit supporting definitions.

## Semantic Boundary

`CHROMATICITY → PROPERTY`

`CHROMATICITY COORDINATE → QUANTITY / VALUE`

`COLOURIMETRIC MEASUREMENT → ACTIVITY / MEASUREMENT`

`COLOUR APPEARANCE → PERCEPTION`

`SPECTRAL DISTRIBUTION → REPRESENTATION / QUANTITATIVE DATA as applicable`

This document defines the reusable characteristic concept only.