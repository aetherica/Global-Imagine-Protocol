# Luminance

**Semantic ID:** `SEM-QUANTITY-LUMINANCE-001`  
**Preferred Name:** Luminance  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Photometry / Imaging / Display  
**Status:** Active  
**Version:** 1.0.0

> Luminance is the photometric quantity describing light emitted, transmitted, or reflected by a surface or source in a specified direction per unit projected area and solid angle.

## What

Luminance quantifies directional photometric emission or transmission associated with a defined surface or source.

## Why

Luminance is central to display characterization, scene brightness measurement, visual environment analysis, photometric imaging, and color/vision applications.

## Structure

A luminance statement should identify the emitting, transmitting, or reflecting surface/source, viewing direction, relevant projected area and solid angle, value, unit, and measurement context where needed.

## How

Luminance may be measured with appropriate photometric instrumentation or derived from radiometric information using the applicable photometric weighting.

## Where

It applies to displays, illuminated surfaces, light sources, scenes, optical targets, and photometric measurement setups.

## Who

Display engineers, photographers, cinematographers, color scientists, vision researchers, lighting professionals, and metrologists use the concept.

## Core Distinctions

### Luminance vs Illuminance

Illuminance describes incident luminous flux per area. Luminance describes directional light leaving/emitted/transmitted from a surface or source per projected area and solid angle.

### Luminance vs Radiance

Luminance is photometric; radiance is radiometric. They use different weighting semantics even where both describe directional radiation from a surface/source.

### Luminance vs Perceived Brightness

Perceived brightness is a perceptual interpretation and depends on observer and context. Luminance is a physical photometric Quantity.

## Units and Value Semantics

The SI coherent unit is candela per square metre (cd/m²).

## Technical Depth

Luminance is directional and can vary spatially across a surface. Measurement geometry, spectral weighting, observer function, calibration, and angular conditions may be significant.

## Constraints / Assumptions

Do not treat luminance as a direct synonym for perceived brightness. Do not infer a unique luminance from an image representation without a validated radiometric/photometric calibration chain.

## Evidence / Trust / Validation

Luminance has established photometric Quantity responsibility. Measurement claims should preserve geometry, spectral response, calibration, and uncertainty where applicable.

## Relations

Potential relations include association with surfaces, sources, viewing directions, observation contexts, and measurement activities.

## Machine / AI Interpretation

`Luminance` resolves to `SEM-QUANTITY-LUMINANCE-001`. A value such as `100 cd/m²` is a quantity value expression.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`LUMINANCE`, `CD/M2`, `CANDELA PER SQUARE METRE`, `CANDELA PER SQUARE METER`, `PHOTOMETRIC RADIANCE`, `SURFACE LUMINANCE`
