# Packaging

**Semantic ID:** `SEM-REPRESENTATION-PACKAGING-001`  
**Preferred Name:** Packaging  
**Artifact Type:** Semantic Definition  
**Primary Responsibility:** Aggregation and organization of one or more artifacts or representations into a package/container for a defined purpose  
**Status:** Canonical Candidate  
**Version:** 1.0.0  
**Authority:** GIOP Semantic Layer — representation-related concept  
**Provenance:** Semantic synthesis from DCAT package-format distinctions, preservation practice, and GIOP representation analysis.  
**Validation:** Packaging/container/representation boundary reviewed.  
**Related IDs:** `SEM-REPRESENTATION-GENERIC-001`

> Packaging is the organization or aggregation of one or more information artifacts, files, metadata objects, or representations into a defined package or container structure.

## What

Packaging creates an aggregate carrier or distribution structure. A package can contain one or more representations, files, manifests, metadata records, or supporting objects.

## Why

Packaging is not equivalent to representation, because the package answers an aggregation/containerization need rather than defining the semantic identity of every object it carries.

## Structure

`Members → packaging structure → Package`

A package may itself have a Representation when its package structure is treated as information-bearing content.

## Core Distinctions

### Packaging vs Representation

Packaging organizes or aggregates artifacts. A Representation expresses identified content. A package can carry representations and can itself be represented.

### Packaging vs Compression

Compression transforms data, commonly to reduce size. Packaging aggregates or organizes members. A package may also be compressed, but these responsibilities remain distinct.

### Packaging vs File

A package can be stored as one file, multiple files, or another carrier. The storage carrier does not define packaging semantics by itself.

### Packaging vs Dataset

A dataset is an organized collection of data. A package is an aggregation/container structure used to carry or distribute one or more objects; the two may overlap operationally but have distinct primary responsibilities.

## Boundary Cases

An archive format may combine packaging, metadata, and compression. GIOP should represent these as linked responsibilities rather than assuming a single term covers every layer.

## Trust and Validation

Packaging claims should identify package specification/version, member structure, manifest rules, ordering or integrity requirements, and compression/encryption characteristics where relevant. Package membership must not be treated as semantic equivalence.

## Lifecycle

**Current state:** Canonical Candidate.

## Retrieval Anchors

`PACKAGING`, `PACKAGE`, `CONTAINER`, `ARCHIVE PACKAGE`, `PACKAGE FORMAT`, `DISTRIBUTION PACKAGE`, `AGGREGATION`
