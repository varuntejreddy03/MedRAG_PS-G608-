# MedRAG_PS-G608-
AI-powered Clinical Decision Support System using Retrieval-Augmented Generation (RAG) with Knowledge Graphs — Inspired by MedRAG Research.
# MedRAG_PS

🚑 A Clinical Decision Support System powered by Retrieval-Augmented Generation (RAG) and Knowledge Graph-Elicited Reasoning.

Inspired by the research paper:
**"MedRAG: Enhancing Retrieval‑Augmented Generation with Knowledge Graph‑Elicited Reasoning for Healthcare Copilot"**

## 🔍 Overview

This project aims to simulate and implement the MedRAG framework to:

- Retrieve similar patient records from EHR datasets (e.g., DDXPlus)
- Use a hierarchical knowledge graph to enhance reasoning
- Generate accurate, explainable diagnoses and follow-up diagnostic questions using LLMs

## 📦 Features

- FAISS-based retrieval on symptom queries
- 4-layer Medical Knowledge Graph (Symptoms → Disease → System)
- GPT-powered diagnostic reasoning
- Follow-up question generation
- Evaluation metrics (L1/L2/L3 Accuracy, BLEU, ROUGE)
- (Optional) React.js UI for doctor interaction

## 🛠️ Tech Stack

- Python, FAISS, NetworkX, Sentence-BERT
- OpenAI GPT-4 or LLaMA for text generation
- DDXPlus dataset (or mock EHR)
- (Optional) React.js, FastAPI, MongoDB

## 🧠 Dataset

- [DDXPlus](https://github.com/SNOWTEAM2023/MedRAG) - Public synthetic patient EHR dataset
- Optional: Kaggle-based symptom-disease data

## 📂 Project Structure
intially idea:
<img width="395" height="336" alt="{8FCA02E8-C0DB-4676-82E8-DED1F9CD0B13}" src="https://github.com/user-attachments/assets/12791438-59ee-4c05-8767-4137c95ae580" />


## 📄 Reference

> MedRAG Paper: [Read here](https://drive.google.com/file/d/1qLFDKiVoNbrbNYo3uKPYdJaNsMLHdjlH/view?usp=sharing)  
> GitHub: https://github.com/SNOWTEAM2023/MedRAG
