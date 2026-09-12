# BIL Implementation Data Schema

Status: ACTIVE PREPARATION STANDARD — V3.1

Every discovered BIL topic/case is represented first as a candidate record rather than immediately becoming a semantic page.

## Required fields
- candidate_id
- preferred_term
- aliases
- subject_scope
- profile/context
- integrity_dimension
- reference_scope
- claim_scope
- existing_giop_owner
- bil_native_candidate
- evidence_family
- observability
- permitted_variation
- deviation/drift relevance
- validation_method
- result/decision form
- provenance
- confidence/uncertainty
- conflict status
- lifecycle state
- visitor-depth projections
- retrieval anchors
- unresolved questions

## Controlled classification
NATIVE = candidate has unique BIL responsibility.
ROUTED = semantics belong to an existing GIOP layer; BIL consumes them.
PROFILE = application/context specialization only.
METHOD = algorithm, metric or implementation mechanism.
EVIDENCE = information source rather than semantic owner.
EXTERNAL = domain knowledge maintained outside BIL.
DEFERRED = insufficient evidence for canonicalization.

## Core invariant
The same candidate meaning must survive D0–D4 Visitor Universe projection. Only explanatory depth, navigation, examples and formal exposure may change.
