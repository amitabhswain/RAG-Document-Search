# End-to-End RAG Document Search System

This project implements a production-style Retrieval-Augmented Generation (RAG) system for semantic document search and question answering over heterogeneous sources (PDFs, URLs, and text files).

The system is built using a modular, graph-based architecture with LangGraph, separating document ingestion, vector storage, retrieval, and generation into reusable components. It supports both standard RAG generation and an agentic ReAct variant, where the LLM dynamically augments retrieved context with external tools (e.g., Wikipedia) when local knowledge is insufficient.

Key features include configurable chunking and embeddings, FAISS-based vector retrieval, explicit state management, and an interactive Streamlit UI that displays answers along with source documents and response latency.
