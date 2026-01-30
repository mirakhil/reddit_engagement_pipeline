# Reddit Engagement Data Pipeline

End-to-end data engineering pipeline to ingest Reddit data, process it into analytics-ready formats,
and enable downstream analytics and ML use cases.

## Tech Stack
- Reddit API (PRAW)
- Python, Pandas, PySpark
- Parquet (Lake-style storage)
- Snowflake + dbt
- Apache Airflow (Docker)
- GitHub Actions
- Future: RAG layer (FAISS + LLM)

## Architecture (High Level)
Reddit API → Python Ingestion → Parquet → Spark → Snowflake → dbt → Analytics / RAG
