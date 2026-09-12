# Causal Representation

- **ID:** `SEM-REPRESENTATION-CAUSAL-001`
- **TITLE:** Causal Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding causal variables, dependencies, mechanisms, interventions, or causal structure
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across causal graphs, structural causal models, causal discovery, and causal representation learning.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-RELATION-CENTRIC-001`, `SEM-MODEL-GENERIC-001`

## Semantic Definition

Causal Representation is an information-bearing form encoding causal variables, dependencies, mechanisms, intervention structure, or other explicitly causal organization among represented elements.

It may be graphical, structural-equation based, symbolic, tabular, tensorial, or learned. Causal semantics require more than generic statistical association.

## Core Distinctions

- **Causal Representation ≠ Causal Model:** a model specifies explanatory or generative causal structure; a representation expresses causal information and may encode a model without being the model.
- **≠ Relation-Centric Representation:** relation organization is broader; causal representation requires causal responsibility.
- **≠ Correlation/association representation:** statistical dependence alone does not establish causal semantics.
- **≠ Event Representation:** events can be causal variables or evidence but are not inherently causal representations.
- **≠ Causal inference process:** estimation/discovery is an activity or process, not the representation.

## Boundary Cases

A directed acyclic graph explicitly interpreted causally, structural causal model encoding, intervention graph, or learned latent representation with documented causal semantics qualifies. A generic knowledge graph does not become causal merely because some edges are interpreted informally as causes.

## Trust / Validation

Record causal interpretation, variable semantics, assumptions, directionality, interventions, confounder treatment, identifiability, evidence, provenance, uncertainty, and scope of causal claims.

## Lifecycle

Active canonical concept. Specific causal model families remain independently governable.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, and relation authorities; no causal relation authority is created by this entry.

Retrieval anchors: `CAUSAL REPRESENTATION`, `CAUSAL GRAPH REPRESENTATION`, `CAUSAL STRUCTURE`, `STRUCTURAL CAUSAL REPRESENTATION`, `CAUSAL LATENT REPRESENTATION`.
