# Representation Knowledge Registry

**Status:** Active Semantic Knowledge Registry  
**Version:** 1.1.0  
**Purpose:** Retain representation-related concepts, decisions, evidence status, and routing without becoming a parallel canonical knowledge base.

## Registry Rules

The registry follows the GIOP Knowledge Entry & Canonicalization Rule:

`RETAIN → CLASSIFY → VERIFY → CONFLICT ANALYSIS → SYNTHESIZE → DECIDE → AUTHOR → VALIDATE`

A registry record is not automatically canonical. Canonical semantic content is authoritative only in the appropriate semantic entry.

## Registry

| Candidate | Semantic responsibility | Evidence basis | GIOP decision | Destination | Status |
|---|---|---|---|---|---|
| Representation | Information-bearing form | HTTP, RDF, DCAT, PREMIS, PROV, PROF, OAIS | Distinct reusable semantic concept | `representation.md` | Active |
| Display | Presentation mechanism | Existing GIOP entry | Existing identity preserved | `display.md` | Active |
| Format | Structural/syntactic specification | Format standards, HTTP, DCAT, RDF syntax practice | Distinct from Representation; final promotion passed | `format.md` | Active |
| Encoding | Coding/transformation scheme | HTTP content coding and encoding practice | Distinct from Format and Representation; final promotion passed | `encoding.md` | Active |
| Serialization | Abstract-to-concrete expression | RDF abstract/concrete syntax model | Distinct from resulting Representation and Activity; final promotion passed | `serialization.md` | Active |
| Media Type | Interoperable data-type identification | RFC 9110 / IANA practice | Distinct from Format and Representation; final promotion passed | `media-type.md` | Active |
| Compression | Representation-data transformation | HTTP / DCAT / fidelity analysis | Distinct from Encoding, Representation, and Fidelity; final promotion passed | `compression.md` | Active |
| Packaging | Aggregation/containerization | DCAT / preservation practice | Distinct from Representation and File; final promotion passed | `packaging.md` | Active |
| Profile | Specification specialization | W3C Profiles Vocabulary | Distinct from Format and Conformance; final promotion passed | `profile.md` | Active |
| Conformance | Requirement-satisfaction assertion | W3C Profiles Vocabulary | Route to relation/assertion semantics | `relations` | Routed |
| File | Storage artifact | PREMIS | Do not collapse with Representation | appropriate storage/file semantics | Routed / preserved |
| Bitstream | Digital bit sequence/storage-level object | PREMIS | Do not collapse with Representation | appropriate storage/file semantics | Routed / preserved |

## Promotion Decision

The seven representation-related candidates have now passed the scoped final promotion gates and are Active canonical semantic concepts at the generic responsibility level. This does not automatically promote individual format families, codecs, registered media types, application profiles, package formats, or encoding families.

## Evidence Notes

The registry records semantic synthesis, not quotations. Source definitions with materially different scope remain distinguishable. External specifications remain evidence sources rather than GIOP authority.

## Visitor Universe Note

No visitor-specific duplicate concepts are registered. Audience relevance is implemented through entry depth and retrieval anchors in canonical entries.
