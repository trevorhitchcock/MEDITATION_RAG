# 🧘 Meditation RAG
A Retrieval-Augmented Generation (RAG) system for generating personalized, context-aware guided meditations using your own meditation library.

This project explores:
- Document ingestion and preprocessing of meditation transcripts
- Vector embedding generation using sentence transformers
- Retrieval of contextually relevant passages
- LLM generation guided by retrieved content

---

## 🚀 Project Overview

The goal of Meditation RAG is to build **grounded meditation scripts** tailored to specific user needs (e.g., sleep support, test anxiety). Instead of hallucinating content, the LLM draws directly from your curated dataset of meditation text.

This repository includes:
- A complete data processing pipeline
- Notebook-based training/evaluation experiments
- A final RAG generation workflow

---

## 🗂️ Structure

| Path | Description |
|------|-------------|
| `notebooks/04_rag_pipeline.ipynb` | Full RAG pipeline: ingestion → embedding → retrieval → generation |
| `notebooks/train_modelX.ipynb` | Experiments with embedding + generation models |
| `data/` | Meditation text files used for embedding (not included in repo) |
| `models/` | Exported embedding and retriever artifacts |

---

## 💻 Requirements

This repo was developed using:

- Python 3.10+
- Jupyter or VS Code for development
- Google Colab for GPU-enabled training steps

Recommended packages include:
