# Spatiotemporal Representation

- **ID:** `SEM-REPRESENTATION-SPATIOTEMPORAL-001`
- **TITLE:** Spatiotemporal Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form jointly encoding spatial structure and temporal extent, ordering, or change
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across spatial-temporal databases, computer vision, robotics, tracking, dynamic scene modeling, and geospatial information.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-TRAJECTORY-001`, `SEM-REPRESENTATION-SCENE-001`

## Semantic Definition

Spatiotemporal Representation is an information-bearing form in which spatial structure and temporal structure are jointly encoded so that location, geometry, topology, change, ordering, or evolution can be interpreted together.

It can encode trajectories, dynamic scenes, moving-object fields, time-indexed maps, event locations, or four-dimensional structures. Neither spatial nor temporal structure alone is sufficient for the defining responsibility.

## Core Distinctions

- **Spatiotemporal Representation ≠ Spatial Representation:** it requires meaningful temporal structure as well as spatial structure.
- **≠ Temporal Representation:** temporal structure alone is insufficient.
- **≠ Trajectory Representation:** a trajectory is one important specialized realization; spatiotemporal representation is broader.
- **≠ Scene Representation:** a scene representation may be static; dynamic scene content qualifies here when joint spatial-temporal organization is primary.
- **≠ Process:** a process is an organized temporal course, not its information-bearing representation.

## Boundary Cases

Time-indexed point clouds, dynamic occupancy fields, 4D scene structures, moving-object tracks, and event-location volumes qualify. A static 3D map with a timestamp is not automatically spatiotemporal.

## Trust / Validation

Validate coordinate reference, temporal reference, synchronization, interpolation, sampling, uncertainty, motion assumptions, provenance, and whether change is observed, inferred, simulated, or predicted.

## Lifecycle

Active canonical concept. Specialized dynamic-scene families require independent review.

## Relations / Retrieval Anchors

Use existing representation and relation authorities; no new relation is introduced.

Retrieval anchors: `SPATIOTEMPORAL REPRESENTATION`, `4D REPRESENTATION`, `SPACE-TIME REPRESENTATION`, `DYNAMIC SPATIAL REPRESENTATION`, `SPATIOTEMPORAL DATA REPRESENTATION`.
