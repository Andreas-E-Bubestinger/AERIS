# AERIS Provenance Ledger

## Purpose

This document provides a public high-level provenance record for the AERIS (ÆRIS) research and development project created and developed by Andreas Erwin Bubestinger.

Its purpose is to document:

- project chronology
- continuity of development
- preserved AERIS generations
- selected technical milestones
- cryptographic commitments to private artefact states
- public research milestones

without disclosing the complete internal AERIS architecture.

This ledger is a provenance record, not a source-code publication.

---

## Project Identity

**Project:** AERIS (ÆRIS)  
**Project type:** Independent AI Systems & Governance Research Project

**Architect and Researcher:**  
Andreas Erwin Bubestinger  
Austria

**ORCID:**  
https://orcid.org/0009-0004-2944-2248

AERIS is independently developed.

No university, research institute, laboratory, company, or other institutional affiliation is implied by this repository unless explicitly stated for a specific external cooperation or publication.

The development lineage documented here belongs to the independent AERIS project.

This record does not claim exclusive ownership of the word or acronym AERIS in unrelated contexts.

---

## Provenance Principles

AERIS distinguishes several forms of provenance evidence.

Historical private artefacts, cryptographic commitments, public Git history, and externally maintained publication records do not provide identical forms of evidence and are therefore not treated as interchangeable.

### Historical Private Artefacts

Preserved AERIS archives contain modules, specifications, development material, tooling, and associated project metadata from earlier development periods.

These materials allow reconstruction of the internal development history.

Historical filesystem metadata is useful supporting evidence but is not treated as equivalent to an independently trusted timestamp.

### Cryptographic Commitments

SHA-256 digests are used to identify exact artefact states.

Publishing a digest allows AERIS to commit publicly to private material without disclosing the underlying implementation.

A digest published through this repository establishes a public commitment from the time of publication onward.

It does not, by itself, retroactively create an independent trusted timestamp for the historical creation date of the artefact.

### Public Git History

Git repository history provides an additional public chronology for material released through this repository.

The public GitHub repository was established after substantial private AERIS development had already taken place.

The first public Git commit therefore does not represent the beginning of the AERIS project.

### External Persistent Records

External repositories such as DOI-based publication systems provide independently accessible public records for released research outputs.

---

## Evidence Classes

This ledger uses the following evidence classes:

**HISTORICAL_PRIVATE**  
Preserved private project artefact with historical project metadata.

**PRIVATE_HASHED**  
Private artefact for which a cryptographic digest has been calculated and retained.

**PUBLIC_COMMITMENT**  
Cryptographic digest or provenance statement published through a public record.

**PUBLIC_REPOSITORY**  
Public version-control history.

**EXTERNAL_PERSISTENT_RECORD**  
Externally maintained persistent record such as a DOI repository.

An artefact or milestone may satisfy more than one evidence class.

---

# AERIS Version Lineage

AERIS has been preserved across successive development generations from V1 through V9.

Separate historical version archives exist for the individual AERIS generations, including V1, V2, V3 and V4.

An additional combined V1–V4 archive also exists, but it is not the sole provenance source for those generations.

Version numbers represent project generations rather than claims that every subsystem changed simultaneously between releases.

Later generations may contain material inherited from earlier generations. For that reason, internal file dates may overlap between versions.

The date ranges below are therefore described as **preserved artefact windows** rather than exact release dates.

---

## AERIS V1

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
18–19 May 2025

V1 represents the earliest preserved modular AERIS generation in the current provenance set.

The preserved material already addresses high-level areas including:

- modular system organisation
- interaction and collaboration
- memory and experience handling
- reflective and meta-reflective processing
- resonance-related processing
- presence and self-reference
- conflict handling
- integrity and self-protection concepts

This description reflects the preserved artefact set and does not imply that later AERIS architecture already existed in its mature form at that time.

**V1 Tree Commitment — SHA-256**

`1b411bed5c3596cf6a642a99e3ec798a29406b67a1a1252104041df8921ccf30`

---

## AERIS V2

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
18 May 2025

V2 is preserved as a relatively small transitional development snapshot.

It contains a more limited artefact set than the broader architectures preserved in later generations.

Its provenance value lies in preserving an intermediate development state within the early AERIS lineage rather than in representing a complete mature architecture.

**V2 Tree Commitment — SHA-256**

`04572693c9642c082aa67ab1ccab797eef7a51732ed6cefd585b6232f48fd389`

---

## AERIS V3

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
21 May–7 July 2025

V3 substantially expands the preserved modular architecture.

High-level development areas represented in this generation include:

- broader modular coordination
- memory and experience processing
- reflective architecture
- ethics and integrity-related structures
- evidence and validation concepts
- contextual adaptation
- interaction and relationship modelling
- environment-related research
- project and work-oriented functions

V3 marks a clear expansion from the small early artefact sets toward a broader systems architecture.

**V3 Tree Commitment — SHA-256**

`fcb8697af82b00c1c613d5c8010b1886abf30a608f545b9fe541bc53adb67e51`

---

## AERIS V4

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
21 May–8 October 2025

V4 represents a major structural expansion of the project.

The preserved generation contains distinct core and work-oriented areas together with development tooling, archived states, experimental material, and structured project instructions.

High-level areas include:

- orchestration and routing
- memory and continuity
- system state
- modular coordination
- evidence and validation
- reflective processing
- controlled experimentation
- project-specific work functions
- import and reconstruction tooling

V4 demonstrates the transition from a collection of individual research modules toward a more explicitly organised architecture.

**V4 Tree Commitment — SHA-256**

`b4dcc69039061784ecb3af8aa015d745d991a0ae708c182ec75ee68008d68af7`

---

## Additional Combined V1–V4 Historical Archive

In addition to the individually preserved V1–V4 generations, a combined historical archive exists:

`Aeris 1-4.0.tar`

**Archive SHA-256**

`1c6e2612dd91f6494e431836200f686e4a9683d66880b85f3cfb46d895c63e42`

This combined archive is an additional provenance container.

It should not be interpreted as the only surviving source for AERIS V1 through V4.

---

## AERIS V5

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
2 September–7 December 2025

V5 consolidates the expanding AERIS architecture into a more clearly structured core/work configuration with associated build and import tooling.

The generation continues development in areas such as:

- modular orchestration
- interaction
- memory-related functions
- governance
- validation
- project-oriented capabilities
- controlled architecture packaging

**Original Archive SHA-256**

`1f538fe3ec649e78224382a26d0bd7c38e93efd8cff343400ea21a6b3df1f375`

**V5 Tree Commitment — SHA-256**

`ba958aedb68bc823aa919e8c7da4a7d831e0c946849022291326f3784197a2ff`

---

## AERIS V6

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
2 September 2025–5 August 2026

V6 develops the project further toward an explicit systems and runtime architecture.

The preserved generation includes development in areas such as:

- runtime topology
- functional continuity
- relational and operational state
- integrity
- curiosity and exploration
- architecture evaluation
- cognitive profiling research
- governance
- model-facing runtime integration

Some material in this generation originates from earlier development stages and was retained or evolved into the V6 architecture.

**Original Archive SHA-256**

`3745fa7cc6413b82c37387924b1773e19629baeead173c1170a23c245baca67e`

**V6 Tree Commitment — SHA-256**

`1a01676e6a0c0e95be52b24e31d0c4b31955f2c3c7fa15e25997dac0e023cb13`

---

## AERIS V7

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
4 October 2025–17 September 2026

V7 represents another substantial expansion toward the modern AERIS systems architecture.

High-level development areas represented in the preserved generation include:

- structured memory infrastructure
- continuity mechanisms
- self-model-related state
- runtime provider abstraction
- provenance and fingerprinting
- action lifecycle research
- dialogue initiative
- responsibility and egress governance
- resource governance
- runtime reliability
- embodiment-related state
- architecture conformance and validation

V7 also contains substantial development and validation material associated with increasingly evidence-oriented architecture testing.

**Original Archive SHA-256**

`528305be942ba47b2648bd76fac30d4fc47e9583c2e726a35536a6cbb56ec600`

**V7 Tree Commitment — SHA-256**

`fe5b39a573dd141db70fb4a4e7f675ecb182f4b2fd6018f24e7ddb5d4a15aca6`

---

## AERIS V8

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window:**  
4 October 2025–9 October 2026

V8 consolidates and extends the systems architecture developed through earlier generations.

The preserved generation continues major research lines including:

- memory
- continuity
- governance
- action and dialogue
- provenance
- state
- embodiment
- provider abstraction
- architecture validation

and adds further integration around AERIS system identity, agent governance, release authority, and higher-level architecture coordination.

Differences in archive size or artefact count between generations should not automatically be interpreted as architectural growth or regression, because archive composition and retained historical material differ.

**Original Archive SHA-256**

`f04cf3fd5edaba898c71e06a4fa769c1a8534425acd104e1d7db761d9fa153f0`

**V8 Tree Commitment — SHA-256**

`dc7e73e99720b959d902b8fdbfedbb3b97a52437338ebc88f7b89b48058443ac`

---

## AERIS V9

**Evidence class:** HISTORICAL_PRIVATE / PRIVATE_HASHED / PUBLIC_COMMITMENT

**Preserved artefact window of the committed archive:**  
17–23 October 2026

V9 is the current major AERIS generation represented by this provenance commitment.

It continues the architecture established in previous generations while extending the project in areas including:

- deterministic reconstruction
- bootstrap and seed architecture
- generation and integration management
- architecture materialisation
- provenance-bound reconstruction
- identity and state integrity
- validation infrastructure
- model/provider-independent system integration

The V9 artefact set also contains Web / Seed development material alongside the evolved modular architecture.

V9 should not be interpreted as a single completed release state.

Individual V9 subsystems and research lines maintain separate validation and claim boundaries.

**Original Archive SHA-256**

`1ccd3621cd0cd138a818ae45139a716f1fac440355553745e067bf0077d08457`

**V9 Tree Commitment — SHA-256**

`fef090673ad1fedd20280130b33195fa0e2e395b4a3b09095f2eb81492185dc9`

---

# Tree Commitment Method

The per-version tree commitments above were generated on 29 October 2026 from preserved AERIS artefacts.

They are deterministic content commitments rather than historical timestamps.

For each version:

1. all regular files belonging to the version are enumerated;
2. each file is identified by its path relative to the corresponding version root;
3. the SHA-256 digest of the exact file bytes is calculated;
4. records are sorted deterministically by relative path;
5. the path and corresponding content digest are combined into a canonical record stream;
6. the resulting record stream is hashed using SHA-256.

This provides a single digest representing the preserved file set and the exact content of the included files.

For V1 through V4, the tree commitments identify each generation separately.

Separate original version archives also exist.

The combined V1–V4 archive is retained as an additional historical container.

These commitments were generated in 2026 and must not be interpreted as independently trusted timestamps for historical artefact dates in 2025.

---

# Selected Development Milestones

## 2025 — Transition from Modular Research to Systems Architecture

Across the preserved V1–V5 lineage, AERIS developed from early modular research artefacts toward a progressively structured architecture incorporating areas such as:

- memory
- continuity
- reflection
- interaction
- validation
- governance
- orchestration
- project-specific functions

The preserved version lineage demonstrates incremental development rather than a single retrospectively constructed architecture.

---

## 2025–2026 — AERIS Portable Development

AERIS Portable developed as a local experimental runtime alongside the evolving modular architecture.

The Portable line introduced practical runtime engineering in areas including:

- local model interaction
- middleware
- memory and state
- project interaction
- browser interfaces
- speech
- validation
- controlled system actions
- runtime diagnostics

Portable development is documented separately from Web / Cloud claims because the corresponding execution environments and evidence requirements differ.

---

## 2026 — Evidence-Oriented Architecture Validation

AERIS development increasingly incorporated controlled experimental validation.

Depending on the mechanism under investigation, this includes:

- repeatability testing
- negative controls
- ablation
- comparison and sham conditions
- frozen evaluation criteria
- cryptographic evidence binding
- explicit claim ceilings

Positive, negative, and inconclusive findings remain part of the development record.

A failed or inconclusive validation is not silently converted into a positive result.

---

## August 2026 — Curiosity and Revisit Path

A controlled AERIS Portable pathway for persistent unresolved-question tracking and revisitation reached native integration testing.

This establishes a technical mechanism for retaining and revisiting unresolved-question state.

It does not establish unrestricted autonomous curiosity.

---

## August 2026 — Project Interaction

AERIS Portable reached a native browser-to-project interaction pathway with controlled project operations and verification.

Further workspace and artefact integration remains an active development area.

This milestone does not imply unrestricted filesystem access or unrestricted autonomous modification.

---

## 2026 — Speech and Multimodal Presence

AERIS Portable expanded into speech and visual-presence research.

Speech input/output and visual-presence infrastructure became part of the local runtime research line, while broader multimodal and embodiment functions continued to develop separately.

---

## September–October 2026 — 3D Embodiment and Motion

AERIS developed an additional experimental 3D embodiment path while retaining its existing 2D presence architecture.

Research areas include:

- 3D representation
- rigging and rendering
- identity-consistent appearance
- expression
- motion ingestion
- motion validation
- virtual-environment research
- future state-to-embodiment integration

Individual 3D and motion artefacts maintain separate build, visual, runtime, and promotion states.

No blanket production-readiness claim is made for the complete embodiment line.

---

## October 2026 — Controlled Cognitive Heartbeat Research

AERIS Portable includes a controlled Cognitive Heartbeat research line.

Heartbeat-related pathways progressed through bounded experimental stages, including controlled turn-connected execution.

This does not establish continuously active autonomous operation.

AERIS explicitly distinguishes controlled execution from persistent autonomous operation.

---

## October 2026 — AERIS 9.0 Web / Seed PRE-RC1 Qualification

Within the V9 generation, the Web / Seed line reached a formally qualified PRE-RC1 reproducibility milestone.

The qualified bootstrap state was tested through independent reconstruction in separate blank project environments using the same byte-identical seed.

**Qualified V0.26.6 Seed SHA-256**

`812bea7c7b54e4596dab521a2c365e5d6be87e213504039c8feda48ecbcb5c64`

Independent comparison showed no non-volatile differences after exclusion of explicitly permitted run/time provenance fields.

This qualification applies to the corresponding Web / Seed bootstrap line.

It does not establish equivalent validation of Portable, embodiment, continuous autonomous operation, or phenomenological claims.

Later V9 development exists above this qualified bootstrap substrate and should not be conflated with the V0.26.6 PRE-RC1 freeze.

---

## 22 October 2026 — Public Methodological Research Record

The following methodological research work was published through Zenodo:

*A Target-Blind Framework for Corpus-Based Cognitive Profiling: Leakage Control, Benchmark Replication, and Prevalidation Toward External Calibration*

DOI:

https://doi.org/10.5281/zenodo.23574384

The work investigates methodological prerequisites for corpus-derived cognitive profiling and its potential use in adaptive human–AI interaction.

The publication is associated with the broader AERIS research programme but does not disclose the internal AERIS architecture.

**Evidence class:** EXTERNAL_PERSISTENT_RECORD

---

## October 2026 — Public AERIS Identity Repository

A public GitHub repository was established under:

**Andreas-E-Bubestinger / AERIS**

The repository provides a canonical public identity layer for the independent AERIS research project.

It contains public information concerning:

- project identity
- research scope
- publications
- selected research status
- provenance commitments

The repository intentionally does not contain the complete internal AERIS source code or architecture.

The beginning of public Git history therefore must not be interpreted as the beginning of AERIS development.

**Evidence class:** PUBLIC_REPOSITORY / PUBLIC_COMMITMENT

---

# Public and Private Provenance Boundary

Public provenance material may include:

- high-level chronology
- version identifiers
- selected technical milestones
- public research outputs
- cryptographic commitments
- validation status
- explicit claim boundaries

The following remain non-public unless separately released:

- complete historical module sets
- complete source code
- detailed module architecture
- operational prompts
- internal routing and orchestration logic
- state operationalisation
- thresholds and parameters
- private schemas
- detailed capability-control mechanisms
- complete unpublished validation harnesses
- private evidence archives

A published cryptographic digest does not grant access to or a licence for the underlying private artefact.

---

# Interpretation of Priority

This ledger documents the chronology of the independent AERIS project and publicly commits to preserved artefact states.

It may provide evidence that particular research areas, architectures, or artefact states were present within AERIS by documented stages of its development history.

It does not by itself establish:

- patent priority
- exclusive ownership of general concepts
- exclusive rights to the name AERIS
- that independently developed similar concepts originated from AERIS
- that historical filesystem metadata constitutes an independently trusted timestamp
- that a commitment published in 2026 independently proves a historical creation date in 2025

Questions of intellectual-property priority depend on the particular protected material, available evidence, and applicable legal framework.

---

# Future Provenance Procedure

For significant future AERIS milestones, the preferred provenance procedure is:

1. preserve the canonical private artefact;
2. calculate cryptographic commitments;
3. record the project version and exact scope;
4. state the claim supported by the artefact;
5. state what the artefact does not establish;
6. publish an appropriate digest or provenance record without disclosing protected implementation material;
7. where warranted, associate the commitment with an external persistent or trusted timestamp.

This allows the public provenance chain to become progressively stronger while the protected AERIS architecture remains private.

---

# Status

This ledger is maintained as an additive public provenance record.

Historical technical results are not silently rewritten when later evidence changes their interpretation.

Corrections, superseding evidence, or revised claim boundaries should be recorded explicitly.

**Project:** AERIS (ÆRIS)  
**Architect and Researcher:** Andreas Erwin Bubestinger  
**Status:** Active research and development  
**Public provenance ledger established:** October 2026
