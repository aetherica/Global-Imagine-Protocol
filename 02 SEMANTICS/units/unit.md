# Unit — `SEM-UNIT-GENERIC-001`

**Preferred semantic name:** Unit of Measurement  
**Short name:** Unit  
**Semantic ID:** `SEM-UNIT-GENERIC-001`  
**Layer:** Unit  
**Status:** Candidate / implementation target  
**Owner:** Units semantic layer  

## 5W1H

**What:** A Unit is a conventionally governed reference quantity used to express values of quantities of the corresponding kind.

**Why:** It supplies the reference against which a quantity value can be expressed and compared numerically.

**Who:** A unit is established or governed by a recognized metrological, standards, scientific, engineering, industrial, or domain convention as applicable.

**Where:** Units occur wherever quantity values are expressed, measured, reported, exchanged, or computed.

**When:** A unit is used as the reference context of a quantity value; its applicability may depend on the governing system or domain convention.

**How:** A quantity value combines a numerical magnitude with an applicable unit or, for dimension-one cases, an explicitly governed unit/reference convention.

## Semantic definition

A Unit is a reusable semantic concept denoting the reference used to express a quantity value of a specified quantity kind, independent of any particular measured value or measurement event.

## Scope and boundary

Unit owns measurement-reference identity. It does not own Quantity, Quantity Value, Measurement, Measurement Result, instrument, procedure, dimension, or representation syntax.

`Unit ≠ Quantity`  
`Unit ≠ Quantity Value`  
`Unit ≠ Measurement`  
`Unit ≠ Measurement Result`  
`Unit ≠ Quantity Dimension`  
`Unit ≠ Unit Symbol`  
`Unit ≠ Unit Code`

A unit may have names, symbols, codes, system membership, dimensional compatibility, and conversion characteristics without those forms becoming alternate Unit identities.

## Distinctions

A Quantity identifies what measurable aspect is concerned; a Unit supplies the reference used to express it. A numerical value is not a Unit. A measurement activity establishes or obtains a value; it does not become the Unit.

## Cross-domain significance

The concept applies across physical science, engineering, imaging, manufacturing, commerce, information technology, and other domains where governed quantity values are expressed.

## Trust and evidence

Primary semantic anchors: JCGM VIM and BIPM SI materials; ISO 80000 family; controlled implementation evidence such as QUDT and UCUM. Current external standards are evidence sources, not GIOP semantic authorities.

## Visitor Universe

Visitor depth may change examples and retrieval orientation but cannot create audience-specific Unit definitions.

## Lifecycle

Implementation-complete candidate. Canonical promotion requires cross-layer validation and Gate-J.

## Retrieval anchors

`UNIT`, `MEASUREMENT UNIT`, `UNIT OF MEASUREMENT`, `REFERENCE UNIT`, `UNIT OF QUANTITY`, `QUANTITY VALUE UNIT`
