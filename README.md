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
