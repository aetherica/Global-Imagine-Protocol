# Optical Condition

**Semantic ID:** `SEM-CONDITION-OPTICAL-001`  
**Preferred Name:** Optical Condition  
**Semantic Class:** Condition  
**Domain:** Optical Imaging  
**Status:** Provisional  
**Version:** 0.2.0

## 5W1H Orientation

### What

An Optical Condition is the defined state of relevant optical influence within a specified spatial, temporal, spectral, directional, observational, or measurement context.

It provides a common semantic basis for describing conditions such as Light, Dark, Illumination, optical availability, and related imaging circumstances.

### Why

Imaging depends on physical and contextual conditions that determine whether radiation exists, propagates, interacts with matter, reaches a receiver, or becomes observable or measurable.

Without a common condition concept, terms such as Light, Dark, Illumination, Shadow, Visibility, and Received Radiation can be incorrectly treated as interchangeable.

### Who

The concept is relevant to anyone who needs to describe, interpret, model, measure, capture, simulate, reproduce, validate, or retrieve optical imaging conditions.

This includes general visitors, students, educators, photographers, cinematographers, imaging engineers, scientists, metrology professionals, AI systems, and machine-readable consumers.

### Where

Optical conditions may be defined in a physical scene, optical system, measurement setup, sensor environment, viewing environment, display environment, simulation, or computational imaging system.

### When

An Optical Condition is always associated with a temporal context.

It may vary continuously or discretely with illumination, motion, exposure, environmental change, source activity, sensor state, observer adaptation, or other time-dependent factors.

### How

An Optical Condition is characterized relative to relevant optical radiation and the entities, regions, observers, sensors, or measurement systems affected by that radiation.

The same physical environment may therefore produce different operational consequences for different observers or sensing systems.

## Semantic Definition

**Optical Condition** is the contextual state of relevant optical influence at a defined spatial, temporal, spectral, directional, observational, or measurement context.

The concept is contextual rather than absolute.

An Optical Condition is not itself:

- a physical substance;
- an optical quantity;
- a measurement result;
- a perceptual state;
- a digital representation;
- a device;
- a registered entity.

## Core Distinctions

### Optical Condition vs Light Condition

An Optical Condition is the broader contextual category.

Light Condition identifies a condition in which relevant optical radiation is present or operative within a defined context.

### Optical Condition vs Dark Condition

Dark Condition identifies a condition in which relevant radiation is absent, negligible, blocked, unavailable, or below a defined operational regime.

Darkness does not necessarily imply zero physical radiation.

### Optical Condition vs Illumination Condition

Illumination Condition concerns the optical influence applied to a receiving region, surface, object, or scene.

Light may be present without a particular receiving region being directly illuminated.

### Optical Condition vs Perception

An optical condition is not the same thing as how an observer perceives it.

Physical radiation, sensor response, and perceived brightness or darkness may differ substantially.

### Optical Condition vs Measurement

An optical condition may be measured, but the condition itself is not the measurement result.

## Context Dimensions

Where relevant, an Optical Condition should be interpreted with respect to:

- spatial region or location;
- temporal instant or interval;
- spectral domain;
- propagation or observation direction;
- source or originating region;
- receiving surface, object, sensor, or observer;
- sensor or observer characteristics;
- measurement configuration;
- relevant threshold or sensitivity;
- whether the statement concerns physical state, measurement, representation, or perception.

## Semantic Relations

Potential canonical relations include:

- `has-condition`
- `has-optical-availability`
- `illuminates`
- `emits`
- `receives`
- `occludes`
- `is-visible-from`
- `affects-observation`
- `affects-measurement`
- `represents`

These relations are defined independently in the GIOP semantic relation domain.

## Cross-Domain Significance

Optical Condition provides a semantic bridge between:

`Light / Dark → Availability → Illumination → Interaction → Observation → Measurement → Capture → Representation → Perception`

The concept therefore has relevance across the physical, optical, sensing, computational, perceptual, display, and imaging domains.

## Trust

This entry defines semantic meaning.

It does not establish a universal numerical threshold for Light, Dark, Visibility, Illumination, or Detectability.

Numerical thresholds, sensor characteristics, radiometric quantities, metrological procedures, perceptual models, and domain-specific performance criteria belong to their responsible semantic or technical domains.

## Lifecycle

**Current state:** Provisional semantic entry.

The concept is intended for continued cross-domain verification and eventual canonical validation and registration when the required semantic and evidentiary requirements are satisfied.

## Retrieval Anchors

`OPTICAL CONDITION`, `LIGHT CONDITION`, `DARK CONDITION`, `ILLUMINATION CONDITION`, `OPTICAL AVAILABILITY`, `VISIBILITY`, `OCCLUSION`, `SHADOW`, `RECEIVED RADIATION`, `OBSERVATION`, `MEASUREMENT`, `PERCEPTION`
