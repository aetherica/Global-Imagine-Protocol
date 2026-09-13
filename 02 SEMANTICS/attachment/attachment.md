# Attachment

**Semantic ID:** `SEM-ATTACHMENT-CANDIDATE-001`  
**Preferred Name:** Attachment  
**Artifact Type:** Semantic Candidate / Relation-Routed Domain Entry  
**Primary Responsibility:** Candidate pattern for a durable or functionally relevant connection in which one entity is attached to another or to a supporting structure.  
**Status:** CANDIDATE — NOT CANONICAL  
**Version:** 0.1.0  
**Authority:** GIOP V3.1 candidate governance; existing Relation authority remains unchanged.  
**Provenance:** Multi-domain semantic synthesis; external sources are evidence, not GIOP authority.  
**Validation:** Internal boundary audit completed; independent Relation promotion review still required.  
**Related IDs:** `SEM-RELATION-GENERIC-001` where applicable; `SEM-PROCESS-GENERIC-001`; relevant garment/textile candidates where applicable.

## 5W1H Orientation

### What

Attachment denotes a candidate semantic pattern in which two or more bearers are connected such that one is attached to another, typically through a physical joint, fastening, mounting, binding, adhesion, integration, or comparable configurational connection. The folder does not establish attachment as a new top-level GIOP ontology layer or as a canonical relation predicate.

### Why

The term appears across imaging, physical-object description, engineering, cultural heritage, garment construction, robotics, and metadata. A bounded candidate is useful because these usages share a recognizable connection pattern while differing in domain-specific realization. Capturing the boundary prevents the word “attachment” from being incorrectly promoted as a universal entity, process, or relation predicate.

### Who

The concept is relevant to object and scene modelers, imaging scientists, engineers, garment and textile specialists, archivists, computer-vision systems, metadata designers, and machine consumers that need to distinguish a current attachment relationship from the operation that created it. Psychological or social uses of attachment are outside this candidate's scope.

### Where

The candidate applies primarily to physical, configurational, and object-assembly contexts in which attachment can be evaluated as a relationship between identifiable bearers. Examples include a component mounted to a device, a garment component fastened to another component, or an artifact component integrated into an assemblage. File-attachment and psychological meanings are routed elsewhere according to their semantic responsibility.

### When

Attachment is relevant when a connection currently exists or is asserted to exist at a defined time or state. The creation, modification, removal, or verification of an attachment is temporally distinct from the attachment relationship itself and must route to Activity, Process, Result, State, or other responsible layers as appropriate.

### How

An attachment claim is established by identifying the participating bearers, the connection circumstances, and sufficient evidence that the stated connection exists or existed. Physical realizations may involve contact, jointing, fastening, adhesion, mounting, binding, or structural integration. The specific operation that establishes the connection is not encoded as part of the candidate relation itself.

## Semantic Definition

**Attachment** is a candidate relation pattern describing a semantically relevant connection in which a designated bearer is attached to another bearer or supporting structure through a physical or configurational coupling.

The candidate is intentionally narrower than generic relation and broader than any single physical joint or fastening technology. It does not assert a new canonical relation namespace. Any future canonicalization must determine whether the pattern belongs inside the existing Relation layer and whether one or more controlled predicates are justified.

## Scope and Boundary

### In scope

- Physical or configurational attachment between identifiable bearers.
- Attachment as a current or historically asserted relationship, when temporally qualified.
- Domain examples such as mounting, fastening, binding, joining, or integration when the common semantic role is attachment.
- Candidate vocabulary for future Relation-layer evaluation.

### Out of scope

- Generic `part-of` semantics.
- The Activity or Process of attaching, fastening, mounting, sewing, gluing, welding, or assembling.
- Garment-specific fastening semantics, which remain owned by the Garment candidate domain.
- Psychological or emotional attachment.
- File or message attachments treated as digital packaging or transfer artifacts.
- New canonical relation predicates introduced solely because the word “attachment” is common.

## Core Distinctions

### Attachment vs Part-of

A part-of assertion describes compositional membership or structural inclusion. An attachment candidate describes a connection between bearers. Some attached things may also be parts, but attachment is not equivalent to part-of.

### Attachment vs Relation

Relation is the established generic semantic layer. Attachment is only a candidate relation pattern routed to that layer; the candidate does not create a parallel relation ontology.

### Attachment vs Activity or Process

Attaching is an operation that changes or establishes a configuration. Attachment is the resulting or asserted relationship. The operation remains owned by Activity/Process/Workflow where appropriate.

### Attachment vs Garment Fastening

Garment Fastening is a domain-specific garment concept. Attachment may describe a wider pattern, while garment fastening provides the domain-specific semantics of how garment components are secured. The two must not be collapsed.

### Attachment vs Connection or Contact

Contact may be a condition of physical adjacency; connection may be broader than attachment. Attachment requires a semantically relevant coupling or securing relation rather than mere proximity.

### Attachment vs Joint or Mount

Joint and mount can name specific structural realizations or domain entities. Attachment is the candidate relation pattern connecting the bearers, not necessarily the component or mechanism itself.

### Attachment vs Psychological Attachment

Psychological attachment is a mental or social phenomenon and has a different semantic owner. It must never be inferred from the physical attachment candidate.

### Attachment vs Digital/File Attachment

A file attachment is an information or packaging artifact in a communication or representation context. It is not automatically a physical attachment relationship.

## Cross-Domain Significance

Attachment can bridge object configuration, engineering, garments, cultural heritage, robotics, and imaging. It is particularly useful when an imaging or reconstruction pipeline needs to describe how visible components are connected without confusing that relationship with the process that produced it or the representation that records it.

The candidate aligns with external evidence showing that physical attachment can be modeled as a relation pattern with distinct realizations, while cultural-heritage models treat incorporation of parts as an activity that results in an assemblage. These are evidence for semantic boundary analysis, not automatic GIOP promotion.

## Trust and Evidence

A statement that two objects are attached is an assertion requiring evidence appropriate to the observation context. Evidence may include direct inspection, imagery, geometry, material interfaces, engineering documentation, or controlled metadata. Evidence sufficiency is distinct from the truth of the claim, provenance of the evidence, and any final adjudication.

External evidence reviewed includes the Attachment Ontology treatment of strong and weak physical attachment, CIDOC CRM material on attachment/integration activities and object assemblages, MeSH's distinct psychological meaning of Object Attachment, and W3C DCAT guidance on generic resource relations. These sources demonstrate polysemy and alternative modeling choices; none is itself GIOP authority.

## Visitor Universe

All 45 visitor categories consume the same candidate definition at different entry depths. A general visitor needs the basic distinction between being connected and merely nearby; an engineering or imaging visitor may need realization and evidence semantics; a machine consumer needs the bounded candidate status and its routing to the existing Relation authority. Visitor categories do not receive separate attachment identities.

## Cross-Layer Routing

- Generic relationship semantics → `relations/`.
- Attaching, mounting, fastening, sewing, gluing, welding, or assembly operation → Activity / Process / Workflow according to responsibility.
- Current configurational mode → State where the state itself is the object of description.
- Garment-specific securing mechanism → `garment/` candidate responsibility.
- Textile joining or finishing operation → `textile/` plus Activity / Process where applicable.
- Evidence of attachment → evidence/provenance/validation mechanisms; evidence is not the attachment itself.
- Digital file/message attachment → Representation, Packaging, Implementation, or application-specific metadata according to use.

No new relation predicate is admitted by this entry.

## Lifecycle

Current state: controlled candidate. Its candidate identity, boundaries, and routing are stable for this phase. Creation or modification of an attachment is modeled outside the candidate itself. Promotion requires independent semantic review, conflict analysis against the closed Relation layer, and explicit governance approval.

## Retrieval Anchors

`ATTACHMENT`, `PHYSICAL ATTACHMENT`, `ATTACHED`, `MOUNTING`, `FASTENING`, `BINDING`, `JOINING`, `ADHERED`, `INTEGRATED`, `JOINT`, `MOUNT`, `ASSEMBLAGE`
