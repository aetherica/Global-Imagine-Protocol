# Affordance Representation

- **ID:** `SEM-REPRESENTATION-AFFORDANCE-001`
- **TITLE:** Affordance Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form expressing action possibilities or agent-environment opportunities
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across ecological affordance theory, robotics manipulation, embodied AI, and action-conditioned representation research.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-ACTION-001`, `SEM-REPRESENTATION-OBJECT-CENTRIC-001`

## Semantic Definition

Affordance Representation is an information-bearing form expressing action possibilities, opportunities, or interaction possibilities available to a specified agent or agent class in relation to an environment, object, state, or task context.

An affordance representation may encode possible actions, enabling conditions, relevant regions, grasp or contact locations, feasibility, costs, uncertainty, or agent-specific applicability. The represented possibility is distinct from the physical opportunity, the action itself, and the procedure used to execute it.

## Core Distinctions

- **Affordance Representation ≠ Affordance:** the affordance is the action possibility/opportunity; the representation expresses information about it.
- **≠ Action Representation:** action representation encodes an action or action structure; affordance representation encodes what actions are possible or enabled.
- **≠ Object-Centric Representation:** object-centric organization may carry affordances but does not make action possibility primary.
- **≠ Capability:** capability concerns agent competence or ability; affordance concerns opportunity in an agent-environment relation.
- **≠ Perception:** perception may establish affordance information but is not the representation.
- **≠ Model:** a model may predict affordances; the predicted information can be represented independently.

## Boundary Cases

A graspable region map, tool-use opportunity tuple, or agent-specific action-opportunity field qualifies when affordance semantics are primary. A generic object segmentation does not qualify merely because it enables affordance inference. A policy is not an affordance representation merely because it selects actions.

## Trust / Validation

Record agent scope, environmental scope, task assumptions, action semantics, enabling conditions, feasibility basis, observation/provenance, uncertainty, and whether affordances are observed, inferred, learned, simulated, or hypothesized.

## Lifecycle

Active canonical concept. Domain-specific affordance families require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `participates-in`, and `part-of` where justified. No new relation authority is created.

Retrieval anchors: `AFFORDANCE REPRESENTATION`, `ACTION POSSIBILITY REPRESENTATION`, `AFFORDANCE MAP`, `INTERACTION OPPORTUNITY REPRESENTATION`, `BEHAVIOUR-GROUNDED REPRESENTATION`.
