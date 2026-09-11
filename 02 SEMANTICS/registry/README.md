# GIOP Semantic Knowledge Registry

## Purpose

The `registry/` directory preserves recovered and evaluated semantic knowledge that has not necessarily been admitted to a canonical semantic layer.

Its purpose is **knowledge retention without semantic inflation**.

The registry prevents GIOP from losing useful terminology, technical concepts, measurements, standards-derived concepts, unresolved candidates, or rejected layer placements merely because they are not yet canonical members of a particular semantic vocabulary.

The registry is therefore not a second canonical ontology and not a replacement for the semantic layer directories.

## Governing Principle

> **Knowledge must not be discarded merely because it is not yet canonical. It must be retained with an explicit semantic classification, epistemic status, evidence state, and canonical decision.**

The canonical semantic layers remain authoritative for GIOP's synthesized semantics. The registry records the evidence and decisions that explain how recovered knowledge was evaluated and where it belongs.

## Separation of Concerns

GIOP keeps three dimensions explicitly separate:

1. **Epistemic status** — how well the knowledge is supported.
2. **Semantic type** — what kind of concept the item is.
3. **Canonical status** — whether and where GIOP admits the item as canonical.

These dimensions MUST NOT be collapsed into a single status field.

For example, a term may be:

`VERIFIED + QUANTITY + NON-CANONICAL-FOR-PROPERTY-LAYER`

without being false, discarded, or globally non-canonical.

## Epistemic Status

The registry uses the following controlled values:

- `UNVERIFIED` — recovered or proposed, but not yet externally verified sufficiently for a GIOP semantic decision.
- `UNDER VERIFICATION` — active verification is in progress.
- `VERIFIED` — the relevant claim or technical concept has sufficient supporting evidence for the recorded decision.
- `CONFLICTED` — credible evidence conflicts materially and has not yet been reconciled.

Epistemic verification applies to the recorded claim or semantic interpretation, not automatically to every assertion made by an external source.

## Semantic Type

The registry may classify an item as one or more of the following controlled semantic types:

`CLASS`

`PROPERTY`

`QUANTITY`

`VALUE`

`STATE`

`STATUS`

`CONDITION`

`RELATION`

`ACTIVITY`

`PROCESS`

`REPRESENTATION`

`PERCEPTION`

`MODEL`

`FORMULA`

`RESULT`

`CAPABILITY`

`PHENOMENON`

`STANDARD`

`IMPLEMENTATION`

`WORKFLOW`

`CLAIM`

`HISTORICAL`

`POLICY/GOVERNANCE`

`DEFERRED/UNRESOLVED`

These are classification categories, not a claim that every category is already a fully implemented canonical GIOP layer.

## Canonical Status

The registry records a separate canonical decision:

- `NOT CANONICAL` — no canonical admission decision yet.
- `CANONICAL CANDIDATE` — semantically plausible and under canonical evaluation.
- `CANONICAL` — admitted to a defined GIOP canonical semantic destination.
- `NON-CANONICAL` — explicitly retained as knowledge but not admitted as a GIOP canonical concept in the evaluated scope.
- `REJECTED-HISTORICAL` — retained only because it has historical, provenance, or audit value and is not an active semantic candidate.

`NON-CANONICAL` MUST always be interpreted together with the recorded destination and rationale. It does not mean false, useless, or deleted.

## Destination

Each registry entry SHOULD identify the intended or considered semantic destination.

Examples:

- `properties/`
- `quantities/`
- `states/`
- `statuses/`
- `conditions/`
- `activities/`
- `processes/`
- `relations/`
- `representations/`
- `results/`
- `capabilities/`
- `registry/deferred/`
- another explicitly defined semantic domain

A destination is a routing decision. It is not itself the semantic definition.

## Verification and Canonicalization Workflow

The registry follows the GIOP recovery workflow:

`RECOVER → CLASSIFY → RESEARCH → VERIFY → RECONCILE → SEMANTICALLY SYNTHESIZE → CANONICALIZE`

The following rules apply:

1. Recovered knowledge MUST be retainable before canonicalization.
2. A source term MUST NOT become canonical solely because the term is familiar or technically common.
3. Verification of a term MUST be distinguished from verification of the semantic abstraction assigned to that term.
4. Conflicting evidence MUST remain visible until reconciled.
5. External sources provide evidence; the GIOP canonical document is an independent semantic synthesis.
6. A concept excluded from one semantic layer MUST remain discoverable through its registry record and destination decision.
7. A deferred concept MAY later be promoted to a canonical layer without reconstructing the original research from scratch.

## Evidence Model

Each entry SHOULD record:

- source or recovered origin;
- evidence type;
- relevant claim;
- semantic interpretation;
- verification state;
- conflicts or unresolved boundaries;
- GIOP reconciliation;
- canonical decision;
- destination;
- rationale;
- reconsideration conditions where applicable.

The registry SHOULD prefer concise evidence summaries and stable source identifiers over copied source text.

## Property-Layer Protection

The registry exists in part to protect the `properties/` layer from absorbing concepts that belong elsewhere.

A technically important term MAY therefore remain fully retained while being deliberately excluded from `properties/`.

Examples include measurement-oriented concepts such as `resolution`, quantitative concepts such as `reflectance` or `transmittance`, activity/process concepts such as `calibration` or `measurement`, and state/status concepts such as `calibration-status`.

Such exclusion is a semantic routing decision, not knowledge deletion.

## Machine Interpretation

Registry records MUST be deterministic enough for machine processing.

A machine MUST be able to distinguish at minimum:

`epistemic_status`

`semantic_type`

`canonical_status`

`destination`

`evidence`

`decision`

A machine MUST NOT infer that `NON-CANONICAL`, `DEFERRED`, or `UNVERIFIED` means `FALSE`.

## Relationship to Canonical Semantic Layers

Canonical semantic directories remain the authoritative published semantic surface. The registry records the evaluation history and retained knowledge that supports those canonical layers.

Canonical content SHOULD link back to relevant registry records when traceability materially improves trust, while registry entries SHOULD link forward to the canonical destination when admission has occurred.

The registry MUST NOT become a parallel duplicate of the canonical ontology.

## Lifecycle

Registry entries may progress through:

`RECOVERED → CLASSIFIED → UNDER VERIFICATION → VERIFIED → RECONCILED → CANONICALIZED`

or remain in an unresolved branch such as:

`RECOVERED → CONFLICTED`

`RECOVERED → DEFERRED`

`RECOVERED → VERIFIED → NON-CANONICAL-FOR-EVALUATED-LAYER`

Historical records MUST NOT be silently rewritten to make an earlier decision appear to have been different. Material semantic changes should create an auditable new decision state or updated entry version according to the project documentation and release policies.

## Visitor Universe Compatibility

The registry supports the canonical model:

`CANONICAL KNOWLEDGE → VISITOR UNIVERSE → ENTRY DEPTH → HUMAN / MACHINE CONSUMPTION`

Different visitors may need visibility into different evidence depths, unresolved states, or semantic destinations, but they do not receive contradictory underlying knowledge.

The registry therefore supports deeper evidence-oriented entry paths without fragmenting canonical knowledge into separate visitor-specific ontologies.

## Boundary

The registry does not:

- define a new universal ontological class system;
- replace canonical semantic layers;
- certify external claims automatically;
- turn every recovered term into a GIOP concept;
- treat every technical term as a Property;
- erase uncertainty or disagreement;
- store arbitrary research notes without semantic identity or provenance.

## Initial Scope

The first operational use of the registry is the Property-layer recovery and classification work. The initial corpus SHOULD retain all previously recovered property candidates, including candidates deliberately routed to quantities, measurement concepts, activities, processes, states/statuses, capabilities, or deferred evaluation.

The registry may later support the same retention and routing discipline for other semantic layers without changing this governing model.
