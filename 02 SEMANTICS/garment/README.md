# Garment Semantic Domain

**Semantic Domain:** Garment
**Status:** IMPLEMENTATION-COMPLETE — V3.1 SEED / CANDIDATE DOMAIN
**Authority Boundary:** Garment owns wearable assembled-article semantics: garment identity, components, construction, sizing, fit, and fastening/closure concepts. Textile materials remain owned by `textile/`; body measurements remain owned by relevant anthropometry/quantity semantics; wear/donning states remain in State/Activity.

## Core Seed Concepts

1. Garment — an assembled wearable article intended to cover/support a body or body region.
2. Garment Component — a constituent part of a garment such as sleeve, collar, waistband, pocket, panel, lining, or fastening component.
3. Garment Construction — the structural organization and assembly of garment components into an article.
4. Garment Pattern — a geometric/template representation used to define garment component shape and construction; the representation itself remains owned by Representation.
5. Garment Size Designation — a size designation associated with intended body dimensions or sizing systems.
6. Garment Fit — the relationship between garment geometry/allowance and the intended body dimensions/shape under a declared wear condition.
7. Garment Fastening — a garment-domain mechanism or component used to secure/close an article, such as buttons, zippers, snaps, hooks, ties, or equivalent closures.

## Scope

Garment semantics include clothing articles, apparel components, construction, sizing, fit, closures, and wear-context distinctions. They cover conventional and specialized garments, including adaptive, protective, performance, ceremonial, theatrical, virtual-production, and reconstructed garments.

## Boundary Rules

- Textile owns fibre/yarn/fabric/material-structure semantics.
- Generic Material remains the owner of material semantics; Garment qualifies material use in apparel.
- Anthropometric quantities and measurements are not duplicated; Garment references them for sizing and fit.
- Pattern geometry is a representation; the Representation layer remains authoritative.
- Manufacturing, sewing, cutting, finishing, laundering, and alteration are Processes/Activities.
- Wearing, donning, doffing, damaged, wet, folded, and similar conditions are State/Activity concepts or domain-qualified applications, not new garment ontology layers.

## Standards Evidence

ISO 8559-1 provides anthropometric measurement definitions for clothing applications; ISO 8559-2 defines primary and secondary garment dimensions and explicitly distinguishes body measurements from garment measurements; ISO 8559-3 defines methods for body measurement tables and intervals used for ready-to-wear sizing. The current ISO/TC 133 catalogue also lists later parts dealing with coverage ratios and head/face measurements. citeturn454778search4turn454778search0turn454778search12turn454778search5

## Core Distinctions

**Garment vs Textile:** assembled wearable article vs textile material/structure.

**Garment Size vs Garment Measurement:** size designation is a standardized/intended fit indicator; garment measurements are product geometry/measurements and are not interchangeable.

**Fit vs Size:** size is designation/classification; fit is the resulting relationship between article and body under a specified context.

**Garment Component vs Accessory:** component participates in garment construction; an accessory may be attached/used with a garment without being structurally part of it.

## Lifecycle

Seed implementation → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`GARMENT`, `CLOTHING`, `APPAREL`, `GARMENT COMPONENT`, `GARMENT CONSTRUCTION`, `GARMENT PATTERN`, `GARMENT SIZE`, `GARMENT FIT`, `FASTENING`, `CLOSURE`
