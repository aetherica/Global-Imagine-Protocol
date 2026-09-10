# GIOP V3.1 — Immutable Proof Chain

**Chain ID:** `GIOP-V3.1`
**Purpose:** Append-oriented cryptographic record of proof-bearing GIOP artifacts and their version history.
**Hash Algorithm:** SHA-512
**Digest Encoding:** lowercase hexadecimal
**Digest Length:** 128 characters

## Chain Principle

Each proof record contains a cryptographic hash of its declared canonical record content and a reference to the SHA-512 hash of the immediately preceding record.

Therefore:

`CURRENT RECORD → PREVIOUS RECORD HASH → EARLIER RECORD → ... → GENESIS`

A change to a previous record changes that record's hash and breaks the chain of every subsequent record unless the later records are correspondingly regenerated and re-recorded.

This provides a tamper-evident historical chain for GIOP proof records. It does not replace Git history, digital signatures, provenance, authorization, or semantic validation.

## Record Rules

1. Records are append-oriented. Historical records MUST NOT be silently rewritten.
2. Every non-genesis record MUST contain the SHA-512 hash of the immediately preceding record.
3. Every record MUST declare its canonical input.
4. Artifact hashes MUST be computed from the exact declared artifact byte sequence.
5. Artifact SHA-512 and Git commit SHA MUST remain distinct identifiers.
6. A Git commit SHA identifies a Git object history state; an artifact SHA-512 identifies the declared artifact bytes; a record hash identifies the canonical proof record.
7. A changed artifact MUST receive a new artifact hash and a new proof record.
8. Superseded artifacts remain historically recoverable through the proof chain and repository history.

## Canonical Record Hashing

For each record, the `Record SHA-512` is computed over the complete canonical record body from `GIOP IMMUTABLE PROOF CHAIN RECORD` through the final declared field immediately before `Record SHA-512`.

The `Record SHA-512` field itself is excluded from its own input.

This avoids self-referential hashing while keeping the record independently reproducible.

## Genesis Record

```text
GIOP IMMUTABLE PROOF CHAIN RECORD
Chain: GIOP-V3.1
Record: 0000
Type: GENESIS
Previous Record Hash: NONE
Anchor Commit: 53b7e41c7e15dd00ffd1fc0fd44a9669416d0d74
Scope: Foundation baseline before Root 02 semantic content entries
```

**Record SHA-512:** `145b0862a61fecdbee24183fd4489ff679048b466738bc8546f29a70328da206ae6735973c6d5ba71318250c6c8242550dc943179ef1c90f36477014f2942a4b`

## Record 0001 — Root 02 Semantic Content Baseline

```text
GIOP IMMUTABLE PROOF CHAIN RECORD
Chain: GIOP-V3.1
Record: 0001
Type: CONTENT-BASELINE
Previous Record Hash: 145b0862a61fecdbee24183fd4489ff679048b466738bc8546f29a70328da206ae6735973c6d5ba71318250c6c8242550dc943179ef1c90f36477014f2942a4b
Anchor Commit: 6e27082dea96bf195e9bda2e3f52e0bdcbd6f5d5
Scope: Root 02 semantic content baseline
Artifact: 02 SEMANTICS/conditions/optical-condition.md
Artifact Version: 0.1.0
Artifact SHA-512: 4b9701e651f489746b21ad80627a924bf3bf1c367d7202bc1bbd8aacc737fe63484a8eaa186157b6e92cd0b6885bc90b68245ed9edfb9b16383465bbc333223c
Artifact: 02 SEMANTICS/conditions/light-condition.md
Artifact Version: 0.1.0
Artifact SHA-512: f11e85380b1338fc099f3bf66985b9b6c1e64690c89b8853ec5d84413dc61e7e6dfc445b763d2ceea0b1ff00b76520bb0548fcf1172abb5ff2d62cd4b6dac750
Artifact: 02 SEMANTICS/conditions/dark-condition.md
Artifact Version: 0.1.0
Artifact SHA-512: 24b4d67731b684596a9514250316f70b9137ba43e68838888309ea48312a4020271b2ffdae6d52f1436ea75184ca6e7ba2c21174618e6c95c0fa5ca6cd028257
```

**Record SHA-512:** `4efc173fb857e106786de946e62cbfd1fb832a98c0535a6af9a5c7aab5898e39570694d7996e75d32dd069391e2fbe22b71e59865ec45a29e276d96a44c004ea`

## Verification Model

To verify an artifact:

1. Recover the exact artifact bytes identified by the record.
2. Compute SHA-512 over those bytes.
3. Compare the result with the recorded `Artifact SHA-512`.
4. Reconstruct the canonical record body.
5. Compute its SHA-512 and compare it with `Record SHA-512`.
6. Verify that `Previous Record Hash` equals the immediately preceding record's `Record SHA-512`.
7. Continue backward until the genesis record is reached.

A complete match establishes cryptographic consistency of the declared artifact and record chain. It does not, by itself, establish authorship, legal ownership, authorization, semantic correctness, or truth of the underlying knowledge claim.

## Scope Boundary

This chain is a Foundation integrity artifact. It records cryptographic lineage; it does not create a second semantic authority, a second registry, or a competing knowledge base.

`02 SEMANTICS` remains responsible for semantic meaning. `03 REGISTRY` remains responsible for canonical registered identity. This chain records integrity and historical linkage between declared proof-bearing representations.
