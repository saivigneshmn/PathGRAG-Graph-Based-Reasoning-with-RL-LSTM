# 📊 PathGRAG: Hybrid Framework for Multi-Hop Reasoning using Graphs and Reinforcement Learning

![GitHub repo size](https://img.shields.io/github/repo-size/saivigneshmn/pathgrag?color=blue)
![License](https://img.shields.io/github/license/saivigneshmn/pathgrag)
![Python](https://img.shields.io/badge/python-3.8+-blue)
![Platform](https://img.shields.io/badge/platform-Google%20Colab-yellow)

---

## 🚀 Overview

**PathGRAG** is a research-focused project that addresses the challenge of hallucination and factual inconsistency in Retrieval-Augmented Generation (RAG) systems. It combines:
- **LSTM**-based path embeddings  
- **Reinforcement Learning** for optimal reasoning path selection  
- **Community Detection** in Knowledge Graphs  
- **Multi-hop Reasoning and Hallucination Filtering**

Built and evaluated using **live multilingual news data** with **LLaMA-3**, semantic search, and `NetworkX`, the model outperforms baseline RAG and GraphRAG architectures.

---

## 📌 Key Features

✅ LSTM + Reinforcement Learning-based Path Optimization  
✅ Knowledge Graph Construction with Community Detection  
✅ Multi-hop Reasoning and Hallucination Filtering  
✅ Real-time Multilingual News Retrieval  
✅ RAGAS-based Output Evaluation  
✅ Visualization with Pyvis & NetworkX

---

## 🧠 Architecture

<p align="center">
  <img src="assets/architecture.png" width="700"/>
</p>

---

## 🧪 Working Demo

<p align="center">
  <img src="assets/demo.gif" width="700"/>
</p>

---

## 🧰 Tech Stack

- Google Colab + Python 3.10+
- Langchain + LLaMA-3-70B (via HuggingFace)
- Sentence Transformers (`all-MiniLM-L6-v2`)
- NetworkX, Pyvis
- Reinforcement Learning with custom reward function
- NewsAPI for real-time news

---

## 🛠️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/saivigneshmn/pathgrag.git
cd pathgrag

# 2. (Optional) Install requirements
pip install -r requirements.txt
> ✅ **Colab Users**:  
> Run the `PathGRAG_Final.ipynb` notebook from the `notebooks/` directory.  
> Upload your PDF or text data directly into the notebook and execute the cells step-by-step.
```

## 📊 Results

| Model        | BLEU | BERT | ROUGE | Cosine Similarity | RAGAS |
|--------------|------|------|--------|-------------------|--------|
| RAG Baseline | 0.16 | 0.59 | 0.35   | 0.81              | 0.67   |
| GraphRAG     | 0.47 | 0.61 | 0.45   | 0.85              | 0.79   |
| **PathGRAG** | **0.49** | **0.63** | **0.47** | **0.91** | **1.0** |

---

## 📚 Citations & References

- [1] Du et al. (2024) – *Graph Neural Network-Based Entity Extraction and Relationship Reasoning*. [arXiv:2411.15195](https://arxiv.org/abs/2411.15195)  
- [2] Saleh et al. (2024) – *SG-RAG: Multi-Hop Question Answering with Large Language Models Through Knowledge Graphs*. [ACL Anthology](https://aclanthology.org/2024.icnlsp-1.45.pdf)  
- [3] Zhang et al. (2023) – *GNN-RAG: Graph Neural Retrieval for Large Language Model Reasoning*. [arXiv:2405.20139](https://arxiv.org/abs/2405.20139)  

📎 **Full reference list** available in the [final_paper.pdf](./final_paper.pdf)

---

## 🤝 Acknowledgements
```
This research was developed at **Vellore Institute of Technology, Chennai**,  
under the guidance of **Brindha Subburaj** and team.
```
