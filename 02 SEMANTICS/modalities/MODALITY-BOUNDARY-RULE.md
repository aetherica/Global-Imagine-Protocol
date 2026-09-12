# GIOP V3.1 — Modality Boundary Rule

**Status:** PROVISIONAL  
**Scope:** `02 SEMANTICS/modalities/`

## 1. Governing Boundary

`Modality` identifies a recognized semantic mode, channel, or manner. It does not replace the identity of the entity, activity, process, representation, or context involved.

## 2. Boundary Matrix

| Neighbor | Primary responsibility | Boundary |
|---|---|---|
| Class | kind of entity | Class identifies what kind of entity; Modality identifies a mode/channel |
| Property | attributable characteristic | Property describes a characteristic; Modality describes a recognized mode/channel |
| Condition | contextual condition | Condition describes circumstance; Modality describes mode/channel |
| State | temporal bearer state | State describes a bearer’s recognizable state; Modality describes semantic mode/channel |
| Context | setting/frame | Context supplies the frame; Modality supplies the relevant mode/channel |
| Activity | actual occurrence | Activity is what occurs; Modality describes the mode/channel relevant to it |
| Process | organized temporal course | Process organizes progression/activities; Modality is not a process |
| Procedure | prescribed way | Procedure specifies how an activity is to be carried out; Modality does not prescribe a procedure |
| Technique | domain-specific way of performing | Technique may implement or occur within a modality; they are not universal synonyms |
| Representation | information-bearing form | Representation carries information; Modality characterizes a mode/channel associated with access or use |
| Format | structural/syntactic specification | Format structures information; it is not a modality |
| Encoding | coding/transformation | Encoding transforms representation data; it is not a modality |
| Perception | perceptual interpretation/experience | Perception is the resulting interpretation/experience; modality is the mode of access |
| Observer | observing entity/model | Observer performs/represents an observing capability; modality characterizes the relevant mode |
| Quantity | measurable concept | Quantity is measurable; Modality is not inherently a measurable quantity |
| Relation | typed connection | Relation connects concepts/entities; Modality is a semantic concept, not a relation authority |

## 3. DICOM Boundary

DICOM modality terminology may identify equipment type, function, or technique, and acquisition modality has a specialized imaging meaning. These are domain applications and evidence for modality usage, not a universal definition of GIOP Modality.

## 4. Sensory Boundary

Sensory modality is not identical to Perception. Sensory modality concerns a recognized sensory mode/pathway; perception concerns perceptual interpretation or experience.

## 5. Interaction Boundary

Interaction modality is not identical to the hardware/software component implementing it and is not identical to the Activity performed through that channel.

## 6. Data Boundary

Data modality is not identical to representation, format, media type, encoding, or storage file semantics. A single modality may be expressed through multiple representations and formats.

## 7. Multimodal Boundary

`Multimodal` denotes combination or coordinated use of multiple modalities. It is not a single modality subtype.

## 8. Classification Boundary

A term may be a modality value in one controlled vocabulary and a Class, technique, device type, or other concept in another. GIOP must preserve authority scope rather than infer universal identity from lexical reuse.

## 9. Relation Boundary

This folder introduces no new relation predicates. Existing canonical relation authority must be used for cross-layer assertions.

## 10. Canonicalization Test

A candidate may be promoted only if it answers all of the following:

1. What recognized mode/channel/manner does it identify?
2. What domain and scope govern the term?
3. Why is it not merely a Class, Property, State, Condition, Context, Activity, Process, Procedure, Technique, Representation, Format, Encoding, or Perception?
4. Is the identity reusable beyond a single implementation?
5. Does independent evidence support the semantic boundary?
6. Does the candidate require a separate canonical identity rather than a terminology mapping?
