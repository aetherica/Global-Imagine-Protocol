# Illuminance

**Semantic ID:** `SEM-QUANTITY-ILLUMINANCE-001`  
**Preferred Name:** Illuminance  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Photometry / Imaging / Lighting  
**Status:** Active  
**Version:** 1.0.0

> Illuminance is the photometric quantity describing luminous flux incident on a surface per unit area under a defined geometrical and photometric context.

## What

Illuminance quantifies the incident luminous flux density on a receiving surface.

## Why

It is important for lighting design, scene illumination characterization, camera exposure analysis, visual assessment, display environments, and photometric measurement.

## Structure

A complete illuminance statement identifies the receiving surface or plane, spatial location/orientation where relevant, value, unit, and measurement context.

## How

Illuminance can be established through photometric measurement or calculation using an appropriate photometric model. The measurement method, geometry, spectral weighting, and uncertainty qualify the result.

## Where

It applies to scene surfaces, work planes, imaging environments, display surroundings, laboratories, and other receiving surfaces.

## Who

Lighting professionals, photographers, cinematographers, display engineers, imaging scientists, metrologists, and AI systems using photometric data.

## Core Distinctions

### Illuminance vs Luminance

Illuminance concerns incident luminous flux per unit area. Luminance concerns light leaving or being emitted/reflected from a surface in a specified direction per projected area and solid angle.

### Illuminance vs Illumination Condition

Illuminance is a Quantity. Illumination Condition is a Condition describing the relevant circumstance of illumination.

### Illuminance vs Irradiance

Illuminance is photometric and incorporates human-vision-based spectral weighting. Irradiance is radiometric.

## Units and Value Semantics

The SI coherent unit is lux (lm/m²). A value must retain its photometric identity and relevant geometry.

## Technical Depth

Illuminance depends on incident luminous flux and receiving area. Spatial non-uniformity means a single reported value may represent a point, average, maximum, minimum, or other statistic; that qualification must not be silently omitted.

## Constraints / Assumptions

Do not infer illuminance from radiometric quantities without the required spectral weighting and photometric context. Do not equate illuminance with perceived brightness.

## Evidence / Trust / Validation

Illuminance has established photometric Quantity responsibility. Measurement claims should preserve instrument, geometry, spectral response, calibration, method, and uncertainty information where relevant.

## Relations

Potential relations include `illuminates`, association with receiving surfaces, observation contexts, and measurement activities. Canonical relation identities are governed independently.

## Machine / AI Interpretation

`Illuminance` resolves to `SEM-QUANTITY-ILLUMINANCE-001`. `500 lx` is a quantity value expression, not the Quantity concept.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`ILLUMINANCE`, `LUX`, `PHOTOMETRIC ILLUMINANCE`, `LUMINOUS FLUX DENSITY`, `INCIDENT ILLUMINANCE`
