# Conversational RAG with PDF & Chat History

A Streamlit-based Retrieval-Augmented Generation (RAG) system that enables users to upload PDFs and interact with their content through conversational queries. The app leverages HuggingFace embeddings for semantic search, Cassandra/ChromaDB as a vector store, and Groq LLM for context-aware Q&A. It also maintains session-based chat history to provide continuity in conversations.

---

## ✨ Features

- **PDF Uploads:** Upload one or multiple PDF documents for instant processing.  
- **Semantic Search:** Uses HuggingFace embeddings to generate embeddings and retrieve contextually relevant passages.  
- **Conversational Q&A:** Groq LLM answers queries with concise, context-aware responses.  
- **Chat History:** Maintains session-based chat history to handle follow-up questions naturally.  
- **Scalable Vector Store:** Stores embeddings in Cassandra/ChromaDB for efficient retrieval.  
- **Interactive UI:** Simple and clean interface built with Streamlit.  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9 or higher
- Groq API Key
- HuggingFace Token

### 1. Clone the Repository
```bash
git clone <repository_url>
cd rag-pdf-chat
