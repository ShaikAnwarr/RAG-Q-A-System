# 📘 RAG Q&A System with Streamlit, FAISS & Hugging Face

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)](https://streamlit.io/)  
[![Hugging Face](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface)](https://huggingface.co/)  
[![FAISS](https://img.shields.io/badge/FAISS-SemanticSearch-green)](https://faiss.ai/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)  

This project implements a **Retrieval-Augmented Generation (RAG) based Question-Answering system** using **Streamlit, FAISS, and Hugging Face Transformers**.  
It enables users to ask context-aware questions and get accurate answers by combining **semantic search** with **state-of-the-art language models**.

---

## 🚀 Features
- 🔍 **Semantic Search** with FAISS for fast and efficient document retrieval.  
- 🤖 **Context-Aware Answers** generated using Hugging Face Transformers.  
- 🌐 **Interactive Web App** built with Streamlit for easy user interaction.  
- 📄 **Document Embedding Indexing** for improved retrieval accuracy.  
- ⚡ **Lightweight & Scalable** design for real-time Q&A.  

---

## 🛠️ Technologies Used
- **Python 3**  
- **Streamlit** (Frontend UI)  
- **FAISS** (Vector Search & Indexing)  
- **Hugging Face Transformers** (Answer Generation)  

---

## 📂 Project Structure

├── app.py # Main Streamlit application
├── requirements.txt # Python dependencies
├── data/ # Folder for documents/corpus (if applicable)
└── README.md # Project documentation

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ShaikAnwarr/RAG-Q-A-System.git
   cd RAG-Q-A-System
Create & activate a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

Install dependencies

pip install -r requirements.txt

Run the Streamlit app

streamlit run app.py

🎯 How It Works
User enters a question in the Streamlit app.

FAISS retrieves the most relevant document embeddings.

Hugging Face Transformer model generates a context-based answer.

Answer is displayed instantly in the UI.


👤 Author
Shaik Anwar


