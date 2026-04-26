# RAG &amp; Retrieval Systems

Embedding models, vector databases, hybrid search and reranking, chunking, agentic RAG, GraphRAG, and what it actually takes to ship retrieval to production.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_RAG_Retrieval/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | Embedding Models | in development | Dense vs sparse; bi-encoder vs cross-encoder; modern families (BGE, GTE, E5, Voyage, OpenAI text-embedding-3, Cohere, Nomic, Jina); ColBERT late interaction; Matryoshka; domain adaptation. |
| 02 | Vector Databases | in development | pgvector, Qdrant, Weaviate, LanceDB, Pinecone, Milvus, Chroma; HNSW, IVF, PQ; recall vs latency; updates and durability; decision matrix. |
| 03 | Hybrid Search &amp; Reranking | in development | BM25 mechanics; RRF and weighted fusion; cross-encoder rerankers (BGE-Reranker, Cohere Rerank, mxbai); ColBERT-as-reranker (PLAID); cascades; latency budgets. |
| 04 | Chunking &amp; Ingestion | in development | Strategies (fixed, semantic, structural, contextual); recursive splitting failure modes; layout-aware (Unstructured, MinerU, LlamaParse, Docling); ColPali for vision; deduplication. |
| 05 | Agentic RAG Patterns | in development | HyDE, query decomposition, Self-RAG, Corrective RAG (CRAG), iterative retrieval, query routing, tool-using RAG. |
| 06 | GraphRAG &amp; Knowledge Graphs | in development | Microsoft GraphRAG, KG construction, entity resolution; Neo4j, Memgraph, KuzuDB; hybrid graph+vector retrieval; Cypher in agent loops. |
| 07 | Production RAG | in development | RAGAS, ARES, Trulens; drift &amp; freshness; latency budgets; multi-tenancy and ACLs; citation &amp; grounding; cost; failure modes. |

> <strong>Status:</strong> sub-hub created with roadmap. Leaf decks land progressively over upcoming sessions.

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
