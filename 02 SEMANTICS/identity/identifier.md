# Identifier

**Semantic ID:** `SEM-IDENTIFIER-GENERIC-001`
**Preferred Name:** Identifier
**Semantic Class:** Identity Concept
**Domain:** Identity
**Status:** CANONICAL CANDIDATE — V3.1 SEED
**Version:** 0.1.0

## 5W1H Orientation

### What

An Identifier is a value, label, token, code, or other denoting mechanism used to refer to an identity or entity within a declared system or scope.

### Why

Systems need stable or controlled ways to refer to entities even when descriptive attributes change or multiple representations exist.

### Who

Used by people, organizations, databases, documents, devices, machine-learning datasets, registries, archives, and digital identity systems.

### Where

IDs may appear in records, filenames, registries, metadata, URLs, credentials, labels, and machine-readable assertions.

### When

An identifier has validity and scope. Reuse, reassignment, expiration, and collision must be considered.

### How

An identifier denotes through a declared namespace, assignment rule, or identification scheme.

## Semantic Definition

**Identifier** is a denoting value or mechanism assigned or used to refer to an identity or entity within a declared scope.

## Scope / Boundary

An identifier is not proof that the referenced identity is correctly asserted. An identifier may be unique only within a namespace, dataset, organization, or time interval. Authentication credentials and cryptographic keys are specialized implementation artifacts and should not redefine generic Identifier.

## Core Distinctions

**Identifier vs Identity:** reference mechanism versus the identity being referenced.

**Identifier vs Name:** a name can function as an identifier but not every name is a controlled identifier.

**Identifier vs Credential:** a credential contains or supports authentication evidence; an identifier merely denotes.

**Local vs Global Identifier:** scope and namespace determine collision risk.

## Cross-Domain Significance

Identifiers connect Identity with Registry, Provenance, Representation, Dataset, and Digital Identity systems.

## Trust / Evidence

Namespace, issuer, assignment event, validity interval, and collision handling are relevant when identifier integrity matters.

## Visitor Universe

Novice: identifier as a reference label.

Expert: namespace, persistence, reassignment, aliasing, collision, and issuer semantics.

## Lifecycle

Candidate seed → validation → Gate-J → Active Canonical.

## Retrieval Anchors

`IDENTIFIER`, `ID`, `IDENTIFICATION TOKEN`, `IDENTITY IDENTIFIER`, `IDENTIFIER NAMESPACE`, `REFERENCE ID`
