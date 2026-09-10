# Dark

**Semantic ID:** `SEM-CONDITION-DARK-001`
**Preferred Name:** Dark
**Semantic Class:** Optical Condition
**Domain:** Optical Imaging
**Status:** Provisional
**Version:** 0.1.0

## 5W1H Orientation

### What
Dark is the condition in which relevant optical radiation is absent, negligible, obstructed, or insufficient for a specified observation or measurement under defined conditions.

### Why
Darkness is not simply the opposite word for a bright pixel. It is a physically and operationally meaningful condition that affects observation, measurement, capture, detectability, representation, computation, and perception.

### Who
The concept is relevant to general visitors and students as well as photographers, cinematographers, sensor and optical engineers, imaging scientists, computer-vision and AI researchers, calibration and metrology professionals, forensic specialists, system integrators, and machine-readable consumers.

### Where
It applies to defined spatial regions, optical paths, environments, measurement configurations, sensor conditions, and other imaging contexts in which relevant radiation is unavailable or insufficient.

### When
Darkness is evaluated for a defined temporal condition. A region may transition between light and dark, and a sensor may experience a dark measurement condition even while the surrounding environment contains radiation outside the measurement path or spectral band.

### How
Darkness is determined relative to a specified observer or sensing system, spectral domain, geometry, time, and measurement condition. It may result from absence, negligible availability, occlusion, insufficient signal, or deliberate measurement configuration.

## Semantic Definition

**Dark** is the condition in which relevant optical radiation is absent, negligible, obstructed, or insufficient for a specified observation or measurement under defined conditions.

Dark is therefore contextual. It is not defined as universal zero radiation, universal zero sensor output, universal black, or a single numerical value.

## Core Distinctions

- **Physical dark** concerns the relevant optical radiation field under defined conditions.
- **Sensor dark** concerns detector output measured without the intended optical input; the output may still contain dark current, read noise, offsets, and other detector or electronic contributions.
- **Display dark** is a display representation produced by controlled light emission and does not reproduce physical absence of radiation.
- **Perceived darkness** is an observer-dependent perceptual state influenced by adaptation, contrast, surround, and viewing conditions.
- **Shadow** is not synonymous with dark. A shadow is a spatial consequence of occlusion that reduces direct visibility of a source; indirect or scattered radiation may remain.
- **Underexposure** is not synonymous with physical darkness. It is a capture condition in which the recorded signal is insufficient for the intended result or measurement.

## Measurement Context

A dark condition must identify the relevant measurement context when precision is required. Relevant variables can include:

- spectral range;
- spatial region;
- time or exposure interval;
- direction and optical path;
- observer or sensor sensitivity;
- measurement threshold;
- background and competing signals;
- whether the condition is physical, instrumental, representational, or perceptual.

A sensor may produce non-zero output in a dark measurement condition. Consequently, `dark` must not be treated as equivalent to `signal = 0` without an explicitly defined model and measurement condition.

## Special Measurement Configurations

Darkness can also be an intentional measurement configuration. In dark-field microscopy, for example, direct illumination is excluded from the collection path while scattered light from the specimen is collected. A dark background therefore does not imply absence of all optical information.

This demonstrates why semantic context is essential: `dark` may describe a physical condition, a measurement arrangement, or a representation.

## Low-Light and Computational Imaging

Low-light imaging may produce sparse photon measurements, increased relative noise, reduced detectability, motion blur, or other capture limitations. Computational enhancement can alter the representation or infer information from the measured data.

An enhanced or reconstructed image must not be interpreted as identical to the original physical optical condition merely because its output appears brighter.

## Relations

- `is-dark-under`
- `has-insufficient-optical-availability`
- `is-occluded-by`
- `reduces-direct-illumination`
- `produces-dark-signal`
- `affects-detectability`
- `is-represented-by`
- `is-perceived-as`

## Trust

This entry defines semantic meaning and distinctions. It does not establish a universal numerical definition of darkness.

Quantitative thresholds, dark-current characterization, noise models, low-light performance, perceptual thresholds, and measurement procedures must be taken from their applicable technical definitions and authoritative standards.

The entry is intentionally conservative: absence of measurable signal is not assumed to prove absence of physical radiation, and a reconstructed representation is not assumed to prove the original scene state.

## Lifecycle

**Current state:** Provisional semantic entry.

Required next steps include cross-domain verification, terminology review, relation validation, and eventual registry assignment after semantic validation.

## Retrieval Anchors

`DARK`, `DARKNESS`, `OPTICAL CONDITION`, `LOW LIGHT`, `DARK SIGNAL`, `DARK CURRENT`, `DARK NOISE`, `SHADOW`, `OCCLUSION`, `DETECTABILITY`, `DARK-FIELD MICROSCOPY`, `PERCEIVED DARKNESS`
