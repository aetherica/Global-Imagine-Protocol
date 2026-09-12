# Has Result

**Semantic ID:** `SEM-RELATION-HAS-RESULT-001`  
**Preferred Name:** Has Result  
**Artifact Type:** Semantic Relation  
**Primary Responsibility:** Relation  
**Domain:** Observation / Measurement / Computation  
**Status:** Active  
**Version:** 1.0.0

> `has-result` relates an execution or result-producing activity to the result information produced by that execution.

## What

The `has-result` relation connects a producing execution with its resulting information object.

## Why

A result must remain semantically traceable to the execution that produced it while remaining distinct from that execution.

## Structure

Canonical pattern:

`Execution → has-result → Result`

Inverse:

`Result → is-result-of → Execution`

## Core Distinctions

`has-result` does not mean `has-value`. A result may contain or expose one or more values, but the relation identifies provenance between an execution and its produced result.

`has-result` does not mean `represents`. Representation is the encoding or expression of information, not its production relationship.

## Relations / Dependencies

The relation is intended to connect execution, observation, measurement, computational method, and result semantics while remaining independent of a specific implementation language or storage format.

## Trust

Use of `has-result` should preserve enough execution identity and provenance to establish which execution produced the referenced result.

## Lifecycle

**Current state:** Active canonical semantic relation.

## Retrieval Anchors

`HAS RESULT`, `IS RESULT OF`, `EXECUTION RESULT`, `OBSERVATION RESULT`, `MEASUREMENT RESULT`, `COMPUTATIONAL RESULT`, `RESULT PROVENANCE`
