# GIOP Semantic Registry Entry Schema

## Purpose

This schema defines the minimum structure for a registry record. It is intentionally compact so that registry records preserve decisions and provenance without duplicating canonical semantic documents.

## Required Fields

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

Initial provenance state, normally `RECOVERED`. This field records the origin state and MUST NOT replace `epistemic_status`.

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

Records where the concept is routed, considered for routing, or intentionally deferred. A destination path SHOULD be populated only when a concrete canonical document exists.

### `definition_or_recovered_claim`

A concise GIOP registry statement. Source text SHOULD NOT be copied wholesale.

### `evidence`

Evidence entries identify the source and the claim supported by that source. Sources are evidence; they are not automatically GIOP canonical definitions.

### `verification`

Records the evidence assessment and the resulting epistemic decision.

### `reconciliation`

Records material conflicts, adjacent concepts, and the boundary used in the semantic decision.

### `canonical_decision`

Records the GIOP-specific admission decision. A technically verified concept may still have `accepted: false` for a particular layer.

### `reconsideration`

Records whether and why the decision may later be revisited. Deferred knowledge is therefore recoverable rather than discarded.

## Semantic Safety Rules

1. `VERIFIED` MUST NOT imply `CANONICAL`.
2. `CANONICAL` MUST NOT imply that the underlying external source is itself authoritative for all GIOP use.
3. `NON-CANONICAL` MUST NOT be interpreted as `FALSE`.
4. `DEFERRED/UNRESOLVED` MUST remain discoverable.
5. A term excluded from `properties/` SHOULD carry its intended semantic destination when known.
6. Numerical values, measured results, implementation claims, and vendor-specific specifications MUST NOT be silently converted into general Property concepts.
7. Registry records SHOULD remain decision-oriented; detailed canonical exposition belongs in the destination layer.

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
