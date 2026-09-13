# Attachment — Cross-Layer Validation

**Status:** CANDIDATE — NOT CANONICAL

## Validation Matrix

| Question | Required routing | Attachment decision |
|---|---|---|
| Is the target a generic typed connection? | Relation | Yes; Attachment remains a Relation candidate pattern. |
| Is the target a compositional inclusion? | Relation `part-of` | Use existing authority; do not substitute Attachment. |
| Is the target an operation that establishes a connection? | Activity / Process / Workflow | Route operation semantics outward. |
| Is the target a current configuration state? | State | Route state semantics outward. |
| Is the target a garment securing mechanism? | Garment | Use Garment Fastening candidate/domain semantics. |
| Is the target a textile construction/finishing operation? | Textile + Activity / Process | Route by primary responsibility. |
| Is the target a picture, mesh, scan, drawing, or file recording attachment? | Representation | Representation owns the information-bearing form. |
| Is the target evidence for an attachment claim? | Evidence / provenance / validation | Keep evidence separate from the claimed relationship. |
| Is the target psychological/social attachment? | External domain | Do not route into this candidate. |
| Is the target a digital file/message attachment? | Representation / Packaging / Implementation | Do not collapse with physical attachment. |
| Is the target an integrity assessment of attachment? | BIL | BIL may assess; it does not own Attachment. |

## Relation Authority Check

No predicate beyond the admitted relation authority is introduced. Existing canonical relations remain `part-of`, `participates-in`, `observes`, `represents`, `derived-from`, and `has-result`.

## Validation Outcome

The candidate is internally coherent as a bounded semantic intake and boundary object. Canonical promotion is **not** justified by the current evidence because the term is polysemous and its physical sense can be represented through the existing Relation responsibility without creating an additional canonical namespace.
