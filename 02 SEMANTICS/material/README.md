# Material — Domain Coordination

**Status:** IMPLEMENTATION-COMPLETE — CLASS-ROUTED DOMAIN COORDINATION
**Folder:** `02 SEMANTICS/material/`
**Canonical semantic owner:** `SEM-CLASS-MATERIAL-001` in `02 SEMANTICS/classes/material.md`
**Purpose:** Provide domain-level analysis, boundary, routing, registry, index, and closure governance for material semantics without creating a duplicate Material semantic layer.
**Authoring standard:** `02 SEMANTICS/DOMAIN-AUTHORING-STANDARD.md`

## Identity / Metadata

This folder does not introduce a second canonical `Material` concept. The canonical responsibility for Material remains the Class layer. This folder documents how material-related knowledge is interpreted, routed, retrieved, and validated against that existing authority.

The stable semantic anchor is therefore `SEM-CLASS-MATERIAL-001`, not a new `SEM-MATERIAL-*` layer identifier.

## 5W1H Orientation

### What
Material denotes a physical substance or medium considered as an entity for composition, structure, manufacture, use, or domain-relevant behaviour. In GIOP, this identity is already owned by the canonical Material Class. The folder therefore coordinates material-domain knowledge rather than redefining the concept.

### Why
Material semantics are frequently confused with material properties, quantities, measurement results, objects, surfaces, textile-specific entities, and representations of materials. A dedicated coordination layer is useful for preventing those collisions while preserving the existing Class authority.

### Who
Material semantics are consumed by material scientists, optical and imaging engineers, manufacturers, metrologists, researchers, archivists, dataset curators, software systems, and machine-learning systems. These visitors enter the same canonical Material concept at different depths; the folder does not create visitor-specific identities.

### Where
The semantic scope includes natural and manufactured matter, material portions in objects, optical and imaging media, coatings, composites, polymers, metals, ceramics, biological materials, and textile materials where the primary responsibility is generic Material. More specific domain ownership remains with Textile, Garment, Property, Quantity, Activity, Process, Representation, State, Condition, or other established layers as appropriate.

### When
Material identity may persist through use while its state, condition, measured properties, composition, or processing history changes. Lifecycle questions such as formation, processing, manufacture, aging, recycling, and disposal are contextual and must not be collapsed into the Material identity itself.

### How
Material identity is established from the relevant evidence about composition, structure, form, provenance, specifications, or characterization. Measurement establishes results and quantities; processes establish transformations or operations; representation records or depicts information about a material. None of these replaces the Material concept.

## Semantic Definition

The GIOP canonical Material definition is the existing Class definition: a physical substance or medium recognized as an entity for purposes of composition, structure, manufacture, use, or domain-relevant behaviour. The material coordination folder inherits that responsibility and adds no alternate genus, taxonomy, or ontology.

## Scope and Boundary

This folder governs material-related semantic routing. It does not own:

- material properties as Property semantics;
- numerical material characteristics as Quantity or Quantity Value;
- measurement acts or results as Activity and Result;
- generic objects or components as Object/Class semantics;
- surfaces or interfaces as Surface/Class semantics;
- textile fibre, yarn, fabric, textile structure, or textile finish as Textile domain semantics;
- garments as Garment semantics;
- material representations, files, scans, meshes, diagrams, or encodings as Representation semantics;
- process operations such as curing, coating, mixing, welding, weaving, printing, or recycling as Activity/Process/Workflow semantics;
- temporary material modes or configurations as State/Condition semantics;
- provenance or authenticity as Foundation-level responsibility.

## Core Distinctions

Material ≠ Material Property.

Material ≠ Quantity Value.

Material ≠ Measurement Result.

Material ≠ Object.

Material ≠ Surface.

Material ≠ Textile.

Material ≠ Garment.

Material ≠ Representation.

Material ≠ Process.

Material ≠ State.

Material ≠ Condition.

Material ≠ Provenance.

## Cross-Domain Significance

Material is a shared physical concept across imaging, optics, manufacturing, textiles, biology, sensing, and measurement. The correct GIOP treatment is therefore broad enough to support cross-domain reuse, but constrained enough to avoid importing a full chemistry, materials-science, manufacturing, or product ontology into the Class layer.

## Trust and Evidence

Material claims may be supported by composition records, supplier or manufacturer specifications, laboratory characterization, analytical methods, standardized tests, reference materials, traceable measurements, or curated domain records. Appearance alone is insufficient to establish material composition when the claim is substantive or high-risk.

Evidence is not the material itself; provenance is not the material itself; a measurement result is not the material itself; and an inference from an image is not equivalent to direct material identification.

## Visitor Universe

Visitor Universe is folder-level routing only. General visitors require an intuitive physical-matter orientation; students and educators need conceptual distinctions; imaging and optics professionals need structure-property and interaction context; metrology and research visitors need characterization and evidence boundaries; AI/ML consumers need the distinction between inferred material labels and validated material identity; machine/API consumers need stable retrieval through `SEM-CLASS-MATERIAL-001`.

No visitor category receives an alternate material identity.

## Lifecycle

Material-related lifecycle information may include source or formation, processing, manufacture, finishing, use, aging, environmental alteration, recycling, reuse, and disposal. These are lifecycle contexts around the material and should route to Activity/Process/State/Condition where the semantics require those layers.

## Retrieval Anchors

Primary: `material`, `material`, `physical substance`, `medium`, `material class`.

Domain anchors: `optical material`, `engineering material`, `composite`, `polymer`, `metal`, `ceramic`, `coating`, `semiconductor`, `textile material`, `biological material`.

Governance anchor: `SEM-CLASS-MATERIAL-001`.

## Governance Decision

No new Material semantic ID is promoted by this folder. Material remains a canonical Class responsibility and this folder is closed as a coordination/routing artifact.
