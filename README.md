#  Kenyan Constitution RAG Pipeline

This repository contains a Retrieval-Augmented Generation (RAG) pipeline designed to query the *Constitution of Kenya, 2010* using LangChain, FAISS, and Groq’s LLMs. It enables fast, source-backed answers to civic and legal questions, with modular components for embedding, retrieval, and inference.

---

##  Overview

- Load and chunk the Constitution PDF
- Embed text using HuggingFace transformers
- Store embeddings in FAISS vector database
- Query using LangChain’s `RetrievalQA` with Groq’s `llama3-8b-8192`
- Return both answer and source documents for transparency

---

## Tech Stack

| Component            | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `LangChain`         | Framework for chaining LLMs with retrieval and tools                        |
| `FAISS`             | Vector store for fast similarity search                                     |
| `Groq LLM`          | High-speed inference using `llama3-8b-8192`                                 |
| `HuggingFace`       | Embedding model: `all-MiniLM-L6-v2`                                         |
| `PyPDFLoader`       | Loads and parses the Constitution PDF                                       |
| `RecursiveTextSplitter` | Splits document into manageable chunks for embedding                  |

---

##  Pipeline Breakdown

### 1.  Load the Constitution.
### 2.  Chunk the text.
### 3.  Embed the Chunks.
### 4.  Store in FAISS.
### 5.  Secure Your API Key.
### 6.  Create the Retrieval Chain.
### 7.  Run a Sample Query.



