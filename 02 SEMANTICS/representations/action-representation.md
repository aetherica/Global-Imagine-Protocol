# Action Representation

- **ID:** `SEM-REPRESENTATION-ACTION-001`
- **TITLE:** Action Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding an action, action structure, parameters, constraints, or executable action description
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across robotics action spaces, planning, control, VLA systems, and machine-action interface practice.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-ACTIVITY-GENERIC-001`, `SEM-REPRESENTATION-AFFORDANCE-001`

## Semantic Definition

Action Representation is an information-bearing form encoding an action, its structure, parameters, preconditions, effects, constraints, or executable description without being the occurrence of executing that action.

It may be symbolic, parametric, trajectory-based, tokenized, programmatic, learned, or multimodal. An action representation can describe a candidate, planned, demonstrated, or executable action.

## Core Distinctions

- **Action Representation ≠ Action Execution:** execution is an Activity/occurrence.
- **≠ Action:** the action is the represented activity/operation; the representation is its information-bearing form.
- **≠ Affordance Representation:** affordance encodes possibilities; action representation encodes a selected or specified action structure.
- **≠ Skill Representation:** a skill represents reusable competence/structure that may generate actions.
- **≠ Trajectory Representation:** a trajectory may realize an action temporally/spatially, but trajectory semantics are not identical to action semantics.
- **≠ Algorithm/Procedure:** an algorithm or procedure specifies a method; an action representation can be a parameterized action without prescribing a general method.

## Boundary Cases

A robot action token, structured action command, parameterized manipulation action, or planned action schema qualifies. A policy model is not automatically Action Representation. A motion trace qualifies only when action semantics, rather than physical trajectory alone, are primary.

## Trust / Validation

Record action identity, actor scope, parameters, preconditions/effects, constraints, temporal/spatial assumptions, provenance, uncertainty, validation status, and execution relationship.

## Lifecycle

Active canonical concept. Specific action-space encodings require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `participates-in`, `derived-from`, and `part-of`; no new relation authority.

Retrieval anchors: `ACTION REPRESENTATION`, `ACTION SPACE REPRESENTATION`, `ACTION SCHEMA`, `PARAMETRIC ACTION`, `ROBOT ACTION REPRESENTATION`, `EXECUTABLE ACTION DESCRIPTION`.
