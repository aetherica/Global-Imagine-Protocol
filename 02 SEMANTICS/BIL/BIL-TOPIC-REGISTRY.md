# BIL Topic Registry — V3.1 Research Dataset

**Status:** RESEARCH / CANDIDATE REGISTRY  
**Primary Responsibility:** Controlled retention and routing of discovered BIL topic-space  
**Canonical status:** None of the rows below is canonical merely by registry inclusion.

## Registry Rule

Each topic is retained first, then classified against existing GIOP semantic ownership. A topic becomes BIL-native only when its integrity responsibility remains distinct after duplicate and boundary analysis.

## Topic Families

### 01 — Biological Subject
Human; animal; wildlife; bird; mammal; reptile; amphibian; fish; insect; arachnid; mollusc; plant; fungus; algae; microorganism; synthetic biological form; hybrid/engineered organism; multi-organism.

### 02 — Anatomical / Structural
Face; head; eye; ear; nose; mouth; hand; finger; limb; torso; skeleton; joint; muscle contour; soft tissue; body surface; species-specific anatomy; deformity; prosthetic anatomy.

### 03 — Identity
Individual identity; species identity; facial identity; body identity; morphology signature; asymmetry; stripe/spot/coat pattern; scar; tattoo; mole; birthmark; biological marking; identity-bearing feature; identity persistence; identity attribution; re-identification.

### 04 — Morphometry / Anthropometry
Height; body dimensions; inter-landmark distances; ratios; angles; circumference; volume; silhouette measurements; species morphometry; population variation; individual deviation; measurement uncertainty.

### 05 — State
Pose; expression; wet/dry; alert/resting; running; flying; swimming; feeding; threat display; physiological appearance; fatigue; exercise state; garment state; environmental state.

### 06 — Behaviour / Action
Gesture; gait; stride; flight; swimming; feeding; hunting; throwing; catching; kicking; jumping; dancing; coordinated behaviour; species behaviour; behavioural signature.

### 07 — Motion / Dynamics
Translation; rotation; acceleration; deceleration; deformation; body motion; limb motion; hair/fur/feather motion; cloth motion; object trajectory; motion blur; motion continuity.

### 08 — Group / Collective Configuration
Pair; trio; team; ensemble; crowd; formation; spacing; alignment; role assignment; group membership; synchrony; choreography; team formation; crowd flow; member persistence.

### 09 — Clothing / Fabric / Wearables
Garment identity; garment-body correspondence; fabric type; weave; knit; pattern; print; seam; fold; wrinkle; drape; stretch; compression; transparency; gloss; roughness; wet fabric; dirty/torn fabric; shoes; glasses; helmet; mask; jewelry.

### 10 — Held / Carried / Attached Objects
Phone; camera; tablet; microphone; book; bottle; cup; food; shopping bag; handbag; backpack; suitcase; umbrella; tool; sports equipment; musical instrument; medical device; wheelchair; cane; crutch.

### 11 — Human/Object Interaction
Holding; grasping; gripping; touching; carrying; wearing; attaching; supporting; pushing; pulling; throwing; catching; kicking; operating; hand-object contact; body-object contact; object affordance; contact region; contact-induced deformation.

### 12 — Surface / Support / Contact
Ground; floor; road; grass; soil; sand; mud; rock; concrete; wood; metal; glass; mirror; water surface; ice; snow; wall; chair; table; vehicle surface; foot-ground contact; body support; suspension; balance.

### 13 — Water / Fluids / Particulates
Water; rain; droplet; splash; mist; fog; steam; condensation; sweat; tears; saliva; mud; dust; sand; snow; ice; oil; paint; foam; smoke; ash; particles; wetness; water film; dripping.

### 14 — Hair / Fur / Feather / Fiber
Hair strands; hair mass; hairline; curl; wave; frizz; clumping; wet hair; wind deformation; fur density; fur length; fur direction; coat pattern; wet fur; feather arrangement; wing feathers; feather layering; wet feathers; fiber orientation; anisotropic appearance.

### 15 — Skin / Tissue / Biological Material
Pigmentation; skin tone; melanin-related appearance; hemoglobin-related appearance; absorption; scattering; subsurface scattering; specularity; roughness; hydration; oiliness; sweat; pores; wrinkles; freckles; scars; bruises; redness; pallor; translucency; animal tissue; scale surface; bioluminescent tissue.

### 16 — Ocular
Eye geometry; gaze; iris; pupil; sclera; cornea; eyelid; lash; blink; catchlight; reflection; refraction; tear film; eye wetness; eye-shine; species-specific pupil shape; nocturnal eye response.

### 17 — Environment / Habitat
Indoor; outdoor; forest; desert; ocean; river; wetland; grassland; mountain; urban; rural; stage; studio; nest; den; burrow; hive; reef; habitat; territory; migration corridor; ecological context.

### 18 — Observation / Imaging Geometry
Viewpoint; view direction; perspective; field of view; distance; elevation; azimuth; projected size; depth ordering; parallax; foreshortening; occlusion geometry; multi-view correspondence; camera-dependent appearance.

### 19 — Optical Evidence
Lighting; highlight; shadow; self-shadow; cast shadow; contact shadow; reflection; refraction; transmission; subsurface scattering; caustics; glare; bloom; lens flare; atmospheric scattering; reflected identity; shadow correspondence.

### 20 — Visibility / Occlusion / Hidden Structure
Visible; partially visible; occluded; amodal structure; inferred structure; reconstructed structure; ambiguous structure; unavailable evidence; concealed hand; hidden body; hidden animal marking; occlusion recovery.

### 21 — Scale / Resolution / Granularity
Macro; close-up; medium; wide; aerial; microscopic; pixel-level; part-level; object-level; subject-level; scene-level; resolution sufficiency; scale-aware evidence.

### 22 — Representation
Still image; frame sequence; burst; stereo; multi-view; depth map; mask; alpha matte; mesh; texture; point cloud; Gaussian representation; volumetric representation; animation; motion capture; rendered frame; generated image; generated video; composite; VFX plate.

### 23 — Temporal Integrity
Frame-to-frame identity; pose continuity; appearance continuity; lighting continuity; shadow continuity; reflection continuity; deformation continuity; object persistence; trajectory continuity; event continuity; temporal drift; flicker; morphing; identity swap; object popping.

### 24 — Biological Change / Lifecycle
Growth; age progression; maturation; weight change; muscle development; pregnancy; hair growth; scar evolution; injury recovery; disease progression; seasonal coat change; molting; feather replacement; plant growth; flowering; leaf development; animal maturation.

### 25 — Transformation / Reconstruction
Crop; scale; resize; denoise; deblur; sharpen; relight; recolour; grade; retouch; inpaint; outpaint; pose edit; expression edit; body reshape; object insertion/removal/replacement; background replacement; style transformation; image-to-image; text-to-image; image-to-video; video-to-video; 3D reconstruction; 4D reconstruction; VFX.

### 26 — Integrity Threats / Manipulation
Morphing; identity blending; identity interpolation; multiple-identity composition; spoofing; presentation attack; replay; mask/prosthetic; reference substitution; reference tampering; synthetic substitution; identity contamination; adversarial presentation.

### 27 — Reference / Evidence Lifecycle
Reference acquisition; reference selection; reference quality; reference sufficiency; sample; feature; template; model; reference configuration; identity binding; version; lineage; renewal; revocation; retirement; reference conflict; evidence coverage.

### 28 — Invariance / Permitted Variation
Identity invariant; structural invariant; pattern invariant; conditional invariant; permitted pose change; permitted expression change; declared styling; declared anatomy change; unconstrained variable; unknown/unobservable variable; intentional deviation; unintended deviation.

### 29 — Evaluation / Validation
Geometric validation; landmark error; morphometric comparison; pixel comparison; colour difference; photometric validation; optical validation; material validation; relational validation; temporal validation; physical validation; species validation; group validation; cross-view validation; cross-representation validation; expert review.

### 30 — Uncertainty / Evidence Conflict
Measurement uncertainty; observation uncertainty; model uncertainty; reference uncertainty; identity confidence; evidence confidence; ambiguous evidence; conflicting evidence; evidence fusion; evidence weighting; evidence sufficiency; conflict escalation; human adjudication.

### 31 — Provenance / Trust / Decision
Reference origin; capture history; transformation history; validation history; provenance binding; evidence provenance; human review; automated review; override; final adjudication; preserved history; supersession; decision state.

## Profile Contexts

Candidate context/profile labels include Human Portrait, Wildlife, Nature, Sports, Dance/Performance, Fashion, Documentary, Scientific, Medical, Macro, Group/Crowd, VFX, Virtual Production, Digital Human, Synthetic Creature, Fantasy, Sci-Fi, Horror, Historical/Retro, Commercial, Still, Video, 3D/4D.

Profiles are routing/configuration metadata and do not create alternate canonical meanings.

## Candidate Interpretation Rules

- Subject names are not automatically BIL semantic concepts.
- Materials and objects remain under their existing semantic ownership unless a distinct BIL responsibility is established.
- Metrics, formulas, thresholds and model names remain evidence/method/profile material unless independently promoted.
- Provenance authenticity is distinct from biological integrity.
- Physical plausibility is distinct from reference fidelity.
- Unknown or unobservable evidence is not automatically failure.
- Component correctness does not guarantee configuration correctness.
- A change is not automatically an integrity failure; intent and declared transformation context matter.

## Initial Status

**Registry populated with the discovered first-wave BIL topic universe.**

The registry is a retention and routing layer. Candidate entries require ownership mapping, boundary testing, evidence review, and applicable Foundation promotion gates before canonical semantic promotion.
