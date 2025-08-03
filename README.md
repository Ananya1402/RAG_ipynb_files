# RAG_ipynb_files

A repository for GenAI, Retrieval Augmented Generation (RAG), and NLP Jupyter notebooks. Each notebook demonstrates practical implementations of modern AI workflows, including document retrieval, knowledge graph integration, and reranking techniques.

---

## Contents

### 1. RAG_full_basic/RAG_practice.ipynb

**Overview:**  
Implements a basic RAG pipeline using ChromaDB as the vector database and Sentence Transformers for embeddings.  
**Features:**  
- Loads external data using web loaders  
- Chunks documents for efficient retrieval  
- Generates embeddings with HuggingFace models  
- Retrieves relevant documents using similarity search  
- Integrates with Google Gemini LLM for response generation  
- Uses LangChain for orchestration

---

### 2. KG_RAG_Neo4j/Knowledge_Graph.ipynb

**Overview:**  
Combines RAG architecture with a Neo4j knowledge graph for enhanced retrieval and reasoning.  
**Features:**  
- Stores entities, metadata, and relationships in Neo4j  
- Uses ChromaDB for vector search  
- Integrates LangChain for graph queries and retrieval  
- Demonstrates entity extraction, relationship mapping, and graph-based augmentation  
- Embeddings generated via HuggingFaceEmbeddings

---

### 3. Reranking/Reranking.ipynb

**Overview:**  
Demonstrates document reranking in a RAG workflow using Cohere's rerank API.  
**Features:**  
- Generates document embeddings with Sentence Transformers  
- Stores and retrieves documents using ChromaDB  
- Applies Cohere's rerank model to improve relevance of retrieved results  
- Skeleton notebook for quick experimentation with reranking

---

## Getting Started

1. Clone the repository.
2. Open any notebook in Jupyter or VS Code.
3. Install required packages (see `%pip install ...` cells in each notebook).
4. Add your API keys (Cohere, Gemini, Neo4j) as needed.

---

## Folder Structure

- `RAG_full_basic/` — Basic RAG pipeline with ChromaDB and Gemini
- `KG_RAG_Neo4j/` — RAG with Neo4j knowledge graph integration
- `Reranking/` — RAG pipeline with document reranking

---

## Requirements

- Python 3.x
- Jupyter Notebook or VS Code
- API keys for Cohere, Gemini, Neo4j (as needed)
- See each notebook for specific package requirements

---

## License

This repository is for educational and research purposes.