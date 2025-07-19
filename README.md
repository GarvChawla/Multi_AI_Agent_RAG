# 🧠 AI Agent RAG with LangGraph + Wikipedia Fallback

This project demonstrates a **LangGraph-powered Retrieval-Augmented Generation (RAG)** system that intelligently routes user queries either to a **vectorstore index** (for domain-specific queries) or to **Wikipedia** (for general knowledge questions).

## 🔧 Tech Stack

- **LangGraph** – Agent workflow engine
- **LangChain** – Retrieval and document processing
- **ChromaDB** – Local vector store (optional)
- **Astra DB + CassIO** – Persistent vector storage
- **Groq (Gemma-2b/9b)** – LLM for intelligent routing
- **HuggingFace Embeddings** – Text embeddings via `all-MiniLM-L6-v2`
- **Wikipedia** – Fallback tool for open-domain queries

---

## 📌 Features

✅ Dynamic query routing between vectorstore and Wikipedia  
✅ Streaming output via LangGraph  
✅ HuggingFace embeddings and Astra DB integration  
✅ Indexed documents from Lilian Weng’s blogs  
✅ Modular architecture with LangGraph nodes  
✅ Easy extensibility (e.g., Arxiv, Google Search, etc.)

---



