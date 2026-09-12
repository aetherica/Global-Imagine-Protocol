# Representation

**Semantic ID:** `SEM-REPRESENTATION-GENERIC-001`  
**Preferred Name:** Representation  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Information-bearing form  
**Domain:** Information / Imaging / Data / Communication / Preservation  
**Status:** Active  
**Version:** 1.0.0  
**Authority:** GIOP Canonical Semantic Layer  
**Provenance:** Synthesized from GIOP architecture and verified external semantic models; see Provenance and Evidence.  
**Validation:** Foundation authoring, boundary, cross-layer, and retrieval requirements applied.  
**Related IDs:** `SEM-DISPLAY-001`, `SEM-ACTIVITY-OBSERVATION-001`, `SEM-ACTIVITY-MEASUREMENT-001`

> A Representation is an information-bearing form through which information, a result, a resource, or other semantic content is expressed, made available, exchanged, stored, presented, or otherwise made interpretable within a defined context.

## What

A Representation is the form in which some underlying semantic content is made available for interpretation or use.

The underlying content and its Representation are related but are not identical. The same underlying content may have multiple representations, and a representation may itself be transformed, serialized, encoded, packaged, stored, transmitted, or presented through different mechanisms.

Representation therefore describes an information-bearing form, not merely a file, data type, visual display, or encoding operation.

## Why

Imaging and information systems routinely separate what information means from the form in which that information is communicated or consumed.

An image result may be represented as a raster file, a compressed stream, a structured record, an archival package, a machine-readable document, or a displayed visual stimulus. Treating all of these as the same semantic object obscures provenance, transformation, format, storage, presentation, and interpretation boundaries.

GIOP uses Representation to preserve this distinction while allowing related semantic layers to connect through canonical relations.

## Who

The concept is relevant to general visitors, learners, educators, photographers, cinematographers, imaging engineers, imaging scientists, AI/ML engineers, dataset engineers, standards professionals, archivists, API/SDK consumers, system integrators, and machine-readable consumers.

Visitor category does not change the identity of Representation. It changes the entry depth required to understand or consume the same canonical concept.

## Where

Representations occur in data exchange, storage and archival systems, imaging pipelines, acquisition and processing outputs, scientific datasets, APIs and machine interfaces, document systems, display and presentation systems, computational workflows, preservation and migration systems, and human/machine communication.

## When

A Representation may exist at any stage after or alongside the availability of underlying information. It may be created by acquisition, processing, serialization, encoding, transformation, packaging, publication, migration, or presentation workflows.

A Representation may also be selected dynamically when multiple valid forms are available.

## How

A Representation is understood by relating it to the underlying represented content, structural/form specification, media-type identification, encoding or transformation, serialization, storage/transport or packaging, provenance and derivation, intended use context, presentation mechanism, and applicable Profile or conformance assertion.

These are related semantic dimensions, not universal subclasses of Representation.

## Semantic Definition

**Representation** is an information-bearing form through which identified semantic content is expressed, made available, exchanged, stored, presented, or otherwise made interpretable in a specified context.

The represented content may be information, a result, a resource, a dataset, a document, an image, a structured graph, or another semantically identifiable object.

A Representation may be concrete and machine- or human-consumable, but concreteness alone does not make a file, stream, display, or encoding operation a Representation.

## Structure

```text
Represented Content
       |
       v
Representation
       |
       +-- structural/form specification → Format
       +-- interoperable type identification → Media Type
       +-- coding/transformation → Encoding
       +-- abstract-to-concrete expression → Serialization
       +-- size/transport transformation → Compression
       +-- aggregation/containerization → Packaging
       +-- presentation mechanism → Display
       +-- application-specific constraints → Profile
       +-- provenance → source / activity / agent relations
```

This is a coordination model, not an inheritance hierarchy.

## Core Distinctions

### Representation vs Information

Information is the represented semantic content. Representation is the information-bearing form in which that content is expressed or made available.

### Representation vs Result

A Result is information produced by an activity. A Representation may express or carry that Result. Representation does not replace Result identity.

### Representation vs Dataset

A Dataset is an organized collection of data. A Representation may express, distribute, store, or transmit a Dataset, but the dataset and its representation remain distinct semantic responsibilities.

### Representation vs File

A File is a storage-oriented artifact. A Representation is not defined by storage alone. One Representation may comprise multiple Files in an archival or preservation context, and a File may participate in a representation without being identical to the represented semantic object.

### Representation vs Format

Format specifies or characterizes the structure or syntax of a representation. A Format is not the representation instance itself.

### Representation vs Media Type

Media Type identifies a standardized data type for interoperable processing or exchange. It is not synonymous with the representation instance or with the underlying format specification.

### Representation vs Encoding

Encoding describes a coding scheme or transformation by which data is expressed. An encoded representation is the resulting information-bearing form; Encoding itself is not the representation.

### Representation vs Serialization

Serialization concerns the production or specification of a concrete expression from an abstract or structured information model. The serialized output may be a Representation, but the serialization operation is distinct.

### Representation vs Compression

Compression transforms representation data, commonly to reduce size or meet transport/storage requirements. A compressed Representation is not identical to the Compression operation.

### Representation vs Packaging

Packaging aggregates or organizes one or more artifacts into a container or distribution structure. A Package may carry one or more representations; packaging is not itself the represented content.

### Representation vs Display

Display is a presentation system or mechanism. Representation is the information-bearing form being presented or otherwise consumed. A display can present a representation without becoming that representation.

### Representation vs Perception

Perception is an observer-dependent perceptual experience or interpretation. A Representation can provide stimulus or information for perception but does not determine the perceptual outcome.

### Representation vs Conformance

Conformance is an assertion that an entity or artifact satisfies specified requirements. A representation may conform to a Profile or standard, but conformance is not a representation type.

## Multiple Representations

The same underlying content may have multiple representations.

```text
Underlying image information
        |
        +-- Representation A → lossless raster form
        +-- Representation B → compressed raster form
        +-- Representation C → structured metadata description
        +-- Representation D → displayed visual presentation
```

These forms may differ in syntax, encoding, compression, packaging, resolution, fidelity, or presentation while retaining a declared relationship to the same underlying content.

Semantic equivalence must not be assumed merely because two representations refer to the same source. Equivalence, derivation, transformation, or similarity must be established by appropriate evidence and relation semantics.

## Representation and Transformation

A representation can be derived from another representation:

`R1 → transformation → R2`

The transformation may be lossless, lossy, reversible, irreversible, format-changing, encoding-changing, resolution-changing, or otherwise qualified.

The existence of R2 does not erase R1. Provenance and derivation should remain explicit when the transformation affects interpretation, fidelity, reproducibility, or trust.

## Representation and Activity

Activities such as Acquisition, Processing, Measurement, Observation, Serialization, or Calibration may produce, modify, select, or validate representations.

The activity is the occurrence; the Representation is the information-bearing form involved in or resulting from that occurrence.

This preserves the GIOP distinction:

`Activity → Result → Representation`

when that chain applies.

## Representation and Context

Interpretation of a Representation can depend on Context, including application, capture, processing, operational, measurement, viewing, preservation, intended-consumer, profile, and specification contexts.

Context qualifies interpretation or use; it does not become part of the Representation's semantic identity unless explicitly represented as content or metadata.

## Boundary Cases

### Same bytes, different interpretation

Byte identity alone does not establish semantic identity. Interpretation depends on declared format, media type, context, and applicable specifications.

### Different bytes, same semantic content

Two byte sequences may represent the same semantic content through different formats or serializations. This does not imply byte identity.

### Lossy transformation

A lossy transformation may produce a new representation that is related to the source while changing information, fidelity, or perceptual characteristics. The relation must not silently imply identity.

### Display output

A display stimulus can be generated from a representation, but the display system, stimulus, representation, and perception remain distinct layers.

### Archive package

A preservation package can contain files, metadata, manifests, and one or more representations. Packaging does not redefine the Representation concept.

## Technical and Cross-Domain Significance

Representation provides a bridge across:

`Information / Result → Representation → Format / Encoding / Serialization → Storage / Exchange / Display → Observation / Perception`

It is therefore central to imaging, data engineering, APIs, computational systems, preservation, machine learning, display, and scientific communication.

## Relations

Existing canonical relation concepts should be used where applicable, including `represents`, `derived-from`, `part-of`, `participates-in`, and observation/presentation relations where semantically justified. `conforms-to` is treated as a qualified conformance assertion rather than a representation subtype.

No new relation authority is silently introduced by this entry.

## Provenance and Evidence

The semantic synthesis is informed by RFC 9110 (HTTP Semantics), W3C RDF 1.2 Concepts and Abstract Data Model, W3C DCAT, PREMIS Data Dictionary 3.0, W3C PROV / PROV-O, W3C Profiles Vocabulary, and ISO 14721:2025 (OAIS).

These sources are evidence for semantic synthesis and are not copied as GIOP definitions.

## Trust and Validation

A Representation claim should identify, where relevant, what content is represented; source or derivation; format and media type; encoding and compression; serialization method; packaging or carrier; transformation history; profile and conformance information; validation method; and limitations or uncertainty.

A representation should not be declared equivalent, lossless, conformant, authentic, or complete without the corresponding evidence or validation basis.

## Lifecycle

**Current state:** Active canonical semantic entry.

The semantic definition remains subject to controlled revision when materially stronger evidence or a justified architectural change is established. Such changes must follow the GIOP knowledge-entry and canonicalization rule.

## Retrieval Anchors

`REPRESENTATION`, `INFORMATION-BEARING FORM`, `REPRESENTATION DATA`, `REPRESENTATION METADATA`, `FORMAT`, `MEDIA TYPE`, `ENCODING`, `SERIALIZATION`, `COMPRESSION`, `PACKAGING`, `FILE`, `DISPLAY`, `PROFILE`, `CONFORMANCE`, `DERIVED REPRESENTATION`, `MULTIPLE REPRESENTATIONS`
