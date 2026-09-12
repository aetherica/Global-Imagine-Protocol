# BIL Integrity Constraint

Status: CANDIDATE — BIL V3.1
Semantic ID: SEM-BIL-INTEGRITY-CONSTRAINT-001

## Definition
An Integrity Constraint is a scoped rule that identifies an invariant, permitted range of variation, correspondence requirement, or acceptance condition relevant to an Integrity Claim.

## Boundary
Constraint ≠ Property; Constraint ≠ Quantity; Constraint ≠ validation result; Constraint ≠ physical law unless explicitly routed to the owning domain.

## Types
Identity constraint; structural constraint; relational/configurational constraint; temporal constraint; representation constraint; contextual constraint; transformation constraint.

## Rule
Constraints must state scope and applicability. A constraint cannot silently convert an observed deviation into a failure.

## Visitor Universe
Constraints are exposed progressively from human-readable intent to formal machine-checkable expressions.
