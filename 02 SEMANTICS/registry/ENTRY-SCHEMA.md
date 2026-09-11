# GIOP Semantic Registry Entry Schema

## Purpose

This schema defines the minimum structure of a GIOP registry record. Registry records preserve recovered knowledge, evidence, semantic classification, routing, and canonicalization decisions without duplicating the canonical semantic document.

The schema implements the project-wide knowledge-entry rule:

`LEARN → RETAIN → CLASSIFY → VERIFY → RECONCILE → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE → RELATE`

A registry record normally represents the retained and evaluated stages before, during, or immediately after canonical authorship.

## Required Record Structure

```yaml
id: TERM-EXAMPLE-001
label: Example Term

source_status: RECOVERED

epistemic_status: VERIFIED

semantic_type:
  primary: PROPERTY
  secondary: []

canonical_status: CANONICAL CANDIDATE

destination:
  layer: properties/
  path: null

definition_or_recovered_claim: >-
  Concise statement of the recovered concept or claim.

evidence:
  - source: SOURCE-ID-001
    type: STANDARD
    claim: >-
      Concise evidence-bearing claim.

verification:
  decision: VERIFIED
  basis: >-
    Why the recorded claim or semantic interpretation is sufficiently supported.

reconciliation:
  conflicts: []
  semantic_boundary: >-
    Boundary separating this concept from adjacent concepts.

canonical_decision:
  accepted: false
  rationale: >-
    GIOP-specific semantic decision.

reconsideration:
  allowed: true
  trigger: >-
    Condition under which the decision should be revisited.
```

## Field Rules

### `id`

Stable registry identifier. It MUST remain stable across ordinary editorial updates.

### `label`

The primary recovered or evaluated term. Synonyms SHOULD be recorded separately when needed.

### `source_status`

Initial provenance state, normally `RECOVERED`. It records origin state and MUST NOT replace `epistemic_status`.

### `epistemic_status`

One of:

`UNVERIFIED` | `UNDER VERIFICATION` | `VERIFIED` | `CONFLICTED`

### `semantic_type`

`primary` identifies the best current semantic classification. `secondary` MAY contain additional classifications when the concept genuinely crosses a boundary or remains under reconciliation.

Secondary classification MUST NOT be used to avoid making a necessary primary semantic decision indefinitely.

### `canonical_status`

One of:

`NOT CANONICAL` | `CANONICAL CANDIDATE` | `CANONICAL` | `NON-CANONICAL` | `REJECTED-HISTORICAL`

### `destination`

Records where the concept is routed, considered for routing, or intentionally deferred. A concrete destination path SHOULD be populated when a canonical document exists.

### `definition_or_recovered_claim`

A concise GIOP registry statement. Source text SHOULD NOT be copied wholesale.

### `evidence`

Evidence entries identify sources and the claims supported by those sources. Sources provide evidence; they do not automatically become GIOP canonical definitions.

### `verification`

Records the evidence assessment and resulting epistemic decision.

### `reconciliation`

Records material conflicts, adjacent concepts, and the semantic boundary used in the decision.

### `canonical_decision`

Records the GIOP-specific admission or routing decision. A technically verified concept may still have `accepted: false` for a particular layer.

### `reconsideration`

Records whether and why the decision may later be revisited. Deferred knowledge is therefore recoverable rather than discarded.

## Knowledge-Entry Rules

1. Search the existing canonical and registry corpus before creating a new record.
2. If the concept already exists, update or relate the existing record rather than creating an unnecessary duplicate.
3. Retain newly recovered knowledge before deciding its canonical destination.
4. Classify the semantic responsibility before authoring canonical content.
5. Verify the relevant claim and the semantic abstraction separately where necessary.
6. Keep conflicting evidence visible until reconciliation is complete.
7. Make the GIOP semantic decision explicitly; do not let source terminology make the decision implicitly.
8. Route the concept to the correct semantic layer or explicitly defer it.
9. Only after the semantic decision should canonical content be created or updated.
10. Validate the resulting canonical entry against the applicable Foundation and layer-specific standard.
11. Add relevant relations, provenance, lifecycle, and retrieval anchors required by the destination standard.
12. Preserve the registry record so the decision remains auditable.

## Semantic Safety Rules

1. `VERIFIED` MUST NOT imply `CANONICAL`.
2. `CANONICAL` MUST NOT imply that an external source is authoritative for all GIOP use.
3. `NON-CANONICAL` MUST NOT be interpreted as `FALSE`.
4. `DEFERRED/UNRESOLVED` MUST remain discoverable.
5. A term excluded from one layer SHOULD carry its intended semantic destination when known.
6. Numerical values, measured results, implementation claims, and vendor-specific specifications MUST NOT be silently converted into general semantic concepts.
7. Registry records SHOULD remain decision-oriented; detailed canonical exposition belongs in the destination layer.
8. A registry record MUST NOT become a substitute for the canonical semantic entry once canonical admission occurs.

## Example: Verified but Not a Property

```yaml
id: TERM-RESOLUTION-001
label: Resolution
source_status: RECOVERED
epistemic_status: VERIFIED
semantic_type:
  primary: QUANTITY
  secondary:
    - MEASUREMENT
canonical_status: NON-CANONICAL
destination:
  layer: deferred/
  path: null
canonical_decision:
  accepted: false
  rationale: >-
    Verified technical concept, but not admitted as a canonical Property
    because its imaging meaning is measurement-oriented and its scope spans
    multiple resolution dimensions.
reconsideration:
  allowed: true
  trigger: >-
    A future GIOP quantity/measurement model may define a stable canonical
    destination.
```

The example illustrates the intended distinction: **retained knowledge, explicit verification, explicit semantic routing, and no knowledge deletion**.

## Relationship to Canonical Entry Standards

The registry schema is deliberately lighter than a canonical semantic entry. It records the evidence and decision pathway; it does not reproduce the destination entry's full 5W1H orientation, technical exposition, trust treatment, lifecycle explanation, or retrieval structure.

When a registry item becomes canonical, the destination entry MUST follow the standard established for that semantic layer. Registry structure and canonical content structure therefore remain complementary rather than identical.
