# Identity Semantic Domain

**Semantic Domain:** Identity
**Domain Role:** Cross-domain entity identity semantics
**Status:** IMPLEMENTATION-COMPLETE — V3.1 SEED / CANDIDATE DOMAIN
**Authority Boundary:** Identity defines what an identity is, what is being identified, how identity is represented, and how identity resolution is scoped. It does not own biometric methods, provenance, authentication protocols, or BIL integrity evaluation.

## 5W1H Orientation

### What

Identity describes the condition of being a distinguishable entity or referent within a declared scope and the information used to represent or resolve that identity.

### Why

Images, documents, datasets, observations, and machine systems may refer to the same or different entities through names, identifiers, attributes, visual appearance, biometric evidence, or other representations. These must not be conflated with identity itself.

### Who

Identity semantics are relevant to humans, animals, plants, objects, devices, places, organizations, digital entities, fictional entities, and machine-generated or reconstructed subjects.

### Where

Identity may be asserted across physical, digital, observational, representational, archival, and application contexts.

### When

Identity is scoped in time and context. Persistence, change, merger, splitting, replacement, and uncertainty must be represented rather than assumed away.

### How

Identity is established or resolved through declared criteria and evidence. An identifier, attribute, representation, biometric observation, or provenance record may support an identity assertion without becoming the identity itself.

## Semantic Boundary

Identity is not a synonym for personhood, name, identifier, appearance, biometrics, authentication, provenance, or BIL integrity.

- **Identity vs Identifier:** an identifier denotes or references an identity; it is not the identity itself.
- **Identity vs Attribute:** attributes describe an entity; they can change without necessarily changing identity.
- **Identity vs Representation:** a representation carries information about an entity; multiple representations may refer to one identity.
- **Identity vs Biometrics:** biometrics provide specialized observable evidence and comparison mechanisms for identity-related decisions.
- **Identity vs BIL:** BIL evaluates integrity relative to an identity/reference claim; Identity defines the identity semantics being evaluated.

## Cross-Layer Routing

Identity claims may consume **Relations**, **Properties**, **States**, **Representations**, **Temporal** information, **Provenance**, and **Results**. Identity resolution and verification are procedural activities and should be routed to the Activity/Process/Workflow layers when formalized as operations.

## Visitor Universe

Novice visitors enter through the distinction between identity, identifier, attribute, and representation. Expert visitors can navigate scope, identity resolution, persistence, evidence, and uncertainty.

## Lifecycle

Identity entries follow the standard GIOP semantic lifecycle: candidate → validated seed → promotion decision → Active Canonical when Gate-J requirements are satisfied.

## Retrieval Anchors

`IDENTITY`, `ENTITY IDENTITY`, `IDENTITY SUBJECT`, `IDENTITY ATTRIBUTE`, `IDENTIFIER`, `IDENTITY REPRESENTATION`, `IDENTITY RESOLUTION`, `IDENTITY CLAIM`, `IDENTITY VERIFICATION`, `REFERENCE IDENTITY`
