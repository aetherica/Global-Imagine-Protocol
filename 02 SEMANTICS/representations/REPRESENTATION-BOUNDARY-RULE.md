# Representation Boundary Rule

**Scope:** `02 SEMANTICS/representations`  
**Status:** Active Canonical Authoring Rule  
**Version:** 1.0.0

## Governing Rule

A Representation is an information-bearing form through which identified semantic content is expressed, made available, exchanged, stored, presented, or otherwise made interpretable in a defined context.

The Representation layer must not absorb neighboring semantic responsibilities merely because those responsibilities are involved in producing, carrying, identifying, validating, or consuming a representation.

## Non-Equivalence Rules

```text
Representation ≠ Information / Knowledge
Representation ≠ Result
Representation ≠ Dataset
Representation ≠ File
Representation ≠ Bitstream
Representation ≠ Format
Representation ≠ Media Type
Representation ≠ Encoding
Representation ≠ Serialization Activity
Representation ≠ Compression
Representation ≠ Packaging
Representation ≠ Display
Representation ≠ Observation
Representation ≠ Perception
Representation ≠ Profile
Representation ≠ Conformance
```

## Routing Rules

| Observed responsibility | Canonical semantic home |
|---|---|
| Entity identity | `classes` |
| Characteristic | `properties` |
| Measurable aspect | `quantities` |
| Quantity value | quantity/value semantics |
| Typed connection | `relations` |
| Actual action/occurrence | `activities` |
| Transformation/progression | `processes` |
| Situational frame | `contexts` |
| Condition | `conditions` |
| State | `states` |
| Perceptual experience | `perception` |
| Information-bearing form | `representations` |
| Presentation mechanism | `representations/display.md` |

## Format Boundary

Format is the structural or syntactic specification of a representation. A Format is not a representation instance.

## Encoding Boundary

Encoding is a coding scheme or transformation. An encoded result may constitute a Representation, but the encoding scheme is not the Representation.

## Serialization Boundary

Serialization is an operation or mechanism for producing a concrete expression from an abstract or structured information model. When performed as an actual occurrence it may also be represented as an Activity. Its output may be a Representation.

## File Boundary

File is a storage-oriented artifact. Representation is not defined by storage. A Representation may comprise multiple Files in some preservation contexts.

## Display Boundary

Display is a presentation system/mechanism. A Display can present a Representation; it does not become the Representation.

## Profile and Conformance Boundary

A Profile is a specification-level constraint/extension/guidance layer. Conformance is an assertion that an applicable artifact satisfies requirements. Neither is a Representation subtype.

## Multiple Representations Rule

The same underlying content may have multiple representations. Multiple representations do not imply multiple underlying semantic identities, and shared source does not automatically imply equivalence.

## Transformation Rule

When `R1 → transformation → R2`, R2 must not silently replace R1. Derivation, transformation type, fidelity, and provenance should be explicit where materially relevant.

## Visitor Universe Rule

Visitor Universe categories never determine semantic identity. Do not create visitor-specific Representation concepts, duplicate definitions, or separate ontologies. Entry depth may expose different amounts of the same canonical entry.

## Canonicalization Rule

A new representation-related concept is admitted only after:

1. existing canonical identity check;
2. semantic classification;
3. evidence review;
4. conflict analysis;
5. GIOP semantic synthesis;
6. canonical destination decision;
7. boundary validation;
8. cross-layer relation validation;
9. lifecycle assignment.

If the responsibility belongs elsewhere, route it rather than creating a duplicate.
