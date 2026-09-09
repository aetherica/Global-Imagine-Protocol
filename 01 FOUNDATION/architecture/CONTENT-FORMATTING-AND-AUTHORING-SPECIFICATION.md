# GIOP V3.1 — Content Formatting & Authoring Specification

Status: PREPARATION DRAFT

Formatting is treated as information architecture, not decoration. Future GIOP content must be readable by general visitors, precise for professionals, predictable for automation, and retrievable by AI systems.

## 1. Canonical authoring format
Preferred source: UTF-8 Markdown with controlled machine-readable metadata front matter. Canonical source contains metadata envelope, stable section hierarchy, content, relations, provenance/evidence, validation, lifecycle and version information. HTML, API, SDK, site, indexes and AI retrieval projections derive from canonical source.

## 2. Core identity envelope
Every substantive record should expose:
ID; TITLE; ARTIFACT TYPE; PRIMARY RESPONSIBILITY; STATUS; VERSION; AUTHORITY; PROVENANCE; VALIDATION; RELATED IDS.
Optional: SUPERSEDES; SUPERSEDED BY; LICENSE; SCOPE; LAST REVIEWED; TAGS.

## 3. Human-readable structure
Default explanatory sequence, where applicable:
# Title
> one-sentence identity statement
## What
## Why
## Structure
## How
## Where
## Who
Then artifact-specific technical sections.
This preserves the V3 5W1H strength without forcing irrelevant sections.

## 4. Technical structure
Preferred order:
formal definition → parameters → assumptions → constraints → equations/models → units/dimensions → examples → implementation notes → validation → limitations.
Normative requirements, explanation, examples and history must be explicitly separated.

## 5. Headings and retrieval
Use one H1. H2 for major semantic sections. H3 for components/subdomains. H4 only for genuine nested technical detail. Headings must be stable, descriptive retrieval anchors.

## 6. Definitions
Definitions must be explicit and locally understandable. Scope, exclusions, related concepts and examples should follow where useful.

## 7. Tables
Use tables for structured comparison, attributes, mappings, parameters and enumerations. Avoid long narrative cells. Put units consistently in headings or field definitions.

## 8. Equations
Every normative equation must identify variables, units/dimensions, domain of validity, assumptions, material edge cases, provenance and validation/test references. Machine-readable notation is preferred over equation screenshots.

## 9. Code
Use fenced code blocks with language identifiers. Code is implementation material and cannot silently redefine normative semantics.

## 10. Terminology
Canonical terminology resolves through the controlled APPENDIX vocabulary layer. Preferred terms, aliases, synonyms, abbreviations, vendor terms and historical terms must remain distinct.

## 11. Cross-references
Prefer stable canonical IDs. Repository paths are navigation aids; semantic identity must not depend on path permanence.

## 12. Provenance and evidence
Distinguish source, evidence, inference, implementation observation and historical statement. Unverified claims must not be presented as certified facts.

## 13. Lifecycle visibility
Show lifecycle near the record top. Supported visible states:
DRAFT; REVIEW; VALIDATED; CERTIFIED; ACTIVE; SUPERSEDED; ARCHIVED; PRESERVED.

## 14. Warnings and limitations
Use explicit labels such as NOTE, WARNING, LIMITATION, UNVERIFIED and DEPRECATED. Do not rely on color alone.

## 15. Historical content
Historical material must be visibly distinguished from current normative content. V3 source may be preserved without becoming current V4 normative truth.

## 16. AI retrieval anchors
Records should expose deterministic anchors:
ID; TITLE; TYPE; STATUS; VERSION; DEFINITION; PRIMARY RESPONSIBILITY; RELATIONS; PROVENANCE; VALIDATION.
Identity and definitions should be self-contained so a retrieved chunk remains meaningful without its neighbors.

## 17. Accessibility
Canonical Markdown must remain intelligible without CSS. Use semantic headings, lists, tables, code blocks and plain-text state labels.

## 18. Separation of layers
Keep normative, explanatory, procedural, example, historical, implementation and generated content distinct by explicit headings and labels.

## 19. Artifact profiles
A shared Core Envelope may be extended by profiles such as:
CONCEPT; REGISTRY ENTITY; CAMERA/BODY; LENS; DISPLAY; SENSOR; FORMULA; STANDARD; REPRESENTATION; COMPUTATIONAL METHOD; AI MODEL/METHOD; CAPTURE SYSTEM; WORKFLOW; DOMAIN; RUNTIME; RESEARCH CLAIM; EVIDENCE; LEGACY.
Profiles cannot contradict the Core Envelope.

## 20. Conformance
A formatting-conformant artifact has a complete identity envelope, valid heading hierarchy, required profile sections, resolvable terminology, explicit units/equations where applicable, required provenance, visible lifecycle, resolvable relations, and correctly labeled examples/warnings.

This specification is preparatory. It does not authorize substantive bulk content authoring.
