# AAAI 2025 Submission: Bias Mitigation in LLMs

This codebase supports our AAAI 2025 submission on mitigating intrinsic and extrinsic bias in large language models (LLMs). It includes scripts for data preparation, bias unlearning, and downstream fairness evaluation.

##  Folder Overview

- `DataPrep/`: Jupyter notebooks for preparing datasets (ACS, Adult, German Credit) and generating counterfactual examples using CDA.
- `IntrinsicBias/`: Code for intrinsic bias mitigation via unlearning (gradient ascent/descent and KL).
- `ExtrinsicBias/`: Code for downstream task evaluation with frozen embeddings and LoRA fine-tuning.

##  Environment Setup (using `uv`)

### Install dependencies using:

```bash
uv pip install -r pyproject.toml
```

### To reproduce the full environment:
```bash
uv venv
uv pip install -r pyproject.toml
uv pip sync
```
