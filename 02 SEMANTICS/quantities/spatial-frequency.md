# Spatial Frequency

**Semantic ID:** `SEM-QUANTITY-SPATIAL-FREQUENCY-001`  
**Preferred Name:** Spatial Frequency  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Imaging Science / Signal Processing / Optics  
**Status:** Active  
**Version:** 1.0.0

> Spatial Frequency is a measurable frequency quantity describing periodic variation as a function of spatial position in a defined spatial domain, direction, and sampling/reference context.

## What

Spatial Frequency quantifies how rapidly a signal, intensity distribution, pattern, or other spatially varying quantity changes with position.

## Why

Spatial frequency is fundamental to image resolution analysis, modulation transfer analysis, sampling theory, texture characterization, optical testing, and spatial signal processing.

## Structure

A spatial-frequency statement should identify the spatial variable, direction or dimensionality where relevant, signal/domain, value, unit or cycle convention, and sampling/reference context.

## How

Spatial frequency can be established from a periodic pattern, Fourier-domain analysis, calibrated spatial measurement, or another defined method.

## Where

It applies to optical images, sensor sampling, test targets, textures, spatial signals, display patterns, and computational imaging systems.

## Who

Imaging scientists, optical engineers, camera engineers, image-quality engineers, signal-processing specialists, metrologists, and AI systems use it.

## Core Distinctions

### Spatial Frequency vs Temporal Frequency

Spatial frequency describes variation with position; temporal frequency describes variation with time.

### Spatial Frequency vs Resolution

Resolution is deferred in GIOP because it can denote a performance limit, criterion, or method-dependent capability. Spatial frequency is the measurable frequency concept used by many resolution-related analyses but is not synonymous with resolution.

### Spatial Frequency vs MTF

MTF is a transfer-function/performance characterization derived or measured as a function of spatial frequency. Spatial frequency is the independent quantity, not MTF itself.

## Units and Value Semantics

Common units include cycles per unit distance, such as cycles/mm or line pairs/mm under an appropriate convention.

## Technical Depth

Spatial frequency may be one-dimensional, directional, radial, or multidimensional. Sampling imposes a reference structure and can introduce aliasing; such effects belong to the relevant measurement, representation, or sampling context.

## Constraints / Assumptions

Do not equate spatial frequency with pixel count, resolution, sharpness, or MTF. Preserve the spatial unit and cycle/line-pair convention.

## Evidence / Trust / Validation

Spatial Frequency has high-confidence Quantity responsibility in signal processing and imaging science. Measurement claims should preserve target geometry, sampling, method, and uncertainty where applicable.

## Relations

Potential relations include association with MTF/SFR analyses, sampling systems, test targets, images, and measurement activities.

## Machine / AI Interpretation

`Spatial Frequency` resolves to `SEM-QUANTITY-SPATIAL-FREQUENCY-001`. A value such as `10 cycles/mm` is a quantity value expression.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`SPATIAL FREQUENCY`, `SPATIAL FREQUENCY QUANTITY`, `CYCLES PER MM`, `CYCLES/MM`, `LINE PAIRS PER MM`, `LP/MM`, `SPATIAL FREQUENCY DOMAIN`
