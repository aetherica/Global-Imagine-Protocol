# GIOP V3.1 — Semantic Closure and Integration Map

**Status:** CLOSED FOR CURRENT V3.1 SEMANTIC NUCLEI + DOMAIN SEED EXTENSIONS + PROVISIONAL MODEL CANDIDATE
**Branch:** `v3.1-tree-architecture`
**Purpose:** Repository-wide closure map for semantic layers and bounded domain/candidate extensions audited and completed in the current implementation wave.

## Governing rule

`Visitor Universe → different entry depth → same canonical knowledge`

Visitor routing never creates alternate semantic identities. Repository placement is organizational; semantic responsibility is authoritative.

## Current semantic-layer closure map

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
| Representations | Representation, Display, Format, Encoding, Serialization, Media Type, Compression, Packaging, Profile, Belief, Object-Centric, and first advanced extension batch | Active canonical | Generic core + first advanced extension batch closed |
| Models | `SEM-MODEL-GENERIC-001` — Model | Provisional candidate layer | Generic candidate fully authored and bounded; specialized model vocabulary deferred; Active promotion not granted |
| Temporal | `SEM-TEMPORAL-TIME-001` — Time | Active canonical | Current temporal nucleus closed |
| Results | `SEM-RESULT-GENERIC-001` — Result | Active canonical | Current result nucleus closed |
| Workflows | `SEM-WORKFLOW-MEASUREMENT-PROCEDURE-001` — Measurement Procedure | Active canonical | Current procedure nucleus closed |
| Computational Methods | `SEM-COMPUTATIONAL-METHOD-ALGORITHM-001` — Algorithm | Active canonical | Current method nucleus closed |
| Implementations | `SEM-IMPLEMENTATION-SOFTWARE-001` — Software | Active canonical | Current implementation nucleus closed |

## V3.1 domain-seed closure extensions

These are completed implementation seeds for previously empty semantic folders. They are **candidate domains**, not automatically Active Canonical nuclei. Their internal implementation is closed for the stated phase; promotion remains subject to semantic validation and Gate-J.

| Domain folder | Seed scope | State | Closure treatment |
|---|---|---|---|
| `identity/` | Identity, Identity Attribute, Identifier, Identity Representation, Identity Resolution | Implementation-complete — candidate | Domain ownership established; identity, identifier, representation, resolution, provenance, and BIL boundaries explicit |
| `biometrics/` | Biometric Characteristic, Biometric Reference, Biometric Template; modality/sample/verification/identification retained as controlled candidates | Implementation-complete — candidate | Biometric ownership established; operational tasks route to Activity/Process/Workflow |
| `textile/` | Textile, Textile Fibre, Yarn, Fabric, Textile Structure, Textile Finish | Implementation-complete — candidate | Textile/material/garment boundaries established; structure and finish now have explicit seed entries |
| `garment/` | Garment, Garment Component, Garment Construction, Garment Pattern, Garment Size Designation, Garment Fit, Garment Fastening | Implementation-complete — candidate | Assembled wearable-article boundary established; textile/body/representation/process boundaries explicit |

## Cross-layer canonical chains

### Acquisition and measurement

`Scene / Object / System → Condition(s) → Procedure → Activity / Execution → Result → Representation`

### Observation and presentation

`Result / Information → Representation → Display → Viewing Conditions → Observer → Perception`

### Computational realization

`Algorithm → Software Implementation → Execution / Processing → Result`

### Model-mediated realization

`Target / Phenomenon → Model → Algorithm / Activity / Process → Result / Representation`

This is a semantic coordination pattern, not a new relation namespace. A model may be non-computational and does not require an algorithm or software implementation.

### Temporal qualification

`Phenomenon → Time context → Acquisition / Execution / Processing → Result time → Presentation`

### Identity and biometric evidence

`Identity → Identity Representation / Attribute / Identifier → Evidence → Identity Resolution`

For biometric applications:

`Biometric Characteristic → Biometric Sample → Biometric Reference / Template → Biometric Comparison → Identity-related Result`

### Textile and garment composition

`Textile Fibre → Yarn → Fabric / Textile Structure → Garment Component → Garment → Fit / Use Context`

## Explicit non-collapses

- Class ≠ Property ≠ Condition ≠ State ≠ Quantity ≠ Activity ≠ Process.
- Procedure ≠ Activity ≠ Execution.
- Algorithm ≠ Software ≠ Processing.
- Result ≠ Measurement Result ≠ Representation.
- Relation concept ≠ relation assertion ≠ validation constraint.
- Quantity ≠ Quantity Value ≠ Unit ≠ Measurement.
- Time ≠ timestamp value ≠ duration quantity.
- Display ≠ Representation.
- Model ≠ Representation ≠ Algorithm ≠ Software ≠ Activity ≠ Process ≠ Result.
- Identity ≠ Identifier ≠ Identity Representation ≠ Biometrics ≠ BIL integrity.
- Textile ≠ Material ontology; Garment ≠ Textile; Fabric ≠ Garment.
- Biometric Reference ≠ Biometric Identity; Biometric Template ≠ generic Representation.

## Candidate discipline

Closure means the present implementation is internally integrated. It does not promote every useful or frequently used term. Controlled candidates and deferred concepts remain explicitly retained and require independent validation before promotion.

## Placeholder rule

`.gitkeep` files in semantic folders are repository placeholders only. Their presence is not used as a completeness test. Folder closure is determined by semantic identity, governance, validation, index integrity, lifecycle state, and cross-layer consistency.

## Model candidate decision

The `models/` folder is implementation-complete for one generic provisional candidate responsibility. It is not Active Canonical. AI model, machine-learning model, causal model, predictive model, world model, system model, architecture model, and digital-twin model remain controlled vocabulary requiring independent promotion review.

## Final decision

The populated domain folders remain distinct from BIL. Model semantics are likewise distinct: BIL may evaluate integrity of model-associated information or configurations but does not own Model. No existing canonical layer has been redefined, and no new relation predicate has been admitted.
