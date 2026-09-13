# Physical Attachment — Cross-Layer Validation

**Status:** CANDIDATE — NOT CANONICAL  
**Version:** 0.2.0

## Validation Matrix

| Question | Required routing | Physical Attachment decision |
|---|---|---|
| Is the target a physical/configurational coupling between identifiable bearers? | Relation | Retain as Physical Attachment candidate pattern. |
| Is the target a generic typed connection without attachment-specific semantics? | Relation | Do not force the Attachment candidate; use existing Relation responsibility. |
| Is the target a compositional inclusion? | Relation `part-of` | Use existing authority; do not substitute Physical Attachment. |
| Is the target mere proximity, adjacency, or contact? | Context / spatial or other responsible layer | Do not infer Physical Attachment automatically. |
| Is the target an operation that establishes, changes, or removes a connection? | Activity / Process / Workflow | Route operation semantics outward. |
| Is the target a current configuration state? | State | Route state semantics outward. |
| Is the target a fastener, joint, bracket, mount, clamp, adhesive, stitch, or weld as an entity/mechanism? | Class / domain-specific mechanism | Do not collapse the mechanism into Physical Attachment. |
| Is the target a garment securing mechanism or garment-specific construction? | Garment | Use Garment candidate/domain semantics. |
| Is the target a textile construction/finishing operation? | Textile + Activity / Process | Route by primary responsibility. |
| Is the target an attachment site/structure? | Domain-specific Class / Anatomy / spatial responsibility | Do not collapse the site/structure into Physical Attachment. |
| Is the target a picture, mesh, scan, drawing, CAD model, or file recording attachment? | Representation | Representation owns the information-bearing form. |
| Is the target evidence for an attachment claim? | Evidence / provenance / validation | Keep evidence separate from the claimed relationship. |
| Is the target psychological/social attachment? | External domain | Do not route into this candidate. |
| Is the target a digital file/message attachment? | Representation / Packaging / Implementation | Do not collapse with physical attachment. |
| Is the target an integrity assessment of attachment? | BIL | BIL may assess; it does not own Physical Attachment. |

## Relation Authority Check

No predicate beyond the admitted relation authority is introduced. Existing canonical relations remain `part-of`, `participates-in`, `observes`, `represents`, `derived-from`, and `has-result`.

External `attached to` terminology is evidence for candidate relational semantics only. It is not imported as a GIOP canonical predicate.

## Logical Safety Check

No symmetry, inverse, transitivity, reflexivity, or cardinality axiom is assumed. In particular, two chained attachment assertions do not automatically yield an attachment assertion between the outer bearers. Temporal validity may qualify a claim without changing the relation identity.

## Validation Outcome

The candidate is internally coherent as a bounded semantic intake and boundary object. The preferred semantic identity is **Physical Attachment**, with bare “Attachment” retained as a retrieval/alias form. Canonical promotion is not justified in this phase because the physical pattern can remain under existing Relation authority and the lexical term has multiple non-physical and non-relational meanings.
