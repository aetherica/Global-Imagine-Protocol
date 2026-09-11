# GIOP Semantic Knowledge Registry

## Purpose

The `registry/` directory preserves recovered, evaluated, unresolved, routed, and canonicalization-related semantic knowledge without turning every recovered item into a canonical concept.

Its governing purpose is **knowledge retention without semantic inflation**.

The registry is a decision and traceability layer between research/recovery and canonical semantic authorship. It is not a second canonical ontology and not a replacement for the semantic layer directories.

## Governing Principle

> **New knowledge is not admitted directly into the canonical knowledge base. It is retained, classified, verified, reconciled, semantically synthesized, and explicitly decided before canonical authorship.**

The operational loop is:

`LEARN → RETAIN → CLASSIFY → VERIFY → RECONCILE → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE`

For registry work, this is represented as:

`RECOVERED KNOWLEDGE → REGISTRY RECORD → CLASSIFY → VERIFY → RECONCILE → SEMANTIC DECISION → CANONICAL DESTINATION`

The registry therefore preserves the reasoning that connects recovered knowledge to canonical semantic content.

## Separation of Concerns

GIOP keeps these dimensions explicitly separate:

1. **Epistemic status** — how well the recorded knowledge or interpretation is supported.
2. **Semantic type** — what kind of semantic concept the item represents.
3. **Canonical status** — whether GIOP admits it as canonical, and where.
4. **Evidence/provenance** — where the knowledge came from and what claim the evidence supports.
5. **GIOP decision** — the independent semantic conclusion reached after evaluation.

These dimensions MUST NOT be collapsed into a single status field.

For example:

`VERIFIED + QUANTITY + NON-CANONICAL-FOR-PROPERTY-LAYER`

does not mean false, discarded, or globally non-canonical.

## Registry Entry Principle

Every substantive registry record MUST answer, at minimum:

- What knowledge was recovered or evaluated?
- What semantic type is currently assigned?
- What evidence supports the recorded interpretation?
- What uncertainty or conflict remains?
- What GIOP semantic boundary was applied?
- What canonical decision was made?
- Where should the knowledge go, or why is it deferred?
- Under what conditions may the decision be reconsidered?

A registry record is therefore a **decision-oriented semantic record**, not a research-note dump.

Detailed canonical exposition belongs in the destination semantic layer. Detailed source material belongs in its appropriate evidence or research location. The registry retains the concise semantic decision and the traceability needed to reconstruct it.

## Epistemic Status

The registry uses the following controlled values:

- `UNVERIFIED` — recovered or proposed, but not yet sufficiently verified for a GIOP semantic decision.
- `UNDER VERIFICATION` — active verification is in progress.
- `VERIFIED` — the relevant claim or semantic interpretation has sufficient supporting evidence for the recorded decision.
- `CONFLICTED` — credible evidence conflicts materially and has not yet been reconciled.

Epistemic verification applies to the recorded claim or semantic interpretation, not automatically to every assertion made by an external source.

## Semantic Type

The registry may classify an item as one or more of the following controlled semantic types:

`CLASS` · `PROPERTY` · `QUANTITY` · `VALUE` · `STATE` · `STATUS` · `CONDITION` · `RELATION` · `ACTIVITY` · `PROCESS` · `REPRESENTATION` · `PERCEPTION` · `MODEL` · `FORMULA` · `RESULT` · `CAPABILITY` · `PHENOMENON` · `STANDARD` · `IMPLEMENTATION` · `WORKFLOW` · `CLAIM` · `HISTORICAL` · `POLICY/GOVERNANCE` · `DEFERRED/UNRESOLVED`

These are classification categories, not a claim that every category is already a fully implemented canonical GIOP layer.

## Canonical Status

The registry records a separate canonical decision:

- `NOT CANONICAL` — no canonical admission decision yet.
- `CANONICAL CANDIDATE` — semantically plausible and under canonical evaluation.
- `CANONICAL` — admitted to a defined GIOP canonical semantic destination.
- `NON-CANONICAL` — explicitly retained as knowledge but not admitted as a GIOP canonical concept in the evaluated scope.
- `REJECTED-HISTORICAL` — retained for historical, provenance, or audit value and not an active semantic candidate.

`NON-CANONICAL` MUST always be interpreted together with the recorded destination and rationale. It does not mean false, useless, or deleted.

## Destination

Each registry entry SHOULD identify the intended or considered semantic destination.

Examples include:

- `classes/`
- `properties/`
- `quantities/`
- `states/`
- `statuses/`
- `conditions/`
- `relations/`
- `activities/`
- `processes/`
- `representations/`
- `results/`
- `capabilities/`
- another explicitly defined semantic domain
- `deferred/unresolved`

A destination is a routing decision. It is not itself the semantic definition.

## Verification and Canonicalization Workflow

The registry follows the project-wide knowledge-entry rule:

`RECOVER → RETAIN → CLASSIFY → VERIFY → RECONCILE → SEMANTICALLY SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE`

The following rules apply:

1. Recovered knowledge MUST be retainable before canonicalization.
2. Existing canonical entries MUST be checked before proposing a new entry.
3. A new file MUST NOT be created merely because a new term was encountered.
4. A source term MUST NOT become canonical solely because it is familiar, frequent, or technically common.
5. Verification of a term MUST be distinguished from verification of the semantic abstraction assigned to it.
6. Conflicting evidence MUST remain visible until reconciled.
7. External sources provide evidence; GIOP canonical documents are independent semantic syntheses.
8. A concept excluded from one semantic layer MUST remain discoverable through its registry record and routing decision.
9. A deferred concept MAY later be promoted without reconstructing the original research from scratch.
10. Canonical authorship MUST preserve the established semantic responsibility and boundary of the destination folder.
11. After canonical authorship, the new or updated entry MUST pass the applicable Foundation validation requirements before it is treated as complete.
12. Relevant relations, provenance, lifecycle, and retrieval anchors MUST be connected where the destination standard requires them.

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

## Semantic Routing Protection

The registry protects canonical layers from absorbing concepts merely because they are technically important.

A concept MAY be fully verified and still be routed away from the layer currently under authoring. Examples include measurement-oriented concepts routed to quantities or measurement semantics, calibration routed to activity/process semantics, and calibration status routed to state/status semantics.

Such exclusion is a semantic routing decision, not knowledge deletion.

## Machine Interpretation

Registry records MUST be deterministic enough for machine processing.

At minimum, a machine MUST be able to distinguish:

`id` · `label` · `epistemic_status` · `semantic_type` · `canonical_status` · `destination` · `evidence` · `verification` · `reconciliation` · `canonical_decision` · `reconsideration`

A machine MUST NOT infer that `NON-CANONICAL`, `DEFERRED`, or `UNVERIFIED` means `FALSE`.

## Relationship to Canonical Semantic Layers

Canonical semantic directories remain the authoritative published semantic surface. The registry records the retained knowledge, evidence, routing, and decisions that support those canonical layers.

Canonical content SHOULD link back to relevant registry records when traceability materially improves trust. Registry entries SHOULD link forward to the canonical destination when admission has occurred.

The registry MUST NOT become a parallel duplicate of the canonical ontology.

## Visitor Universe Compatibility

The registry does not create visitor-specific knowledge bases or visitor-specific semantic records.

The governing visitor model remains:

`CANONICAL KNOWLEDGE → VISITOR UNIVERSE → ENTRY DEPTH → HUMAN / MACHINE CONSUMPTION`

Visitor Universe and Entry Depth determine how the same canonical knowledge may be entered and consumed. They do not alter registry semantics, canonical decisions, evidence states, or the underlying knowledge.

## Lifecycle

Registry entries may progress through:

`RECOVERED → CLASSIFIED → UNDER VERIFICATION → VERIFIED → RECONCILED → DECIDED → CANONICALIZED`

or remain in an unresolved branch such as:

`RECOVERED → CONFLICTED`

`RECOVERED → DEFERRED`

`RECOVERED → VERIFIED → NON-CANONICAL-FOR-EVALUATED-LAYER`

Historical records MUST NOT be silently rewritten to make an earlier decision appear to have been different. Material semantic changes SHOULD create an auditable new decision state or updated entry version according to the project documentation and release policies.

## Boundary

The registry does not:

- define a new universal ontological class system;
- replace canonical semantic layers;
- certify external claims automatically;
- turn every recovered term into a GIOP concept;
- treat every technical term as a Property;
- erase uncertainty or disagreement;
- store arbitrary research notes without semantic identity or provenance;
- create separate visitor-specific knowledge bases.

## Initial and Continuing Scope

The initial operational use of the registry was Property-layer recovery and classification. The same retention and routing discipline now applies to other semantic recovery work, including Context and Relation research.

The registry may support future semantic layers without changing this governing model.
