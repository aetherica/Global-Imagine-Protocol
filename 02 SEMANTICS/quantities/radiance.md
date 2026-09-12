# Radiance

**Semantic ID:** `SEM-QUANTITY-RADIANCE-001`  
**Preferred Name:** Radiance  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Radiometry / Optics / Imaging  
**Status:** Active  
**Version:** 1.0.0

> Radiance is the radiometric quantity describing radiant power propagating in a specified direction per unit projected area and solid angle, with the relevant spectral or integrated domain specified.

## What

Radiance quantifies directional radiant power associated with a source, surface, or beam per projected area and solid angle.

## Why

Radiance is a core quantity for radiometric imaging, optical system analysis, remote sensing, rendering, sensor modelling, calibration, and energy-transfer analysis.

## Structure

A radiance statement should identify the source or surface, direction, projected-area basis, solid-angle basis, spectral domain where applicable, value, unit, and relevant propagation/measurement context.

## How

Radiance may be measured or calculated from radiant-power distributions under a defined geometry and spectral domain.

## Where

It applies to optical sources, reflecting/transmitting surfaces, beams, scenes, imaging systems, detectors, remote-sensing systems, and rendering models.

## Who

Optical engineers, imaging scientists, radiometrists, sensor engineers, computational-imaging researchers, rendering specialists, and metrologists use it.

## Core Distinctions

### Radiance vs Irradiance

Radiance is directional and normalized by projected area and solid angle. Irradiance is incident radiant power per receiving area.

### Radiance vs Luminance

Radiance is radiometric; luminance is photometric and includes photometric spectral weighting.

### Radiance vs Radiant Flux

Radiant flux is total radiant power. Radiance describes its directional density with area and solid-angle terms.

## Units and Value Semantics

Radiance is commonly expressed in watts per square metre per steradian (W·m⁻²·sr⁻¹), with spectral forms carrying additional per-wavelength or per-frequency dimensions as applicable.

## Technical Depth

Radiance is a directional quantity and its spectral form depends on the chosen spectral variable. Geometry, medium, source distribution, and measurement bandwidth must be preserved where relevant.

## Constraints / Assumptions

Do not equate radiance with irradiance or luminance. Do not omit whether a reported value is spectral, band-integrated, or broadband when that distinction affects interpretation.

## Evidence / Trust / Validation

Radiance has established radiometric Quantity responsibility. Calibration, detector response, geometry, bandwidth, and uncertainty can be critical to measurement validity.

## Relations

Potential relations include association with sources, surfaces, directions, spectral conditions, detectors, and measurement activities.

## Machine / AI Interpretation

`Radiance` resolves to `SEM-QUANTITY-RADIANCE-001`. A value such as `W·m⁻²·sr⁻¹` expresses a value/unit combination and is not the Quantity concept.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`RADIANCE`, `RADIOMETRIC RADIANCE`, `SPECTRAL RADIANCE`, `RADIANCE QUANTITY`, `W/M2/SR`, `W M-2 SR-1`
