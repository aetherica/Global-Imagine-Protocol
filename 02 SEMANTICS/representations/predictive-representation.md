# Predictive Representation

- **ID:** `SEM-REPRESENTATION-PREDICTIVE-001`
- **TITLE:** Predictive Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form structured to encode information useful for predicting future states, observations, events, or outcomes
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across predictive state representations, predictive coding, reinforcement learning, world models, and temporal representation learning.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-BELIEF-001`, `SEM-REPRESENTATION-SPATIOTEMPORAL-001`

## Semantic Definition

Predictive Representation is an information-bearing form structured so that its contents encode or support prediction of future states, observations, events, trajectories, or outcomes.

Prediction may be explicit or implicit in the representation's intended semantic role. The representation itself is distinct from a predictive model, forecasting activity, policy, or predicted result.

## Core Distinctions

- **Predictive Representation ≠ Predictive Model:** the model generates or interprets predictions; the representation is the information-bearing form.
- **≠ Belief Representation:** belief is agent-relative epistemic commitment; predictive organization can exist without representing uncertainty or belief.
- **≠ Prediction Result:** a result is an output/result of prediction; the representation is the form carrying predictive information.
- **≠ State Representation:** state representation need not have predictive organization.
- **≠ World Model:** a world model is a model; its internal predictive representation is a distinct concern.

## Boundary Cases

A latent state designed to retain information predictive of future observations qualifies when predictive responsibility is explicit. A generic embedding does not qualify merely because a downstream model can predict from it.

## Trust / Validation

Record prediction target, horizon, conditioning information, uncertainty, training/model dependence, temporal scope, leakage risks, calibration, provenance, and validation performance.

## Lifecycle

Active canonical concept. Specific predictive realization families remain independently reviewable.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `participates-in`, and `part-of`; no new relation authority.

Retrieval anchors: `PREDICTIVE REPRESENTATION`, `PREDICTIVE STATE REPRESENTATION`, `PREDICTIVE LATENT`, `PREDICTIVE WORLD REPRESENTATION`, `FUTURE-PREDICTIVE REPRESENTATION`.
