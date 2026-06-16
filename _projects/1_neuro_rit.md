---
layout: page
title: Neuro-RIT
description: Neuron-guided instruction tuning for robust retrieval-augmented language models
img:
importance: 1
category: research
related_publications: true
---

**Role:** First author — ARK Lab (Prof. Seo Yeon Park)
**Status:** arXiv:2604.02194
**Stack:** PyTorch · Hugging Face

## Overview

Retrieval-augmented generation (RAG) adds external knowledge to language models, but the
retrieved context is often noisy and degrades answer quality. **Neuro-RIT** tackles this by
analyzing, at the neuron level, how the model actually uses that context.

## Key Contributions

- **Neuron-level functional decomposition** — identifies *context-specific* and *shared*
  neuron groups inside the model, separating where retrieved context is processed from where
  the model's parametric knowledge lives.
- **Role-specific summary-based denoising** — uses the decomposition to suppress the
  influence of noisy retrieved context.
- **Layer-aware selective adaptation** — tunes only the layers that matter for robustness,
  improving stability while reducing interference.
