# Intermediate Representation

- **ID:** `SEM-REPRESENTATION-INTERMEDIATE-001`
- **TITLE:** Intermediate Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Program representation used between source-level, target-level, or other computational abstraction levels
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across compiler IR, bytecode/virtual machines, program transformation, optimization, and systems tooling.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-PROGRAM-001`

## Semantic Definition

Intermediate Representation (IR) is a program representation deliberately positioned between computational abstraction levels so that analysis, transformation, optimization, lowering, interpretation, or code generation can operate on a defined intermediate form.

IR may be textual, graph-based, SSA-like, bytecode-like, typed, control-flow oriented, data-flow oriented, or otherwise structured.

## Core Distinctions

- **IR ≠ Program Representation in general:** IR is a specialized position/purpose within program representation.
- **≠ Algorithm:** IR encodes program structure; algorithms are methods.
- **≠ Compiler Process:** compilation is an Activity/Process; IR is an information-bearing artifact/form used by it.
- **≠ Source Code:** source can be an input program representation but is not necessarily intermediate.
- **≠ Machine Code:** machine code may be a target representation rather than an intermediate form, depending on workflow.

## Boundary Cases

A compiler's SSA form, typed IR, bytecode used as a compilation intermediate, or graph IR qualifies when intentionally used between abstraction stages. The same byte sequence can have different semantic classification depending on its role; identity follows documented responsibility and lifecycle context.

## Trust / Validation

Record IR semantics, invariants, abstraction level, transformation stage, target assumptions, provenance, version, and validation of transformations preserving intended semantics.

## Lifecycle

Active canonical concept. Specific IR families remain independently governed.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in`.

Retrieval anchors: `INTERMEDIATE REPRESENTATION`, `IR`, `COMPILER IR`, `SSA REPRESENTATION`, `PROGRAM INTERMEDIATE FORM`, `BYTECODE REPRESENTATION`.
