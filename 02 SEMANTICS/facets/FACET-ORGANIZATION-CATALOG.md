# GIOP V3.1 — Facet Organization Catalog

## Status

**CANONICAL — V3.1 VALIDATED ORGANIZATIONAL VIEWS**

This catalog records concrete Facet organizations validated against the current V3.1 canonical corpus. These are organizational views over existing canonical identities, not new semantic definitions and not independent domain-specific ontology classes.

## Governing Rule

Every organization in this catalog follows:

```text
DEFINED SCOPE
    ↓
ORGANIZING DIMENSION
    ↓
CHARACTERISTIC OF DIVISION
    ↓
COMPARABLE MEMBERS / ARRAYS
    ↓
EXISTING CANONICAL IDENTITIES
```

The primary semantic authority of every member remains in its owning semantic layer.

## Organization A — Imaging-System Role View

**Internal View ID:** `FACET-VIEW-IMAGING-SYSTEM-ROLE-001`  
**Status:** VALIDATED ORGANIZATIONAL VIEW  
**Independent Facet Entry:** No

### Scope

Canonical imaging-related Classes that can be organized by their functional role within an imaging system or imaging environment.

### Organizing Dimension

**Functional role in the imaging system/environment.**

### Characteristic of Division

The role an entity or entity type performs relative to capture, sensing, illumination, observation, scene/object representation, or measurement support.

### Arrays

**Capture / Sensing**
- Camera — `classes/camera.md`
- Sensor — `classes/sensor.md`

**Optical / Radiative**
- Lens — `classes/lens.md`
- Light Source — `classes/light-source.md`

**Scene / Subject**
- Scene — `classes/scene.md`
- Object — `classes/object.md`
- Surface — `classes/surface.md`
- Material — `classes/material.md`

**Observation / Measurement**
- Observer — `classes/observer.md`
- Measuring System — `classes/measuring-system.md`

### Validation

The members are comparable because the organization asks what role each Class plays in an imaging system or imaging situation. This does not create `Camera`, `Lens`, or `Sensor` as Facet concepts; their Class definitions remain authoritative.

### Boundary

This view must not be interpreted as:

- a replacement for the Class taxonomy;
- a part-whole model of an actual camera system;
- a claim that every listed entity is physically present in every capture;
- an `is-a` hierarchy between the members.

## Organization B — Imaging-Characteristic Domain View

**Internal View ID:** `FACET-VIEW-IMAGING-CHARACTERISTIC-001`  
**Status:** VALIDATED ORGANIZATIONAL VIEW  
**Independent Facet Entry:** No

### Scope

Current canonical Property concepts.

### Organizing Dimension

**Technical characteristic domain represented by the Property.**

### Characteristic of Division

The principal imaging behavior or characteristic family to which a Property contributes within the current canonical corpus.

### Arrays

**Optical / Image-Formation Behavior**
- Optical Distortion — `properties/optical-distortion.md`
- Chromatic Aberration — `properties/chromatic-aberration.md`
- Transparency — `properties/transparency.md`

**Spectral / Detector Response**
- Spectral Response — `properties/spectral-response.md`
- Sensitivity — `properties/sensitivity.md`
- Linearity — `properties/linearity.md`

**Color / Appearance**
- Chromaticity — `properties/chromaticity.md`

**Dynamic / Performance Characteristic**
- Dynamic Range Characteristic — `properties/dynamic-range-characteristic.md`

### Validation

All members are canonical Properties. The facet does not redefine any Property; it provides a controlled organizational view of the current Property vocabulary.

The arrays are organizational groupings and must not be interpreted as a new formal Property taxonomy unless separately validated.

### Boundary

A grouping under an array does not imply equivalence, shared units, shared measurement procedure, causal dependence, or identical bearer applicability.

## Organization C — Contextual-Frame Use View

**Internal View ID:** `FACET-VIEW-CONTEXTUAL-FRAME-USE-001`  
**Status:** VALIDATED ORGANIZATIONAL VIEW  
**Independent Facet Entry:** No

### Scope

Canonical Context concepts whose current V3.1 status is sufficient for established membership.

### Organizing Dimension

**Primary use or situational purpose of the contextual frame.**

### Characteristic of Division

The principal activity or interpretive purpose for which the Context provides a frame.

### Arrays

**Measurement / Evaluation**
- Measurement Context — `contexts/measurement-context.md`
- Assessment Context — `contexts/assessment-context.md`

**Viewing / Interpretation**
- Viewing Context — `contexts/viewing-context.md`

**Application / Knowledge Use**
- Application Context — `contexts/application-context.md`
- Domain Context — `contexts/domain-context.md`

### Candidate Handling

The following remain excluded from established membership until their Context status is promoted or otherwise explicitly authorized:

- Capture Context — `contexts/capture-context.md`
- Processing Context — `contexts/processing-context.md`
- Operational Context — `contexts/operational-context.md`

### Boundary

This view does not imply that Contexts are subclasses of one another. It organizes distinct contextual frames by principal use and preserves each Context's own semantic boundary.

## Organization D — Relation-Function View

**Internal View ID:** `FACET-VIEW-RELATION-FUNCTION-001`  
**Status:** VALIDATED ORGANIZATIONAL VIEW  
**Independent Facet Entry:** No

### Scope

The current canonical V3.1 Relation seed vocabulary.

### Organizing Dimension

**Primary semantic function of the Relation.**

### Characteristic of Division

The kind of connection established by the relation concept.

### Arrays

**Structural / Participation**
- Part Of — `relations/part-of.md`
- Participates In — `relations/participates-in.md`

**Observation / Representation**
- Observes — `relations/observes.md`
- Represents — `relations/represents.md`

**Provenance / Lineage**
- Derived From — `relations/derived-from.md`

### Validation

All members are canonical Relation concepts. The view supports retrieval and comparison while preserving each relation's directionality, domain/range, logical characteristics, qualification requirements, and assertion semantics.

### Boundary

Array membership must not be interpreted as:

- inverse relation;
- subclassing;
- transitivity or symmetry;
- equivalence;
- causal relationship;
- shared domain/range;
- identical inference behavior.

Those meanings remain controlled by the individual Relation definitions.

## Cross-View Rule

A canonical concept may legitimately participate in more than one organization when the organizing dimensions are genuinely different.

For example, a canonical concept may be organized by semantic type in one downstream system, by technical function in another, and by application purpose in another. Such multiple organization does not create multiple canonical identities.

## Canonical-Identity Preservation Test

Every membership in this catalog must satisfy:

1. the target identity already exists in a canonical layer or has an explicitly governed candidate status;
2. the membership does not redefine the target;
3. the division criterion is explicit;
4. the members are comparable under the criterion;
5. the organization does not silently create an `is-a`, `part-of`, causal, observation, representation, measurement, or provenance assertion;
6. candidate concepts are not presented as canonical without promotion;
7. removal of a membership would not delete or redefine the member concept.

## Visitor Universe / Entry Depth

These organizational views are navigation structures over the same canonical corpus. Different visitors may enter at different depths, but no view creates audience-specific semantic definitions.

A machine consumer may resolve the view ID, division criterion, array, member ID, primary authority, and membership status. A human visitor may encounter only the practical organization and linked canonical entries.

## Lifecycle

This catalog is versioned as an organizational artifact. Changing a view requires revalidation of its scope, division criterion, arrays, memberships, candidate statuses, and cross-layer boundaries.

A change to a member's primary semantic definition does not automatically change the view; affected memberships must be rechecked.

## Decision

The four organizations above are admitted as **validated organizational views**, not as four additional V3.1 canonical Facet semantic entries. This preserves the current two-concept semantic nucleus while demonstrating concrete, reusable Facet organization over the published corpus.
