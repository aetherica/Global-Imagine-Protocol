# Light Condition

**Semantic ID:** `SEM-CONDITION-LIGHT-001`  
**Preferred Name:** Light Condition  
**Semantic Class:** Optical Condition  
**Domain:** Optical Imaging  
**Status:** Provisional  
**Version:** 0.2.0

## 5W1H Orientation

### What

A Light Condition is an Optical Condition in which relevant optical radiation is present, available, or operative within a specified context.

### Why

Imaging requires radiation that can propagate, interact with matter, reach a receiving system, or participate in observation or measurement.

A Light Condition therefore describes an optical circumstance rather than identifying a particular light source or assigning a universal brightness value.

### Who

The concept is relevant to general visitors, students, photographers, cinematographers, optical engineers, sensor engineers, imaging scientists, metrology professionals, AI systems, simulation systems, and machine-readable consumers.

### Where

It may occur in a scene, optical path, receiving region, measurement setup, sensor environment, viewing environment, or simulated imaging environment.

### When

A Light Condition exists only relative to a defined temporal context.

The condition may vary with source activity, motion, exposure interval, environmental change, modulation, or other time-dependent factors.

### How

A Light Condition is determined relative to the relevant radiation and the receiver, observer, sensor, measurement configuration, or region under consideration.

The same environment may be a Light Condition for one observer or sensor and an operationally Dark Condition for another because sensitivity, spectral response, direction, or measurement configuration differs.

## Semantic Definition

**Light Condition** is an Optical Condition in which relevant optical radiation is present, available, or operative for a defined spatial, temporal, spectral, directional, observational, or measurement context.

Light Condition does not imply a particular numerical intensity, luminance, radiance, exposure, perceptual brightness, or sensor signal.

## Core Distinctions

### Light Condition vs Light Source

A Light Source is an emitting or otherwise source-forming entity.

A Light Condition describes the resulting contextual optical circumstance.

### Light Condition vs Illumination Condition

A Light Condition can describe radiation being present within a region or optical environment.

An Illumination Condition specifically concerns the optical influence delivered to a receiving region, surface, object, or scene.

### Light Condition vs Brightness

Brightness is a perceptual concept.

Light Condition is an optical condition.

### Light Condition vs Radiance or Irradiance

Radiance and irradiance are measurable radiometric quantities.

A Light Condition may be characterized using such quantities but is not itself a quantity.

### Light Condition vs Exposure

Exposure is a capture-related or measurement-related concept involving integration over time and system response.

A Light Condition may exist before, during, or after an exposure interval.

## Boundary Cases

A Light Condition may exist even when:

- radiation is outside the visible spectrum;
- the radiation is not perceptually visible to a human observer;
- a sensor is below its detection threshold;
- a display does not reproduce the original radiation;
- illumination is indirect rather than direct;
- radiation exists in only a limited spectral band;
- radiation is spatially or temporally localized.

Therefore:

**Human invisibility does not imply physical darkness.**

**Low sensor response does not by itself imply absence of radiation.**

## Cross-Domain Significance

Light Condition provides the positive optical counterpart to Dark Condition while remaining distinct from perceptual brightness and numerical radiometric quantities.

It participates in the broader relationship:

`Light → Availability → Interaction → Illumination → Observation → Measurement → Capture`

## Trust

This entry does not assign a universal threshold separating Light from Dark.

Thresholds depend on the relevant physical, spectral, sensor, observer, and measurement context.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`LIGHT CONDITION`, `LIGHT`, `OPTICAL CONDITION`, `OPTICAL AVAILABILITY`, `ILLUMINATION`, `RADIATION`, `RECEIVED RADIATION`, `OBSERVATION`, `MEASUREMENT`
