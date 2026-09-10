# GIOP V3.1 — Compatibility Policy

Status: CANONICAL

## Purpose

Define how GIOP communicates compatibility across versions, artifacts, implementations, and external systems.

## Compatibility dimensions

Compatibility may concern semantic meaning, identifier stability, data representation, mathematical behavior, file interchange, implementation behavior, or runtime expectations. These dimensions must not be conflated.

## Rules

A claim of compatibility must identify what is compatible and against which version or artifact.
Semantic compatibility cannot be inferred solely from a shared filename or repository path.
Breaking changes must be explicit.
Adapters and compatibility layers must preserve the canonical definition rather than create alternate meanings.

## Migration

When an older artifact remains useful but no longer matches the active model, retain the source and document its relation to the current artifact.
