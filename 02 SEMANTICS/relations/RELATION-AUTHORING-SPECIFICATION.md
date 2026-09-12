# Relation Authoring Specification

Status: Active — Scoped Relation Implementation Standard
Version: 1.0.0
Semantic Layer: Relation

## Purpose

This document defines the implementation pattern for canonical GIOP relation entries. A relation entry defines the meaning and controlled behaviour of a reusable semantic connection. It does not store instance assertions, validation logs, raw research notes, or visitor-specific duplicate knowledge.

## Authoring Order

Identity / Metadata → 5W1H Orientation → Semantic Definition → Relation Family → Subject / Domain → Object / Range → Directionality → Inverse → Logical Characteristics → Qualification / Context → Core Distinctions / Non-equivalence → What This Relation Does Not Mean → Inference Boundary → Cross-Layer Significance → Typical GIOP Usage → Trust / Evidence / Validation → Machine / AI Interpretation → Lifecycle → Retrieval Anchors → Semantic Boundary.

The sequence follows the established GIOP authoring pattern used by canonical semantic entries while adding relation-specific semantic and logical contracts.

## Identity / Metadata

Every canonical relation entry MUST expose a stable identity, preferred term, semantic layer, status, version, provenance/evidence basis, and relevant related identifiers.

## 5W1H Orientation

5W1H is an orientation device, not a rigid six-field form. The entry should answer what the relation means, why it is needed, what kinds of subjects and objects it connects, where and when the relation is applicable, and how it is interpreted.

## Semantic Contract

A canonical relation MUST define:

- its semantic definition;
- relation family, where established;
- subject/domain;
- object/range;
- directionality;
- inverse, when applicable;
- relevant superrelation/subrelation information, when established.

Examples do not establish the domain or range. The semantic contract governs examples.

## Logical Contract

Logical characteristics and inference behaviour MUST be documented separately from ordinary data validation constraints. Where applicable, document symmetry, transitivity, reflexivity/irreflexivity, functionality, inverse behaviour, permitted inference, conditional inference, and prohibited inference.

An unspecified characteristic MUST NOT be represented as false merely because evidence is absent.

## Qualification / Context

A relation assertion may require temporal, spatial, configurational, procedural, observational, measurement, or provenance qualification. Qualification belongs to the assertion/context layer unless it is intrinsic to the relation's meaning.

## Boundary Contract

Every relation should identify neighbouring concepts that are easily confused with it and state what the relation does not imply. Similar natural-language wording is not sufficient evidence of semantic identity.

## Cross-Layer Significance

Relation entries should explain which GIOP semantic layers they connect and why the connection matters. Relations connect semantic concepts; they do not absorb the responsibility of the concepts they connect.

## Trust / Evidence / Validation

Provenance, evidence, authority, validation status, confidence, and historical status remain differentiated. Validation constraints must not be silently promoted into ontology-level meaning.

## Machine / AI Interpretation

Machine-facing interpretation should expose the canonical relation identifier, subject/object roles, direction, inverse, inference boundary, and distinction between asserted and inferred relationships. This supports different Visitor Universe entry depths over the same canonical knowledge.

## Visitor Universe

No visitor-specific duplicate definitions are authored. Novice, expert, and machine-facing access may expose different entry depths into the same canonical relation. Orientation is the shallowest layer; semantic contract and boundaries provide deeper technical access; logical and machine interpretation provide the deepest formal layer.

## Canonicalization Rule

A new relation term MUST NOT be canonicalized merely because it appears in research, source material, or natural language. First determine whether an existing canonical relation already carries the intended semantic responsibility. Candidate relations require evidence, conflict analysis, cross-layer reconciliation, and explicit promotion before becoming canonical.

## Index Integrity

The relation README, canonical index, individual relation entries, stable IDs, status, and version MUST remain synchronized. A relation file existing in the repository does not by itself confer canonical authority.

## Exclusions

The relation layer does not own:

- class definitions;
- property definitions;
- quantities or values;
- conditions or states;
- activity execution records;
- processes;
- results as entities;
- representation content;
- instance assertions;
- validation reports;
- raw evidence archives;
- visitor-specific knowledge copies.

## Lifecycle

Candidate → Authored → Integrated → Validated → Approved → Active Canonical, subject to the applicable GIOP promotion gate. Scope-specific promotion MUST NOT be represented as universal approval for future relation concepts.
