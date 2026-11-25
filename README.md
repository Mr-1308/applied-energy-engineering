# Applied Mathematics for Renewable Energy Engineering

An independent self-study project connecting university-level mathematics to photovoltaic systems, battery energy storage and electrical power engineering.

**Objective:** Prepare for DTU Mathematics 1a (01003) while developing reproducible engineering models and documenting the learning process. This is not an official DTU programme, qualification or affiliation.

## Study framework

- [Curriculum and applied cases](CURRICULUM.md)
- [Learning progress](PROGRESS.md)
- [Teaching and assessment protocol](TEACHING_PROTOCOL.md)
- [References](REFERENCES.md)
- [PyPSA power-system modelling and optimisation track](PYPSA_TRACK.md)
- [Module 00 — mathematical foundations](00-mathematical-foundations/README.md)

## Method

1. Study theory and definitions from the source.
2. Solve mathematical exercises manually and justify each step.
3. Apply the concepts to an original PV, BESS or electrical engineering problem.
4. Implement and verify the solution using Python (SymPy, NumPy, SciPy, pvlib, PyPSA or Linopy as appropriate).
5. Record assumptions, units, results, limitations and corrections.
6. Complete independent exam-style practice before marking a topic mastered.

The suggested cadence is 5–6 hours per week, adjusted after the initial diagnostic. Mathematical exam preparation remains distinct from engineering applications.

## Hybrid-first engineering approach

Reflecting the learner's utility-scale development experience, treat PV+BESS co-design as the default applied case whenever technically relevant. Retain PV-only baselines and test whether storage is technically and economically justified, rather than assuming every PV project requires it. Study battery power and energy sizing, duration, usable capacity, efficiency, degradation, dispatch, model calibration and validation together with PV design and shared grid constraints.

## Development environment

JupyterLab is the primary local learning environment. PVlib produces PV generation time series; PyPSA and Linopy model energy-system operation and optimisation. Record package and solver versions for reproducibility.

## Reproducibility and integrity

Use public or synthetic inputs only. Do not publish employer data, internal project drawings, proprietary calculations, restricted course material or copied textbook solutions. Link to original learning resources rather than redistributing them. AI-assisted explanations and code are reviewed by the learner; progress reflects demonstrated understanding, not generated content.

## Status

Project initiated 25 November 2026. Diagnostic assessment and environment setup pending.
