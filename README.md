# QGF Score Specification v0.1

## Question Gravitational Field Score

**QGF Score** is a minimal specification for measuring the structural influence of a question.

It estimates how strongly a question attracts thought, AI responses, structural derivatives, trace records, lineage relations, and civilizational discourse.

In short:

> A strong question does not merely ask for an answer.  
> It bends the structure of thought around it.

---

## Status

```text
Version: v0.1
Status: Draft
Scope: Conceptual / Structural Measurement
Legal status: Non-legal / Non-deterministic
```

This specification does **not** determine legal authorship, copyright ownership, monetary entitlement, or originality by itself.

It is intended as a structural observation and measurement layer.

---

## Purpose

The purpose of QGF Score is to estimate the gravitational field created by a question.

A question may generate:

- new concepts
- AI responses
- articles
- specifications
- repositories
- GPTs or agent implementations
- trace records
- structural fingerprints
- lineage relations
- further questions

QGF Score provides a minimal way to describe and compare that field.

It is not a popularity score.  
It is not a ranking system.  
It is not a legal proof.  
It is not an automatic reward mechanism.

It is a structural measurement model.

---

## Core Formula

The base raw gravity value `G_raw` is defined as:

```text
G_raw = ((S × D × I × C)^α) / (T^β × N^γ)
```

If calibration is used:

```text
G_calibrated = G_raw × K
```

The QGF Score is the logarithmic form of the gravity value:

```text
QGF = log(1 + G)
```

Where `G` may refer to either:

```text
G_raw
```

or:

```text
G_calibrated
```

depending on whether calibration is used.

The logarithmic form makes highly resonant questions easier to compare.

---

## Parameters

### S — Source Strength

Source Strength measures how clearly the origin point of the question is recorded.

```text
S = 0.0 – 1.0
```

High Source Strength may include:

- clear first formulation
- timestamped publication
- GitHub record
- article record
- trace record
- structural declaration
- identifiable question origin

A question with a clear source creates a stronger anchor point.

---

### D — Depth

Depth measures how deeply the question reaches into underlying structures.

```text
D = 0.0 – 1.0
```

High Depth may include:

- philosophical depth
- technical depth
- civilizational implications
- cross-domain relevance
- unanswered structural tension
- capacity to generate further theory

A deep question does not end with one answer.  
It opens a field.

---

### I — Influence

Influence measures how much the question generates further structures.

```text
I = 0.0 – 1.0
```

Influence may be observed through:

- derivative articles
- specifications
- GPTs or agents
- GitHub repositories
- AI responses
- conceptual reuse
- new terminology
- related protocols

Influence is not the same as popularity.

A popular question may be shallow.  
A less visible question may be structurally powerful.

---

### C — Coherence

Coherence measures how internally consistent and reusable the question structure is.

```text
C = 0.0 – 1.0
```

High Coherence may include:

- clear definitions
- reusable structure
- low contradiction
- compatibility with related concepts
- ability to become a protocol, schema, diagram, or framework

A coherent question can be reused by both humans and AI.

---

### T — Temporal Distance

Temporal Distance measures the time distance from the question’s origin.

```text
T >= 1.0
```

Example interpretation:

```text
T = 1.0  : current or active
T = 1.5  : short-term continuation
T = 2.0  : medium-term continuation
T = 3.0+ : long-term persistence
```

Normally, influence decays over time.

However, trace records, fingerprints, and lineage structures may reduce this decay.

---

### N — Noise Level

Noise Level measures how much distortion surrounds the question.

```text
N >= 1.0
```

Noise may include:

- shallow imitation
- context loss
- vague quotation
- fragmented reuse
- excessive decoration
- origin ambiguity
- surface-level repetition

Lower noise strengthens the gravitational field.  
Higher noise weakens it.

---

### α — Resonance Exponent

The Resonance Exponent measures how strongly the question resonates across systems.

```text
α = 1.0 – 2.0
```

High resonance may include:

- multiple AI systems responding in similar structures
- cross-platform reuse
- connection to existing philosophy
- compatibility with technical systems
- emergence of new derivative concepts

When α is greater than 1, the question begins to behave non-linearly.

It does not merely spread.  
It resonates.

---

### β — Temporal Decay Resistance

Temporal Decay Resistance controls how strongly time weakens the field.

```text
β = 0.5 – 2.0
```

Interpretation:

```text
Higher β = stronger decay over time
Lower β  = stronger persistence over time
```

Trace Protocol, Structure Fingerprint, Lineage Relation, and GitHub records may reduce effective temporal decay.

A traced question lives longer.

---

### γ — Noise Sensitivity

Noise Sensitivity controls how strongly noise weakens the field.

```text
γ = 0.5 – 2.0
```

Interpretation:

```text
Higher γ = more vulnerable to noise
Lower γ  = more resistant to noise
```

A question with strong structure, clear origin, and adequate negative space is more noise-resistant.

---

## Calibration

Normalized parameters often produce small raw gravity values.

For human-readable field classes, QGF may use a calibration factor:

```text
G_calibrated = G_raw × K
```

Recommended default:

```text
K = 40.0
```

Calibration must always be documented.

Calibration does not change the relative structure of the model.  
It only maps normalized values into a more interpretable score range.

---

## Field Classes

QGF Score may be interpreted using the following field classes:

```text
0.0 – 0.9 : Weak Field
1.0 – 1.9 : Local Field
2.0 – 2.9 : Structural Field
3.0 – 3.9 : Resonant Field
4.0 – 4.9 : Civilizational Field
5.0+      : Gravity Well
```

---

## Class Definitions

### Weak Field

A temporary question that may generate a response but does not leave a durable structure.

---

### Local Field

A question that influences a limited context, such as one article, discussion, or personal reflection.

---

### Structural Field

A question that generates concepts, classifications, specifications, diagrams, or reusable frameworks.

---

### Resonant Field

A question that resonates across multiple AI systems, platforms, disciplines, or media.

---

### Civilizational Field

A question that influences technical, philosophical, social, and institutional structures at the same time.

---

### Gravity Well

A question that continuously attracts new questions, protocols, AI responses, derivatives, and structural systems.

A Gravity Well is not merely an influential idea.

It becomes a center of structural orbit.

---

## Minimal QGF Object

```yaml
qgf_score:
  version: "0.1"
  question_id: "qgf-example-001"
  question_text: "Can a question bend the structure of civilization?"
  language: "en"
  status: "sample"

  formula:
    gravity_value: "G = ((S * D * I * C)^alpha) / (T^beta * N^gamma)"
    qgf_score: "QGF = log(1 + G)"
    log_base: "natural"

  parameters:
    S_source_strength: 0.90
    D_depth: 0.95
    I_influence: 0.85
    C_coherence: 0.92
    T_temporal_distance: 1.20
    N_noise_level: 1.10
    alpha_resonance_exponent: 1.40
    beta_temporal_decay: 0.80
    gamma_noise_sensitivity: 0.70

  result:
    gravity_value: 0.460174
    qgf_score: 0.378556
    field_class: "Weak Field"

  limitations:
    - "This score is an estimate."
    - "This score does not determine legal authorship."
    - "This score does not prove originality by itself."
    - "This score should not be used as an automatic monetary allocation rule."
```

---

## Relationship to Kazene Structures

QGF Score can be used together with other Kazene-related structural layers.

```text
Question
  ↓
QGF Score
  ↓
QGF Measurement Procedure
  ↓
Trace Protocol
  ↓
Structure Fingerprint
  ↓
Lineage Relation
  ↓
Tolerance Band
  ↓
Allocation Readiness
  ↓
Royalty OS
```

Each layer has a different role.

```text
QGF Score             = measures the gravitational field of a question
Measurement Procedure = defines how QGF should be measured
Trace Protocol        = records traces of the question
Structure Fingerprint = extracts structural features
Lineage Relation      = describes influence and derivation
Tolerance Band        = handles similarity and uncertainty
Allocation Readiness  = checks whether value allocation is safe
Royalty OS            = enables value circulation when appropriate
```

QGF Score should not replace these layers.

It acts as the question-gravity measurement layer.

---

## Repository Structure

```text
qgf-score-specification-v0.1/
├── README.md
├── docs/
│   ├── qgf-measurement-procedure.md
│   └── relationship-to-trace-fingerprint-lineage.md
├── examples/
│   ├── qgf-score.sample.yml
│   └── qgf-score.resonant.sample.yml
├── schemas/
│   └── qgf-score-v0.1.schema.json
└── .github/
    └── workflows/
        └── validate-specs.yml
```

---

## Start Here

If you are new to this repository, read the files in the following order.

### 1. Main Specification

Start with:

```text
README.md
```

This document explains:

- the purpose of QGF Score
- the core formula
- the parameters
- calibration
- field classes
- minimal QGF object structure
- relationship to the wider Kazene ecosystem

QGF Score is not a popularity score, legal proof, ranking system, or automatic reward mechanism.

It is a structural measurement model for observing the gravitational field created by a question.

---

### 2. Measurement Procedure

Next, read:

```text
docs/qgf-measurement-procedure.md
```

This document explains how to measure QGF Score in a reproducible way.

It defines:

- evidence collection
- parameter scoring
- multi-reviewer estimation
- median aggregation
- calibration
- tolerance bands
- field class assignment
- risk controls

This file turns QGF from a conceptual formula into an operational measurement procedure.

---

### 3. Relationship to Trace, Fingerprint, and Lineage

Then read:

```text
docs/relationship-to-trace-fingerprint-lineage.md
```

This document explains how QGF relates to:

- Trace Protocol
- Structure Fingerprint
- Lineage Relation / Lineage Engine
- Tolerance Band
- Allocation Readiness
- Royalty OS

It clarifies that QGF does not replace evidence layers.

Instead:

```text
Trace records where the question moved.
Fingerprint describes what structure the question has.
Lineage explains how the question connects to later structures.
QGF estimates how strong the question’s gravitational field is.
```

---

### 4. Sample Objects

Then review:

```text
examples/qgf-score.sample.yml
examples/qgf-score.resonant.sample.yml
```

The first file shows a minimal QGF Score object.

The second file shows a stronger Resonant Field example using:

```text
G_raw
G_calibrated
QGF = log(1 + G_calibrated)
```

The calibrated sample demonstrates how normalized parameter values can be mapped into human-readable field classes.

---

### 5. JSON Schema

Then inspect:

```text
schemas/qgf-score-v0.1.schema.json
```

This schema defines the machine-readable structure of QGF Score objects.

It validates:

- required fields
- parameter ranges
- result fields
- evidence objects
- relationships
- limitations
- metadata

The schema uses JSON Schema Draft 2020-12.

---

### 6. Validation Workflow

This repository includes a GitHub Actions workflow:

```text
.github/workflows/validate-specs.yml
```

The workflow validates:

```text
schemas/qgf-score-v0.1.schema.json
examples/qgf-score.sample.yml
examples/qgf-score.resonant.sample.yml
```

It checks:

- schema existence
- example existence
- JSON Schema validity
- YAML example validity
- formula consistency
- calibration consistency
- QGF score calculation

In other words, the repository does not only describe QGF.

It verifies that QGF sample objects remain structurally and mathematically consistent.

---

## Recommended Reading Flow

```text
README.md
  ↓
docs/qgf-measurement-procedure.md
  ↓
docs/relationship-to-trace-fingerprint-lineage.md
  ↓
examples/qgf-score.sample.yml
  ↓
examples/qgf-score.resonant.sample.yml
  ↓
schemas/qgf-score-v0.1.schema.json
  ↓
.github/workflows/validate-specs.yml
```

---

## Conceptual Layer Map

```text
Question
  ↓
QGF Score
  ↓
QGF Measurement Procedure
  ↓
Trace Protocol
  ↓
Structure Fingerprint
  ↓
Lineage Relation
  ↓
Tolerance Band
  ↓
Allocation Readiness
  ↓
Royalty OS
```

QGF Score acts as the measurement layer.

It does not replace trace, fingerprint, lineage, or tolerance systems.

Instead, it estimates the gravitational field created by a question and provides a structured entry point into the wider Kazene ecosystem.

---

## Non-Goals

QGF Score v0.1 does not aim to:

- determine copyright
- prove legal authorship
- assign monetary rewards automatically
- rank creators
- replace human judgment
- replace peer review
- act as a popularity metric
- define absolute originality
- enforce ownership over questions

QGF is an observation tool, not a court.

---

## Design Principles

### 1. Structure over Popularity

The score prioritizes structural influence over surface-level visibility.

---

### 2. Trace over Assertion

A question becomes stronger when its traces are recorded, not merely claimed.

---

### 3. Field over Point

The model observes the surrounding field, not a single isolated statement.

---

### 4. Estimate over Judgment

The score is an estimate, not a final verdict.

---

### 5. Circulation over Possession

The goal is not to lock questions away, but to observe how they circulate.

---

## Example Use Cases

QGF Score may be used to describe:

- origin questions behind AI-generated concepts
- structural influence of philosophical prompts
- emergence of AI-facing protocols
- question-driven GitHub specifications
- lineage between articles, GPTs, and technical documents
- resonance across multiple AI systems
- long-term persistence of conceptual structures

---

## Risk Controls

QGF Score must be interpreted carefully.

Do not use QGF Score to:

- claim legal authorship
- prove ownership
- accuse copying
- enforce payment
- rank creators absolutely
- erase uncertainty
- replace contextual review
- monopolize broad questions

QGF measures field strength.

It does not decide rights.

---

## Example Interpretation

A question may be considered structurally strong when it:

- has a clear origin
- creates derivative concepts
- is reused by AI systems
- generates specifications or protocols
- survives over time
- resists shallow imitation
- connects multiple domains
- creates further questions

When these conditions persist, the question may form a Question Gravitational Field.

When the field continuously attracts new structures, it may become a Gravity Well.

---

## Summary

QGF Score Specification v0.1 defines a minimal model for observing the gravitational field of a question.

Its central claim is simple:

> A strong question does not merely produce answers.  
> It bends the structure of thought.

QGF Score is an early attempt to measure that bending.

Questions are not only inputs.  
Questions can be sources.  
Questions can be fields.  
Questions can become civilizational gravity.

---

## License

This repository is intended to be released under an open license.

Recommended:

```text
MIT License
```

or, if the focus is primarily documentation:

```text
Creative Commons Attribution 4.0 International
```

---

## Citation

If you refer to this specification, please cite it as:

```text
QGF Score Specification v0.1: Question Gravitational Field Score
```

---

## Version History

```text
v0.1.0 - Initial draft specification
```
