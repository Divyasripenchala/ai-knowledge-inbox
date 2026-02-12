# AI Knowledge Inbox

An AI-powered document-based question answering system built using FastAPI and Retrieval-Augmented Generation (RAG).

## Project Overview

AI Knowledge Inbox allows users to upload documents and ask questions based on their content.  
The system retrieves relevant information and generates intelligent responses using LLM-powered retrieval.

---

## Tech Stack

- Python
- FastAPI
- RAG (Retrieval Augmented Generation)
- Vector Database
- LLM Integration
- Git & GitHub

---

## Project Structure

backend/
 ├── app/
 │   ├── main.py
 │   ├── routes/
 │   ├── services/
 │   ├── utils/
 │   ├── config.py

 ## Features

- Upload and process documents
- Automatic text chunking
- Semantic search using embeddings
- Vector database storage
- Context-aware answer generation using LLM
- FastAPI backend APIs

## Architecture Flow

1. Document Upload
2. Text Chunking
3. Embedding Generation
4. Store embeddings in Vector Database
5. User Query → Convert to Embedding
6. Retrieve Top-K Similar Chunks
7. Pass context to LLM
8. Generate Final Answer

## How to Run

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run the FastAPI server:
   uvicorn main:app --reload
4. Access API at http://127.0.0.1:8000

 

