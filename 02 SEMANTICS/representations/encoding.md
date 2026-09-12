# Encoding

**Semantic ID:** `SEM-REPRESENTATION-ENCODING-001`  
**Preferred Name:** Encoding  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Coding or transformation scheme used to express information/data  
**Status:** Canonical Candidate  
**Version:** 1.0.0  
**Authority:** GIOP Semantic Layer — representation-related concept  
**Provenance:** Semantic synthesis from HTTP content-coding semantics, character/data encoding practice, format specifications, and GIOP representation analysis.  
**Validation:** Boundary review completed; specific encoding families remain separately classified where needed.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`

> An Encoding is a defined coding scheme or transformation by which information or representation data is expressed in a specified code or coded form.

## What

Encoding describes a rule-governed mapping between an information/data form and a coded expression. The mapping may concern characters, binary values, transport content, or other representational transformations.

## Why

Encoding must remain distinct from Format and Representation. The same format may permit different encodings, and an encoded output may be a Representation without making the encoding itself that Representation.

## Structure

`Source information/data → Encoding rule → coded data`

The resulting coded data may participate in a Representation with additional format, media-type, compression, packaging, or transport characteristics.

## Core Distinctions

### Encoding vs Format

Format concerns structural organization and syntax. Encoding concerns coding or transformation.

### Encoding vs Compression

Compression is a transformation generally intended to reduce size or improve transport/storage efficiency. Encoding is the broader coding concept. Compression can be implemented as an encoding/content-coding mechanism, but encoding is not synonymous with compression.

### Encoding vs Representation

Encoding is the scheme or transformation; Representation is the information-bearing form resulting from or using that scheme.

### Encoding vs Serialization

Serialization is the production or definition of a concrete expression from an abstract/structured model. Encoding may be part of that process but has a distinct responsibility.

## Boundary Cases

Character encodings such as UTF-8 and content codings such as gzip illustrate different encoding responsibilities. A codec may combine coding and compression functions; GIOP classifies the semantic responsibility rather than relying on product terminology.

## Relations

Representation-related assertions must use the authoritative GIOP relation vocabulary. Existing canonical relations such as `derived-from`, `represents`, `part-of`, `participates-in`, and `has-result` may be used where semantically applicable. No new encoding-specific relation authority is introduced here.

## Trust and Validation

Encoding claims should identify the applicable specification, version, input/output domain, reversibility or loss characteristics where relevant, and validation requirements.

## Lifecycle

**Current state:** Canonical Candidate. Specific encoding families should be admitted only after independent semantic and evidence review.

## Retrieval Anchors

`ENCODING`, `DATA ENCODING`, `CHARACTER ENCODING`, `CONTENT CODING`, `CODED FORM`, `ENCODED DATA`, `ENCODING SCHEME`
