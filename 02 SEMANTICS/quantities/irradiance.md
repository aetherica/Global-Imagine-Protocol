# Irradiance

**Semantic ID:** `SEM-QUANTITY-IRRADIANCE-001`  
**Preferred Name:** Irradiance  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Radiometry / Optics / Imaging  
**Status:** Active  
**Version:** 1.0.0

> Irradiance is the radiometric quantity describing radiant power incident on a receiving surface per unit area under a defined spectral and geometrical context.

## What

Irradiance quantifies incident radiant flux density on a receiving surface.

## Why

It is important for optical power analysis, sensor exposure, solar/lighting characterization, detector calibration, radiometric imaging, and energy-transfer analysis.

## Structure

A complete statement identifies the receiving surface or plane, location/orientation where relevant, spectral domain, value, unit, and measurement context.

## How

Irradiance can be measured with calibrated radiometric systems or calculated from a defined radiometric model.

## Where

It applies to detector planes, scene surfaces, optical receivers, imaging systems, illumination systems, and radiometric test setups.

## Who

Radiometrists, optical engineers, sensor engineers, imaging scientists, calibration professionals, and computational imaging specialists use it.

## Core Distinctions

### Irradiance vs Radiance

Irradiance is incident radiant power per area. Radiance additionally describes directional distribution per projected area and solid angle.

### Irradiance vs Illuminance

Irradiance is radiometric. Illuminance is photometric and applies luminous weighting.

### Irradiance vs Exposure

Irradiance describes incident power density. A time-integrated radiant exposure involves duration and is a distinct quantity.

## Units and Value Semantics

Irradiance is commonly expressed in watts per square metre (W/m²), with spectral forms carrying the relevant additional spectral dimension.

## Technical Depth

Spatial and spectral non-uniformity can make a single value dependent on sampling geometry, area averaging, bandwidth, and orientation. Those qualifications belong with the value/result/context.

## Constraints / Assumptions

Do not infer photometric illuminance without the required spectral weighting. Do not confuse irradiance with radiance or radiant flux.

## Evidence / Trust / Validation

Irradiance has established radiometric Quantity responsibility. Calibration, detector response, geometry, bandwidth, and uncertainty may materially affect measurement validity.

## Relations

Potential relations include association with receiving surfaces, sources, sensors, radiance fields, measurement activities, and optical conditions.

## Machine / AI Interpretation

`Irradiance` resolves to `SEM-QUANTITY-IRRADIANCE-001`. A value such as `10 W/m²` is a quantity value expression.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`IRRADIANCE`, `RADIOMETRIC IRRADIANCE`, `SPECTRAL IRRADIANCE`, `IRRADIANCE QUANTITY`, `W/M2`, `W M-2`
