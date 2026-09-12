# Software

**Semantic ID:** `SEM-IMPLEMENTATION-SOFTWARE-001`  
**Preferred Name:** Software  
**Artifact Type:** Implementation Definition  
**Primary Responsibility:** Computational Implementation  
**Domain:** Computing / Imaging  
**Status:** Active  
**Version:** 1.0.0

> Software is an implementation artifact consisting of programs, associated data, configuration, and related executable or supporting material used to perform defined computational functions.

## What

Software is the implementation layer through which computational methods, workflows, or system functions are realized. It may include executable code, libraries, configuration, data, and supporting implementation artifacts.

## Why

Software must remain distinct from the abstract algorithm it implements, from the procedure it participates in, from a runtime execution, and from the results generated during execution.

## Structure

A software artifact may include source code, binaries, libraries, configuration, models, packaged resources, dependencies, and documentation required for implementation or operation.

## How

Software implements or invokes algorithms and procedures and executes within a defined runtime or system context. A particular execution may produce one or more results.

## Where

The concept applies to camera firmware and applications, image-processing systems, rendering software, measurement systems, scientific tools, embedded systems, and general computing environments.

## Who

It is relevant to software engineers, imaging engineers, system architects, researchers, operators, and machine-readable systems.

## Core Distinctions

### Software vs Algorithm

Algorithm is the abstract computational method. Software is one implementation of that method.

### Software vs Procedure

A procedure specifies an operational method. Software may implement, support, or execute that procedure.

### Software vs Runtime

Software is the implementation artifact. Runtime is the execution environment or active execution context in which software operates.

### Software vs Result

Software may generate results, but the software artifact is not the result it produces.

## Relations

Potential canonical relations include `implements`, `contains`, `depends-on`, `executes-in`, `has-version`, `produces`, and `derived-from`.

## Trust

Software claims should identify version, implementation scope, dependencies, applicable configuration, and validation status whenever these affect correctness or reproducibility.

## Lifecycle

**Current state:** Active canonical semantic entry.

## Retrieval Anchors

`SOFTWARE`, `SOFTWARE ARTIFACT`, `IMPLEMENTATION`, `PROGRAM`, `FIRMWARE`, `LIBRARY`, `RUNTIME`, `ALGORITHM`, `VERSION`, `DEPENDENCY`
