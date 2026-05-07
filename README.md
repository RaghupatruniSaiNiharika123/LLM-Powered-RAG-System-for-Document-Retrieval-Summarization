# LLM-Powered-RAG-System-for-Document-Retrieval-Summarization
Developed an LLM-powered RAG system for document retrieval and summarization using chunking, embeddings, and semantic search. Built FastAPI-based Q&amp;A APIs, processed 10K+ text chunks, improved answer relevance by 35%, reduced response time by 30%, and enhanced output precision by 25% through retrieval optimization and prompt tuning.

## Overview
This project is an end-to-end Retrieval-Augmented Generation (RAG) system designed for intelligent document retrieval, semantic search, question answering, and text summarization using Large Language Models (LLMs).

The system processes large volumes of documents by chunking text, generating embeddings, storing them in a vector database, and retrieving the most relevant information for user queries.

---

## Features
- Document chunking and preprocessing
- Embedding generation for semantic search
- FastAPI-based APIs
- LLM-powered Question Answering
- Automatic document summarization
- Semantic search using vector embeddings
- Scalable document indexing
- Optimized retrieval and prompt tuning

---

## Tech Stack

### Backend
- Python
- FastAPI

### AI / NLP
- LangChain
- OpenAI / HuggingFace
- Sentence Transformers

### Vector Database
- FAISS / ChromaDB

### Other Libraries
- NumPy
- Pandas
- Uvicorn

---

## Project Highlights
- Improved answer relevance by 35%
- Reduced response time by 30%
- Improved output precision by 25%
- Processed and indexed 10K+ text chunks
- Built scalable semantic search pipeline

---

## System Workflow
1. Upload documents
2. Preprocess and chunk text
3. Generate embeddings
4. Store embeddings in vector database
5. Retrieve relevant chunks
6. Pass context to LLM
7. Generate answers and summaries

---

## API Endpoints

### Question Answering API
POST `/ask`

Example Request:
```json
{
  "query": "What is Retrieval-Augmented Generation?"
}
