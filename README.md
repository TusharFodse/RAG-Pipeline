📚 RAG Pipeline – Retrieval Augmented Generation

A complete Retrieval-Augmented Generation (RAG) pipeline built using Python, LangChain / LangGraph, Groq LLM, and a Vector Database to enable accurate, context-aware question answering over custom documents.

🚀 Features

📄 Load data from PDF / CSV / Text

✂️ Intelligent text chunking

🧠 Embeddings generation

🗂️ Persistent Vector Database (Chroma / FAISS)

🔍 Semantic similarity search

🤖 LLM response generation using Groq (LLaMA)

🧵 Optional LangGraph memory for conversational RAG

🔐 Secure API key handling using environment variables

🧠 What is RAG?

Retrieval-Augmented Generation (RAG) improves LLM responses by:

Retrieving relevant documents from a vector database

Injecting them as context into the LLM prompt

Generating accurate, grounded answers

📌 This avoids hallucinations and improves reliability.

🏗️ Project Architecture

User Query
   ↓
Embedding Model
   ↓
Vector Database (Chroma / FAISS)
   ↓
Relevant Chunks
   ↓
Prompt + Context
   ↓
Groq LLM
   ↓
Final Answer


🧰 Tech Stack
Component	Technology
Language	Python
LLM	Groq (LLaMA-3 / LLaMA-3.3)
Framework	LangChain / LangGraph
Vector DB	Chroma / FAISS
Embeddings	Sentence Transformers
Data	PDF, CSV, Text
Environment	Virtualenv
