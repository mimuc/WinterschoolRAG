# WinterschoolRAG

A hands-on tutorial for building a **Retrieval-Augmented Generation (RAG)** system that runs entirely on your local machine.

## What You'll Learn

- How to set up a local RAG pipeline using LlamaIndex
- Using Ollama for local LLM inference
- Embedding documents with HuggingFace sentence-transformers
- Storing and querying vectors with ChromaDB

## Prerequisites

1. **Python 3.11+**
2. **Ollama** installed and running ([download here](https://ollama.com/download))
3. A model pulled: `ollama pull llama3.1:8b`

## Setup

```bash
# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start Ollama (in a separate terminal)
ollama serve
```

## Usage

1. Add PDF documents to the `./documents` folder
2. Open `local_rag_tutorial.ipynb` in Jupyter
3. Run through the cells to build and query your RAG system

## Project Structure

```
WinterschoolRAG/
├── documents/          # Place your PDFs here
├── chroma_db/          # Vector database (auto-generated)
├── local_rag_tutorial.ipynb  # Main tutorial notebook
├── requirements.txt    # Python dependencies
└── README.md
```

