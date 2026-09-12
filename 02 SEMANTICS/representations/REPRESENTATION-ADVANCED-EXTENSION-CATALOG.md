# Representation Advanced Extension Catalog

**Status:** Active Controlled Extension Dataset  
**Version:** 1.0.0  
**Scope:** AI, robotics, computational, spatial, temporal, agent/action, and advanced information-bearing representation forms.

## Purpose

This catalog records representation concepts identified as materially missing from the generic Representation batch when compared with current AI, robotics, computer-vision, world-model, programming-language, and data-system usage.

It is a controlled semantic intake layer. Presence here does not by itself confer canonical status. Each concept requires independent responsibility, evidence, boundary, relation, lifecycle, and cross-layer validation before promotion.

## Multidimensional Organization

The candidate universe is intentionally not modeled as a single inheritance tree. The following dimensions may intersect:

- Referent: object, state, relation, event, action, scene, world, program, capability, belief, resource;
- Abstraction: concrete, symbolic, structural, latent, predictive, causal;
- Structure: object-centric, graph/relational, field, tensor, sequence, trajectory;
- Temporal scope: static, event, trajectory, spatiotemporal;
- Agent coupling: passive description, belief, affordance, action, skill, interaction;
- Computational realization: symbolic, differentiable, neural, serialized, intermediate.

## First Extension Batch

| ID | Preferred Name | Primary Responsibility | Initial Decision |
|---|---|---|---|
| `SEM-REPRESENTATION-BELIEF-001` | Belief Representation | Information-bearing form expressing an agent's uncertain or probabilistic state of belief | Candidate — high priority |
| `SEM-REPRESENTATION-OBJECT-CENTRIC-001` | Object-Centric Representation | Representation organized around distinct entities/objects and their attributes or states | Candidate — high priority |
| `SEM-REPRESENTATION-RELATION-CENTRIC-001` | Relation-Centric Representation | Representation organized around typed relations among entities or semantic elements | Candidate — high priority |
| `SEM-REPRESENTATION-AFFORDANCE-001` | Affordance Representation | Representation expressing action possibilities or agent-environment opportunities | Candidate — high priority |
| `SEM-REPRESENTATION-ACTION-001` | Action Representation | Information-bearing form encoding an action, action structure, parameters, or executable action description | Candidate — high priority |
| `SEM-REPRESENTATION-EVENT-001` | Event Representation | Information-bearing form encoding event identity, occurrence structure, or event attributes | Candidate — high priority |
| `SEM-REPRESENTATION-SPATIOTEMPORAL-001` | Spatiotemporal Representation | Representation jointly encoding spatial and temporal structure or change | Candidate — high priority |
| `SEM-REPRESENTATION-CAUSAL-001` | Causal Representation | Representation encoding causal variables, dependencies, mechanisms, or causal structure | Candidate — high priority |
| `SEM-REPRESENTATION-PREDICTIVE-001` | Predictive Representation | Representation structured to encode information useful for predicting future states, observations, or outcomes | Candidate — high priority |
| `SEM-REPRESENTATION-NEURAL-FIELD-001` | Neural Field Representation | Continuous or field-based learned representation mapping coordinates/inputs to represented scene, signal, or state information | Candidate — high priority |
| `SEM-REPRESENTATION-PROGRAM-001` | Program Representation | Information-bearing form expressing computational instructions or program structure | Candidate — high priority |
| `SEM-REPRESENTATION-INTERMEDIATE-001` | Intermediate Representation | Compiler/system representation used between source-level and lower-level computational forms | Candidate — high priority |
| `SEM-REPRESENTATION-DIGITAL-TWIN-001` | Digital-Twin Representation | Representation of a physical or operational counterpart within a digital-twin system | Candidate — requires system-boundary review |
| `SEM-REPRESENTATION-SKILL-001` | Skill Representation | Information-bearing form expressing reusable action competence, skill structure, or skill parameters | Candidate — requires Action/Model boundary review |
| `SEM-REPRESENTATION-TRAJECTORY-001` | Trajectory Representation | Representation encoding ordered temporal/spatial evolution of an entity, state, or motion | Candidate — high priority |
| `SEM-REPRESENTATION-SCENE-001` | Scene Representation | Representation encoding entities, structure, geometry, semantics, or relationships of a scene | Candidate — high priority |
| `SEM-REPRESENTATION-WORLD-001` | World Representation | Representation encoding a broader environment/world state, structure, or dynamics | Candidate — requires Model/World-Model boundary review |
| `SEM-REPRESENTATION-MAP-001` | Map Representation | Representation encoding spatial organization, landmarks, geometry, topology, or semantic environment structure for mapping/navigation | Candidate — high priority |

## Deliberately Not Promoted by This Dataset

The following remain routed or dimensional rather than automatically canonical Representation concepts:

- Digital Representation
- Physical Representation
- Visual Representation
- Textual Representation
- Audio Representation
- Video Representation
- Structured Representation
- Unstructured Representation
- Multimodal Representation
- Machine-Readable / Machine-Interpretable / Machine-Actionable / Machine-Executable
- Representation Granularity
- Representation Abstraction
- Representation Quality
- Representation Learning
- Feature Representation
- Embedding Representation
- Latent Representation
- Tensor Representation
- Neural Representation

These terms can be useful classifications, realizations, properties, processes, or implementation families depending on context. They require responsibility-based routing before promotion.

## Cross-Layer Exclusions

- State is represented by State Representation; State itself remains in `states`.
- Observation remains in observation/activity semantics; its representation is separate.
- Action execution is an Activity; Action Representation is the information-bearing form.
- Process and Activity remain temporal occurrences/courses; process diagrams and workflow artifacts are Representations.
- Model remains a formal explanatory/predictive construct; a Model Representation is not automatically a Model.
- Dataset, File, and Bitstream remain distinct from the Representation that may embody or communicate them.
- Perception remains the perceptual phenomenon/outcome; a perceptual representation is not itself Perception.

## Promotion Rule

No entry in this catalog becomes Active canonical merely because the term is common in research or implementation practice. Promotion requires:

`IDENTITY → PRIMARY RESPONSIBILITY → EXISTING-ENTRY CHECK → BOUNDARY → EVIDENCE → RELATION AUTHORITY → CROSS-LAYER VALIDATION → LIFECYCLE → RETRIEVAL`

## Retrieval Anchors

Representation, Belief Representation, Object-Centric Representation, Relation-Centric Representation, Affordance Representation, Action Representation, Event Representation, Spatiotemporal Representation, Causal Representation, Predictive Representation, Neural Field Representation, Program Representation, Intermediate Representation, Digital-Twin Representation, Skill Representation, Trajectory Representation, Scene Representation, World Representation, Map Representation.
