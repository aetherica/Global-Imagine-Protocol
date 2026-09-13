# Physical Attachment

**Semantic ID:** `SEM-ATTACHMENT-CANDIDATE-001`  
**Preferred Name:** Physical Attachment  
**Artifact Type:** Semantic Candidate / Relation-Routed Domain Entry  
**Primary Responsibility:** Candidate relation pattern for semantically relevant physical or configurational coupling between identifiable bearers.  
**Status:** CANDIDATE — NOT CANONICAL  
**Version:** 0.2.0  
**Authority:** GIOP V3.1 candidate governance; existing Relation authority remains unchanged.  
**Provenance:** Multi-dimensional multi-domain semantic synthesis; external sources are evidence, not GIOP authority.  
**Validation:** Final research and internal boundary analysis completed; independent Relation promotion review remains required.  
**Related IDs:** `SEM-RELATION-GENERIC-001` where applicable; `SEM-PROCESS-GENERIC-001`; relevant garment/textile candidates where applicable.

## 5W1H Orientation

### What

Physical Attachment denotes a candidate relation pattern in which identifiable physical bearers are coupled through an attachment relationship. The pattern may be realized by fastening, mounting, binding, adhesion, joining, structural coupling, or comparable mechanisms, but the mechanism is not the relation's identity. The folder does not establish Attachment as a new top-level GIOP ontology layer or as a canonical relation predicate.

### Why

The lexical term “attachment” occurs across physical-object modelling, engineering, anatomy, imaging, garments, cultural heritage, and digital systems. A bounded physical candidate is useful because several physical usages share a recognizable coupling pattern while differing in realization and domain vocabulary. Explicit scoping also prevents physical attachment from being confused with file/message attachment, psychological attachment, attachment sites, attachment devices, or generic compositional membership.

### Who

The concept is relevant to object and scene modelers, imaging scientists, engineers, garment and textile specialists, cultural-heritage modelers, robotics practitioners, archivists, computer-vision systems, metadata designers, and machine consumers that need to distinguish a physical attachment relationship from the operation, evidence, representation, or state associated with it. Non-physical meanings are outside this candidate's scope.

### Where

The candidate applies primarily to physical, configurational, and object-assembly contexts in which attachment can be evaluated as a relationship between identifiable bearers. Examples include a component mounted to a device, a garment component secured to another component, an artifact component coupled to an assemblage, or equipment attached to a support. Digital/file and psychological meanings are routed elsewhere according to semantic responsibility.

### When

Attachment is relevant when a physical/configurational coupling is asserted to exist or to have existed at a relevant time or state. Creation, modification, removal, or verification of the attachment is temporally and operationally distinct from the attachment relationship itself and routes to Activity, Process, Result, State, Evidence, or other responsible layers as appropriate.

### How

An attachment claim is established by identifying the participating bearers, the relevant connection circumstances, and sufficient evidence that the stated coupling exists or existed. Physical realizations may involve contact plus securing, jointing, fastening, adhesion, mounting, binding, or structural integration. The operation and mechanism that establish the connection are not encoded as the candidate relation itself.

## Semantic Definition

**Physical Attachment** is a candidate relation pattern describing a semantically relevant physical or configurational coupling between identifiable bearers, in which one bearer is attached to another bearer or supporting structure.

The candidate is intentionally narrower than generic connection and broader than any single physical joint, fastener, or construction technology. It does not assert a new canonical relation namespace. Any future canonicalization must determine whether the pattern belongs inside the existing Relation layer and whether a controlled predicate is justified under GIOP relation governance.

The bare lexical form **Attachment** is retained as a retrieval/alias form only; the candidate identity is explicitly scoped to Physical Attachment.

## Scope and Boundary

### In scope

- Physical or configurational attachment between identifiable bearers.
- Attachment as a current or historically asserted relationship when temporally qualified.
- Mounting, fastening, binding, adhesion, joining, or structural coupling when the common semantic responsibility is the attachment relationship rather than the operation or mechanism.
- Candidate vocabulary for future Relation-layer evaluation.

### Out of scope

- Generic `part-of` semantics or compositional membership.
- Mere proximity, adjacency, or contact without the required attachment/coupling semantics.
- The Activity or Process of attaching, fastening, mounting, sewing, gluing, welding, or assembling.
- Fasteners, joints, brackets, mounts, clamps, adhesives, or other mechanisms/entities as such.
- Garment-specific fastening semantics, which remain owned by the Garment candidate domain.
- Textile-specific joining, finishing, or construction semantics where those have primary Textile responsibility.
- Attachment sites or attachment structures as domain-specific anatomical or spatial entities.
- Psychological or emotional attachment.
- File or message attachments treated as digital packaging, transfer, or application artifacts.
- New canonical relation predicates introduced solely because the word “attachment” is common.

## Core Distinctions

### Physical Attachment vs Part-of

A part-of assertion describes compositional membership or structural inclusion. A Physical Attachment candidate describes a coupling relationship between bearers. Some attached things may also be parts, but attachment is not equivalent to part-of and must not inherit part-of reasoning automatically.

### Physical Attachment vs Generic Connection

Connection is a broader relational notion. Physical Attachment is a narrower candidate pattern in which the coupling has attachment/securing significance. Mere contact, adjacency, or indirect connectivity is not sufficient by itself.

### Physical Attachment vs Activity or Process

Attaching is an operation that establishes, changes, or removes a configuration. Physical Attachment is the resulting or asserted relationship. The operation remains owned by Activity/Process/Workflow.

### Physical Attachment vs Mechanism or Device

A fastener, joint, bracket, mount, clamp, adhesive, stitch, or weld may realize or participate in attachment. Such mechanisms or entities are not themselves the attachment relation.

### Physical Attachment vs State

An assertion that a bearer is currently attached may be expressed with State when the target is a current configuration. The state qualification does not replace the underlying relation pattern.

### Physical Attachment vs Garment Fastening

Garment Fastening is a domain-specific garment concept. Physical Attachment may describe the generic coupling, while garment semantics describe the garment-specific securing structure or practice. The two must not be collapsed.

### Physical Attachment vs Representation

An image, scan, mesh, CAD model, drawing, metadata record, or file may represent or record an attachment. The representation is not itself the attachment relation.

### Physical Attachment vs Evidence

Evidence supports or evaluates an attachment claim; it is not the claimed relationship. Evidence sufficiency, provenance, and adjudication remain separate responsibilities.

### Physical Attachment vs Attachment Site / Structure

An attachment site or anatomical structure may be an entity or domain-specific structure. Physical Attachment is the relation involving participating bearers, not the site or structure itself.

### Physical Attachment vs Digital/File Attachment

A file or message attachment is an information, packaging, transfer, or application construct. It is not automatically a physical attachment relationship.

### Physical Attachment vs Psychological Attachment

Psychological or social attachment is a mental/social phenomenon with a different semantic owner and must never be inferred from this physical candidate.

## Formal / Logical Behavior

The candidate intentionally leaves relation axioms unresolved until explicit Relation-layer governance.

- **Symmetry:** unresolved; not assumed from lexical form.
- **Inverse relation:** unresolved; no inverse predicate admitted.
- **Transitivity:** not assumed; two attachment relations do not imply an attachment relation between the outer bearers.
- **Reflexivity:** not assumed.
- **Cardinality:** not canonically constrained.
- **Temporal persistence:** context-dependent; an attachment claim may be time-qualified without making time part of the relation identity.
- **Mechanism dependence:** not intrinsic; different physical realizations may instantiate the same candidate pattern.

External formalizations of `attached to` are evidence for a relational interpretation, but their logical axioms are not automatically imported into GIOP.

## Cross-Domain Significance

Physical Attachment can bridge object configuration, engineering, garments, textile construction, cultural heritage, robotics, anatomy, and imaging. It is particularly useful when an imaging or reconstruction pipeline needs to describe how visible components are coupled without confusing that relationship with the operation that produced it, the representation that records it, or the evidence used to evaluate it.

The same lexical term is polysemous across physical, anatomical, psychological, and digital contexts. GIOP therefore uses explicit physical scoping rather than treating the lexical term as a universal semantic identity.

## Trust and Evidence

A statement that two objects are physically attached is an assertion requiring evidence appropriate to the observation context. Evidence may include direct inspection, imagery, geometry, material interfaces, engineering documentation, controlled metadata, or other domain-appropriate sources. Evidence sufficiency is distinct from the truth of the claim, provenance of the evidence, and final adjudication.

External evidence reviewed across formal ontology, engineering, anatomy/biomedicine, cultural heritage, metadata, web standards, and imaging-related practice demonstrates multiple modelling choices and lexical meanings. These sources support boundary analysis only; none is GIOP canonical authority.

## Visitor Universe

All visitor categories consume the same candidate definition at different entry depths. A general visitor needs the distinction between physical attachment and mere proximity/contact; an engineering, anatomy, garment, or imaging visitor may need realization and evidence semantics; a machine consumer needs the bounded candidate status and routing to the existing Relation authority. Visitor categories do not receive separate Physical Attachment identities.

## Cross-Layer Routing

- Generic physical attachment relationship → existing `relations/` authority as a candidate pattern.
- Attaching, mounting, fastening, sewing, gluing, welding, binding, or assembly operation → Activity / Process / Workflow according to primary responsibility.
- Current attached/detached configuration → State when state is the semantic target.
- Garment-specific securing semantics → `garment/` candidate responsibility.
- Textile-specific joining, finishing, or construction → `textile/` plus Activity / Process where applicable.
- Attachment representation → Representation.
- Evidence supporting an attachment claim → Evidence / Provenance / Validation mechanisms.
- Integrity evaluation of an attachment-related configuration → BIL; BIL does not own Physical Attachment semantics.
- Digital file/message attachment → Representation / Packaging / Implementation or application-specific metadata.

**No new relation predicate is admitted by this entry.**

## Lifecycle

Current state: controlled candidate. Its candidate identity, boundaries, and routing are stable for this phase. Creation, modification, removal, and verification of an attachment are modeled outside the candidate itself. Promotion requires independent semantic review, conflict analysis against the closed Relation layer, and explicit governance approval.

## Retrieval Anchors

`PHYSICAL ATTACHMENT`, `ATTACHMENT`, `ATTACHED`, `ATTACHED TO`, `PHYSICAL COUPLING`, `MOUNTING`, `FASTENING`, `BINDING`, `ADHESION`, `JOINING`, `STRUCTURAL ATTACHMENT`
