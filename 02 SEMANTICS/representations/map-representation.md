# Map Representation

- **ID:** `SEM-REPRESENTATION-MAP-001`
- **TITLE:** Map Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding spatial organization, landmarks, geometry, topology, or semantic environment structure for mapping or navigation
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across robotic mapping, metric/topological maps, occupancy mapping, geospatial information, and IEEE robot-map representation practice.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-SCENE-001`, `SEM-REPRESENTATION-SPATIOTEMPORAL-001`

## Semantic Definition

Map Representation is an information-bearing form encoding spatial organization of an environment through geometry, coordinates, occupancy, landmarks, topology, semantics, or related spatial structure for mapping, localization, navigation, or environmental reasoning.

It may be metric, topological, semantic, hybrid, grid-based, graph-based, point-based, mesh-based, or learned.

## Core Distinctions

- **Map Representation ≠ Map as environment model:** the map is the represented spatial information; representation is its information-bearing form.
- **≠ Scene Representation:** scene representation is broader for scene understanding; map representation is specifically oriented to spatial organization for mapping/navigation.
- **≠ World Representation:** world representation may include dynamics, agents, beliefs, and non-map information.
- **≠ Spatial Quantity/Coordinate:** coordinates and measurements can populate a map but are not the map representation itself.
- **≠ Mapping Activity:** mapping is a process/activity that constructs or updates a representation.

## Boundary Cases

Occupancy grids, topological graphs, metric maps, semantic maps, landmark maps, and hybrid robot maps qualify. A raw point cloud is not automatically a map unless it is organized/used as an environmental map.

## Trust / Validation

Record coordinate reference, map extent, resolution, topology assumptions, update time, localization frame, sensor provenance, uncertainty, dynamic-object treatment, and validation coverage.

## Lifecycle

Active canonical concept. Specific map realization families require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in`.

Retrieval anchors: `MAP REPRESENTATION`, `ROBOT MAP`, `METRIC MAP REPRESENTATION`, `TOPOLOGICAL MAP REPRESENTATION`, `SEMANTIC MAP`, `OCCUPANCY MAP REPRESENTATION`.
