# Quantity

**Semantic ID:** `SEM-QUANTITY-GENERIC-001`  
**Preferred Name:** Quantity  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** General Metrology / Imaging  
**Status:** Active  
**Version:** 1.0.0

> Quantity is a reusable canonical semantic concept denoting a measurable aspect of an eligible entity, phenomenon, system, material, spatial region, temporal occurrence, or other bearer whose magnitude can be expressed through an appropriate value-and-reference structure.

## What

A Quantity identifies what measurable aspect is being quantified. It is the semantic concept that can be instantiated or qualified by particular magnitudes, units, references, temporal scopes, spatial scopes, and measurement contexts.

Examples include distance, duration, temperature, wavelength, focal length, illuminance, luminance, radiance, irradiance, and spatial frequency.

## Why

Technical and scientific information frequently combines a semantic concept with a numerical value, unit, measurement method, uncertainty, and context. Separating these elements is necessary for interoperable knowledge representation and machine reasoning.

## Structure

A Quantity concept may participate in a structure such as:

`Quantity → Quantity Value → Unit / Reference`

and, when established by measurement:

`Quantity → Measurand → Measurement Activity → Measurement Result → Quantity Value + qualification`

The exact measurement architecture may vary by domain; Quantity identity does not depend on one implementation model.

## How

A Quantity value may be established by measurement, observation, calculation, modelling, simulation, or other justified procedures. The mechanism establishing a value does not change the semantic identity of the Quantity.

## Where

Quantities can characterize physical systems, optical systems, sensors, displays, scenes, materials, spatial regions, temporal phenomena, computational models, and measurement arrangements.

## Who

The concept is usable at every GIOP entry depth: general orientation, learning, professional imaging, engineering, science, metrology, AI/data processing, system integration, enterprise technology, preservation, and technical communication.

## When

A quantity value may apply at an instant, interval, or time-varying domain. Temporal qualification belongs to the value/assertion/context rather than being required as part of the Quantity concept itself.

## Semantic Definition

A Quantity is a reusable semantic concept for a measurable aspect that can be assigned or established through a magnitude/value structure under an appropriate reference system.

## Scope

This generic concept governs the semantic layer. Domain-specific Quantity entries must establish their own identity and scope and must not merely repeat this definition.

## Core Distinctions

### Quantity vs Quantity Value

Quantity identifies the measurable aspect; Quantity Value expresses a particular magnitude for that aspect.

### Quantity vs Unit

Unit provides an expression/reference convention for a value. It is not the measurable aspect.

### Quantity vs Measurement

Measurement is an activity used to establish a value of a quantity.

### Quantity vs Measurement Result

A measurement result is information produced by a measurement activity and may contain one or more quantity values, uncertainty, context, and provenance.

### Quantity vs Property

A Property denotes a characteristic. A measurable characteristic may be represented using quantities, but the concepts remain distinct unless semantic responsibility is identical by evidence.

### Quantity vs State

A State denotes a recognized mode at a temporal locus. A quantity may characterize a state without being the state.

### Quantity vs Condition

A Condition denotes a relevant circumstance or condition. A quantity can specify or qualify a condition.

### Quantity vs Metric

A metric may be a calculated or evaluative construct and is not automatically a Quantity.

### Quantity vs Parameter / Variable

Parameter and Variable are model roles. They can carry quantity values without becoming Quantity concepts.

## Quantity Characteristics

A Quantity may be associated with:

- quantity kind;
- quantity dimension;
- scalar or structured mathematical form;
- unit system;
- reference or scale;
- temporal and spatial scope;
- uncertainty and qualification;
- measurement method and context.

These characteristics do not automatically constitute separate V3.1 canonical layers.

## Technical Depth

Physical quantities can have dimensions and compatible units. Dimensionless quantities can remain quantities when their measurable semantic responsibility is established. Ratios, logarithmic expressions, and derived quantities require domain-specific validation rather than automatic exclusion.

A numerical expression can be a quantity value without the surrounding term being a Quantity concept. Conversely, a Quantity concept remains valid independently of whether a value is currently available.

## Constraints / Assumptions

A Quantity entry must not silently assume a unit, scale, reference, measurement method, uncertainty, or application-specific convention when those affect interpretation.

The word `measurement` in a source does not automatically mean the source is defining a Quantity. Likewise, the word `parameter` does not automatically exclude a concept from Quantity.

## Evidence / Trust / Validation

Quantity classification is based on semantic responsibility, normative and scientific evidence, conflict analysis, and cross-layer validation. Source authority is not identical to GIOP canonical authority.

## Relations

Potential relation patterns include relations to values, units, measurement activities, measurement results, conditions, contexts, states, properties, and representations. Relation identities are governed independently by the GIOP Relation layer.

## Machine / AI Interpretation

Machine consumers should represent Quantity identity separately from literal values, units, measurement activities, results, uncertainty, contexts, and provenance. Stable Semantic IDs are authoritative identifiers; path and lexical coincidence are not.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`QUANTITY`, `MEASURABLE QUANTITY`, `PHYSICAL QUANTITY`, `QUANTITY CONCEPT`, `MEASURABLE ASPECT`, `QUANTITY KIND`, `QUANTITY DIMENSION`, `QUANTITY VALUE`, `MEASUREMENT`
