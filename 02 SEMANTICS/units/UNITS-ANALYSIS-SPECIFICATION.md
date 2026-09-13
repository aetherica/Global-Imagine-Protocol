# Units Analysis Specification

## Purpose

This specification defines the V3.1 authoring scope for the Units semantic layer. It translates metrology evidence into GIOP-compatible semantic ownership without importing an external ontology as canonical authority.

## Core dataset

| ID | Concept | Role |
|---|---|---|
| `SEM-UNIT-GENERIC-001` | Unit | Generic measurement-unit identity |
| `SEM-UNIT-BASE-001` | Base Unit | System-designated unit for a base quantity |
| `SEM-UNIT-DERIVED-001` | Derived Unit | Unit associated with a derived quantity |
| `SEM-UNIT-COHERENT-DERIVED-001` | Coherent Derived Unit | System-relative coherent derived status |
| `SEM-UNIT-SYSTEM-001` | System of Units | Organized unit-system concept |

## Controlled candidate concerns

Unit composition, prefixes, multiples/submultiples, conversion relationships, and specialized unit families remain controlled supporting candidates. They must not be promoted merely because they are common or computationally useful.

## Supporting metadata

Unit name, symbol, code, quantity compatibility, system membership, dimensional compatibility, conversion multiplier, conversion offset, and expression form are supporting information unless independent semantic responsibility is later demonstrated.

## Deferred scope

Information units, logarithmic units, historical/legacy units, specialized technical units, and domain-specific unit families require separate evidence and boundary review before promotion.

## Evidence hierarchy

Primary anchors: JCGM VIM, BIPM SI materials, ISO 80000 family, and applicable IEC standards. QUDT, UCUM, OM, OBOE and related ontologies are implementation/comparative evidence, not GIOP authorities.

## Authoring constraints

No new relation predicate may be introduced. No Quantity, Measurement, Result, Representation, Property, State, Condition, or generic Dimension concept may be re-owned by Units. Candidate status must remain explicit until promotion.
