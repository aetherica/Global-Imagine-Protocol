# Object

**GIOP Semantic Class ID:** `SEM-CLASS-OBJECT-001`

## Identity

**Preferred Name:** Object  
**Artifact Class:** Contextually Identifiable Entity  
**Artifact Type:** Object  
**Primary Domain:** Imaging and domain modeling  

## 5W1H Orientation

**What:** An object is an entity that is identifiable as a unit within a defined scene, domain, task, or observation context.

**Why:** Object semantics allow a system to refer to an identifiable entity independently of the representation used to depict, measure, or describe it.

**Who:** Objects may be identified by humans, scientific observers, machine-vision systems, computer-vision systems, databases, or other domain processes.

**Where:** Objects may occur in physical scenes, images, datasets, simulations, virtual environments, or other explicitly defined domains.

**When:** Object identity may be associated with a temporal scope because objects can persist, change, appear, disappear, or be reidentified over time.

**How:** An object is identified by criteria appropriate to its domain, context, and task. Those criteria must not be assumed to be universal.

## Semantic Definition

An **Object** is a contextually identifiable entity treated as a unit within a specified domain, scene, observation, measurement, or computational task.

GIOP deliberately does not use Object as a universal metaphysical ontology. Its identity is always interpreted relative to the semantic context in which the object is identified.

## Principal Types

Examples include:

- physical object;
- imaging target;
- manufactured object;
- biological object;
- astronomical object;
- machine-vision object;
- reconstructed object;
- virtual object;
- dataset object;
- domain-specific object.

These are contextual types, not a universal hierarchy.

## Distinctions

### Object vs Scene

A scene is a bounded contextual configuration. An object is an identifiable entity within or associated with that scene.

### Object vs Surface

An object may have one or more surfaces. A surface is a spatial boundary or interface associated with an object or material.

### Object vs Material

An object may be composed of one or more materials. Material identifies a substance or medium, not the object as a whole.

### Object vs Image Region

An image region is part of a representation. An object is the entity to which that region may refer, subject to the evidence and interpretation context.

## Identification Scope

Object identity may depend on:

- spatial continuity;
- physical continuity;
- semantic criteria;
- task definition;
- domain ontology;
- temporal persistence;
- observer interpretation;
- computational tracking or reconstruction.

The criteria should be explicit when ambiguity is material.

## Technical Characteristics

Relevant object characteristics may include:

- geometry;
- spatial location;
- orientation;
- dimensions;
- material composition;
- surface characteristics;
- motion;
- temporal persistence;
- appearance;
- semantic category;
- identity confidence;
- reconstruction state.

These belong to properties, quantities, states, identities, or other appropriate semantic layers.

## Trust and Validation

Object identification should distinguish:

- directly observed identity;
- measured identity;
- inferred identity;
- reconstructed identity;
- classified identity;
- tracked identity.

An object label assigned by a machine does not by itself prove the physical identity or nature of the corresponding entity.

## Lifecycle

`Emergence / Formation → Identification → Observation / Use → Change / Transformation → Reidentification / Tracking → Retirement / Disappearance`

## Relations

An object may:

- belong to a scene;
- consist of or contain materials;
- have surfaces;
- be illuminated;
- be observed;
- be captured by a camera;
- be measured;
- be represented in an image or other representation;
- participate in spatial and temporal relations.

## Machine and AI Interpretation

A machine should preserve the distinction between an object and its representation. Detection, segmentation, classification, tracking, or reconstruction may provide evidence about an object but does not automatically establish complete physical identity.

## Retrieval Anchors

Primary terms: `object`, `imaging object`, `target object`, `entity`.

Related terms: `physical object`, `scene object`, `machine-vision object`, `reconstructed object`, `virtual object`.

## Semantic Boundary

This class establishes **what an object is as a contextually identifiable entity**. It does not define universal ontology, object properties, material identity, surface identity, image regions, detection algorithms, or classification results.
