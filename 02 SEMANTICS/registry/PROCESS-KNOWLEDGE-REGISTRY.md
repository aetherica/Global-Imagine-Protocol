# GIOP V3.1 — Process Knowledge Registry

**Registry ID:** `GIOP-REG-PROCESS`  
**Semantic Area:** Process  
**Version:** 1.0.0  
**Status:** Active  
**Authority:** GIOP

## Registry Purpose

This registry retains Process-related recovered knowledge, candidate concepts, evidence, decisions, uncertainty, boundaries, and reconsideration triggers. It is a retention, decision, and audit layer; it is not a parallel Process ontology.

## Canonical Record

### R-PRO-001

- **Semantic ID:** `SEM-PROCESS-GENERIC-001`
- **Preferred Name:** Process
- **Semantic Type:** Generic semantic concept
- **Epistemic Status:** Synthesized / validated
- **Canonical Status:** Active
- **Primary Responsibility:** Organized temporal course / transformation / progression
- **Destination:** `02 SEMANTICS/processes/process.md`
- **Evidence Basis:** GIOP Activity semantics; ISO 9000 process terminology; W3C PROV-O; CIDOC CRM as comparative evidence
- **Boundary Decision:** Distinct from Activity, Procedure, Result, State, Condition, Context, Representation, Algorithm, Software, Project, and Method.
- **Validation:** Cross-layer and scoped promotion gates passed.

## Controlled Candidate Records

### R-PRO-C01 — Transformation Process

- **Status:** Canonical Candidate
- **Responsibility hypothesis:** Process centered on transformation of inputs toward changed outputs/results.
- **Reason not promoted:** Potential overlap with generic Process, Processing Activity, computational transformation, and domain-specific transformation semantics.
- **Reconsideration trigger:** A distinct reusable responsibility and interoperability need is demonstrated without duplicating existing Process/Activity semantics.

### R-PRO-C02 — Development Process

- **Status:** Canonical Candidate
- **Responsibility hypothesis:** Organized progression toward development, construction, maturation, or improvement.
- **Reason not promoted:** Strong domain dependence and possible overlap with lifecycle, engineering development, software development, research progression, or biological process semantics.
- **Reconsideration trigger:** Stable cross-domain definition and independently validated boundary established.

### R-PRO-C03 — Operational Process

- **Status:** Canonical Candidate
- **Responsibility hypothesis:** Controlled or repeatable operational course in a runtime, production, or service context.
- **Reason not promoted:** Generic Process frequently carries the same semantics; operational terminology is domain and organizationally variable.
- **Reconsideration trigger:** A distinct semantic responsibility becomes necessary for interoperability or cross-domain canonicalization.

### R-PRO-C04 — Workflow Process

- **Status:** Canonical Candidate
- **Responsibility hypothesis:** Explicitly organized sequence/graph of activities and execution stages.
- **Reason not promoted:** Workflow may denote a process, process model, procedure, automation artifact, or representation.
- **Reconsideration trigger:** Evidence establishes a stable semantic concept distinct from Procedure, Process Model, Representation, and realized Process.

## Routed / Non-Canonical Records

| Term | Decision | Destination |
|---|---|---|
| Processing | Existing Activity responsibility | `activities` |
| Execution | Existing Activity responsibility | `activities` |
| Procedure | Separate specification responsibility | Future/applicable semantic layer |
| Result | Separate output/result responsibility | Applicable semantic layer |
| Workflow document | Representation/artifact | `representations` |
| Process diagram | Representation of process information | `representations` |
| Algorithm | Computational method | Applicable semantic layer |
| Software | Implementation artifact | Applicable semantic layer |
| Project | Organizational endeavor | Applicable semantic layer |

## Evidence and Epistemic Controls

The registry distinguishes source statements, recovered knowledge, evidence, inference, semantic synthesis, implementation observations, historical statements, and canonical decisions.

`VERIFIED ≠ CANONICAL`  
`NON-CANONICAL ≠ FALSE`  
`DEFERRED ≠ DELETED`  
`FILTERED ≠ DISCARDED`

A source definition may support a candidate without determining GIOP identity. Canonical status requires GIOP semantic classification, boundary validation, and promotion.

## Visitor Universe Rule

Visitor Universe information is retained only as routing/entry-depth metadata where useful. No visitor-specific Process records are created.

## Reconsideration Triggers

Reopen or promote Process semantics only when one or more of the following is established:

1. a material semantic boundary failure;
2. a demonstrable duplicate or missing responsibility;
3. a new interoperability requirement;
4. materially stronger authoritative evidence;
5. a specialized candidate becomes independently reusable and cross-domain stable;
6. an existing Activity/Process distinction becomes insufficient for a validated use case.

## Registry Integrity Rule

The registry must not become a second authoring location for canonical Process definitions. Canonical meaning is authoritative in the semantic entry; the registry records why the concept was retained, routed, deferred, or promoted.
