# Observer Knowledge Registry

**Artifact Type:** Knowledge Decision Registry  
**Semantic Layer:** Observer  
**Version:** 1.1.0  
**Status:** Active  
**Authority:** GIOP

The registry retains recovered and synthesized Observer knowledge and records promotion decisions. It is not a parallel ontology.

## Canonical / Existing

### R-OBS-001
- **Recovered claim:** Observer is an eligible observing entity or participant.
- **Semantic type:** Class
- **Epistemic status:** Verified / established
- **Canonical status:** Existing canonical
- **Decision:** Retain under `SEM-CLASS-OBSERVER-001`.
- **Boundary:** Do not collapse with Observer Model, Observation, or Perception.

### R-OBS-002
- **Recovered claim:** Observer Model is a reusable formal construct specifying observer response behavior for defined inputs, tasks, assumptions, parameters, and applicability conditions.
- **Semantic type:** Model
- **Epistemic status:** Verified GIOP synthesis with strong external support
- **Canonical status:** Active
- **Destination:** `02 SEMANTICS/observers/observer-model.md`
- **Decision:** Promote `SEM-OBSERVER-MODEL-001` to Active for the V3.1 Observer core scope under the explicit scoped promotion gate recorded by `OBSERVER-FOLDER-CLOSURE-AUDIT.md`.
- **Evidence:** ISO 19156:2023; W3C/OGC SSN/SOSA; ISO/CIE 11664-1:2019; CIE standard colorimetric observer publications/datasets; ISO 18314-4:2024; observer-model research literature.
- **Boundary:** Model is distinct from observer, functions, datasets, standards, algorithms, implementations, executions, results, representations, properties, quantities, contexts, conditions, states, and perception.

## Controlled Candidate Records

### R-OBS-C01 — Standard Observer
- **Semantic type:** Candidate specialization of Observer Model
- **Status:** Controlled candidate
- **Decision:** Do not create independent root yet.
- **Reason:** Strongly established term, but generic Observer Model can accommodate the responsibility unless independent lifecycle or interoperability requirements justify a separate identity.

### R-OBS-C02 — CIE 1931 Standard Colorimetric Observer
- **Semantic type:** Candidate model specialization
- **Status:** Controlled candidate
- **Evidence:** ISO/CIE 11664-1:2019 and CIE S 017:2020.
- **Decision:** Retain as candidate pending dedicated model-family canonicalization analysis.
- **Associated data:** CIE 1931 colour-matching functions and chromaticity datasets remain representations/data, not automatically the model identity.

### R-OBS-C03 — CIE 1964 Standard Colorimetric Observer
- **Semantic type:** Candidate model specialization
- **Status:** Controlled candidate
- **Evidence:** ISO/CIE 11664-1:2019 and CIE S 017:2020.
- **Decision:** Retain as candidate pending dedicated model-family canonicalization analysis.

### R-OBS-C04 — Ideal / Computational / Human / Population / Individual / Task-Specific Observer Models
- **Semantic type:** Candidate model families
- **Status:** Deferred as independent canonical roots
- **Decision:** Retain lexical and semantic evidence without promotion until each has an independently reusable boundary.

## Reconsideration Triggers

Reopen a candidate when authoritative terminology changes, a distinct interoperability identifier is required, a stable lifecycle independent of Observer Model is demonstrated, or cross-layer validation reveals a responsibility that cannot be represented without semantic loss under the current model.

## Closure Linkage

The Observer folder closure is recorded in `02 SEMANTICS/observers/OBSERVER-FOLDER-CLOSURE-AUDIT.md`. Closure activates the generic Observer Model nucleus only; it does not promote deferred specializations.
