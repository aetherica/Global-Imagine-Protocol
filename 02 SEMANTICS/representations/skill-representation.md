# Skill Representation

- **ID:** `SEM-REPRESENTATION-SKILL-001`
- **TITLE:** Skill Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form expressing reusable action competence, skill structure, parameters, constraints, or execution-relevant organization
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across robotics skill learning, hierarchical control, imitation learning, motor skill representations, and action semantics.
- **VALIDATION:** Independent Action/Model boundary review passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-ACTION-001`, `SEM-MODEL-GENERIC-001`

## Semantic Definition

Skill Representation is an information-bearing form expressing reusable action competence or skill structure, including action sequences, parameters, preconditions, temporal organization, constraints, affordance dependencies, or execution-relevant knowledge.

It represents a reusable competence description; it is not itself the competence, an action occurrence, or necessarily a model.

## Core Distinctions

- **Skill Representation ≠ Skill/Capability:** competence or capability is distinct from its information-bearing form.
- **≠ Action Representation:** an action represents a particular action structure; a skill can organize reusable families of actions or execution competence.
- **≠ Model:** a skill model may generate or refine a skill representation but is not identical to it.
- **≠ Procedure:** a procedure prescribes a method; a skill representation may encode learned or adaptable competence without a fixed procedure.
- **≠ Policy:** a policy maps conditions to actions; a skill representation can be the reusable information used by a policy.

## Boundary Cases

A parameterized manipulation skill, learned motor primitive description, or hierarchical skill schema qualifies. A raw action trajectory qualifies only if reusable skill semantics are explicitly primary.

## Trust / Validation

Record actor scope, task scope, skill identity, parameters, preconditions, adaptation range, demonstrations/training provenance, safety constraints, uncertainty, and execution validation.

## Lifecycle

Active canonical concept. Specific skill-learning and hierarchical-skill families require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `participates-in`, and `part-of`.

Retrieval anchors: `SKILL REPRESENTATION`, `ROBOT SKILL REPRESENTATION`, `MOTOR SKILL REPRESENTATION`, `SKILL SCHEMA`, `LEARNED SKILL FORM`.
