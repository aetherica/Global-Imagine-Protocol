# Light

**Semantic ID:** `SEM-CONDITION-LIGHT-001`
**Preferred Name:** Light
**Semantic Class:** Optical Condition
**Domain:** Optical Imaging
**Status:** Provisional
**Version:** 0.1.0

## 5W1H Orientation

### What
Light is the condition in which relevant optical radiation is available at a specified location, time, direction, spectral domain, observer, or sensing system at a level relevant to the intended observation or measurement.

### Why
Light is the physical starting condition for optical imaging. Imaging systems do not operate on an abstract image first; they interact with radiation that can be emitted, transmitted, reflected, scattered, absorbed, received, measured, and represented.

### Who
The concept is used by general visitors, students, photographers and cinematographers, optical and sensor engineers, imaging scientists, computer-vision and AI researchers, calibration and validation professionals, system integrators, and machine-readable consumers.

### Where
It applies to optical radiation in imaging environments, including visible and non-visible spectral regions when those regions are relevant to the observing or sensing system.

### When
Light is evaluated over a defined time or interval. Temporal variation can affect exposure, motion, measurement, detectability, and representation.

### How
The meaning of light depends on what receiver or observer is being considered. Radiation that is sufficient for one sensor may be insufficient for another, and radiation invisible to a human observer may still be measurable by an imaging system.

## Semantic Definition

**Light** is the condition in which relevant optical radiation is available at a specified location, time, direction, spectral domain, observer, or sensing system at a level relevant to the intended observation or measurement.

Light is therefore a contextual physical condition, not a universal scalar and not necessarily limited to visible radiation.

## Core Distinctions

- Light is not synonymous with visible light in every imaging context.
- Light availability is not identical to visibility; an available signal may remain below an observer's or sensor's effective detectability threshold.
- Light is not identical to illumination. Illumination concerns radiation reaching a receiving region or surface under a defined geometry and measurement context.
- Light is not identical to brightness. Brightness is a perceptual concept.
- A display can emit light while representing a scene that was physically dark; reproduced light is not the original scene radiation.

## Optical Roles

Relevant radiation may be:

- emitted by a source;
- transmitted through a medium or optical element;
- reflected by a surface;
- scattered by a medium or surface;
- absorbed by matter;
- received by an observer or sensing system.

These are distinct semantic relations and must not be collapsed into the single term `light`.

## Measurement Context

A statement that an environment is light should, when precision matters, identify the receiving or observing context and the relevant spectral, spatial, temporal, directional, and measurement conditions.

Radiometric quantities such as radiance, irradiance, radiant flux, and radiant intensity provide quantitative descriptions of optical radiation. Their numerical definitions do not belong to this semantic entry.

## Relations

- `emits`
- `illuminates`
- `is-received-by`
- `is-visible-from`
- `is-measured-by`
- `contributes-to`
- `transforms-into`
- `is-represented-by`

## Trust

This entry defines the semantic use of `Light` in GIOP. It does not assert a universal intensity threshold or replace radiometric, photometric, sensor, or perceptual measurement standards.

The entry is consistent with the GIOP principle that imaging knowledge connects observation, measurement, computation, and perception while preserving the distinctions between those layers.

## Lifecycle

**Current state:** Provisional semantic entry.

Required next steps include cross-domain verification, relation validation, terminology review, and eventual registry assignment after semantic validation.

## Retrieval Anchors

`LIGHT`, `OPTICAL CONDITION`, `OPTICAL RADIATION`, `OPTICAL AVAILABILITY`, `ILLUMINATION`, `VISIBILITY`, `RADIANCE`, `IRRADIANCE`, `RECEIVED RADIATION`, `IMAGING`
