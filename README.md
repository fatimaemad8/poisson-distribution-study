# The Poisson Distribution: A Comprehensive Examination

A research study of the Poisson distribution from theoretical and computational perspectives: complete proofs, numerical validation, and five Poisson-regression applications on synthetic data.

**Author:** Fatima Emad · **Date:** July 16, 2025

**Read the paper:** [The Poisson Distribution: A Comprehensive Examination](paper/The_Poisson_Distribution.pdf)

## Contents
- `paper/` – the full paper and a standalone proofs document (PDF)
- `notebooks/` – Jupyter notebook that reproduces every figure

## What is inside
- Derivations: PMF (binomial limit), CDF, MGF, mean, variance, mode
- Reliability and hazard functions (waiting-time and discrete-count settings)
- Binomial, exponential and normal relationships
- Applications: call volume, breach detection, traffic flow,
  disease surveillance (overdispersion), clickstream analysis

## Run it
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Poisson_Distribution_Companion.ipynb
```

Run the notebook from top to bottom; a single seeded generator makes the
results reproducible.

## Notes
All datasets are synthetic, generated from known parameters, so the project
validates methods rather than making claims about real systems.

## License
MIT © 2025 Fatima Emad
