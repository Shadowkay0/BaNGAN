# BaNGAN - BN → Rule‑Penalised CTGAN


This repository scaffolds the experiments of a **two‑phase hybrid model**:
1) **Bayesian Network (BN) imputation** on incomplete clinical tables, and
2) **Rule‑penalised CTGAN** training for transparent synthetic data generation.

It includes:
- A BN imputer (structure learning + per‑row conditional sampling) that outputs **M completed tables**,
- A PyTorch **WGAN‑GP** trainer with **differentiable clinical rule penalties**,
- A simple **tabular transformer** for mixed continuous/categorical data,
- Evaluation scripts (fidelity, utility, and rule‑adherence).
