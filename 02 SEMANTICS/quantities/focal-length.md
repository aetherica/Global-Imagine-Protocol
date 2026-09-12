# Focal Length

**Semantic ID:** `SEM-QUANTITY-FOCAL-LENGTH-001`  
**Preferred Name:** Focal Length  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Geometrical Optics / Imaging  
**Status:** Active  
**Version:** 1.0.0

> Focal Length is a measurable optical distance associated with the imaging or optical behavior of a defined optical system under its applicable optical model and reference conditions.

## What

Focal Length identifies an optical distance associated with an optical system. In idealized geometrical optics it is defined through the system's focal properties; in real optical systems its interpretation depends on the applicable optical model and reference conventions.

## Why

Focal length is fundamental to optical characterization, lens selection, imaging geometry, field-of-view analysis, and system modelling.

## Structure

A focal-length statement should identify the optical system and, where relevant, the reference convention, object/image space, wavelength or spectral condition, focus condition, and numerical value with unit.

## How

Focal length can be established through optical measurement, calibration, design data, or a defined optical model. The measurement method and uncertainty belong to the relevant measurement/result context rather than changing Quantity identity.

## Where

It applies to lenses, optical assemblies, imaging systems, and other systems for which a focal length is meaningfully defined.

## Who

It is relevant to photographers, cinematographers, lens designers, optical engineers, imaging scientists, metrologists, system integrators, educators, and machine consumers.

## Semantic Definition

Focal Length is a measurable optical distance describing the focal property of a defined optical system under an applicable optical model and reference convention.

## Core Distinctions

### Focal Length vs Distance

Focal length is a specialized optical distance quantity. Generic Distance is the broader spatial quantity.

### Focal Length vs Lens Parameter

Focal length may be used as a parameter in an engineering model, but `parameter` is a model role and is not its canonical semantic owner.

### Focal Length vs Field of View

Field of view is a geometric/angular characteristic or related derived quantity. It is not identical to focal length.

### Focal Length vs F-number

F-number expresses a ratio involving focal length and aperture. It is not identical to focal length.

### Focal Length vs Focus State

Focus State is a state of an imaging/optical system. Focal length is a quantity associated with optical geometry.

## Technical Depth

For a thin-lens idealization, focal length is related to object and image distances through the applicable thin-lens equation. Real systems can require more precise optical definitions and reference conventions.

The same nominal focal-length label may not capture all wavelength-, focus-, configuration-, or measurement-dependent behavior of a real optical system.

## Units and Value Semantics

Focal-length values are normally expressed as a length with an appropriate unit. The numerical value alone is insufficient without the quantity identity and applicable reference conditions.

## Constraints / Assumptions

Do not assume that a nominal product focal-length label is an uncertainty-free metrological realization. Do not collapse effective focal length, equivalent focal length, back focal distance, flange focal distance, and other distinct optical distances into one concept without semantic analysis.

## Evidence / Trust / Validation

Focal Length is admitted to Quantity because its normative optical meaning is a measurable distance. Evidence from optical terminology and measurement standards supports the routing. Product specifications may provide observations or declared values but do not define GIOP identity.

## Relations

Potential relations include `has-value`, `has-unit`, and relations connecting an optical system to its focal-length characterization. Canonical relation identities are governed independently.

## Machine / AI Interpretation

`Focal Length` should resolve to `SEM-QUANTITY-FOCAL-LENGTH-001`. A value such as `50 mm` is a quantity value expression associated with this Quantity; it is not the Quantity itself.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`FOCAL LENGTH`, `FOCAL-LENGTH QUANTITY`, `OPTICAL FOCAL LENGTH`, `EFFECTIVE FOCAL LENGTH`, `EFL`, `FOCAL DISTANCE`, `LENS FOCAL LENGTH`
