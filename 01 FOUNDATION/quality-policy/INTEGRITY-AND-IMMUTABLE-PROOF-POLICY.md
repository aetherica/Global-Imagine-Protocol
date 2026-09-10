# GIOP V3.1 — Integrity and Immutable Proof Policy

Status: CANONICAL FOUNDATION POLICY

## Purpose

Define the canonical cryptographic integrity mechanism used to represent the immutable proof fingerprint of a GIOP artifact, release material, or other declared proof-bearing object.

## Scope

This policy governs the representation and verification of cryptographic integrity fingerprints. It does not by itself establish authorship, legal ownership, semantic authority, registry authority, or identity.

## Canonical Hash Specification

- Hash algorithm: SHA-512
- Digest size: 512 bits
- Canonical encoding: lowercase hexadecimal
- Canonical digest length: 128 characters

A conforming SHA-512 integrity fingerprint MUST therefore be represented as exactly 128 lowercase hexadecimal characters unless an explicitly versioned alternate encoding is declared by a future policy.

## Integrity Meaning

The canonical hash is an integrity fingerprint of the declared byte sequence or artifact representation to which it is attached. Verification consists of recomputing the declared SHA-512 digest over the same canonical input and comparing the resulting canonical representation.

A matching hash demonstrates consistency with the hashed representation. It does not, by itself, prove authorship, legal ownership, authorization, or semantic correctness.

## Trust Boundary

Integrity proof is one component of the GIOP trust model.

- Integrity: cryptographic fingerprint of the declared material.
- Provenance: record of origin, source, lineage, and relevant evidence.
- Validation: determination that the material satisfies its declared technical or structural requirements.
- Authority: determination of which role or layer is entitled to establish or approve a claim.
- Authentication or signature: mechanism used when identity of the signer or publisher must be cryptographically established.

These concepts MUST NOT be treated as interchangeable.

## Immutability and Change

A changed byte sequence produces a different SHA-512 fingerprint. A new version, corrected representation, or superseding artifact MUST receive and record its own fingerprint rather than silently reusing the fingerprint of a different representation.

Historical material MAY remain preserved with its original fingerprint even when superseded.

## Release Verification

Release processes SHOULD verify the integrity fingerprint of declared release-bearing artifacts where reproducibility or tamper detection is required. Release policy remains the authority for release lifecycle and release-state decisions; this policy remains the authority for the canonical hash representation.

## Registry Boundary

`03 REGISTRY` MAY store or expose an integrity fingerprint as metadata associated with a registered object. Registry registration does not redefine this hashing standard.

## Future Algorithm Agility

SHA-512 is the canonical V3.1 representation. Any future alternative algorithm or encoding MUST be introduced as an explicitly versioned policy decision and MUST NOT silently replace the V3.1 canonical form.

## Conformance

An artifact claiming conformance to the GIOP V3.1 immutable-proof convention MUST declare or otherwise make recoverable:

1. the canonical input or artifact representation being hashed;
2. the use of SHA-512;
3. the resulting 128-character lowercase hexadecimal digest; and
4. sufficient provenance to determine what object and version the digest represents.
