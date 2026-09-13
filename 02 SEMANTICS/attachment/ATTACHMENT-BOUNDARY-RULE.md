# Physical Attachment — Boundary Rule

**Status:** CANDIDATE — NOT CANONICAL  
**Version:** 0.2.0

## Ownership Rule

Physical Attachment is retained only as a bounded candidate relation pattern. The established Relation layer remains the semantic owner of relation concepts and relation assertions.

## Boundary Rules

1. **Do not create a new top-level semantic layer for Physical Attachment.**
2. **Do not introduce a canonical predicate** such as `attached-to`, `attaches`, `mounts`, `fastened-to`, or `joined-to` without an independent Relation promotion pass.
3. `part-of` remains the authority for compositional inclusion; Physical Attachment may coexist with part-of but does not replace it or inherit its inference rules.
4. Mere proximity, adjacency, or contact is not automatically Physical Attachment.
5. Attaching, mounting, fastening, sewing, gluing, welding, binding, or assembling as actions route to Activity/Process/Workflow.
6. Fasteners, joints, brackets, mounts, clamps, adhesives, stitches, and welds as entities or mechanisms are not themselves the Physical Attachment relation.
7. Garment Fastening remains a Garment-domain candidate responsibility; it is not redefined as generic Physical Attachment.
8. Textile joining, finishing, and construction remain in Textile or Process/Activity according to primary responsibility.
9. A current mode such as attached/detached may be represented through State when the semantic target is the configuration state rather than the relation itself.
10. A picture, scan, mesh, CAD model, drawing, metadata record, or file that depicts or records an attachment belongs to Representation; it is not itself the attachment relation.
11. Evidence that supports an attachment claim is distinct from the claim, relation, provenance, and validation decision.
12. Attachment sites or attachment structures are domain-specific entities/locations and are not collapsed into the generic relation candidate.
13. Psychological/social attachment and other non-physical meanings are excluded.
14. Digital/file attachment is excluded from the physical candidate and must route according to representation, packaging, implementation, or application semantics.
15. BIL may evaluate whether an attachment-related configuration affects integrity, but BIL does not own Physical Attachment semantics.

## Logical-Property Safeguards

- Symmetry is **unresolved** and must not be assumed.
- An inverse predicate is **unresolved** and must not be introduced implicitly.
- Transitivity is **not assumed**.
- Reflexivity is **not assumed**.
- Cardinality is **not canonically constrained**.
- Temporal qualification may scope an attachment assertion but is not part of the candidate's identity.

## Non-Collapse Tests

- Physical Attachment ≠ Part-of
- Physical Attachment ≠ Generic Connection
- Physical Attachment ≠ Contact
- Physical Attachment ≠ Support
- Physical Attachment ≠ Integration
- Physical Attachment ≠ Activity
- Physical Attachment ≠ Process
- Physical Attachment ≠ State
- Physical Attachment ≠ Representation
- Physical Attachment ≠ Mechanism / Device
- Physical Attachment ≠ Garment Fastening
- Physical Attachment ≠ Attachment Site / Structure
- Physical Attachment ≠ Psychological Attachment
- Physical Attachment ≠ File Attachment
- Physical Attachment ≠ Evidence
- Physical Attachment ≠ Integrity Decision

## Promotion Gate

Any future promotion requires an explicit scope demonstrating reusable semantic value beyond the current Relation seed and showing why the pattern cannot be handled as an existing controlled relation, domain-specific concept, or context-qualified assertion. Formal logical characteristics must be independently decided before canonical predicate admission. Until then, the candidate remains non-canonical.
