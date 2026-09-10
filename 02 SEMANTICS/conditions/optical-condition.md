# Optical Condition

**Semantic ID:** `SEM-CONDITION-OPTICAL-001`
**Preferred Name:** Optical Condition
**Semantic Class:** Condition
**Domain:** Optical Imaging
**Status:** Provisional
**Version:** 0.1.0

## 5W1H Orientation

### What
An optical condition is a defined state of relevant optical influence at a specified spatial, temporal, spectral, directional, and observational context.

### Why
Imaging begins with physical conditions that determine whether radiation is available to interact with an object, surface, aperture, observer, or sensing system. A common semantic concept is required so that terms such as light, dark, illumination, shadow, visibility, and received radiation can be related without treating them as interchangeable.

### Who
This concept is relevant to anyone who needs to understand, measure, model, capture, reproduce, simulate, or interpret optical imaging conditions, from general visitors and students through imaging professionals, engineers, scientists, validation specialists, and machine-readable consumers.

### Where
It applies wherever optical radiation is observed, measured, modeled, transformed, represented, or reproduced.

### When
The condition is always evaluated for a defined temporal context. An optical condition may change with exposure time, motion, illumination, environment, adaptation, or other time-dependent factors.

### How
An optical condition is characterized relative to relevant radiation and the receiving or observing system. The same physical scene may therefore have different operational consequences for different sensors or observers.

## Semantic Definition

**Optical Condition** is the state of relevant optical influence at a defined spatial, temporal, spectral, directional, and observational context.

This definition is contextual rather than absolute. It does not assert that an optical condition is a substance, object, or universal binary numerical state.

## Core Distinctions

- **Light** and **Dark** are complementary semantic conditions within the optical domain.
- **Dark** does not necessarily mean zero radiation.
- **Physical darkness**, **sensor dark signal**, **display dark**, and **perceived darkness** are distinct contexts.
- **Shadow** is an optical phenomenon produced by occlusion and reduced direct visibility of a source; it is not synonymous with darkness.
- **Visibility** describes an observation relationship, not merely the presence of radiation.

## Context Requirements

An optical-condition statement should identify, where relevant:

- spatial location or region;
- temporal interval or instant;
- spectral domain;
- propagation or observation direction;
- source and receiving system;
- observer or sensor characteristics;
- measurement configuration;
- relevant threshold or sensitivity;
- whether the statement concerns physical state, measurement, representation, or perception.

## Relations

- `has-condition`
- `has-optical-availability`
- `illuminates`
- `emits`
- `receives`
- `occludes`
- `is-visible-from`
- `measures`
- `represents`

## Trust

This entry establishes semantic meaning only. It does not by itself establish a numerical threshold, measurement standard, sensor specification, or perceptual threshold.

The concepts are aligned with the broader GIOP imaging chain from observation and measurement through computation and perception. Numerical definitions and domain-specific measurement procedures belong to the relevant technical content and authoritative standards.

## Lifecycle

**Current state:** Provisional semantic entry.

This entry is intended for review, cross-domain verification, refinement, and eventual canonical registration when the required evidence and semantic validation are complete.

## Retrieval Anchors

`OPTICAL CONDITION`, `LIGHT`, `DARK`, `OPTICAL AVAILABILITY`, `VISIBILITY`, `ILLUMINATION`, `OCCLUSION`, `SHADOW`, `RECEIVED RADIATION`, `MEASUREMENT`, `PERCEPTION`
