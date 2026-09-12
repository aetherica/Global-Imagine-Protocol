# Representation Knowledge Registry

**Status:** Active Semantic Knowledge Registry  
**Version:** 1.0.0  
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
| Format | Structural/syntactic specification | Format standards, HTTP, DCAT, RDF syntax practice | Distinct from Representation | `format.md` | Canonical Candidate |
| Encoding | Coding/transformation scheme | HTTP content coding and encoding practice | Distinct from Format and Representation | `encoding.md` | Canonical Candidate |
| Serialization | Abstract-to-concrete expression | RDF abstract/concrete syntax model | Distinct from resulting Representation; may also be an Activity when occurring | `serialization.md` | Canonical Candidate |
| Media Type | Interoperable data-type identification | RFC 9110 / IANA practice | Distinct from Format and Representation | `media-type.md` | Canonical Candidate |
| Compression | Representation-data transformation | HTTP / DCAT / fidelity analysis | Distinct from Encoding, Representation, and Fidelity | `compression.md` | Canonical Candidate |
| Packaging | Aggregation/containerization | DCAT / preservation practice | Distinct from Representation and File | `packaging.md` | Canonical Candidate |
| Profile | Specification specialization | W3C Profiles Vocabulary | Distinct from Format and Conformance | `profile.md` | Canonical Candidate |
| Conformance | Requirement-satisfaction assertion | W3C Profiles Vocabulary | Route to relation/assertion semantics | `relations` | Routed |
| File | Storage artifact | PREMIS | Do not collapse with Representation | appropriate storage/file semantics | Routed / preserved |
| Bitstream | Digital bit sequence/storage-level object | PREMIS | Do not collapse with Representation | appropriate storage/file semantics | Routed / preserved |

## Open Questions

1. Final promotion gate for each candidate concept.
2. Whether GIOP requires dedicated canonical File/Bitstream semantics in a future batch.
3. Exact canonical relation names for representation/profile/conformance assertions.
4. Whether specific format families should be admitted as controlled domain entries or remain externally specified.

## Evidence Notes

The registry records semantic synthesis, not quotations. Source definitions with materially different scope remain distinguishable.

## Visitor Universe Note

No visitor-specific duplicate concepts are registered. Audience relevance is implemented through entry depth and retrieval anchors in canonical entries.
