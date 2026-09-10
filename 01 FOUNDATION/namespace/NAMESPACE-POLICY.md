# GIOP V3.1 — Namespace Policy

Status: CANONICAL

## Purpose

Provide stable, machine-safe naming rules for GIOP artifacts and controlled identifiers.

## Rules

Identifiers must be deterministic, unique within their namespace, stable across repository reorganization, and safe for machine processing.

Preferred names and aliases are separate fields. Vendor names, historical names, abbreviations, and temporary project names must not silently become canonical identifiers.

A namespace change is a compatibility-impacting event and must be recorded.

Canonical namespace design must remain aligned with `IDENTITY-POLICY` and later registration rules.
