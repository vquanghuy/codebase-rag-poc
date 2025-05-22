# TypeScript Codebase Retrieval-Augmented Generation pipeline (POC)

Proof of Concept (POC) for a Retrieval-Augmented Generation (RAG) system designed to enhance understanding and interaction with a large TypeScript/React Native codebase. 

**Key Technologies:**
* **LLM:** Llama family model (via Ollama)
* **Framework:** LlamaIndex (Python)
* **Vector Store:** Qdrant (Primary) / FAISS (Alternative)
* **Embedding Model:** GraphCodeBERT
* **Code Chunking:** AST-based parsing (via LlamaIndex CodeSplitter with tree-sitter)
* **Target Codebase:** TypeScript / React Native (~5000 files)
* **UI (Optional):** Open WebUI

**Goals:**
* Improve codebase understanding.
* Facilitate more accurate code fixing.
* Enhance code completion suggestions.
* Explore local, privacy-focused AI-assisted development.

This project aims to build a local RAG pipeline to provide contextual insights and assistance for developers working on the specified codebase.
