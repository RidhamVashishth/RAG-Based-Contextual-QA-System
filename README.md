# AskTheDoc - Multi-Format Document Q&A System

A proficient, accurate, and interactive question-answering web application built with Streamlit. This tool leverages a Retrieval-Augmented Generation (RAG) pipeline to allow users to ask questions about the content of their uploaded documents (PDF, DOCX, PPTX, XLSX). The app can be accessed by visiting https://ragbasedanswers.streamlit.app/

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

# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source v

Of course. Here is the content from the document formatted as a raw Markdown string. You can copy and paste this directly into your README.md file on GitHub.

Markdown

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

### 2. Create a Virtual Environment
It is highly recommended to use a virtual environment to manage project dependencies.

Bash

## For Windows
python -m venv venv
venv\Scripts\activate

## For macOS/Linux
python3 -m venv venv
source venv/bin/activate

### 3. Install Dependencies
Create a requirements.txt file in the root of your project with the following content, and then run the installation command.

requirements.txt:

streamlit
google-generativeai
python-dotenv
pypdf
python-docx
python-pptx
openpyxl
langchain
langchain-text-splitters
langchain-community
langchain-huggingface
faiss-cpu
sentence-transformersenv/bin/activate

#### Installation Command:

pip install -r requirements.txt

### 4. Configure Environment Variables
Create a file named .env in the root directory and add your Google API key.

GOOGLE_API_KEY='YOUR_API_KEY_HERE'

### 5. Run the Application
streamlit run app.py

Of course. Here is the content from the document formatted as a raw Markdown string. You can copy and paste this directly into your README.md file on GitHub.

Markdown

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
2. Create a Virtual Environment
It is highly recommended to use a virtual environment to manage project dependencies.

Bash

# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
Create a requirements.txt file in the root of your project with the following content, and then run the installation command.

requirements.txt:

streamlit
google-generativeai
python-dotenv
pypdf
python-docx
python-pptx
openpyxl
langchain
langchain-text-splitters
langchain-community
langchain-huggingface
faiss-cpu
sentence-transformers
Installation Command:

Bash

pip install -r requirements.txt
4. Configure Environment Variables
Create a file named .env in the root directory and add your Google API key.

GOOGLE_API_KEY='YOUR_API_KEY_HERE'

### 5. Run the Application
Launch the Streamlit app from your terminal.

streamlit run app.py
The application should now be running and accessible in your web browser, typically at http://localhost:8501.

### Usage

Navigate to the application's URL.

Click the "Upload" button to select a supported document (PDF, DOCX, PPTX, or XLSX).

Wait for the success message indicating that the document has been processed.

Type your question about the document's content into the text input field.

Click the "Submit" button to receive an answer generated by the AI.

### License

This project is licensed under the MIT License. See the LICENSE file for more details.






