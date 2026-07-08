# Electrochemical Degradation Generation and Classification of NCM Cathode Materials Using Conditional Generative AI

> **⚠️ Repository Status:** Under Development (Code Not Yet Released)

This repository contains the implementation of a deep learning framework for generating and classifying degradation morphologies of lithium-ion battery cathode materials from scanning electron microscopy (SEM) images.

The project is currently under active development as part of the future work of my Ph.D. dissertation. The codebase is being refined before its public release.

---

## Overview

Understanding degradation mechanisms in lithium-ion battery cathodes typically requires extensive electrochemical cycling followed by destructive post-mortem characterization. This work explores whether degradation morphology can instead be predicted directly from pristine SEM images using generative artificial intelligence.

The proposed framework employs an **Auxiliary Classifier Generative Adversarial Network (AC-GAN)** to generate realistic degradation morphologies for three NCM cathode compositions:

- NCM333
- NCM622
- NCM811

Unlike conventional CNN classifiers that only recognize degradation states, this framework generates plausible degraded SEM morphologies while preserving composition-specific characteristics.

---

## Objectives

- Generate realistic degraded SEM images from composition-conditioned inputs.
- Classify generated degradation images with high semantic consistency.
- Preserve structural and textural characteristics of real degradation morphologies.
- Provide an AI-assisted pre-screening tool for battery degradation analysis.

---

## Methodology

The framework consists of:

- Modified AC-GAN architecture
- Conditional image generation
- Auxiliary degradation classification
- Composite model selection strategy
- Multi-metric image evaluation

Evaluation metrics include:

- Fréchet Inception Distance (FID)
- Deep Image Structure and Texture Similarity (DISTS)
- Auxiliary classification accuracy

---

## Results

The best-performing model achieved:

| Metric | Performance |
|---------|-------------|
| Auxiliary classification accuracy | **99.28%** |
| Real SEM classification accuracy | **87.50%** |
| Image similarity evaluation | Strong preservation of structural and textural morphology (DISTS) |

The generated degradation images successfully preserved key microstructural features while maintaining high semantic consistency across different NCM compositions.

---

## Future Work

The repository will be released after completing the ongoing research, including:

- Improved AC-GAN architecture
- Enhanced model-selection strategy
- Better balance between image realism and semantic consistency
- Improved paired morphology fidelity
- Evaluation on out-of-distribution SEM images (e.g., additive-containing NCM materials)
- Additional experimental validation

---

## Repository Status

This repository is currently **private** while the research is being completed and prepared for publication.

The code will be released after:

- Completion of the planned future work
- Final manuscript preparation
- Code cleaning and documentation
- Reproducibility verification

---

## Citation

If you find this work useful, please cite the corresponding publication once it becomes available.

---
