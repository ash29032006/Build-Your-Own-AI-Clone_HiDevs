# AI Chatbot with RAG - By Ashwin

## 📌 Overview
An AI-powered chatbot using **Streamlit, LangChain, FAISS, and GROQ's LLM (Llama3-70B)**. It provides intelligent, document-based responses by retrieving relevant information from uploaded files.

## ✨ Features
- **Supports multiple formats** – PDF, DOCX, TXT, CSV, HTML, Markdown.
- **Conversational Memory** – Tracks chat history for contextual responses.
- **Smart Chunking** – Uses **RecursiveCharacterTextSplitter** (1000 tokens, 200 overlap).
- **Embeddings & Vector Storage** – **HuggingFace (all-mpnet-base-v2)** & **FAISS**.
- **Modern UI** – User messages on the right, AI on the left.

## 🚀 Setup
1. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```
2. **Set API Key:**  
   Replace `your_groq_api_key` in the script.
3. **Run the chatbot:**  
   ```bash
   streamlit run app.py
   ```

## 🏗️ RAG Pipeline
1. **Load Documents** → Process using LangChain loaders.
2. **Chunking** → Split text using RecursiveCharacterTextSplitter.
3. **Embedding** → Convert text into vectors with HuggingFace.
4. **Store & Retrieve** → FAISS for efficient search.
5. **Generate Responses** → Llama3-70B provides answers based on retrieved data.

## 📌 Use Cases
- AI Assistant for document-based Q&A.
- Research, legal insights, and customer support.

---
🎯 **Powered by LangChain, FAISS, and GROQ 🤖**
