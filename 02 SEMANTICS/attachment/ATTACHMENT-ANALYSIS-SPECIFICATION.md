# Physical Attachment — Analysis Specification

**Status:** CANDIDATE — NOT CANONICAL  
**Folder:** `02 SEMANTICS/attachment/`  
**Semantic role:** bounded candidate routed to the existing Relation layer.  
**Version:** 0.2.0

## Analysis Objective

Determine whether the physical sense of “Attachment” has independently useful semantic responsibility in GIOP V3.1 without creating a duplicate of Relation, Activity, Process, State, Representation, Garment, Textile, Anatomy, or other established responsibilities.

## Research Dimensions

1. Formal and domain ontologies: physical attachment, connectedness, mereotopology, and object-assembly semantics.
2. Engineering and industrial modelling: mounting, fastening, joining, realizing elements, joints, and connection mechanisms.
3. Biomedical/anatomical terminology: physical attachment versus attachment sites/structures and non-physical lexical meanings.
4. Cultural-heritage semantics: incorporation, assembly, attached features, and identifiable physical objects.
5. Metadata, web, and communication standards: digital/file attachment and resource-association semantics.
6. Imaging and reconstruction practice: visible component coupling, observation, evidence, and representation boundaries.
7. GIOP internal architecture: existing Relation, `part-of`, Activity, Process, State, Representation, Textile, Garment, and BIL boundaries.
8. Logical-property analysis: symmetry, inverse, transitivity, reflexivity, cardinality, and temporal qualification.

## Competing Interpretations

### Interpretation A — Attachment as a universal entity/class

Rejected. The bare term is polysemous and frequently names a relationship, operation, domain structure, device, or digital datatype rather than a stable universal bearer class.

### Interpretation B — Attachment as a canonical relation predicate

Not admitted in this phase. The Relation layer is already closed for its current seed, and external ontology predicates do not automatically become GIOP predicates.

### Interpretation C — Attachment as an Activity/Process

Rejected as primary responsibility. Attaching, mounting, fastening, sewing, gluing, welding, or assembling are operations. The candidate describes the resulting or asserted physical/configurational relationship.

### Interpretation D — Physical Attachment as a Relation-layer candidate pattern

Retained. This provides a bounded semantic intake point while preserving the closed Relation authority and avoiding a duplicate ontology layer.

### Interpretation E — Attachment as a digital/file concept

Rejected as the general physical meaning. File/message attachments belong to representation, packaging, implementation, or application semantics according to context.

### Interpretation F — Attachment as psychological/social bonding

Rejected from this folder. It is a distinct non-physical domain meaning.

### Interpretation G — Attachment as an attachment site, structure, or device

Rejected as the generic relation identity. Anatomical attachment sites/structures and engineering attachment devices are entities or domain-specific concepts and require independent ownership.

## Semantic Ownership Decision

Primary ownership is **Relation-layer candidate responsibility** for physical/configurational attachment. The folder is an intake, synthesis, and boundary artifact, not proof that Physical Attachment has become a canonical layer or predicate.

## Candidate Universe

Retain as controlled examples rather than automatically promoted concepts:

- strong physical attachment
- weak physical attachment
- mounting
- fastening
- binding
- adhesion
- joining
- jointing
- structural integration
- attachment point
- attachment site

These terms may encode different relations, entities, properties, processes, locations, or domain-specific structures and require independent treatment before promotion.

## Formal Boundary Findings

External formalizations support a relational interpretation of physical attachment and distinguish it from broader connectedness. However, GIOP does not inherit external logical axioms automatically.

- Symmetry: unresolved.
- Inverse relation: unresolved.
- Transitivity: not assumed.
- Reflexivity: not assumed.
- Cardinality: not canonically constrained.
- Temporal validity: context-dependent and separately qualified.

In particular, `A attached-to B` plus `B attached-to C` does not by itself entail `A attached-to C`.

## Evidence Summary

The Attachment Ontology literature explicitly models physical attachment types such as strong and weak attachment as relational patterns. OBO Relation Ontology provides an external `attached to` relation and broader connectedness hierarchy. IFC engineering models distinguish connection relationships from realizing elements. CIDOC CRM distinguishes physical features, component structures, and activities that incorporate or alter physical objects. Biomedical sources demonstrate that attachment may also denote anatomical sites or non-physical phenomena. IETF/FHIR and web metadata standards demonstrate separate digital meanings. Together these sources support a scoped physical relation candidate and strong lexical boundary preservation rather than automatic GIOP promotion.

## GIOP Decision

`SEM-ATTACHMENT-CANDIDATE-001` remains **CANDIDATE — NOT CANONICAL**. Preferred name is **Physical Attachment**; bare “Attachment” is retained as a retrieval/alias form. No new relation predicate, semantic layer, visitor-specific record, or duplicate domain ontology is created.
