# Sepideh Moafi 

### Computational Researcher · Biomedical AI & Computational Biology

Research Software · Genomics · Multi-omics · Foundation Models

Building reproducible research software for biomedical data science: foundation models, genomics, transcriptomics, and evidence-grounded retrieval systems.

---

## What I Work On

- **Biomedical Foundation Models** — BioGPT fine-tuning, LoRA/PEFT, retrieval-augmented generation
- **Computational Genomics** — ClinVar, TCGA, transcriptomics, variant interpretation
- **Reproducible Research Software** — pytest, GitHub Actions, Docker, leakage-safe machine learning
- **Open Science** — public models, datasets, and reproducible research artifacts

---

## Tech Stack

**Languages & Frameworks:**
Python · PyTorch · Hugging Face Transformers · PyTorch Geometric · scikit-learn

**Research Software Engineering:**
Git · pytest · GitHub Actions · Docker · YAML/JSON · CI

**Biomedical AI:**
BioGPT · LoRA/PEFT · FAISS · RAG · Sentence Transformers

**Bioinformatics:**
Scanpy · DESeq2 · edgeR · limma/voom · Biopython

---

## Featured Projects

### LongiHealth — Leakage-safe longitudinal EHR analysis
[github.com/AIResearcher20/longihealth](https://github.com/AIResearcher20/longihealth)

A twelve-module Python pipeline for longitudinal electronic health records, built on MIMIC-IV. Enforces patient-level splitting and training-only preprocessing to prevent data leakage in mortality modelling. Ships with tests, YAML configuration, Docker image, and CI.

`Python · pytest · Docker · GitHub Actions · MIMIC-IV`

### scp-bench — Reproducible ML benchmarking for single-cell proteomics
[github.com/AIResearcher20/scp-bench](https://github.com/AIResearcher20/scp-bench)

A modular benchmarking framework on SCoPE2 data with cell-aware cross-validation and leakage-safe preprocessing. Compares five classifiers across eight metrics. LightGBM reaches 98.3% test accuracy under permutation validation.

`Python · LightGBM · XGBoost · PyTorch · pytest · Docker · SCoPE2`

### VariantLens — Command-line tool for rare Mendelian variant interpretation
[github.com/AIResearcher20/variant-lens](https://github.com/AIResearcher20/variant-lens)

A fifteen-module CLI for annotating, retrieving, and ranking biomedical literature evidence for rare genetic variants. Migrated the ClinVar data layer from rate-limited web services to official bulk tables, reducing evidence preparation from minutes to seconds. Includes a benchmark of BM25, PubMedBERT dense retrieval, and hybrid Reciprocal Rank Fusion.

`Python · ClinVar · PubMedBERT · BM25 · FAISS`

### BioGPT-ClinVar — Parameter-efficient fine-tuning on ClinVar
[github.com/AIResearcher20/biogpt-clinvar](https://github.com/AIResearcher20/biogpt-clinvar)

Fine-tuned BioGPT (347M parameters) with LoRA on ClinVar-derived instruction data, using a single NVIDIA T4 GPU. Released the fine-tuned model, the adapter weights, and the instruction dataset on Hugging Face.

`Python · PyTorch · BioGPT · LoRA/PEFT · Hugging Face`

### PathogenAgentAI — Biomedical foundation model and retrieval platform
[github.com/AIResearcher20/PathogenAgent](https://github.com/AIResearcher20/PathogenAgent)

Processed 8.99 million raw ClinVar records into more than 4.2 million analysis-ready variants. Includes a modular retrieval-augmented generation layer built on sentence embeddings, FAISS, and UniProt, together with a Gradio interface.

`Python · BioGPT · LoRA/PEFT · FAISS · Gradio · ClinVar`

### OmniLatent — Representation learning for transcriptomic data
[github.com/AIResearcher20/OmniLatent](https://github.com/AIResearcher20/OmniLatent)

A deep autoencoder trained on TCGA-BRCA RNA-seq data (1,231 samples × 23,375 genes), compressing expression profiles into a 128-dimensional latent space. Released pretrained weights and a processed dataset with predefined splits.

`Python · PyTorch · Autoencoder · TCGA-BRCA`

### RACIPE-EMT — Mechanistic modelling of EMT heterogeneity
A nine-state mechanistic ODE model of epithelial–mesenchymal transition, extended with 10,000 randomized RACIPE kinetic models and validated against transcriptomic time-course data.

`Python · ODE modelling · RACIPE`

---

## Connect

[GitHub](https://github.com/AIResearcher20) · [Hugging Face](https://huggingface.co/Sepideh2027)
