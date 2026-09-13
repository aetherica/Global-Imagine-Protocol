# Derived Unit — `SEM-UNIT-DERIVED-001`

**Preferred semantic name:** Derived Unit  
**Semantic ID:** `SEM-UNIT-DERIVED-001`  
**Layer:** Unit  
**Status:** Candidate / implementation target  
**Parent semantic:** `SEM-UNIT-GENERIC-001`

## 5W1H

**What:** A Derived Unit is a Unit associated with a derived quantity and obtained through the defining relations of a system of quantities.

**Why:** It permits quantities derived from other quantities to be expressed consistently.

**Who:** Its definition and use are governed by the applicable quantity/unit system or domain convention.

**Where:** Derived units occur across scientific, engineering, industrial, imaging, and technical measurement contexts.

**When:** A unit has derived status when its relation to the underlying quantity system is derivational rather than base-unit designation.

**How:** It can be represented through products, quotients, and powers of units associated with the underlying quantities.

## Semantic definition

A Derived Unit is a Unit assigned to a derived quantity and determined from the defining relations of a system of quantities and its associated units.

## Scope and boundary

Derived Unit owns derivational unit status. It does not own the derived quantity itself, its numerical value, or the measurement process.

`Derived Unit ≠ Derived Quantity`  
`Derived Unit ≠ Quantity Dimension`  
`Derived Unit ≠ Measurement Result`  
`Derived Unit ≠ Unit Expression`

Derived does not imply coherent: coherence is a separate, system-relative property.

## Distinctions

A Base Unit is designated for a base quantity in a specified system. A Derived Unit is associated with a derived quantity. A Coherent Derived Unit is a derived unit satisfying the coherence condition of the relevant system.

## Cross-domain significance

Derived-unit semantics enable dimensional consistency, engineering calculation, scientific reporting, interoperability, and compositional unit expressions.

## Trust and evidence

JCGM VIM, BIPM SI materials, and ISO 80000 provide primary/reference terminology. QUDT and UCUM provide implementation evidence for machine-readable composition.

## Visitor Universe

Examples may vary by domain, but the derivational criterion remains stable.

## Lifecycle

Implementation-complete candidate; canonical promotion requires cross-layer validation and Gate-J.

## Retrieval anchors

`DERIVED UNIT`, `DERIVED MEASUREMENT UNIT`, `COMPOSITE DERIVED UNIT`
