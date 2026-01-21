AI Chatbot with LangGraph & RAG (PDF-Based Q&A)

An intelligent, stateful AI chatbot that enables document-based question answering using Retrieval-Augmented Generation (RAG). Users can upload PDF documents and ask natural language questions to receive accurate, context-aware responses grounded in the uploaded content.

This project leverages LangGraph for conversational workflow orchestration and FAISS for efficient semantic search over document embeddings.

🚀 Features

📄 PDF Upload Support – Upload documents and query them conversationally

🧠 Retrieval-Augmented Generation (RAG) – Answers are generated using retrieved document context

🔁 Multi-turn Conversations – Maintains conversational context across interactions

🗂 Semantic Search – Fast and accurate document retrieval using vector embeddings

💬 Interactive UI – Real-time chat interface built with Streamlit


🧱 Architecture Overview :

PDF Upload
   ↓
Document Loader (PyPDF)
   ↓
Text Chunking
   ↓
Embeddings (OpenAI)
   ↓
FAISS Vector Store
   ↓
Retriever
   ↓
LangGraph Workflow
   ↓
LLM Response (Context-Aware Answer)
