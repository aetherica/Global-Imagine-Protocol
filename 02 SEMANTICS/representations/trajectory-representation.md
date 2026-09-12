# Trajectory Representation

- **ID:** `SEM-REPRESENTATION-TRAJECTORY-001`
- **TITLE:** Trajectory Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form encoding ordered spatial, temporal, or state evolution of an entity, motion, or system
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across robotics motion planning, tracking, dynamical systems, trajectory learning, and spatiotemporal data.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-SPATIOTEMPORAL-001`, `SEM-REPRESENTATION-ACTION-001`

## Semantic Definition

Trajectory Representation is an information-bearing form encoding ordered evolution through space, time, state, or a related trajectory domain, including sampled positions, poses, velocities, actions, or latent trajectory states.

Ordering and evolution are primary. A trajectory can be observed, planned, demonstrated, predicted, simulated, or learned.

## Core Distinctions

- **Trajectory Representation ≠ Trajectory:** the trajectory is the represented evolution; the representation is its information-bearing form.
- **≠ Spatiotemporal Representation:** trajectory is a specialized ordered evolution; spatiotemporal representation is broader.
- **≠ Action Representation:** an action may induce a trajectory; action semantics are not reducible to geometric/time evolution.
- **≠ Process:** process is an organized temporal course, not its representation.
- **≠ Motion Model:** a model explains or predicts trajectory; representation carries trajectory information.

## Boundary Cases

Robot end-effector paths, object tracks, planned motion sequences, and state trajectories qualify. A static point set does not become a trajectory merely because points have an acquisition timestamp.

## Trust / Validation

Record reference frame, temporal sampling, interpolation, coordinate semantics, source, observed/planned/predicted status, uncertainty, synchronization, and provenance.

## Lifecycle

Active canonical concept. Domain-specific trajectory families require independent review.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in`.

Retrieval anchors: `TRAJECTORY REPRESENTATION`, `MOTION TRAJECTORY`, `STATE TRAJECTORY`, `ROBOT TRAJECTORY`, `TRAJECTORY DATA REPRESENTATION`.
