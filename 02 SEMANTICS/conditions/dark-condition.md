# Dark Condition

**Semantic ID:** `SEM-CONDITION-DARK-001`  
**Preferred Name:** Dark Condition  
**Semantic Class:** Optical Condition  
**Domain:** Optical Imaging  
**Status:** Provisional  
**Version:** 0.2.0

## 5W1H Orientation

### What

A Dark Condition is an Optical Condition in which relevant optical radiation is absent, negligible, blocked, unavailable, or insufficient for a defined observational or measurement context.

### Why

Darkness is fundamental to imaging, but it is frequently misunderstood.

Physical darkness is not necessarily equivalent to zero radiation, zero sensor output, zero display output, black image values, underexposure, shadow, or perceived darkness.

A precise Dark Condition allows these different meanings to remain distinct.

### Who

The concept is relevant to all imaging participants, including general visitors, photographers, cinematographers, optical and sensor engineers, imaging scientists, metrology professionals, machine-vision engineers, AI systems, forensic analysts, and machine-readable consumers.

### Where

It may occur in physical scenes, optical paths, shadow regions, measurement configurations, sensor environments, display systems, simulations, or other imaging contexts.

### When

Dark Condition is always evaluated for a specified temporal context.

A region can transition from Light to Dark, Dark to Light, or through intermediate conditions.

### How

A Dark Condition is determined relative to the radiation that is relevant to the specified receiver, observer, sensor, spectral range, direction, threshold, or measurement configuration.

The same environment can therefore be Dark for one system and a Light Condition for another.

## Semantic Definition

**Dark Condition** is an Optical Condition in which relevant optical radiation is absent, negligible, blocked, unavailable, or insufficient within a defined spatial, temporal, spectral, directional, observational, or measurement context.

Dark Condition is contextual and must not be interpreted as an assertion that all electromagnetic radiation is absent.

## Core Distinctions

### Physical Dark vs Sensor Dark

A physical environment may be sufficiently dark for a sensor while the sensor still produces dark current, offsets, read noise, or other non-zero output.

Therefore:

`Dark Condition ≠ Zero Sensor Signal`

### Physical Dark vs Display Black

A display produces a new optical output.

Display black therefore does not establish that the original scene was physically dark.

### Physical Dark vs Perceptual Darkness

Perceived darkness depends on observer adaptation, visual sensitivity, contrast, surrounding conditions, and other perceptual factors.

### Physical Dark vs Underexposure

Underexposure is a capture condition or outcome involving insufficient exposure relative to the intended representation or measurement objective.

A physically well-lit scene can be underexposed.

### Physical Dark vs Shadow

A shadow is an optical consequence of occlusion relative to a source and receiving region.

A shadow can be dark without being completely radiation-free.

## Boundary Conditions

A Dark Condition may arise because relevant radiation is:

- physically absent;
- sufficiently weak;
- outside the relevant spectral sensitivity;
- blocked by an occluder;
- unavailable along the relevant propagation path;
- below a defined detection or measurement threshold;
- intentionally excluded by an optical or measurement configuration.

Darkness is therefore not necessarily a universal binary condition.

## Continuum Interpretation

Dark and Light should not automatically be treated as two mutually exclusive numerical states.

Relevant conditions may occupy continua such as:

`very low → low → moderate → high → extreme`

Different systems may interpret these conditions differently because physical, measurement, and perceptual scales are not identical.

## Measurement Context

A sensor operating under a Dark Condition may still produce non-zero measurements.

Dark current, read noise, offsets, thermal effects, and electronic noise can remain present without useful incident optical radiation.

Therefore any statement about a “dark signal” must identify the measurement context.

## Special Measurement Configurations

Darkness can also be an intentional measurement configuration. In dark-field microscopy, for example, direct illumination is excluded from the collection path while scattered light from the specimen is collected.

A dark background therefore does not imply absence of all optical information.

This demonstrates why semantic context is essential: `dark` may describe a physical condition, a measurement arrangement, or a representation.

## Computational and AI Context

An AI system may increase apparent brightness, reconstruct hidden information, or infer scene content from a dark representation.

Such output does not retroactively establish the original physical optical condition.

An inferred or enhanced representation must remain distinguishable from the original observation.

## Cross-Domain Significance

Dark Condition connects physical optical absence or insufficiency with sensing thresholds, noise, shadow, visibility, low-light capture, perception, computational enhancement, display rendering, and forensic interpretation.

## Trust

A Dark Condition statement should identify the relevant context whenever ambiguity could alter its meaning.

Statements such as “the scene was dark” are incomplete unless the relevant observer, sensor, spectral band, spatial region, temporal interval, or measurement regime is understood.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`DARK CONDITION`, `DARK`, `OPTICAL CONDITION`, `LOW LIGHT`, `DARK SIGNAL`, `DARK CURRENT`, `DARK NOISE`, `SHADOW`, `OCCLUSION`, `VISIBILITY`, `PERCEPTION`, `UNDEREXPOSURE`
