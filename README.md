## 🧠 AI Resume Screener (LangChain + Vector DB)

> An AI-powered resume screening system that summarizes resumes and evaluates their relevance against job descriptions using embeddings and semantic search.

---

## 📌 About

This project uses **LangChain and LLMs** to automate resume screening:

- 📄 Accepts **PDF / DOCX resumes**
- ✂️ Performs **chunking & text splitting**
- 🔢 Generates **embeddings** stored in a **vector database**
- 📝 Creates an **AI-generated resume summary**
- 📋 Embeds **job descriptions**
- 📊 Computes a **resume–JD match score**

---

## 🛠️ Tech Stack

<p align="left">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-0E76A8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LLM-GenAI-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Vector%20DB-FAISS-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Embeddings-Semantic_Search-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PDF-DOCX-red?style=for-the-badge"/>

</p>

---

## ⚙️ Workflow

```text
Resume / JD → Chunking → Embeddings → Vector DB → Similarity Search → LLM Summary & Score
