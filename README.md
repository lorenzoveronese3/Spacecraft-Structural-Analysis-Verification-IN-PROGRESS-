# Spacecraft Structural Analysis & Verification on Vega-C (MSC Nastran/Femap)

> **Status: in progress.** This is an ongoing course project. The models, scripts and report will be published here after the course assessment.

Team project for the *Analysis and Testing of Space Structures* course, MSc in Space Engineering, Politecnico di Milano, A.Y. 2026/27.

## Goal

Design and verify a basic spacecraft structure for launch on **Vega-C**:

- derive the mechanical requirements from the launcher user's manual;
- show compliance with each requirement through finite element analysis (MSC Nastran, with Femap for pre- and post-processing) and analytical checks.

## Workflow and status

| Step | Analysis | Status |
|---|---|---|
| FE models | Equivalent-shell models of the launcher and of a 1500 kg spacecraft: geometry, mesh quality, materials, lumped masses, fairing usable volume | ✅ Done |
| Model tuning | Launcher tuned to its reference free-free frequencies; spacecraft checked against the minimum fundamental frequencies in hard-mounted condition (SOL 103) | ✅ Done |
| Quasi-static loads | 1 g unit load cases (SOL 101), interface line loads over the quasi-static flight envelope, symmetric and asymmetric configurations, clamp-band tension | ✅ Done |
| Dynamic coupling | Launcher–spacecraft coupling assessed with a 3-DOF frequency-response model in MATLAB | ✅ Done |
| Thermoelastic | Thermal load case on the spacecraft (SOL 101) and relative rotations between instruments | 🔄 In progress |
| Sine and acoustic | Sine vibration and acoustic response predictions | ⏳ Planned |
| Buckling | Buckling assessment of the spacecraft structure | ⏳ Planned |

## Tools

MSC Nastran (SOL 101, SOL 103), Femap, MATLAB, Excel

## Team

Marco Bosoni, Gioele Costantino Bordogna, Samuele Cerquaglia, Lorenzo Veronese, Francesco Berardinelli
