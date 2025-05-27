# Periodic Table of Human Phenotypes (ALMS Framework)

This repository presents the concept, structure, and ethical guidelines for the **Algorithm for Locating Maximally Similar Faces (ALMS)** and the proposed **Periodic Table of Human Phenotypes** — a data-driven framework for classifying human morphological diversity based on facial topology.

---

## 🧠 Core Idea
We propose a reproducible, interpretable method for grouping human faces by topological similarity, independent of race, ethnicity, or culture. This enables:
- Objective formation of phenogroups and phenoclusters
- Visualization of human morphological diversity as a structured grid
- Discovery of causal links between form, cognition, and culture
- Anticipation of emergent forms ("empty cells") in human phenotypic space

---

## 📐 What is ALMS?
**ALMS** builds a hierarchical tree of phenotypes based on the cosine similarity between:
- Procrustes-aligned landmarks (68-point geometry)
- Spectral descriptors (Laplace–Beltrami eigenvalues)
- Fractal dimension of the facial contour
- Deep face embeddings (e.g., ArcFace)

It uses:
- k-Nearest Neighbors Graph (k=30)
- HDBSCAN for density-based clustering
- Agglomerative consolidation with silhouette score filtering (S > 0.25)

The output is a tree `T`, reproducible and interpretable — forming the basis of the **periodic grid**.

---

## 🧬 Grid of Phenotypes
The tree is projected onto a 2D lattice:
- **X-axis** — spectral smoothness (λ₁)
- **Y-axis** — fractal complexity (Dₑ)

Each cell = phenogroup. Empty cells = predicted but unseen forms.

---

## 📊 Cognitive & Cultural Layers
Overlaid variables:
- IQ, working memory, creativity
- HVIC (individualism/collectivism)
- SES, age, sex
- Language features (phonetics, syntax)
- Genetic admixture

Findings:
- Topology explains 3–5% variance in IQ
- Spectral complexity correlates with individualism (r ≈ 0.27)

---

## 🧩 Use Cases
- Predictive diagnostics in medicine
- Adaptive VR/AR and education platforms
- Cultural evolution modeling
- Explainable AI models for identity and interaction

---

## ⚖️ Ethical Commitments
- 🔓 Open-source under AIGPL
- 🛑 Community killswitch built-in
- 🔄 All simulations tested in reversible sandbox
- 🧭 Oversight consortium for critical use cases

> \"The power of AI must remain governed by science — not ideology, profit, or control.\"

---

## 📎 Contents
- `whitepaper.pdf` – Full paper
- `/figures/` – Infographics (grids, trees, graphs)
- `/notebooks/` – Experimental pseudocode and demos
- `LICENSE` – AIGPL

---

© Anton L., 2025 — Independent Laboratory for the Evolution of Form
