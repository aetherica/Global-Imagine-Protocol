# Color — Knowledge Registry

**Status:** IMPLEMENTATION-COMPLETE — COORDINATION  
**Semantic ID:** `SEM-COLOR-DOMAIN-001`  
**Version:** 0.1.0

## Registry Rule

This registry records controlled colour-related retrieval terms and their semantic routing. Entries are coordination records, not independent canonical Color concepts unless an existing GIOP authority already owns the target.

| Term / family | Routing | Treatment |
|---|---|---|
| Color / Colour | Color domain | Lexical intake aliases |
| Perceived Color | Perception | Observer/context qualified |
| Color Appearance | Perception | Viewing-condition qualified |
| Color Characteristic | Property | Bearer-specific and conditional |
| Chromaticity | Quantity/Property | Defined coordinate/system required |
| Tristimulus Value | Quantity/Quantity Value | Specified observer/system required |
| Color Difference | Quantity/validation context | Specified colour space required |
| Color Space | Representation | Geometric/system representation |
| Color Space Encoding | Representation/Encoding | Digital encoding, not colour identity |
| ICC Profile | Representation/Profile | Transformation/profile authority |
| Palette | Representation | Encoded/display vocabulary |
| Color Map | Representation | Mapping/visualization construct |
| False Color | Representation | Visualization mapping; not literal object colour |
| Color Measurement | Activity/Measurement | Event, not colour identity |
| Color Measurement Result | Result | Result with values/uncertainty/context |
| Color Rendering | Viewing/illumination/perception | Effect/context semantics |
| Metamerism | Colorimetry/measurement context | System-relative equivalence |
| Pigmentary Coloration | Material/physical domain | Mechanism family |
| Structural Coloration | Material/physical domain | Mechanism family |
| Emissive Coloration | Physical/optical domain | Mechanism family |
| Interference Coloration | Physical/optical domain | Mechanism family |
| Scattering Coloration | Physical/optical domain | Mechanism family |
| Responsive/Dynamic Color | State/Activity/Process/material domain | Target-dependent |
| Color Signal | Context/Function/Representation | Functional use |
| Safety Color | Context/standard/Representation | Normative convention |
| Biological Color Signal | Domain signal/function | Context dependent |
| Color Name | Terminology/linguistic context | Lexical form |
| Color Category | Linguistic/cognitive context | Language/task dependent |
| Color Fastness | Textile/BIL/validation | Integrity/quality context |
| Color Consistency | Validation/integrity context | Not intrinsic Color identity |

## Controlled Negative Mappings

- `Color` must not be registered as a synonym of `Perception`.
- `Color` must not be registered as a synonym of `Property`.
- `Color Space` must not be registered as a synonym of `Color`.
- `Pixel Color` must not imply intrinsic surface colour.
- `Red = danger` must not be encoded as an intrinsic semantic law.
- A colour-generation mechanism must not be promoted as Color itself.
- A validation metric must not be promoted as a Color concept.

## External Terminology Note

CIE, ISO/CIE, ICC, W3C, DICOM, PATO, CIDOC CRM, Getty AAT and domain literature provide evidence and terminology variants. Their identifiers and axioms are not imported as GIOP canonical identities by this registry.
