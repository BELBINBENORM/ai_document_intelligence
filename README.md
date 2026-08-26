# AI Document Intelligence & Contract Risk Analyst

End-to-end FastAPI project: document ingestion, chunking, retrieval, RAG, structured risk analysis, PostgreSQL, Docker and tests.

Run: `cp .env.example .env && docker compose up --build` then open `/docs`.

The retrieval service starts with lexical retrieval so the project is runnable. Upgrade it to embeddings + pgvector hybrid search for the production version.
