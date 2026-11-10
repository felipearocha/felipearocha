<!-- =========================================================
Felipe Rocha — Profile README (landing page)
Audience: technical peers · engineering-first · standards-traceable
========================================================== -->

<h1 align="center">Felipe Rocha</h1>

<p align="center">
  <strong>Asset Integrity Engineer</strong> — physics-first, standards-traceable simulators
</p>

<p align="center">
  <em>Open-source integrity simulators with governing equations documented in code,<br/>
  hand-calc benchmarks, stated limitations, and DOI-archived releases.</em>
</p>

<!-- Metrics band (every number is verifiable) -->
<p align="center">
  <img src="https://img.shields.io/badge/packages-10-1f6feb?style=for-the-badge&labelColor=0d1117" alt="10 open-source packages">
  <img src="https://img.shields.io/badge/tests-1%2C400%2B-238636?style=for-the-badge&labelColor=0d1117" alt="1,400+ tests">
  <img src="https://img.shields.io/badge/codes%20%26%20standards-15%2B-8250df?style=for-the-badge&labelColor=0d1117" alt="15+ codes and standards">
  <img src="https://img.shields.io/badge/Zenodo%20DOIs-8-1682D4?style=for-the-badge&labelColor=0d1117" alt="8 Zenodo DOIs">
</p>

<!-- Calls to action -->
<p align="center">
  <a href="https://github.com/felipearocha?tab=repositories"><img src="https://img.shields.io/badge/Browse_the_Series-1f6feb?style=for-the-badge&logo=github&logoColor=white" alt="Browse the Series"></a>
  <a href="https://github.com/felipearocha/integrity-code-series-dashboard"><img src="https://img.shields.io/badge/Live_Dashboard-238636?style=for-the-badge&logo=githubactions&logoColor=white" alt="Live Dashboard"></a>
  <a href="https://zenodo.org/search?q=%22Felipe%20Rocha%22"><img src="https://img.shields.io/badge/Zenodo-1682D4?style=for-the-badge&logo=zenodo&logoColor=white" alt="Zenodo"></a>
  <a href="https://www.linkedin.com/in/felipe-rocha-7a944b133/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:feliper@infinitygrowth.ca"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## Engineering Profile

I design and implement decision-support systems for asset-integrity and risk-based-inspection (RBI) programs — at the boundary of **engineering judgment, structured data systems, and physics-constrained machine learning**.

The objective is not algorithmic novelty. It is **defensible operational decisions**: explicit assumptions, transparent transformation logic, inspectable data lineage, bounded model behavior, and visible failure modes.

---

## Expertise

Core domains, and the methods & standards that sit under each.

| Domain | Methods &amp; Standards |
|---|---|
| **Asset Integrity &amp; RBI** | API 510 / 570 / 653 · API 571 (damage mechanisms) · API 580 / 581 (RBI) · API 579-1 / ASME FFS-1 · API RP 970 (CCDs) |
| **Corrosion &amp; Electrochemistry** | CO₂ corrosion (NORSOK M-506) · galvanic (Butler–Volmer / Laplace) · CUI · NNpH-SCC (Chen–Sutherby–Xing) · erosion-corrosion (DNV-RP-O501 / ASTM G119) · H₂ service (B31.12) |
| **Physics-Informed ML (PIML)** | PINN surrogates · soft-penalty physics constraints · gradient-boosted surrogates · Monte-Carlo uncertainty quantification |
| **Data Architecture &amp; Secure Automation** | ingestion-time validation · deterministic transforms · SHA-256 audit chains · CI/CD · reproducibility harnesses |

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

---

## The Integrity Code Series

Self-contained, physics-first integrity simulators. Each one documents its governing equations, flags its assumptions and states its limitations. The simulators ship a `run_all.py` that reproduces their figures, and most add hand-calc benchmarks and a Monte-Carlo or sensitivity layer over the deterministic core.

> **Live status:** [integrity-code-series-dashboard](https://github.com/felipearocha/integrity-code-series-dashboard) — CI, releases and last-push, auto-refreshed monthly.

### Featured results

<table>
  <tr>
    <td width="50%" align="center"><a href="https://github.com/felipearocha/integrity-code-series-week11-erosion-corrosion-multiphase"><img src="https://raw.githubusercontent.com/felipearocha/integrity-code-series-week11-erosion-corrosion-multiphase/main/assets/hero_erosion_corrosion_week11.png" alt="Week 11 · wall-loss field on a multiphase elbow" width="100%"></a><br><sub>Week 11 · wall-loss field on a multiphase elbow</sub></td>
    <td width="50%" align="center"><a href="https://github.com/felipearocha/integrity-code-series-week7-h2-lferw"><img src="https://raw.githubusercontent.com/felipearocha/integrity-code-series-week7-h2-lferw/main/assets/hero_h2_crack.png" alt="Week 7 · hydrogen field and crack growth at an ERW seam" width="100%"></a><br><sub>Week 7 · hydrogen field and crack growth at an ERW seam</sub></td>
  </tr>
  <tr>
    <td width="50%" align="center"><a href="https://github.com/felipearocha/integrity-code-series-week6-smartphone-galvanic"><img src="https://raw.githubusercontent.com/felipearocha/integrity-code-series-week6-smartphone-galvanic/main/assets/hero_potential_current.png" alt="Week 6 · potential and current density in a USB-C port" width="100%"></a><br><sub>Week 6 · potential and current density in a USB-C port</sub></td>
    <td width="50%" align="center"><a href="https://github.com/felipearocha/Vibration-Accelerated-Corrosion-Coupled-Mechano-Electrochemical-Simulation"><img src="https://raw.githubusercontent.com/felipearocha/Vibration-Accelerated-Corrosion-Coupled-Mechano-Electrochemical-Simulation/main/assets/hero_3d_cr_surface.png" alt="Vibration · corrosion-rate surface at a pipe support" width="100%"></a><br><sub>Vibration · corrosion-rate surface at a pipe support</sub></td>
  </tr>
</table>

### All packages

| # | Repository | Domain | Tests | Key standards / methods | DOI |
|---|---|---|:---:|---|---|
| **11** ⭐ | [erosion-corrosion-multiphase](https://github.com/felipearocha/integrity-code-series-week11-erosion-corrosion-multiphase) | Coupled erosion-corrosion at a multiphase elbow | **471** | NORSOK M-506 · DNV-RP-O501 · ASTM G119 · API 571 / 579 | <a href="https://doi.org/10.5281/zenodo.21114866"><img src="https://img.shields.io/badge/DOI-zenodo.21114866-1682D4" alt="DOI 10.5281/zenodo.21114866"></a> |
| 10 | [nnph-scc](https://github.com/felipearocha/integrity-code-series-week10-nnph-scc) | Near-neutral-pH stress-corrosion cracking | 221 | Chen–Sutherby–Xing · BS 7910 · API 579 · Bayesian inspection planning | <a href="https://doi.org/10.5281/zenodo.20172241"><img src="https://img.shields.io/badge/DOI-zenodo.20172241-1682D4" alt="DOI 10.5281/zenodo.20172241"></a> |
| 9 | [cui](https://github.com/felipearocha/integrity-code-series-week9-cui) | Corrosion under insulation (thermo-hygro-electrochemical) | 156 | 2 PDEs + Butler–Volmer · Strang splitting · DFOS inverse | <a href="https://doi.org/10.5281/zenodo.20172508"><img src="https://img.shields.io/badge/DOI-zenodo.20172508-1682D4" alt="DOI 10.5281/zenodo.20172508"></a> |
| 8 | [creep-fatigue-heater](https://github.com/felipearocha/integrity-code-series-week8-creep-fatigue-heater) | Creep-fatigue in fired-heater tubes (9Cr-1Mo) | 333 | ASME III-5 · Norton/Omega · Coffin–Manson | <a href="https://doi.org/10.5281/zenodo.20172467"><img src="https://img.shields.io/badge/DOI-zenodo.20172467-1682D4" alt="DOI 10.5281/zenodo.20172467"></a> |
| 7 | [h2-lferw](https://github.com/felipearocha/integrity-code-series-week7-h2-lferw) | Hydrogen conversion of vintage LF-ERW pipe | 192 | H diffusion · HA-FCG · B31.12-form MAOP | <a href="https://doi.org/10.5281/zenodo.20172481"><img src="https://img.shields.io/badge/DOI-zenodo.20172481-1682D4" alt="DOI 10.5281/zenodo.20172481"></a> |
| 6 | [smartphone-galvanic](https://github.com/felipearocha/integrity-code-series-week6-smartphone-galvanic) | Galvanic corrosion in a thin electrolyte film | 44 | Laplace 2D · Butler–Volmer · oxide growth | <a href="https://doi.org/10.5281/zenodo.20172479"><img src="https://img.shields.io/badge/DOI-zenodo.20172479-1682D4" alt="DOI 10.5281/zenodo.20172479"></a> |
| 3 | [f1-lap-simulation](https://github.com/felipearocha/integrity-code-series-week3-f1-lap-simulation) | F1 lap dynamics (six-state model) | 14 | arc-length ODE integration · thermal grip window | — |
| ◆ | [synthetic-integrity-digital-twin-**piml**](https://github.com/felipearocha/synthetic-integrity-digital-twin-piml) | Physics-informed NN surrogate for an integrity digital twin | 5 | PINN-style demo · Paris-type rollout · soft-penalty constraints | <a href="https://doi.org/10.5281/zenodo.20172483"><img src="https://img.shields.io/badge/DOI-zenodo.20172483-1682D4" alt="DOI 10.5281/zenodo.20172483"></a> |
| ◆ | [vibration-accelerated-corrosion](https://github.com/felipearocha/Vibration-Accelerated-Corrosion-Coupled-Mechano-Electrochemical-Simulation) | Vibration-accelerated corrosion at pipe supports | 31 | SDOF · stress-modified Butler–Volmer · Archard | <a href="https://doi.org/10.5281/zenodo.20172485"><img src="https://img.shields.io/badge/DOI-zenodo.20172485-1682D4" alt="DOI 10.5281/zenodo.20172485"></a> |
| ◆ | [integrity-data-foundation](https://github.com/felipearocha/integrity-data-foundation) | Engineering-first data validation baseline for RBI | 7 | rule-based validation · deterministic transforms | — |

<sub>⭐ flagship · ◆ companion package · test counts are from each repo's own suite.</sub>

---

## Method &amp; Rigor

```mermaid
flowchart LR
    A[Physical Reality] --> B[Structured Engineering Data]
    B --> C[Explicit Domain Logic]
    C --> D[Physics / Risk Framing]
    D --> E[Validation Harness]
    E --> F[Operational Decision Support]
```

The series works to one standard of evidence:

- **Traceable constants** — constants cite a source or carry an `[ASSUMED]` flag, with a confidence tier (**T1** standard/paper · **T2** derived · **T3** practitioner). Modelling assumptions are called out, never dressed as standards.
- **Analytical checks** — hand-calc benchmarks wherever a closed form exists.
- **Uncertainty, not point estimates** — Monte-Carlo or sensitivity layers around the deterministic cores.
- **Reproducibility** — `run_all.py` regenerates the figures; releases are archived to Zenodo with permanent DOIs.

> *If an assumption is not written, it fails silently.*
> *If data lineage is not explicit, the decision is not defensible.*
> *If a model cannot state its boundary conditions, it is not operational.*

---

## Cite &amp; Reproduce

Eight packages are archived on [Zenodo](https://zenodo.org/search?q=%22Felipe%20Rocha%22) with a **concept DOI** (always resolves to the latest version) and a machine-readable `CITATION.cff` that drives GitHub's *"Cite this repository"* widget.

```bibtex
@software{rocha_integrity_code_series,
  author    = {Rocha, Felipe},
  title     = {Integrity Code Series — physics-first integrity simulators},
  year      = {2026},
  publisher = {Zenodo},
  url       = {https://github.com/felipearocha},
  note      = {Concept DOIs resolve to the latest archived release of each package.}
}
```

To reproduce a simulator: `pip install -r requirements.txt && python run_all.py`.

---

## Contact

Open to technical discussion on **asset-integrity digitalization, RBI architecture, physics-informed modeling, and engineering-grade automation**.

- ✉️ feliper@infinitygrowth.ca · felipe@olivainternationaltech.com
- 🔗 [linkedin.com/in/felipe-rocha-7a944b133](https://www.linkedin.com/in/felipe-rocha-7a944b133/)
