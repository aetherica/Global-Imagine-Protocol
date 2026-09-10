# GIOP V3.1 — Versioning Policy

Status: CANONICAL

## Purpose

Make GIOP change understandable, comparable, and traceable across time.

## Version model

GIOP uses major, minor, and patch levels as signals of change significance.

Major changes indicate an incompatible change to a canonical contract or architecture.
Minor changes add or extend knowledge and capabilities without intentionally breaking the established contract.
Patch changes correct defects, wording, metadata, or non-breaking implementation details.

## Artifact versioning

An artifact may have its own version or inherit the version context of a release. Artifact version and repository release version must not be assumed identical.

## Supersession

When an artifact is replaced, record the relation between the prior and current states. Preserve the historical source where it has evidentiary, compatibility, or archival value.

## Traceability

A reader should be able to determine what version they are reading, what it supersedes, and what material depends on it.
