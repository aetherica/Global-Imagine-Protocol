# Identity Attribute

## Identity / Metadata
- GIOP ID: SEM-IDENTITY-ATTRIBUTE-001
- Semantic Layer: Domain Semantic Layer
- Domain: Identity
- Status: CANONICAL CANDIDATE — V3.1 SEED
- Cross-layer dependencies: Identity, Property, Quantity, State, Temporal, Representation

## 5W1H Orientation

### What
An Identity Attribute is a characteristic, descriptor, or value associated with an identity for purposes of describing, distinguishing, classifying, or managing that identity.

### Why
Identity attributes provide structured information about a referent and support identity resolution, registry management, eligibility decisions, personalization, and interoperability. They allow identity information to change without redefining the identity itself.

### Who
Attributes may be asserted by the identity subject, an authority, an observer, a measuring system, a registry, or another qualified source. The source and assurance level affect the trust of the assertion.

### Where
Attributes may exist in identity records, registries, profiles, representations, observations, or external systems. Their meaning is always interpreted within a domain and attribute vocabulary.

### When
An attribute may be time-invariant for a defined scope or may change with state, circumstance, measurement, or lifecycle. Temporal qualification is therefore often necessary.

### How
Attributes are represented as typed characteristics with values, units where applicable, provenance, temporal validity, and scope. Some attributes are measured; others are assigned, inferred, or asserted.

## Semantic Definition
An Identity Attribute is a typed characteristic associated with an identity within a declared scope. It describes or qualifies the identity without becoming identical to the referent.

## Scope / Boundary
Identity Attribute owns identity-associated descriptive semantics. Generic Property and Quantity remain owners of general characteristics and measurable quantities. State owns recognized temporal configurations. Biometrics owns biometric characteristics. An attribute may reference any of these without duplicating their semantics.

## Core Distinctions
- Attribute ≠ Identity.
- Attribute ≠ Identifier.
- Attribute ≠ Property in the generic ontology sense, although an attribute may instantiate a property.
- Attribute ≠ Biometric characteristic.
- Attribute value ≠ identity proof.

## Cross-Domain Significance
Attributes bridge identity records with measurement, observation, representation, governance, and temporal reasoning. They are central to identity resolution while remaining distinguishable from the evidence used to establish them.

## Trust / Evidence
Every important attribute assertion should be interpretable with source, provenance, confidence or assurance where available, and validity interval when relevant. An attribute can be correct, stale, disputed, inferred, or unknown independently of the identity referent.

## Visitor Universe
Novices need the distinction between identity and descriptions of identity. Experts need attribute vocabulary, source authority, temporal validity, derivation, assurance, and conflict handling. Machines need typed attribute predicates and value references.

## Lifecycle
Attributes can be asserted, verified, updated, superseded, disputed, withdrawn, or archived. Attribute lifecycle does not necessarily change identity lifecycle.

## Retrieval Anchors
identity attribute, identity characteristic, identity descriptor, identity value, subject attribute, identity record attribute
