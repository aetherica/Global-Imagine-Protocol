# Attachment — Analysis Specification

**Status:** CANDIDATE — NOT CANONICAL  
**Folder:** `02 SEMANTICS/attachment/`  
**Semantic role:** bounded candidate routed to the existing Relation layer.

## Analysis Objective

Determine whether “Attachment” has an independently useful semantic responsibility in GIOP V3.1 without creating a duplicate of Relation, Activity, Process, State, Representation, Garment, or other established layers.

## Research Dimensions

1. Formal and domain ontologies: physical attachment/joint modeling and object-assembly semantics.
2. Cultural-heritage semantics: attachment/integration of components and continuity of identifiable objects.
3. Biomedical/psychological terminology: non-physical attachment meanings used to test lexical non-collapse.
4. Metadata and web vocabularies: generic resource relations and digital attachment semantics.
5. Imaging and engineering practice: mounting, fastening, joining, adhesion, and visible component coupling.
6. GIOP internal architecture: existing Relation, part-of, participates-in, Activity, Process, State, Representation, Textile, Garment, and BIL boundaries.

## Competing Interpretations

### Interpretation A — Attachment as a universal entity/class
Rejected. The term frequently names a relationship or a domain-specific phenomenon, not a stable GIOP class of bearer.

### Interpretation B — Attachment as a canonical relation predicate
Not admitted in this phase. The Relation layer is already closed for its current seed, and a new predicate cannot be introduced silently.

### Interpretation C — Attachment as an Activity/Process
Rejected as the primary responsibility. Attaching is an operation; the candidate describes the resulting or asserted relationship. The operation routes to Activity/Process/Workflow.

### Interpretation D — Attachment as a Relation-layer candidate pattern
Retained. This provides a bounded semantic intake point while preserving the closed Relation authority and avoiding a duplicate ontology layer.

### Interpretation E — Attachment as a digital/file concept
Rejected as the general meaning. File and message attachments belong to representation, packaging, implementation, or application metadata depending context.

### Interpretation F — Attachment as psychological/social bonding
Rejected from this folder. It is a separate domain meaning and must not be conflated with physical/configurational attachment.

## Semantic Ownership Decision

Primary ownership is **Relation-layer candidate responsibility** for physical/configurational attachment. The folder is an intake and boundary artifact, not proof that Attachment has become a canonical layer.

## Candidate Universe

Retain as examples rather than automatically promoted concepts:

- strong physical attachment
- weak physical attachment
- mounting
- fastening
- binding
- adhesion
- joining
- jointing
- integration of a component
- attachment point

These terms may encode different entities, properties, processes, or relations and require independent treatment before promotion.

## Evidence Summary

The Attachment Ontology literature explicitly models physical attachment types such as strong and weak attachment as relational patterns. CIDOC CRM material models the addition/integration of parts through activities and resulting assemblages rather than making “attachment” a universal independent object. MeSH demonstrates that “Object Attachment” can denote a psychological phenomenon. W3C DCAT distinguishes a generic relation from more specific resource-linking relations. Together these sources support polysemy and boundary preservation rather than direct canonical promotion.

## GIOP Decision

`SEM-ATTACHMENT-CANDIDATE-001` remains **CANDIDATE — NOT CANONICAL**. No new relation predicate, semantic layer, visitor-specific record, or duplicate domain ontology is created.
