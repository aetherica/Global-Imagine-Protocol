# Textile

**Semantic ID:** `SEM-TEXTILE-GENERIC-001`  
**Preferred Name:** Textile  
**Semantic Class:** Textile Domain Concept  
**Domain:** Textile  
**Status:** CANONICAL CANDIDATE — V3.1 SEED  
**Version:** 0.2.0

## 5W1H Orientation

### What
Textile is a domain concept covering textile fibres, filaments, yarns, fabrics, textile structures, finishes, and related flexible textile materials or articles.

### Why
Textile semantics are needed to organize a specialized material/article domain without replacing the generic Material, Property, Quantity, Process, Activity, or Representation layers.

### Who
The concept is relevant to textile scientists, fibre and yarn specialists, manufacturers, garment technologists, designers, conservation specialists, imaging systems, e-commerce systems, quality-control systems, and machine-readable datasets.

### Where
It applies to fibres, filaments, yarns, woven/knitted/nonwoven and related fabrics, finished textile articles, technical textiles, garments containing textile constituents, and digital representations of these objects.

### When
Textile identity and observable configuration may change through production, finishing, laundering, wear, damage, ageing, repair, or transformation. Such changes must be interpreted in their declared context.

### How
Textiles are characterized through constituent fibres/filaments, yarn structure, fabric construction, composition, surface/finish, intended use, state, and measured or observed properties.

## Semantic Definition

**Textile** is a domain-qualified material, structure, or article concept whose relevant constitution or construction involves textile fibres, filaments, yarns, fabrics, or related textile structures.

## Scope / Boundary

Textile owns textile-domain concepts from constituent fibre/filament through yarn, fabric, textile structure, finish, and article-level textile identification.

It does not replace:

- Material for generic material semantics;
- Property for generic characteristics;
- Quantity/Measurement for test values and dimensional quantities;
- Process/Activity for spinning, weaving, knitting, bonding, finishing, laundering, and other operations;
- Representation for textile images, diagrams, scans, meshes, labels, and records;
- Garment for assembled wearable articles;
- BIL for integrity assessment of textile or garment-related configuration.

## Core Distinctions

### Fibre / Filament vs Yarn
A fibre or filament is a constituent textile element; yarn is an assembled or continuous strand structure formed from fibres, filaments, or other defined constituents.

### Yarn vs Fabric
Yarn is a strand-level textile structure/material; fabric is a higher-order textile structure produced through mechanisms such as interlacing, interlooping, bonding, felting, or related construction.

### Fabric vs Garment
Fabric is a textile structure or article/component; a garment is an assembled wearable article that may contain one or more fabrics.

### Textile vs Material
Textile is a domain-qualified concept; generic Material remains responsible for material semantics applicable across domains.

### Textile Structure vs Textile Finish
Structure concerns constituent organization and construction. Finish concerns a treatment or resulting surface/article condition applied after or during formation.

## Cross-Domain Significance

`Material → Textile Fibre / Filament → Yarn → Fabric → Textile Structure / Finish → Garment / Technical Article → Observation / Measurement → Representation → BIL`

The chain permits textile-domain specificity while retaining generic GIOP ownership of foundational semantics.

## Trust / Evidence

Textile assertions should distinguish material composition, observed structure, measured properties, inferred construction, and manufacturing history. Fibre/yarn terminology should follow the applicable vocabulary and declared classification system. Quantitative claims should identify measurement context and method rather than embedding test methodology in the textile concept itself.

## Visitor Universe

**Novice:** textile versus fibre, yarn, fabric, and garment.  
**Intermediate:** construction, structure, finish, composition, and textile article distinctions.  
**Expert:** morphology, construction mechanisms, material qualification, measurement context, degradation, conservation, and cross-representation consistency.  
**Machine:** stable IDs, typed constituent/construction references, measurements, evidence, provenance, and uncertainty.

## Lifecycle

Candidate seed → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`TEXTILE`, `TEXTILE MATERIAL`, `TEXTILE ARTICLE`, `TEXTILE FIBRE`, `FILAMENT`, `YARN`, `FABRIC`, `WOVEN`, `KNIT`, `NONWOVEN`, `TEXTILE STRUCTURE`, `TEXTILE FINISH`
