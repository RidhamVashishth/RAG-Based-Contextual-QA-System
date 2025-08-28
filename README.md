# AskTheDoc - Multi-Format Document Q&A System

A proficient, accurate, and interactive question-answering web application built with Streamlit. This tool leverages a Retrieval-Augmented Generation (RAG) pipeline to allow users to ask questions about the content of their uploaded documents (PDF, DOCX, PPTX, XLSX).

---

## Overview

AskTheDoc is an intelligent assistant designed to help users quickly find and synthesize information from various document formats. By uploading a file, the system processes the text, creates a searchable knowledge base, and uses a powerful language model (Google Gemini) to provide contextually accurate answers to user queries. This eliminates the need for manual searching and allows for a natural, conversational way to interact with document content.

### Features

* **Multi-Format Support**: Ingests and processes PDF, Microsoft Word (.docx), PowerPoint (.pptx), and Excel (.xlsx) files.
* **RAG-Powered Q&A**: Utilizes a Retrieval-Augmented Generation architecture for accurate, context-aware answers based solely on the provided document.
* **High-Quality Embeddings**: Employs HuggingFace's `all-MiniLM-L6-v2` model for efficient and effective text embeddings.
* **Fast Vector Search**: Uses FAISS (Facebook AI Similarity Search) for rapid retrieval of relevant text chunks.
* **Interactive Interface**: A clean and user-friendly web interface built with Streamlit.

---

## Technology Stack

* **Language**: Python
* **Framework**: Streamlit
* **AI Model**: Google Gemini (`gemini-1.5-flash`)
* **Core Libraries**:
    * `langchain`, `langchain-community`, `langchain-text-splitters`, `langchain-huggingface`
    * `faiss-cpu` for vector storage
    * `pypdf`, `python-docx`, `python-pptx`, `openpyxl` for file parsing
    * `python-dotenv` for environment variable management

---

## Local Setup and Installation

To run this project on your local machine, please follow these steps.

### Prerequisites

* Python 3.8 or higher
* A Google API Key with the Generative Language API enabled. You can obtain one from [Google AI Studio](https://aistudio.google.com/app/apikey).

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <repository-directory>
