# World Representation

- **ID:** `SEM-REPRESENTATION-WORLD-001`
- **TITLE:** World Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding a broader environment or world state, structure, entities, dynamics, or task-relevant context
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across world-state representations, embodied AI, robotics world models, environment modeling, and spatial-temporal representation.
- **VALIDATION:** Independent Model/World-Model boundary review passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-SCENE-001`, `SEM-REPRESENTATION-PREDICTIVE-001`, `SEM-STATE-GENERIC-001`

## Semantic Definition

World Representation is an information-bearing form encoding a broader environment or world state, structure, entities, relationships, dynamics, or task-relevant context at a defined scope.

It can be static or dynamic, symbolic or learned, local or global, and may support prediction or action without itself being a world model.

## Core Distinctions

- **World Representation ≠ World Model:** a world model is a model with explanatory/predictive behavior; a world representation is the information-bearing world description/state form.
- **≠ Scene Representation:** scene is generally a scoped spatial situation; world representation can span broader environments, latent state, dynamics, or task context.
- **≠ Predictive Representation:** predictive organization is optional; world representation need not be optimized for prediction.
- **≠ World State:** world state is the represented state; representation expresses it.
- **≠ Map Representation:** a map is a spatial organization for mapping/navigation; world representation can include dynamics, agents, state, and non-map information.

## Boundary Cases

A structured latent environment state, multimodal world state, or environment representation used by a robot qualifies. A predictive simulator qualifies as a model/system, while its internal world-state representation may qualify separately.

## Trust / Validation

Record world scope, state variables, temporal extent, observability, uncertainty, model dependence, provenance, update mechanism, and whether information is observed, inferred, simulated, or predicted.

## Lifecycle

Active canonical concept. World-model-specific representations remain independently reviewable.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in`.

Retrieval anchors: `WORLD REPRESENTATION`, `WORLD STATE REPRESENTATION`, `ENVIRONMENT REPRESENTATION`, `EMBODIED WORLD REPRESENTATION`, `WORLD-STATE FORM`.
