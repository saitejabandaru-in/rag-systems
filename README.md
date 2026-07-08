# RAG Systems

**Build production-grade Retrieval-Augmented Generation systems — with real evaluation and benchmarks.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## What Is RAG?

RAG = Retrieval-Augmented Generation

Instead of relying on the LLM's training data, RAG retrieves relevant documents in real-time:

User Question → Embed → Search vector DB → Find relevant docs →
LLM + retrieved docs → Grounded answer with citations

**Why RAG?** Current knowledge, private data, reduced hallucinations, source citations.

## RAG Evolution

Naive RAG → Advanced RAG → Modular RAG → Agentic RAG

## Key Components

### Document Loading
Load PDF, Word, HTML, code, CSV, and more.

### Chunking
Split documents into chunks (fixed size, recursive, or semantic).
Chunk size and overlap are critical for retrieval quality.

### Embeddings
Convert text to vectors (OpenAI, Cohere, BGE, or local models).

### Vector Database
Store and search embeddings (ChromaDB, Pinecone, Weaviate, pgvector).

### Retrieval
- Semantic search (vector similarity)
- BM25 (keyword)
- Hybrid (best of both)
- Reranking (cross-encoder)

## Advanced Techniques

- **HyDE** — Generate hypothetical answer, search with it
- **RAG Fusion** — Multiple query reformulations, combine results
- **Corrective RAG** — Evaluate retrieval quality, search web if poor
- **Agentic RAG** — Agent decides what to retrieve and when

## Evaluation with RAGAS

Metrics: faithfulness, answer relevancy, context recall, context precision

---

Part of the [Real-World AI Skills Ecosystem](https://github.com/saitejabandaru-in)
