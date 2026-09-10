# GIOP V3.1 — Immutable Proof Record

Status: OPERATIONALLY VERIFIED FOUNDATION RECORD

## Proof Object

- Object ID: `GIOP-V3.1-FOUNDATION-INTEGRITY-PROOF-001`
- Object Type: `Foundation Integrity Proof Input`
- Object Version: `V3.1`
- Canonical Input: `01 FOUNDATION/quality-policy/IMMUTABLE-PROOF-INPUT-V3.1.md`
- Proof Scope: SHA-512 integrity of the exact UTF-8 byte sequence of the declared canonical input file.

## Canonical Integrity Representation

- Hash Algorithm: `SHA-512`
- Digest Size: `512 bits`
- Encoding: `lowercase hexadecimal`
- Digest Length: `128 characters`

## Immutable-Proof Digest

`a4f079add6fa82345959d05459bcaa9300bd3b3795444d7ffb9d4f53f83fcf31d5fe23e20d8ae0180d6541031300e0217f7759811bac316f3314ffc4a04e1155`

## Verification Rule

To verify this record, recompute SHA-512 over the exact UTF-8 bytes of `IMMUTABLE-PROOF-INPUT-V3.1.md` and compare the resulting lowercase hexadecimal digest character-for-character with the digest recorded above.

A matching digest establishes integrity of the declared input representation. It does not independently establish authorship, legal ownership, authorization, semantic correctness, or digital-signature authenticity.

## Repository Reference

The proof input was added on branch `v3.1-tree-architecture` in commit `c0820671242ed9320b903358819a32548e715f41`.

The Git commit SHA is repository history metadata and is not the GIOP immutable-proof digest. The GIOP immutable-proof requirement applies to the 128-character SHA-512 digest recorded above.

## Reverification Requirement

Any change to the canonical proof input MUST invalidate this digest for the changed representation. A new proof input version or corrected representation MUST receive a newly computed SHA-512 digest and a new proof record or superseding record.
