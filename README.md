# RAG &amp; Retrieval Systems

Embedding models, vector databases, hybrid search and reranking (plus two deep-dive companions on the two-step cascade architecture and the underlying reranker mathematics), chunking, agentic RAG, GraphRAG, and what it actually takes to ship retrieval to production.

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
| 08 | [Two-Step Retrieval &mdash; Architecture &amp; Cost-Quality Mathematics](https://brendanjameslynskey.github.io/RAG_08_Two_Step_Retrieval_Architecture/) | live | Companion deep-dive to deck 03. The bi-encoder / cross-encoder asymmetry; indexability barrier (why MIPS scales and cross-attention doesn&apos;t); ANN math (HNSW, IVF, PQ recall&ndash;latency curves); recall-ceiling theorem; RRF derivation, CombSUM, Z-score; latency composition under tails; the (k, quality, latency) Pareto frontier; Platt / isotonic / temperature calibration; worked example at 10&nbsp;M docs / 200&nbsp;ms. |
| 09 | [Reranker Mathematics](https://brendanjameslynskey.github.io/RAG_09_Reranker_Mathematics/) | live | Stage-2 maths. Cross-encoder attention &amp; the token-interaction story; ColBERT MaxSim formal definition; learning-to-rank families (pointwise / pairwise / listwise); RankNet sigmoid loss and the &ldquo;lambdas&rdquo;; LambdaRank gradient weighted by <code>\|&Delta;NDCG\|</code>; LambdaMART GBDT; InfoNCE contrastive loss with hard negatives; MarginMSE cross-encoder &rarr; bi-encoder distillation; DCG / NDCG / MRR / MAP derivations. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
