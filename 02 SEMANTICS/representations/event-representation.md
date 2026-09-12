# Event Representation

- **ID:** `SEM-REPRESENTATION-EVENT-001`
- **TITLE:** Event Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding event identity, occurrence structure, temporal bounds, participants, or event attributes
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across event semantics, temporal databases, event-based vision, provenance, and event-centric AI.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-STATE-GENERIC-001`, `SEM-ACTIVITY-GENERIC-001`

## Semantic Definition

Event Representation is an information-bearing form encoding an event or event structure, including occurrence identity, temporal extent, participants, attributes, ordering, or event-related evidence.

It may represent discrete events, event streams, event graphs, timestamped occurrences, or event-derived structures. Event representation is independent of the represented event and of the activity that constructs the representation.

## Core Distinctions

- **Event Representation ≠ Event:** the event is the occurrence; the representation is its information-bearing form.
- **≠ Activity:** an activity may generate event information; the representation is not the occurrence.
- **≠ State:** a state is a recognized mode/condition; an event may mark or cause a transition but is not a state.
- **≠ Event-based sensor data:** raw event data may instantiate or carry event representations, while the sensor process remains separate.
- **≠ Temporal Representation in general:** temporal structure may be represented without event identity being primary.

## Boundary Cases

Event-camera event streams, event graphs, incident records, and structured temporal occurrence records qualify when event semantics are primary. A timestamped sensor sample is not automatically an event. A state-change record qualifies when the represented object is the occurrence of change rather than merely the resulting state.

## Trust / Validation

Record event identity, temporal precision, participants, source, provenance, ordering assumptions, uncertainty, missingness, detection/inference status, and synchronization basis.

## Lifecycle

Active canonical concept. Domain-specific event representations require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in`; no new relation authority.

Retrieval anchors: `EVENT REPRESENTATION`, `EVENT DATA REPRESENTATION`, `EVENT STREAM REPRESENTATION`, `EVENT GRAPH`, `TEMPORAL EVENT REPRESENTATION`.
