# Program Representation

- **ID:** `SEM-REPRESENTATION-PROGRAM-001`
- **TITLE:** Program Representation
- **ARTIFACT TYPE:** Semantic Definition
- **PRIMARY RESPONSIBILITY:** Information-bearing form expressing computational instructions, control structure, data structure, or executable program semantics
- **STATUS:** Active
- **VERSION:** 1.0.0
- **AUTHORITY:** GIOP Canonical Semantic Layer — Representation
- **PROVENANCE:** Semantic synthesis across programming-language theory, compiler practice, program analysis, and executable-system representations.
- **VALIDATION:** Independent promotion gates passed.
- **RELATED IDS:** `SEM-REPRESENTATION-GENERIC-001`, `SEM-REPRESENTATION-INTERMEDIATE-001`, `SEM-ACTIVITY-GENERIC-001`

## Semantic Definition

Program Representation is an information-bearing form expressing computational instructions, control/data structure, semantics, or executable program organization at a specified abstraction level.

It includes source-level, syntax-tree, bytecode, machine-level, or other program-structural forms when their primary responsibility is expressing a program.

## Core Distinctions

- **Program Representation ≠ Program Execution:** execution is an Activity.
- **≠ Program as abstract computational artifact:** the representation is a particular information-bearing form of program structure.
- **≠ Algorithm:** an algorithm is a computational method; a program representation encodes an implemented or expressible program.
- **≠ Intermediate Representation:** IR is a specialized program representation positioned between abstraction levels.
- **≠ File/Serialization:** a file or serialization can carry the program representation without being its semantic identity.

## Boundary Cases

Source code, abstract syntax trees, bytecode, executable instruction structures, and program graphs qualify. A natural-language procedure is not automatically a Program Representation.

## Trust / Validation

Record language or abstraction level, semantics, version, target environment, dependencies, provenance, integrity, conformance, and whether the form is source, intermediate, generated, or executable.

## Lifecycle

Active canonical concept. Language-specific and machine-specific forms remain independently reviewable.

## Relations / Retrieval Anchors

Use existing `represents`, `derived-from`, `part-of`, and `participates-in` where justified.

Retrieval anchors: `PROGRAM REPRESENTATION`, `PROGRAM FORM`, `PROGRAM STRUCTURE`, `SOURCE REPRESENTATION`, `EXECUTABLE REPRESENTATION`.
