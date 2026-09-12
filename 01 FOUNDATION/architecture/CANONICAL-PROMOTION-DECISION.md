# GIOP V3.1 — Canonical Promotion Decision

**Scope:** Current semantic pilot batch  
**Decision:** NOT PROMOTED TO ACTIVE CANONICAL  
**Current state:** VALIDATED FOR PILOT / PROVISIONAL

## Decision Summary

The current semantic batch has completed the substantive semantic integration and pilot validation pass. It has **not** been promoted to active canonical status because the governing content-authoring readiness specification remains explicitly `PREPARATION ONLY` and states that failure at any validation gate blocks canonical promotion. fileciteturn45file0L2-L2

This is a gating decision, not a semantic rejection.

## What Has Been Accepted

The following semantic responsibilities are accepted for continued pilot use:

- Temperature → Quantity
- Temperature Condition → Condition
- Distance → Quantity
- Viewing Distance → Relation + Distance qualification
- Measurement Procedure → reusable workflow/procedure specification
- Time → temporal semantic foundation
- Result → execution-generated result entity
- Display → presentation system/mechanism
- Algorithm → computational method/rule
- Software → computational implementation/artifact
- has-result → reusable execution-to-result relation

The semantic integration map records these boundaries and their canonical chains. They remain aligned with the existing class/property/condition/relation architecture rather than replacing it.

## Why Active Promotion Is Blocked

The readiness specification requires the following before canonical promotion:

- executable provenance and evidence controls;
- validation paths and review state;
- resolved cross-reference controls;
- lifecycle/version and supersession semantics;
- differentiated trust/integrity metadata;
- migration/promotion approval.

The current preparation documents explicitly state that substantive authoring/promotion remains gated until readiness is established. fileciteturn45file0L2-L2

The format validation matrix likewise states that the emerging system is a validation instrument and that principles should be promoted only after they survive relevant artifact stress tests and do not conflict with canonical semantics, registry identity, terminology, provenance, or lifecycle requirements. fileciteturn46file0L2-L2

## Promotion Rule

No file in the current pilot batch should be relabeled `ACTIVE` merely to indicate completion of the writing task. Repository presence, semantic validation, and canonical activation are three different states.

The current state is therefore:

`AUTHORED → INTEGRATED → VALIDATED FOR PILOT → PROMOTION BLOCKED → PROVISIONAL`

The correct next promotion event is an explicit Gate-J approval after the remaining readiness controls have been demonstrated.

## Preservation

No existing semantic record, class definition, relation vocabulary, or V3 source material is discarded by this decision. Deferred promotion is not deletion, and pilot validation is not an instruction to rewrite the architecture.
