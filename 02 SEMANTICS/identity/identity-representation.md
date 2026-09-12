# Identity Representation

## Identity / Metadata
- GIOP ID: SEM-IDENTITY-REPRESENTATION-001
- Semantic Layer: Domain Semantic Layer
- Domain: Identity
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Identity, Representation, Provenance, Temporal

## 5W1H Orientation

### What
An Identity Representation is a representation that conveys, depicts, describes, encodes, or references information about an identity. It can be visual, textual, symbolic, structured, biometric, or multimodal.

### Why
Identity representations allow an identity to be communicated, stored, compared, retrieved, or interpreted across systems. They provide observable or encoded evidence without becoming the underlying identity.

### Who
Representations may be produced or consumed by people, sensors, databases, software, institutions, or automated systems. Their authority depends on provenance, generation method, and context.

### Where
An identity representation may occur in documents, profiles, databases, images, video, audio, tokens, templates, records, or other media. Representation semantics remain governed by the generic Representation layer.

### When
Representations are generated, updated, transformed, transmitted, stored, or retired over time. A representation may become stale or inconsistent while the identity remains unchanged.

### How
An identity is represented through a defined representational form, with provenance and contextual metadata where required. Interpretation requires distinguishing the represented referent from the representation artifact.

## Semantic Definition
An Identity Representation is a representation whose intended referent or semantic subject is an identity. It may contain identity attributes, identifiers, biometric information, or other evidence, but it is not itself the identity.

## Scope / Boundary
This folder owns the identity-specific role of representations. Generic Representation owns representation types and mechanics. Biometrics owns biometric references/templates. Provenance owns lineage and authenticity claims. BIL evaluates representation integrity when relevant to an integrity profile.

## Core Distinctions
- Representation ≠ Identity.
- Representation ≠ Identifier.
- Representation ≠ Identity Attribute.
- Representation ≠ Evidence of truth by default.
- Representation fidelity and provenance are distinct properties.

## Cross-Domain Significance
Identity representations connect identity semantics to imaging, text, audio, structured data, biometrics, provenance, and retrieval. Cross-representation consistency is important when several representations claim to refer to the same identity.

## Trust / Evidence
Trust depends on provenance, source authority, generation history, integrity controls, and contextual suitability. Authentic provenance does not by itself prove that the representation accurately describes the claimed identity.

## Visitor Universe
Novices need referent-versus-representation clarity. Experts need representation lineage, transformations, temporal validity, cross-representation consistency, and evidence quality. Machines need typed representation links, provenance, and identity references.

## Lifecycle
A representation may be created, captured, transformed, validated, published, superseded, archived, or withdrawn. These lifecycle events do not necessarily alter the underlying identity.

## Retrieval Anchors
identity representation, identity record, identity depiction, identity encoding, identity profile representation, identity evidence representation
