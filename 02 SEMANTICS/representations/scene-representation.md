# Scene Representation

- **ID:** `SEM-REPRESENTATION-SCENE-001`
- **TITLE:** Scene Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding the entities, structure, geometry, semantics, or relationships of a scene
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across computer vision, robotics mapping, 3D reconstruction, scene graphs, neural rendering, and spatial AI.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-OBJECT-CENTRIC-001`, `SEM-REPRESENTATION-MAP-001`, `SEM-REPRESENTATION-NEURAL-FIELD-001`

## Semantic Definition

Scene Representation is an information-bearing form encoding selected entities, geometry, spatial organization, appearance, semantics, topology, relations, or other structured information about a scene for interpretation, reconstruction, navigation, interaction, or analysis.

It may be metric, topological, semantic, object-centric, graph-based, volumetric, neural, or multimodal. No single realization defines the concept.

## Core Distinctions

- **Scene Representation ≠ Scene:** the scene is the represented environment/configuration; the representation is its information-bearing form.
- **≠ Object-Centric Representation:** object-centric organization may be a scene representation, but scene responsibility can include geometry, spatial context, and non-object structure.
- **≠ Map Representation:** a map is oriented toward spatial organization for mapping/navigation; scene representation is broader for scene understanding/reconstruction.
- **≠ Neural Field Representation:** neural fields are one realization family, not the whole scene concept.
- **≠ Perception:** perception may produce scene information; the representation is not the perceptual phenomenon.

## Boundary Cases

Point clouds, voxel maps, meshes, SDFs, scene graphs, NeRF/3DGS scene structures, and multimodal scene descriptions qualify when scene organization is primary. A single object representation without scene context is not automatically Scene Representation.

## Trust / Validation

Record coordinate frame, scene extent, temporal scope, resolution, object/entity assumptions, geometry/appearance provenance, uncertainty, reconstruction method, and validation coverage.

## Lifecycle

Active canonical concept. Specific scene-realization families require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `part-of`, `derived-from`, and relation authorities.

Retrieval anchors: `SCENE REPRESENTATION`, `3D SCENE REPRESENTATION`, `SCENE GRAPH REPRESENTATION`, `SPATIAL SCENE REPRESENTATION`, `NEURAL SCENE REPRESENTATION`.
