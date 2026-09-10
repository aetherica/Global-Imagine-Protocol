# GIOP V3.1 — Quality Policy

Status: CANONICAL

## Purpose

Define the minimum quality expected before GIOP material is treated as dependable within its declared role.

## Quality dimensions

Identity, responsibility assignment, terminology, structure, provenance, integrity, evidence, technical correctness, relation integrity, lifecycle state, accessibility, and preservation.

## Quality gates

A material artifact should pass: identity check → responsibility check → structural check → provenance check → integrity check → claim/formula review → relation check → duplicate-authority check → lifecycle/version check.

## Integrity reference

Cryptographic integrity fingerprints MUST follow `INTEGRITY-AND-IMMUTABLE-PROOF-POLICY.md` when the GIOP immutable-proof convention is declared. The canonical V3.1 form is SHA-512, encoded as exactly 128 lowercase hexadecimal characters.

## Trust distinctions

Status, validation, confidence, authority, provenance, and integrity are distinct fields and must not be used as synonyms.

## Failure handling

Known uncertainty must be labeled. A failed or incomplete validation blocks stronger claims of authority but does not require destruction of the underlying material. An integrity mismatch indicates that the hashed representation and the presented representation do not match and must be investigated.
