# Conversational RAG with PDF Upload & Chat History

## 📌 Overview
This project implements a **Conversational Retrieval-Augmented Generation (RAG)** system that allows users to **upload PDFs** and **chat** with their contents. It uses **GROQ's Llama3-8B model** to generate responses based on retrieved document chunks, maintaining **chat history** for a contextual conversation.

## ✨ Features
- 📂 **PDF Upload**: Upload one or multiple PDFs for knowledge extraction.
- 🔍 **Retrieval-Augmented Generation (RAG)**: Uses FAISS for efficient vector-based retrieval.
- 🗂 **Contextual Question Answering**: Converts user queries into standalone questions for better retrieval.
- 📝 **Chat History Maintenance**: Stores and reuses past interactions for context-aware responses.
- 🤖 **Uses Llama3-8B Model**: Powered by **GROQ API** for accurate and fast responses.

## 🏗️ Tech Stack
- **Python**
- **Streamlit** – for UI
- **LangChain** – for RAG & chatbot pipeline
- **FAISS** – for vector search
- **PyPDFLoader** – for document processing
- **HuggingFace Embeddings** – for text vectorization
- **GROQ API** – for Llama3 model-based responses

## 📖 Usage Guide
1. **Enter your GROQ API Key** in the input field.
2. **Upload one or more PDF files**.
3. Ask questions about the content of the PDFs.
4. The system retrieves relevant document chunks and generates answers.
5. **Chat history is maintained** to improve the conversational experience.

## ✉️ Contact
For any issues or feature requests, please raise an **issue** in the repository or contact me at `likithsatya192@gmail.com`.

