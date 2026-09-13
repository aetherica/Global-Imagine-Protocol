# System of Units — `SEM-UNIT-SYSTEM-001`

**Preferred semantic name:** System of Units  
**Semantic ID:** `SEM-UNIT-SYSTEM-001`  
**Layer:** Unit  
**Status:** Candidate / implementation target

## 5W1H

**What:** A System of Units is an organized set of units established for a specified system of quantities.

**Why:** It provides a coherent framework for selecting, relating, and using units across quantities.

**Who:** Systems are established or governed by metrological, scientific, standards, or domain authorities and conventions.

**Where:** Systems operate within defined scientific, engineering, industrial, historical, or domain contexts.

**When:** A system applies when its conventions are selected as the reference framework for expressing relevant quantity values.

**How:** A system specifies its unit structure, including base-unit choices and the rules under which derived and coherent units are formed.

## Semantic definition

A System of Units is an organized set of measurement units associated with a specified system of quantities and governed by rules for their selection and relationships.

## Scope and boundary

A System of Units is not a single Unit, Quantity System, Quantity Dimension, Measurement Procedure, or registry.

`System of Units ≠ Unit`  
`System of Units ≠ System of Quantities`  
`System of Units ≠ SI-only vocabulary`  
`System of Units ≠ Unit Catalog`

System membership and status are contextual; a unit's identity does not disappear merely because another system is selected.

## Distinctions

A Base Unit is a unit designation within a specified system. A Derived Unit is determined from quantity relations. A Coherent Derived Unit additionally satisfies the coherence condition of the relevant system. The System of Units organizes these units but does not replace them.

## Cross-domain significance

System-of-units semantics support scientific interoperability, standards comparison, conversion, dimensional reasoning, engineering communication, and machine-readable quantity-value exchange.

## Trust and evidence

JCGM VIM, BIPM SI materials, and ISO 80000 provide primary/reference evidence. QUDT and UCUM provide implementation evidence only.

## Visitor Universe

Visitor orientation may explain SI, customary, historical, information, or specialized systems without creating audience-specific system identities.

## Lifecycle

Implementation-complete candidate; canonical promotion requires cross-layer validation and Gate-J.

## Retrieval anchors

`SYSTEM OF UNITS`, `UNIT SYSTEM`, `MEASUREMENT UNIT SYSTEM`, `COHERENT SYSTEM OF UNITS`
