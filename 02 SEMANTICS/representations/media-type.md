# Media Type

**Semantic ID:** `SEM-REPRESENTATION-MEDIA-TYPE-001`  
**Preferred Name:** Media Type  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Interoperable identification and classification of representation data type  
**Status:** Canonical Candidate  
**Version:** 1.0.0  
**Authority:** GIOP Semantic Layer — representation-related concept  
**Provenance:** Semantic synthesis from RFC 9110 and IANA media-type registration practice.  
**Validation:** Format/media-type boundary reviewed; registry-specific details remain external to the GIOP concept.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-FORMAT-001`

> A Media Type is a standardized identifier that classifies the nature of representation data for interoperable communication and processing.

## What

A Media Type identifies a representation data type in an interoperable vocabulary, commonly using a type/subtype form with optional parameters.

## Why

Media Type must remain distinct from the representation instance and from the complete format specification. It provides a stable identification mechanism for communication, processing, negotiation, and interpretation.

## Structure

```text
Representation
      |
      +-- data type identification → Media Type
      |
      +-- structural specification → Format
```

A Media Type may carry parameters that refine interpretation or processing requirements.

## Core Distinctions

### Media Type vs Representation

The Media Type identifies a representation's data type; it is not the representation instance.

### Media Type vs Format

A Media Type can identify or point toward a data format, but it is not necessarily the complete technical specification of that format.

### Media Type vs File Extension

A filename extension is a naming convention. A Media Type is an interoperable semantic/registry identifier.

### Media Type vs Encoding

Media Type classifies the data type. Encoding describes coding or transformation applied to data.

## Boundary Cases

A Media Type registration does not by itself prove that an arbitrary byte sequence conforms to every requirement of the associated format. Conformance requires appropriate validation.

## Relations

Relevant relations include `has-media-type`, `identified-by`, `uses-format`, and `conforms-to`, subject to the authoritative GIOP relation vocabulary.

## Trust and Validation

Registry status, specification authority, version, parameters, and actual byte-level or structural conformance should be kept distinct. A declared Media Type is metadata/identification evidence, not automatic proof of content validity.

## Lifecycle

**Current state:** Canonical Candidate.

## Retrieval Anchors

`MEDIA TYPE`, `MIME TYPE`, `CONTENT-TYPE`, `TYPE/SUBTYPE`, `MEDIA-TYPE PARAMETER`, `REGISTERED MEDIA TYPE`
