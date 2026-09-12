# Relation-Centric Representation

- **ID:** `SEM-REPRESENTATION-RELATION-CENTRIC-001`
- **TITLE:** Relation-Centric Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form organized primarily around typed relations among entities, concepts, or semantic elements
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across graph representation, knowledge representation, scene graphs, relational learning, and GIOP relation semantics.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-OBJECT-CENTRIC-001`, `SEM-RELATION-GENERIC-001`

## 5W1H Orientation

**What:** A representation whose primary organizing unit is a typed connection among represented entities or semantic elements.

**Why:** To preserve and communicate relational structure such as connectivity, dependency, association, topology, interaction, or semantic linkage.

**Where:** Knowledge graphs, scene graphs, relational databases/structures, robotics, social or interaction models, semantic systems, and graph-based learning.

**When:** Whenever relation structure is primary rather than merely incidental metadata.

**Who:** Any system, agent, dataset, model, or information process that constructs or consumes relational information.

**How:** Through graph, edge-centric, relation tables, triples/quads, typed links, relational tensors, or learned relational structures.

## Semantic Definition

Relation-Centric Representation is an information-bearing form organized primarily around typed relations among entities, concepts, states, events, or other semantic elements, optionally including the participating elements and relation qualifications.

It may be symbolic, tabular, graph-based, tensor-based, or learned. Realization does not determine identity; relational organization and responsibility do.

## Core Distinctions

- **Relation-Centric Representation ≠ Relation:** a Relation is the reusable semantic connection concept; the representation is a form that expresses instances or structure of such connections.
- **≠ Object-Centric Representation:** object units are primary in object-centric organization; relations are primary here.
- **≠ Scene Representation:** a scene representation may contain relations without making relation structure its primary responsibility.
- **≠ Relation Assertion:** an assertion is a semantic statement; a representation can encode many assertions and their structure.
- **≠ Knowledge Graph as a whole:** a knowledge graph is a broader information system/data structure; this concept identifies its relation-organized representational responsibility.
- **≠ Model:** a learned relational model may generate or interpret the representation but is not the representation itself.

## Boundary Cases

A graph containing object nodes and typed edges qualifies when relational structure is the organizing responsibility. A table of pairwise relations qualifies when the relation set is primary. An object record with a few relation fields remains Object-Centric if object identity is primary.

## Trust / Validation

Validate relation type, endpoint identity, directionality where applicable, multiplicity, qualifiers, temporal/spatial scope, provenance, uncertainty, and whether the structure is asserted, inferred, learned, simulated, or hypothesized.

## Lifecycle

Active canonical concept. Specific realization families require independent review.

## Relations / Retrieval Anchors

Use existing GIOP `represents`, `derived-from`, `part-of`, and other admitted relations; no new relation authority is created here.

Retrieval anchors: `RELATION-CENTRIC REPRESENTATION`, `RELATIONAL REPRESENTATION`, `RELATION-ORGANIZED REPRESENTATION`, `GRAPH REPRESENTATION`, `EDGE-CENTRIC REPRESENTATION`.
