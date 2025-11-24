# rag-notebook

A Python-based RAG (Retrieval-Augmented Generation) system for document processing and vector search.

## Features

- PDF and text document loading with LangChain
- Document chunking and embedding generation
- Vector storage using ChromaDB and FAISS
- Support for multiple document formats (PDF, TXT)

## Dependencies

- langchain & langchain-community
- chromadb
- faiss-cpu
- sentence-transformers
- pymupdf & pypdf

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Documents are stored in `data/` directory:
- `data/pdf/` - PDF files
- `data/text_files/` - Text files
- `data/vector_store/` - ChromaDB vector storage

## Notebooks

Example notebooks demonstrating document loading, processing, and RAG pipeline:

- [document.ipynb](notepad/document.ipynb) - Basic document loading with text and PDF files
- [pdf_loader.ipynb](notepad/pdf_loader.ipynb) - Complete RAG pipeline with PDF processing, chunking, embeddings, and vector storage
