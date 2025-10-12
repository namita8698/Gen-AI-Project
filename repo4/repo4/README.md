# RAG Project – PDF Loader with FAISS

This project demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline using Python, LangChain, FAISS, and OpenAI embeddings. It loads PDF documents, converts them to embeddings, and allows semantic search or retrieval tasks.

## Features
- Load PDF documents with `PyPDFLoader`.
- Convert text from PDFs into embeddings using OpenAI.
- Store embeddings in **FAISS vector store** for fast similarity search.
- Ready to extend for question-answering or chatbot functionality.

## Project Structure
Task-03-RAG-Basic/
├── documents/ # Place your PDF files here
├── rag_task4_full.py # Main RAG pipeline script
├── requirements.txt # Python dependencies
└── README.md # Project documentation
