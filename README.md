# RAG Configuration Evaluator with RAGChecker

This project evaluates Retrieval-Augmented Generation (RAG) systems by testing combinations of chunking strategies, embedding models, and vector stores. It automates the comparison of RAG performance metrics (e.g., precision, recall, hallucination) across configurations

## Overview
This project benchmarks RAG (Retrieval-Augmented Generation) systems by testing different combinations of:
- **Chunking strategies** (fixed-length, context-aware, Markdown/LaTeX-aware)
- **Embedding models** (OpenAI, HuggingFace)
- **Vector stores** (FAISS, Pinecone, Chroma)

Metrics like precision, recall, faithfulness, and hallucination are evaluated to identify optimal configurations.

## Features
- **Chunking**: Supports multiple text-splitting strategies for diverse document types.
- **Embeddings**: OpenAI and HuggingFace embedding models.
- **Vector Stores**: Integration with FAISS (local), Pinecone (cloud), and Chroma (local/cloud).
- **Evaluation**: Metrics exported to CSV for easy comparison.


This notebook was developed in the scope of the European Union’s funded Project XR5.0 [GA
101135209].
