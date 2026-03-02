# AI Engineering — RAG System
## Document Q&A Chatbot with Vector Database

---

## What This Project Builds

A complete Retrieval Augmented Generation system — an AI 
chatbot that reads documents and answers questions based 
specifically on their content.

Unlike standard LLM chatbots that rely purely on training 
data, RAG systems retrieve relevant context from a knowledge 
base before generating responses. This dramatically reduces 
hallucinations and makes the AI grounded in real, specific 
information.

---

## Why RAG Matters

RAG is currently one of the most in-demand AI Engineering 
skills in the UK job market. Companies building internal 
knowledge tools, customer support bots, and document 
processing systems all rely on RAG architecture.

Building this project demonstrates:
- Understanding of how LLMs actually work
- Practical AI engineering beyond just using ChatGPT
- Ability to connect ML systems to real applications via API
- Production mindset — not just notebooks but deployed systems

---

## System Architecture
```
User Question
      ↓
Query Embedding (converts question to vector)
      ↓
FAISS Vector Database Search
      ↓
Retrieve Top Relevant Document Chunks
      ↓
Augment LLM Prompt with Retrieved Context
      ↓
LLM Generates Grounded Response
      ↓
Answer Returned via FastAPI Endpoint
```

---

## Project Structure
```
AI-Engineering-RAG-System/
│
├── data/
│   └── sample_documents/
│
├── notebooks/
│   ├── 01_embeddings_exploration.ipynb
│   ├── 02_vector_database_setup.ipynb
│   └── 03_rag_pipeline_prototype.ipynb
│
├── app/
│   ├── main.py              ← FastAPI application
│   ├── rag_chain.py         ← RAG pipeline logic
│   └── requirements.txt     ← All dependencies
│
└── README.md
```

---

## Build Roadmap

**Phase A — Foundations (Week 13–14)**
- Understand embeddings and how text becomes vectors
- Explore tokenisation and chunking strategies
- Build prompt engineering experiments notebook
- Compare before and after RAG response quality

**Phase B — RAG Pipeline (Week 15–16)**
- Build document ingestion and chunking pipeline
- Set up FAISS vector store
- Connect embeddings to retrieval system
- Build basic question answering on sample documents

**Phase C — Backend and Deployment (Week 17–18)**
- Wrap complete RAG pipeline in FastAPI
- Build clean REST endpoints
- Test all endpoints with Postman
- Deploy live on Render or Railway

**Phase D — Optimisation (Week 19–20)**
- Reduce hallucination rate
- Improve retrieval accuracy with better chunking
- Add logging and error handling
- Record 2-minute demo video for LinkedIn and CV

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Current Status

> Full build begins Week 13 of my 100 Days of Data Science 
> challenge. ML foundations are being completed first to ensure 
> this project is built with proper understanding — not just 
> copy-pasted tutorials.
>
> Follow the full journey on LinkedIn.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shoaib-aslam32922)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/imshoaibaslam)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:aslamshoaib197@gmail.com)
