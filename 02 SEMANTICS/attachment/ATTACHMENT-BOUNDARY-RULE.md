# Attachment — Boundary Rule

**Status:** CANDIDATE — NOT CANONICAL

## Ownership Rule

Attachment is retained only as a bounded candidate relation pattern. The established Relation layer remains the semantic owner of relation concepts and relation assertions.

## Boundary Rules

1. **Do not create a new top-level semantic layer for Attachment.**
2. **Do not introduce a canonical predicate** such as `attached-to`, `attaches`, `mounts`, `fastened-to`, or `joined-to` without an independent Relation promotion pass.
3. `part-of` remains the authority for compositional inclusion; Attachment may coexist with part-of but does not replace it.
4. Attaching, mounting, fastening, sewing, gluing, welding, binding, or assembling as actions route to Activity/Process/Workflow.
5. Garment Fastening remains a Garment-domain candidate responsibility; it is not redefined as generic Attachment.
6. Textile joining, finishing, and construction remain in Textile or Process/Activity according to primary responsibility.
7. A current mode such as attached/detached may be represented through State when the semantic target is the configuration state rather than the relation itself.
8. A picture, scan, mesh, CAD model, metadata record, or file that depicts or records an attachment belongs to Representation; it is not itself the attachment relation.
9. Evidence that supports an attachment claim is distinct from the claim, relation, provenance, and validation decision.
10. Psychological/social attachment and other non-physical meanings are excluded.
11. Digital/file attachment is excluded from the physical candidate and must route according to representation, packaging, implementation, or application semantics.
12. BIL may evaluate whether an attachment-related configuration affects integrity, but BIL does not own Attachment semantics.

## Non-Collapse Tests

- Attachment ≠ Part-of
- Attachment ≠ Relation assertion
- Attachment ≠ Activity
- Attachment ≠ Process
- Attachment ≠ State
- Attachment ≠ Representation
- Attachment ≠ Garment Fastening
- Attachment ≠ Psychological Attachment
- Attachment ≠ File Attachment
- Attachment ≠ Evidence
- Attachment ≠ Integrity Decision

## Promotion Gate

Any future promotion requires an explicit scope demonstrating that the candidate adds reusable semantic value beyond the current Relation seed and cannot be handled as a controlled relation subtype, domain-specific concept, or context-qualified assertion. Until then, the candidate remains non-canonical.
