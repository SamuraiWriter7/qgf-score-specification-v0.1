# Changelog

All notable changes to this project will be documented in this file.

This project follows a simple versioned specification history.

---

## [Unreleased]

### Planned

- Add QGF Map concept document.
- Add Gravity Well theory document.
- Add integration examples with Trace Protocol, Structure Fingerprint, and Lineage Relation.
- Add additional validation test vectors.
- Add diagrams for the QGF measurement layer.

---

## [0.1.0] - 2026-05-17

### Added

- Initial `README.md` for QGF Score Specification v0.1.
- Core QGF formula:

```text
G_raw = ((S × D × I × C)^α) / (T^β × N^γ)
QGF = log(1 + G)
Parameter definitions:
S_source_strength
D_depth
I_influence
C_coherence
T_temporal_distance
N_noise_level
alpha_resonance_exponent
beta_temporal_decay
gamma_noise_sensitivity
Calibration model using:
G_calibrated = G_raw × K
Field class definitions:
Weak Field
Local Field
Structural Field
Resonant Field
Civilizational Field
Gravity Well
examples/qgf-score.sample.yml
Minimal QGF Score sample object.
examples/qgf-score.resonant.sample.yml
Resonant Field sample using raw gravity, calibrated gravity, and QGF score.
schemas/qgf-score-v0.1.schema.json
JSON Schema Draft 2020-12 definition for QGF Score objects.
.github/workflows/validate-specs.yml
GitHub Actions workflow for validating:
schema existence
example existence
JSON Schema validity
YAML example validity
formula consistency
calibration consistency
QGF score calculation
docs/qgf-measurement-procedure.md
Standard procedure for measuring QGF Score.
Includes evidence collection, parameter scoring, median aggregation, calibration, tolerance bands, and risk controls.
docs/relationship-to-trace-fingerprint-lineage.md
Relationship document explaining how QGF connects to:
Trace Protocol
Structure Fingerprint
Lineage Relation
Tolerance Band
Allocation Readiness
Royalty OS
LICENSE
MIT License.
CITATION.cff
Citation metadata for GitHub and academic/reference use.
Notes

QGF Score v0.1 is a structural observation and measurement layer.

It does not determine:

legal authorship
copyright ownership
originality by itself
monetary entitlement
automatic reward allocation
creator ranking

QGF measures the gravitational field created by a question.

It is not a court, throne, or ownership claim.
