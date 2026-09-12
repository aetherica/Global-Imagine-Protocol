# Format

**Semantic ID:** `SEM-REPRESENTATION-FORMAT-001`  
**Preferred Name:** Format  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Structural or syntactic specification of information representation  
**Status:** Canonical Candidate  
**Version:** 1.0.0  
**Authority:** GIOP Semantic Layer — representation-related concept  
**Provenance:** Semantic synthesis from format specifications, HTTP Semantics, RDF concrete-syntax architecture, DCAT, and GIOP representation analysis.  
**Validation:** Boundary and cross-layer review completed; independent format-family enumeration remains outside this entry.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`

> A Format is a defined structural, syntactic, or organizational specification that determines how information or representation data is arranged and interpreted.

## What

Format describes the prescribed or recognized organization and syntax of information-bearing data. It can specify structure, fields, ordering, encoding conventions, permissible constructs, and interpretation rules.

## Why

A Representation needs a way to describe its structural form without making that specification identical to the representation instance. Format provides that distinction.

## Structure

`Format specification → constrains/characterizes → Representation form`

A Format may have versions, profiles, extensions, restrictions, and conformance requirements.

## Core Distinctions

### Format vs Representation

A Format is the specification or structural scheme; a Representation is an instance or form carrying identified content according to such a scheme.

### Format vs Encoding

Format describes organization and syntax. Encoding describes how information is coded or transformed. A format may prescribe or permit one or more encodings.

### Format vs Media Type

A Media Type is an interoperable identifier/classification used to communicate a representation's data type. It is not the complete format specification.

### Format vs File

A File is a storage artifact. A file can contain data conforming to a Format, but the file itself is not the Format.

### Format vs Profile

A Profile constrains, extends, combines, or guides use of a specification. A Profile is not automatically a new Format.

## Boundary Cases

A filename extension is not itself a Format. A vendor product name is not automatically a Format. A schema, profile, codec, container, or media type must be classified according to its primary semantic responsibility rather than its common marketing terminology.

## Relations

Relevant relations include `conforms-to`, `uses-format`, `has-format`, `profile-of`, and `derived-from`, subject to the authoritative GIOP relation vocabulary.

## Trust and Validation

Claims about a Format should identify its authoritative specification, version, scope, normative status, extensions, constraints, and validation/conformance mechanism where applicable.

## Lifecycle

**Current state:** Canonical Candidate. The concept is sufficiently bounded for GIOP use but remains subject to final semantic-folder promotion gates.

## Retrieval Anchors

`FORMAT`, `DATA FORMAT`, `FILE FORMAT`, `STRUCTURAL FORMAT`, `SYNTAX`, `FORMAT SPECIFICATION`, `FORMAT VERSION`, `FORMAT PROFILE`
