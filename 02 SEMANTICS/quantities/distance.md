# Distance

**Semantic ID:** `SEM-QUANTITY-DISTANCE-001`  
**Preferred Name:** Distance  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Quantity  
**Domain:** Geometry / Imaging / Measurement  
**Status:** Provisional  
**Version:** 0.1.0  
**Related IDs:** `SEM-RELATION-VIEWING-DISTANCE-001`

> Distance is a measurable spatial quantity expressing the separation associated with two defined references under a specified geometric context.

## What

Distance expresses spatial separation between defined points, locations, surfaces, objects, or other geometric references.

## Why

A numerical distance has meaning only with identified endpoints or references and a defined spatial context. In viewing contexts, the distance quantity provides the value associated with the Viewing Distance relation.

## Structure

A distance statement should identify its references, geometric interpretation, coordinate or measurement frame where relevant, numerical value, and unit.

## How

Distance may be calculated or measured from defined spatial references. The method and uncertainty depend on the geometry, instrument, coordinate reference, and intended use.

## Core Distinctions

### Distance vs Viewing Distance

Distance is a quantity. Viewing Distance is a semantic relation linking a viewing reference to a viewed target and may carry a distance quantity value.

### Distance vs Focal Length

Focal length is an optical-system parameter. Distance is a spatial quantity.

### Distance vs Field of View

Field of view is an angular/geometric characteristic. Distance is spatial separation.

## Units and Constraints

Distance values require an identified unit or compatible reference system. The unit must be dimensionally appropriate to spatial length.

## Relations

Potential canonical relations include `has-value`, `has-unit`, `measures-separation`, and `associated-with-viewing-distance`.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`DISTANCE`, `DISTANCE QUANTITY`, `SPATIAL DISTANCE`, `VIEWING DISTANCE`, `LENGTH`, `SEPARATION`, `FOCAL LENGTH`
