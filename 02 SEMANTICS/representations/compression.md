# Compression

**Semantic ID:** `SEM-REPRESENTATION-COMPRESSION-001`  
**Preferred Name:** Compression  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Transformation that reduces representation-data size or otherwise optimizes storage/transport representation  
**Status:** Canonical Candidate  
**Version:** 1.0.0  
**Authority:** GIOP Semantic Layer — representation-related concept  
**Provenance:** Semantic synthesis from HTTP content-coding semantics, DCAT compression vocabulary, and GIOP representation/fidelity analysis.  
**Validation:** Compression/encoding/fidelity boundaries reviewed.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-ENCODING-001`

> Compression is a transformation that changes representation data to reduce its size or satisfy storage, transport, or processing objectives, with preservation or loss of information determined by the applicable method and context.

## What

Compression transforms representation data. The result can form or participate in another Representation.

## Why

Compression is commonly discussed as if it were a format or representation. GIOP separates the transformation from the resulting form so that provenance and fidelity consequences remain explicit.

## Structure

`R1 → compression transformation → compressed data / R2`

Compression may be lossless or lossy.

## Core Distinctions

### Compression vs Encoding

Compression is a transformation objective/mechanism; Encoding is the broader coding concept. A compression method may be implemented as a content coding, but the terms are not interchangeable.

### Compression vs Format

A compressed representation may use a particular format/container. Compression does not automatically define the complete structural format.

### Compression vs Representation

The compressed output may be a new Representation or a representation state, while Compression is the transformation that produced it.

### Compression vs Fidelity

Lossless compression aims to permit exact reconstruction of the relevant input data under the method's defined conditions. Lossy compression intentionally or effectively changes information and therefore requires appropriate fidelity qualification.

## Boundary Cases

A container that both packages and compresses data has at least two semantic responsibilities. A codec that combines prediction, quantization, entropy coding, and packaging must be decomposed conceptually by primary responsibility rather than product naming.

## Trust and Validation

Claims of losslessness must be tied to a defined input/output scope and reconstruction criterion. Claims of quality preservation require the relevant metric, task, viewing context, or perceptual criterion rather than compression ratio alone.

## Lifecycle

**Current state:** Canonical Candidate.

## Retrieval Anchors

`COMPRESSION`, `LOSSLESS COMPRESSION`, `LOSSY COMPRESSION`, `COMPRESSED DATA`, `COMPRESSION RATIO`, `DECOMPRESSION`, `CODEC`, `CONTENT CODING`
