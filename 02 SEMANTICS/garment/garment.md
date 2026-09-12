# Garment

**Semantic ID:** `SEM-GARMENT-GENERIC-001`  
**Preferred Name:** Garment  
**Semantic Class:** Garment Domain Concept  
**Domain:** Garment  
**Status:** CANONICAL CANDIDATE — V3.1 SEED  
**Version:** 0.2.0

## 5W1H Orientation

### What
A Garment is an assembled wearable article designed to cover, support, protect, decorate, or otherwise interface with part or all of a body.

### Why
A distinct garment concept is required to separate an assembled wearable article from textile constituents, generic materials, body anatomy, measurements, and the representations used to describe or reconstruct it.

### Who
The concept applies to apparel designers, garment technologists, anthropometric and sizing specialists, manufacturers, costume and performance practitioners, imaging/vision systems, e-commerce systems, virtual-production systems, and machine-readable clothing datasets.

### Where
It applies to physical garments, product records, technical specifications, photographs, video, 3D clothing models, reconstructed scenes, virtual garments, and other declared representations.

### When
Garment identity, configuration, size, fit, and state may change through alteration, assembly, wear, damage, laundering, folding, donning, doffing, or reconstruction. Such changes must not automatically be treated as a change of article identity.

### How
A garment is characterized through its article identity, components, construction, intended use, sizing context, fit, closures, constituent materials, state, and representations.

## Semantic Definition

**Garment** is an assembled wearable article intended to interact with and cover, support, protect, or otherwise interface with a body or body region under a declared use context.

## Scope / Boundary

Garment owns the semantic identity of the assembled wearable article and its domain-specific component, construction, sizing, fit, and fastening concepts.

It does not replace:

- Textile for fibre, yarn, fabric, and textile-structure semantics;
- Material for generic material semantics;
- Class for generic entity classification;
- Quantity or Measurement for anthropometric and dimensional quantities;
- Representation for patterns, drawings, meshes, images, and other representations;
- State for worn, folded, damaged, wet, or other state conditions;
- Activity/Process for cutting, sewing, manufacturing, laundering, alteration, wearing, and related operations;
- BIL for integrity evaluation against a declared reference.

## Core Distinctions

### Garment vs Textile
A garment is an assembled wearable article; textile concerns textile materials, structures, and articles that may constitute the garment.

### Garment vs Garment Component
A garment is the assembled article; a component is a constituent part participating in its construction.

### Garment vs Garment Representation
The garment is the referent. A photograph, drawing, pattern, mesh, scan, or record is a representation of it.

### Garment Size vs Garment Measurement
A size designation classifies or communicates an intended sizing position; a garment measurement is a dimensional observation or specification. They are not interchangeable.

### Size vs Fit
Size is a designation or classification within a sizing system. Fit concerns the relationship between the garment and the intended body under a declared context.

## Cross-Domain Significance

`Body / Anthropometry → Garment → Textile / Material → Construction → Size / Fit → Representation → Observation / Measurement → BIL Integrity Evaluation`

Garment therefore acts as a domain bridge without taking ownership of the underlying generic semantic layers.

## Trust / Evidence

Garment assertions should declare the article scope, representation modality, sizing context, measurement basis, and relevant state when these materially affect interpretation. Automated visual inference should distinguish observed evidence from inferred construction, size, fit, or material.

## Visitor Universe

**Novice:** garment versus textile, component, size, and representation.  
**Intermediate:** construction, sizing, fit, fastening, state, and material relationships.  
**Expert:** article identity persistence, measurement/sizing distinction, representation uncertainty, reconstruction, and cross-layer validation.  
**Machine:** stable semantic ID, typed attributes, relations, evidence references, and explicit uncertainty.

## Lifecycle

Candidate seed → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`GARMENT`, `CLOTHING`, `APPAREL`, `WEARABLE ARTICLE`, `CLOTHING ARTICLE`, `GARMENT IDENTITY`, `GARMENT CONSTRUCTION`, `GARMENT FIT`
