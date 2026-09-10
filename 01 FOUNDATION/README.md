# GIOP V3.1 — FOUNDATION

Status: CANONICAL FOUNDATION LAYER

`01 FOUNDATION` defines the framework within which GIOP knowledge is created, identified, governed, validated, versioned, preserved, and exchanged.

It does not define the canonical meaning of imaging concepts. Canonical semantic meaning belongs to `02 SEMANTICS`; canonical registered identity belongs to `03 REGISTRY`.

## Foundation responsibility

FOUNDATION answers: what GIOP is allowed to be, how the project changes, how artifacts are authored, how authority is established, how compatibility and quality are handled, and how history is preserved.

## Foundation map

| Area | Responsibility |
|---|---|
| architecture | Structural and authoring architecture |
| change-management | Controlled change and decision records |
| compatibility | Compatibility policy and migration expectations |
| contribution | Contribution pathway and contributor requirements |
| documentation-policy | Documentation behavior and publication rules |
| governance | Authority, decision rights, review and escalation |
| identity | Project and artifact identity principles |
| interoperability-policy | Interchange and boundary requirements |
| mission | Operational mission |
| namespace | Stable naming and namespace rules |
| principles | Non-negotiable project principles |
| quality-policy | Quality model and quality gates |
| release-policy | Release readiness and release discipline |
| roadmap | Sequencing of project work |
| scope | In-scope, out-of-scope and boundary rules |
| terminology-policy | Rules for controlled language usage |
| versioning-policy | Version semantics and compatibility signaling |
| vision | Long-term direction |

## Boundary rules

1. FOUNDATION defines framework, not domain semantics.
2. Repository placement is navigation, not semantic authority.
3. A policy may constrain an artifact, but it must not silently redefine that artifact's canonical meaning.
4. Historical material is preserved rather than silently erased.
5. Later implementation layers must trace back to authoritative Foundation rules and canonical semantic or registry records.

## Completion gate

FOUNDATION is considered ready for downstream semantic work when its responsibility folders are populated or intentionally marked as future-operational, its cross-references are resolvable, its policies do not contradict one another, and the downstream boundary `FOUNDATION → SEMANTICS → REGISTRY` is explicit.
