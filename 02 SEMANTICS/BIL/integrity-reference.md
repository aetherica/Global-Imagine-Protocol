# BIL Integrity Reference

Status: CANDIDATE — BIL V3.1
Semantic ID: SEM-BIL-INTEGRITY-REFERENCE-001

## Definition
An Integrity Reference is the declared reference context, representation, feature set, configuration, or evidence basis against which an integrity claim is evaluated. It is a BIL control concept, not a replacement for Representation, Identity, Biometric Reference, Scene, or Object.

## Scope
The reference may cover identity, structure, configuration, interaction, appearance, spatial correspondence, temporal continuity, or contextual plausibility. Scope must be explicit.

## Boundary
Reference ≠ source image; Reference ≠ biometric identity; Reference ≠ template; Reference ≠ Result; Reference ≠ truth guarantee.

## Core relations
Reference → scopes → Integrity Claim
Reference → supplies basis for → Integrity Evaluation
Reference → has provenance → Provenance layer
Reference → may be represented by → Representation

## Integrity rule
A reference establishes the comparison basis; it does not itself establish that an output is faithful.

## Visitor Universe
All visitor depths address the same reference semantics. Depth changes explanation and retrieval detail, not reference meaning.

## Lifecycle
Candidate → validated → approved → canonical or deferred. Version and provenance are mandatory when promoted.
