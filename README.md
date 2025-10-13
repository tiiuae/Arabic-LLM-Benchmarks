# Arabic LLM Benchmarks: A Comprehensive Collection

[![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](YOUR_ARXIV_LINK)
[![Survey](https://img.shields.io/badge/Survey-EACL%202025-blue.svg)](YOUR_PAPER_LINK)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

A centralized, actively maintained repository cataloging all Arabic Large Language Model evaluation benchmarks. This resource accompanies our survey paper: **"Evaluating Arabic Large Language Models: A Survey of Benchmarks, Methods, and Gaps"**.

## 📝 Abstract

This survey provides the first systematic review of Arabic LLM benchmarks, analyzing 40 evaluation frameworks across NLP tasks, knowledge domains, cultural understanding, and specialized capabilities. We propose a taxonomy organizing benchmarks into four categories: Knowledge and STEM, NLP Tasks, Culture and Dialects, and Target-Specific evaluations. Our analysis reveals significant progress in benchmark diversity while identifying critical gaps: limited temporal evaluation, insufficient multi-turn dialogue assessment, and cultural misalignment in translated datasets. We examine three primary approaches: native collection, translation, and synthetic generation discussing their trade-offs regarding authenticity, scale, and cost. This work serves as a comprehensive reference for Arabic NLP researchers, providing insights into benchmark methodologies, reproducibility standards, and evaluation metrics while offering recommendations for future development.

## 🎯 Purpose

Despite rapid growth in Arabic LLM development, evaluation resources remain fragmented across 30+ benchmarks with varying accessibility. This repository provides:

- **Centralized access** to all Arabic LLM benchmarks
- **Direct links** to papers, datasets, code repositories, and evaluation frameworks
- **Standardized metadata** for easy comparison and selection
- **Regular updates** as new benchmarks emerge

## 📊 Quick Stats

- **40 Benchmarks** across 4 major categories
- **Coverage:** NLP Tasks, Knowledge & STEM, Culture & Dialects, Target-Specific
- **xx%** of benchmarks released in 2024-2025
- **xx%** provide both public datasets and code repositories

## 🗂️ Benchmark Categories

### 1. **Arabic NLP Tasks** (xx benchmarks)
Classical and comprehensive NLP evaluation including translation, summarization, QA, and multi-task assessment.

### 2. **Knowledge & STEM** (xx benchmarks)
General knowledge, STEM subjects, and domain-specific evaluation (law, medicine, poetry, religious knowledge).

### 3. **Culture & Dialects** (xx benchmarks)
Cultural understanding, commonsense reasoning, dialectal diversity, and proverbs.

### 4. **Target-Specific Tasks** (xx benchmarks)
Instruction-following, RAG evaluation, hallucination detection, safety, and multimodal capabilities.

## 📋 Complete Benchmark Table

### Legend
- 🟢 **Fully Public:** Dataset + Code + Evaluation pipeline available
- 🟡 **Partially Public:** Dataset available, code/evaluation limited
- 🔴 **Private:** Dataset unavailable or access upon request
- ⚡ **Framework:** Integrated with lighteval or lm-eval-harness

---

### Arabic NLP Tasks

| Year | Benchmark | Status | Paper | Dataset | Code | Framework | Size | Metrics | Tasks |
|------|-----------|--------|-------|---------|------|-----------|------|---------|-------|
| 2019 | ARCD | 🟢 | [Paper](https://arxiv.org/abs/1906.05394) | [Dataset](LINK) | [Code](LINK) | - | 1.4k | EM, F1 | Reading Comprehension |
| 2020 | TyDiQA (Arabic) | 🟢 | [Paper](https://arxiv.org/abs/2003.05002) | [Dataset](LINK) | [Code](LINK) | - | 14k | EM, F1 | Question Answering |
| 2023 | ORCA | 🟢 | [Paper](https://arxiv.org/abs/2212.10758) | [Dataset](LINK) | [Code](LINK) | - | 588k | Acc, F1, Pearson | Multi-task NLU (60 datasets) |
| 2023 | Dolphin | 🟢 | [Paper](https://arxiv.org/abs/2305.14989) | [Dataset](LINK) | [Code](LINK) | - | 2M | BLEU, ROUGE, BERTScore | Multi-task NLG (15 datasets) |
| 2024 | LAraBench | 🟢 | [Paper](https://aclanthology.org/2024.eacl-long.28/) | [Dataset](LINK) | [Code](LINK) | - | 296k | F1, BLEU, Task-specific | 33 tasks across 61 datasets |
| 2025 | BALSAM | 🟡 | [Paper](https://arxiv.org/abs/2507.22603) | [Partial](LINK) | [Code](LINK) | ⚡ | 52k | LLM-as-Judge, BLEU, ROUGE | 78 tasks, 14 categories |

---

### Knowledge & STEM Tasks

| Year | Benchmark | Status | Paper | Dataset | Code | Framework | Size | Domain | Topics |
|------|-----------|--------|-------|---------|------|-----------|------|--------|--------|
| 2020 | MMLU_ar | 🟢 | [Paper](https://arxiv.org/abs/2009.03300) | [Dataset](LINK) | [Code](LINK) | ⚡ | 14.97k | General | 57 subjects (translated) |
| 2020 | EXAMS_ar | 🟢 | [Paper](https://arxiv.org/abs/2011.03080) | [Dataset](LINK) | [Code](LINK) | - | 562 | STEM | High school exams |
| 2024 | ArabicMMLU | 🟢 | [Paper](https://arxiv.org/abs/2402.12840) | [Dataset](LINK) | [Code](LINK) | ⚡ | 14.57k | General | Native, all education levels |
| 2024 | AraST EM | 🔴 | [Paper](https://arxiv.org/abs/2501.00559) | ❌ | ❌ | - | 11.63k | STEM | Native STEM focus |
| 2024 | Qiyas | 🔴 | [Paper](https://arxiv.org/abs/2407.00146) | ❌ | ❌ | - | 2.4k | General | GAT-based (linguistic + math) |
| 2024 | ArabLegalEval | 🟢 | [Paper](https://arxiv.org/abs/2408.07983) | [Dataset](LINK) | [Code](LINK) | - | 26.4k | Law | Saudi legal system |
| 2025 | MizanQA | 🟡 | [Paper](https://arxiv.org/abs/2508.16357) | [Dataset](LINK) | ❌ | - | 1.7k | Law | Moroccan law |
| 2025 | Fann or Flop | 🟢 | [Paper](https://arxiv.org/abs/2505.18152) | [Dataset](LINK) | [Code](LINK) | - | 6.9k | Poetry | Arabic poetry understanding |
| 2025 | Hajj-FAQ | 🟢 | [Paper](LINK) | [Dataset](LINK) | [Code](LINK) | - | TBD | Religion | Islamic jurisprudence |
| 2025 | MedArabiQ | 🟢 | [Paper](https://arxiv.org/abs/2505.03427) | [Dataset](LINK) | [Code](LINK) | - | 700 | Medicine | Medical QA and exams |
| 2025 | GATmath & GATLc | 🟡 | [Paper](LINK) | [Dataset](LINK) | ❌ | - | 16k | General | GAT-based (9k+7k) |
| 2025 | 3LM | 🟢 | [Paper](https://arxiv.org/abs/2507.15850) | [Dataset](LINK) | [Code](LINK) | - | 3.15k | STEM + Code | Native, synthetic, code |
| 2025 | Arabic-GSM8K | 🟡 | [Paper](LINK) | [Dataset](https://huggingface.co/datasets/Omartificial-Intelligence-Space/Arabic-gsm8k-v2) | ❌ | - | 8.9k | Math | Translated + validated |

---

### Culture & Dialects Tasks

| Year | Benchmark | Status | Paper | Dataset | Code | Framework | Size | Focus |
|------|-----------|--------|-------|---------|------|-----------|------|-------|
| 2025 | Jawaher | 🟢 | [Paper](LINK) | [Dataset](LINK) | [Code](LINK) | - | 10k | Proverbs, figurative language |
| 2025 | PALM | 🟢 | [Paper](LINK) | [Dataset](LINK) | [Code](LINK) | - | 17.4k | Cultural expressions, 22 countries |
| 2025 | PalmX | 🟢 | [Paper](https://arxiv.org/abs/2509.02550) | [Dataset](LINK) | [Code](LINK) | - | 6.4k | Shared task: Arabic & Islamic culture |
| 2025 | Commonsense in Arab Culture | 🟢 | [Paper](LINK) | [Dataset](LINK) | [Code](LINK) | - | 3.5k | Culturally situated inference |
| 2025 | AraDiCE | 🟢 | [Paper](LINK) | [Dataset](LINK) | [Code](LINK) | - | 45k | Dialectal capabilities (QA, cloze, classification) |
| 2025 | AL-QASIDA | 🔴 | [Paper](LINK) | ❌ | ❌ | - | - | Dialectal error analysis |
| 2025 | Absher | 🔴 | [Paper](https://arxiv.org/abs/2507.10216) | ❌ | ❌ | - | 18k | Saudi dialect (6 categories) |

---

### Target-Specific Tasks

| Year | Benchmark | Status | Paper | Dataset | Code | Framework | Size | Purpose |
|------|-----------|--------|-------|---------|------|-----------|------|---------|
| 2024 | CamelEval | 🔴 | [Paper](LINK) | ❌ | ❌ | - | 1.61k | Instruction-following |
| 2024 | Halwasa | 🔴 | [Paper](https://aclanthology.org/2024.lrec-main.699/) | ❌ | ❌ | - | 10k | Hallucination detection |
| 2025 | ALRAGE | 🟢 | [Paper](LINK) | [Dataset](LINK) | [Code](LINK) | ⚡ | 21.2k | RAG evaluation |
| 2025 | AraTable | 🟢 | [Paper](https://arxiv.org/abs/2507.18442) | [Dataset](LINK) | [Code](LINK) | - | 615 | Tabular reasoning |
| 2025 | AraHalluEval | 🟡 | [Paper](https://arxiv.org/abs/2509.04656) | [Dataset](LINK) | ❌ | - | 1.52k | Hallucination (QA + summarization) |
| 2025 | HalluVerse25 | 🟡 | [Paper](https://arxiv.org/abs/2503.07833) | [Dataset](LINK) | ❌ | - | 828 | Fine-grained hallucination |
| 2024 | AraTrust | 🟢 | [Paper](https://arxiv.org/abs/2403.09017) | [Dataset](LINK) | [Code](LINK) | - | 522 | Trustworthiness (9 dimensions) |
| 2025 | ASAS | 🟢 | [Website](https://www.aiastrolabe.com/post/redteaming-frontier-llms-with-ai-astrolabe-arabic-safety-index-asas) | [Info](LINK) | - | - | 5.8k | Safety red-teaming |
| 2024 | Peacock/Henna | 🟢 | [Paper](https://arxiv.org/abs/2403.01031) | [Dataset](LINK) | [Code](LINK) | - | - | Multimodal (VQA/OCR + culture) |
| 2024 | CAMEL-Bench | 🟢 | [Paper](https://arxiv.org/abs/2410.18976) | [Dataset](LINK) | [Code](LINK) | - | - | Multimodal (8 domains, 38 subdomains) |
| 2025 | ARB | 🟢 | [Paper](https://arxiv.org/abs/2505.17021) | [Dataset](LINK) | [Code](LINK) | - | - | Multimodal reasoning |

---

### Statistics

Last Updated: 15/10/2025
Benchmarks Tracked: 40

---

## 📚 Citation
If you use this repository or find our survey helpful, please cite:
```
@inproceedings{ahmed2025arabic,
  title={Evaluating Arabic Large Language Models: A Survey of Benchmarks, Methods, and Gaps},
  author={Ahmed Alzubaidi, Shaikha Alsuwaidi, Basma El Amel Boussaha,  Leen AlQadi, Omar Alkaabi, Mohammed Alyafeai, Hamza Alobeidli, Hakim Hacid},
  booktitle={arxiv},
  year={2025}
}
```
