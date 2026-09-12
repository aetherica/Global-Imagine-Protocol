# GIOP V3.1 — Canonical Registry and Lifecycle Control

**Status:** ACTIVE CONTROL FOR PILOT PROMOTION

## Purpose

Define the minimum registry and lifecycle contract required for a semantic artifact to move from validated pilot state to active canonical state.

## Identity contract

Each promoted semantic record must retain:

- stable semantic identifier;
- preferred human-readable name;
- primary responsibility root;
- semantic layer;
- lifecycle state;
- version;
- provenance/evidence reference;
- canonical relations where applicable.

Repository relocation must not change semantic identity.

## Lifecycle

The canonical lifecycle is:

`DRAFT → REVIEW → VALIDATED → ACTIVE → SUPERSEDED → ARCHIVED`

`PROVISIONAL` is permitted for controlled pilot artifacts before activation.

## Promotion condition

An artifact may enter `ACTIVE` only when identity, responsibility, structure, provenance/evidence, cross-reference, duplicate-authority, lifecycle, trust/integrity, and migration/promotion approval gates are satisfied.

## Pilot registry rule

For the current semantic pilot, semantic identity is carried by the Semantic ID in each record. A future centralized registry may project these identities, but registry placement is not allowed to redefine their semantic meaning.

## Supersession

Activation does not erase prior versions. Superseded definitions remain traceable and recoverable.
