# Process Knowledge Registry

## Registry Status

**ACTIVE — SCOPED PROCESS BATCH**

This registry is a routing and canonicalization record for Process semantics. It is not a parallel knowledge base.

## Records

| ID | Name | Type | Status | Evidence / Routing |
|---|---|---|---|---|
| `SEM-PROCESS-GENERIC-001` | Process | Semantic Concept | Active | ISO 9000; W3C PROV-O; CIDOC CRM; GIOP Activity boundary |
| `SEM-PROCESS-TRANSFORMATION-001` | Transformation Process | Candidate | Deferred | Requires distinction from generic Process and Processing Activity |
| `SEM-PROCESS-DEVELOPMENT-001` | Development Process | Candidate | Deferred | Domain-dependent; requires lifecycle/development boundary |
| `SEM-PROCESS-OPERATIONAL-001` | Operational Process | Candidate | Deferred | Organizational/operational scope requires separate validation |
| `SEM-PROCESS-WORKFLOW-001` | Workflow Process | Candidate | Deferred | Must distinguish process, workflow model, procedure, and representation |

## Canonical Decision Rules

1. A verified external definition is evidence, not automatically GIOP canonical truth.
2. Existing GIOP concepts retain their authority unless a formal semantic decision changes routing.
3. Candidate records are not Active merely because they are listed.
4. Deferred concepts remain recoverable and are not deleted.
5. Visitor Universe does not create duplicate records.
6. Relation terms not already admitted to GIOP are not silently registered from Process pages.

## Evidence Classes

The registry distinguishes:

- source statement
- recovered knowledge
- evidence
- inference
- semantic synthesis
- implementation observation
- historical statement
- canonical decision

## Open Promotion Questions

- Does Transformation Process deserve a distinct canonical responsibility beyond generic Process?
- Does Development Process require a lifecycle-specific semantic layer rather than a Process subtype?
- Is Operational Process sufficiently cross-domain to justify canonical promotion?
- Should Workflow be represented as a process concept, a specification/model concept, or both in separate semantic layers?

These questions remain open by design and do not weaken the generic Process nucleus.
