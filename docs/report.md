# Homework 7 Report — Studying the Geometry of a Toy Model

## Status

This report is currently in progress.

This repository was created as the initial public submission for Homework 7 of the course **Selected Research Topics in AI**.

The full report will be expanded with implementation details, experiments, plots, and conclusions.

---

## Problem statement

This homework studies how changes in the properties of a **Toy Model of superposition** affect:

- the geometry of learned feature embeddings,
- the geometry of hidden states,
- the training behavior and reconstruction quality of **Sparse Autoencoders (SAEs)**,
- the ability of SAEs to recover the original structure of the toy model.

---

## Planned report structure

### 1. Setup

- definition of the toy model,
- feature activation frequencies,
- hidden-state generation process,
- autoencoder training procedure,
- SAE architecture and objective,
- evaluation metrics.

### 2. Part 1 — Geometry and structure

Goal:
analyze how changes in model parameters affect the structure and geometry of feature embeddings and hidden states.

Planned factors:
- frequency distribution parameters,
- vocabulary size,
- hidden dimension,
- training duration,
- other controlled parameters if needed.

### 3. Part 2 — SAE quality

Goal:
study which properties of the toy model and training setup influence SAE quality.

Planned metrics:
- explained variance,
- reconstruction quality,
- additional geometric diagnostics if useful.

### 4. Part 3 — Recovery of true features

Goal:
study how well SAE recovers the original feature frequencies and embeddings.

Planned analysis:
- effect of sparsity-related hyperparameters,
- comparison across different superposition regimes,
- sensitivity to toy-model parameters.

### 5. Optional Part 4 — Open-ended experiments

Potential direction:
test additional hypotheses that emerge during the work.

### 6. Conclusions

The final version of the report will summarize:
- what worked,
- what did not work,
- what was learned from the experiments,
- what future directions seem promising.

---

## Immediate next steps

- implement a minimal toy model,
- implement SAE training,
- run first smoke experiments,
- produce the first diagnostic plots,
- expand this report with real results.
