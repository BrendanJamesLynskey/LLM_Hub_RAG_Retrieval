# RAG &amp; Retrieval Systems

Embedding models, vector databases, hybrid search and reranking, chunking, agentic RAG, GraphRAG, and what it actually takes to ship retrieval to production.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_RAG_Retrieval/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Embedding Models](https://brendanjameslynskey.github.io/RAG_01_Embedding_Models/) | live | Dense vs sparse; bi-encoder vs cross-encoder; modern families (BGE, GTE, E5, Voyage, OpenAI text-embedding-3, Cohere, Nomic, Jina); ColBERT late interaction; Matryoshka; domain adaptation. |
| 02 | [Vector Databases](https://brendanjameslynskey.github.io/RAG_02_Vector_Databases/) | live | pgvector, Qdrant, Weaviate, LanceDB, Pinecone, Milvus, Chroma; HNSW, IVF, PQ; recall vs latency; updates and durability; decision matrix. |
| 03 | [Hybrid Search &amp; Reranking](https://brendanjameslynskey.github.io/RAG_03_Hybrid_Search_and_Reranking/) | live | BM25 mechanics; RRF and weighted fusion; cross-encoder rerankers (BGE-Reranker, Cohere Rerank, mxbai); ColBERT-as-reranker (PLAID); cascades; latency budgets. |
| 04 | [Chunking &amp; Ingestion](https://brendanjameslynskey.github.io/RAG_04_Chunking_and_Ingestion/) | live | Strategies (fixed, semantic, structural, contextual); recursive splitting failure modes; layout-aware (Unstructured, MinerU, LlamaParse, Docling); ColPali for vision; deduplication. |
| 05 | [Agentic RAG Patterns](https://brendanjameslynskey.github.io/RAG_05_Agentic_RAG_Patterns/) | live | HyDE, query decomposition, Self-RAG, Corrective RAG (CRAG), iterative retrieval, query routing, tool-using RAG. |
| 06 | [GraphRAG &amp; Knowledge Graphs](https://brendanjameslynskey.github.io/RAG_06_GraphRAG_and_KGs/) | live | Microsoft GraphRAG, KG construction, entity resolution; Neo4j, Memgraph, KuzuDB; hybrid graph+vector retrieval; Cypher in agent loops. |
| 07 | [Production RAG](https://brendanjameslynskey.github.io/RAG_07_Production_RAG/) | live | RAGAS, ARES, Trulens; drift &amp; freshness; latency budgets; multi-tenancy and ACLs; citation &amp; grounding; cost; failure modes. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
