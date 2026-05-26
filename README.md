# LangChain Operations

A complete hands-on repository covering different LangChain operations, Retrieval-Augmented Generation (RAG), Vector Stores, Embeddings, Data Ingestion, and Local LLM applications using Ollama.

---

# 📂 Project Structure

```bash id="m8q2vk"
Langchain/
│
├── 1-Langchain/
│   ├── 1.1-openai/
│   │
│   └── 1.2-ollama/
│       ├── 1.2.1-Simpleapp.ipynb
│       └── app.py
│
├── 3.2-Dataingestion/
│   ├── 3.2-Dataingestion.ipynb
│   ├── attention.pdf
│   ├── records.xml
│   └── speech.txt
│
├── 3.3-DataTransformer/
│   ├── 3.3-RecursiveCharacterTextSplitter.ipynb
│   ├── 3.4-CharacterTextSplitter.ipynb
│   ├── 3.5-HTMLTextsplitter.ipynb
│   ├── 3.6-RecursiveJsonSplitter.ipynb
│   ├── attention.pdf
│   └── speech.txt
│
├── 4-Embeddings/
│   ├── 4.1-embedding.ipynb
│   ├── 4.2-ollamaembedding.ipynb
│   ├── 4.3-huggingface.ipynb
│   └── speech.txt
│
├── 5-VectorStore/
│   ├── chroma_db/
│   ├── faiss_index/
│   ├── 5.1-Faiss.ipynb
│   ├── 5.2-Chroma.ipynb
│   └── speech.txt
│
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

---

# 📌 Topics Covered

## 🔹 LangChain Basics

* Prompt Templates
* Chains
* Output Parsers
* Document Chains
* Retrieval Chains

---

## 🔹 Data Ingestion

* Text Loader
* PDF Loader
* XML Loader
* WebBaseLoader
* Wikipedia Loader
* Arxiv Loader

---

## 🔹 Data Transformation

* Recursive Character Text Splitter
* Character Text Splitter
* HTML Text Splitter
* Recursive JSON Splitter

---

## 🔹 Embeddings

* OpenAI Embeddings
* Ollama Embeddings
* HuggingFace Embeddings

---

## 🔹 Vector Stores

* FAISS
* ChromaDB

---

## 🔹 GenAI Applications

* Streamlit App 
* Local LLM using Ollama
* Gemma Model Integration

---

# 🛠️ Tech Stack

* Python
* LangChain
* Ollama
* Streamlit
* FAISS
* ChromaDB
* HuggingFace
* OpenAI
* Sentence Transformers

---

# ⚙️ Setup Instructions

## 1️⃣ Clone Repository

```bash id="x5q9wc"
git clone https://github.com/alokitm/GenAI.git
```

---

## 2️⃣ Move to Project Directory

```bash id="u1p4tx"
cd GenAI
```

---

## 3️⃣ Create Environment

```bash id="r7m8qp"
conda create -p venv python=3.13 -y
```

---

## 4️⃣ Activate Environment

```bash id="f2m5vk"
conda activate ./venv
```

---

## 5️⃣ Install Requirements

```bash id="k9q2wc"
pip install -r requirements.txt
```

---

# 🤖 Ollama Setup

Install Ollama and pull model:

```bash id="v4m8tx"
ollama pull gemma:2b
```

Check installed models:

```bash id="p6q1vk"
ollama list
```

---

# ▶️ Run Streamlit App

Move into app directory:

```bash id="x3m7wc"
cd 1-Langchain/1.2-ollama
```

Run app:

```bash id="m1v4tx"
streamlit run app.py
```

---

# 📚 What You Will Learn

* Building LLM Applications
* Retrieval-Augmented Generation (RAG)
* Document Loading
* Text Chunking
* Embedding Models
* Vector Databases
* Local LLM Integration
* Streamlit Deployment
* End-to-End LangChain Pipelines

---

# 👨‍💻 Author

Alokit Mishra

---

# ⭐ Star the Repository

If you found this repository useful, consider giving it a star ⭐
