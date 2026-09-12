# GIOP V3.1 — BIL Authoring Specification

**Status:** ACTIVE PREPARATION STANDARD — CANDIDATE SCOPE  
**Domain:** Biological Integrity Lock (BIL)  
**Branch:** `v3.1-tree-architecture`

## Purpose

This specification establishes the common authoring pattern for BIL candidate semantic entries so that BIL records use the same controlled information architecture as established GIOP semantic folders while retaining BIL-specific technical depth.

BIL records are not exempt from the Foundation authoring rules. They must expose stable identity, semantic responsibility, explicit boundaries, evidence/provenance, lifecycle, retrieval anchors and Visitor Universe compatibility.

## Canonical Pattern

Where applicable, every substantive BIL entry follows:

`Identity / Metadata → 5W1H Orientation → Semantic Definition → Scope / Boundary → Core Distinctions → Cross-Domain Significance → Trust / Evidence → Visitor Universe → Lifecycle → Retrieval Anchors`

Technical or profile-specific sections may be inserted between Cross-Domain Significance and Trust when required.

## Identity Envelope

Every entry must expose:

- Semantic ID;
- Preferred Name;
- Semantic Class / Artifact Type;
- Domain;
- Status;
- Version.

Where applicable also expose provenance, authority tier, validation status, related IDs, supersession and scope.

## 5W1H Rule

5W1H is an orientation layer, not a rigid six-field form. Sections may be omitted when genuinely irrelevant, but their underlying information must remain recoverable.

## Definition Rule

The Semantic Definition must state the reusable BIL responsibility in one bounded formulation. It must not simply repeat an external standard, a prompt statement, or an implementation description.

## Boundary Rule

Every entry must distinguish itself from adjacent GIOP layers and from neighbouring BIL candidates. Particularly important boundaries include:

- Property vs Integrity;
- State vs Integrity;
- Relation vs Integrity;
- Representation vs Integrity;
- Validation vs Integrity Decision;
- Evidence vs Claim;
- Deviation vs Failure;
- Drift vs Deviation;
- Permitted Variation vs Arbitrary Change;
- Provenance vs Biological/Configurational Integrity;
- Physical Plausibility vs Reference Fidelity.

## Cross-Layer Rule

BIL consumes existing GIOP semantic layers and must not silently create parallel definitions for their responsibilities. References to Class, Property, Condition, State, Quantity, Activity, Process, Relation, Representation, Temporal, Result, Workflow, Computational Method, Implementation and Provenance should resolve to existing canonical identities where applicable.

## Evidence / Trust Rule

Distinguish source, evidence, inference, validation state, confidence, authority, historical status and unresolved questions. None of these may be collapsed into one generic trust label.

## Visitor Universe Rule

All BIL entries must support the same canonical meaning across visitor depths. Entry depth may change orientation, examples, technical detail, evidence visibility and machine exposure; it must not create audience-specific semantic identities or definitions.

## Machine Retrieval Rule

An isolated BIL record should remain meaningful through stable retrieval anchors including ID, Title, Type, Status, Definition, Primary Responsibility, Evidence/Validation, Provenance and Related IDs.

## Lifecycle Rule

BIL candidate pages remain non-canonical until the applicable Foundation validation and Gate-J promotion are completed. A complete page is not evidence of promotion.

## Formula / Threshold Rule

Profile-specific equations, metrics, thresholds, model parameters and implementation details remain specialized artifacts unless independently validated and promoted. Module 05 values are not universal BIL constants.

## Completion Rule

A BIL authoring pass is structurally complete when all admitted candidate entries follow this pattern, index/registry records are synchronized, boundaries are explicit, Visitor Universe routing remains invariant, and no entry silently creates another semantic authority.
