# Forecasting-Euclid

[![arXiv](https://img.shields.io/badge/arXiv-2510.09153-b31b1b.svg)](https://arxiv.org/abs/2510.09153)

This repository contains all **scripts** and **Jupyter notebooks** used to forecast **Euclid’s scientific performance** by the end of its mission operations (Data Release 3).  It accompanies the paper [*Euclid preparation. Cosmology Likelihood for Observables in Euclid (CLOE). III. Inference and Forecasts*](https://arxiv.org/abs/2510.09153).

---

## 🛰️ Overview

The scripts and notebooks in this repository are part of the **Euclid CLOE (Cosmology Likelihood for Observables in Euclid)** framework, developed to assess the mission’s final cosmological constraining power.  

They include tools for:
- Performing likelihood-based forecasts for Euclid DR3 using `nautilus` and `CLOE` v2.0.2.  
- Exploring cosmological model inference under the Euclid survey specifications.

---

## 📁 Contents

| Folder / File | Description |
|----------------|-------------|
| `notebooks/`   | Jupyter notebooks illustrating the analyses of the posterior samples. |
| `scripts/`     | Python scripts to run CLOE with Cobaya and Nautilus sampler. |

---

## ⚙️ Requirements

All scripts use standard scientific Python libraries: numpy, scipy, matplotlib, scikit-learn, seaborn, jupyter

## 📖 Reference
If you use this repository, please cite:

```
@article{CanasHerrera2025,
  author       = {C{\~a}nas‐Herrera, Guadalupe and the Euclid Collaboration},
  title        = {Euclid preparation. Cosmology Likelihood for Observables in Euclid (CLOE). 3. Inference and Forecasts},
  journal      = {arXiv preprint arXiv:2510.09153},
  year         = {2025},
  note         = {Submitted 10 Oct 2025},
  doi          = {10.48550/arXiv.2510.09153},
  eprint       = {2510.09153},
  archivePrefix= {arXiv},
  primaryClass = {astro-ph.CO}
}
```

