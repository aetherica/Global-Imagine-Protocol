# Quantity Knowledge Registry

**Artifact Type:** Knowledge Retention / Decision Registry  
**Semantic Layer:** Quantity  
**Version:** 1.0.0  
**Status:** Active  
**Primary Responsibility:** Retain recovered Quantity-related knowledge and record classification, conflict resolution, canonical decisions, routing, and reconsideration triggers.

## Registry Rule

This registry is not a parallel ontology. Canonical semantic folders remain authoritative.

Each record preserves the path from recovered knowledge to a GIOP decision without treating every retained claim as canonical.

## Decision Record Schema

Each substantive candidate should preserve:

- Registry ID
- Recovered term/claim
- Proposed semantic responsibility
- Evidence/source class
- Epistemic status
- Canonical status
- Conflict/uncertainty
- Existing canonical owner
- GIOP synthesis
- Decision
- Destination
- Reconsideration trigger

## Canonical Records

### QR-0001 — Quantity

**Recovered:** Quantity / physical quantity / measurable quantity terminology.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/quantity.md`.  
**Rationale:** Reusable measurable semantic responsibility distinct from values, units, measurement activities, results, properties, metrics, parameters, and variables.

### QR-0002 — Distance

**Recovered:** Distance as spatial separation.  
**Semantic type:** Quantity.  
**Decision:** Canonical / existing entry preserved.  
**Destination:** `02 SEMANTICS/quantities/distance.md`.  
**Rationale:** Established measurable spatial quantity. `Viewing Distance` remains a relation-qualified use rather than replacing Distance identity.

### QR-0003 — Temperature

**Recovered:** Temperature as thermodynamic physical quantity.  
**Semantic type:** Quantity.  
**Decision:** Canonical / existing entry preserved.  
**Destination:** `02 SEMANTICS/quantities/temperature.md`.  
**Rationale:** Distinct from Temperature Condition, color temperature, CCT, and measurement result.

### QR-0004 — Focal Length

**Recovered:** Focal length as an optical distance.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/focal-length.md`.  
**Rationale:** Optical distance is the primary semantic responsibility. Engineering parameter usage is secondary role semantics.

### QR-0005 — Wavelength

**Recovered:** Wavelength as spatial period of a wave/optical field.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/wavelength.md`.

### QR-0006 — Exposure Time

**Recovered:** Exposure/integration duration in imaging.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/exposure-time.md`.

### QR-0007 — Illuminance

**Recovered:** Photometric incident luminous-flux density.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/illuminance.md`.

### QR-0008 — Luminance

**Recovered:** Photometric directional light quantity.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/luminance.md`.

### QR-0009 — Radiance

**Recovered:** Radiometric directional radiant-power density.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/radiance.md`.

### QR-0010 — Irradiance

**Recovered:** Radiometric incident radiant-power density.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/irradiance.md`.

### QR-0011 — Spatial Frequency

**Recovered:** Spatial periodicity/frequency used in imaging and signal analysis.  
**Semantic type:** Quantity.  
**Decision:** Canonical.  
**Destination:** `02 SEMANTICS/quantities/spatial-frequency.md`.

## Deferred Records

### QR-D001 — Resolution

**Decision:** Deferred.  
**Reason:** The term spans performance characteristic, limiting capability, criterion, and method-specific usage.  
**Reconsider when:** A cross-standard semantic owner can be established without collapsing distinct resolution concepts.

### QR-D002 — MTF

**Decision:** Deferred.  
**Reason:** Transfer-function/performance construct with method and system dependence.  
**Reconsider when:** A distinct canonical responsibility and relation to Spatial Frequency, SFR, OTF, and Property are resolved.

### QR-D003 — SFR

**Decision:** Deferred.  
**Reason:** Commonly a derived/test-method construct.  
**Reconsider when:** Method-independent semantic responsibility is established.

### QR-D004 — Noise

**Decision:** Deferred.  
**Reason:** Physical, statistical, signal-component, and performance meanings diverge.  
**Reconsider when:** Domain distinctions can be represented without semantic inflation.

### QR-D005 — SNR

**Decision:** Deferred.  
**Reason:** Generally a derived comparison/metric based on signal and noise quantities.  
**Reconsider when:** Its primary semantic responsibility is demonstrated as distinct from Metric and Quantity Value structures.

### QR-D006 — Dynamic Range

**Decision:** Deferred.  
**Reason:** Ratio, logarithmic, performance, and specification meanings vary.  
**Reconsider when:** Normative cross-domain responsibility is resolved.

### QR-D007 — Sensitivity

**Decision:** Controlled candidate.  
**Reason:** May denote a Property, response characteristic, or quantity-like concept depending on domain.  
**Reconsider when:** Imaging, sensor, photometric, and metrological usages are reconciled.

## Controlled Candidate Records

### QR-C001 — Pixel Pitch

**Decision:** Candidate.  
**Question:** physical spatial separation versus system specification role.  
**Reconsider when:** Sensor/display geometry and Quantity/Property boundaries are cross-validated.

### QR-C002 — Frame Rate

**Decision:** Candidate.  
**Question:** temporal frequency versus operational specification role.  
**Reconsider when:** Video/temporal semantics and Quantity boundaries are validated.

### QR-C003 — F-number

**Decision:** Candidate.  
**Question:** dimensionless optical ratio versus parameter/configuration role.  
**Reconsider when:** optical and measurement standards are consolidated.

### QR-C004 — Reflectance

**Decision:** Candidate.  
**Question:** normative radiometric quantity versus material/surface characteristic and context-specific ratio terminology.  
**Reconsider when:** CIE/ISO/radiometric distinctions are consolidated.

### QR-C005 — Transmittance

**Decision:** Candidate.  
**Question:** normative radiometric quantity versus optical property/ratio terminology.  
**Reconsider when:** transmission/optical-property boundaries are validated.

## Routed Elsewhere

`Quantity Value` → value/result semantics.  
`Unit` → unit/reference semantics.  
`Measurement` → Activity / measurement semantics.  
`Measurement Result` → result/representation semantics.  
`Optical Distortion` → Property.  
`Temperature Condition` → Condition.  
`Viewing Distance` → Relation usage.  
`Focus State` → State.

## Registry Integrity

A registry record may preserve a rejected, deferred, filtered, or routed candidate without implying that the underlying source claim is false. Registry status records a GIOP decision, not universal truth.
