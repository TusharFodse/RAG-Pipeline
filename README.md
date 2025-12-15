# 📚 RAG Pipeline – Retrieval Augmented Generation

A complete Retrieval-Augmented Generation (RAG) pipeline built using Python, Groq LLM, LangChain / LangGraph, and a Vector Database to enable accurate, context-aware question answering over custom documents.

---

## 🚀 Features

- Load data from PDF / CSV / Text
- Text chunking and preprocessing
- Embeddings generation
- Persistent Vector Database (Chroma / FAISS)
- Semantic similarity search
- LLM-based answer generation using Groq (LLaMA)
- Optional conversational memory using LangGraph
- Secure API key handling with environment variables

---

## 🧠 What is RAG?

Retrieval-Augmented Generation (RAG) improves LLM responses by retrieving relevant information from a vector database and injecting it into the prompt before generating an answer.  
This reduces hallucinations and improves accuracy.

---

## 🏗️ Architecture

User Query  
↓  
Embedding Model  
↓  
Vector Database  
↓  
Relevant Chunks  
↓  
Prompt + Context  
↓  
Groq LLM  
↓  
Final Answer  

---

## 📂 Project Structure

RAG-Pipeline/
│
├── data/
│   ├── raw_docs/
│   └── vector_store/
│
├── Notebook/
│   └── RAG.ipynb 
|
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md

---

## 🧰 Tech Stack

Language: Python  
LLM: Groq (LLaMA-3 / LLaMA-3.3)  
Framework: LangChain / LangGraph  
Vector DB: Chroma / FAISS  
Embeddings: Sentence Transformers  

---

## ⚙️ Installation

1. Clone repository

git clone https://github.com/TusharFodse/RAG-Pipeline.git  
cd RAG-Pipeline  

2. Create virtual environment

python -m venv venv  
venv\Scripts\activate  

3. Install dependencies

pip install -r requirements.txt  

---

## 🔐 Environment Variables

Create a .env file:

GROQ_API_KEY=your_groq_api_key_here

Note: Never commit API keys to GitHub.

---

## ▶️ How to Run

Run using Jupyter Notebook:

jupyter notebook  
Open Notebook/RAG.ipynb  

OR

Run using Python:

python src/rag_pipeline.py  

---

## 🧪 Example Query

Question: What is Encoder and Decoder in Deep Learning?

Answer:
The encoder converts input data into a compressed representation,
while the decoder reconstructs output from that representation.

---

## 🧵 Conversational RAG (Optional)

Supports conversational memory using LangGraph to maintain context across multiple queries.

---

## 🛡️ Security

- API keys stored in environment variables
- .env added to .gitignore
- GitHub push-protection safe

---

## 📈 Future Enhancements

- Web UI (Streamlit / React)
- Hybrid Search (BM25 + Vector)
- Re-ranking models
- Multi-document indexing
- Evaluation metrics

---

## 👨‍💻 Author

Tushar Fodse  
Aspiring AI / ML Engineer  

---

## 📜 License

MIT License

