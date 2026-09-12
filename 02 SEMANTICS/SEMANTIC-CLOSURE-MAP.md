# GIOP V3.1 — Semantic Closure and Integration Map

**Status:** CLOSED FOR CURRENT V3.1 SEMANTIC NUCLEI
**Branch:** `v3.1-tree-architecture`
**Purpose:** Repository-wide closure map for the semantic layers audited and completed in the current implementation wave.

## Governing rule

`Visitor Universe → different entry depth → same canonical knowledge`

Visitor routing never creates alternate semantic identities. Repository placement is organizational; semantic responsibility is authoritative.

## Current closure map

| Layer | Current canonical nucleus | State | Closure treatment |
|---|---|---|---|
| Classes | Camera, Lens, Sensor, Light Source, Surface, Material, Observer, Scene, Object, Measuring System, Representation | Active | Existing compact class model preserved |
| Conditions | Optical Condition and admitted specialized conditions | Active | Existing condition boundaries preserved |
| Properties | Existing canonical property corpus | Active | Property boundary preserved |
| States | `SEM-STATE-GENERIC-001` — State | Active | Specialized states remain controlled candidates |
| Activities | Activity, Execution, Observation, Measurement, Acquisition, Processing, Calibration | Active canonical — scoped | Seven-concept batch closed |
| Relations | part-of, participates-in, observes, represents, derived-from, has-result | Active canonical — scoped | Six-concept seed closed; viewing-distance routed candidate |
| Quantities | Registered active nucleus in `QUANTITY-INDEX.md` | Active canonical | Current nucleus closed; candidate/deferred sets retained |
| Processes | `SEM-PROCESS-GENERIC-001` — Process | Active canonical — scoped | Generic process closed; four specialized candidates deferred |
| Representations | Representation, Display, Format, Encoding, Serialization, Media Type, Compression, Packaging, Profile | Active canonical | Generic batch closed |
| Temporal | `SEM-TEMPORAL-TIME-001` — Time | Active canonical | Current temporal nucleus closed |
| Results | `SEM-RESULT-GENERIC-001` — Result | Active canonical | Current result nucleus closed |
| Workflows | `SEM-WORKFLOW-MEASUREMENT-PROCEDURE-001` — Measurement Procedure | Active canonical | Current procedure nucleus closed |
| Computational Methods | `SEM-COMPUTATIONAL-METHOD-ALGORITHM-001` — Algorithm | Active canonical | Current method nucleus closed |
| Implementations | `SEM-IMPLEMENTATION-SOFTWARE-001` — Software | Active canonical | Current implementation nucleus closed |

## Cross-layer canonical chains

### Acquisition and measurement

`Scene / Object / System → Condition(s) → Procedure → Activity / Execution → Result → Representation`

### Observation and presentation

`Result / Information → Representation → Display → Viewing Conditions → Observer → Perception`

### Computational realization

`Algorithm → Software Implementation → Execution / Processing → Result`

### Temporal qualification

`Phenomenon → Time context → Acquisition / Execution / Processing → Result time → Presentation`

### Viewing geometry

`Reference A → Viewing Distance → Reference B`, with a Distance quantity/value used as qualification where applicable.

## Explicit non-collapses

- Class ≠ Property ≠ Condition ≠ State ≠ Quantity ≠ Activity ≠ Process.
- Procedure ≠ Activity ≠ Execution.
- Algorithm ≠ Software ≠ Processing.
- Result ≠ Measurement Result ≠ Representation.
- Relation concept ≠ relation assertion ≠ validation constraint.
- Quantity ≠ Quantity Value ≠ Unit ≠ Measurement.
- Time ≠ timestamp value ≠ duration quantity.
- Display ≠ Representation.

## Candidate discipline

Closure means the present canonical nucleus is internally integrated. It does not promote every useful or frequently used term. Controlled candidates and deferred concepts remain explicitly retained and require independent validation before promotion.

## Placeholder rule

`.gitkeep` files in semantic folders are repository placeholders only. Their presence is not used as a completeness test. Folder closure is determined by semantic identity, governance, validation, index integrity, lifecycle state, and cross-layer consistency.

## Final decision

The audited semantic folders are mapped to their current responsibility and closure state. No existing canonical layer is redesigned merely to remove lexical or organizational irregularity. Future expansion proceeds by candidate-level validation and explicit promotion rather than by folder-name inference.
