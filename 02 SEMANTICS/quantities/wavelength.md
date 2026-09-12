# Wavelength

**Semantic ID:** `SEM-QUANTITY-WAVELENGTH-001`  
**Preferred Name:** Wavelength  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Optics / Photonics / Imaging  
**Status:** Active  
**Version:** 1.0.0

> Wavelength is a measurable spatial period associated with a propagating wave or periodic optical field under a defined medium, propagation condition, and reference frame.

## What

Wavelength describes the spatial period of a wave. In optical imaging it is commonly used to characterize electromagnetic radiation spectrally.

## Why

Wavelength is fundamental to spectral response, diffraction, interference, optical filtering, chromatic behavior, detector response, and color/imaging science.

## Structure

A wavelength statement should identify the wave or optical radiation, relevant medium or propagation condition, reference frame where material, and numerical value with unit.

## How

Wavelength may be established from spectral measurement, physical relationships, source characterization, or other justified procedures. Frequency and wavelength are related through the applicable propagation model; they are distinct quantities.

## Where

Wavelength applies to optical radiation, lasers, illumination, spectral measurements, optical components, detectors, and wave-based imaging systems.

## Who

It is relevant to imaging practitioners, optical engineers, photonics scientists, sensor engineers, color scientists, metrologists, and computational systems.

## Semantic Definition

Wavelength is the measurable spatial period of a defined wave or periodic optical field under specified propagation conditions.

## Core Distinctions

### Wavelength vs Frequency

Wavelength is spatial periodicity; frequency is temporal periodicity. Their numerical relationship depends on propagation conditions.

### Wavelength vs Spectral Band

A spectral band is a region or range in the spectrum. A wavelength identifies a particular spatial-period quantity.

### Wavelength vs Color

Color is a perceptual/colorimetric concept and is not identical to wavelength.

### Wavelength vs Spectral Response

Spectral Response is a Property concept describing response across spectral conditions; wavelength is a Quantity used to specify spectral position.

## Technical Depth

In a homogeneous non-dispersive idealization, wavelength, frequency, and propagation speed are related by the standard wave relationship. In dispersive media, wavelength depends on the relevant propagation conditions and must not be treated as universally interchangeable with frequency.

## Units and Value Semantics

Wavelength is expressed using a unit of length. Nanometres and other length units may be used when appropriate. Unit choice does not alter Quantity identity.

## Constraints / Assumptions

Do not infer perceived color directly from one wavelength without specifying the relevant spectral and observer model. Do not silently assume vacuum wavelength when a medium-dependent wavelength is intended.

## Evidence / Trust / Validation

Wavelength has high-confidence Quantity responsibility in physics, optics, photonics, and metrology. Exact reported values require source, method, reference conditions, and uncertainty where applicable.

## Relations

Potential relations include association with spectral response, optical radiation, source, detector, and measurement activities. Relation identities are governed independently.

## Machine / AI Interpretation

`Wavelength` resolves to `SEM-QUANTITY-WAVELENGTH-001`. A literal such as `550 nm` is a value expression, not a new Quantity concept.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`WAVELENGTH`, `OPTICAL WAVELENGTH`, `SPECTRAL WAVELENGTH`, `WAVELENGTH QUANTITY`, `LAMBDA`, `NM`, `NANOMETRE`, `NANOMETER`
