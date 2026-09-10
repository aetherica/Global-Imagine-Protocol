# GIOP V3.1 — Release Policy

Status: CANONICAL

## Purpose

Define release readiness for GIOP knowledge snapshots, specifications, and implementation artifacts.

## Release levels

A release may expose draft, reviewed, validated, certified, active, superseded, archived, or preserved material according to declared lifecycle state.

## Readiness

Before release, verify version identity, affected artifacts, validation status, unresolved issues, compatibility impact, provenance, integrity requirements, and preservation of prior release state.

Where the GIOP immutable-proof convention is declared, release-bearing artifacts must apply the canonical integrity representation defined in `../quality-policy/INTEGRITY-AND-IMMUTABLE-PROOF-POLICY.md`. Release policy governs when release integrity verification is required; the integrity policy governs the hash representation itself.

## No silent mutation

A released artifact must remain reproducible for its declared version. Corrections requiring a new state must be represented through versioning or supersession rather than silent replacement.
