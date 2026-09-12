# Identifier

## Identity / Metadata
- GIOP ID: SEM-IDENTIFIER-001
- Semantic Layer: Domain Semantic Layer
- Domain: Identity
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Identity, Representation, Relation, Provenance

## 5W1H Orientation

### What
An Identifier is a value, token, label, code, or other designated reference used to denote or distinguish an identity within a declared scope. It is a reference mechanism, not the identity itself.

### Why
Identifiers allow systems and people to refer to an identity consistently, exchange records, establish relations, and retrieve information without requiring the full identity semantics to be embedded in every reference.

### Who
Identifiers may be assigned, generated, maintained, or interpreted by people, organizations, registries, software systems, devices, or other authorities. Their authority depends on the scope that recognizes them.

### Where
An identifier is meaningful within its namespace or identification system. The same lexical value can identify different referents in different namespaces, while one identity can possess multiple identifiers across systems.

### When
Identifiers may be issued, activated, changed, revoked, retired, reused under explicit policy, or superseded. Temporal validity therefore belongs to the identifier's relation to an identity and namespace rather than to the lexical token alone.

### How
An identifier denotes an identity through an explicit or governed mapping, normally expressed with namespace, issuer, scope, and validity information. Resolution of that mapping is an identity operation, not an inherent property of the token.

## Semantic Definition
An Identifier is a scoped reference value intended to denote or distinguish an identity. Its semantic meaning is determined by the identification scheme, namespace, issuer or authority, scope, and applicable validity conditions.

## Scope / Boundary
Identifier owns reference-token semantics. Identity owns the referent. Identity Attribute owns descriptive characteristics. Identity Resolution owns determination of correspondence. A biometric template is not automatically an identifier, although it may participate in identification or verification workflows.

## Core Distinctions
- Identifier ≠ Identity.
- Identifier ≠ Attribute.
- Identifier ≠ Representation.
- Identifier ≠ Biometric Template.
- Identifier equality does not imply referent equality without namespace and scope.

## Cross-Domain Significance
Identifiers support registry lookup, object tracking, dataset linkage, provenance, access control, and cross-system interoperability. They are especially important where the same referent appears in multiple representations or systems.

## Trust / Evidence
Trust in an identifier concerns its issuer, namespace, binding, lifecycle, and provenance. A validly formatted identifier does not prove that its binding to a referent is correct.

## Visitor Universe
Novices need the identity-versus-identifier distinction. Experts need namespace, issuer, binding, temporal validity, collision, reuse, and resolution semantics. Machines need namespace-qualified identifier values and explicit identity relations.

## Lifecycle
Identifier lifecycle may include issuance, activation, suspension, reassignment where permitted, revocation, retirement, and archival. Lifecycle status must be represented separately from the identifier value.

## Retrieval Anchors
identifier, identity identifier, identifier token, namespace identifier, reference code, identity reference
