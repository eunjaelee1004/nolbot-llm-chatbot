![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-GPT--4-blue)
![RAG](https://img.shields.io/badge/RAG-Enabled-green)

# NolBot: LLM-based Support System for Developmental Disabilities

## 📌 Overview

NolBot is an AI-based support system designed to assist parents of children with developmental disabilities in daily communication and interaction.

The system leverages Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to provide:

- Context-aware dialogue guidance
- Parenting skill recommendations
- Activity (play) suggestions
- Related educational video recommendations

This project was developed for the Business Big Data course as a final project.

---

## 🎯 Problem Statement

The number of registered developmental disabilities has increased significantly in recent years, while access to continuous therapy remains limited.

Existing solutions face:
- High cost
- Regional imbalance in specialists
- Limited daily-life support

NolBot aims to bridge the gap between clinical therapy sessions by providing an AI-powered, low-cost, high-frequency daily support tool.

---

## 🧠 System Architecture

The system consists of multiple functional nodes:

1. Dialogue Guide Generator  
2. Parenting Skill Information (RAG-based)  
3. Play Recommendation (RAG-based)  
4. Video Recommendation (LLM + filtering pipeline)

Key technical components:
- Prompt engineering
- Embedding-based document retrieval
- Chunking to overcome token limits
- Multi-stage recommendation filtering
- Token usage and cost tracking

---

## 🔎 Key Features

### 1️⃣ Dialogue Guidance
- Categorizes conversation into planning, recall, and free discussion
- Encourages positive response strategies
- Avoids harmful reaction types (e.g., blame, correction overload)

### 2️⃣ Parenting Knowledge Retrieval
- Uses embedded Q&A dataset derived from official parenting guides
- Contextual answer generation via RAG

### 3️⃣ Play Recommendation
- Generates activity suggestions based on video context
- Incorporates domain-specific educational materials

### 4️⃣ Related Video Recommendation
- Web-crawled database (~400+ videos)
- Two-stage filtering using LLM
- Token-efficient chunked processing

---

## 📂 Repository Structure
nolbot-llm-chatbot/
├── README.md
├── notebooks/
│   └── team5_nolbot.ipynb
├── slides/
│   └── nolbot-presentation.pdf

## 👥 Team

- 박종휘
- 이은재
- 홍성연
