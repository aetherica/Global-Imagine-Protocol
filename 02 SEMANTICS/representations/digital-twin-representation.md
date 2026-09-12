# Digital-Twin Representation

- **ID:** `SEM-REPRESENTATION-DIGITAL-TWIN-001`
- **TITLE:** Digital-Twin Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form representing a physical or operational counterpart within a digital-twin system
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across ISO digital-twin terminology, manufacturing digital-twin frameworks, twinning/synchronization practice, and GIOP representation boundaries.
- **VALIDATION:** Independent system-boundary review passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-STATE-GENERIC-001`, `SEM-MODEL-GENERIC-001`

## Semantic Definition

Digital-Twin Representation is an information-bearing form that represents a physical or operational counterpart, or selected aspects of that counterpart, within a digital-twin system and its twinning/synchronization context.

It may contain identity, structure, geometry, state, behaviorally relevant information, history, or synchronized observations. It does not imply that every digital twin is merely a static representation; a complete digital-twin system can include models, processes, interfaces, data, and synchronization mechanisms.

## Core Distinctions

- **Digital-Twin Representation ≠ Physical Twin:** the latter is the physical counterpart.
- **≠ Digital Twin System:** the system can include representation plus models, interfaces, synchronization, processes, and services.
- **≠ Model:** a model may be embedded or associated with the representation but does not define all representational content.
- **≠ State:** synchronized state is content that may be represented, not the representation itself.
- **≠ Visualization:** a visualization is a presentation of selected information, not necessarily the twin representation.

## Boundary Cases

A synchronized digital representation of an industrial asset qualifies. A generic CAD model becomes a Digital-Twin Representation only when it participates in the defined counterpart/twinning responsibility rather than merely depicting geometry.

## Trust / Validation

Record counterpart identity, synchronization scope, time, provenance, source systems, fidelity, update latency, model dependencies, uncertainty, and lifecycle relationship to the physical counterpart.

## Lifecycle

Active canonical concept. Industry-specific twin representations require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in`; no new twinning relation authority.

Retrieval anchors: `DIGITAL-TWIN REPRESENTATION`, `DIGITAL REPRESENTATION OF PHYSICAL ENTITY`, `TWIN REPRESENTATION`, `INDUSTRIAL DIGITAL-TWIN REPRESENTATION`, `DIGITAL TWIN DATA REPRESENTATION`.
