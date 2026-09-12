# Representation Analysis Specification

**Status:** Active Semantic Authoring Specification  
**Version:** 1.0.0  
**Scope:** `02 SEMANTICS/representations`

## Objective

Establish a stable GIOP semantic model for information-bearing forms while preserving the boundaries among form, coding, serialization, storage, presentation, specification, and conformance.

## Research Synthesis

The semantic model was synthesized from multiple standards traditions rather than copied from a single vocabulary:

- RFC 9110 separates representation data, representation metadata, media type, and content coding.
- RDF architecture separates an abstract data model from concrete RDF syntaxes/serializations.
- DCAT distinguishes distributions, formats, media types, compression formats, and package formats.
- PREMIS distinguishes Representation, File, and Bitstream in preservation contexts.
- PROV provides provenance relations among entities, activities, and agents.
- W3C Profiles Vocabulary separates profiles from the specifications they profile and from conformance assertions.
- OAIS/ISO 14721 provides preservation-oriented representation-information context.

## GIOP Semantic Axes

### Information-bearing form

Representation.

### Structural/syntactic form

Format.

### Interoperable data-type identification

Media Type.

### Coding/transformation

Encoding.

### Abstract-to-concrete expression

Serialization.

### Size/transport transformation

Compression.

### Aggregation/containerization

Packaging.

### Presentation

Display.

### Specification specialization

Profile.

### Requirement satisfaction assertion

Conformance, routed primarily through relation semantics.

## Core Model

```text
Underlying semantic content
           |
           v
      Representation
           |
  +--------+--------+----------------+
  |        |        |                |
 Format  Encoding  Media Type    Display
  |        |
  |     Compression
  |
 Serialization
           |
       Packaging
           |
       File/Stream
```

This is a semantic coordination map, not a class hierarchy.

## Transformation Model

```text
R1 --serialization/encoding/compression/etc.--> R2
```

Whenever a transformation materially changes information, fidelity, interpretation, provenance, or reproducibility, the transformation and its consequences must remain distinguishable from the resulting Representation.

## Multiple-Representation Model

One underlying semantic content may be associated with multiple representations. The relationship may be identity-preserving, lossless, lossy, derived, approximate, or otherwise qualified. Shared source does not establish equivalence automatically.

## Representation and Activity

An actual serialization, compression, conversion, export, import, packaging, or migration occurrence can be represented as an Activity in the appropriate GIOP activity/process architecture. This folder does not redefine Activity.

## Representation and Result

A result produced by an activity may be represented in one or more forms. Result identity and Representation identity remain distinct.

## Representation and Display

Display presents information through a presentation mechanism under defined conditions. It may consume a Representation and produce an observable stimulus, but it is not the Representation.

## Representation and Visitor Universe

Visitor Universe is an access/retrieval dimension. It must not create semantic duplication. The canonical entry should support multiple entry depths through progressive orientation, distinctions, technical depth, trust, relations, examples, and retrieval anchors.

## Authoring Requirements

Every canonical representation entry must provide, as applicable:

- identity envelope;
- one-sentence identity statement;
- 5W1H orientation;
- semantic definition;
- scope/structure;
- core distinctions;
- boundary cases;
- technical significance;
- relations;
- provenance/evidence;
- trust/validation;
- lifecycle;
- retrieval anchors.

## Status Policy

`Active` is reserved for concepts whose canonical semantic responsibility and validation are sufficiently established. `Canonical Candidate` is used where the concept is framed and evidenced but has not completed all promotion gates.

Research notes, unresolved conflicts, or future candidate enumerations must not be presented as Active canonical semantics.

## Out of Scope

This specification does not define:

- individual image/file formats;
- codec implementations;
- storage filesystem semantics;
- API-specific payload schemas;
- display hardware classes;
- perceptual quality metrics;
- measurement quantities;
- authentication or cryptographic proof systems;
- visitor-specific knowledge bases.

Those responsibilities belong to their appropriate semantic layers or future controlled topic batches.
