# PyPSA — Power-system modelling and optimisation

Status: planned, not assessed. This is an applied extension to the independent DTU Mathematics 1a preparation, not an official DTU assignment. Follow [TEACHING_PROTOCOL.md](TEACHING_PROTOCOL.md) for every case; learner implements, submits, receives review, revises and validates before publication.

## Learning progression

| Stage | Mathematical prerequisite | Applied case | Evidence |
|---|---|---|---|
| P01 | Units, functions and linear equations | Single bus, generator and load; hourly energy balance | Manual balance and Jupyter model |
| P02 | Linear inequalities and vectors | PVlib AC generation profile as PyPSA availability | Aligned timestamps, MW/MWh, curtailment and balance checks |
| P03 | Algebra and time-indexed energy balances | Battery state of charge with efficiency and power/energy limits | Manual short-horizon calculation and validation |
| P04 | Linear objective functions and constraints | Economic dispatch with hourly synthetic electricity prices | Explain objective, constraints, solver status and revenues |
| P05 | Matrices and Kirchhoff laws | Two-bus network, line limits and linearised power flow | Hand-calculated flow benchmark |
| P06 | Linear optimisation and sensitivity | PV+BESS plant under a shared 15 MW active-power export constraint | 2 h versus 4 h storage, curtailment, dispatch and net revenue |
| P07 | Optimisation, costs and uncertainty | Capacity expansion and scenario comparison | Cost assumptions, sensitivities and reproducible results |

Linear programming, energy economics and power-flow modelling are supplemental subjects beyond the core Mathematics 1a curriculum. Start with small synthetic systems before using annual profiles.

## Capstone: synthetic PV+BESS plant

Compare a 15 MW active-power export limit with PV-only and PV+BESS cases. Generate PV AC availability with pvlib; document weather source, system assumptions, conversion and loss boundaries. Use PyPSA for hourly dispatch, storage efficiency, energy capacity, charging limits and shared export constraints. Define import permissions and costs explicitly, avoid double-counting inverter losses, distinguish MW from MWh, and specify initial and terminal state of charge. Compare 2-hour and 4-hour storage at equal battery power, then optionally optimise capacity. Verify energy balance, export and SOC limits, curtailment, solver termination and net revenues (with explicit tariff/price assumptions). Perfect-foresight results are a benchmark, not a guaranteed achievable outcome. This simplified model does not establish AC apparent-power limits, reactive-power compliance, protection settings or grid-code compliance.

## Local environment

Use the existing energy-engineering environment with JupyterLab. Install PyPSA, Linopy and HiGHS; verify the active kernel, imported versions and solver availability. Record tested versions per notebook. See https://docs.pypsa.org/stable/ and https://docs.pypsa.org/latest/home/installation/.

No code solutions are provided in advance. Each future case will include learner-editable notebook cells and manual derivations, with validation and instructor-style comments following submission.
