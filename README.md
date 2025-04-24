# 🧑‍⚖️ RAG-Based Legal Question Answering System for Indian Law

This project implements a Retrieval-Augmented Generation (RAG) system designed to answer legal questions related to Indian law. It retrieves relevant legal statutes and case law, and uses a large language model to generate accurate, context-aware answers.

---

## 🔍 Overview

The system has two main versions:

1. **Older Version**: Uses local retrieval and HuggingFace model: 'allenai/unifiedqa-v2-t5-large-1363200' to generate answers based on retrieved legal texts.
2. **Gemini Version** (recommended): A more advanced implementation using Google's Gemini API, offering improved reasoning and response quality.

---

## 🧠 What It Does

- Accepts user questions related to Indian law.
- Embeds and indexes legal documents using **FAISS**.
- Retrieves top-k relevant sections based on semantic similarity.
- Feeds context into an LLM (HuggingFace model or Gemini) to generate a final answer.

---

## 🚀 Technologies Used

- **SentenceTransformers** for document embeddings
- **FAISS** for vector similarity search
- **LangChain / Gemini API / OpenAI API** for LLM integration
- **Jupyter Notebooks** for experimentation and visualization

---

## 📌 Notes

- The Gemini version is currently the **recommended** one due to improved quality.
- You can test either version by running them with your respective API credentials and dependencies.
- Legal data used for retrieval includes scraped or structured Indian legal texts.

---
