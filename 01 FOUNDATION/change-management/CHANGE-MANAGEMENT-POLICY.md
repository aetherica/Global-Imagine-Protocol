# GIOP V3.1 — Change Management Policy

Status: CANONICAL

## Purpose

Control changes to GIOP structure, policy, documentation, semantic content, registry identity, implementation references, and release material without losing traceability.

## Change classes

- Structural: repository tree or responsibility-boundary change.
- Policy: change to a Foundation rule.
- Semantic: change to canonical meaning.
- Registry: change to canonical identity or registration.
- Content: correction, addition, or clarification that does not alter authority boundaries.
- Implementation: code, schema, runtime, or machine artifact change.
- Historical: preservation or annotation of superseded material.

## Required change record

A material change should identify: reason, affected artifact(s), current state, proposed state, impact, evidence, reviewer, version consequence, and rollback or supersession path where applicable.

## Structural restraint

Locked tree architecture is not changed for convenience. A structural change requires demonstrated responsibility failure, unresolved overlap, or a durable new responsibility boundary.

## Decision order

Observation → problem definition → alternatives → decision → validation against related artifacts → implementation → record.

## Preservation

No material source is deleted merely because a newer representation exists.
