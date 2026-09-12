# Process Analysis Specification

## Status

**VALIDATED — SCOPED PROCESS BATCH**

## 1. Research Basis

The Process layer was synthesized against multiple independent semantic models rather than copied from a single vocabulary.

### ISO 9000 process semantics

ISO 9000 defines a process as a set of interrelated or interacting activities that uses or transforms inputs to deliver a result. This establishes the core relationship between process, activity, input, transformation, and result. citeturn0search7turn0search48

### W3C PROV-O

PROV-O defines an Activity as something that occurs over a period of time and acts upon or with entities, including consuming, processing, transforming, modifying, relocating, using, or generating entities. This supports the GIOP distinction between occurrence-level Activity and a broader Process construct. citeturn0search6

### CIDOC CRM

CIDOC CRM models E7 Activity as an event-level action and permits complex, composite, and long-lasting actions. Its model demonstrates the value of distinguishing temporal occurrences from other persistent entities, while its class hierarchy is not imported wholesale into GIOP. citeturn0search50

## 2. Semantic Synthesis

The independent sources converge on several useful axes:

| Axis | GIOP routing |
|---|---|
| organized temporal course | Process |
| occurrence-level action | Activity |
| prescribed method | Procedure |
| generated output/information | Result |
| recognized mode at time | State |
| situational circumstance | Condition / Context |
| information-bearing form | Representation |
| computational method | Algorithm |
| implementation artifact | Software |

## 3. Core Model

```text
Process
  ├── organized temporal course
  ├── interrelated/interacting activities
  ├── inputs/resources
  ├── transformations/progression/coordination
  └── results

Activity
  └── actual occurrence within or associated with the course
```

This is a coordination model, not a universal inheritance tree.

## 4. Candidate Concepts

### Transformation Process

Potential responsibility: process whose primary semantic identity is transformation of one or more inputs into changed outputs/results.

Status: **Canonical Candidate**.

Reason for deferral: transformation is central to many process models but can overlap with generic Process, Processing Activity, computational transformation, and domain-specific transformation semantics.

### Development Process

Potential responsibility: organized progression through stages toward development, maturation, construction, or improvement.

Status: **Canonical Candidate**.

Reason for deferral: development is strongly domain-dependent and can overlap with lifecycle, engineering development, software development, research progression, or biological processes.

### Operational Process

Potential responsibility: repeatable or controlled operational course executed in a production/service/runtime context.

Status: **Canonical Candidate**.

Reason for deferral: operational terminology is organizational and domain-specific; generic Process can often carry the same semantics without another root.

### Workflow Process

Potential responsibility: explicitly organized sequence/graph of activities, dependencies, and execution stages.

Status: **Canonical Candidate**.

Reason for deferral: workflow is often a specification, model, automation artifact, or process realization rather than a single universal semantic category. It must not be conflated with Procedure or Process without further analysis.

## 5. Non-Candidates / Routing Decisions

- Processing is already an Active canonical Activity concept.
- Execution is already an Active canonical Activity concept.
- Procedure is not silently created in this batch.
- Result is not silently created in this batch.
- Project is not treated as Process.
- Algorithm is not treated as Process.
- Workflow documents/files are representations or artifacts describing processes, not automatically processes themselves.

## 6. Relation Authority

The Process batch does not create new relation concepts. Existing canonical relations are reused only where their definitions legitimately apply. Any future process-specific relation must be independently authored and promoted in the Relations layer.

## 7. Visitor Universe

The semantic body remains singular. Visitor classes affect entry depth, retrieval framing, and explanation, not canonical Process identity.
