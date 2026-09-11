# Illumination Condition

**Semantic ID:** `SEM-CONDITION-ILLUMINATION-001`  
**Preferred Name:** Illumination Condition  
**Semantic Class:** Optical Condition  
**Domain:** Optical Imaging  
**Status:** Provisional  
**Version:** 0.1.0

## 5W1H Orientation

### What

An Illumination Condition describes the optical radiation condition acting upon a specified receiving region, surface, object, or scene.

### Why

The presence of radiation somewhere in an environment does not mean that a particular surface, object, or region is illuminated. Illumination depends on source geometry, propagation, occlusion, direction, reflection, scattering, transmission, and the receiving context.

### Who

The concept is relevant to observers, photographers, cinematographers, lighting professionals, optical engineers, rendering engineers, imaging scientists, sensor specialists, virtual-production professionals, and machine-readable systems.

### Where

It applies to physical scenes, laboratory measurements, optical systems, rendering environments, displays, virtual production, simulation, and other imaging contexts.

### When

Illumination is always associated with a spatial and temporal context. The condition may change as sources, objects, observers, or environments move or as sources vary over time.

### How

An Illumination Condition is characterized by the relevant radiation reaching or acting upon the receiving region from one or more optical paths. Those paths may include direct and indirect contributions.

## Semantic Definition

**Illumination Condition** is an Optical Condition describing the relevant optical radiation acting upon a defined receiving region, surface, object, or scene.

Illumination may include direct, reflected, transmitted, scattered, or otherwise relevant radiation contributions.

## Core Distinctions

### Illumination vs Light Source

The Light Source is an entity. Illumination Condition describes the condition produced at a receiving region.

### Illumination vs Light Condition

Light Condition concerns the presence or availability of relevant radiation in a broader context. Illumination Condition concerns that radiation as it acts upon a receiver or region.

### Direct vs Indirect Illumination

Direct illumination results from a source reaching a receiver along a relevant direct path without an intervening occlusion of that direct source path.

Indirect illumination results from radiation reaching the receiver after one or more interactions or alternative optical paths, such as reflection or scattering.

Absence of direct illumination does not necessarily imply absence of all illumination.

### Illumination vs Exposure

Illumination is an optical condition. Exposure involves the temporal integration of radiation by a sensing or imaging system.

## Spatial and Directional Context

An Illumination Condition may vary across a single object or surface.

Two nearby regions may simultaneously experience different illumination conditions because of geometry, orientation, occlusion, source position, scattering, or reflected contributions.

## Cross-Domain Significance

Illumination Condition is a bridge between:

`Light Source → Radiation → Propagation → Interaction → Receiving Surface/Object → Observation/Capture`

It is relevant to physical imaging, cinematography, rendering, sensor exposure, display environments, computer vision, and virtual production.

## Trust

An illumination statement should avoid assuming that all illumination originates from a single direct source. When quantitative characterization is required, the relevant radiometric quantities and measurement conditions must be specified separately.

## Lifecycle

**Current state:** Provisional semantic entry.

## Retrieval Anchors

`ILLUMINATION CONDITION`, `ILLUMINATION`, `DIRECT ILLUMINATION`, `INDIRECT ILLUMINATION`, `LIGHT SOURCE`, `LIGHT CONDITION`, `RECEIVING REGION`, `SURFACE`, `OBJECT`, `SHADOW`
