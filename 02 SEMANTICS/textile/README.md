# Textile Semantic Domain

**Semantic Domain:** Textile
**Status:** IMPLEMENTATION-COMPLETE — V3.1 SEED / CANDIDATE DOMAIN
**Authority Boundary:** Textile owns textile-domain concepts from fibre/yarn through fabric and textile structures/finishes. Generic Material, Property, Quantity, Process, and Activity semantics remain in their existing layers.

## Core Seed Concepts

1. Textile — material/product domain concept for flexible textile structures and textile articles.
2. Textile Fibre — constituent textile fibre/filament concept.
3. Yarn — continuous textile strand formed from fibres/filaments or other specified constructions.
4. Fabric — textile structure produced by interlacing, interlooping, bonding, felting, or other construction mechanisms.
5. Textile Structure — organization of fibres, yarns, loops, layers, or other constituents that defines textile construction.
6. Textile Finish — post-formation treatment or finish that modifies a textile article or surface; individual treatments route to Process/Condition/Property where appropriate.

## Scope

The domain includes natural and manufactured fibres, yarn forms, woven/knit/nonwoven and related fabric structures, textile surface/finish semantics, composition, and article-level textile identification. Fibre/yarn morphology is especially important because ISO 8159:2025 establishes principal vocabulary for forms of textile fibres and yarns up to cabled yarns. citeturn708541search1

## Boundary Rules

- Generic Material is not duplicated; Textile qualifies materials for textile-domain use.
- Fibre/yarn/fabric production operations belong to Process/Activity.
- Quantitative fibre content and textile test values belong to Quantity/Property/Measurement with Textile as domain context.
- Garments are constructed articles that may contain textile materials; Garment semantics belong in `garment/`.
- Care labels and treatment symbols are representation/usage semantics over textile articles, not a second ontology.

## Important distinctions

**Fibre vs Yarn:** fibre/filament is a constituent unit or continuous element; yarn is an assembled strand structure.

**Yarn vs Fabric:** yarn is an intermediate textile structure/material; fabric is a higher-order planar or otherwise constructed textile structure.

**Fabric vs Garment:** fabric is a textile structure/material/article component; garment is an assembled wearable article.

**Textile vs Material:** textile is a domain-qualified material/article concept, not a replacement for generic Material.

## Evidence Basis

ISO 8159:2025 provides current terminology for fibre and yarn morphology. ISO 1833 provides quantitative chemical analysis methods for textile fibre mixtures. ISO 3758:2023 defines textile care-labelling symbols for supplied textile articles. citeturn708541search1turn454778search7turn454778search2

## Lifecycle

Seed implementation → cross-layer validation → Gate-J → Active Canonical.

## Retrieval Anchors

`TEXTILE`, `TEXTILE FIBRE`, `FIBRE`, `FILAMENT`, `YARN`, `FABRIC`, `WOVEN`, `KNIT`, `NONWOVEN`, `TEXTILE STRUCTURE`, `TEXTILE FINISH`
