# GIOP V3.1 — State Example Catalog

## Status

**CANONICAL — V3.1 STATE VALIDATION EXAMPLES**

## Purpose

This catalog stress-tests State semantics against realistic imaging, sensing, operational, and system examples. Examples are organizational and explanatory evidence; they do not create independent canonical State entries unless a separate canonical decision is made.

## Governing Rule

Each example must answer:

1. What is the bearer?
2. What State is being asserted?
3. What is the temporal locus?
4. Why is the primary responsibility State?
5. Why is it not primarily Condition, Property, Status, Quantity/Value, Activity, Process, Event, Disposition, Configuration, or Context?

## Example 01 — Camera in Standby

**Assertion:** Camera-01 is in Standby at `t₁`.

**Why State:** The assertion describes a recognized operational mode occupied by the camera at a temporal locus.

**Why not Activity:** No action is being denoted.

**Why not Process:** No transformation is being described.

**Why not Property:** Standby is not an attributable technical characteristic such as spectral response or linearity.

**V3.1 disposition:** Valid State usage example; `Standby` remains candidate vocabulary, not an independent canonical entry.

## Example 02 — Camera Ready for Capture

**Assertion:** Camera-01 is Ready at `t₂`.

**Why State:** Ready describes a recognized bearer mode relevant to operational behavior.

**Boundary:** The exact meaning of Ready depends on the governing system model and its readiness criteria.

**V3.1 disposition:** Strong State candidate; not separately canonicalized in V3.1.

## Example 03 — Camera Recording

**Assertion:** Camera-01 is in Recording during interval `I₁`.

**Why State:** In a state model, Recording may denote the current operational mode of the camera.

**Why not automatically Activity or Process:** The same term may denote the recording activity or recording process in another model.

**V3.1 disposition:** Deferred candidate because State/Activity/Process/Mode responsibilities can overlap.

## Example 04 — Sensor Active

**Assertion:** Sensor-01 is Active during interval `I₂`.

**Why State:** Active may characterize a current operational mode of a sensor.

**Boundary:** In another model Active may be status, control state, or configuration. The governing model must be explicit.

**V3.1 disposition:** Candidate only.

## Example 05 — Sensor Temperature and Overheated State

**Evidence:** A sensor temperature measurement is 85 °C at `t₃`; an established diagnostic rule classifies the sensor as Overheated.

**Measurement:** `85 °C` belongs to quantity/value semantics.

**Inference:** The diagnostic rule is a computational/model process.

**State:** Overheated may be a recognized state when the system defines that classification as a bearer condition.

**V3.1 disposition:** Strong example of measurement-derived State; `Overheated` remains candidate.

## Example 06 — Low Illumination During Capture

**Assertion:** The scene is under low illumination during interval `I₃`.

**Primary responsibility:** Condition.

**Why not State:** The statement describes an applicable optical circumstance rather than a recognized operational mode of the scene/camera bearer.

**V3.1 disposition:** Route to `conditions/` semantics.

## Example 07 — Camera Calibration Status

**Assertion:** Camera-01 calibration is current.

**Primary responsibility:** Status-related semantics.

**Why not automatically State:** The phrase expresses a validity/standing determination about calibration, not necessarily a current bearer mode.

**V3.1 disposition:** Deferred / route toward future Status-layer analysis.

## Example 08 — Camera Configuration

**Description:** Camera-01 is configured for 4K, 24 fps, codec X, lens Y.

**Primary responsibility:** Configuration/settings semantics.

**Why not automatically State:** The statement describes selected configuration, not necessarily a recognized current mode.

**V3.1 disposition:** Not a canonical State assertion.

## Example 09 — Ready to Running Transition

```text
Ready
  ↓ transition
Running
```

**Primary responsibility:** Transition/state-machine structure.

**Why not State:** The arrow denotes change between States, not either State itself.

**V3.1 disposition:** Structural State-model example.

## Example 10 — Multiple Concurrent State Dimensions

```text
Camera-01
├── Power State: On
├── Recording State: Recording
└── Network State: Connected
```

**Purpose:** Demonstrates that a bearer may participate in several model-specific State dimensions.

**Boundary:** This does not establish a universal GIOP rule that every bearer has exactly one State or that these are canonical subtypes of State.

**V3.1 disposition:** Valid structural example.

## Example 11 — Disposition Versus State

**Disposition:** Sensor-01 has a tendency/capability to overheat under defined conditions.

**State:** Sensor-01 is Overheated at `t₄`.

**Process:** Temperature rises and the physical change unfolds.

**V3.1 disposition:** Demonstrates separation of disposition, process, and State.

## Example 12 — Observation Versus State

**Observation:** A system observes a device indicator or receives telemetry indicating Running.

**State:** The semantic classification is Running under the governing state model.

**Provenance:** The assertion may be backed by an observation source.

**Boundary:** Observation establishes evidence; it does not redefine State semantics.

## Example 13 — Value Versus State

**Value:** `85 °C`.

**State:** Overheated.

**Rule:** A state may be derived from one or more values, but the State and value remain distinct semantic responsibilities.

## Example 14 — Visitor Depth

### General

A State tells us what mode or condition a bearer is in.

### Learning

Ready, Standby, Recording, and similar terms may be State candidates, but environmental conditions and measured values are not automatically States.

### Practitioner

State semantics can support operational navigation and system interpretation.

### Engineering / Research

State assertions require bearer scope, temporal qualification, evidence, model constraints, and cross-layer boundaries.

### Machine / AI

Use stable State IDs, assertion structures, provenance, validation status, and explicit semantic type rather than lexical or folder inference.

## Example Governance

Examples may be expanded as new semantic conflicts are discovered. Expansion must not silently promote an example term into a canonical semantic entry.
